# 📸 Session Photos

Drop session photos into this folder and commit them. A GitHub Action will automatically update `gallery.html` with any new images.
It will also open a pull request to copy them to `beardofedu/dnd-level20` under
`april-idea/session-images`. Legacy images under `April-ideas` are removed during the
sync. Configure the `DND_LEVEL20_TOKEN` repository secret with
access to that repository to enable the cross-repository pull request. A fine-grained
PAT needs both **Contents** and **Pull requests** read/write permissions (a classic PAT
needs the `repo` scope).

**Supported formats:** `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.svg`

**Naming convention (recommended):** `session-01-description.jpg`

Photos named with the `session-NN-` prefix will automatically get a "Session N" label in the gallery. The rest of the filename becomes the display title (hyphens and underscores are converted to spaces).
