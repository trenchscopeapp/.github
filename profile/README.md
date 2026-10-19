<p align="center">
  <a href="https://www.trenchscope.dev"><img src="https://raw.githubusercontent.com/trenchscopeapp/.github/main/profile/assets/trenchscope.png" alt="trenchscope" width="112" height="112"></a>
</p>
<h1 align="center">trenchscope</h1>
<p align="center"><strong>a terminal for the trenches.</strong></p>
<p align="center">An open-source Solana memecoin screener, with your own Claude or Codex as the analyst.</p>
<p align="center">
  <a href="https://www.trenchscope.dev">Website</a> ·
  <a href="https://github.com/trenchscopeapp/trenchscope">Source &amp; docs</a> ·
  <a href="https://www.npmjs.com/package/trenchscope">npm</a> ·
  <a href="https://x.com/trenchscopehq">X</a>
</p>

### See what is moving. Ask better questions.

Screen Solana tokens, open token dossiers, inspect price charts, and check holders and risk signals. Connect the read-only MCP server to Claude or Codex to explore the same data in conversation.

- **In your terminal:** a keyboard-driven screener with your own Claude or Codex login as the analyst.
- **In Claude.ai:** an interactive token screener and dossiers with token images, clickable contract and wallet links, and price charts in compatible MCP Apps views.
- **For developers:** open source under AGPL-3.0. The MCP server has no tools to build, sign, or send transactions.

### Get started

With Node.js 22.18 or newer:

```sh
npm install -g trenchscope
trenchscope doctor
trenchscope
```

[Install on macOS, Linux, or Windows](https://github.com/trenchscopeapp/trenchscope#install) · [Set up Claude Code or Codex](https://github.com/trenchscopeapp/trenchscope#use-it-from-claude-or-codex)

### Add to Claude.ai

In **Settings > Connectors > Add custom connector**, use:

```text
Name: Trenchscope
MCP server URL: https://trenchscope-mcp-production.up.railway.app/mcp
```

Choose **No sign-in**, leave request headers empty, and enable the connector in a conversation. Try: **Show trending Solana tokens.** Public market data needs no login or API key.

[Browse the source and documentation](https://github.com/trenchscopeapp/trenchscope)

### Build with us

[Report a bug](https://github.com/trenchscopeapp/trenchscope/issues) · [Read the contributing guide](https://github.com/trenchscopeapp/trenchscope/blob/main/CONTRIBUTING.md) · [Report a security issue](https://github.com/trenchscopeapp/trenchscope/security/policy)

<sub>Early software. Market data and model analysis can be incomplete or wrong. Paper and live trading are experimental. Not financial advice. Built from <a href="https://github.com/dexterm-xyz/dexterm">dexterm</a>.</sub>

