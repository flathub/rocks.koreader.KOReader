# KOReader (rocks.koreader.KOReader)

This repo builds KOReader flathub packages based on the latest released upstream binaries,
for x86_64 and aarch64.

## Permissions rationale

1. Read and manage documents:

- host `--filesystem=host`
- remote mountpoints `--filesystem=xdg-run/gvfs`

2. Use gamepads as input devices

- `--device=all`, flathub doesn't support `--device=input` yet.
