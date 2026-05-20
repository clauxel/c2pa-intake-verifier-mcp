# Workflow

C2PA Intake Verifier is a hosted remote MCP for C2PA intake verifier MCP.

## Repeatable Flow

1. Open C2PA Intake Verifier and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://c2paintake.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call verify_c2pa_intake with public-safe sample data.
5. Save the returned receipt or export for human review.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
