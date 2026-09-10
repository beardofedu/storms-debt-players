# 📸 Session Photos

Drop session photos into this folder and commit them. A GitHub Action will automatically update `gallery.html` with any new images.
It will also open a pull request to copy them to `beardofedu/dnd-level20` under
`April-ideas/session-images`. Configure the `DND_LEVEL20_TOKEN` repository secret with
write access to that repository to enable the cross-repository pull request.

**Supported formats:** `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.svg`

**Naming convention (recommended):** `session-01-description.jpg`

Photos named with the `session-NN-` prefix will automatically get a "Session N" label in the gallery. The rest of the filename becomes the display title (hyphens and underscores are converted to spaces).
