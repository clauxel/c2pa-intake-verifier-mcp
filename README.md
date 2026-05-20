# C2PA Intake Verifier

C2PA Intake Verifier is a hosted remote MCP for C2PA intake verifier MCP.

This repository is a public documentation project for C2PA Intake Verifier. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://c2paintake.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=readme_home
- Pricing: https://c2paintake.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=readme_pricing
- Checkout: https://c2paintake.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://c2paintake.clauxel.com/mcp
- Server card: https://c2paintake.clauxel.com/server-card.json
- Registry name: `com.clauxel.c2paintake/c2paintake-mcp`
- Tools: `verify_c2pa_intake`, `classify_source_risk`, `issue_media_receipt`, `explain_missing_credentials`, `export_intake_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI governance teams, policy reviewers, trust and safety leads, and compliance operators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: verify_c2pa_intake
- MCP tool: classify_source_risk
- MCP tool: issue_media_receipt
- MCP tool: explain_missing_credentials
- MCP tool: export_intake_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
