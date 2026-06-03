# reindexme ⚡

Infrastructure tool for search engine indexing updates.

ReIndexMe helps synchronize publicly available web content with search engines by leveraging existing indexing protocols such as IndexNow and sitemap submission workflows.

The goal is to reduce the delay between content updates and search engine re-crawling, improving the freshness of search results for updated web content.

🔗 Live service: https://reindexme.com

---

## 🧭 Overview

Search engines do not instantly detect when web content changes.

In many cases, updates to pages such as profiles, articles, or public information may take days or weeks to be reflected in search results.

ReIndexMe provides a simple interface to trigger indexing signals through supported search engine protocols, helping reduce this delay.

---

## ⚙️ How it works

ReIndexMe uses existing, publicly available indexing mechanisms:

| Step | Engine | Method | Estimated Time |
|------|--------|--------|----------------|
| 1 | Bing | IndexNow API | Minutes |
| 2 | Yandex | IndexNow API | ~24 hours |
| 3 | Google | Sitemap submission | Days |
| 4 | Google | URL inspection / indexing workflows | Days |

The system operates within existing search engine guidelines and does not bypass or manipulate indexing rules.

---

## 🔌 Integrations

ReIndexMe integrates with established search engine indexing systems:

- Bing IndexNow API
- Yandex IndexNow API
- Sitemap-based submission workflows
- Standard URL re-crawling mechanisms used by search engines

It is designed to complement existing SEO and indexing infrastructure.

---

## 🧩 Widget

ReIndexMe provides an embeddable widget that can be integrated into external websites.

```html
<iframe
  src="https://reindexme-widget.vercel.app"
  width="480"
  height="420"
  title="ReIndexMe widget"
  style="border:none;width:100%;max-width:480px;overflow:hidden;"
></iframe>

Widget documentation: https://reindexme.com/widget-demo.html

## 🚀 Production usage

ReIndexMe is a live service available at:

- https://reindexme.com
- embeddable widget for third-party websites

The system is designed for real-world usage rather than experimental or demo purposes.


## 🛠 Actively maintained

ReIndexMe is actively maintained with ongoing iterative development.

Current engineering focus includes:

- improving reliability of indexing workflows
- expanding support for additional search engine integrations
- improving widget stability and embeddability
- refining UI and user experience
- optimizing performance and load handling

## 🔒 Privacy

ReIndexMe follows a privacy-first design philosophy.

The service is intentionally built to minimize data collection and user tracking:

- No user accounts are required
- No cookies or tracking mechanisms are used
- No personal data is stored or processed beyond request handling
- Submitted URLs are processed transiently without persistent storage


## 🧱 Stack

- Vanilla HTML, CSS, and JavaScript
- Hosted on GitHub Pages
- Widget hosted on Vercel


## 📌 Design principles

ReIndexMe is built around a set of constraints focused on simplicity, openness, and usability:

- Uses existing open web standards where possible
- Avoids proprietary or closed indexing mechanisms
- Prioritizes simplicity and accessibility in design
- Does not collect or store user data
- Remains free and publicly accessible


## 📄 License

ReIndexMe uses a proprietary source code license.

The service is free to use and can be embedded in external websites with attribution.

For full licensing terms, see: https://reindexme.com/license.html
