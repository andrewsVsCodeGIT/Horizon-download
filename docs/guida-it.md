# Guida di Horizon

Horizon serve a pianificare progetti: attività con date e dipendenze sul Gantt, chi fa cosa, quanto è carico il team e come procede il lavoro rispetto al piano. Funziona dal browser, come app per Windows e come app per Android. Le app lavorano anche da sole e, se vuoi, si collegano a un server o a un computer del team.

## Primi passi

1. **Crea un account:** apri l'indirizzo del server e scegli "Crea un account". Se il server è solo su invito, usa il link ricevuto per e-mail.
   - La password deve avere almeno 10 caratteri: una frase facile da ricordare va benissimo.
   - Sono rifiutate le password molto comuni e quelle che contengono il tuo nome o l'e-mail.
2. **Dai un nome all'organizzazione e al primo progetto.** L'organizzazione raccoglie persone e progetti; puoi averne più di una e passare dall'una all'altra dal menu in alto a sinistra.
3. **Aggiungi le attività** con "Nuova attività", oppure scrivi direttamente nella riga in fondo alla vista.

## Le viste di un progetto

| Vista | A cosa serve |
|---|---|
| **Gantt** | Barre sul calendario, dipendenze, percorso critico, linea di oggi. Trascina una barra per spostarla, il bordo per cambiarne la durata, la maniglia per collegarla a un'altra attività |
| **Tabella** | Tutte le colonne, modifica di più righe insieme |
| **Kanban** | Colonne per stato: spostare una scheda cambia lo stato |
| **Calendario** | Mese, settimana o agenda |
| **Panoramica** | Il progetto in un colpo d'occhio: avanzamento effettivo e previsto nel tempo, attività completate e in ritardo, ore, costi, timeline per sezione e persone |
| **Mappa** | L'albero del progetto (sezioni, attività, sotto-attività) da aprire, chiudere, trascinare e ingrandire |
| **Andamento** | Avanzamento per sezione e confronto con una baseline |

Spostando un'attività con dipendenti, Horizon mostra in anteprima cosa si sposterebbe e chiede conferma. **Ctrl+Z** annulla.

**Tastiera nel Gantt:**

| Tasto | Azione |
|---|---|
| Ctrl+C / Ctrl+V | Copia l'attività, incollala sotto la riga |
| Alt+← / Alt+→ | Sposta l'attività di un giorno |
| Alt+Maiusc+← / → | Cambia la fine |
| L | Collega l'attività alla successiva che scegli |
| T | Vai a oggi |
| + / − | Ingrandisci o riduci la scala |
| Invio | Apri i dettagli |
| Ctrl+Maiusc+→ / ← | Aumenta o riduci il rientro (sotto-attività) |
| Maiusc+F10 o tasto Menu | Menu dell'attività |

Ovunque, **Ctrl+K** apre la ricerca rapida di progetti, attività e comandi.

**Timeline della Panoramica:** mostra tutto l'arco del progetto. **Vista** passa da Compatta (una barra per sezione) a Estesa (ogni sezione con le sue attività); **Colori** sceglie per stato, colore dell'attività o avanzamento; la scala va da settimane ad anni, lo zoom − + allarga il disegno e **Copia negli appunti** lo porta in una mail o in una presentazione come immagine.

**Colonne:** in Gantt e Tabella il pulsante **Colonne** sceglie cosa vedere: numero dell'attività, date, durata, stato, %, persone, ore, priorità, rischio, etichette, dipendenze, costi e campi personalizzati. La scelta vale per il progetto su questo dispositivo e si salva anche nelle viste salvate. Nel Gantt puoi cambiare stato e % cliccandoli direttamente, e trascinare il bordo della colonna delle attività per allargarla.

**Esporta e condividi:** il pulsante accanto a «Nuova attività» crea un'immagine o un PDF, un foglio Excel o un CSV, oppure un link di sola lettura.

**Densità:** sui computer Horizon usa un'interfaccia **compatta** (testo più piccolo, righe più basse) per mostrare più piano in una schermata. Se preferisci più spazio scegli **Comoda** dal menu dell'utente, dalla ricerca rapida o da Impostazioni › Profilo. Nel Gantt, **Adatta al progetto** sceglie lo zoom che mostra tutto il progetto.

## Attività

Ogni attività ha:
- sezione, date, durata in giorni lavorativi e stato;
- priorità, avanzamento, stima in ore;
- etichette, assegnatari con percentuale e vincoli;
- per le milestone, una sola data.

