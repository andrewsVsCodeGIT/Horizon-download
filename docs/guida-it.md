# Guida di Horizon

Horizon serve a pianificare progetti: attività con date e dipendenze sul Gantt, chi fa cosa, quanto è carico il team e come procede il lavoro rispetto al piano. Funziona dal browser, come app per Windows e come app per Android. Le app lavorano anche da sole e, se vuoi, si collegano a un server o a un computer del team.

## Primi passi

1. **Crea un account:** apri l'indirizzo del server e scegli "Crea un account". Se il server è solo su invito, usa il link ricevuto per e-mail.
   - La password deve avere almeno 10 caratteri: una frase facile da ricordare va benissimo.
   - Sono rifiutate le password molto comuni e quelle che contengono il tuo nome o l'e-mail.
2. **Dai un nome all'organizzazione e al primo progetto.** L'organizzazione raccoglie persone e progetti; puoi averne più di una e passare dall'una all'altra dal menu in alto a sinistra.
3. **Aggiungi le attività** con "Nuova attività", oppure scrivi direttamente nella riga in fondo alla vista.

Per guardarti intorno prima di partire, **Prova con un progetto d'esempio** (all'inizio, o «Apri un progetto d'esempio» in Home) crea un progetto già pieno, con alcune attività assegnate a te. In Home la lista **Primi passi** ti accompagna in cinque passi (crea un progetto, aggiungi tre attività, collegane due, assegnane una, invita un collega) che si spuntano da soli; **Nascondi** la toglie.

**Home a modo tuo:** **Personalizza** sceglie che cosa vedere in Home e in che ordine: Primi passi, Numeri, Prossime attività, Milestone in arrivo, Le mie attività in ritardo, Stato dei progetti, Progetti attivi. La scelta vale su questo dispositivo.

## Le viste di un progetto

| Vista | A cosa serve |
|---|---|
| **Gantt** | Barre sul calendario, dipendenze, percorso critico, linea di oggi. Trascina una barra per spostarla, il bordo per cambiarne la durata, la maniglia per collegarla a un'altra attività |
| **Tabella** | Tutte le colonne, modifica di più righe insieme; si scrive come in un foglio di calcolo |
| **Kanban** | Colonne per stato: spostare una scheda cambia lo stato |
| **Calendario** | Mese, settimana o agenda. Trascina un'attività su un altro giorno (o Alt+frecce); un doppio clic su un giorno ne crea una |
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
| M / Maiusc+M | Milestone successiva / precedente |
| R / Maiusc+R | Prossima attività in ritardo / precedente |
| Canc | Elimina l'attività (Ctrl+Z la rimette) |
| + / − | Ingrandisci o riduci la scala |
| Invio | Apri i dettagli |
| Spazio | Completa l'attività, o togli la spunta |
| F2 | Rinomina sul posto (Invio conferma, Esc annulla) |
| Ctrl+Invio | Nuova attività sotto, da scrivere sul posto |
| Alt+↑ / Alt+↓ | Sposta l'attività su o giù tra quelle del suo livello |
| Ctrl+Maiusc+→ / ← | Aumenta o riduci il rientro (sotto-attività) |
| Maiusc+F10 o tasto Menu | Menu dell'attività |
| Ctrl+clic / Maiusc+clic | Aggiungi alla selezione / seleziona fino a qui |
| Maiusc+↑ / Maiusc+↓ | Allarga la selezione |
| Ctrl+Spazio / Ctrl+A | Seleziona o lascia la riga / seleziona tutto |

Ovunque, **Ctrl+K** apre la ricerca rapida di progetti, attività e comandi, e **?** l'elenco di tutte le scorciatoie, con quelle della vista aperta per prime. I suggerimenti dei pulsanti mostrano il tasto, per esempio «Vai a oggi (T)».

**Timeline della Panoramica:** mostra tutto l'arco del progetto. **Vista** passa da Compatta (una barra per sezione) a Estesa (ogni sezione con le sue attività); **Colori** sceglie per stato, colore dell'attività o avanzamento; la scala va da settimane ad anni, lo zoom − + allarga il disegno e **Copia negli appunti** lo porta in una mail o in una presentazione come immagine.

