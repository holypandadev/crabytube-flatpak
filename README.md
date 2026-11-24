# CrabyTube Flatpak repository

This repository holds the Flatpak repository of [CrabyTube](https://github.com/holypandadev/crabytube),
which GitHub Pages serves at <https://holypandadev.github.io/crabytube-flatpak/>. Its files are
written by `scripts/flatpak-repo.py` in CrabyTube's repository at each release, and only the current
version is kept.

Install CrabyTube from it with:

```bash
flatpak install --user https://holypandadev.github.io/crabytube-flatpak/crabytube.flatpakref
```

The commits and the summary are signed with the key in `crabytube.gpg`. The source code of what is
published here, and its license (GPL-3.0-or-later), are in CrabyTube's repository.
