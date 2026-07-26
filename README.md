# ZenTerm

A dev-first terminal.

Pixel-perfect panes, drawers, and tool floats, orchestrated into workspaces a
keystroke away, with a keyboard-first way through all of it. It runs on a
libghostty core, which renders the text and runs the shell.

## Download

Grab the latest `ZenTerm-<version>-arm64.dmg` from
[Releases](https://github.com/zen-term/zen-term-releases/releases), open it, and
drag ZenTerm to Applications.

**Requirements:** macOS 14 or later, Apple Silicon.

Every build is Developer ID signed and notarized by Apple, so it opens without a
warning.

## Getting started

[Onboarding](docs/onboarding.md) covers install, the shortcuts worth learning
first, and setting up your first workspace.

Configuration is a plain text file in `~/.config/zen-term/`, and Settings (⌘,)
writes it for you. Annotated references for every option:
[`config`](docs/config/config) for appearance, behavior, tools, and shortcuts,
and [`workspaces`](docs/config/workspaces) for workspaces.

## Neovim

[zen-navigator.nvim](https://github.com/zen-term/zen-navigator.nvim) makes
`Ctrl-hjkl` walk across Neovim splits and ZenTerm panes as one motion. It is
opt-in, and [onboarding](docs/onboarding.md) covers the setup. The socket
contract it is written against is
[documented here](docs/nvim-navigator-protocol.md).

## Issues

Found a bug or have a request? Open an
[issue](https://github.com/zen-term/zen-term-releases/issues) here. Include the
version, which Settings (⌘,) shows at the bottom of the left column.

ZenTerm is closed source. This repository hosts releases and issue tracking.
