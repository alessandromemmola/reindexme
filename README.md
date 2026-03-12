# reindexme.com

**Forza i motori di ricerca a ri-scansionare il tuo profilo LinkedIn.**

Hai aggiornato la tua posizione su LinkedIn ma Google mostra ancora quella vecchia? reindexme invia segnali di re-indicizzazione a Bing, Yandex e Google per accelerare l'aggiornamento — senza registrazione, senza cookie, direttamente dal browser.

🔗 **[reindexme.com](https://reindexme.com)**

---

## Come funziona

1. Inserisci l'URL del tuo profilo LinkedIn
2. Il tool invia automaticamente ping a **Bing IndexNow** e **Yandex IndexNow**
3. Fornisce link diretti agli strumenti ufficiali Google per forzare il re-fetch
4. Suggerisce il boost organico tramite condivisione su LinkedIn

Aggiornamento atteso: **24–72h** su Bing · **3–10 giorni** su Google.

---

## Struttura del repo

```
reindexme/
├── index.html        # Tool principale
├── widget-demo.html  # Pagina demo del widget embeddabile
├── licenza.html      # Licenza d'uso sito + widget
└── README.md
```

> Il codice sorgente del widget embeddabile è ospitato in un repo privato e deployato su [widget.reindexme.com](https://widget.reindexme.com).

---

## Widget embeddabile

reindexme è disponibile come widget gratuito da integrare su qualsiasi sito, personale o commerciale.

**iFrame**
```html
<iframe
  src="https://widget.reindexme.com/index.html"
  width="480"
  height="420"
  frameborder="0"
  title="reindexme LinkedIn profile tool"
  style="border:none;width:100%;max-width:480px;overflow:hidden;"
></iframe>
```

**Script tag**
```html
<div id="reindex-widget-container"></div>
<script>
  (function() {
    var s = document.createElement('script');
    s.src = 'https://widget.reindexme.com/widget.js';
    s.dataset.container = 'reindex-widget-container';
    document.head.appendChild(s);
  })();
</script>
```

→ [Vedi la demo e le istruzioni complete](https://reindexme.com/widget-demo.html)

---

## Licenza

Il sito e i suoi contenuti sono di proprietà di **Alessandro Memmola** — tutti i diritti riservati.  
Il widget è concesso in licenza gratuita per l'embed su qualsiasi sito a condizione che il branding rimanga intatto.

→ [Leggi la licenza completa](https://reindexme.com/licenza.html)

---

## Autore

**Alessandro Memmola**  
[alessandromemmola.com](https://alessandromemmola.com) · [LinkedIn](https://www.linkedin.com/in/alessandro-memmola-233868372/) · [GitHub](https://github.com/alessandromemmola) · [X](https://x.com/alexmemmola)

Se reindexme ti è stato utile, puoi supportare il progetto:  
❤️ [paypal.me/onlycreator](https://paypal.me/onlycreator)
