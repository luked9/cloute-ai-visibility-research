# Cloute AI Visibility Research

Open data from [Cloute](https://cloute.ai), an AI visibility company for local businesses. Cloute measures how often ChatGPT, Gemini, Claude, Perplexity and Google AI Overviews recommend a business against its local competitors.

Licensed CC BY 4.0. Cite as: **Source: Cloute, https://cloute.ai/research**

## Datasets

| File | What it is | Write-up |
|---|---|---|
| [`data/named-rate-read-vs-not-read-2026.csv`](data/named-rate-read-vs-not-read-2026.csv) | Share of AI answers naming a local business when the engine had, or had not, opened one of the business's own pages while answering. 64,441 answers, 2026. | [AI recommends what it has read](https://cloute.ai/research/ai-reads-before-it-recommends) |
| [`data/ai-crawler-visits-2026.csv`](data/ai-crawler-visits-2026.csv) | Visits by self-identified AI crawlers to local business pages, from server logs, 2026. 80,000+ visits from 19 crawlers. | [AI crawlers on local business websites](https://cloute.ai/research/ai-crawlers-local-business-websites-2026) |
| [`data/aeo-vendor-visibility-index-2026-10.csv`](data/aeo-vendor-visibility-index-2026-10.csv) | Which AI visibility / AEO vendors ChatGPT, Claude, Gemini and Perplexity name when asked 37 buyer questions, 444 answers, October 2026. Cloute, the publisher, is excluded. | [AEO Vendor Visibility Index](https://cloute.ai/research/aeo-vendor-visibility-index) |
| [`data/dealer-website-ai-readability-2026-10.csv`](data/dealer-website-ai-readability-2026-10.csv), [`data/dealer-website-platforms-2026-10.csv`](data/dealer-website-platforms-2026-10.csv) | 2,915 US car dealership websites in 58 metros: robots.txt rules for AI crawlers, readable HTML without JavaScript, bot-protection refusals, by platform. October 2026. Requests identified as a normal browser; no crawler was impersonated. | [Can AI read dealership websites?](https://cloute.ai/research/can-ai-read-dealership-websites) |
| [`data/local-website-ai-readability-2026-10.csv`](data/local-website-ai-readability-2026-10.csv) | 6,143 US local business websites (car dealerships, hotels, dental practices) in 58 metros: bot-protection refusals, robots.txt AI rules, readability without JavaScript. October 2026. | [Can AI read local business websites?](https://cloute.ai/research/can-ai-read-local-business-websites) |

## Key findings

- **AI recommends what it has read.** Engines named a local business 83.7% of the time when they had opened one of its own pages while answering, and 16.2% when they had not. Gemini 92.2% vs 20.7%, Google AI Overviews 89.0% vs 33.4%, Claude 86.6% vs 11.9%, Perplexity 81.3% vs 16.7%, ChatGPT 79.4% vs 21.1%.
- **Seven in ten first-measurement answers name someone else.** Before any work, 70% of AI answers about a local business named a competitor or nobody (18,613 answers).
- **AI crawlers read local business sites at scale.** ClaudeBot made the most visits, then GPTBot. OpenAI's three crawlers (GPTBot, OAI-SearchBot, ChatGPT-User) together made 30,434 visits.
- **Dealer sites: bot protection, not robots.txt.** Of 2,915 dealership websites, 0.3% block AI search crawlers in robots.txt, but 29.5% refused or challenged a plain automated request.
- **The engines disagree about vendors.** In the October 2026 AEO Vendor Visibility Index, Profound (32.9% of answers) and Semrush (32.2%) were named most, but no vendor led on all four engines.

## Method

How answers are collected, read and counted: [cloute.ai/research/methodology](https://cloute.ai/research/methodology). Short version: customer-style questions, live web search on, every answer kept in full with the sources the engine used, before-and-after only on identical questions and engines, misses kept in every total.

## Updates

The AEO Vendor Visibility Index is re-run monthly on the same questions. New editions are added to `data/` with the month in the file name.

## Contact

Questions about the data: [cloute.ai](https://cloute.ai/contact).