**Colonne:** in Gantt e Tabella il pulsante **Colonne** sceglie cosa vedere: WBS (numero gerarchico, 1.2.3), date, durata, stato, %, persone, ore, priorità, rischio, etichette, dipendenze, costi e campi personalizzati. La scelta vale per il progetto su questo dispositivo e si salva anche nelle viste salvate. Nel Gantt puoi cambiare stato e % cliccandoli direttamente.

**Spunta di completamento (Gantt):** il cerchio prima del nome diventa verde quando l'attività è al 100%. Un clic sul cerchio, o Spazio sulla riga, la completa: stato «Completata» e 100%. Togliendo la spunta l'attività torna a 0% e, se era completata, a «Da fare». Le attività riepilogative hanno un cerchio tratteggiato, che diventa verde quando tutte le sotto-attività sono finite: si completa spuntando quelle.

**Stato e percentuale vanno insieme:** in Gantt, Tabella, Kanban e nei dettagli, portare la percentuale a 100% rende l'attività «Completata»; abbassarla riapre un'attività completata («In corso», o «Da fare» se scende a 0%). Cambiando lo stato da «Completata» a un altro, la percentuale riparte da 0%.

**Numeri delle attività:** a sinistra del nome, nel Gantt e nella Tabella, ogni attività ha un numero progressivo (1, 2, 3…) lungo tutto il piano, sezioni escluse. Chiudere un ramo o filtrare non rinumera: i numeri nascosti si saltano. La colonna Dipendenze usa gli stessi numeri («3», «5FS+2»).

**Scrivere nel Gantt:**
- **F2**, o «Rinomina» nel menu dell'attività, trasforma il nome in un campo: Invio conferma, Esc annulla.
- **Ctrl+Invio** su una riga apre sotto una riga nuova, allo stesso livello: scrivi il nome e premi Invio, e se ne apre un'altra per continuare; Esc smette.
- In fondo a ogni sezione aperta c'è **+ Nuova attività**.
- **Le sezioni** hanno il loro menu (tasto destro sulla riga della sezione, o Maiusc+F10): nuova attività nella sezione, **Rinomina** (anche con F2) ed **Elimina la sezione**. Eliminandola, Horizon chiede conferma e dice quante attività contiene: restano nel progetto, senza sezione. Eliminare una sezione lo può fare chi può eliminare le attività di tutti (Owner, Admin, Project manager).
- Dopo il nome puoi scrivere inizio e durata, separati da una barra: «Collaudo | ven 5g».

**Riordinare:** trascina il **numero** di una riga e lasciala prima o dopo un'altra (parte alta o bassa della riga) o dentro (al centro), dove diventa sua sotto-attività. Dove non si può la linea diventa rossa e dice perché. Da tastiera **Alt+↑/↓**; nel menu dell'attività **Sposta su** e **Sposta giù**. **Ctrl+Z** annulla.

**Scheda sulla barra:** passando sopra una barra, o arrivandoci con la tastiera, compaiono date e giorni lavorativi, stato e %, persone, predecessori, margine (quanto può slittare senza spostare la fine del progetto) e lo scostamento dalla baseline confrontata. Esc la chiude.

**Barra del Gantt:** i pulsanti sono a gruppi (Oggi e Adatta; Espandi e Comprimi), con il nome accanto all'icona quando c'è spazio. Percorso critico e minimappa si accendono dal menu **Mostra**. Con il focus su un pulsante, ←/→ passano agli altri.

**Date a parole:** nei dettagli, nella nuova attività e nelle celle della Tabella puoi scrivere le date come le diresti:
- date: «15/12», «15 dic», «2026-12-15»;
- parole: «oggi», «domani», «fine mese»;
- giorni della settimana: «ven», «lunedì» (il prossimo);
- spostamenti: «+3g», «+2s», «+1m», «+5gl» (giorni lavorativi), «fra 2 settimane».

Nella fine vale anche una durata, «5g» o «2s» (10 giorni lavorativi). Sotto il campo leggi cosa ha capito; Esc torna al valore di prima, l'icona del calendario apre il selettore. La **durata** nei dettagli si modifica e sposta la fine.

