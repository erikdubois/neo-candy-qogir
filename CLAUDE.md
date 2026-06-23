# CLAUDE.md — neo-candy-qogir

## Project overview

Standalone repo for the **neo-candy-qogir** folder-icon theme — the same folder set as
`erikdubois/surfn-qogir` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-qogir/` — folders only. Packaged as `neo-candy-qogir-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-qogir/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
