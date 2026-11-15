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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global API management and developer portal market is estimated at **$8B–$11B**, projected to grow at a robust **16%–22% CAGR** to surpass **$30B+** over the next decade. The sector exhibits a **moderately concentrated, bifurcated structure**: major hyperscalers and legacy enterprise software giants (Google Cloud Apigee, Salesforce MuleSoft, Microsoft) command roughly 55%–62% of core infrastructure spend, while specialized API-first platforms and internal developer portals (Postman, Kong, Port, Backstage) capture a rapidly growing, fragmented share catering to multi-cloud cataloging and developer experience.

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
| **[Kong Gateway](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | **Cloud-Native API Gateway & Service Hub.** Apache-2.0. High-performance, Lua/Nginx-based API gateway connecting microservices, routing APIs, and offering native developer portal and service registry plugins. |
| **[Backstage](https://github.com/backstage/backstage)** | [![Stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers) | **The industry-standard open-source developer portal framework.** Apache-2.0, CNCF Incubating project created by Spotify. Centralized software catalog for microservices, APIs, libraries, TechDocs, and hundreds of community plugins. |
| **[Swagger UI](https://github.com/swagger-api/swagger-ui)** | [![Stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers) | **OpenAPI Interactive Documentation & Discovery.** Apache-2.0. The ubiquitous visualization tool that turns OpenAPI (Swagger) specifications into dynamic, interactive API discovery portals. |
| **[Redoc](https://github.com/redocly/redoc)** | [![Stars](https://img.shields.io/github/stars/redocly/redoc?style=social&color=white)](https://github.com/redocly/redoc/stargazers) | **Responsive OpenAPI/Swagger Documentation Portal.** MIT. Clean 3-panel API documentation and discovery portal generator for responsive, production-ready enterprise catalogs. |
| **[Apache APISIX](https://github.com/apache/apisix)** | [![Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers) | **Dynamic Cloud-Native API Gateway & Management.** Apache-2.0. Full-lifecycle API management platform featuring dynamic routing, service discovery, authentication, and a developer-friendly management dashboard. |
| **[Scalar](https://github.com/scalar/scalar)** | [![Stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers) | **Modern Open-Source API Reference & Developer Portal.** MIT. Beautiful, customizable developer portal and interactive API reference generator supporting OpenAPI/Swagger specifications. |
| **[Stoplight Elements](https://github.com/stoplightio/elements)** | [![Stars](https://img.shields.io/github/stars/stoplightio/elements?style=social&color=white)](https://github.com/stoplightio/elements/stargazers) | **Embeddable API Documentation & Portal Components.** Apache-2.0. Web components for building custom API documentation and catalog portals from OpenAPI specs and Markdown docs. |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | **Full Enterprise API Lifecycle Management & Developer Portal.** Apache-2.0. Comprehensive open-source platform offering an API publisher, developer marketplace, gateway, and governance tooling. |
| **[Apiman](https://github.com/apiman/apiman)** | [![Stars](https://img.shields.io/github/stars/apiman/apiman?style=social&color=white)](https://github.com/apiman/apiman/stargazers) | **Open-Source API Management & Catalog.** Apache-2.0. Lightweight API management and cataloging engine with policy enforcement, metrics, and developer management UI. |
| **[Gravitee API Management](https://github.com/gravitee-io/gravitee-api-management)** | [![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | **Event-Native API Management & Developer Portal.** Apache-2.0. Complete API management solution featuring an API catalog, developer portal, API publisher, and real-time streaming analytics. |

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