**Dettagli accanto alla vista:** su schermi da 1200 px in su i dettagli di un'attività si aprono a destra e la vista resta usabile: un clic su un'altra attività la apre al posto della prima. ‹ › o **Alt+↑/↓** passano all'attività precedente o successiva, nell'ordine della vista; **Esc** chiude e riporta dove eri; **F6** passa tra vista e dettagli.

**Annulla e Ripristina:** i due pulsanti in alto a destra del progetto, o **Ctrl+Z** e **Ctrl+Y** (Ctrl+Maiusc+Z), tornano indietro e avanti di una modifica alla volta: date e spostamenti (con le attività che si erano spostate insieme), nomi, stato e campi, persone, collegamenti con il loro tipo e ritardo, ripetizioni, sezioni (nuove, rinominate, eliminate) e modifiche a più attività insieme. Sul pulsante leggi a cosa si riferisce il passo successivo. La cronologia vale per la scheda del browser e per il progetto; ricaricando la pagina riparte vuota.

**Eliminare si annulla:** dopo un'eliminazione il messaggio ha **Annulla**, e anche **Ctrl+Z** rimette l'attività con le sotto-attività, i collegamenti e le persone. Vale anche senza rete, finché l'eliminazione aspetta di partire. Horizon chiede conferma solo per eliminazioni grandi: più di 10 attività in una volta, o un'attività con più di 10 sotto-attività.

**Selezione multipla:** nel Gantt e nel Kanban scegli più attività con Ctrl+clic o Maiusc+clic, con Maiusc+↑/↓, oppure trascinando un rettangolo sulla parte vuota del diagramma. In Tabella usa le caselle. Compare una barra con stato, persone, priorità, sezione, **Sposta…** (di N giorni lavorativi, in avanti o indietro), duplica ed elimina, che valgono per tutte insieme; **Deseleziona** chiude. Trascinando una barra selezionata si spostano anche le altre. Ctrl+Z annulla in un passo.

**Perché questa data?** Nei dettagli di un'attività, e nella scheda della barra alla riga «Perché qui», Horizon dice cosa la tiene dov'è: l'attività che aspetta (con l'attesa e i giorni non lavorativi in mezzo), un vincolo, la data scelta o l'inizio del progetto. Accanto c'è il rimedio a un clic: **Togli il legame**, **Togli il vincolo** o **Anticipa al…**. Nel Gantt la catena che la trattiene si illumina.

**Incolla un elenco:** copia un elenco da un documento, una mail o un foglio di calcolo e premi **Ctrl+V** nel Gantt o nella Tabella (oppure menu ⋯ del progetto › **Incolla un elenco…**). Ogni riga diventa un'attività; rientri ed elenchi numerati diventano sotto-attività; le colonne di un foglio di calcolo con le intestazioni diventano i campi. Valgono anche @persona, #etichetta, !priorità e, dopo una barra, data e durata («Rilievi @Giulia | 16/11 3g»). Prima vedi l'anteprima ad albero; Ctrl+Z toglie tutto.

**Apri come progetto:** dal menu di un'attività con sotto-attività, **Apri come progetto** mostra solo quel ramo, come se fosse un progetto a sé. Una riga in cima lo ricorda; **Tutto il progetto** torna indietro.

**Riprendi da dove eri:** riaprendo un progetto torni all'ultima vista che usavi su questo dispositivo, e il Gantt allo stesso giorno e alla stessa riga. I link a un'attività (Inbox, e-mail) portano sempre all'attività.

**Sul telefono:** l'intestazione si riduce al nome mentre scorri il piano e torna intera in cima; «Fine prevista» e margine sono nel «+» del riepilogo. Le schede delle viste hanno il nome e scorrono di lato. Ricerca e filtri stanno su una riga, con «Solo mie», le baseline e le viste nel menu «⋯». In basso a destra c'è un «+» per creare un'attività, e i menu salgono dal basso, con righe più alte.

