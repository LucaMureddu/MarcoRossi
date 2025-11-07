# 📷 Marco Rossi - Urban Explorer (Web Performance Audit)

> [cite_start]Sito portfolio minimalista e ad altissima performance per un fotografo di strada[cite: 78]. [cite_start]Il design è interamente focalizzato sulle immagini, utilizzando un'interfaccia "invisibile" per non distrarre dal contenuto visivo[cite: 79].

*(Nota: Inserisci qui uno screenshot del sito)*

## 🚀 Live Demo

* [cite_start]**Guarda il portfolio live:** [https://marcorossi.netlify.app/](https://marcorossi.netlify.app/) [cite: 99]

## 🎯 Obiettivo del Progetto

[cite_start]Questo progetto è un esercizio di stile e ottimizzazione tecnica, creato per dimostrare la capacità di costruire layout eleganti, moderni e performanti[cite: 81]. [cite_start]L'obiettivo era padroneggiare le tecniche di **Web Performance** specifiche per i siti ricchi di contenuti multimediali [cite: 95][cite_start], garantendo un punteggio Lighthouse elevato nonostante il caricamento di numerose immagini ad alta risoluzione[cite: 96].

## ✨ Caratteristiche Tecniche e di Performance

* [cite_start]**Ottimizzazione Critica delle Immagini:** Utilizzo del tag `<picture>` (implicito con `srcset` e `sizes`) e attributi (`width`, `height`, `fetchpriority="high"`, `loading="eager"`) per garantire il caricamento rapido delle prime immagini e ridurre il CLS (Cumulative Layout Shift)[cite: 82, 83, 84].
* [cite_start]**Layout Masonry Avanzato:** Utilizzo di proprietà CSS `columns` per ottenere un layout dinamico e accattivante, che si adatta a 1, 2, 3 o 4 colonne a seconda della risoluzione[cite: 86].
* [cite_start]**Lazy Loading e CLS Mitigation:** Utilizzo di `loading="lazy"` per le immagini fuori dallo viewport iniziale e `content-visibility: auto` nel CSS per mitigare il CLS[cite: 87].
* [cite_start]**Light-Box Funzionale:** Galleria interattiva con Light-Box in Vanilla JS per la visualizzazione a schermo intero delle foto, inclusa la chiusura con il tasto Escape[cite: 88].
* [cite_start]**Design Minimalista & Mobile First:** L'interfaccia (header fisso con `backdrop-filter: blur(10px)`) è progettata per mettere in risalto il contenuto visivo[cite: 89].

## 💻 Tecnologie Utilizzate

* [cite_start]**HTML5:** Struttura semantica con enfasi sull'accessibilità delle immagini (tag `alt`)[cite: 91].
* [cite_start]**CSS3:** Layout Grid, Flexbox, Media Queries dettagliate e Performance CSS (`will-change`, `contain`)[cite: 92].
* [cite_start]**Vanilla JavaScript (ES6):** Implementazione della logica Lightbox e animazioni di caricamento iniziali[cite: 93].
