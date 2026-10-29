# Awesome-Audience-Targeting-Platform

**Top Audience Targeting Platform (Opensource & SaaS) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Audience Segmentation, First-Party Data Activation, Real-Time Personalization & Privacy-First Targeting*

**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Audience Targeting Platforms**. These tools enable organizations to build, segment, and activate audiences across advertising, marketing, and personalization channels—from fully managed enterprise data platforms with identity graphs and cross-channel activation to self-hosted CDPs and segment engines that give teams complete control over first-party data and privacy compliance.

**Open-source emphasis**: This section is expanded with relevant projects for self-hosting, audience segmentation, customer data pipelines, and open activation infrastructure. **Critical note**: True open-source audience targeting—with cross-publisher identity graphs and ad network integrations—is essentially nonexistent. Open-source projects address the **audience building and activation** layer within your own first-party data, not the external ad network targeting that LiveRamp or The Trade Desk provide.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global audience targeting and customer data platform (CDP) market is estimated between **$4.5 billion and $8.5 billion** in 2026, projected to exceed **$25+ billion** by the early 2030s fueled by the deprecation of third-party cookies and enterprise transition to privacy-first, first-party data activation. The sector exhibits a **concentrated, winner-take-most structure at the top**—dominated by mega-cap digital walled gardens (Alphabet, Meta) and enterprise cloud/ad-tech powerhouses (The Trade Desk, Adobe, Twilio Segment)—alongside a **moderately fragmented long-tail** of specialized independent CDPs, composable warehouse-native engines, and vertical-specific personalization providers.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Price | Free Tier / Trial Limits | Description & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Audience Network](https://ads.google.com/)** | ~$3.80T Market Cap (Alphabet) / ~$350B+ TTM Rev | Pay-as-you-go ad spend (no platform fee; ad bids start at $0.01 CPC/CPM) | Free platform access forever; requires active Google Ads account (free $500 ad credit match available for qualified new advertisers upon spending $500 within 60 days) | Google's native audience targeting across Search, Display, YouTube, and Discovery campaigns. Includes Customer Match, affinity, and custom intent audiences. **Best for**: Advertisers leveraging Google's ecosystem. |
| **[Meta Custom Audiences](https://www.facebook.com/business/)** | ~$1.58T Market Cap (Meta Platforms) / ~$160B+ TTM Rev | Pay-as-you-go ad spend (no platform fee; ad minimum spend $1.00/day) | Free platform access forever; requires active Meta Business / Ad account (periodic promotional credits for new businesses; no software fees) | Upload customer lists, build Lookalike Audiences, and retarget on Facebook, Instagram, and Audience Network. **Best for**: Advertisers retargeting existing customers and scaling lookalikes across Meta properties. |
| **[Shopify Audiences](https://www.shopify.com/)** | ~$215B Market Cap (Shopify) / ~$8.5B+ TTM Rev | Requires Shopify Plus plan starting at $2,300/month (3-year term) or $2,500/month (1-year term); app itself has no additional cost | 3-day free trial on standard Shopify store plans, followed by promotional first month at $1/month; no standalone free tier for Shopify Plus features | Shopify's first-party audience targeting tool using pooled merchant behavioral signals to generate high-intent audiences for Meta, Google, and TikTok. **Best for**: High-volume Shopify Plus merchants. |
| **[Adobe Audience Manager](https://business.adobe.com/)** | ~$100B Market Cap (Adobe) / ~$21B+ TTM Rev | Contracts typically start from ~$50,000/year (~$4,166/month) scaling up based on server call tiers and ingested profile volume | No free tier forever; customized enterprise proof-of-concept (PoC) / sandbox trial available exclusively via direct Adobe sales qualification | Enterprise Data Management Platform (DMP) and Experience Platform component for segmentation, lookalike modeling, and omnichannel cross-device activation. **Best for**: Large enterprises unified on Adobe Experience Cloud. |
| **[Segment Engage](https://segment.com/)** (Twilio) | ~$39B Market Cap (Twilio) / ~$4.3B+ TTM Rev | Team plan starts at $120/month (for up to 10,000 MTUs); Unify & Engage audience modules require custom contract | Free plan forever: Up to 1,000 Monthly Tracked Users (MTUs), 2 web/mobile sources, unlimited destinations, and 1 data warehouse sync/day | Customer engagement and audience activation platform built on Twilio Segment's CDP to build unified customer profiles and real-time behavioral cohorts. **Best for**: Product and growth teams wanting unified data routing and marketing syncs. |
| **[The Trade Desk](https://www.thetradedesk.com/)** | ~$6.15B Market Cap / ~$2.99B TTM Rev | Direct enterprise seats require minimum ad spend commitments of $100,000/quarter (~$33,333/month) plus ~20% platform tech fee (SMBs can access via partner agencies/resellers with lower minimums) | No free tier forever; no self-serve free trial (pilot access granted on contracted commitments via enterprise Master Services Agreements) | Independent demand-side platform (DSP) with programmatic audience targeting, Unified ID 2.0 (UID2) cross-channel identity graph, and data marketplace integrations. **Best for**: Programmatic buyers across Connected TV, display, audio, and video. |
| **[Klaviyo](https://www.klaviyo.com/)** | ~$5.95B Market Cap / ~$1.39B TTM Rev | Email plan starts at $20/month (up to 500 active profiles & 5,000 monthly email sends); Email + SMS starts at $35/month | Free plan forever: Up to 250 active profiles, 500 monthly email sends, and 150 free SMS/MMS credits (includes Klaviyo branding and 60 days of email support) | E-commerce marketing automation and customer data platform featuring granular dynamic segmentation, predictive RFM analytics, and omni-channel campaigns. **Best for**: E-commerce brands automating segmented email and SMS campaigns. |
| **[LiveRamp](https://liveramp.com/)** | ~$2.31B Market Cap / ~$832M TTM Rev | Standard tier starts at $20,000/year (~$1,666/month, includes under 5M records and 1-3 media destinations); Premier tier starts at $150,000/year | No free tier forever; guided enterprise sandbox/PoC trials available on request via sales for qualified enterprise accounts | Deterministic identity resolution and data connectivity platform (RampID) for privacy-safe audience activation and data clean rooms across publishers and ad networks. **Best for**: Enterprises needing cross-publisher identity resolution. |
| **[Criteo](https://www.criteo.com/)** | ~$800M Market Cap / ~$1.86B TTM Rev | Pay-as-you-go working media budget (self-serve campaigns have no fixed subscription fee; typically recommended starting campaign budget of $500) | Free self-serve sign-up forever; new advertiser onboarding incentives provide matching ad credits up to $1,500 after initial spend milestones | Commerce media, retail media network (RMN), and dynamic retargeting platform with first-party audience activation for retailers and performance marketers. **Best for**: Retailers and brands focused on commerce-driven audience targeting. |
| **[Quantcast](https://www.quantcast.com/)** | ~$75M+ Est. Rev / Private (~$150M Total Raised) | Self-serve ad platform has no fixed monthly subscription fee and no minimum spend requirement (pay per campaign CPM/CPC) | 30-day free trial for platform access and exploration (Quantcast Measure web analytics product also offers a permanent free tier with basic traffic insights) | AI-powered audience intelligence, cookie-free predictive targeting (Ara platform), and real-time demographic insights. **Best for**: Marketers seeking live audience discovery and programmatic buying. |

## Open-Source GitHub Projects

The following table lists active open-source projects for customer data unification, audience segmentation, real-time edge evaluation, and activation pipelines, ordered by GitHub stargazers count:

| Project | Stars | Primary Purpose | Tech Stack | License | Key Capabilities & Architecture |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[PostHog](https://github.com/PostHog/posthog)** | [![Stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers) | Product OS & CDP / Cohort Targeting | Python, TypeScript, ClickHouse, Kafka | MIT | Dynamic behavioral cohort builder, event ingestion, real-time feature flags, session replay, and warehouse syncs. Self-hosted or Cloud. |
| **[Mautic](https://github.com/mautic/mautic)** | [![Stars](https://img.shields.io/github/stars/mautic/mautic?style=social&color=white)](https://github.com/mautic/mautic/stargazers) | Marketing Automation & Audience Segmentation | PHP, Symfony, MySQL | GPL-3.0 | Comprehensive contact management, lead scoring, dynamic audience segments, rule-based campaign journeys, and multi-channel owned messaging. |
| **[GrowthBook](https://github.com/growthbook/growthbook)** | [![Stars](https://img.shields.io/github/stars/growthbook/growthbook?style=social&color=white)](https://github.com/growthbook/growthbook/stargazers) | Feature Flagging & Audience Targeting Engine | TypeScript, React, Go / Python SDKs | MIT | Warehouse-native targeting engine for feature flags and A/B experiments; evaluates user segments and targeting rules in <1ms without sending user data externally. |
| **[Snowplow](https://github.com/snowplow/snowplow)** | [![Stars](https://img.shields.io/github/stars/snowplow/snowplow?style=social&color=white)](https://github.com/snowplow/snowplow/stargazers) | Behavioral Data Platform & Event Pipeline | Scala, Kafka, ClickHouse, Snowflake | Apache-2.0 | Enterprise-grade behavioral event collection and enrichment pipeline delivering clean first-party event streams directly into warehouses for audience modeling. |
| **[Jitsu](https://github.com/jitsucom/jitsu)** | [![Stars](https://img.shields.io/github/stars/jitsucom/jitsu?style=social&color=white)](https://github.com/jitsucom/jitsu/stargazers) | Open-Source CDP & Data Routing | Go, TypeScript, ClickHouse, Redis | MIT | Flexible open-source Segment alternative for tracking first-party events and syncing customer records into warehouses and marketing destinations. |
| **[RudderStack Server](https://github.com/rudderlabs/rudder-server)** | [![Stars](https://img.shields.io/github/stars/rudderlabs/rudder-server?style=social&color=white)](https://github.com/rudderlabs/rudder-server/stargazers) | Warehouse-Native Customer Data Pipeline | Go, Node.js, PostgreSQL | AGPL-3.0 | Collects, unifies, and routes customer events to 180+ cloud destinations and warehouses for downstream audience modeling and activation. |
| **[Dittofeed](https://github.com/dittofeed/dittofeed)** | [![Stars](https://img.shields.io/github/stars/dittofeed/dittofeed)](https://github.com/dittofeed/dittofeed/stargazers) | Customer Engagement & Audience Journeys | TypeScript, Node.js, PostgreSQL | MIT | Open-source alternative to Customer.io/Braze with visual and SQL-based segment builders, automated journey triggers, and multi-channel message delivery. |
| **[Prebid.js](https://github.com/prebid/Prebid.js)** | [![Stars](https://img.shields.io/github/stars/prebid/Prebid.js?style=social&color=white)](https://github.com/prebid/Prebid.js/stargazers) | Header Bidding & First-Party Data Module | JavaScript | Apache-2.0 | Standard programmatic header bidding library featuring First-Party Data (FPD) and Real-Time Data (RTD) modules to pass audience segments directly into ad auctions. |
| **[Grouparoo](https://github.com/grouparoo/grouparoo)** | [![Stars](https://img.shields.io/github/stars/grouparoo/grouparoo?style=social&color=white)](https://github.com/grouparoo/grouparoo/stargazers) | Reverse ETL & Customer Cohort Sync | TypeScript, Node.js, PostgreSQL | Apache-2.0 | Reverse ETL framework that queries your data warehouse to define customer cohorts and continuously syncs audience groups into advertising and CRM tools. |
| **[Tracardi](https://github.com/Tracardi/tracardi)** | [![Stars](https://img.shields.io/github/stars/Tracardi/tracardi?style=social&color=white)](https://github.com/Tracardi/tracardi/stargazers) | API-First Composable CDP | Python, Elasticsearch | MIT + CC | Open customer data platform for profile unification, event tracking, rule-driven segmentation, and real-time website personalization. |
| **[Prebid Server](https://github.com/prebid/prebid-server)** | [![Stars](https://img.shields.io/github/stars/prebid/prebid-server?style=social&color=white)](https://github.com/prebid/prebid-server/stargazers) | Server-Side Ad Auction & Audience Routing | Go | Apache-2.0 | High-throughput cloud auction server supporting server-side header bidding, privacy compliance checks, and secure first-party audience signal routing. |
| **[Apache Unomi](https://github.com/apache/unomi)** | [![Stars](https://img.shields.io/github/stars/apache/unomi?style=social&color=white)](https://github.com/apache/unomi/stargazers) | Oasis CDP Reference Implementation | Java, Apache Karaf, Elasticsearch | Apache-2.0 | Apache customer data platform implementing OASIS Customer Data Platform specification; manages profiles, segments, scoring, rules, and privacy consent. |
| **[Google Megalista](https://github.com/google/megalista)** | [![Stars](https://img.shields.io/github/stars/google/megalista?style=social&color=white)](https://github.com/google/megalista/stargazers) | First-Party Ad Data Onboarding Integration | Python | Apache-2.0 | Serverless pipeline to push first-party audience segments and offline conversions from BigQuery into Google Ads (Customer Match) and Campaign Manager. |
| **[Helio](https://github.com/achref-soua/helio)** | [![Stars](https://img.shields.io/github/stars/achref-soua/helio?style=social&color=white)](https://github.com/achref-soua/helio/stargazers) | AI-Native Growth Platform & Segments | TypeScript, Python, ClickHouse, Temporal | AGPL-3.0 | Modern customer engagement platform with visual nested segment builders, streaming evaluation, AI copilot for natural-language cohorts, and messaging journeys. |
| **[LEO CDP](https://github.com/trieu/leo-cdp-framework)** | [![Stars](https://img.shields.io/github/stars/trieu/leo-cdp-framework?style=social&color=white)](https://github.com/trieu/leo-cdp-framework/stargazers) | AI-First Customer Data Platform | Java, Python, Dagster, Docker | GPL-3.0 | Omnichannel customer data platform framework with real-time 360 profiles, ML-based RFM/churn segmentation, and automated marketing activation connectors. |
| **[MessageBirds](https://github.com/Mullassery/MessageBirds)** | [![Stars](https://img.shields.io/github/stars/Mullassery/MessageBirds?style=social&color=white)](https://github.com/Mullassery/MessageBirds/stargazers) | Rust Event-Driven CDP & Identity Graph | Rust, TypeScript, Kafka, PostgreSQL | MIT | High-performance CDP featuring an identity graph with deterministic matching and real-time streaming rule-based audience segment membership evaluation. |
| **[EdgePersona](https://github.com/Crynge/EdgePersona)** | [![Stars](https://img.shields.io/github/stars/Crynge/EdgePersona?style=social&color=white)](https://github.com/Crynge/EdgePersona/stargazers) | Real-Time Edge Segment Evaluation Engine | Python, FastAPI, Redis, DBSCAN | MIT | Ultra-fast AST-based segment evaluation engine (<1ms at 1M evals/sec), deterministic + DBSCAN clustering, and multi-armed bandit personalization algorithms. |

### Architectural Patterns for Building an Open-Source Audience Stack

Organizations building a fully open, self-hosted audience targeting stack can combine these modular projects:
1. **Event Ingestion & Routing**: **Snowplow**, **RudderStack**, or **Jitsu** to collect first-party behavioral events across web and mobile.
2. **Profile Unification & Segmentation**: **PostHog**, **Tracardi**, or **Apache Unomi** to merge identity profiles and generate dynamic user cohorts.
3. **Data Activation & Reverse ETL**: **Grouparoo** or **Google Megalista** to sync computed audience lists back into ad platforms (Google Ads, Meta) or CRM tools.
4. **Edge Personalization & Ad Delivery**: **GrowthBook** or **EdgePersona** for ultra-low latency segment checks on the frontend, and **Prebid.js / Prebid Server** for first-party data monetization in ad auctions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow the table formats and keep entries sorted accordingly).
3. Include: name, link, concise factual description, company scale / pricing details for SaaS, and star badge / license for open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Audience targeting platforms handling customer data and behavioral signals must comply with data protection regulations (GDPR, CCPA, ePrivacy, etc.) and implement appropriate consent management, access controls, and data retention policies.
- **The "first-party audience segmentation" vs. "cross-publisher identity resolution" vs. "ad network targeting" distinction is critical.** Open-source tools like **PostHog, Tracardi, Apache Unomi, Helio, and Dittofeed** build and segment audiences from **your own first-party data**. **Google Megalista** pushes audiences into **Google's ad products**. **LiveRamp** provides **cross-publisher identity resolution (RampID)**. **The Trade Desk**, **Google**, and **Meta** provide **ad network targeting** at global scale. **No open-source project replicates LiveRamp's commercial identity graph or The Trade Desk's DSP marketplace.**
- Commercial pricing and enterprise minimums fluctuate and are subject to contract terms. Validate pricing directly with vendors against your anticipated audience volumes and activation requirements.
- Self-hosted open-source solutions require secure server configuration, encryption, and regular maintenance to handle sensitive customer signals compliantly.

---

**Made for developers, marketing teams, and organizations building transparent audience targeting solutions.**

Let's make Audience Targeting Platforms more open, data-driven, and privacy-friendly.
