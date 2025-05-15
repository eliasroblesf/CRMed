## GitHub Copilot Chat

- Extension Version: 0.27.0 (prod)
- VS Code: vscode/1.100.0
- OS: Windows

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.114.5 (8 ms)
- DNS ipv6 Lookup: Error (4 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (13 ms)
- Electron fetch (configured): HTTP 200 (214 ms)
- Node.js https: HTTP 200 (220 ms)
- Node.js fetch: HTTP 200 (232 ms)
- Helix fetch: HTTP 200 (266 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.113.22 (6 ms)
- DNS ipv6 Lookup: Error (5 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (3 ms)
- Electron fetch (configured): HTTP 200 (211 ms)
- Node.js https: HTTP 200 (233 ms)
- Node.js fetch: HTTP 200 (221 ms)
- Helix fetch: HTTP 200 (231 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).