# NeoForge 26.1.2 Generator

A plugin for MCreator 2026.3 that adds the Minecraft 26.1.x Java Edition generators back.
From the third 2026.3 snapshot on, MCreator only ships the 1.21.1 and 26.3.x generators.
This plugin keeps NeoForge 26.1.2 usable next to them.

## What is included

- NeoForge 26.1.2 generator, with the same mod element support as in the second 2026.3 snapshot
- Minecraft 26.1.x data pack and resource pack generators (the NeoForge generator depends on them)

## Compatibility

- MCreator 2026.3 snapshot 3 (2026.03.44621) and later 2026.3 releases
- Not for earlier snapshots: they still ship this generator built in

New procedure blocks added in snapshot 3 (for example "is entity moving" or "can item repair item") are not available for 26.1.2.

## Installation

1. Create a zip with `plugin.json` at its root and the folders `neoforge-26.1.2`, `datapack-26.1.x` and `resourcepack-26.1.x` next to it (or download the zip from the releases, if one is published).
2. Put the zip in `<user home>/.mcreator/plugins`.
3. Restart MCreator.

## License

GPL-3.0-or-later, with MCreator's additional permission for code generator templates. See `LICENSE` and `NOTICE`.
This is a modified copy of MCreator's generator files and not an official MCreator product.
