# Palepale CLI downloads

Official Palepale CLI binaries and SHA-256 checksums are published in [Releases](https://github.com/amangly/palepale-releases/releases). This repository contains downloads and documentation; source code is maintained privately.

| Platform | Release asset |
| --- | --- |
| Windows x64 | `palepale-x86_64-pc-windows-msvc.exe` |
| macOS Apple Silicon | `palepale-aarch64-apple-darwin` |
| Linux x64 | `palepale-x86_64-unknown-linux-musl` |

Rename your platform's downloaded binary to `palepale.exe` on Windows or `palepale` on macOS/Linux, and place it in a folder you can write to. On macOS/Linux, make it executable. Verify its SHA-256 against the release's `SHA256SUMS`.

Published CLI builds check for a newer release when you open an interactive session, at most once per day. Run `palepale update` to check immediately. Restart after an update to use the new version. Your saved account connection, settings and conversations stay in your CLI home directory.

To disable background updates, set `auto_update = false` in `~/.palepale/config.toml`, or set `PALEPALE_NO_UPDATE=1`.

The first release is pending publication. More information: [palepale.tech](https://palepale.tech).