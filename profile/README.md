# PonsMCP

**Agent payment infrastructure for the Machine Payments Protocol.**

PonsMCP gives autonomous agents a small, inspectable MCP tool surface for pons launch intelligence, USDG payment quotes, local policy checks, Robinhood Chain execution, and on-chain receipt verification.

## Product repositories

| Repository | Purpose |
|---|---|
| [ponsmcp-sdk](https://github.com/ponsmcpai/ponsmcp-sdk) | TypeScript SDK and stdio MCP server |
| [ponsmcp-docs](https://github.com/ponsmcpai/ponsmcp-docs) | Installation, tool reference, security, and integration docs |
| [presentation-layer](https://github.com/ponsmcpai/presentation-layer) | Website and Mission Control console |
| [ponsmcp-contracts](https://github.com/ponsmcpai/ponsmcp-contracts) | Reserved for future deployed contracts; current settlement is direct USDG transfer |

## Principles

- Agent private keys stay in the local agent runtime, never the browser.
- Payment success means a verified chain receipt, not a UI confirmation.
- Token names and tickers are not identity; contract addresses are.
- $MCP contract details are published only after the official launch.
