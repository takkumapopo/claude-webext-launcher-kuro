# KURO patch

This fork keeps the upstream Claude WebExtension Launcher while changing only the update sources needed for the KURO setup.

## Changes

- Usage Tracker updates come from `takkumapopo/claude-usage-tracker-kuro`.
- Launcher self-updates come from `takkumapopo/claude-webext-launcher-kuro`.
- Claude Toolbox and Claude Desktop compatibility data continue to come from their upstream sources.
- Launcher version uses a fourth numeric segment (for example `3.3.3.1`) to distinguish the KURO build.

## Upstream

`https://github.com/lugia19/Claude-WebExtension-Launcher`

The local checkout keeps an `upstream` remote. Merge upstream deliberately, preserve the two KURO update-source changes, test, then publish a new KURO release.
