# reindexme.com

🇬🇧 [English version available at reindexme.com](https://reindexme.com)

**Aiuta i motori di ricerca a riscoprire ciò che è cambiato.**

ReIndexMe è un progetto di Memmola Labs dedicato alla riscoperta dei contenuti aggiornati nei motori di ricerca.

Il progetto parte da un principio semplice:

**nessun account, nessuna verifica del dominio, nessun accesso permanente al sito e nessuna raccolta permanente degli URL.**

ReIndexMe comprende due percorsi principali:

- **LinkedIn Refresh** — per controllare un profilo LinkedIn aggiornato e verificarne la visibilità attuale nei motori di ricerca.
- **ReIndexMe Local Inspector** — estensione browser in sviluppo per analizzare localmente una pagina web e individuare segnali che possono influenzarne crawling, indicizzabilità e riscoperta.

🔗 **[reindexme.com/it](https://reindexme.com/it/)**

---

## LinkedIn Refresh

Hai aggiornato il tuo profilo LinkedIn ma Google o Bing mostrano ancora informazioni precedenti?

LinkedIn Refresh offre un workflow guidato per:

1. Verificare l'URL pubblico del profilo LinkedIn
2. Aprire e controllare il profilo aggiornato
3. Controllare la visibilità attuale su **Google**
4. Controllare la visibilità attuale su **Bing**
5. Aprire strumenti diagnostici ufficiali Google
6. Seguire azioni legittime che possono aiutare il profilo a essere riscoperto
7. Ricontrollare successivamente i risultati

ReIndexMe **non invia richieste di indicizzazione per linkedin.com** e non afferma di poter forzare Google, Bing o LinkedIn a effettuare nuovamente il crawl di un profilo.

I motori di ricerca decidono autonomamente quando e come aggiornare i propri risultati.

---

## ReIndexMe Local Inspector

**Local Inspector è attualmente in sviluppo.**

Sarà un'estensione browser progettata per analizzare la pagina che l'utente sta visualizzando, direttamente nel browser e solo quando viene richiesto.

L'obiettivo è aiutare a individuare segnali utili alla riscoperta di una pagina aggiornata, tra cui:

- indicizzabilità
- canonical
- title e meta description
- dati strutturati
- `dateModified`
- altri segnali tecnici rilevanti

Non sarà necessario creare un account ReIndexMe o verificare la proprietà del dominio.

Le estensioni per **Google Chrome** e **Microsoft Edge** saranno collegate al sito quando disponibili.

---

## Privacy by design

ReIndexMe è progettato per richiedere il minor livello di fiducia possibile all'utente.

Il workflow principale non richiede:

- account ReIndexMe
- verifica del dominio
- accesso permanente al sito
- installazione di file di verifica nella root del dominio
- raccolta permanente degli URL analizzati
- cookie di profilazione

Local Inspector è progettato per eseguire l'analisi della pagina attiva localmente nel browser quando l'utente la richiede.

---

## Struttura del repo

```text
reindexme/
├── index.html            # ReIndexMe principale (inglese)
├── widget-demo.html      # Widget e istruzioni embed (inglese)
├── license.html          # Licenza e condizioni (inglese)
├── it/
│   ├── index.html        # ReIndexMe principale (italiano)
│   ├── widget-demo.html  # Widget e istruzioni embed (italiano)
│   └── licenza.html      # Licenza e condizioni (italiano)
├── sitemap.xml
├── robots.txt
└── README.md

---

## Widget embeddabile

LinkedIn Refresh è disponibile anche come widget gratuito da incorporare in siti personali o commerciali.

Il widget permette agli utenti di utilizzare una versione compatta del workflow direttamente all'interno del sito ospitante.

iFrame
<iframe
  src="https://reindexme-widget.vercel.app/it/index.html"
  width="480"
  height="420"
  title="ReIndexMe LinkedIn Refresh widget"
  loading="lazy"
  style="border:0;width:100%;max-width:480px;overflow:hidden;"
></iframe>

Il widget non richiede account, configurazioni backend o integrazioni JavaScript con il sito ospitante.

→ Demo e istruzioni complete

Cosa ReIndexMe non fa

ReIndexMe non promette di:

forzare il crawling di Google o Bing
forzare l'indicizzazione o la re-indicizzazione
garantire tempi di aggiornamento
garantire ranking o presenza nei risultati di ricerca
inviare URL appartenenti a domini di terzi fingendo di controllarli

ReIndexMe fornisce invece analisi, controlli, diagnostica e percorsi trasparenti per capire meglio cosa può aiutare un contenuto aggiornato a essere riscoperto.

---

## Licenza

ReIndexMe è un progetto di Alessandro Memmola / Memmola Labs.

Il sito, l'interfaccia, il branding, la documentazione e il codice proprietario sono protetti salvo diversa indicazione.

Il widget ufficiale può essere incorporato gratuitamente su siti personali o commerciali mantenendo intatta l'attribuzione ReIndexMe / Memmola Labs e rispettando le condizioni della licenza.

→ Leggi la licenza completa

Memmola Labs

ReIndexMe è sviluppato da Memmola Labs, studio software indipendente creato da Alessandro Memmola.

🌐 memmolalabs.com
🌐 alessandromemmola.com
💻 GitHub
💼 LinkedIn
𝕏 Memmola Labs su X

---

## Supporta il progetto

ReIndexMe è disponibile gratuitamente.

Se vuoi contribuire allo sviluppo e al mantenimento del progetto:

❤️ Dona tramite PayPal
⭐ GitHub Sponsors

© 2026 Alessandro Memmola — Memmola Labs. Tutti i diritti riservati.
