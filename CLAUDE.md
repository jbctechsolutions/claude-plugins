# CLAUDE.md

Commercial Claude Code plugin marketplace for JBC Tech Solutions.

## Purpose

This is a **thin registry** that points to standalone plugin repos intended for external distribution. It contains no plugin code -- only `marketplace.json` with pointers.

## Structure

```
claude-plugins/
├── .claude-plugin/
│   └── marketplace.json    # Registry pointing to standalone plugin repos
├── README.md               # Installation instructions
└── CLAUDE.md               # This file
```

## Adding a Plugin

Add an entry to `.claude-plugin/marketplace.json` with `source` pointing to the plugin's standalone GitHub repo.

## Related Repos

- **jbctech-claude-marketplace** -- Internal consulting tools (private)
- **sr-router** -- LLM request router plugin
- **mcp-outlook-mac** -- Outlook MCP server plugin
