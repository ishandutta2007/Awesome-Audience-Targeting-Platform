# Awesome-Audience-Targeting-Platform

# Awesome-Audience-Targeting-Platform

**Top Audience Targeting Platform (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Audience Segmentation, First-Party Data Activation, Real-Time Personalization & Privacy-First Targeting*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Audience Targeting Platforms**. These tools enable organizations to build, segment, and activate audiences across advertising, marketing, and personalization channels—from fully managed enterprise data platforms with identity graphs and cross-channel activation to self-hosted CDPs and segment engines that give teams complete control over first-party data and privacy compliance.



**Examples** include Shopify Audiences, Klaviyo, LiveRamp, Quantcast, Criteo, Meta Custom Audiences, The Trade Desk, Adobe Audience Manager, Segment Engage, and Google Audience Network (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, audience segmentation, and open activation infrastructure. **Critical note**: True open-source audience targeting—with cross-publisher identity graphs and ad network integrations—is essentially nonexistent. Open-source projects address the **audience building and activation** layer within your own first-party data, not the external ad network targeting that LiveRamp or The Trade Desk provide.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Shopify Audiences](https://www.shopify.com/)**

  **Shopify's first-party audience targeting tool** for merchants. Uses Shopify's aggregated shopper data to build custom audiences for Meta and Google ads. **Pricing**: Available to Shopify Plus merchants; quote-based. **Free tier**: None. **Best for**: Shopify merchants wanting to leverage platform-level shopper signals for paid acquisition without building a CDP.



- **[Klaviyo](https://www.klaviyo.com/)**

  **Marketing automation and customer data platform** with segmentation, predictive analytics, and cross-channel activation. **Pricing**: Free tier for up to 250 contacts; paid plans scale with contact count. **Free tier**: Yes, with limited contacts and features. **Best for**: e-commerce brands wanting unified customer data and segmented email/SMS campaigns.



- **[LiveRamp](https://liveramp.com/)**

  **Data connectivity and identity resolution platform** for privacy-safe audience activation across publishers and ad tech. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: enterprises needing deterministic identity resolution and cross-publisher audience activation at scale.



- **[Quantcast](https://www.quantcast.com/)**

  **Audience intelligence and programmatic advertising platform** with real-time audience insights. **Pricing**: Quote-only. **Free tier**: None. **Best for**: advertisers wanting audience discovery and programmatic activation based on live behavior.



- **[Criteo](https://www.criteo.com/)**

  **Commerce media and retargeting platform** with audience segmentation for retail and performance marketing. **Pricing**: Quote-only; performance-based models available. **Free tier**: None. **Best for**: retailers and brands wanting commerce-focused audience targeting and retargeting.



- **[Meta Custom Audiences](https://www.facebook.com/business/)**

  **Meta's audience targeting tool** for uploading customer lists and building lookalike audiences on Facebook and Instagram. **Pricing**: Ad spend-based; no separate audience fee. **Free tier**: Yes (requires Meta ad account). **Best for**: advertisers wanting to retarget existing customers and find similar audiences on Meta platforms.



- **[The Trade Desk](https://www.thetradedesk.com/)**

  **Demand-side platform** with audience targeting, data marketplace, and cross-channel activation. **Pricing**: Quote-only; platform fees plus media spend. **Free tier**: None. **Best for**: programmatic advertisers wanting data-driven audience buying across connected TV, display, and video.



- **[Adobe Audience Manager](https://business.adobe.com/)**

  **Enterprise data management platform (DMP)** for audience segmentation and activation across Adobe and third-party channels. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: Adobe Experience Cloud customers wanting unified audience management across marketing channels.



- **[Segment Engage](https://segment.com/)** (Twilio)

  **Customer engagement and audience activation** built on Segment's CDP. **Pricing**: Tiered by monthly tracked users and destination volume. **Free tier**: Limited free tier available. **Best for**: Segment customers wanting to build audiences from unified customer data and activate across marketing tools.



- **[Google Audience Network](https://ads.google.com/)**

  **Google's audience targeting** across Search, Display, YouTube, and Discovery campaigns. Includes Customer Match, affinity, in-market, and custom intent audiences. **Pricing**: Ad spend-based; no separate audience fee. **Free tier**: Yes (requires Google Ads account). **Best for**: advertisers wanting Google's native audience targeting across its ecosystem.



## Open-Source GitHub Projects



- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**

  **AI-first Customer Data Platform framework** (license per repo) — **the most comprehensive open-source audience segmentation platform** found in this research. **Features**: Omnichannel data collection (web, mobile, CRM, POS, social, ads, IoT); real-time Customer 360 profiles; **ML-based segmentation** with RFM, CLV, churn prediction, purchase propensity, and lead scoring; behavioral tracking and journey mapping; real-time audience activation to marketing, sales, and advertising platforms; Agentic AI/LLM-powered personalization; consent management and RBAC . **Tech stack**: Multi-component (Dagster orchestration, Docker/Kubernetes). **Deploy**: Self-hosted. **Trade-off**: **Ambitious scope but early-stage**—community validation is limited, and the full stack requires significant operational maturity. It builds and segments audiences from your first-party data; it does not connect to external ad networks like LiveRamp or The Trade Desk. **Best for**: developers and data teams wanting a self-hosted, AI-native CDP foundation for first-party audience segmentation and activation.



- **[MessageBirds](https://github.com/Mullassery/MessageBirds)**

  **Event-driven Customer Data & Engagement Platform** (license per repo) — **a modern Rust-based CDP with real-time audience evaluation**. **Features**: Identity graph with deterministic matching and merge/split audit trails; schema registry with field-level governance labels; **rule-based audience definitions with real-time streaming membership evaluation**; durable journey engine; consent ledger; and multi-SDK support (Web, iOS, Python, TypeScript) . **Tech stack**: Rust (core), TypeScript (SDKs/UI), Kafka/Redpanda, PostgreSQL. **Deploy**: Self-hosted (Docker Compose for dev infra). **Trade-off**: **Early-stage with disclosed unverified components** (Android SDK, edge gateway not deployed). Audience activation is through webhooks and a bulk-sync destination, not native ad network integrations. **Best for**: developers wanting a modern, Rust-based CDP foundation with strong governance and real-time audience evaluation.



- **[EdgePersona](https://github.com/Crynge/EdgePersona)**

  **Python real-time cross-channel personalization engine (Edge CDP)** (license per repo) — **the most performant open-source segment evaluation engine** in this list. **Features**: Identity resolution with deterministic + DBSCAN clustering (claimed 92-95% match rate); **AST-based segment rule engine** (AND/OR/NOT/Condition) evaluating in **<1ms** at 1M evals/sec; multi-armed bandit personalization (Thompson Sampling/UCB1) with 22% lift claimed; Bayesian A/B testing; Redis-backed profile cache with <5ms reads; FastAPI async server at 5K req/sec . **Tech stack**: Python, FastAPI, Redis, DBSCAN. **Deploy**: Self-hosted (`pip install edgepersona`). **Trade-off**: **Personalization and segment evaluation engine**, not a full audience targeting platform—no ad network activation, no data collection SDKs, no CRM integrations. **Best for**: developers wanting a high-performance, embeddable segment engine for real-time personalization within their own applications.



- **[Tracardi](https://github.com/Tracardi/tracardi)**

  **API-first composable Customer Data Platform** (MIT with Common Clause) — **a flexible, developer-oriented CDP** for audience segmentation and personalization. **Features**: Customer data collection and unification from multiple sources; data modeling rules; **marketing segmentation**; real-time personalization via frontend apps and customized messages; profile unification with auto-deduplication; and integration with internal systems . **Tech stack**: Python, Elasticsearch. **Deploy**: Self-hosted (Docker). **Trade-off**: **CDP infrastructure**, not a turnkey audience targeting platform—no ad network connectors or pre-built activation destinations. Segmentation and personalization require configuration and development. **Best for**: developers wanting an open, composable CDP foundation to build audience segmentation and personalization workflows.



- **[Helio](https://github.com/achref-soua/helio)**

  **Open-source AI-native growth platform** (AGPL-3.0) — **a modern marketing automation and engagement platform with CDP capabilities**. **Features**: Segment/RudderStack-compatible tracking API; **visual nested AND/OR segment builder** with always-live membership (segments are predicates, not sync jobs); durable campaigns and journeys on Temporal; email/SMS/WhatsApp/push channels; AI copilot for natural-language segment and journey creation; predictive lead scoring and churn; MCP server for AI agent access . **Tech stack**: TypeScript, Python, PostgreSQL, ClickHouse, Redpanda, Temporal. **Deploy**: Self-hosted (Docker, Kubernetes Helm). **Trade-off**: **Marketing automation and engagement platform**, not an ad targeting platform—no external ad network activation. Audience segmentation is for owned-channel activation (email, SMS, push). **Best for**: teams wanting a self-hosted, AI-native alternative to Klaviyo or Customer.io with strong segmentation capabilities.



- **[Dittofeed](https://github.com/dittofeed/dittofeed)**

  **Open-source customer engagement platform** (MIT) — **a self-hosted Customer.io/Braze alternative** with segment-driven journeys. **Features**: **SQL or visual segment builder** for defining audiences; automated journeys triggered by user behavior or schedules; multi-channel messaging (email, SMS, push); Docker and PostgreSQL deployment . **Tech stack**: TypeScript, Node.js, PostgreSQL. **Deploy**: Self-hosted (Docker) or Dittofeed Cloud. **Trade-off**: **Engagement platform**, not an audience targeting platform—segments are used for owned-channel messaging, not ad network activation. **Best for**: startups and mid-size teams wanting control over customer data and segment-driven messaging without per-contact fees.



- **[Google Megalista](https://github.com/google/megalista)**

  **First-party data integration solution** (Apache 2.0) — **the most directly relevant open-source tool for ad platform audience onboarding**. **Features**: Enables marketing teams to onboard **audiences and conversions into Google Marketing products** (Google Ads, Campaign Manager, Google Analytics); built for first-party data activation at scale. **Tech stack**: Python. **Deploy**: Self-hosted (Google Cloud). **Trade-off**: **Google-ecosystem-specific**—it moves your data into Google's ad products but does not provide segmentation, identity resolution, or cross-platform targeting. It is an ETL/onboarding utility, not a targeting platform. **Best for**: organizations wanting to push first-party audience segments into Google Ads and related products programmatically.



### Additional Strong Open-Source Options



- **RudderStack** — Warehouse-first customer data pipeline (AGPL-3.0 core). Collects and routes events to destinations but does not provide audience segmentation or targeting itself; pair with a CDP or warehouse queries for audience building . **Best for**: data teams wanting to own event collection before building audiences in their warehouse.

- **audience-engine-beta** — Privacy-first, cookieless audience management web app for ad campaigns (JavaScript, license per repo). **Note**: **Zero stars, last updated over 1 year ago**—effectively abandoned and unvalidated . **Best for**: reference only, not production adoption.

- **adcontextprotocol/signals-agent** — Reference implementation of an AdCP Signals Agent (license per repo). Demonstrates discovery and activation of audience signals with integrations for LiveRamp and Index Exchange . **Note**: **Reference/protocol implementation**, not a turnkey platform—requires Gemini API and custom configuration. **Best for**: developers exploring ad-tech protocol implementations.



**Frameworks for building custom systems**: Combine **LEO CDP** or **MessageBirds** for audience segmentation and identity resolution with **Helio** or **Dittofeed** for owned-channel activation, **Google Megalista** for pushing audiences into Google Ads, and **EdgePersona** for real-time segment evaluation at the edge—creating a first-party audience targeting stack. **None of these replace LiveRamp or The Trade Desk** for cross-publisher identity resolution and ad network targeting.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Audience targeting platforms handling customer data and behavioral signals must comply with data protection regulations (GDPR, CCPA, ePrivacy, etc.) and implement appropriate consent management, access controls, and data retention policies.

- **The "first-party audience segmentation" vs. "cross-publisher identity resolution" vs. "ad network targeting" distinction is critical.** **LEO CDP, MessageBirds, Tracardi, Helio, and Dittofeed** build and segment audiences from **your own data** for owned-channel activation. **Google Megalista** pushes your audiences into **Google's ad products**. **LiveRamp** provides **cross-publisher identity resolution**—connecting your data to publisher ecosystems. **The Trade Desk** and **Meta/Google** provide **ad network targeting** at scale. **No open-source project replicates LiveRamp's identity graph or The Trade Desk's demand-side platform.**

- **Open-source audience targeting is fundamentally limited to first-party data.** The projects listed here excel at collecting, unifying, and segmenting your own customer data. **They do not provide access to external audiences, publisher networks, or third-party data marketplaces.** If your use case requires reaching new audiences beyond your existing customer base, you will need commercial platforms.

- **LEO CDP is the most comprehensive but least validated.** It claims full CDP capabilities with ML segmentation and real-time activation, but community adoption is limited and operational complexity is high. **MessageBirds and EdgePersona are more focused but earlier-stage.** Evaluate maturity carefully before committing production audience workflows.

- **Google Megalista is the only open-source project directly connected to ad network activation**—but only for Google's ecosystem. It is an onboarding pipeline, not a targeting platform, and requires Google Cloud infrastructure .

- **Pricing opacity is universal across commercial vendors.** Shopify Audiences, LiveRamp, Quantcast, Criteo, The Trade Desk, Adobe Audience Manager, and Segment Engage all require sales contact or spend-based estimation. Meta Custom Audiences and Google Audience Network are free to use (ad spend-based). **Validate with direct vendor conversations against your actual audience volumes and activation channels.**

- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Customer data and behavioral signals are sensitive**—ensure your hosting meets your organization's security and privacy requirements before deploying.



---



**Made for developers, marketing teams, and organizations building transparent audience targeting solutions.**

Let's make Audience Targeting Platforms more open, data-driven, and privacy-friendly.
