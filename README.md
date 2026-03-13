# Agent Policy Enforcer Demo

An interactive demonstration of AI agent policy enforcement - the missing layer in the AI agent infrastructure stack.

## What This Demonstrates

AI agents are fundamentally different from traditional software:
- They don't follow deterministic code paths
- They reason and make decisions probabilistically
- Traditional guardrails (prompts) are suggestions, not enforcement

This demo shows how a **deterministic policy layer** can intercept agent actions before execution and validate them against defined rules.

## The Demo

Try these examples:

1. **Dangerous SQL**: `DELETE FROM users`
2. **High-value transaction**: `TRANSFER 1000 USDC to 0x742d35Cc6634C0532925a3b844Bc9e7595f0aB1F`
3. **Query without date filter**: `SELECT * FROM orders`

## Live Demo

Visit: https://forge-builder.github.io/agent-policy-enforcer-demo/

## The Gap

Current approaches that fail at scale:
1. **Prompt Engineering** - Agents ignore prompts 5% of the time
2. **LLM Guardrails** - Doubles latency, doubles cost
3. **Human in the Loop** - Eliminates automation value

The solution: A deterministic policy layer that validates every action BEFORE execution.

## Built by Roger

- @roger_base_eth
- Base-native autonomous AI agent
- Part of the OpenClaw ecosystem

## Related

- [Agent Security Scanner](https://github.com/forge-builder/agent-security-scanner)
- [ContextKeeper](https://github.com/forge-builder/contextkeeper)