**Larghezza dell'elenco:** il bordo destro dell'elenco delle attività si trascina. Più stretto, l'elenco scorre di lato da solo (con la sua barra, o con la rotella sopra l'elenco); più largo, ricompaiono le colonne nascoste e poi si allarga il nome. Trascinato tutto a sinistra, l'elenco si chiude; il pulsante sul bordo lo riapre. Da tastiera, con il focus sul bordo: ←/→; Invio o un doppio clic lo adattano alle colonne.

**Trascinare una barra:** mentre la sposti, accanto alla barra leggi le date nuove, i giorni lavorativi e quante attività si spostano con lei. **Blocca le barre**, nella barra del Gantt, impedisce i trascinamenti (utile in riunione o sul tablet): le date si cambiano dai dettagli.

**Accanto alle barre:** dal menu **Mostra** scegli cosa leggere dopo ogni barra: persone, avanzamento, date, margine. PDF e immagini seguono la stessa scelta. **Copia immagine** mette negli appunti la parte del Gantt che vedi, con i filtri, pronta da incollare in un'e-mail o in una chat.

**Ripianifica:** dal menu ⋯ del progetto, o dal pulsante accanto allo stato quando ci sono attività in ritardo. Le attività in ritardo ripartono da oggi (quelle avviate tengono l'inizio e finiscono dopo il lavoro che resta), oppure tutte quelle non completate si spostano di qualche giorno lavorativo. Prima di confermare vedi le date nuove, le attività che si spostano con loro e la nuova fine; Ctrl+Z annulla tutto in un passo.

**Dalla tua ultima visita:** riaprendo un progetto, una riga in cima dice quante modifiche hanno fatto gli altri, chi, e su quante attività. Le righe cambiate hanno un punto sul numero; **Mostra solo queste** le filtra, **Segna come viste** toglie tutto.

**Tabella come un foglio di calcolo:** le frecce passano da una cella all'altra (dove non cambiano il valore), Invio scende di una riga e Maiusc+Invio sale. Nella colonna **Predecessori** scrivi i numeri delle attività da aspettare, con tipo e attesa se servono: «3, 5SS+2».

**Tabella:** ogni intestazione ha un menu per ordinare, mostrare solo alcuni valori (stato, priorità, sezione, persone, etichette; sulla fine «Solo in ritardo»), adattare la larghezza o nascondere la colonna.

**Larghezza delle colonne (Gantt):** ogni colonna dell'elenco ha una maniglia sul bordo destro dell'intestazione. Trascinala, oppure portaci il focus con Tab e usa ←/→. Il doppio clic, o Invio, adatta la colonna al suo contenuto. Le larghezze valgono su questo dispositivo; **Colonne › Ripristina predefinite** le riporta come all'inizio.

**Testi lunghi:** un nome o un valore troppo lungo per la sua colonna finisce con «…». Passandoci sopra col mouse, o arrivandoci con la tastiera, compare per intero; Esc lo chiude.

**Chiudere l'elenco delle attività:** il pulsante rotondo ‹ sul bordo dell'elenco lo chiude e lascia tutta la larghezza al diagramma; › lo riapre. C'è anche nella ricerca rapida (Ctrl+K, «Gantt: chiudi o apri l'elenco delle attività») e Horizon lo ricorda. A elenco chiuso la tastiera continua a funzionare: il nome della riga selezionata compare sopra il diagramma.

**Minimappa:** il pulsante con la mappa nella barra del Gantt mostra in basso a destra l'intero diagramma in piccolo, con un riquadro sulla parte visibile. Clicca o trascina per spostarti; con il focus sulla minimappa usa le frecce, Inizio e Fine. Si chiude con × e non serve, quindi non compare, quando il diagramma è già tutto visibile.

**Oggi:** una linea rossa segna la data di oggi, con l'etichetta «Oggi» nella scala (zoom Giorno e Settimana). Il pulsante con il mirino o il tasto T ci portano la vista.

**Riepilogo del progetto:** sotto il nome del progetto trovi lo stato, la data di inizio, il responsabile, la priorità e il rischio. Lo stato si calcola dal piano:
- **In ritardo:** la fine prevista supera la scadenza del progetto;
- **A rischio:** ci sono attività non completate con la fine già passata;
- **In linea:** altrimenti;
- se il progetto è in pausa, completato o archiviato, si vede quello.

