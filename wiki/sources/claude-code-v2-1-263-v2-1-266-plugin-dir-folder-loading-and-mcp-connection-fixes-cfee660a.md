---
fetched_at: &id001 2026-09-09
freshness_window_days: 365
image_count: 0
kind: source
last_updated: *id001
last_verified: *id001
sha256: cfee660a82e3ecfef55066830f45be8c90e326ad7d84516e0f8dfed126ead8b6
sources: []
title: 'Claude Code v2.1.263-v2.1.266: plugin-dir folder loading and MCP connection
  fixes'
topic: agentic-coding
url: https://dev.classmethod.jp/articles/20260909-cc-updates-v2-1-266/
---

## Excerpts

> HTTP-configured MCP servers that only support the legacy HTTP+SSE transport can now connect properly, with the system falling back to SSE according to MCP specifications.

> The plugin-dir feature now allows specifying parent folders that automatically load multiple plugins from subfolders, improving the convenience of loading multiple plugins at once for testing.

> A regression in v2.1.265 involving the CLAUDE_CODE_USE_GATEWAY environment variable was fixed in v2.1.266 — the variable no longer forces Cloud gateway sign-in when used alone, restoring compatibility with API key and custom authentication configurations.

> Versions v2.1.262 and v2.1.264 were not published to npm, and v2.1.266 is a regression fix for v2.1.265. The updates span from September 6-8, 2026 (UTC).