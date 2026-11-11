## Signalix

Signalix ranks Hyperliquid traders, vaults and bots by verified on-chain results. Every number is computed from public chain data: time-weighted return, maximum drawdown, return against drawdown, win rate, and the real cost of trading, net of fees and funding. Nothing is self-reported, and nobody can pay to be listed higher.

### How it works

Addresses are discovered from the public Hyperliquid leaderboard and vault list. For each one we collect fills, funding, ledger movements and account history, convert every fee to USD, and compute metrics per period. Deposits and withdrawals are taken out of returns, so a large deposit never looks like profit. Accounts with incomplete or inconsistent history are flagged and kept out of the rankings instead of being shown with guessed numbers.

### For developers

The same data is available through a public REST API, a Node.js and TypeScript SDK, and a read-only MCP server for Claude, Cursor and other MCP clients. The SDK and the MCP server are being prepared and will be published in this organization.

### Links

- [Website](https://signalix.trading)

Signalix is an analytics service. It does not give investment advice and does not manage funds.
