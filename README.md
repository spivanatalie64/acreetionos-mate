# AcreetionOS MATE Edition

MATE Desktop Community Edition.

> Self-contained archiso profile. Builds standalone from standard Arch mirrors.

## Build

```bash
git clone https://github.com/spivanatalie64/acreetionos-mate.git
cd acreetionos-mate
./build.sh
```

ISO lands in `./ISO/`. CI builds weekly and on push, then publishes a GitHub
release with the ISO asset.

## Layout

| Path | Purpose |
|------|---------|
| `profiledef.sh` | Edition metadata |
| `packages.x86_64` | Static package list |
| `pacman.conf` | Standard Arch mirrors |
| `airootfs/` | Live-environment overlay (DM, configs) |
| `.github/workflows/` | CI: ISO build + lint + release |

## Community

- **Discord:** AcreetionOS Community Server
- **Issues:** https://github.com/spivanatalie64/acreetionos-mate/issues
- **Website:** https://acreetionos.org
