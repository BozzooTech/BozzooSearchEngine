# Bozzoo Search Engine 🧅

**🌐 Official Address:** `http://bozzookr2v4kxgjszl7gcjheljhugkqsbxoaowtdfsdhqbhwoua6exid.onion`

**Bozzoo** is a high-performance, privacy-first search engine built specifically for indexing the Tor network (.onion sites). We provide the dark web with professional-grade relevancy, blistering fast indexing, and uncompromising  protection.

---

## 🚀 Why Bozzoo?

The Deep Web has historically been plagued by slow search aggregators, dead links, and pages cluttered with scams. **Bozzoo changes everything.**

### How We Compare to the Competition:
Most current onion search engines rely on primitive partial-keyword matching and rarely update their databases. Bozzoo introduces enterprise-grade search architecture to the Tor network:

1. **BM25 Relevance Engine:** Unlike legacy competitors that show irrelevant pages just because they contain a single matching keyword, Bozzoo uses a mathematical relevance model that handles term frequency and document saturation. What you search for is ranked by true topical relevance.
2. **99.9% Live Links:** Bozzoo features an optimized, asynchronous SOCKS5 ping worker tuned for maximum reliability. If an onion site goes offline, it is flagged in our index. You will rarely click a dead link again.
3. **Advanced Architecture:** Utilizing segregated MongoDB clusters, Redis caching, and scalable Celery crawl workers, our engine processes thousands of queries with sub-20ms latency.

---

## 🛡️ Uncompromising Abuse & Scam Protection

The safety of our users is our absolute highest priority. The dark web is dangerous, but searching it shouldn't be.

- ** Report Filtering:** Bozzoo features an integrated user-reporting mechanism. If a site is reported as a scam or abusive by the user, our backend adjusts its internal Trust Score.
- **Maximum Blocking:** If a malicious unverified site exceeds our strict reporting thresholds, the Bozzoo engine completely **excises and permanently blocks** the URL from the database autonomously.
- **Clean Index Guarantee:** We strictly quarantine abusive platforms to ensure your search results remain clean and legitimate.

---

## 🤖 Autonomous Bot Management

Bozzoo handles operations at scale without manual administrative intervention. Our backend is governed by interconnected python bots built into our task queues:

- **The Harvester Spider:** A recursive data-mining bot that accepts a seed URL and automatically discovers interconnected Tor links.
- **The Ring Blocker:** A cyber-defense script integrated into the API. When an abusive domain exceeds reporting thresholds, the API triggers a background worker that autonomously proxies into the reported domain, scans for outbound links, and purges the entire interconnected "Scam Ring" from our database.
- **The Optimized Health Pinger:** A resource-efficient bulk pinger that ensures the directory stays fresh without saturating server resources or Tor circuits.

---

## ✨ Features
* **Visual Transparency:** Search results display real-time **Visitor Counts** and ** Trust Scores**. See if a site is vetted by the  *before* you visit it.
* **Lightning Fast:** Sub-millisecond local Redis query caching.
* **Smart Crawling:** Celery queue automatically traverses new submissions, validates `.onion` formats, and intelligently determines page health.
* **Privacy First:** We don't track your IP. We don't store your history. No registration required.
* **100% Free:** No ads, no tracking, no cost.

---

## 💎 Help Us Grow

Bozzoo is a project built to clean up and modernize exploration on the Tor network. Our goal is to maintain a high-quality, free directory that anyone can use.

### How you can contribute:
1. **Submit Sites:** If you know a legitimate .onion site that isn't indexed, submit it today.
2. **Report Scams:** Help keep the index clean by reporting malicious or dead sites.
3. **Become a Sponsor:** Running a high-performance search engine requires server resources. Any support helps keep Bozzoo Search free and online for everyone.

**☕ Buy Me a Coffee:** [buymeacoffee.com/bozzoosearch](https://www.buymeacoffee.com/bozzoosearch)

**💰 Bitcoin (BTC):** `bc1qqd7xeannn0ec8azp7xldc95q05uxfu7nlkkjzt`

---
*Developed by Bozzoo Tech Solutions.*
