# homebrew-tap

Homebrew tap for [Rome](https://github.com/ompatel-24/rome), which runs any
interactive CLI in a pseudo-terminal and lets you drive the same session from
your phone's browser on a trusted local network.

## Install Rome

```bash
brew install ompatel-24/tap/rome
rome version
```

Or tap first, then install by name:

```bash
brew tap ompatel-24/tap
brew install rome
```

Formulae are available for macOS and Linux on amd64 and arm64. See the
[Rome repository](https://github.com/ompatel-24/rome) for usage, security
notes, and other install options.

## Formulae

| Formula | Status |
| --- | --- |
| `rome` | Current. Published automatically by Rome's release workflow. |
| `ivy` | Legacy. Ivy 0.1.0, the project's name before it was renamed to Rome. Not updated. |

Upgrading from Ivy doesn't happen in place:

```bash
brew uninstall ivy
brew install ompatel-24/tap/rome
```
