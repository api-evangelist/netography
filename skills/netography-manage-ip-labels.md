---
name: Enrich traffic with IP context labels
description: Authenticate, then create, bulk-update and read IP context labels used
  to enrich flows.
api: openapi/netography-openapi.yml
operations:
- v1_auth_token_post
- v1_labels_ips_get
- v1_labels_ips_post
- v1_labels_ips_bulk_put
- v1_labels_ips_ip_context_get
---

# Enrich traffic with IP context labels

Authenticate, then create, bulk-update and read IP context labels used to enrich flows.

Base URL: `https://api.netography.com`  ·  Auth: JWT bearer (see `authentication/netography-authentication.yml`).

## Steps

1. **Authenticate** — POST /api/v1/auth/token; use the bearer on all calls. (`v1_auth_token_post`)
2. **List labels** — GET /api/v1/labels/ips to see existing IP labels. (`v1_labels_ips_get`)
3. **Create a label** — POST /api/v1/labels/ips with an ip + context + value. (`v1_labels_ips_post`)
4. **Bulk upsert** — PUT /api/v1/labels/ips/bulk to create/update many IP labels at once. (`v1_labels_ips_bulk_put`)
5. **Read for an IP** — GET /api/v1/labels/ips/{ip}/{context} to read a label for one IP+context. (`v1_labels_ips_ip_context_get`)

## Conventions

- All calls after auth send `Authorization: Bearer <access_token>`.
- Searches use NQL (Netography Query Language) with a start/end time range.
- Errors return `{status, name, message}` (see `errors/netography-problem-types.yml`).
