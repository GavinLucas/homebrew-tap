# homebrew-tap

Homebrew tap for [GavinLucas/docker-mcp-server](https://github.com/GavinLucas/docker-mcp).

## Usage

```bash
brew install gavinlucas/tap/docker-mcp-server
```

Then add to your MCP client configuration:

```json
{
  "mcpServers": {
    "docker-mcp-server": {
      "command": "docker-mcp-server",
      "args": [],
      "env": {}
    }
  }
}
```

> **Homebrew 6.0+ note:** The fully-qualified form above (`gavinlucas/tap/docker-mcp-server`) auto-trusts this tap for that formula. If you use the short form after `brew tap gavinlucas/tap`, run `brew trust --formula gavinlucas/tap/docker-mcp-server` first.

For full documentation see [github.com/GavinLucas/docker-mcp](https://github.com/GavinLucas/docker-mcp#readme).

---

The formula in this tap is maintained automatically by [publish-homebrew.yaml](https://github.com/GavinLucas/docker-mcp/blob/main/.github/workflows/publish-homebrew.yaml) — do not edit it by hand.
