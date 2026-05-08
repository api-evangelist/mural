# Mural (mural)

Mural is a visual collaboration platform. It exposes both a Mural API and a Mural Enterprise API with OAuth 2.0 authentication, scope-based permissions, rate limiting, pagination, and a published OpenAPI specification. Postman workspace and Zapier integration are also available.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mural/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=mural-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Mural Public API** - REST at `https://app.mural.co/api/public/v1`. OAuth 2.0 with scopes; murals, widgets, rooms, workspaces, file uploads.
- **Mural Enterprise API** - Additional admin / identity / audit endpoints for Enterprise plans.

## Tags
- Collaboration, Whiteboard, Workshops, Enterprise, OAuth

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.mural.co/)
- [Developer Portal](https://developers.mural.co/)
- [API Reference](https://developers.mural.co/public/reference)
- [Pricing](https://www.mural.co/pricing)
- [Community](https://community.mural.co/)
- [GitHub](https://github.com/muralco)
- [Plans](plans/mural-plans-pricing.yml)
- [RateLimits](rate-limits/mural-rate-limits.yml)
- [FinOps](finops/mural-finops.yml)

## Notes
- Pricing reconciled (research): Free (3 active murals); Team+ $9.99-12/member/mo; Business $17.99/member/mo (SSO); Enterprise custom (SCIM, audit logs, data residency). Visitors view-free.
- OpenAPI spec is referenced by Mural's developer portal but is rendered behind their SPA — not directly downloadable as a static file. Both Public and Enterprise surfaces are documented.
- This is the **richest API** of the four whiteboard providers — published rate limits, OAuth scopes, Postman workspace, and Zapier.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
