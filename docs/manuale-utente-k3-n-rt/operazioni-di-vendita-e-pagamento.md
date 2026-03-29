# Operazioni di Vendita e Pagamento

Questa sezione descrive come registrare le vendite, applicare modificatori come sconti o storni, e gestire le diverse forme di pagamento.

### Registrazione Articoli
Le vendite possono essere registrate in due modalità principali:
- **Su Reparto**: Digitando l'importo e premendo il tasto del reparto corrispondente (se a prezzo libero) o semplicemente premendo il tasto del reparto (se a prezzo prefissato).
- **Su PLU (Price Look Up)**: Inserendo il codice PLU o utilizzando un lettore di codici a barre. È possibile vendere articoli a peso tramite la funzione PLU bilancia.

### Modificatori
Durante una transazione è possibile applicare diverse modifiche:
- **Annullo Scontrino (F007)**: Annulla l'intera transazione prima della chiusura.
- **Annulli (F008)**: Cancella l'ultima voce inserita.
- **Storno (F026)**: Storna un articolo precedentemente registrato nello stesso scontrino.
- **Sconto/Maggiorazione Percentuale**: Applica uno sconto o una maggiorazione in percentuale su un articolo o sul subtotale.
- **Sconto/Maggiorazione a Valore**: Applica uno sconto o una maggiorazione a valore fisso su un articolo o sul subtotale.
- **Documento di Annullo/Reso (F032/F031)**: Permette di annullare o gestire il reso di una transazione precedente, anche di giorni diversi.

### Gestione Pagamenti
La chiusura della transazione avviene selezionando una o più modalità di pagamento.

| Tipo di Pagamento | Funzione Default | Descrizione |
| --- | --- | --- |
| Contanti | F102 | Pagamento in contanti, con calcolo automatico del resto. |
| Credito | F100 | L'importo viene addebitato a un cliente registrato. |
| Assegno | F099 | Pagamento tramite assegno. |
| Buoni Pasto | F901 | Pagamento tramite buoni pasto. |
| Carta di Credito | F104 | Pagamento elettronico. |
| Bancomat | F908 | Pagamento elettronico. |
| Pagamenti Misti | - | È possibile combinare diverse forme di pagamento per raggiungere il totale. |
| Cambio Valuta | F143 | Permette di gestire pagamenti in valute diverse dall'Euro. |
