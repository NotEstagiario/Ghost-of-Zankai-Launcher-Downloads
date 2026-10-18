# Ghost of Zankai — Launcher (Windows x64)

Official public launcher downloads for the Ghost of Zankai private playtest. No game source code or full client is stored in this repository.

## Current launcher — 0.0.2 (auto-update)

**Recommended, first-time installation:** [GhostOfZankai-Instalador-Rapido-0.0.2.zip](https://github.com/NotEstagiario/Ghost-of-Zankai-Launcher-Downloads/releases/download/launcher-auto-update-0.0.2-final/GhostOfZankai-Instalador-Rapido-0.0.2.zip)

Extract the small ZIP and double-click `Instalar Ghost of Zankai.cmd`. The installer downloads the Windows launcher, checks its SHA-256, and installs it to `%LOCALAPPDATA%\Programs\GhostOfZankaiLauncher`.

**Alternative:** [Complete Windows launcher package](https://github.com/NotEstagiario/Ghost-of-Zankai-Launcher-Downloads/releases/download/launcher-auto-update-0.0.2-final/GhostOfZankaiLauncher-Win64-0.0.2.zip).

This build includes the in-place launcher self-update worker, verified Oracle downloads, SHA-256 checks, and rollback. Future automatic updates require a signed/current release manifest, a valid authenticated playtest session, and access to the service; they do not ordinarily require downloading the installer again.

**Do not install** the older `launcher-auto-update-0.0.2` release: it was superseded by `launcher-auto-update-0.0.2-final` to correct Electron's physical `app.asar` hash handling.
