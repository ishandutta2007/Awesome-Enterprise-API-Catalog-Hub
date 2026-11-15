# Awesome-Enterprise-API-Catalog-Hub

# Top Enterprise API Catalog & Hub Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Developer Portals, Service Catalogs & API Discovery*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise API Catalog & Hub**. These tools help organizations inventory their APIs, services, and ownership metadata—creating a searchable catalog that developers can use to discover reusable assets, understand dependencies, and follow platform standards.

**Examples** include Postman API Catalog, Spotify Backstage, Port, Cortex, OpsLevel, Kong Konnect, Axway Amplify, Apigee API Hub, and MuleSoft Anypoint Exchange (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted developer portals, open-source service catalogs, and community-driven API discovery—ideal for platform teams seeking to avoid per-developer SaaS fees while maintaining full control over their internal developer portal. The open-source landscape has a clear leader: **Backstage** is the CNCF-incubated framework that Spotify open-sourced, and it remains the most widely adopted foundation for building a custom developer portal [citation:3].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Postman API Catalog](https://www.postman.com/)** | API catalog within Postman Enterprise plan. Provides a centralized view of APIs across teams with governance and discovery features. Included with Enterprise tier alongside private API networks and advanced RBAC [citation:12]. | Enterprise: **$800/user/month** (annual); Team: $400/user/month [citation:2] | **Free**: 1 user only; **30-day Enterprise trial** available [citation:2] |
| **[Port](https://www.port.io/)** | Internal developer portal with software catalog, self-service actions, and scorecards. Positioned as a more opinionated, faster-to-deploy alternative to Backstage. **Free plan: up to 15 seats** with 10K entities and 400 runs [citation:13]. | Free: **$0** (15 seats); Basic: **$30/user/month**; Standard: **$40/user/month**; Enterprise: custom [citation:4][citation:13] | **Free forever**: 15 seats, 10K entities, 400 runs, usage-limited AI agents [citation:13] |
| **[Cortex](https://www.cortex.io/)** | Internal developer portal with service catalog, scorecards, and initiatives. **Pricing is contact-sales only**—no published rate card. Third-party listings suggest a starting point around **~$25/developer/month**, but this is unconfirmed [citation:14]. | Quote-only (contact sales) | No confirmed free tier; demos via sales [citation:14] |
| **[OpsLevel](https://www.opslevel.com/)** | Internal developer portal with service catalog, scorecards, and campaigns. **Priced per developer** using the portal; volume discounts available. Custom pricing via sales [citation:10]. | Quote-only (per-developer) | No free tier; demo via sales [citation:10] |
| **[Kong Konnect](https://konghq.com/)** | API management platform with service catalog capabilities. **Plus plan: usage-based** with 1M requests included monthly; Enterprise: contract-based with 24/7 support [citation:6][citation:15]. | Plus: usage-based (1M requests included); Enterprise: quote-only | **30-day trial** with free credits [citation:6] |
| **[Axway Amplify Engage](https://www.axway.com/)** | API catalog and marketplace for discovering, classifying, and managing API assets. **Engage tier: 5 assets / 10 subscriptions minimum**; priced by API assets and marketplace subscriptions [citation:7]. | Quote-only (asset/subscription-based) | No free tier; demo via sales |
| **[Apigee API Hub](https://cloud.google.com/apigee)** | API catalog within Google Cloud's Apigee platform. **No additional charges for API Hub utilization** as of its GA feature set—included with Apigee subscription [citation:8]. | Included with Apigee (consumption-based API management) | No standalone free tier; Apigee evaluation available |
| **[MuleSoft Anypoint Exchange](https://www.mulesoft.com/)** | Catalog of reusable assets, developer portals, and MCP server publishing. **Shares a credit pool** with MuleSoft's gateway, manager, and integrations—suitable for API programs with many internal consumers [citation:1][citation:11]. | Quote-only (shared Mule credits) | **30-day Agent Fabric trial** (no credit card) [citation:1] |

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
