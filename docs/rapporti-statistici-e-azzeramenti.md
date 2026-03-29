# Rapporti Statistici e Azzeramenti

Questa sezione illustra come generare report statistici e gestionali (letture) e come eseguire le procedure di azzeramento, inclusa la chiusura fiscale giornaliera.

### Rapporti Statistici e Gestionali (Letture - Assetto X)
Le letture permettono di consultare i dati di vendita senza azzerare i totalizzatori. Si accede tramite l'assetto **LETTURA**. I principali rapporti disponibili sono:
- **X00**: Lista dei rendiconti disponibili.
- **X01/X03**: Informazioni generali ed estese del dispositivo.
- **X10**: Rapporto finanziario generale di riepilogo.
- **X20/X21**: Rapporto reparti del giorno o per un periodo.
- **X22/X23**: Rapporto gruppi reparto del giorno o per un periodo.
- **X30/X31**: Rapporto PLU del giorno o per un periodo.
- **X41**: Rapporto attività oraria.
- **X50/X51**: Rapporto IVA del giorno o per un periodo.
- **X70-X99**: Vari report sulla memoria di dettaglio (scontrini lotteria, documenti non fiscali, interventi tecnici, ecc.).

### Azzeramenti (Assetto Z)
Gli azzeramenti resettano i totalizzatori. Si accede tramite l'assetto **AZZERAMENTO**.
- **Chiusura Fiscale (Z01)**: È l'operazione **obbligatoria** da eseguire a fine giornata. Genera il documento gestionale di riepilogo e predispone i dati per l'invio telematico all'Agenzia delle Entrate. Il dispositivo visualizza l'esito della trasmissione (`<ESITO POSITIVO>` o `<ESITO NEGATIVO>`).
- **Azzeramenti Periodici**: Resettano i totalizzatori usati per i report gestionali su un determinato periodo.
  - **Z20**: Azzeramento reparti periodo.
  - **Z21**: Azzeramento PLU periodo.
  - **Z41**: Azzeramento attività oraria.
  - **Z51**: Azzeramento IVA periodo.
  - **Z60/Z61**: Azzeramento totalizzatori clienti e modalità di pagamento.
