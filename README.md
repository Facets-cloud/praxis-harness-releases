# Praxis releases

Release binaries for **Praxis** (`prx`) — a coding agent that is also a library:
an interactive terminal client, a headless runner and an embeddable SDK in one
pure-Go binary — and the **Praxis desktop app** for macOS.

This repository holds releases only. Every release is published here
automatically.

## Install

**Homebrew** (macOS and Linux):

```sh
brew install facets-cloud/tap/prx
```

Upgrade with `brew upgrade prx`.

**Archive**: download `praxis-harness_<version>_<os>_<arch>.tar.gz` for your
platform from [Releases](https://github.com/Facets-cloud/praxis-harness-releases/releases),
then:

```sh
tar xzf praxis-harness_<version>_<os>_<arch>.tar.gz && ./prx
```

Each release lists SHA-256 sums in `checksums.txt`.

**Desktop app** (macOS, experimental): download `Praxis-<version>.zip`, unzip,
and move `Praxis.app` to `/Applications`. It is ad-hoc signed for now, so run
`xattr -dr com.apple.quarantine /Applications/Praxis.app` once (or right-click >
Open).

## Staying current

`prx upgrade` and the desktop app's updater read this repository; no GitHub
account or token is needed. A prx installed with Homebrew upgrades with
`brew upgrade prx`.