Nel pannello dei dettagli trovi anche commenti, allegati e cronologia delle modifiche.

- **Dipendenze:** fine→inizio, inizio→inizio, fine→fine, inizio→fine, con ritardo o anticipo in giorni.
- **Calendari:** i giorni lavorativi vengono dal calendario del progetto; le assenze delle persone (Impostazioni › Assenze) contano per il carico di lavoro.

### Sotto-attività e livelli

Sotto ogni sezione puoi costruire un elenco a più livelli: un'attività con sotto-attività, che hanno a loro volta sotto-attività, fino a **10 livelli**.

- **Menu dell'attività:** tasto destro sulla riga (Gantt, Tabella) o sulla scheda (Mappa), il pulsante ⋯ o ⋮, oppure Maiusc+F10. Contiene: apri i dettagli, nuova attività allo stesso livello, nuova sotto-attività, aumenta rientro, riduci rientro. Se una voce non si può usare, resta spenta e dice perché.
- **Aumenta rientro** (Ctrl+Maiusc+→): l'attività va sotto quella che la precede allo stesso livello.
- **Riduci rientro** (Ctrl+Maiusc+←): l'attività sale di un livello e si mette subito dopo l'attività che la conteneva.
- **Ctrl+Z** annulla anche questi spostamenti.
- Un'attività con sotto-attività è un **riepilogo**: date, avanzamento e ore impiegate vengono dalle sotto-attività. Le sotto-attività hanno la sezione della loro attività di primo livello.
- Una milestone non può avere sotto-attività. In Tabella i livelli si cambiano solo con l'ordine del piano (senza ordinamenti per colonna).

### Copiare e incollare attività

Dal menu dell'attività scegli **Copia** (o **Ctrl+C**), poi su un'altra riga **Incolla sotto** (o **Ctrl+V**). In Tabella si copiano le righe selezionate con le caselle.

- Una riga copiata porta con sé le sue sotto-attività; si può incollare anche in un altro progetto della stessa organizzazione.
- Le copie tengono date, stima, persone, etichette e i collegamenti fra loro, e ripartono da «Da fare» e 0 %, senza ore impiegate.
- **Ctrl+Z** toglie tutto quello che hai incollato.

### Campi personalizzati

Ogni progetto può avere campi suoi: **Colonne › Gestisci campi personalizzati** (o menu ⋯ del progetto), per chi gestisce il progetto.

| Tipo | Esempio |
|---|---|
| Elenco a scelta, con colori | Impresa |
| Testo | Numero d'ordine |
| Numero decimale o intero | Metri quadri |
| Valuta (quella del progetto) | Budget |
| Percentuale | Sconto |
| Casella | Verificata |

- Si compilano nel pannello dell'attività, nella Tabella e, se scegli la colonna, nel Gantt. Finiscono in CSV ed Excel.
- Eliminando un campo o un'opzione si perdono i valori: Horizon dice prima quante attività ne hanno uno.
- **Copia i campi da un altro progetto** porta le definizioni, senza i valori.
- I link di sola lettura non li mostrano.

## Lavorare insieme

- **Commenti e menzioni:** scrivi `@` e il nome. La persona riceve una notifica nella **Inbox**, per e-mail o push se le ha attivate (Impostazioni › Notifiche).
- **Presenza:** vedi chi sta guardando lo stesso progetto. Le modifiche degli altri compaiono senza ricaricare la pagina.
- **Link di sola lettura:** dal menu ⋯ del progetto, con scadenza e revoca.
- **Allegati:** trascina i file nel pannello di un'attività. Si scaricano sempre come file; se il server ha l'antivirus, un file infetto viene rifiutato.

## Pianificare meglio

- **Carico di lavoro:** ore assegnate per persona e per giorno, rispetto alla capacità; i sovraccarichi sono evidenziati. Horizon non riassegna mai nulla da solo.
- **Baseline:** fotografie del piano (menu ⋯ › Baseline…), da confrontare sul Gantt, in tabella e nell'andamento.
- **Modelli:** salva un progetto come modello e ripartì da lì; ci sono anche modelli pronti.
- **Viste salvate:** filtri, ordinamenti e colonne, per te o per tutti.
- **Importare:** menu ⋯ › Importa da CSV:
  1. carichi il file e scegli le colonne;
  2. controlli l'anteprima riga per riga;
  3. importi.

  Ogni importazione si può annullare dalla Cronologia.
