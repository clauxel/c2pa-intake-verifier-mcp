# Evaluation Guide

Use this page to evaluate whether C2PA Intake Verifier fits a real workflow.

## What To Test

- C2PA intake verifier MCP
- C2PA Intake Verifier
- C2PA Intake Verifier documentation
- C2PA Intake Verifier remote MCP
- c2paintake server card

## Expected Evidence

- Open C2PA Intake Verifier and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://c2paintake.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call verify_c2pa_intake with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.
- Confirm region-specific disclosure and rights decisions with the accountable policy owner.

## Buyer Path

Default plan: team.

- https://c2paintake.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=evaluation_checkout
