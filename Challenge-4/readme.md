# YouTube Clone Layout - Esercitazione HTML & CSS

Questo progetto è un'esercitazione pratica di sviluppo web front-end che mira a replicare la struttura e il layout dell'interfaccia principale di YouTube utilizzando esclusivamente HTML5 e CSS3.

## 📋 Descrizione

L'obiettivo dell'esercizio è creare una pagina web statica strutturata in diverse sezioni chiave (Sidebar, Navbar e una griglia di video) imparando a gestire il posizionamento degli elementi tramite **Flexbox** e rendendo il layout **responsivo** per i dispositivi mobili.

## 🚀 Funzionalità Principali

- **Layout basato su Flexbox**: Utilizzo intensivo di flexbox per allineare correttamente la barra di navigazione, la barra laterale e la griglia delle miniature dei video.
- **Design Responsivo (Media Queries)**: 
  - Su schermi desktop (sopra gli 800px), il layout mostra una griglia a più colonne con la sidebar laterale e la barra di ricerca completa.
  - Su dispositivi mobili (sotto gli 800px), la griglia passa a una singola colonna (100% della larghezza), la barra laterale e la barra di ricerca vengono nascoste per ottimizzare lo spazio visivo.
- **Effetti Hover**: Le card dei video hanno un leggero effetto di background al passaggio del mouse per migliorare l'esperienza utente (UI/UX).

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Per la struttura semantica della pagina.
- **CSS3**: Per la stilizzazione, il layout (Flexbox) e la responsività (Media Queries).
- **FontAwesome (v7.3.1)**: Per l'inserimento delle icone vettoriali (menu, notifiche, ricerca, ecc.).
- **Google Fonts**: Per la tipografia, utilizzando il font *"Roboto"*.

## 📁 Struttura dei File

- `index.html`: Contiene lo scheletro della pagina, inclusa la Navbar, la Sidebar e il container principale per i video.
- `style.css`: Contiene tutte le regole di stile, le classi di utilità (es. `.row`, `.col-8`, `.col-4`) e le media query.
- `static/image/`: (Da aggiungere localmente) Cartella destinata a contenere le immagini di copertina dei video.

## 💻 Come visualizzare il progetto

Non è necessaria alcuna installazione o configurazione di server. 
1. Clona o scarica il repository.
2. Assicurati di avere un'immagine di test al percorso `static/image/thedigitalartist-mountain-2143877.jpg` (oppure modifica il percorso in `index.html` con un'immagine a tua scelta).
3. Apri il file `index.html` con qualsiasi browser web moderno (Chrome, Firefox, Safari, Edge).