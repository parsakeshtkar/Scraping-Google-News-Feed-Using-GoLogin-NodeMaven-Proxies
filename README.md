<h1 align="center">📰 Scraping Google News Feed Using GoLogin & NodeMaven Proxies</h1>

## 📚 Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
    - [Future Enhancements](#future-enhancements)
3. [Requirements](#requirements)
4. [Usage Examples](#usage-examples)
   - [Setup and Installation Instructions](#setup-and-installation-instructions)
5. [Troubleshooting Tips](#troubleshooting-tips)
6. [Contribution Guidelines](#contribution-guidelines)


## Project Overview
This tool is crafted for efficiently scraping the **entire Google News feed**, organizing the data into a clean and structured table. Each row includes:
- The **news source’s website name**
- A direct **URL to the original article**

Whether you're building a media tracker, sentiment analyzer, or just need fresh, organized headlines—this scraper has you covered.

## Features
- 📰 **Full Feed Scraper** – Capture articles across multiple categories in real time.
- 🔎 **Structured Output** – Get brand names and article URLs neatly formatted.
- 🧠 **Smart Parsing** – Handles edge cases and dynamic elements in the Google News DOM.
- 🛡️ **GoLogin Integration** – Browser fingerprinting protection for high-volume scraping.
- 🌐 **NodeMaven Proxies** – Fast, secure proxies for anonymous scraping at scale.
- 📈 **Scalable Architecture** – Scrape hundreds of entries without detection or rate-limits.


## Future Enhancements
- 🧩 NLP Layer: Extract and analyze article summaries or sentiment.
- 🌍 Region Filters: Scrape by geography or language.
- 🧠 AI Tagging: Auto-classify articles by topic using LLMs.
- 🕒 Scheduler: Background cron support for hourly/daily scraping.


## Requirements
- Python 3.x
- Selenium or Playwright
- GoLogin Account & Browser Profiles
- NodeMaven Proxy Subscription


## Usage Example

```python
from news_scraper import GoogleNewsScraper

scraper = GoogleNewsScraper(gologin_profile='my_profile_id', proxy='http://user:pass@proxy')
articles = scraper.fetch()
for item in articles:
    print(f"Source: {item['brand']} | URL: {item['link']}")
```


## Setup & Installation
1. Clone the repo.
2. Install requirements:
```pip install -r requirements.txt```

3. Set your GoLogin API and NodeMaven proxy settings in ```config.py```
4. Run the script:
```python scrape_google_news.py```

## Troubleshooting
- ❌ **Blank Pages?** — Check if your GoLogin session is loading pages properly.
- 🔄 **Captcha Loop?** — Switch proxies or increase delay between requests.
- ⚠️ **Wrong Brand Names?** — Google’s structure may change—update the XPaths.


## Contribution Guidelines
If you're into clean data, stealth scraping, or automation magic—feel free to contribute.
1. Fork this repo
2. Add your feature or fix.
3. Submit a pull request with a quick explanation.

We especially welcome contributors with:
- Experience using GoLogin or Puppeteer Stealth.
- News aggregation or media monitoring projects under their belt.

## Exclusive NodeMaven Proxy Offers
Boost your scraping power with trusted residential proxies:
- ```BB2``` – Get **+2 GB free** with any plan (except trial)
- ```BB50``` – Score a **50% discount** on any package (limited to 20 uses!)
- ```BB80``` – Supercharge your data flows with **+80% traffic**

🎯 [Use this referral link to claim your perks](https://nodemaven.com/?a_aid=Zeeshanahmad4)


