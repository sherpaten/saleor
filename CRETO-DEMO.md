# Creto Studio Demo Plan — Saleor Commerce

This repository is the upstream Saleor API-first commerce platform. The Creto demo will be a separately branded sample commerce experience built on Saleor; it is not a claim that the upstream project was authored by Creto Studio.

## Demo concept
**Creto Commerce Pro — Headless commerce**

- Demonstrate a sample catalogue, product variants, channels, cart, checkout, and order flow.
- Use fictional products, customers, prices, and orders only.
- Connect a separate storefront to Saleor's GraphQL API and use the Saleor Dashboard for administration.
- Brand the customer-facing demo as a Creto Studio implementation while retaining upstream notices and attribution.

## Implementation boundary
Saleor is an API-only backend. A complete demo needs a compatible storefront, the Saleor API/platform services, and the Dashboard. Do not treat this repository alone as a ready-to-run storefront.

## Deployment prerequisites
- Python/runtime and service versions required by the selected Saleor release.
- PostgreSQL, Redis, and other services required by the official deployment configuration.
- Separate deployments for API/platform, dashboard, and storefront as appropriate.
- Sandbox/test payment integration only; no live payment credentials in a public demo.

## Licensing and attribution
The root LICENSE is BSD 3-Clause. Preserve the copyright notice, conditions, and disclaimer in source distributions and required notices in binary distributions. Do not imply Saleor endorses Creto Studio.

## Status
- [x] Demo scope documented.
- [ ] Verify selected release and all storefront/dashboard dependencies and licences.
- [ ] Scaffold a Creto-branded storefront and sample catalogue.
- [ ] Configure isolated Saleor services and test order flow.
- [ ] Deploy and add the verified demo URL to Creto Studio Projects.
