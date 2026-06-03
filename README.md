# getdebug Homebrew tap

Homebrew tap for the [getdebug](https://getdebug.dev) CLI.

## Install

```sh
brew install getdebug-ai/tap/getdebug
```

That's it. The formula pulls the matching binary for your platform (macOS arm64 / x86_64, Linux arm64 / x86_64) from the [getdebug-ai/cli](https://github.com/getdebug-ai/cli) GitHub releases.

## Upgrade

```sh
brew update
brew upgrade getdebug
```

## Uninstall

```sh
brew uninstall getdebug
brew untap getdebug-ai/tap
```

## What is this?

A [Homebrew tap](https://docs.brew.sh/Taps) is a third-party formula source. This one serves a single formula — `getdebug` — that resolves to the right pre-built binary for your OS + architecture.

Releases are cut from the [private monorepo](https://github.com/getdebug-ai) by `scripts/build-cli-binaries.sh`; this tap is updated when a new version goes live on the [cli releases page](https://github.com/getdebug-ai/cli/releases).

## Other install methods

- npm: `npm install -g @getdebug/cli` — bundles a tiny launcher that downloads the platform binary from GitHub Releases on first run.
- Direct download: grab the archive for your platform from [getdebug-ai/cli releases](https://github.com/getdebug-ai/cli/releases).
- Build from source: see the [cli repo](https://github.com/getdebug-ai/cli).
