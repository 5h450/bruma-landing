# Bruma — Landing page

Landing page one-page per **Bruma**, una piccola torrefazione artigianale immaginaria.
Realizzata in HTML, CSS e JavaScript puri, senza build step né dipendenze.

## Anteprima

Apri `index.html` nel browser, oppure avvia un server locale:

```bash
python3 -m http.server 4173
# http://localhost:4173
```

## Contenuto

- Header sticky con navigazione e call to action
- Hero con claim, immagine e numeri chiave
- Striscia dei punti di forza
- Tre card su metodo e filiera
- Citazione dei fondatori
- Form newsletter con validazione email lato client
- Footer minimale

## Dettagli tecnici

- Layout responsive con CSS Grid, nessun overflow orizzontale
- Animazioni di reveal on-scroll con rispetto di `prefers-reduced-motion`
- Palette crema / inchiostro / terracotta
- Font: Fraunces e Inter (Google Fonts)
- Immagini placeholder da [placehold.co](https://placehold.co)
- Lighthouse: 100 Accessibilità, 100 Best Practices, 100 SEO

## Struttura

```text
.
├── index.html
└── README.md
```

## Licenza

Progetto dimostrativo. Testi, marchio e persona di Bruma sono di fantasia.
