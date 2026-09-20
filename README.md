# source — releases

Public release artifacts + auto-update manifest for the **source** video player.

The application source code lives in a separate private repository. This repo holds
only the built installers and the `latest.json` update manifest that the app's in-app
updater reads. Releases are published automatically by CI on each `vX.Y.Z` tag.

## Website

The landing page at **https://sourceplayer.app** is served by GitHub Pages from the
[`docs/`](docs/) folder of this repo (no build step: one HTML file, self-hosted fonts,
and a small script that asks the GitHub API for the latest release so the download
buttons always point at the current installers). Edit `docs/index.html` and merge to
publish.
