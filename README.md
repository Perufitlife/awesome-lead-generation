# Awesome Lead Generation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free and open-source lead generation tools, APIs, and resources for sales teams, marketers, and growth hackers.

If you find this list useful, please give it a star! Contributions are welcome - see [Contributing](#contributing).

---

## Contents

- [Free Lead APIs](#free-lead-apis)
- [Chrome Extensions](#chrome-extensions)
- [Python Libraries](#python-libraries)
- [Sales Tools](#sales-tools)
- [CRM Integrations and Open-Source CRMs](#crm-integrations-and-open-source-crms)
- [Email Finding and Verification](#email-finding-and-verification)
- [Data Enrichment](#data-enrichment)
- [Web Scraping Frameworks](#web-scraping-frameworks)
- [Cold Outreach Tools](#cold-outreach-tools)
- [Guides and Articles](#guides-and-articles)

---

## Free Lead APIs

APIs you can call to get leads and business data without enterprise contracts.

| API | Auth Required | Free Tier | Data Returned |
|-----|---------------|-----------|---------------|
| [LeadFinder API](https://leadscraper-coral.vercel.app/docs.html) | No | 10 req/day | Names, phones, addresses, ratings from Google Maps |
| [Google Places API](https://developers.google.com/maps/documentation/places/web-service) | API Key | $200/mo credit | Business details, photos, reviews |
| [Yelp Fusion API](https://docs.developer.yelp.com/docs/fusion-intro) | API Key | 5K req/day | Business info, reviews, photos |
| [OpenCorporates API](https://api.opencorporates.com/) | Optional | 500 req/mo | Company registrations worldwide |
| [Clearbit Logo API](https://clearbit.com/logo) | No | Unlimited | Company logos by domain |
| [FullContact API](https://www.fullcontact.com/) | API Key | 100/mo | Contact enrichment |
| [Abstract API](https://www.abstractapi.com/) | API Key | 100/mo | Email validation, company data |
| [People Data Labs](https://www.peopledatalabs.com/) | API Key | 100/mo | B2B contact data |
| [Hunter.io API](https://hunter.io/api) | API Key | 25 searches/mo | Email addresses by domain |

- [LeadFinder](https://leadscraper-coral.vercel.app) - Completely free Google Maps lead finder. No API key, no signup. Returns business names, phone numbers, addresses, and Google ratings. Best for quick local business prospecting. ([API Docs](https://leadscraper-coral.vercel.app/docs.html))
- [Company Social Profile Finder](https://apify.com/publicrecords/company-social-profile-finder) - Company domain or name to its LinkedIn, X, YouTube, Instagram and Facebook links, with confidence scores (Apify Actor, API + MCP).
- [Google Ads Transparency Scraper](https://apify.com/publicrecords/google-ads-transparency-scraper) - Google ads a competitor runs, from the Ads Transparency Center, with first and last shown dates (Apify Actor, API + MCP).
- [Ashby Jobs Scraper](https://apify.com/publicrecords/ashby-jobs-scraper) - New job postings from any Ashby job board since a date or window (24h, 7d, 30d) (Apify Actor, API + MCP).
- [Greenhouse Jobs Scraper](https://apify.com/publicrecords/greenhouse-jobs-scraper) - New job postings from any Greenhouse job board since a date or window (Apify Actor, API + MCP).
- [Lever Jobs Scraper](https://apify.com/publicrecords/lever-jobs-scraper) - New job postings from any Lever job board since a date or window (Apify Actor, API + MCP).
- [SmartRecruiters Jobs Scraper](https://apify.com/publicrecords/smartrecruiters-jobs-scraper) - New job postings from any SmartRecruiters careers site since a date or window (Apify Actor, API + MCP).

---

## Chrome Extensions

Browser extensions for prospecting and lead capture.

- [Hunter.io Extension](https://hunter.io/chrome) - Find email addresses on any website. Free tier available.
- [Apollo.io Extension](https://www.apollo.io/) - B2B contact database with LinkedIn integration.
- [Lusha](https://www.lusha.com/) - Find phone numbers and emails from LinkedIn profiles.
- [Wappalyzer](https://www.wappalyzer.com/) - Identify technologies used on websites (great for tech-based prospecting).
- [SimilarWeb](https://www.similarweb.com/apps/browser-extension/) - Website traffic estimates to qualify leads.
- [LinkedIn Sales Navigator](https://business.linkedin.com/sales-solutions/sales-navigator) - Advanced LinkedIn search and lead management.
- [Clearbit Connect](https://clearbit.com/connect) - Find emails and enrich contacts directly in Gmail.
- [RocketReach](https://rocketreach.co/) - Find emails and phone numbers. Free lookups available.
- [Skrapp.io](https://skrapp.io/) - LinkedIn email finder extension.
- [GetProspect](https://getprospect.com/) - LinkedIn lead generation with email finder.

---

## Python Libraries

Python packages for building custom lead generation pipelines.

- [Scrapy](https://scrapy.org/) - Fast, high-level web crawling framework for extracting structured data.
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - HTML/XML parsing library. Great for quick scraping scripts.
- [Selenium](https://selenium-python.readthedocs.io/) - Browser automation for scraping JavaScript-heavy sites.
- [Playwright for Python](https://playwright.dev/python/) - Modern browser automation by Microsoft. Faster than Selenium.
- [googlemaps](https://github.com/googlemaps/google-maps-services-python) - Official Python client for Google Maps Platform APIs.
- [python-linkedin](https://github.com/tomquirk/linkedin-api) - Unofficial LinkedIn API client for Python.
- [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parse, format, and validate phone numbers.
- [email-validator](https://github.com/JoshData/python-email-validator) - Robust email address validation.
- [pandas](https://pandas.pydata.org/) - Data manipulation essential for processing and deduplicating lead lists.
- [requests-html](https://github.com/psf/requests-html) - HTML parsing with JavaScript rendering support.

---

## Sales Tools

Platforms and tools for managing the sales process.

### Free / Freemium

- [HubSpot CRM](https://www.hubspot.com/products/crm) - Free CRM with contact management, deals, and email tracking.
- [Freshsales](https://www.freshworks.com/crm/sales/) - AI-powered CRM with free tier for small teams.
- [Streak](https://www.streak.com/) - CRM built into Gmail. Free for individuals.
- [Mailchimp](https://mailchimp.com/) - Email marketing with free tier (500 contacts).
- [Brevo (formerly Sendinblue)](https://www.brevo.com/) - Email marketing and CRM. 300 emails/day free.
- [Lemlist](https://www.lemlist.com/) - Cold email outreach with personalization.
- [Woodpecker](https://woodpecker.co/) - Cold email tool with follow-up automation.
- [Mixmax](https://www.mixmax.com/) - Email tracking and scheduling for Gmail.

### LinkedIn Tools

- [Dux-Soup](https://www.dux-soup.com/) - LinkedIn automation for lead generation.
- [Phantombuster](https://phantombuster.com/) - LinkedIn scraping and automation flows.
- [Expandi](https://expandi.io/) - Safe LinkedIn automation tool.
- [Octopus CRM](https://octopuscrm.io/) - LinkedIn automation and CRM.

### Lead Scoring

- [MadKudu](https://www.madkudu.com/) - Predictive lead scoring for B2B.
- [Leadfeeder](https://www.leadfeeder.com/) - Identify companies visiting your website.
- [Visitor Queue](https://www.visitorqueue.com/) - Website visitor identification.

---

## CRM Integrations and Open-Source CRMs

### Open-Source CRMs

- [SuiteCRM](https://suitecrm.com/) - Open-source CRM forked from SugarCRM. Full-featured.
- [EspoCRM](https://www.espocrm.com/) - Lightweight open-source CRM with modern UI.
- [Monica](https://www.monicahq.com/) - Personal relationship management (open-source).
- [Twenty](https://twenty.com/) - Modern open-source CRM. Building a Salesforce alternative.
- [ERPNext](https://erpnext.com/) - Open-source ERP with built-in CRM module.
- [Odoo CRM](https://www.odoo.com/app/crm) - Part of the Odoo suite. Community edition is free.

### Integration Platforms

- [Zapier](https://zapier.com/) - Connect 5,000+ apps. 100 tasks/mo free.
- [Make (formerly Integromat)](https://www.make.com/) - Visual automation platform. 1,000 ops/mo free.
- [n8n](https://n8n.io/) - Open-source workflow automation. Self-hostable.
- [Activepieces](https://www.activepieces.com/) - Open-source alternative to Zapier.

---

## Email Finding and Verification

- [Hunter.io](https://hunter.io/) - Find and verify email addresses. 25 free searches/mo.
- [Snov.io](https://snov.io/) - Email finder and drip campaigns. 50 free credits.
- [Voila Norbert](https://www.voilanorbert.com/) - Email finder with high accuracy.
- [Verify-Email](https://verify-email.org/) - Free email verification tool.
- [NeverBounce](https://neverbounce.com/) - Email list cleaning and verification.
- [ZeroBounce](https://www.zerobounce.net/) - Email validation with data enrichment.
- [EmailListVerify](https://emaillistverify.com/) - Bulk email verification at low cost.
- [Reacher](https://reacher.email/) - Open-source email verification.

---

## Data Enrichment

- [Clearbit](https://clearbit.com/) - Company and contact data enrichment.
- [People Data Labs](https://www.peopledatalabs.com/) - B2B data enrichment API.
- [FullContact](https://www.fullcontact.com/) - Identity resolution and enrichment.
- [Pipl](https://pipl.com/) - People search and identity verification.
- [Datanyze](https://www.datanyze.com/) - Technographics and contact data.
- [BuiltWith](https://builtwith.com/) - Website technology profiling.
- [SimilarTech](https://www.similartech.com/) - Technology market intelligence.

---

## Web Scraping Frameworks

Build your own lead generation scrapers.

- [Apify](https://apify.com/) - Cloud platform for web scraping and automation. Pre-built scrapers available.
- [Crawlee](https://crawlee.dev/) - Web scraping and browser automation library by Apify.
- [Scrapy](https://scrapy.org/) - Python framework for large-scale scraping.
- [Puppeteer](https://pptr.dev/) - Node.js library for controlling headless Chrome.
- [Playwright](https://playwright.dev/) - Cross-browser automation by Microsoft.
- [Colly](https://go-colly.org/) - Fast scraping framework for Go.
- [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - Python library for automating websites.
- [Cheerio](https://cheerio.js.org/) - Fast HTML parsing for Node.js (no browser needed).

---

## Cold Outreach Tools

- [Lemlist](https://www.lemlist.com/) - Personalized cold email with images and video.
- [Instantly.ai](https://instantly.ai/) - Scale cold email with unlimited accounts.
- [Smartlead](https://www.smartlead.ai/) - Cold email infrastructure with warmup.
- [Mailshake](https://mailshake.com/) - Sales engagement and cold email platform.
- [Reply.io](https://reply.io/) - Multichannel sales engagement.
- [Salesloft](https://www.salesloft.com/) - Enterprise sales engagement platform.
- [Outreach.io](https://www.outreach.io/) - Sales execution platform.
- [Cold Outreach Templates](https://github.com/Perufitlife/cold-outreach-templates) - 50+ free cold email and cold call templates.

---

## Guides and Articles

### Lead Generation Strategy

- [The Ultimate Guide to Local Business Lead Generation](https://leadscraper-coral.vercel.app/blog/ultimate-guide-local-business-leads) - Complete guide to finding and converting local business leads.
- [How to Find Business Leads Using Google Maps](https://leadscraper-coral.vercel.app/blog/google-maps-lead-generation-guide) - Step-by-step guide to extracting leads from Google Maps.
- [Cold Email That Actually Works](https://leadscraper-coral.vercel.app/blog/cold-email-templates-local-businesses) - Templates and strategies for cold outreach.
- [HubSpot Lead Generation Guide](https://blog.hubspot.com/marketing/beginner-inbound-lead-generation-guide-ht) - Comprehensive inbound lead gen guide.
- [Sales Hacker](https://www.saleshacker.com/) - Community and resources for B2B sales professionals.
- [Close.io Blog](https://blog.close.com/) - Practical sales advice and strategies.

### Building Lead Gen Tools

- [How to Build a Web Scraper with Playwright](https://playwright.dev/docs/intro) - Official Playwright documentation.
- [Apify Academy](https://docs.apify.com/academy) - Free courses on web scraping and automation.
- [ScrapingBee Blog](https://www.scrapingbee.com/blog/) - Tutorials on web scraping techniques.

### Books

- *Predictable Revenue* by Aaron Ross - The outbound sales playbook.
- *Fanatical Prospecting* by Jeb Blount - Prospecting strategies that work.
- *New Sales. Simplified.* by Mike Weinberg - Essential sales prospecting.
- *The Sales Development Playbook* by Trish Bertuzzi - Building SDR teams.
- *Hacking Sales* by Max Altschuler - Modern tools and techniques for sales.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

- Add tools you have personally used or can vouch for
- Keep descriptions concise (1-2 sentences)
- Place new entries at the end of their category
- Check for duplicates before adding

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
