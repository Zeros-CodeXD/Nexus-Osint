# 🌐 NEXUS OSINT
**Advanced B2B Lead Harvester & Deep Intel Forensics Engine**

NEXUS OSINT is a high-concurrency, asynchronous reconnaissance suite built for modern data extraction and identity correlation. Engineered with Python, `aiohttp`, and a dark-themed `customtkinter` interface, it merges rapid lead generation with deep-dive forensic capabilities without triggering rate limits or UI freezing.

---

## 🚀 Core Modules

* **Domain Lead Harvester:** Asynchronous static HTML scraping engine. Bypasses standard bot-detection using randomized User-Agents and execution jitter. Extracts and deduplicates emails and international phone formats instantly.
* **The Identity Matrix:** Cross-references target usernames across 20+ major social networks and developer platforms simultaneously using zero-payload HTTP `HEAD` requests.
* **EXIF Forensics:** Deep-dive metadata stripper for local images. Extracts camera hardware, software history, and embedded GPS coordinates, dynamically converting them into actionable map links.
* **Archive Recon:** Interrogates the Internet Archive (Wayback Machine) CDX API to retrieve the absolute oldest and newest available snapshots of a target URL, bypassing modern page deletions.
* **Stealth Manager:** Built-in defensive layer handling concurrent semaphore limits, connection pooling, and payload anonymization to prevent IP flagging.
* **Payload Exporter:** One-click compilation of messy extraction dicts into clean, flat CSV files for client delivery or CRM integration.

---

## 💻 Tech Stack

* **Core:** Python 3.10+
* **Concurrency:** `asyncio`, `aiohttp`, `threading`
* **Parsing & Forensics:** `BeautifulSoup4`, `re`, `Pillow` (PIL)
* **GUI Architecture:** `customtkinter` (Windows 11 / Fluent Design aesthetic)

---

## ⚙️ Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/zeros-codexd/nexus-osint.git](https://github.com/zeros-codexd/nexus-osint.git)
cd nexus-osint
pip install customtkinter aiohttp beautifulsoup4 pillow
🕹️ Usage
Launch the GUI dashboard:

Bash
python NexusV2.py
Best Practices for Lead Harvesting
Feed the Harvester direct, static URLs (e.g., local business domains, directories).

Avoid single-page applications (SPAs) or login-walled targets (like LinkedIn or Facebook), as the aiohttp engine is optimized for speed over JavaScript rendering.

Utilize the Identity Matrix for hunting specific handles across heavily protected social media firewalls.

⚠️ Legal & Ethical Disclaimer
NEXUS OSINT is built strictly for educational purposes, authorized reconnaissance, and legal B2B lead generation. > Users are solely responsible for ensuring their actions comply with local data privacy laws (such as GDPR or CCPA) and the robots.txt or Terms of Service of target domains. The developers assume no liability for misuse, IP bans, or unauthorized data extraction.