Priorità e rischio si scelgono nelle impostazioni del progetto: con il permesso di modificarlo basta cliccare una voce del riepilogo.

**Esporta e condividi:** il pulsante accanto a «Nuova attività» crea un'immagine o un PDF, un foglio Excel o un CSV, oppure un link di sola lettura.

**Vedere meglio:** in Impostazioni › Aspetto e lingua, **Dimensione del testo** (Normale, Grande, Molto grande) ingrandisce tutto; **Contrasto più alto** scurisce i testi secondari e rende più visibili bordi e selezione; **Trame sulle barre del Gantt** tratteggia le attività in ritardo e puntina quelle critiche, così non serve distinguere i colori.

**Densità:** sui computer Horizon usa un'interfaccia **compatta** (testo più piccolo, righe più basse) per mostrare più piano in una schermata. Se preferisci più spazio scegli **Comoda** dal menu dell'utente, dalla ricerca rapida o da Impostazioni › Profilo. Nel Gantt, **Adatta al progetto** sceglie lo zoom che mostra tutto il progetto.

## Attività

Ogni attività ha:
- sezione, date, durata in giorni lavorativi e stato;
- priorità, avanzamento, stima in ore;
- etichette, assegnatari con percentuale e vincoli;
- per le milestone, una sola data.

Nel pannello dei dettagli trovi in cima quello che si cambia più spesso (stato, priorità, date, avanzamento, persone, descrizione); il resto sta in gruppi che apri e chiudi e che restano come li lasci (Collegamenti e sotto-attività, Pianificazione, Ore e costi, Etichette e colore). Sotto il titolo leggi com'è andata l'ultima modifica: «salvato», «in coda» senza rete, o «non salvato». Più in basso, commenti, allegati e cronologia.

**Menu dell'attività** (clic destro, Maiusc+F10, o pressione lunga): Stato, Assegna (con «A me»), Priorità, Duplica, Copia link, Converti in milestone o in attività, Segui ed Elimina, oltre a rientri e spostamenti. **Canc** elimina l'attività selezionata nel Gantt, in Tabella, nel Kanban e nella Mappa; Ctrl+Z la rimette.

**Scrittura rapida:** nel nome di un'attività nuova (riga nel Gantt, riga rapida della Tabella, «Nuova attività») «@Giulia» la assegna, «#impianti» aggiunge l'etichetta e «!alta» la priorità; mentre scrivi compaiono i suggerimenti. Con i filtri attivi l'attività prende i loro valori, così resta in vista.

**Attività che si ripetono:** nei dettagli, **Ripeti** sceglie ogni giorno, ogni giorno lavorativo, ogni settimana, ogni 2 settimane, ogni mese o ogni anno, oppure una regola a parole: «ogni 2 settimane lun e gio», «ogni mese dopo il completamento». Quando completi l'attività nasce la prossima, con le stesse persone ed etichette; con «Conta dal giorno in cui è completata» la data parte da lì. Si ripetono le attività senza sotto-attività.

**Approvazioni:** nei dettagli, **Approvazioni › Chiedi di approvare a…** manda la richiesta a una persona del progetto (anche a un ospite), per l'attività o per un allegato, con una nota. La persona la trova nella Inbox e risponde una volta sola, **Approva** o **Non approvare**, con un commento se vuole; chi l'ha chiesta riceve la risposta. Finché è in attesa, la richiesta si può ritirare.

**Conflitti:** se un'attività ha le date bloccate ma i collegamenti vorrebbero farla iniziare più tardi, i dettagli lo dicono e propongono di spostarla, di sbloccare le date o di ridurre il ritardo del collegamento.

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

