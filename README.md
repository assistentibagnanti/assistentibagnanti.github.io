# Assistenti Bagnanti

> Informazione, quadro normativo, giurisprudenza e modulistica sull'attività di
> **Assistente Bagnanti** in Italia — per chi la svolge **e** per chi gestisce una struttura con
> una piscina.

Sito: **https://assistentibagnanti.github.io/**

## Perché esiste

Fare l'Assistente Bagnanti (AB) è una professione poco valorizzata: spesso chi la svolge si ritrova a
coprire molte altre mansioni in contemporanea. Ma davanti alla legge l'AB è **garante** della
sicurezza dei bagnanti e, in caso di evento, ne risponde **in prima persona** — anche quando agisce su
ordine del datore.

Questo progetto raccoglie, in modo strutturato e accessibile, il materiale per:

1. **sensibilizzare** l'AB sul proprio ruolo e sulle responsabilità;
2. **informarsi** (leggi, accordi, sentenze, documenti ufficiali);
3. **tutelarsi** con strumenti pratici (lettere, segnalazioni, registri).

Il sito parla a **due pubblici**:

- **gli Assistenti Bagnanti**, per conoscere ruolo, responsabilità e strumenti di tutela;
- **le strutture con piscina** (hotel, camping, agriturismi, palestre…), per sapere chi è l'AB,
  quando è obbligatorio e cosa si rischia se manca o se gli si assegnano mansioni incompatibili.

Si parte dalle **piscine**, con l'idea di estendere in futuro ad acque interne e mare.

> ⚠️ **Materiale informativo, non consulenza legale.** Vedi [`docs/disclaimer.md`](docs/disclaimer.md).

## Struttura del repository

```
docs/
  index.md              # home con il bivio AB / struttura
  per-ab/               # area "Per gli Assistenti Bagnanti" (hub del percorso AB)
  per-strutture/        # area "Per le strutture": chi è l'AB, obblighi e rischi per il gestore
  guida-pratica/        # il ruolo e le responsabilità dell'AB
  quadro-normativo/     # leggi, accordi, codice penale, D.Lgs. 81/2008
  giurisprudenza/       # sentenze e casi reali, con la lezione per l'AB
  modulistica/          # modelli pronti (registro, contestazioni, segnalazioni, PEC)
  regioni/              # recepimenti regionali dell'Accordo Stato-Regioni
  risorse/              # PDF ufficiali scaricabili
mkdocs.yml              # configurazione del sito (MkDocs + tema Material)
requirements.txt        # dipendenze per la build
.github/workflows/      # deploy automatico su GitHub Pages
```

## Come lavorare in locale

Serve Python 3. Poi:

```bash
pip install -r requirements.txt
mkdocs serve          # anteprima su http://127.0.0.1:8000
mkdocs build --strict # build di verifica (fallisce su link rotti)
```

## Pubblicazione (GitHub Pages)

Il sito viene pubblicato **automaticamente** a ogni push sul branch `main` tramite GitHub Actions
(vedi [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)). La sorgente di **Pages** è già
configurata su **GitHub Actions** (**Settings → Pages**): non serve altro, ogni push aggiorna il sito.

## Contribuire

Tutti possono contribuire, anche chi non è tecnico: vedi [`CONTRIBUTING.md`](CONTRIBUTING.md) e la
pagina [Contribuisci](docs/contribuisci.md). Per favore, **mai dati personali** di terzi.

## Licenza

- **Contenuti** (testi del sito): [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it) — vedi [`LICENSE`](LICENSE).
- I documenti normativi e le sentenze restano soggetti al regime delle rispettive fonti ufficiali.
