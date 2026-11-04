# Horizon — download

Pianifica progetti sul **Gantt** con dipendenze e percorso critico, segui il carico del team e
l'avanzamento rispetto al piano. Tabella, Kanban, calendario, panoramica e mappa del progetto;
campi personalizzati, baseline, importazione CSV ed esportazione in Excel, PDF e PNG.

L'app per **Windows** e quella per **Android** funzionano da sole, senza account: i dati restano
cifrati sul dispositivo. Per lavorare in gruppo si collegano a un **server Horizon** (o a un computer
Windows in modalità host), anche dopo periodi senza rete.

Gratis, senza pubblicità.

## ⬇️ Scarica

| | Download diretto (ultima versione) | Note |
|---|---|---|
| **Windows** 10 / 11 (64 bit) | **[Horizon-Setup.exe](https://github.com/andrewsVsCodeGIT/Horizon-download/releases/latest/download/Horizon-Setup.exe)** | installer, ~13 MB |
| **Android** 8.0 o successivo | **[Horizon.apk](https://github.com/andrewsVsCodeGIT/Horizon-download/releases/latest/download/Horizon.apk)** | ~75 MB |
| **Server** Windows o Linux (64 bit) | dalla pagina **[Releases](../../releases/latest)** | `horizon-server-<versione>-windows-x64.zip` o `-linux-x64.tar.gz`, ~16 MB |

Note di versione e versioni precedenti: **[Releases](../../releases)**.

Questo repository contiene solo i file da scaricare e la documentazione: il codice sorgente non è pubblico.

## Windows
1. Scarica ed esegui `Horizon-Setup.exe`.
2. L'installer non è firmato digitalmente, quindi Windows può mostrare l'avviso
   **"Windows ha protetto il PC"** (SmartScreen): fai clic su **Ulteriori informazioni → Esegui comunque**.
3. Scegli se installare **solo per te** (senza diritti di amministratore) o **per tutti gli utenti**.
4. All'avvio trovi un'area di lavoro su questo computer, senza account. La chiave che cifra i dati
   è nel Gestore credenziali di Windows.

Per aggiornare esegui il nuovo `Horizon-Setup.exe` sopra la versione installata.

## Android
1. Scarica `Horizon.apk` sul telefono e aprilo (da Download, File o Drive).
2. Android chiede di consentire l'installazione di app da **origini sconosciute** per l'app con cui
   apri il file: consentila.
3. **Google Play Protect** può avvisare che lo sviluppatore non è noto: tocca **Installa comunque**.
4. All'avvio trovi un'area di lavoro sul telefono, senza account, cifrata con una chiave custodita
   dal sistema (Android Keystore).

Il nuovo APK si installa sopra la versione precedente e i dati restano.
⚠️ Disinstallando l'app i dati salvati sul telefono vengono cancellati.

## Lavorare in gruppo: il server
Il server è l'edizione Web: un solo eseguibile con l'interfaccia, l'API e il database, da aprire dal
browser. Non servono Node, database né altri programmi.

1. Scarica dalla pagina [Releases](../../releases/latest) l'archivio per il tuo sistema ed estrailo.
   L'eseguibile `horizon-server` e la cartella `web` devono restare insieme.
2. Avvialo dalla sua cartella (su Windows basta il doppio clic) e apri <http://localhost:8721>:
   crea l'account e la prima organizzazione.
3. I dati vanno nella cartella `horizon-data` accanto all'eseguibile: per un backup copiala a server
   fermo. Per aggiornare, sostituisci `horizon-server` e la cartella `web` e lascia `horizon-data` dov'è.

Per default il server risponde solo su questo computer. Per gli altri dispositivi della rete avvialo
con `--listen 0.0.0.0:8721`. Fuori da `localhost` serve HTTPS, altrimenti gli accessi viaggiano in
chiaro: mettilo dietro un reverse proxy (per esempio Caddy) e avvialo con `--public-url https://…`
e `--trust-proxy`.

**Collegare le app:** nel browser apri Impostazioni › Sicurezza e dispositivi › **Collega un'app
Horizon**; nell'app apri **Questo computer** (o **Questo telefono**) › **Collegati a un host** e scrivi
il codice, oppure inquadra il QR col telefono.

## Documentazione
- [Guida di Horizon](docs/guida-it.md) · [Horizon guide (English)](docs/guide-en.md)
- Licenze dei componenti di terze parti: [librerie Rust](docs/rust-licenses.md),
  [librerie JavaScript](docs/npm-licenses.md), [dati inclusi](docs/data-notices.md)

## Verifica dei file (facoltativa)
Ogni release contiene `SHA256SUMS.txt` con l'impronta **SHA-256** di ogni file. Su Windows puoi
confrontarla con:
```powershell
Get-FileHash .\Horizon-Setup.exe -Algorithm SHA256
```

## English
Horizon plans projects on a Gantt chart with dependencies and the critical path, and tracks team
workload and progress. The Windows and Android apps work on their own, without an account; for
teamwork they connect to a Horizon server. Download the files from the table above; the installer is
not code-signed, so SmartScreen may warn on first run (*More info → Run anyway*). See the
[English guide](docs/guide-en.md).
