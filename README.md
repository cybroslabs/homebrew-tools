# cybros labs Homebrew Tap

A [Homebrew](https://brew.sh) tap containing casks for cybros labs CLI tools.

## Prerequisites

[Homebrew](https://brew.sh) must be installed on your macOS system.

To install Homebrew, open Terminal and run:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Usage

### Add this tap

```sh
brew tap cybroslabs/homebrew-tools https://github.com/cybroslabs/homebrew-tools
```

### Browse available tools

```sh
brew search cybroslabs/homebrew-tools
```

### Install a tool

```sh
brew install <tool-name>
```

### Update a tool

```sh
brew update
brew upgrade <tool-name>
```

### Uninstall a tool

```sh
brew uninstall <tool-name>
```

## How it works

This repository serves as a Homebrew tap -- a collection of cask definitions that describe how to download and install each tool. Each cask contains the download URLs, checksums, and binary paths for the corresponding tool.

Casks are automatically generated and updated by CI/CD pipelines whenever a new version of a tool is released. Manual edits to cask files are not necessary and will be overwritten on the next release.

## About

Published and maintained by [cybros labs](https://www.cybroslabs.com).
