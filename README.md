# FocusShield releases

Public release feed for the FocusShield in-app updater. The source repository is private.

- Latest release: https://github.com/Aniket-Man/FOCUSSHEILD-releases/releases/latest
- The app reads this endpoint **unauthenticated**, so no GitHub token ships inside the APK.
- Each release attaches the signed APK as an `.apk` asset; the updater ignores every other asset.
- Publish new versions **here**, not to the private source repository — a release there is invisible
  to the updater (unauthenticated callers receive 404).

See `docs/UPDATE_SYSTEM.md` in the source repository for the full update architecture.