# 🚀 Infinite-Crawl Stealth Engine

A high-performance web automation tool built with **Python** and **Playwright**. This system is designed to navigate complex paginated directories while remaining undetected by modern anti-bot fingerprints.

## 🛠️ Technical Highlights
- **Playwright Stealth:** Uses advanced browser-level spoofing to bypass `navigator.webdriver` detection.
- **Atomic Data Flushing:** Implements `f.flush()` after every page scrape to ensure zero data loss during long-running tasks.
- **Human-Behavior Emulation:** Includes randomized mouse-wheel scrolling and jittered delays (12s-18s) to mimic real user interaction.
- **Asynchronous Loop:** Efficiently handles multiple geographical targets sequentially with safety cooldowns.

## 📂 Project Structure
- `infinite_crawl.py`: The core automation engine.
- `index.html` & `style.css`: The professional storefront built for the global tech market.

## 🚀 How to Run
1. Install requirements: `pip install playwright pandas playwright-stealth`
2. Run the script: `python infinite_crawl.py`
