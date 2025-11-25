# 🎵 Vibe Music Blog

> Uno spazio digitale minimale e "cozy" per recensioni musicali oneste e dettagliate.

Questo progetto è un blog statico (HTML/CSS) progettato per recensire album con un focus analitico **traccia per traccia**. L'estetica è pensata per essere rilassante (colori crema, terracotta, dark grey), invitando alla lettura lenta accompagnata dall'ascolto in alta fedeltà.

![Preview del Sito](img/preview.jpg)
*(Nota: Carica uno screenshot della tua home nella cartella img e chiamalo preview.jpg per vederlo qui)*

## ✨ Caratteristiche

* **Cozy UI:** Una palette di colori caldi (Cream & Earth Tones) per un'esperienza di lettura senza stress.
* **Track-by-Track Analysis:** Struttura ottimizzata per recensire ogni singolo brano separatamente, con voto e commento dedicato.
* **Tidal Integration:** Supporto nativo per gli embed di **Tidal** (e Amazon Music) per ascoltare estratti dei brani in alta qualità direttamente dalla recensione.
* **Zero Bloat:** Niente database, niente framework pesanti. Solo HTML5 e CSS3 puro. Velocissimo e leggero.
* **Responsive:** Griglia flessibile che si adatta a desktop e mobile.

## 🛠️ Tecnologie Usate

* **HTML5:** Struttura semantica (uso di `<article>`, `<header>`, `<iframe>`).
* **CSS3:**
    * CSS Variables per la gestione dei colori (facile cambio di temi).
    * Flexbox & CSS Grid per il layout.
    * Google Fonts (Inter).

## 📂 Struttura del Progetto

```text
/blog-musica
├── index.html            # La Home (Vetrina delle recensioni)
├── style.css             # Foglio di stile globale (Colori, Layout, Typography)
├── README.md             # Documentazione
├── /recensioni           # Cartella contenente le pagine dei singoli album
│   └── album-1.html      # Esempio di recensione (Tame Impala)
└── /img                  # Copertine degli album e asset grafici