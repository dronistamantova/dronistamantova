# Dronista Mantova — sito web

Sito statico a una pagina, ottimizzato per la SEO sulla keyword **"dronista mantova"**.

## Struttura del progetto

```
├── index.html          → l'intero sito (testi, stile e illustrazione in un unico file)
├── robots.txt          → indicazioni per i motori di ricerca
└── sitemap.xml         → mappa del sito per Google
```

Il sito è volutamente in un solo file, così è facilissimo da caricare, modificare e capire.

## Come pubblicarlo su GitHub Pages (gratis)

1. Vai su [github.com](https://github.com) e crea un account (se non ce l'hai già).
2. Clicca su **New repository** (in alto a destra, "+").
3. Chiamalo ad esempio `dronista-mantova` e crealo (può essere pubblico).
4. Nella pagina del repository appena creato, clicca **"uploading an existing file"**.
5. Trascina dentro **tutti i file** contenuti in questo zip (`index.html`, `robots.txt`, `sitemap.xml`).
6. Clicca **Commit changes** in basso per salvare.
7. Vai su **Settings → Pages** (menu a sinistra).
8. In "Branch" seleziona `main` e cartella `/ (root)`, poi **Save**.
9. Dopo 1-2 minuti il sito sarà online all'indirizzo:
   `https://TUONOMEUTENTE.github.io/dronista-mantova/`

## Collegare un dominio tuo (es. dronistamantova.it)

Se in futuro acquisti il dominio `dronistamantova.it`:

1. In **Settings → Pages** inserisci il dominio nel campo "Custom domain".
2. Dal pannello del tuo provider dominio, crea un record DNS di tipo `CNAME` che punti a `TUONOMEUTENTE.github.io`.
3. Aggiorna nei file `index.html`, `sitemap.xml` e `robots.txt` gli indirizzi
   `https://www.dronistamantova.it/` con il tuo dominio effettivo, se diverso.

## Cosa modificare in futuro

- **Testi e servizi**: apri `index.html` con un editor di testo e modifica il contenuto tra i tag `<h2>`, `<h3>` e `<p>`.
- **Colori**: sono tutti definiti in cima al file, dentro il tag `<style>`, nel blocco `:root`.
- **Telefono/email/P.IVA**: cerca "370 327 3920", "dronistacertificato@gmail.com" e "IT02753480207" dentro `index.html` e sostituiscili.

## Nota sulla SEO

Il sito è stato ottimizzato al massimo lato "on-page" sulla keyword **"dronista Mantova"**:

- **Title e meta description** con la keyword all'inizio;
- **H1** esatto "Dronista a Mantova e provincia", e la keyword ripetuta in modo naturale in H2, sottotitoli, testo dei servizi, FAQ, contatti e footer;
- **Sezione FAQ** (con relativo markup `FAQPage`) pensata per intercettare le ricerche a coda lunga ("chi è il dronista di Mantova", "quanto costa", ecc.) e per comparire come riquadro Q&A nei risultati Google;
- **Dati strutturati Schema.org** `LocalBusiness` arricchiti con servizi offerti, comuni serviti, P.IVA e contatti, così Google può capire meglio chi sei e cosa offri;
- **Link interni** nel menu (Servizi, FAQ, Contatti) con testo di ancoraggio pertinente;
- **Comuni della provincia** citati esplicitamente in footer e FAQ, utile per il posizionamento locale;
- `sitemap.xml`, `robots.txt`, tag `hreflang` e `canonical`.

**Una cosa importante da sapere**: non ho volutamente riempito il testo di "dronista Mantova" ripetuto meccanicamente ovunque (il cosiddetto *keyword stuffing*). Google penalizza i siti che abusano della parola chiave: nella pratica un testo innaturale danneggia il posizionamento invece di migliorarlo. Ho invece distribuito la keyword e le sue varianti naturali ("dronista a Mantova", "drone a Mantova e provincia", "pilota di drone a Mantova") nei punti che contano di più per Google (title, H1, prime righe, intestazioni, FAQ) mantenendo un testo che si legge bene.

### Cosa conta ANCORA di più del testo del sito (fattori "off-page")

Per una parola chiave locale come "dronista Mantova", questi passaggi pesano spesso più del sito stesso:

1. **Scheda Google Business Profile** intestata a "Dronista Mantova", con indirizzo/area di servizio, categoria corretta e foto reali del tuo lavoro (drone, riprese, sopralluoghi).
2. **Recensioni Google** dai primi clienti: sono uno dei fattori più forti per il posizionamento locale.
3. **Backlink locali**: farsi citare da siti di categoria (Pagine Gialle, directory locali di Mantova, articoli di giornali locali, collaborazioni con altre attività).
4. **Google Search Console**: registra il sito e invia la sitemap (`sitemap.xml`) appena il sito è online, per farlo scansionare più in fretta.
5. **Foto reali**: quando avrai fotografie vere del tuo lavoro, salvale con nomi file descrittivi come `dronista-mantova-ripresa-aerea.jpg` o `drone-mantova-ispezione-tetto.jpg` invece di nomi generici tipo `IMG_1234.jpg`, e aggiungile al sito con un testo alternativo (attributo `alt`) che descriva l'immagine, ad esempio `alt="Drone in volo sopra Mantova durante un rilievo aereo"`.

Nessuno di questi passaggi si può "finire" nel codice del sito: sono attività che si costruiscono nel tempo, ma sono quelle che davvero spostano l'ago della bilancia per una ricerca locale come questa.
