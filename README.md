<img src="./assets/hero.svg" alt="Divyansh Sharma — Backend & Integration Engineer. Data flowing from Stripe, HubSpot, Gmail, Cloudbeds and Athenahealth through an integration service, Redis + BullMQ and a worker into the product." width="100%" />

I build the integrations that connect products to the platforms they depend on, and the backend services behind them.<br/>
**This profile works like an API. Click an endpoint to call it.**

<details>
<summary><picture><img src="./assets/ep-about.svg" alt="GET /about — who I am" width="94%" /></picture></summary>
<br/>

```json
{
  "name": "Divyansh Sharma",
  "role": "Backend & Integration Engineer",
  "experience_years": 4,
  "location": "Bengaluru, India",
  "focus": ["third-party API integrations", "OAuth 2.0", "webhooks", "queues and workers", "backend services"],
  "stack": ["Node.js", "Python", "Express", "MongoDB", "SQL", "Redis", "BullMQ", "Docker", "Google Cloud"],
  "certifications": ["Google Cloud Digital Leader"],
  "education": "B.Tech, Presidency University, Bangalore"
}
```
</details>

<details>
<summary><picture><img src="./assets/ep-integrations.svg" alt="GET /integrations — 20+ platforms I've shipped" width="94%" /></picture></summary>
<br/>

<img src="./assets/integrations.svg" alt="Integrations by domain. Payments: Stripe Connect. CRM and legal: HubSpot, Clio. Healthcare: Athenahealth, eClinicalWorks, NexHealth. Hospitality: Cloudbeds. Scheduling: Cal.com, Calendly. Email and data: Gmail with Pub/Sub, Google Sheets, BigQuery. Ads: Google Ads, Meta Conversions API. Social: Instagram, Facebook, YouTube. Automation: Make.com connector." width="100%" />

<sub>eCW = eClinicalWorks · CAPI = Meta Conversions API</sub>
</details>

<details>
<summary><picture><img src="./assets/ep-architecture.svg" alt="GET /architecture — the pattern behind most of them" width="94%" /></picture></summary>
<br/>

```mermaid
flowchart LR
    P["Platform<br/>Stripe · HubSpot · Gmail"] -- "webhook / Pub/Sub" --> S["Integration service"]
    S -- "OAuth 2.0 · polling" --> P
    S -- "verify, then enqueue" --> Q[("Redis + BullMQ")]
    Q --> W["Worker"] --> D[("MongoDB")]
    W -- "actions" --> A["AI agent · CRM · workflows"]
```
</details>

<details>
<summary><picture><img src="./assets/ep-backend.svg" alt="GET /backend — beyond integrations" width="94%" /></picture></summary>
<br/>

- **Microservices** — led the Node.js upgrade across microservices with minimal downtime, and moved from Moment.js to Day.js to cut bundle size.
- **Data** — migrated text-file data into databases with Java and SQL, added automated schedulers for periodic updates, and built audit logging into BigQuery.
- **Performance** — Redis caching and BullMQ job queues that made the system 30% faster.
- **APIs & auth** — RESTful APIs, standardized JSON API templates, and JWT authentication middleware.
- **Python** — event-driven functions that automate email processing and blacklist management.

</details>

<details>
<summary><picture><img src="./assets/ep-projects.svg" alt="GET /projects — things I've built in the open" width="94%" /></picture></summary>
<br/>

<p>
<a href="https://github.com/divyanshsharma11/calendlyIntegration"><img src="./assets/proj-calendlyintegration.svg" alt="calendlyIntegration" width="49%" /></a>
<a href="https://github.com/divyanshsharma11/hubSpot-Integration"><img src="./assets/proj-hubspot-integration.svg" alt="hubSpot-Integration" width="49%" /></a>
<a href="https://github.com/divyanshsharma11/luduscore"><img src="./assets/proj-luduscore.svg" alt="luduscore" width="49%" /></a>
<a href="https://github.com/divyanshsharma11/fetchAndSendStock"><img src="./assets/proj-fetchandsendstock.svg" alt="fetchAndSendStock" width="49%" /></a>
<a href="https://github.com/divyanshsharma11/STONKS-WEBAPP"><img src="./assets/proj-stonks-webapp.svg" alt="STONKS-WEBAPP" width="49%" /></a>
<a href="https://github.com/divyanshsharma11/MACHINE_LEARNING_STOCK_PREDICTION_MODEL"><img src="./assets/proj-ml-stock-prediction.svg" alt="ML stock prediction" width="49%" /></a>
</p>

</details>

<details>
<summary><picture><img src="./assets/ep-experience.svg" alt="GET /experience — four years, three companies" width="94%" /></picture></summary>
<br/>

<img src="./assets/timeline.svg" alt="Career timeline: Capgemini Engineering from July 2022, promoted to Associate II in April 2024; Vodex AI from August 2024; M32 AI from December 2025 to August 2026." width="100%" />

**M32 AI** · Integration Engineer
- Built a Make.com connector app from scratch (OAuth2, webhook and polling triggers)
- Stripe Connect with webhook signature verification and multi-account support
- Healthcare (Athenahealth, eClinicalWorks via NexHealth) and hospitality (Cloudbeds) integrations for an AI voice receptionist and chat agent

**Vodex AI** · Software Developer
- Cal.com, Gmail, Google Sheets and HubSpot integrations
- Redis caching and BullMQ queues, 30% faster
- JWT authentication middleware

**Capgemini Engineering** · Associate → Associate II Software Engineer
- Led a Node.js upgrade across microservices
- Asynchronous message auditing with data in BigQuery
- Event-driven Python automation

</details>

<details>
<summary><picture><img src="./assets/ep-fun-fact.svg" alt="GET /fun-fact — one thing about me" width="94%" /></picture></summary>
<br/>

```json
{ "fact": "I code with music on. It keeps the bugs away, most of the time." }
```
</details>

<a href="https://www.linkedin.com/in/divyansh-sharma1121"><img src="./assets/hire.svg" alt="POST /hire — open to backend and integration roles. Connect on LinkedIn." width="100%" /></a>
