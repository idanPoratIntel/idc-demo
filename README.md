# test-marketplace-demo

A demo Copilot agent plugins marketplace, structured like [github/copilot-plugins](https://github.com/github/copilot-plugins).

## Structure

```
.github/plugin/marketplace.json   # marketplace manifest
plugins/
  demo/
    README.md
    skills/
      say-hi/SKILL.md
```

## Plugins

| Plugin | Description |
|--------|-------------|
| [demo](plugins/demo) | Demo plugin with a `say-hi` skill. |