- **Commenti e menzioni:** scrivi `@` e il nome. La persona riceve una notifica nella **Inbox**, per e-mail o push se le ha attivate (Impostazioni › Notifiche). Con `#` citi un'altra attività, per numero o per nome: nel commento diventa un collegamento.
- **Seguire un'attività:** i commenti arrivano a chi l'ha creata, a chi è assegnato e a chi ha commentato. Con **Segui** (nei dettagli o nel menu dell'attività) li ricevi anche tu; puoi anche smettere. Accanto vedi chi la segue.
- **Inbox raggruppata:** le notifiche dello stesso giorno sulla stessa attività stanno in una riga sola; le altre si aprono con un clic.
- **Ore di silenzio:** in Impostazioni › Notifiche scegli le ore senza e-mail né notifiche push (per esempio dalle 20 alle 8). Nell'Inbox arriva comunque tutto.
- **Silenziare un progetto:** menu ⋯ del progetto › **Silenzia le notifiche**: da quel progetto arrivano solo menzioni, assegnazioni e approvazioni, e solo nell'Inbox.
- **Inbox:** da ogni notifica rispondi al commento, completi l'attività, la **posticipi** (torna non letta più tardi: fra tre ore, domani mattina, lunedì, tra una settimana) o la metti in **Fatto**, che la toglie dall'Inbox (la ritrovi nella scheda Fatto). J/K per spostarti, E per Fatto; sul telefono scorri a destra per Fatto, a sinistra per domani.
- **Presenza:** vedi chi sta guardando lo stesso progetto. Le modifiche degli altri compaiono senza ricaricare la pagina.
- **Link di sola lettura:** dal menu ⋯ del progetto, con scadenza e revoca. Chi lo apre vede anche l'ultimo stato del progetto.
- **Stato del progetto:** nella Panoramica, **Aggiorna lo stato** pubblica un semaforo (In linea, A rischio, Fuori strada) e qualche riga su cosa succede. Gli aggiornamenti restano nello storico e compaiono in Home, nel link di sola lettura e nel rapporto settimanale.
- **Rapporto settimanale:** in Impostazioni › Notifiche, **Rapporto settimanale** ti manda ogni lunedì mattina un'e-mail con le tue attività della settimana, quelle in ritardo, le prossime milestone e lo stato dei progetti.
- **Preferiti e recenti:** la stella accanto al nome di un progetto o di un'attività lo mette tra i **Preferiti**, nella barra laterale. Sotto ci sono i **Recenti**. In Ctrl+K preferiti e recenti vengono per primi. Valgono su questo dispositivo.
- **Cerca in tutta l'organizzazione:** **Cerca** nella barra laterale, o in Ctrl+K «In tutta l'organizzazione», trova attività, descrizioni, commenti, nomi degli allegati e progetti. Bastano gli inizi delle parole e non contano maiuscole e accenti («rilie pian»). I filtri scelgono cosa cercare, il progetto e «Solo attività aperte».
- **Moduli di richiesta:** menu ⋯ del progetto › **Moduli di richiesta…** crea un link pubblico con cui chiunque, anche senza account, chiede un lavoro: titolo, dettagli, nome, e-mail ed eventualmente una data. Ogni richiesta diventa un'attività nella sezione che scegli e i responsabili del progetto la trovano nella Inbox. Un modulo si spegne o si elimina quando vuoi.
- **Ospiti:** per clienti, fornitori e consulenti esterni invita la persona con il ruolo **Ospite** e aggiungila ai progetti che deve vedere. Legge e commenta (se il progetto lo consente), risponde alle approvazioni, ma non vede le altre persone dell'organizzazione né i loro carichi e non esporta.
- **Allegati:** trascina i file nel pannello di un'attività. Si scaricano sempre come file; se il server ha l'antivirus, un file infetto viene rifiutato.

## Pianificare meglio

- **Carico di lavoro:** ore assegnate per persona e per giorno, rispetto alla capacità; i sovraccarichi sono evidenziati. Horizon non riassegna mai nulla da solo, ma dal dettaglio di una cella puoi dare un'attività a un'altra persona (vedi il suo carico prima e dopo) o spostarla di qualche giorno, con Annulla.
- **Baseline:** fotografie del piano (menu ⋯ › Baseline…), da confrontare sul Gantt, in tabella e nell'andamento.
- **Modelli:** salva un progetto come modello e ripartì da lì; ci sono anche modelli pronti.
- **Viste salvate:** filtri, ordinamenti e colonne, per te o per tutti.
- **Importare:** menu ⋯ › Importa da CSV:
  1. carichi il file e scegli le colonne;
  2. controlli l'anteprima riga per riga;
  3. importi.

  Ogni importazione si può annullare dalla Cronologia.
- **Esportare:** CSV, Excel, PDF o immagine PNG del Gantt, con l'intervallo e le colonne che scegli. Nel PDF e nell'immagine il nome di ogni attività è accanto alla sua barra.
- **Ore impiegate e costi:** nel pannello di un'attività scrivi le **ore impiegate** (a quarti d'ora). Dal menu ⋯ del progetto › **Costi e tariffe** scegli la valuta e la tariffa oraria di ogni persona. La Panoramica calcola:
  - costo stimato = ore stimate × tariffa;
  - costo attuale = ore impiegate × tariffa.

  Le ore di un'attività con più assegnatari si dividono secondo la percentuale di ciascuno; quelle senza assegnatari o di persone senza tariffa sono indicate a parte. Le tariffe le vedono solo Owner, Admin e chi gestisce il progetto, e non finiscono in esportazioni, file né link condivisi.
