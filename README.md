# Zo CLI

Official standalone downloads for the Zo command-line interface.

## Install

On macOS 15+ or Linux with glibc 2.35+, using arm64 or x64:

```sh
curl -fsSL https://zo.computer/install.sh | sh
export PATH="$HOME/.local/bin:$PATH"
zo --version
zo login
```

The executable includes Node.js; you do not need to install Node or npm. Sign-in requires a Zo workspace with System API access enabled.

Each [release](https://github.com/zocomputer/zo-cli/releases) contains four platform archives, the installer, SHA-256 checksums, and release metadata. macOS executables are Developer ID signed and notarized. Published releases are immutable.

This repository holds downloads and release metadata. Development takes place in Zo's private source repository.

Visit [Zo](https://zo.computer) to learn more.
