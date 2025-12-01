# claude-marketplace

A curated collection of [Claude Code](https://claude.ai/code) plugins for software development workflows.

## Usage

Add this marketplace to Claude Code:

```bash
claude marketplace add michellepellon/claude-marketplace
```

Browse available plugins:

```bash
claude marketplace search
```

Install a plugin:

```bash
claude plugin install claude-workbench
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [claude-workbench](https://github.com/michellepellon/claude-workbench) | 19 skills and 9 commands for Python, JS/TS, SQL, shell scripting, SEO, data visualization, and more |

## Contributing

To submit a plugin to this marketplace:

1. Fork this repository
2. Add your plugin to `index.json`:
   ```json
   {
     "name": "your-plugin-name",
     "description": "Brief description",
     "repository": "username/repo-name",
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
