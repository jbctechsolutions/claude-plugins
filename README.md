# Claude Plugins by JBC Tech Solutions

Commercial Claude Code plugins from JBC Tech Solutions.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [sr-router](https://github.com/jbctechsolutions/sr-router) | Intelligent LLM request router -- routes requests to the cheapest model meeting quality requirements |
| [mcp-outlook-mac](https://github.com/jbctechsolutions/mcp-outlook-mac) | MCP server for Microsoft Outlook on macOS |

## Installation

Add this marketplace to your Claude Code settings (`~/.claude/settings.json`):

```json
{
  "extraKnownMarketplaces": [
    {
      "name": "jbc-tech-solutions",
      "source": {
        "source": "github",
        "repo": "jbctechsolutions/claude-plugins"
      }
    }
  ]
}
```

Then install plugins using:

```
/install sr-router
/install mcp-outlook-mac
```

## About

This is a thin registry that points to standalone plugin repositories. Each plugin is maintained in its own repo with full documentation, tests, and releases.

For internal consulting tools, see the separate [jbctech-claude-marketplace](https://github.com/jbctechsolutions/jbctech-claude-marketplace) repository.
