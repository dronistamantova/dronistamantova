# Dronista Mantova — sito web

Sito statico a una pagina, ottimizzato per la SEO sulla keyword **"dronista mantova"**.

## Struttura del progetto

```
├── index.html          → pagina unica del sito
├── style.css           → tutto lo stile
├── robots.txt          → indicazioni per i motori di ricerca
├── sitemap.xml         → mappa del sito per Google
└── assets/
    ├── favicon.svg          → icona del sito
    └── social-preview.svg   → immagine mostrata quando condividi il link
```

## Come pubblicarlo su GitHub Pages (gratis)

1. Vai su [github.com](https://github.com) e crea un account (se non ce l'hai già).
2. Clicca su **New repository** (in alto a destra, "+").
3. Chiamalo ad esempio `dronista-mantova` e crealo (può essere pubblico).
4. Nella pagina del repository appena creato, clicca **"uploading an existing file"**.
5. Trascina dentro **tutti i file e le cartelle** contenuti in questo zip (mantenendo la cartella `assets`).
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
- **Colori**: sono tutti definiti all'inizio di `style.css`, nel blocco `:root`.
- **Telefono/email/P.IVA**: cerca "370 327 3920", "geometra.tanganelli@gmail.com" e "IT02753480207" dentro `index.html` e sostituiscili.

## Nota sulla SEO

Il sito include già:
- Tag `<title>` e `<meta description>` con la keyword "dronista mantova";
- Dati strutturati Schema.org (`LocalBusiness`) con indirizzo, telefono, email e P.IVA, così Google può mostrare la scheda attività nei risultati;
- `sitemap.xml` e `robots.txt`;
- Tag Open Graph per un'anteprima curata quando il link viene condiviso su WhatsApp, Facebook, ecc.

Per rafforzare ulteriormente il posizionamento, consigliato (fuori dallo sviluppo del sito):
- Creare una scheda **Google Business Profile** intestata a "Dronista Mantova";
- Ottenere qualche recensione Google dai primi clienti;
- Registrare il sito su **Google Search Console** e inviare la sitemap.
