# source — releases

Public release artifacts + auto-update manifest for the **source** video player.

The application source code lives in a separate private repository. This repo holds
only the built installers and the `latest.json` update manifest that the app's in-app
updater reads. Releases are published automatically by CI on each `vX.Y.Z` tag.
