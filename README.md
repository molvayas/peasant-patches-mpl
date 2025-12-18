# peasant-patches-mpl

MPL-2.0 licensed patches for the Peasant Brave browser build.

## Overview

These patches modify existing Brave Browser code and are derivative works licensed under MPL-2.0 (the same license as Brave Browser).

## Patches

| Patch | Description |
|-------|-------------|
| `001-brave-browser-main-parts.patch` | Add launch authorization check |
| `002-chrome-browser-policy-connector.patch` | Inject hardcoded policy provider |
| `003-brave-policy-build.patch` | Update BUILD.gn for policy provider |

## Usage

These patches are applied using `quilt` during the build process:

```bash
export QUILT_PATCHES=/path/to/peasant-patches-mpl/patches
export QUILT_SERIES=/path/to/peasant-patches-mpl/series
cd /path/to/brave-core
quilt push -a
```

## License

MPL-2.0 - See [LICENSE](LICENSE)