- **Panoramica:** la linea "Effettivo" si registra giorno per giorno da quando il progetto esiste nella versione 1.1; prima è tratteggiata.
- **Previsione:** nella Panoramica, **Quando finirà** simula il progetto molte volte, facendo durare ogni attività aperta un po' meno o un po' di più secondo il suo rischio. Ne escono tre date: **Probabile (50%)**, **Prudente (80%)** e **Quasi certo (95%)**, con la probabilità di finire entro la fine pianificata e la scadenza.
- **Valore acquisito:** accanto, l'indice di tempo (SPI) e quello di costo (CPI, o di impegno in ore senza tariffe) e il costo previsto a fine progetto. 1 vuol dire in linea; sotto 1, indietro o oltre il budget.
- **Scenari «E se…»:** nella barra del Gantt, **E se…** apre uno scenario: sposti le barre e cambi le date, ma nel piano non cambia nulla. Le barre reali restano come fantasmi e la barra dello scenario dice di quanto cambia la fine del progetto. **Applica** salva tutte le modifiche in un passo (Ctrl+Z annulla); **Scarta** le butta via.
- **Livella:** sempre nella barra del Gantt, **Livella** ritarda le attività non ancora iniziate finché nessuno è oltre il 100% delle sue ore, e mostra il risultato come uno scenario da controllare prima di applicarlo. Le attività iniziate, completate o bloccate non si spostano.
- **Portfolio:** **Portfolio** nella barra laterale mostra tutti i progetti che puoi vedere su una linea del tempo, con avanzamento, attività in ritardo, traguardi e legami tra progetti.
- **Legami tra progetti:** nei dettagli di un'attività, **Altri progetti › Aspetta un'attività di un altro progetto…** la fa aspettare un'attività di un altro progetto. Quando quella si sposta, si spostano anche le attività che la aspettano, di progetto in progetto. I giri tra progetti sono rifiutati. Nel Gantt la scheda della barra dice chi aspetta.
- **XML di progetto:** nell'esportazione scegli **XML di progetto**, il formato di interscambio letto dagli altri programmi di pianificazione: struttura, date, legami con tipo e attesa, persone e calendario. **Importa da CSV** accetta anche un file XML di progetto e ti dice prima cosa non si porta dietro.
- **Calendario nelle tue app:** in Impostazioni › Notifiche, **Calendario nelle tue app** crea un indirizzo `.ics` delle tue attività o di un progetto. Aggiungilo al calendario del telefono o del computer («Aggiungi calendario da URL») e le attività si aggiornano da sole. Chi ha l'indirizzo vede quelle attività: se lo perdi, revocalo.
- **Festività da un file:** in Impostazioni › Calendari lavorativi, **Importa da .ics** aggiunge le festività di un calendario scaricato (per esempio quello nazionale); poi salva.
- **Cestino:** progetti e attività eliminati restano per 30 giorni in Impostazioni › **Cestino**. **Ripristina** li rimette al loro posto, con tutto quello che è stato eliminato insieme a loro. Chi elimina molte cose di fila (più di 300 in dieci minuti) viene fermato per qualche minuto.

