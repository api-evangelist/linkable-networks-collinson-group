# Linkable Networks (Collinson Group)

Linkable Networks, Inc. is a Boston-based card-linked-offers (CLO) and SKU-linked-offers platform. Consumers
attach digital offers to the credit and debit cards already in their wallet; when a linked card is used for a
qualifying purchase on the Visa, MasterCard, American Express or PayPal rails, the Linkable platform receives
the transaction, optionally confirms item-level detail via the on-premises Linkable SKU Matcher, and delivers
the savings back as a statement credit, eGift, points or miles — with no POS integration and no extra hardware
or software.

Associated with the Collinson Group, the privately-owned global travel, loyalty and insurance operator behind
Priority Pass. Surfaced through the Bain Capital Ventures portfolio.

## API

**MyLinkables Consumer API** — `https://api.mylinkables.com`, version 1.0, JSON or XML, OAuth 2.0 Resource
Owner Password Credentials. Covers consumer registration/opt-out, offers by state (available, linked,
redeemed, reserved) and linked payment card management. Card add/update is restricted to PCI-compliant
partners. Documentation and credentials are issued on email request — see
[Developers/Publishers](https://linkablenetworks.com/appweb-developers/).

## Status

Legacy. The production API host is live and answering (every documented path returns 403, not 404), with TLS
1.3 and HSTS preload. But the public developer page is dated "Copyright 2013", the marketing site is an
unmaintained WordPress install carrying injected third-party SEO link-spam, its News and Terms of Service
links are broken, and the associated GitHub organization is named "Collinson Group - Legacy" with zero public
repositories. There is no OpenAPI, SDK, CLI, sandbox, changelog, status page, deprecation policy, error
reference, rate-limit policy, trust center or `.well-known` surface.

Backed by: bain-capital-ventures
