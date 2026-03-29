# Programmazione e Configurazione Avanzata

Questa sezione riassume le principali opzioni di programmazione per personalizzare il funzionamento del dispositivo. Si accede alla modalità **PROGRAMMAZIONE** tramite il tasto `Chiave`.

### Programmazioni Generali
- **P010/P011**: Impostazione di ora e data.
- **P014/P015**: Configurazione della disposizione e del feedback acustico dei tasti.
- **P016**: Impostazione delle aliquote IVA.
- **P018**: Regolazione dei parametri della stampante (es. intensità, velocità).
- **P019**: Configurazioni generali (es. obbligo di subtotale, gestione PLU a prezzo variabile).

### Configurazione Scontrino
- **P021**: Personalizzazione dell'intestazione dello scontrino (fino a 9 righe).
- **P023**: Personalizzazione dei messaggi di fine scontrino (righe di cortesia).
- **P024/P028**: Gestione delle icone grafiche da stampare periodicamente sullo scontrino.

### Programmazione Archivi
- **Reparti (P120)**: Creazione e modifica dei reparti, associando descrizione, prezzo, codice IVA, limiti di importo e altre opzioni.
- **PLU (P220)**: Creazione e modifica degli articoli (PLU), con codice, descrizione, prezzo, reparto associato e IVA.
- **Clienti (P340)**: Gestione di un'anagrafica clienti per l'assegnazione di vendite a credito.
- **Operatori (P320)**: Configurazione degli operatori, con codice, password e abilitazioni specifiche (sconti, storni, accesso a determinate funzioni).

### Funzioni Multiple (Macro)
- **P061**: Creazione di sequenze di operazioni (macro) che possono essere richiamate con un singolo tasto. Utile per vendite complesse o ripetitive (es. vendita di un cesto natalizio composto da più articoli e uno sconto).

### Comunicazione
- **P902**: Programmazione della porta seriale.
- **P911**: Configurazione dei parametri di rete Ethernet (IP, gateway, DNS).
- **P912**: Configurazione dei parametri Wi-Fi.
- **P913**: Configurazione dei parametri Bluetooth.
