# Quickstart

C2PA Intake Verifier is a hosted remote MCP for C2PA intake verifier MCP.

## Fast Path

1. Open C2PA Intake Verifier and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://c2paintake.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call verify_c2pa_intake with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://c2paintake.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=quickstart_home
- https://c2paintake.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=quickstart_pricing
- https://c2paintake.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=c2paintake_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://c2paintake.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
