# Come contribuire

Grazie per voler contribuire! Questo progetto vive dei contributi degli Assistenti Bagnanti e di
chiunque voglia rendere il mestiere più consapevole e più sicuro. **Puoi contribuire anche se non
sei una persona tecnica.**

## Regola numero uno: niente dati personali

Non inviare e non inserire **dati personali tuoi o di terzi**:

- nomi di colleghi, datori di lavoro, vittime, strutture identificabili;
- numeri di brevetto, documenti aziendali riconoscibili (mansionari con loghi/firme, ecc.);
- qualsiasi informazione che permetta di identificare persone o aziende in casi privati.

I casi giudiziari si trattano **solo** sulla base di **fonti pubbliche**, concentrandosi sui principi e
sulla lezione pratica. Per i procedimenti in corso vale la **presunzione di innocenza**.

## Cosa puoi proporre

- **Sentenze e casi** (con estremi o link alla fonte).
- **Normativa regionale** sulle piscine / recepimenti dell'Accordo Stato-Regioni.
- **Modulistica** (modelli da generalizzare).
- **Correzioni** di errori, refusi, link rotti, contenuti non aggiornati.

## Modi per contribuire

### A) Non sei tecnico/a (più semplice)

1. **Apri una issue**: nella pagina del repository su GitHub, vai su **Issues → New issue** e scegli
   il modello (proponi un contenuto / segnala un caso / correggi un errore). Basta un account
   GitHub gratuito.
2. **Oppure scrivi via email**: `assistentibagnanti@proton.me`, allegando il materiale e la fonte.

Penseremo noi a inserirlo e generalizzarlo.

### B) Conosci Git/GitHub (Pull Request)

1. Fai un **fork** del repository.
2. Crea un branch descrittivo (es. `aggiunta-sentenza-xyz`).
3. Modifica/aggiungi file Markdown in `docs/` (vedi struttura nel `README`).
4. Verifica in locale:
   ```bash
   pip install -r requirements.txt
   mkdocs serve            # anteprima
   mkdocs build --strict   # deve passare senza errori (link rotti, ecc.)
   ```
5. Apri una **Pull Request** spiegando la modifica e **citando le fonti**.

## Stile dei contenuti

- **Lingua:** italiano, tono chiaro e fattuale, pensato per chi non è giurista.
- **Cita sempre la fonte** (legge, articolo, sentenza, link).
- Una pagina = un argomento; usa titoli, elenchi e i box (`!!! note`, `!!! warning`, `!!! danger`).
- I percorsi interni vanno linkati come file relativi (es. `../quadro-normativo/codice-penale.md`).
- I PDF ufficiali vanno in `docs/risorse/` con nomi chiari (minuscolo, trattini).

## Licenza dei contributi

Contribuendo, accetti che il tuo contributo sia rilasciato con licenza
**[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it)**, la stessa dei contenuti
del sito.

## Codice di condotta

Partecipando, accetti il [Codice di Condotta](CODE_OF_CONDUCT.md). In sintesi: rispetto, toni
civili, niente attacchi personali.
