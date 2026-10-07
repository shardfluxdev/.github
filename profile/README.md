<a href="https://shardflux.dev">
  <img src="https://raw.githubusercontent.com/shardfluxdev/.github/main/profile/assets/shardflux-banner.png" alt="Shardflux. Persistent workspaces for customer-facing agent products." width="1500">
</a>

### Persistent workspaces for customer-facing agent products.

Give each of your customers their own computer for your agent. It sleeps when there is no work, wakes in milliseconds, and keeps every file and running app where they left it.

- **Scales to zero.** When the work stops, the compute bill stops with it. Files, apps and memory stay.
- **Wakes on the next call.** Your agent's next call wakes it in milliseconds, so your customers never wait on a cold start.
- **Keeps everything.** Files, packages, running apps and memory stay put. Your customer comes back next week and picks up where they left off.
- **Forks a new direction.** Copy a running workspace, memory and all, and let two agents try different ideas from the same point.
- **Isolated by default.** Every customer runs in their own microVM with its own kernel, fully separate from everyone else.

```sh
npm i -g shardflux
shard signup
shard exec acme/demo --template default -- python3 -c 'print(40 + 2)'
```

**Your own coding agents work here too.** `shard ./` starts Claude Code or Codex on your project in the cloud, with your machine and project ready, and keeps it working when you close your laptop. Open it from your terminal, Claude Desktop or the Codex app.

TypeScript SDK [`@shardflux/sdk`](https://www.npmjs.com/package/@shardflux/sdk) · Python SDK [`shardflux`](https://pypi.org/project/shardflux/) · CLI [`shard`](https://www.npmjs.com/package/shardflux) · [MCP server](https://docs.shardflux.dev/reference/mcp) · [HTTP API](https://docs.shardflux.dev/reference/http-api) · [E2B SDK](https://docs.shardflux.dev/guides/e2b) · [Plugins for Claude Code, Cowork and Codex](https://github.com/shardfluxdev/plugins)

[Website](https://shardflux.dev) · [Quickstart](https://docs.shardflux.dev/quickstart) · [Documentation](https://docs.shardflux.dev) · [Pricing](https://docs.shardflux.dev/limits) · [Support and bugs](https://github.com/shardfluxdev/community) · [Follow on X](https://x.com/Shardfluxdev)
