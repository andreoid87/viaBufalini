# Via Fausto Bufalini 23 — dossier urbanistico-catastale

Repository di lavoro per ricostruire, in modo incrementale e verificabile, la storia catastale e urbanistica dell'unità immobiliare in **Via Fausto Bufalini 23, Messina**.

## Stato del dossier

Il documento principale è in `dossier/main.tex` e viene compilato automaticamente con GitHub Actions.

Il PDF viene prodotto come artifact del workflow **Build dossier PDF**.

## Identificativi principali

- Comune: Messina (F158)
- Catasto: Fabbricati
- Foglio: 124
- Particella: 509
- Subalterno: 5
- Piano: T
- Categoria: A/4
- Classe: 14
- Consistenza: 5 vani
- Rendita: €232,41

## Obiettivo dell'indagine

Verificare, prima di un eventuale accesso agli atti comunale, tutti i dati disponibili online e catastalmente, con particolare attenzione a:

- trasformazione storica di una porzione originariamente assimilabile a veranda/servizio in superficie interna del bagno;
- confronto con appartamenti sovrapposti o tipologicamente analoghi nel fabbricato;
- ricostruzione della nascita catastale dell'edificio;
- verifica del sedime storico del fabbricato;
- eventuali vincoli urbanistici, compresa la fascia di rispetto cimiteriale;
- individuazione puntuale dei documenti da richiedere al Comune.

## Struttura

- `dossier/main.tex` — dossier completo e incrementale;
- `dossier/figures/` — immagini e figure usate nel dossier;
- `fonti/F158_012400.dxf` — foglio catastale originario 124 in formato DXF;
- `.github/workflows/build-dossier.yml` — compilazione automatica del PDF.

## Privacy

Il repository è pubblico. Per questo motivo il dossier evita di pubblicare codici fiscali e altri dati personali non necessari di terzi. I documenti originali non redatti vengono mantenuti fuori dal repository; nel dossier sono riportati solo i dati tecnici pertinenti all'indagine.

## Aggiornamento incrementale

Ogni nuovo documento viene classificato come:

- **documentato** — dato direttamente leggibile da un atto;
- **ricordo/testimonianza** — informazione fornita dal proprietario;
- **inferenza** — conclusione ragionevole ma non ancora provata;
- **questione aperta** — punto da verificare con ulteriori fonti.

