## GitHub Copilot Chat

- Extension Version: 0.22.4 (prod)
- VS Code: vscode/1.95.2
- OS: Mac

## Network

User Settings:
```json
  "github.copilot.advanced": {
    "debug.useElectronFetcher": true,
    "debug.useNodeFetcher": false
  }
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 20.201.28.148 (2 ms)
- DNS ipv6 Lookup: ::ffff:20.201.28.148 (23 ms)
- Electron Fetcher (configured): HTTP 200 (390 ms)
- Node Fetcher: HTTP 200 (211 ms)
- Helix Fetcher: HTTP 200 (515 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: Error: getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- DNS ipv6 Lookup: Error: getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Electron Fetcher (configured): HTTP 200 (390 ms)
- Node Fetcher: Error: getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Helix Fetcher: Error: getaddrinfo ENOTFOUND api.individual.githubcopilot.com

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).