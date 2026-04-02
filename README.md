# Bozzoo Search Engine 🧅

**🌐 Official Address:** `http://bozzookr2v4kxgjszl7gcjheljhugkqsbxoaowtdfsdhqbhwoua6exid.onion`

**Bozzoo** is a high-performance, privacy-first search engine built specifically for indexing the Tor network (.onion sites). We provide the dark web with surface-web (Google/Bing) level relevancy, blistering fast indexing, and uncompromising community protection against malicious actors.

---

## 🚀 Why Bozzoo?

The Deep Web has historically been plagued by slow search aggregators, dead links, and pages cluttered with scams. **Bozzoo changes everything.**

### How We Compare to the Competition:
Most current onion search engines rely on primitive partial-keyword matching and rarely update their databases. Bozzoo introduces enterprise-grade search algorithms to the Tor network:

1. **Google-Grade Search Relevancy:** Unlike legacy competitors that show irrelevant pages just because they contain a single matching keyword, Bozzoo uses highly-weighted **Boolean AND logic** overlaid with custom Trust, Popularity, and Exact-Phrase Multipliers. What you search for is *exactly* what you get.
2. **Zero Dead Links:** Bozzoo features a massive 50-concurrency asynchronous SOCKS5 ping worker running constantly in the background. If an onion site goes offline, it is stripped from search results instantly. You will never click a dead link again.
3. **Advanced Architecture:** Utilizing dual-segregated MongoDB clusters asynchronously accessed through FastAPI, and powered by Redis caching and scalable Celery crawl workers, our engine processes thousands of queries in sub-20ms latency.

---

## 🛡️ Uncompromising Abuse & Scam Protection

The safety of our users is our absolute highest priority. The dark web is dangerous, but searching it shouldn't be.

- **Community Report Filtering:** Bozzoo features an integrated user-reporting mechanism. If a site is reported as a scam or abusive by the community, our backend instantly slashes its internal Trust Score.
- **Maximum Blocking:** If a malicious unverified site exceeds our strict reporting thresholds, the Bozzoo engine completely **excises and permanently blocks** the URL from the database autonomously.
- **Clean Index Guarantee:** Unlike competitors who profit off sponsored scam links, we strictly quarantine abusive platforms to ensure your search results remain clean and legitimate.

---

## ✨ Features
* **Visual Transparency:** Every search result prominently displays real-time **Visitor Counts** and **Community Trust Scores**. See if a site is heavily vetted and trusted by the community *before* you expose yourself to visiting it.
* **Lightning Fast:** Sub-10 millisecond local Redis query caching.
* **Smart Crawling:** Celery queue automatically traverses new submissions, validates `.onion` formats, and intelligently determines page health.
* **Privacy First:** We don't track your IP. We don't store your history. Session tokens are uniquely hashed, zero-knowledge, and temporary.
* **Vector Ready:** Future-proofed with FAISS vector embedding architecture to eventually support semantic AI search. 

---

## 💎 Support & Donations

Bozzoo is a passion project built to clean up and modernize exploration on the Tor network. Server costs for multi-cluster databases, Tor routing proxies, and cloud hostings are incredibly expensive while we refuse to sell ads to spammers.

If you believe in our mission of providing a fast, scam-free, and highly accurate dark web search engine, please consider supporting our development! Your donations keep the servers running and our crawlers active.

**☕ Buy Me a Coffee:** [buymeacoffee.com/bhumasai](https://www.buymeacoffee.com/your-username)
**💰 Bitcoin (BTC):** `bc1qqd7xeannn0ec8azp7xldc95q05uxfu7nlkkjzt`

*(If you are an enterprise sponsor or wish to acquire a legitimate sponsored indexing slot, please use the Contact form on our platform).*
