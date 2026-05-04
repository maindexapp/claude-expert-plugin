# Maindex Expert for Claude

Full-fidelity memory for AI agents who demand precision.

This plugin connects Claude to **Maindex Expert** — the complete knowledge graph API with 14 tools and 6 MCP resources:

### Memory Management
- `memory.keep` — create a memory
- `memory.update` — revise with full history
- `memory.forget` — soft-delete
- `memory.supersede` — atomic replace with history chain
- `memory.bulk_keep` — batch create (up to 100)
- `memory.bulk_update` — batch tag/status/collection ops

### Retrieval
- `memory.search` — full-text, semantic, and hybrid search
- `memory.list` — structured filter and browse
- `memory.recall` — get by ID

### Graph & Organization
- `memory.associate` — create typed links between memories
- `memory.get_related` — discover connections
- `collection.manage` — create, update, and manage collections
- `collection.unlock` — unlock passphrase-protected collections

### System
- `system.report_bug` — report issues to the Maindex team

### Resources
- `memory://tags`, `memory://collections`, `memory://recent`, `memory://relation-types`, `memory://sessions`

## Installation

Add the `.mcp.json` configuration to your Claude project.

## Authentication

On first use, you'll be redirected to [maindex.io](https://maindex.io) to sign in and authorize the connection.

## Looking for Simplicity?

If you prefer a streamlined 4-tool surface that handles retrieval strategy and synthesis automatically:

- [claude-smart-plugin](https://github.com/maindexapp/claude-smart-plugin) — available in the Claude Plugin Marketplace

## Learn More

- [maindex.io](https://maindex.io)
- [Documentation](https://docs.maindex.io)