- **Esportare:** CSV, Excel, PDF o immagine PNG del Gantt, con l'intervallo e le colonne che scegli.
- **Ore impiegate e costi:** nel pannello di un'attività scrivi le **ore impiegate** (a quarti d'ora). Dal menu ⋯ del progetto › **Costi e tariffe** scegli la valuta e la tariffa oraria di ogni persona. La Panoramica calcola:
  - costo stimato = ore stimate × tariffa;
  - costo attuale = ore impiegate × tariffa.

  Le ore di un'attività con più assegnatari si dividono secondo la percentuale di ciascuno; quelle senza assegnatari o di persone senza tariffa sono indicate a parte. Le tariffe le vedono solo Owner, Admin e chi gestisce il progetto, e non finiscono in esportazioni, file né link condivisi.
- **Panoramica:** la linea "Effettivo" si registra giorno per giorno da quando il progetto esiste nella versione 1.1; prima è tratteggiata.

## Assistente AI

Se l'organizzazione lo ha attivato, dal menu ⋯ del progetto scegli **Assistente AI…**:
1. descrivi il lavoro (un elenco di attività, una per riga, funziona meglio);
2. Horizon propone sezioni, attività, durate e dipendenze;
3. correggi, togli righe, cambia le date di inizio;
4. premi **Applica**.

**Finché non applichi, nel progetto non cambia nulla.** Una proposta applicata si annulla come un'importazione. Le regole offline non inviano dati da nessuna parte; un modello esterno (per esempio Claude) riceve solo il testo che scrivi.

## Integrazioni

In Impostazioni › Integrazioni (Owner e Admin) colleghi un progetto a uno strumento di issue:
- le issue nuove diventano attività;
- titolo, stato ed etichette restano allineati, anche nei due sensi se lo scegli;
- se entrambe le parti cambiano, Horizon registra un conflitto e ti chiede quale tenere.

C'è un "Sandbox Tracker" per provare senza account esterni; GitHub Issues richiede una OAuth App configurata da chi gestisce il server.

## Sicurezza del tuo account

**Impostazioni › Sicurezza e dispositivi:**
- **Cambia password:** gli altri dispositivi vengono disconnessi.
- **Verifica in due passaggi:** consigliata, e obbligatoria se la tua organizzazione o il server la richiedono.
  1. Installa un'app di autenticazione: Aegis o FreeOTP, gratuite e libere, oppure Google o Microsoft Authenticator.
  2. Premi **Attiva…**, conferma la password e inquadra il codice QR.
  3. Scrivi il codice di 6 cifre.
  4. **Conserva i 10 codici di recupero**, per esempio nel tuo gestore di password. Ognuno vale una volta se perdi il telefono.

  All'accesso, dopo la password, Horizon chiede il codice dell'app.
- **Dispositivi:** l'elenco dei browser e delle app con cui sei entrato; puoi disconnetterli uno per uno o tutti.
- **Inattività:** se non usi Horizon da un browser per 14 giorni, ti verrà chiesto di accedere di nuovo.

Se hai perso telefono e codici di recupero, chiedi a chi gestisce il server: dopo aver verificato chi sei, potrà disattivare la verifica in due passaggi per farti entrare.

## Le app per Windows e Android

- **Da sole:** all'avvio hai un'area di lavoro su questo computer o telefono, senza account e cifrata, con chiave nel sistema.
- **Collegate:** nel browser del server (o del computer host) apri Impostazioni › Sicurezza e dispositivi › **Collega un'app Horizon**: compaiono un codice e un QR. Nell'app apri **Questo computer** (o **Questo telefono**) › **Collegati a un host** e scrivi il codice, oppure inquadra il QR col telefono.
- **Senza rete:** le modifiche restano in coda e partono appena torna la connessione. Se nel frattempo qualcuno ha cambiato lo stesso campo, scegli tu quale valore tenere.
- **Modalità host (Windows):** il computer fa da server per la rete locale, per esempio un piccolo ufficio senza server.

**Uscendo dal browser** (menu dell'utente › Esci): se ci sono modifiche non ancora inviate, Horizon te lo dice prima di cancellarle da quel browser.

## Ruoli

| Ruolo | Cosa può fare |
|---|---|
| Owner | Tutto, compresa l'organizzazione e i suoi Owner |
| Admin | Persone, workspace, integrazioni, impostazioni dell'organizzazione |
| Project Manager | I propri progetti: impostazioni, membri, baseline, link, importazioni, tariffe e costi |
| Member | Attività, dipendenze, commenti, esportazioni |
| Viewer | Solo lettura (commenti se il progetto li consente) |
