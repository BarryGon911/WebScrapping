# Playwright_WebScraping

Web Scraping, Automation, and CAPTCHA Solving with Playwright + Web Unlocker

## Recommended Environment Setup

```
>> conda create -n env_name python=3.11
>> conda activate env_name
>> pip install pytest-playwright
>> playwright install
>> playwright install-deps
```

## Files

- **pw_quickstart.py** includes a basic Playwright syntax of navigating to a web page and fetching its source code, title and screenshot.
- **pw_CAPTCHA.py** includes a basic implementation of a CAPTCHA solving mechanism named Web Unlocker, by Bright Data.
- **PDF_scraper.py [coming soon...]** web scrapes keyword-based research papers from Arxiv.org and automatically downloads them to a local machine.
