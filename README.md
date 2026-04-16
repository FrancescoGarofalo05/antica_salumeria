markdown

# 🍖 Antica Salumeria

**Landing Page per una salumeria tradizionale di Giugliano in Campania.**

Un sito web moderno, responsive e accessibile, progettato per presentare l'attività, i prodotti tipici e facilitare il contatto tramite WhatsApp e social media.

![Antica Salumeria Preview](./src/img/hero-salumeria.jpg)

---

## 🚀 Demo Live

🔗 **[Vedi la demo su Vercel](https://antica-salumeria.vercel.app)** _(sostituisci con il tuo link dopo il deploy)_

---

## ✨ Caratteristiche Principali

- 🎨 **Design Moderno** – Ispirato ai colori caldi della tradizione campana (marrone cuoio, beige, rosso salume)
- 📱 **Fully Responsive** – Ottimizzato per mobile, tablet, desktop e TV 4K
- ♿ **Accessibilità** – Conforme WCAG 2.1: skip-to-content, ARIA labels, supporto screen reader
- 🖼️ **Galleria Prodotti** – Carosello interattivo con Swiper.js (8 slide)
- 💬 **Float Widget** – Pulsante flottante per contatti rapidi WhatsApp e Instagram
- 🗺️ **Mappa Google** – Integrata per mostrare la posizione dell'attività
- ⚡ **Performance** – Immagini lazy-loading, preload critico, scroll fluido
- 🔍 **SEO Ready** – Meta tag ottimizzati, Open Graph per social sharing

---

## 🛠️ Tecnologie Utilizzate

| Tecnologia            | Utilizzo                                                           |
| --------------------- | ------------------------------------------------------------------ |
| **HTML5**             | Struttura semantica e accessibile                                  |
| **CSS3**              | Styling responsive con Flexbox, Grid, Variabili CSS                |
| **JavaScript (ES6)**  | Interattività: menu hamburger, float widget, Swiper, scroll reveal |
| **Swiper.js**         | Carosello prodotti touch-friendly                                  |
| **Google Maps Embed** | Mappa interattiva                                                  |
| **Google Fonts**      | Font Inter (caricato via CDN)                                      |

---

## 📁 Struttura del Progetto

antica-salumeria/
├── index.html # Pagina principale
├── css/
│ └── style.css # Stili responsive mobile-first
├── js/
│ └── main.js # Logica JavaScript
├── src/
│ └── img/ # Immagini del sito
│ ├── logo.png
│ ├── hero-salumeria.jpg
│ ├── parmigiano.jpg
│ ├── salame.jpg
│ ├── prosciutto.jpg
│ ├── ricotta.jpg
│ ├── pancetta.jpg
│ ├── guanciale.jpg
│ ├── olio.jpg
│ └── formaggi.jpg
└── README.md # Documentazione

text

---

## 🧩 Funzionalità JavaScript

| Funzione                  | Descrizione                                                                     |
| ------------------------- | ------------------------------------------------------------------------------- |
| **Hamburger Menu**        | Toggle menu mobile con animazione, chiusura al click esterno e tasto ESC        |
| **Float Widget**          | Bottone omino che espande WhatsApp e Instagram. Icona cambia in ✕ quando aperto |
| **Swiper Carosello**      | Galleria prodotti con loop, navigazione, paginazione e breakpoint responsive    |
| **Scroll Reveal**         | Animazioni fade-in allo scroll usando Intersection Observer                     |
| **Header Sticky**         | Sfondo semi-trasparente con blur dopo lo scroll                                 |
| **Smooth Scroll**         | Navigazione fluida alle ancore interne con offset per header fisso              |
| **Lazy Loading Fallback** | Supporto per browser che non supportano `loading="lazy"`                        |
| **Anno Copyright**        | Aggiornamento automatico dell'anno nel footer                                   |

---

## 🚀 Deploy su Vercel

1. Crea un repository su **GitHub** e carica il progetto
2. Vai su [Vercel](https://vercel.com) e clicca **"Import Project"**
3. Seleziona il repository da GitHub
4. Lascia le impostazioni di default e clicca **"Deploy"**
5. Il sito sarà online in pochi secondi!

---

## 📱 Responsive Breakpoints

| Breakpoint       | Dispositivo   | Layout                                   |
| ---------------- | ------------- | ---------------------------------------- |
| `< 640px`        | Mobile        | 1 colonna, menu full-width, hero 60vh    |
| `640px - 1023px` | Tablet        | 2 colonne card, menu dropdown a destra   |
| `≥ 1024px`       | Desktop       | 3 colonne card, grid contatti 2 colonne  |
| `≥ 1440px`       | Large Desktop | Container allargato, immagini più grandi |
| `≥ 2560px`       | 4K TV         | Font scalati, altezze maggiorate         |

---

## ✅ Checklist Accessibilità

- [x] Attributi `alt` descrittivi per tutte le immagini
- [x] Link "Salta al contenuto" per screen reader
- [x] ARIA labels per pulsanti e menu (`aria-expanded`, `aria-hidden`, `aria-label`)
- [x] Ruoli semantici (`role="banner"`, `role="navigation"`, `role="main"`, `role="contentinfo"`)
- [x] Supporto navigazione da tastiera (ESC per chiudere menu)
- [x] Riduzione animazioni per `prefers-reduced-motion`

---

## 👨‍💻 Autore

**Francesco Garofalo**  
Web Developer & Appassionato di scrittura

- 📧 Email: [francescogarofalo34@gmail.com](mailto:francescogarofalo34@gmail.com)

---

## 📄 Licenza

Questo progetto è rilasciato sotto licenza **MIT**.  
Vedi il file [LICENSE](./LICENSE) per i dettagli.

---

## 🙏 Ringraziamenti

- [Swiper.js](https://swiperjs.com/) per il carosello touch-friendly
- [Google Fonts](https://fonts.google.com/) per i font Inter e Georgia
- [Unsplash](https://unsplash.com/) per le immagini placeholder (da sostituire con foto reali)

---

_Realizzato con ❤️ e 🍖 a Giugliano in Campania_
