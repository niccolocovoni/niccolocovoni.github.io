# Stato dei lavori

Ultimo aggiornamento: 2026-06-25

## Regola operativa

Ogni volta che viene fatta una modifica al sito, questo file va aggiornato con:

- data dell'intervento;
- file modificati;
- sintesi delle modifiche;
- verifiche eseguite;
- prossimi passi utili.

## Stato attuale

Il sito e' una pagina personale accademica statica in HTML/CSS.

File principali presenti nella cartella:

- `index_updated.html`: versione precedente piu' completa.
- `index_updated_v2.html`: versione intermedia piu' snella.
- `index_v3.html`: versione 3 attuale, creata a partire dalla chat condivisa.

## Ultime modifiche

### 2026-06-25

File modificati:

- `index_v3.html`
- `index.html`
- `.gitignore`
- `stato_dei_lavori.md`

Modifiche effettuate:

- recuperato il piano di lavoro dalla chat condivisa di ChatGPT;
- creata la Versione 3 del sito;
- aumentata la dimensione della foto profilo;
- ripristinata la sezione Research con quattro aree di ricerca;
- sostituito "the status of quantum states" con "Segal entropy";
- aggiunta la visita accademica a Cagliari;
- aggiunto "Lugano Philosophy Colloquia" nella sezione Teaching;
- impostato il contatto email su Gmail;
- aggiunto link a Google Scholar nei contatti;
- mantenuto il testo giustificato su desktop;
- corretto l'allineamento mobile per evitare spaziature eccessive nel testo;
- verificato che la navigazione interna non abbia ancore rotte;
- verificato che non ci sia overflow orizzontale su desktop e mobile.
- preparato `index.html` come copia pubblicabile della Versione 3 per GitHub Pages;
- aggiunto `.gitignore` per escludere `.DS_Store` e la cartella locale `00_pipeline/` dal repository.
- inizializzato un repository Git locale;
- creato il commit iniziale `8f8f4e8` con i file pubblicabili del sito.

Verifiche eseguite:

- apertura locale tramite server `http://localhost:8000/index_v3.html`;
- controllo sezioni presenti: About, Research, Publications, Academic Visits, Teaching, CV, Contact;
- controllo ancore della navbar;
- controllo resa desktop;
- controllo resa mobile a 390x844.

Prossimi passi utili:

- sostituire il link Facebook generico con il profilo corretto;
- valutare una sezione News o Talks;
- eventualmente aggiungere una pagina dedicata a `Tractatus Quanticus`;
- verificare/aggiornare CV e pubblicazioni prima della pubblicazione online.
- creare o collegare un repository GitHub;
- pubblicare il sito con GitHub Pages.
