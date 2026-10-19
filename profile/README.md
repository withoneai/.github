<img src="https://assets.withone.ai/banners/github.png" alt="One — The integration runtime for AI agents." style="border-radius: 5px;">

<h3 align="center">One</h3>

<p align="center">
  <a href="https://withone.ai"><strong>Website</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://withone.ai/docs"><strong>Docs</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://app.withone.ai"><strong>Dashboard</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://withone.ai/knowledge"><strong>Knowledge</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://withone.ai/changelog"><strong>Changelog</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://x.com/withoneai"><strong>X</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://linkedin.com/company/withoneai"><strong>LinkedIn</strong></a>
</p>

<p align="center">
  <a href="https://withone.ai/knowledge"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fapi.withone.ai%2Fopen%2Fcount%2Fplatforms" alt="platforms"></a>
  &nbsp;
  <a href="https://withone.ai/knowledge"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fapi.withone.ai%2Fopen%2Fcount%2Ftools" alt="tools"></a>
</p>

---

One is the trust layer for AI agents. Connect each app once, in an account that belongs to you, and every agent you run works through that connection: scoped to the action, revocable in one click, and recorded in a complete audit trail. Agents get a grant, never your credentials. One is a passthrough, so your data is never stored.

**1,000+ platforms and 130,000+ verified tools**, each one tested before an agent runs it.

### Products

| | |
|---|---|
| **[Connect](https://withone.ai/products/connect)** | Connect once, and every agent you run uses it. Add it to your own product too: a button and two backend routes let your users grant your app scoped, revocable access to their tools. [`connect`](https://github.com/withoneai/connect) |
| **[Knowledge](https://withone.ai/products/knowledge)** | The open API knowledge base behind every action: parameters, auth flows and edge cases, verified and free to use. [`knowledge`](https://github.com/withoneai/knowledge) |
| **[CLI](https://withone.ai/products/cli)** | The same connection from the terminal, for any agent that can run a command line. [`cli`](https://github.com/withoneai/cli) |
| **[MCP](https://withone.ai/products/mcp)** | Every connection you own, in any MCP agent, through three tools. [`mcp`](https://github.com/withoneai/mcp) |
| **[Relay](https://withone.ai/products/relay)** | Events from your apps to your agents. |

### Get started

Point any MCP agent at One's hosted server and sign in when it asks:

```bash
$ claude mcp add --transport http one https://mcp.withone.ai/mcp
```

Or install the CLI:

```bash
$ npm install -g @withone/cli
$ one init
$ one onboard
```

The [One CLI](https://www.npmjs.com/package/@withone/cli) will prompt you for your API key (get one from the [dashboard](https://app.withone.ai/settings/api-keys)) and configure One for your agent of choice: Claude Code, Codex, Cursor, Claude Desktop, Windsurf and more. Setup guides for every agent are at [withone.ai/mcp](https://withone.ai/mcp).

### See it working

[Use cases](https://withone.ai/use-cases) shows working agents, each with its own repo, and [awesome-one](https://github.com/withoneai/awesome-one) collects what people have built on One.
