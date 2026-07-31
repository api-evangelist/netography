---
name: Query flow and detection data with NQL
description: Authenticate, discover searchable fields for a context, then run an NQL
  search over flow/DNS/alert records and aggregate stats.
api: openapi/netography-openapi.yml
operations:
- v1_auth_token_post
- v1_search_context_fields_get
- v1_search_context_post
- v1_stats_context_agg_post
- v1_fetch_context_id_get
---

# Query flow and detection data with NQL

Authenticate, discover searchable fields for a context, then run an NQL search over flow/DNS/alert records and aggregate stats.

Base URL: `https://api.netography.com`  ·  Auth: JWT bearer (see `authentication/netography-authentication.yml`).

## Steps

1. **Authenticate** — POST /api/v1/auth/token with a JWT request token signed from your NETOSECRET; keep the returned access_token as the bearer. (`v1_auth_token_post`)
2. **Discover fields** — GET /api/v1/search/{context}/fields to learn valid NQL fields for the context (e.g. flow, dns, alert). (`v1_search_context_fields_get`)
3. **Search records** — POST /api/v1/search/{context} with an NQL query and a start/end time range. (`v1_search_context_post`)
4. **Aggregate** — POST /api/v1/stats/{context}/agg to summarize (top talkers, counts) over the range. (`v1_stats_context_agg_post`)
5. **Fetch one** — GET /api/v1/fetch/{context}/{id} to retrieve a single record by id. (`v1_fetch_context_id_get`)

## Conventions

- All calls after auth send `Authorization: Bearer <access_token>`.
- Searches use NQL (Netography Query Language) with a start/end time range.
- Errors return `{status, name, message}` (see `errors/netography-problem-types.yml`).
