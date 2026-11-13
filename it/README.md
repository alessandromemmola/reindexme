# ReIndixMe

[Versione italiana disponibile su reindexme.com/it](https://reindexme.com/it/)

**Aiuta i motori di ricerca a riscoprire cosa è cambiato.**

ReIndexMe è un progetto Memmola Labs focalizzato sull'aiutare gli utenti a capire se i contenuti online aggiornati siano pronti per essere riscoperti dai motori di ricerca.

Il progetto si basa su un semplice principio:

**no account ReIndexMe, nessuna verifica del dominio, nessun accesso permanente al sito web e nessuna raccolta permanente di URL.**

ReIndexMe include attualmente due percorsi principali:

- **LinkedIn Refresh** ☐ un flusso di lavoro guidato per controllare un profilo aggiornato del pubblico LinkedIn e la sua visibilità attuale nei motori di ricerca.
- **ReIndexMe Local Inspector** Un'estensione del browser in sviluppo per l'ispezione locale delle pagine web e l'identificazione dei segnali che possono influenzare la striscia, l'indicizzazione e la riscoperta.

🔗 **[reindexme.com](https://reindexme.com)**

---

Rilascio ##

Ultima versione: [v1.0.0](https://github.com/alessandromemmola/reindexme/releases/tag/v1.0.0)

ReIndexMe è attivamente mantenuto ed evolve oltre la versione originale messa a fuoco di LinkedIn.

---

Servizio ## in diretta

Sito web:

https://reindexme.com

Versione italiana:

https://reindexme.com/it/

Demo widget:

https://reindexme.com/widget-demo.html

Demo widget italiano:

https://reindexme.com/it/widget-demo.html

---

## Screenshots Ispettore locale

[ReIndexMe screenshot](assets/1.png)  
![ReIndexMe screenshot](assets/2.png)  
![ReIndexMe screenshot](assets/3.png)  
![ReIndexMe screenshot](assets/4.png)  
[ReIndexMe screenshot](assets/5.png)  
![ReIndexMe screenshot](assets/6.png)  
![ReIndexMe screenshot](assets/7.png)

---

## ReIndexMe Ispettore locale

**Versione:**__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

ReIndexMe Local Inspector è un'estensione del browser per Google Chrome e Microsoft Edge che controlla la pagina web ** corrente solo quando l'utente lo richiede**. Aiuta i proprietari di siti web, sviluppatori e creatori di contenuti identificare segnali in pagina che possono influenzare la scoperta e l'indicizzazione della ricerca.

### Che cosa controlla

- Titolo della pagina e meta descrizione, compresa la guida di lunghezza approssimativa.
- direttive sui robot on-page (ad esempio,
- Dichiarazioni URL canoniche.
- Struttura della rubrica H1 e linguaggio del documento.
- presenza e sintassi dei dati strutturati JSON-LD.
- Open Graph e altri metadati social-sharing.
- Disponibilità di testo alternativo.
- Dichiarazioni di Hreflang e suggerimenti di modifica.
- Collegamenti interni ed esterni.

### Come funziona

1. Aprire una pagina web regolare in Chrome o Bordo.
2. Fare clic sull'icona dell'estensione ReIndexMe Local Inspector per ispezionare la pagina attiva.
3. Rivedere il punteggio **0.0.100 sulla pagina del segnale** e le spiegazioni di
4. Usare **Copiare il rapporto** per copiare i risultati del testo negli appunti, se necessario.
5. Aprire i controlli manuali suggeriti separatamente quando è necessario indagare i segnali lato server.

Il punteggio è un **indicativo diagnostica on-page**, non una classifica di ricerca, probabilità di indicizzazione, o garanzia di visibilità del motore di ricerca.

### Elaborazione e autorizzazioni locali

Local Inspector v0.1.0 usa i permessi del browser **

- Un account ReIndexMe o la verifica della proprietà del sito.
- Persistente accesso ai siti web o cronologia di navigazione.
- Analytics, tracker pubblicitari, o un backend di ispezione remoto.
- Conservazione permanente di URL o rapporti controllati.

L'azione **Copy report** scrive agli appunti di sistema solo quando l'utente lo richiede. Vedere la [Local Inspector Privacy Policy](https://reindexme.com/local-inspector-privacy.html) per i dettagli.

### Cosa non verifica

L'estensione non verifica in modo indipendente i codici di risposta del server, le intestazioni di risposta dei robot-Tag dei robot, le restrizioni dei robot.txt, la disponibilità della mappa del sito, o se Google o Bing hanno indicizzato una pagina. Alcune di queste possono essere aperte per **controlli manuali**, ma non sono incluse come risultati verificati in pagina.

**Disponibilità:** I pacchetti v0.1.0 sono stati presentati per la revisione nel novembre 2026. I link al negozio saranno aggiunti qui **dopo l'approvazione e la pubblicazione**. La presentazione non è un'approvazione o un rilascio pubblico.

**Scope del deposito:** Il repository esistente documenta principalmente e ospita il sito web di ReIndexMe. Il pacchetto di estensione Local Ispettore è un componente separato; la sua fonte non dovrebbe essere considerata inclusa in questo repository fino a quando non è stata effettivamente impegnata qui. I termini di licenza per il sito web e l'estensione sono regolati dai rispettivi materiali distribuiti.

---

Aggiorna ## collegato

Avete aggiornato il vostro profilo LinkedIn mentre Google o Bing mostra ancora le informazioni più vecchie?

LinkedIn Refresh fornisce un flusso di lavoro guidato a:

1. Convalida l'URL del profilo di LinkedIn pubblico
2. Aprire e verificare il profilo pubblico aggiornato
3. Controllare la sua visibilità attuale su **Google**
4. Controllare la sua visibilità attuale su **Bing**
5. Aprire strumenti diagnostici ufficiali di Google
6. Seguire le azioni di scoperta legittime che possono aiutare il profilo aggiornato essere riscoperto
7. Ricontrollare i risultati della ricerca più tardi

ReIndexMe **non presenta richieste di indicizzazione per linkedin.com** e non pretende di costringere Google, Bing, LinkedIn o qualsiasi altra terza parte a recrawl un profilo.

I motori di ricerca decidono autonomamente quando e come i loro risultati sono strisciati, indicizzati e aggiornati.

---

## Privacy by Design

ReIndexMe è progettato per richiedere il minor numero possibile di fiducia aggiuntiva all'utente.

Il flusso di lavoro principale non richiede:

- un account ReIndexMe
- verifica della proprietà del dominio
- accesso permanente al sito web
- file di verifica installati nella root dominio
- raccolta permanente di URL controllati
- cookie di profilazione

Local Inspector è progettato per ispezionare la pagina attiva localmente nel browser quando richiesto dall'utente.

---

Struttura del deposito ##

Testo in italiano
reindexme/
Sito web ReIndexMe principale (inglese)
widget-demo.html # Widget demo e incorporare le istruzioni (Inglese)
Licenza.html # Licenza e termini (Inglese)
it/
Sito web ReIndexMe
Widget-demo.html # Widget demo e incorporare le istruzioni
Licenza.html # Licenza e termini (Italiano)
Sitemap.xml
Robots.txt
...
evento

> Il codice sorgente del widget incorporato viene ospitato separatamente e distribuito tramite [reindexme-widget.vercel.app](https://reindexme-widget.vercel.app).

---

Widget incorporabile ##

LinkedIn Refresh è disponibile anche come widget ** libero embeddable** per siti web personali e commerciali.

Il widget fornisce una versione compatta del flusso di lavoro LinkedIn Aggiorna direttamente all'interno del sito web dell'host.

### iFrame

N. CAS: 97-77-4
<iframe
  src="https://reindexme-widget.vercel.app/index.html"
  larghezza="480"
  altezza="420"
  titolo="ReIndexMe LinkedIn Aggiorna widget"
  loading="lazy"
  style="border:0;width:100%;max-width:480px;overflow:hidden;"
> </iframe>
evento

Il widget non richiede alcun account ReIndexMe, configurazione backend o integrazione JavaScript con il sito web host.

→ [Visualizza la demo e le istruzioni complete](https://reindexme.com/widget-demo.html)

---

## Cosa ReIndixMe non fa

ReIndexMe non promette:

- forzare Google o Bing a strisciare un URL
- indicizzazione o riindicizzazione della forza
- tempi di aggiornamento della garanzia
- garantire la classifica o la visibilità dei risultati della ricerca
- inviare URL appartenenti a domini di terze parti fingendo di controllarli

ReIndexMe fornisce invece **ispezioni, diagnostica, controlli di visibilità e flussi di lavoro trasparenti** per aiutare gli utenti a capire cosa può aiutare a riscoprire i contenuti aggiornati.

---

Obiettivi del progetto ##

ReIndexMe è costruito intorno ad una piccola serie di principi guida:

- semplicità rispetto alla complessità
- privacy per progettazione
- comportamento trasparente
- nessuna indicazione fuorviante dell'indicizzazione
- requisiti minimi di infrastruttura
- la trasformazione locale ogniqualvolta sia pratica
- la manutenzione a lungo termine

L'obiettivo non è quello di sostituire Google Search Console, Bing Webmaster Tools, LinkedIn, o piattaforme professionali SEO.

ReIndexMe si concentra su una domanda più ristretta:

**Quanto possiamo aiutare a riscoprire una pagina o un profilo aggiornati senza chiedere all'utente ulteriori fiducia?**

---

Licenza ##

ReIndexMe è un progetto di Alessandro Memmola Labs**.

Il sito web, l'interfaccia originale, il marchio, la documentazione e il codice proprietario sono protetti, salvo indicazione contraria.

Il widget ufficiale può essere incorporato gratuitamente su siti web personali o commerciali a condizione che l'attribuzione di ReIndexMe / Memmola Labs rimanga intatta e che i termini di licenza attuali siano rispettati.

→ [Leggi la licenza completa](https://reindexme.com/license.html)

---

Laboratori di Memmola ##

ReIndexMe è stato sviluppato da **Memmola Labs**, uno studio di software indipendente creato da Alessandro Memmola.

🌐 [memmolalabs.com](https://memmolalabs.com)  
🌐 [alessandromemmola.com](https://alessandromemmola.com)  
💻 [GitHub](https://github.com/alessandromemmola)  
💼 [LinkedIn](https://www.linkedin.com/in/alessandro-memmola-233868372/)  
X [Memmola Labs on X](https://x.com/MemmolaLabs)

---

## Supporta il progetto

ReIndexMe è disponibile gratuitamente.

Se desideri supportarne lo sviluppo e la manutenzione:

❤️ [Donare tramite PayPal](https://www.paypal.com/donate/?hosted_button_id=BDKSZVWFYY5ZL)  
[Sponsor GitHub](https://github.com/sponsors/alessandromemmola)

---

© 2026 Alessandro Memmola Labs. Tutti i diritti riservati.
