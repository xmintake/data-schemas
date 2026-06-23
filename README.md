# data-schemas

Published at **https://xmintake.github.io/data-schemas/** (GitHub Pages).

All fetchable schema URLs use this host. Do not use `xmintake.app` until that domain serves content.

## Layout

| Path | URL |
|---|---|
| `meta/` | Meta-schemas (intake form, API payload, scenarios, entitlements) |
| `schemas/` | Intake form schemas referenced by `schemaUrl` on destinations |
| `spec/registry/` | [registry-destination.schema.json](spec/registry/registry-destination.schema.json) — XMRegistry `.destination.json` |
| `spec/config/` | [global-config-v1.1.schema.json](spec/config/global-config-v1.1.schema.json) — XMIntake `global-config.json` |

Registry **destination files** (signed artifacts) live in the [registry](https://github.com/xmintake/registry) repo under `destinations/`; they reference schemas here via `schemaUrl` and `$schema`.

## Scenarios

Scenarios let you script, automate, and validate real-world XMIntake workflows using simple, portable JSON.
