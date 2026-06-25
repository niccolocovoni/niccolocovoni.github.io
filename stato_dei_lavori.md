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

- `index.html`: versione pubblicata online e file principale del sito.
- `stato_dei_lavori.md`: memoria locale del progetto.
- `github_profile_README.md`: bozza usata come README del profilo GitHub.

## Ultime modifiche

### 2026-06-25

File modificati:

- `index_v3.html`
- `index.html`
- `.gitignore`
- `stato_dei_lavori.md`
- `github_profile_README.md`

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
- preparata una bozza di README per il profilo GitHub nel file `github_profile_README.md`.
- collegato il repository locale al remote `https://github.com/niccolocovoni/niccolocovoni.github.io.git`.
- tentato il push verso GitHub; bloccato per mancanza di credenziali GitHub disponibili nella sessione (`could not read Username for 'https://github.com'`).
- verificato che non ci sono chiavi SSH locali disponibili in `~/.ssh`.
- avviata installazione locale di GitHub CLI (`gh`) in `.tools/`, esclusa dal repository.
- completato login GitHub CLI come `niccolocovoni`.
- creato repository pubblico `https://github.com/niccolocovoni/niccolocovoni.github.io`.
- configurato Git per usare le credenziali di GitHub CLI.
- pubblicato il branch `main` su GitHub.
- abilitato GitHub Pages da branch `main`, cartella `/`.
- verificato che `https://niccolocovoni.github.io/` risponde con `HTTP 200`.
- creato repository profilo pubblico `https://github.com/niccolocovoni/niccolocovoni`.
- pubblicato `github_profile_README.md` come `README.md` del profilo GitHub.
- eliminate le vecchie copie locali non tracciate `index_updated.html` e `index_updated_v2.html`.
- eliminata la copia locale `index_v3.html`; `index.html` resta l'unico HTML ufficiale del sito.
- aggiornato il footer del sito con copyright e dicitura `Built with HTML & CSS`.
- aggiornata la posizione istituzionale da `researcher` a `Non-Tenured Assistant Professor` nel sito e nella bozza del profilo GitHub.
- aggiunta la sezione `Research Coordination` al sito.
- inserito il ruolo di coordinatore di CI2, Complexity & Information Initiative, presso ICTS/Sophia University Institute.
- aggiunto link alla pagina CI2: `https://sankio23.github.io/icts-website/research/ci2.html`.
- aggiunta voce navbar `CI²`, etichetta breve per mantenere compatta la navigazione mobile.
- aggiornata la bozza del README del profilo GitHub con CI2.
- centrato il bottone `Visit CI²` nella sezione Research Coordination.
- rimossa la freccia verso il basso dal bottone `Download CV`.
- uniformati i titoli accademici nelle sezioni About e Academic Visits per Francesca Vidotto, Hanna Podsędkowska, Eugene Y. S. Chua, Roberto Giuntini e Giuseppe Sergioli.
- uniformata la posizione istituzionale come `Non-Tenured Assistant Professor`.
- uniformato `Prof.` in `Professor` nel testo del progetto di dottorato.
- rinominata la sezione `Academic Visits` in `Research Visits`.
- aggiornata la frase di contatto in `You can reach me by email at`.
- sostituito il link esterno del bottone `Download CV` con il PDF locale `files/Academic_CV.pdf`.
- aggiunto `.nojekyll` per pubblicare il sito GitHub Pages come statico puro.
- aggiunta la sezione `Talks` con invited talks, selected presentations e public presentations.
- aggiunta voce `Talks` nella navbar.
- confermato che le poster presentations non sono state inserite nella sezione `Talks`; restano solo nel blocco `Posters` di `Publications`.
- aggiornato `github_profile_README.md` con link diretti a `Talks` e al PDF del CV.

Verifiche eseguite:

- apertura locale tramite server `http://localhost:8000/index_v3.html` durante la fase V3;
- controllo sezioni presenti: About, Research, Research Coordination, Publications, Talks, Research Visits, Teaching, CV, Contact;
- controllo ancore della navbar;
- controllo resa desktop;
- controllo resa mobile a 390x844.

Prossimi passi utili:

- sostituire il link Facebook generico con il profilo corretto;
- valutare una sezione News;
- eventualmente aggiungere una pagina dedicata a `Tractatus Quanticus`;
- rifinire il README del profilo GitHub se vuoi un tono piu' personale o piu' accademico.
- valutare se creare in futuro una pagina interna dedicata a CI2, invece del solo rimando alla pagina ICTS.
