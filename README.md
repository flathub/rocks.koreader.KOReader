# KOReader (rocks.koreader.KOReader)

## Permissions rationale

1. Read and manage documents:

- host `--filesystem=host`
- remote mountpoints `--filesystem=xdg-run/gvfs`

2. Use gamepads as input devices

- `--device=all`, flathub doesn't support `--device=input` yet.
