# timone-sito

Sito statico di presentazione di Timone (app di controllo e analisi aziendale per imprese italiane).
Stato: **anteprima, versione di prova**. Riferimento: app Timone 1.15.2 (commit `7408aa7`).

Solo HTML e CSS: nessun JavaScript, nessuna compilazione, nessuna dipendenza, nessuna risorsa esterna.
Tutte le pagine hanno `noindex` e una politica di sicurezza restrittiva.

## File
`index.html`, `funzioni.html`, `dati.html`, `prova.html`, `privacy.html`, `404.html`, `stile.css`, `icona.svg`, `immagini/` (vuota per ora).

## Percorso base
`404.html` usa percorsi che iniziano con `/timone-sito/`. Se cambiano il nome del repository o il dominio, vanno aggiornati.

## Cose da completare (segnaposto)
Nelle pagine compare «da completare» con accanto un commento `DA-COMPILARE: NOME`. Per trovarli: cerca `DA-COMPILARE` nei file.

| Segnaposto | Dove |
|---|---|
| `EMAIL_CONTATTO` (indirizzo di posta) | piè di pagina di tutte le pagine (`index`, `funzioni`, `dati`, `prova`, `privacy`, `404`); `privacy.html` (elenco contatti); `prova.html` |
| `TITOLARE` | `privacy.html` |
| `DATI_FISCALI` | `privacy.html` |
| `LINK_INFORMATIVA_GITHUB` (da verificare aprendo l'indirizzo) | `privacy.html`, sezione «Chi lo ospita» |
| `URL_APP` (da verificare aprendo l'indirizzo) | `prova.html`; finché manca non c'è nessun pulsante che apra l'app |
| `URL_SITO` | non ancora usato: servirà per le anteprime sui social (Open Graph), omesse in anteprima |

Altro da fare prima della pubblicazione aperta:
- `prova.html`, riga con `DA-VERIFICARE-FASE-3`: controllare i nomi dei pulsanti aprendo l'app.
- Inserire le schermate in `immagini/` al posto dei riquadri «in preparazione» di `prova.html`.
- Far verificare la bozza di `privacy.html`.
- Rimuovere `noindex` solo dopo conferma.
- Controllare nel browser: nessuna richiesta esterna, nessuno scorrimento orizzontale a 360, 390, 768 e 1280px, `404.html` servita da `/timone-sito/`.
