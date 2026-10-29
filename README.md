# data-schemas (retired)

This repository no longer hosts schemas. Intake schemas, destinations, and scenarios are published, signed, on
**XMRegistry**: <https://registry.xmarin.dev> (repository [`xmintake/registry`](https://github.com/xmintake/registry)).
XMIntake only loads schemas published there; schema URLs on this host are refused.

What remains is kept only because its URLs are used as identifiers:

| Path | Why it stays |
|---|---|
| `meta/` | `$id` / `$schema` identifiers used by XMIntake schemas, scenarios, entitlements, and the API payload sent to HTTP API destinations (`xmintake-api-payload-schema.v1.json`) |
| `spec/` | Legacy identifiers for the registry destination spec and `global-config.json` spec. The current destination spec is at `https://xmintake.github.io/registry/spec/registry/registry-destination.schema.json` |

Don't add new files here. These identifiers move to XMRegistry with the next major version of each format.
