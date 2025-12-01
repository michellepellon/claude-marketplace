# claude-marketplace

[![GitHub](https://img.shields.io/badge/GitHub-michellepellon%2Fclaude--marketplace-blue)](https://github.com/michellepellon/claude-marketplace)

A curated collection of [Claude Code](https://claude.ai/code) plugins for software development workflows.

## Usage

Add this marketplace to Claude Code (run inside a Claude Code session):

```
/plugin marketplace add michellepellon/claude-marketplace
```

Browse available plugins:

```
/plugin
```

Install a plugin:

```
/plugin install claude-workbench@claude-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [claude-workbench](https://github.com/michellepellon/claude-workbench) | 19 skills and 9 commands for Python, JS/TS, SQL, shell scripting, SEO, data visualization, and more |

## Contributing

To submit a plugin to this marketplace:

1. Fork this repository
2. Add your plugin to `.claude-plugin/marketplace.json`:
   ```json
   {
     "name": "your-plugin-name",
     "description": "Brief description",
     "source": "username/repo-name",
     "tags": ["relevant", "tags"]
   }
   ```
3. Open a pull request

### Plugin Requirements

- Must have a valid `.claude-plugin/manifest.json`
- Must include a README with installation instructions
- Must be publicly accessible on GitHub

## License

MIT
