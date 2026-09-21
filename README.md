# cloudbase-sites

CloudBase Sites Plugin — create, deploy, and manage Vite web apps on CloudBase

This repository is automatically synced from [TencentCloudBase/CloudBase-MCP](https://github.com/TencentCloudBase/CloudBase-MCP)
(`plugin/cloudbase-sites/`, Open Plugin Spec artifacts only).

A CNB mirror is synced the same way as [cloudbase-skills](https://github.com/TencentCloudBase/cloudbase-skills):
this repo's `.github/workflows/sync-to-cnb.yml` mirrors to
[https://cnb.cool/tencent/cloud/cloudbase/cloudbase-sites-plugin](https://cnb.cool/tencent/cloud/cloudbase/cloudbase-sites-plugin).

Claude Code / Codex native marketplace install continues to use the main
[CloudBase-MCP](https://github.com/TencentCloudBase/CloudBase-MCP) repository.

## Installation

```bash
# Default (GitHub)
npx plugins add TencentCloudBase/cloudbase-sites-plugin -y --scope user

# Fallback when GitHub clone fails (CNB mirror — use full URL; short owner/repo always hits GitHub)
npx plugins add https://cnb.cool/tencent/cloud/cloudbase/cloudbase-sites-plugin.git -y --scope user
```

## Agent Plugins

This plugin conforms to the [Agent Plugins 1.0.0 specification](https://agent-plugins.org/specification)
(the standard previously published as Open Plugin Spec).

## License

MIT