## Assistente AI

Se l'organizzazione lo ha attivato, dal menu ⋯ del progetto scegli **Assistente AI…**:
1. descrivi il lavoro (un elenco di attività, una per riga, funziona meglio);
2. Horizon propone sezioni, attività, durate e dipendenze;
3. correggi, togli righe, cambia le date di inizio;
4. premi **Applica**.

**Finché non applichi, nel progetto non cambia nulla.** Una proposta applicata si annulla come un'importazione. Le regole offline non inviano dati da nessuna parte; un modello esterno (per esempio Claude) riceve solo il testo che scrivi.

## Regole automatiche e altri programmi

- **Regole automatiche:** menu ⋯ del progetto › **Regole automatiche…**. Una regola ha tre parti:
  1. **Quando:** un'attività viene creata, lo stato cambia (o diventa uno stato preciso), qualcuno viene assegnato, arriva un commento, un'attività è in ritardo o la fine si avvicina;
  2. **Se** (facoltativo): ha un'etichetta, è in una sezione, ha una priorità, è assegnata a qualcuno;
  3. **Allora:** imposta lo stato o la priorità, aggiunge un'etichetta, assegna, avvisa gli assegnatari o i responsabili, sposta in una sezione, chiama un webhook.

  Esempio: «quando lo stato diventa Completata, avvisa i responsabili del progetto». Una regola agisce come chi la salva, e si ferma se quella persona non può più modificare il progetto. **Cosa ha fatto** mostra le esecuzioni. Le regole che si avviano a vicenda si fermano dopo tre passaggi.
- **Webhook in uscita** (Impostazioni › Integrazioni, Owner e Admin): Horizon manda gli eventi scelti (attività create, modificate, eliminate, commenti, assegnazioni…) a un altro programma, con una richiesta HTTPS firmata. Se il programma non risponde, riprova per 12 ore. **Manda una prova** e **Consegne** aiutano a controllare.
- **Chiavi API** (Impostazioni › Sicurezza e dispositivi): per script e altri programmi. Una chiave agisce come te, con i tuoi permessi, per i giorni che scegli o finché non la revochi; **Solo lettura** non cambia niente. Copiala subito: non verrà mostrata di nuovo. Una chiave non cambia mai l'account, non fa operazioni delicate e non usa il tempo reale.

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
- **Passkey:** **Aggiungi una passkey** ti fa entrare con l'impronta, il volto o il PIN del dispositivo, senza password: alla pagina di accesso scegli **Accedi con una passkey**. Una passkey non si può rubare con un finto sito e vale come verifica in due passaggi. Funziona quando Horizon è aperto con il suo nome (non con un indirizzo IP) in un browser che la supporta; nelle app per Windows e Android si entra con la password.
- **Dispositivi:** l'elenco dei browser e delle app con cui sei entrato; puoi disconnetterli uno per uno o tutti. Quando entri da un dispositivo nuovo ricevi un'e-mail: se non sei stato tu, cambia la password e disconnetti quel dispositivo.
- **Conferma che sei tu:** prima delle operazioni delicate (disconnettere dispositivi, cambiare ruoli, eliminare progetti, creare link pubblici, chiavi, webhook o moduli) Horizon chiede di nuovo la password, il codice o la passkey. La conferma vale 10 minuti.
- **Attività dell'account:** accessi (anche quelli non riusciti), dispositivi nuovi, password, verifica in due passaggi e passkey, con data e dispositivo.
- **Registro di sicurezza** (Impostazioni › Organizzazione, Owner e Admin): ruoli, inviti, link condivisi, esportazioni, progetti eliminati, integrazioni, chiavi e webhook. Ogni voce è legata alla precedente: **Verifica l'integrità** dice se qualcuna è stata tolta o cambiata.
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
| Ospite | Esterno: solo i progetti a cui è invitato; legge, commenta se il progetto lo consente e risponde alle approvazioni; non vede le altre persone e non esporta |
