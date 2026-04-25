# homebrew-netspeed-cli

Homebrew tap for [netspeed-cli](https://github.com/mapleDevJS/netspeed-cli) — a command-line internet bandwidth tester using speedtest.net servers.

## Install

```bash
brew install mapleDevJS/homebrew-netspeed-cli/netspeed-cli
```

## Features

- Download, upload, and latency testing against speedtest.net servers
- Latency under load with jitter measurement
- Peak speed detection
- Connection quality rating (Excellent → Poor)
- Real server distance via haversine formula
- Multiple output formats: simple, JSON, CSV
- Shell completions (bash, zsh, fish)
- Persistent test history

## Usage

```bash
netspeed-cli
netspeed-cli --json
netspeed-cli --csv
netspeed-cli --bytes
netspeed-cli --server 1234
netspeed-cli --list
```

## Update

```bash
brew upgrade netspeed-cli
```

## Uninstall

```bash
brew uninstall netspeed-cli
```

## License

MIT
