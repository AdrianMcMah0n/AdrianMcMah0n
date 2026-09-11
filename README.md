# Adrian McMahon

**Data Engineer - Web Data Acquisition, API Integration and ETL**

I build production data systems in Python: large-scale web-data acquisition, CRM
and ERP integrations, and the ETL and verification layers that turn messy public
and third-party sources into clean, queryable datasets on MongoDB.

Most of my day-to-day work is proprietary, so these repositories show selected,
sanitized parts of each system: the design, the hard engineering problems, and
representative code, with all credentials and full production logic left out.

## What I do

- **Web data acquisition at scale** - reverse-engineering undocumented back ends
  (signed JSON APIs, ASP.NET WebForms state, Angular and Laravel SPAs), captcha
  automation, rate-limit and WAF handling, proxy rotation, and pipelines that are
  idempotent, merge-safe and resumable.
- **API and CRM integration** - Flask and FastAPI services, webhooks, OAuth2, and
  client-side-encryption logins ported from JavaScript to Python, delivering clean
  lead and reporting data to non-technical teams.
- **Data engineering** - MongoDB schema design, canonical normalisation, entity
  resolution and fuzzy matching, and verification tooling that catches silent data
  loss (the kind that passes every structural check).
- **AI-augmented** - LLM APIs in production (classification, vision OCR, outreach
  drafting) with strict output validation and hallucination detection.

## Featured case studies

| Project | What it is |
|---|---|
| [rera-data-platform](https://github.com/AdrianMcMah0n/rera-data-platform) | 28-state regulatory data platform, about 265,000 records on MongoDB |
| [crm-lead-integrations](https://github.com/AdrianMcMah0n/crm-lead-integrations) | Lead and reporting integrations across 10+ CRM/ERP platforms |
| [binance-futures-trading-bot](https://github.com/AdrianMcMah0n/binance-futures-trading-bot) | Automated futures trading system with a walk-forward optimiser |
| [lead-intelligence-platform](https://github.com/AdrianMcMah0n/lead-intelligence-platform) | 14-module B2B lead-intelligence and AI-outreach pipeline |
| [court-case-tracker](https://github.com/AdrianMcMah0n/court-case-tracker) | Automated case monitoring across 750+ court portals |
| [rotating-proxy-pool](https://github.com/AdrianMcMah0n/rotating-proxy-pool) | Self-verifying rotating-proxy library with leak detection |

## Toolbox

Python, MongoDB, Pandas, Flask, FastAPI, Selenium, Playwright, BeautifulSoup,
Docker, SearXNG, OpenAI and Claude APIs, Tesseract and vision OCR, Google Sheets
and SMTP automation, Git.

## Reach me

- Kaggle: [kaggle.com/adrianmcmahon](https://www.kaggle.com/adrianmcmahon)
- Email: adrian_mac15@yahoo.com

> Note on code: these repositories contain selected, sanitized excerpts, not full
> production systems. Credentials and sensitive processing logic are deliberately
> omitted. Happy to walk through the full design and trade-offs on request.
