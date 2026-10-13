PROBABILITÀ TEXAS HOLD'EM — PACCHETTO PWA

CONTENUTO
- index.html: applicazione web adattata per installazione
- manifest.json: nome, icone e modalità app
- service-worker.js: cache dell'app shell e supporto di base all'uso offline
- icons/: icone per Android e iOS

COME INSTALLARLA
1. Pubblica tutti i file mantenendo la struttura delle cartelle su un sito HTTPS (ad esempio GitHub Pages, Firebase Hosting o un hosting aziendale).
2. Apri l'URL HTTPS da Chrome su Android oppure Safari su iPhone.
3. Android/Chrome: menu ⋮ > "Installa app" oppure "Aggiungi a schermata Home".
4. iPhone/Safari: Condividi > "Aggiungi alla schermata Home".

IMPORTANTE
- Non basta aprire index.html direttamente dal computer: manifest e service worker richiedono un server web; il service worker richiede HTTPS (fa eccezione localhost).
- La prima apertura deve avvenire online per scaricare i file. Dopo il primo caricamento, la cache consente l'apertura offline dell'app shell.
- I Google Fonts sono esterni: offline potrebbero non essere disponibili, ma l'app usa font di riserva.
- Il pacchetto non pubblica automaticamente il sito e non configura account o autenticazione.
