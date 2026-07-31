---
name: Create and tune detection models
description: Authenticate, list traffic detection models, create one, enable it, and
  set per-object threshold overrides.
api: openapi/netography-openapi.yml
operations:
- v1_auth_token_post
- v1_traffic_detection_models_get
- v1_traffic_detection_model_post
- v1_traffic_detection_model_id_enable_put
- v1_threshold_overrides_put
---

# Create and tune detection models

Authenticate, list traffic detection models, create one, enable it, and set per-object threshold overrides.

Base URL: `https://api.netography.com`  ·  Auth: JWT bearer (see `authentication/netography-authentication.yml`).

## Steps

1. **Authenticate** — POST /api/v1/auth/token; use the bearer. (`v1_auth_token_post`)
2. **List models** — GET /api/v1/rule-engine/algorithms to review detection models. (`v1_traffic_detection_models_get`)
3. **Create model** — POST /api/v1/rule-engine/algorithm with the model config. (`v1_traffic_detection_model_post`)
4. **Enable** — PUT /api/v1/rule-engine/algorithm/{id}/enable to activate it. (`v1_traffic_detection_model_id_enable_put`)
5. **Tune thresholds** — PUT /api/v1/rule-engine/triggers to set threshold overrides. (`v1_threshold_overrides_put`)

## Conventions

- All calls after auth send `Authorization: Bearer <access_token>`.
- Searches use NQL (Netography Query Language) with a start/end time range.
- Errors return `{status, name, message}` (see `errors/netography-problem-types.yml`).
