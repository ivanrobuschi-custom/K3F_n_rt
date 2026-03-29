# Servizi Telematici e Lotteria degli Scontrini

Questa sezione descrive le funzionalità telematiche del registratore per la comunicazione con l'Agenzia delle Entrate e la gestione della Lotteria degli Scontrini.

### Servizi Telematici
Il dispositivo gestisce l'invio telematico dei corrispettivi giornalieri. Le principali funzionalità includono:
- **Gestione Disallineamenti**: Se lo stato del dispositivo sul portale dell'Agenzia delle Entrate non corrisponde a quello locale, il dispositivo si blocca e segnala la necessità di un intervento tecnico per il riallineamento.
- **Periodo Inattivo**: In caso di inattività superiore a 12 giorni, all'accensione il dispositivo richiede una chiusura fiscale a zero per comunicare il periodo di inattività.
- **Verifica Connessioni (P698)**: Una funzione per testare la connessione di rete con i server remoti.
- **Gestione File XML Sospesi**: In caso di mancato invio dei corrispettivi (es. per assenza di connessione), i file XML vengono memorizzati come "sospesi". È possibile forzarne l'invio manuale o esportarli per un caricamento manuale sul portale.
- **Aggiornamento Firmware da Remoto**: Il dispositivo può ricevere e installare aggiornamenti firmware predisposti da un tecnico abilitato, previa conferma dell'esercente.

### Lotteria degli Scontrini (Fiscale e Istantanea)
Il K3-N RT supporta sia la lotteria periodica che quella istantanea.
- **Lotteria degli Scontrini (Periodica)**: Per partecipare, il cliente deve fornire il proprio "codice lotteria" (alfanumerico di 8 caratteri) prima del pagamento. Il codice può essere acquisito tramite lettore di barcode o digitato manualmente. La transazione deve essere chiusa con un pagamento elettronico.
- **Lotteria Istantanea**: Non richiede il codice del cliente. Se la vendita è di importo pari o superiore a 1,00 € e pagata con metodo elettronico, lo scontrino emesso conterrà un codice bidimensionale (QR code) che il cliente può verificare tramite l'app "Gioco Legale" per scoprire un'eventuale vincita immediata.

L'attivazione di una o entrambe le lotterie avviene tramite la programmazione **P699 (Servizi Telematici)**.
