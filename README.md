# 🎵 Vibe Music

> Il significato nascosto dietro le canzoni che ascoltiamo ogni giorno.

Vibe Music è un blog musicale scritto da **Nicolò Crisafulli**. Non trovi recensioni né classifiche — solo analisi approfondite sul significato dei brani, scritte da chi la musica la sente davvero.

Il sito è live su: **[crisa221.github.io/vibe_music_reviews](https://crisa221.github.io/vibe_music_reviews)**

---

## 🎤 Artisti e brani analizzati

### Tame Impala
| Brano | Album | Anno |
|---|---|---|
| Dracula | DeadBeat | 2025 |
| Afterthought | DeadBeat | 2025 |
| Ethereal Connection | DeadBeat | 2025 |

### Addison Rae
| Brano | Album | Anno |
|---|---|---|
| Headphones On | Addison | 2025 |
| Times Like These | Addison | 2025 |

### Madison Beer
| Brano | Album | Anno |
|---|---|---|
| Prossimamente | Locket | 2025 |

---

## 📁 Struttura del progetto

```
vibe_music_reviews/
├── index.html               # Homepage con feed articoli
├── about.html               # Pagina About
├── style.css                # Foglio di stile globale
├── README.md                # Questo file
├── img/                     # Immagini del sito
│   ├── deadbeat_cover.webp
│   ├── addison_rae_addison.webp
│   ├── locket.webp
│   └── favicon.png
└── articles/                # Articoli del blog
    ├── tame-impala-dracula.html
    ├── tame-impala-afterthought.html
    ├── tame-impala-ethereal.html
    ├── addison-rae-headphones.html
    └── addison-rae-times-like-these.html
```

---

## ✍️ Come aggiungere un nuovo articolo

**1. Duplica il template**

Nella cartella `articles/`, copia un articolo esistente e rinominalo seguendo la convenzione:
```
nome-artista-nome-brano.html
```
Esempio: `madison-beer-locket.html`

**2. Modifica il contenuto**

Apri il file e aggiorna:
- `<title>` — nome brano e artista
- `<img src>` — immagine dell'album
- Breadcrumb (artista / album / anno)
- Titolo hero e sottotitolo
- Meta-bar (artista, album, anno, genere, vibe score)
- Testo intro, sezioni e tag tematici
- Articoli correlati in fondo

**3. Aggiungi la card nella homepage**

Apri `index.html` e aggiungi una nuova card nel grid degli articoli:
```html
<a class="article-card" href="articles/nome-artista-nome-brano.html" data-artist="nome-artista">
  <div class="card-img">
    <img src="img/nome-immagine.webp" alt="Artista">
    <div class="card-img-overlay"></div>
    <div class="card-img-tag"><span class="tag">Artista</span></div>
  </div>
  <div class="card-body">
    <p class="card-meta">Album · Anno</p>
    <h3 class="card-title">Brano — Sottotitolo</h3>
    <p class="card-excerpt">Breve descrizione dell'analisi.</p>
    <div class="card-footer">
      <span class="card-read">Leggi analisi</span>
      <div class="card-arrow">→</div>
    </div>
  </div>
</a>
```

**4. Pubblica**

```bash
git add .
git commit -m "Aggiungo articolo: Nome Artista - Nome Brano"
git push origin main
```

GitHub Pages aggiornerà il sito in 1-2 minuti. Puoi monitorare la build dalla tab **Actions** su GitHub.

---

## 🛠️ Tecnologie

- HTML5
- CSS3 (variabili, grid, flexbox)
- JavaScript vanilla (filtri artisti)
- Google Fonts — Bebas Neue, DM Mono, Syne
- GitHub Pages per il deploy

---

## 📬 Contatti

- Instagram: [@vibemusic](https://instagram.com/vibemusic)
- Tidal: [@nicocrysa](https://tidal.com/@nicocrysa)

---

*Vibe Music — perché la musica è arte, e ogni arte merita di essere capita.*
