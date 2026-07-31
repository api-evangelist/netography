---
name: Automate response policies and blocking
description: Authenticate, look up IP intelligence, list/create response policies,
  and clear the block list.
api: openapi/netography-openapi.yml
operations:
- v1_auth_token_post
- v1_intel_lookup_ips_post
- v1_response_policies_get
- v1_response_policy_post
- v1_blocks_delete
---

# Automate response policies and blocking

Authenticate, look up IP intelligence, list/create response policies, and clear the block list.

Base URL: `https://api.netography.com`  ·  Auth: JWT bearer (see `authentication/netography-authentication.yml`).

## Steps

1. **Authenticate** — POST /api/v1/auth/token; use the bearer. (`v1_auth_token_post`)
2. **Look up IPs** — POST /api/v1/intel/lookup/ips to enrich suspect IPs (geo/reputation). (`v1_intel_lookup_ips_post`)
3. **List policies** — GET /api/v1/rule-engine/rules to review response policies. (`v1_response_policies_get`)
4. **Create policy** — POST /api/v1/rule-engine/rule to add a response policy that fires an integration. (`v1_response_policy_post`)
5. **Clear blocks** — DELETE /api/v1/blocks to clear the current block list. (`v1_blocks_delete`)

## Conventions

- All calls after auth send `Authorization: Bearer <access_token>`.
- Searches use NQL (Netography Query Language) with a start/end time range.
- Errors return `{status, name, message}` (see `errors/netography-problem-types.yml`).
