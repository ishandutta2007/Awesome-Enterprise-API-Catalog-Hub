# Awesome-Enterprise-API-Catalog-Hub

## Top Enterprise API Catalog & Hub Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Developer Portals, Service Catalogs & API Discovery*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise API Catalog & Hub**. These tools help organizations inventory their APIs, services, and ownership metadata—creating a searchable catalog that developers can use to discover reusable assets, understand dependencies, and follow platform standards.

**Examples** include Postman API Catalog, Spotify Backstage, Port, Cortex, OpsLevel, Kong Konnect, Axway Amplify, Apigee API Hub, and MuleSoft Anypoint Exchange (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted developer portals, open-source service catalogs, and community-driven API discovery—ideal for platform teams seeking to avoid per-developer SaaS fees while maintaining full control over their internal developer portal. The open-source landscape has a clear leader: **Backstage** is the CNCF-incubated framework that Spotify open-sourced, and it remains the most widely adopted foundation for building a custom developer portal [citation:3].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-----------------------------------|-------------|-------------------|--------------------------|
| **[Apigee API Hub](https://cloud.google.com/apigee)** | **~$2.1T Market Cap** (Alphabet / Google Cloud ~$35B+ ARR) | Enterprise API catalog & governance tool within Google Cloud's Apigee suite. | Pay-as-you-go Base Environment: **$0.50/hour/region** (~$365/month + $20/1M proxy calls; API Hub features included at no extra charge) | **60-day free trial** (Apigee Evaluation tier sandbox environment) |
| **[MuleSoft Anypoint Exchange](https://www.mulesoft.com/)** | **~$280B Market Cap** (Salesforce / MuleSoft ~$1.5B+ ARR) | Catalog of reusable APIs, connectors, and developer portals in Anypoint Platform. | Integration Starter: **$2,000/month** (billed annually at $24,000/year) | **30-day free trial** (full Anypoint Platform access; 30-day metric retention) |
| **[Postman API Catalog](https://www.postman.com/)** | **$5.6B Valuation** (~$310M ARR) | Centralized view of APIs across teams with governance and discovery features. | Enterprise: **$49/user/month** (annual) | **Free forever**: 1 user only (10,000 API calls/month, 5 integrations); **30-day Enterprise trial** |
| **[Kong Konnect](https://konghq.com/)** | **$2.0B Valuation** (~$100M+ ARR) | API lifecycle management and service catalog with multi-cloud control planes. | Plus tier: **$25/month** (Serverless Control Plane; includes 1M requests/month) | **30-day full Enterprise free trial** (unlimited trial evaluation, 30-day analytics retention) |
| **[Axway Amplify Engage](https://www.axway.com/)** | **~$1.3B Market Cap** (~$800M+ Revenue) | API catalog and enterprise marketplace for discovering and governing API assets. | Minimum entry package: **5 Assets / 10 Subscriptions** (Enterprise contract-based quote) | **30-day guided trial / evaluation PoC** (available upon request via sales) |
| **[Port](https://www.port.io/)** | **$800M Valuation** (Series C, ~$20M+ ARR) | Internal developer portal with software catalog, self-service actions, and scorecards. | Basic: **$30/user/month** (annual) | **Free forever**: 15 seats, 10,000 entities, 400 runs/month |
| **[Cortex](https://www.cortex.io/)** | **$470M Valuation** (Series C, ~$15M+ ARR) | Internal developer portal with service catalog, scorecards, and initiatives. | Baseline entry: **$39,000/year** (~$65/user/month for 50 users via AWS Marketplace) | **14-day to 30-day free trial** / custom PoC (available upon request via sales/marketplace) |
| **[OpsLevel](https://www.opslevel.com/)** | **~$75M Valuation** (Series A, ~$5M-$10M ARR) | Internal developer portal with service catalog, scorecards, and campaigns. | Baseline entry: **$39/user/month** (annual contract; ~$46,800/year for 100 users) | **14-day to 30-day free trial** / custom PoC (available upon request via sales) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Backstage](https://github.com/backstage/backstage)** | [![Stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers) | **The most widely adopted open-source developer portal framework.** Apache-2.0, released by Spotify and now a CNCF incubating project. **A framework for building your own developer portal**—not a turnkey product. Provides a **centralized software catalog** for APIs, services, libraries, and documentation, plus TechDocs ("docs like code") and a plugin ecosystem. Spotify open-sourced about a third of its internal plugins; the rest remain proprietary, but the community has built hundreds more [citation:3]. **Best for platform teams with engineering capacity** wanting to build a fully customized, self-hosted developer portal without per-seat SaaS fees. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Backstage Plugins (Community)](https://github.com/backstage/backstage/tree/master/plugins)** | — | **The plugin ecosystem that extends Backstage's catalog.** Community-maintained plugins add integrations for Kubernetes, CI/CD, API documentation, and more. The catalog becomes truly useful when plugins surface data from your existing tooling [citation:3]. |

**Frameworks for building custom systems**: **Backstage** is the only mature open-source foundation for an enterprise API catalog. It provides the catalog data model, plugin architecture, and TechDocs foundation—you supply the plugins and customization to match your organization's tooling. **Port** offers a faster SaaS alternative with a generous free tier (15 seats), but it is proprietary [citation:13].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- API catalogs and developer portals handle internal service metadata and ownership information; enforce access controls and avoid exposing sensitive architectural details to unauthorized users.
- **Open-source API cataloging has one clear leader with a trade-off.** **Backstage is a framework, not a product**—it requires engineering investment to build and customize, but eliminates per-developer SaaS fees and gives you full control [citation:3]. **Port offers a faster path** with a free tier for up to 15 seats, but pricing scales at $30–$40/user/month and the platform is proprietary [citation:13]. **Cortex and OpsLevel are quote-only** with unconfirmed starting points (Cortex's ~$25/developer/month is modeled, not confirmed) [citation:14][citation:10]. **Enterprise API management platforms** (Kong, Axway, Apigee, MuleSoft) include catalog features but are priced for broader API management, not cataloging alone [citation:6][citation:7][citation:1]. **Validate whether you need a framework (Backstage) or a turnkey portal (Port)** based on your engineering capacity and timeline.

---

**Made for platform engineers, developer experience teams, and organizations building internal developer portals.**  
Let's make enterprise API catalogs more open, discoverable, and developer-friendly.
