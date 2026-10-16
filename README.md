# Joboostr for Claude

This repository distributes the Joboostr plugin for Claude chat, Cowork and Claude Code. The plugin connects to the same hosted Joboostr service as the existing OpenAI integration, with the same account, job allowance, membership checks, interactive cards, job tracking and resume tools.

The plugin source is in [`joboostr/`](joboostr/README.md). It contains no credentials, product backend source or customer data. Its package rights are reserved. Use of the service is governed by the linked Joboostr terms.

For the public directory, submit this repository with plugin path `joboostr`, and register `https://mcp.joboostr.com/mcp` separately as the related MCP connector. Complete Claude account and surface testing before claiming feature parity or publication.

For a local Claude Code check:

```sh
claude plugin validate --strict ./joboostr
claude --plugin-dir ./joboostr
```

The public distribution repository is https://github.com/joboostr/joboostr-claude. The marketplace catalog is `.claude-plugin/marketplace.json`. Install with `/plugin install joboostr --marketplace joboostr/joboostr-claude` in current Claude Code, or use Claude’s Add marketplace flow with the repository URL. A local archive is for private testing; it does not create a directory listing.
