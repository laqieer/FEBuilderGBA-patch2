# FEBuilderGBA-patch2

This repository contains patches for FEBuilderGBA, separated from the main repository for independent versioning and faster updates.

## Structure

- `FE6/` - Fire Emblem 6 (Binding Blade) patches
- `FE7J/` - Fire Emblem 7 (Blazing Blade) Japanese patches
- `FE7U/` - Fire Emblem 7 US/International patches
- `FE8J/` - Fire Emblem 8 (Sacred Stones) Japanese patches
- `FE8U/` - Fire Emblem 8 US/International patches

## Version Tracking

Versioning is handled via git — the commit history is the version history.
To check the current version: `git log -1 --format="%h %s"`

## Usage

This repository is included in the main FEBuilderGBA repository as a git submodule:

```bash
git submodule update --init --recursive
```

## Mirrors

For users in mainland China, a Gitee mirror is kept in sync automatically on every push to `master`:

- **GitHub**: `https://github.com/laqieer/FEBuilderGBA-patch2.git`
- **Gitee**: `https://gitee.com/laqieer/FEBuilderGBA-patch2.git`

FEBuilderGBA automatically selects the appropriate source based on the language / release source setting in Options.

## Contributing

To contribute patches:

1. Fork this repository
2. Add your patch to the appropriate game directory
3. Follow the existing patch structure (PATCH_*.txt descriptor file + assets)
4. Submit a pull request
5. Wait for review and merge

## Patch Structure

Each patch should contain:
- `PATCH_PatchName.txt` - Patch descriptor with metadata
- Supporting files (`.event`, `.s`, `.dmp`, etc.)

## License

Patches are provided as-is under various licenses. Check individual patch directories for specific license information.

## Main Repository

This is a submodule of the main FEBuilderGBA project:
https://github.com/laqieer/FEBuilderGBA

## History

Extracted from main FEBuilderGBA repository on 2026-02-25 to enable independent patch versioning and faster split updates.
