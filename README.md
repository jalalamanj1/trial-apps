# Trial Apps

Windows trial installers for two independent applications. Each application is
versioned and released separately, with its own tag namespace and GitHub Release.

| Application | Version | Release tag | Installer |
| --- | --- | --- | --- |
| Edara Trial | 1.0.0 | `edara-v1.0.0` | `Edara-Trial-Setup-1.0.0.exe` |
| Murshid Trial (مرشد تجريبي) | 2.1.0 | `murshid-v2.1.0` | `murshid-trial-2.1.0-win-x64.exe` |

## Downloads

Installers are published as assets on the Releases page:

<https://github.com/jalalamanj1/trial-apps/releases>

- Edara Trial 1.0.0 — <https://github.com/jalalamanj1/trial-apps/releases/tag/edara-v1.0.0>
- Murshid Trial 2.1.0 — <https://github.com/jalalamanj1/trial-apps/releases/tag/murshid-v2.1.0>

## Notes

- The installers are distributed as release assets and are intentionally not
  committed to Git history (each is over 100 MB).
- Releases are independent: publishing a new Murshid build does not affect the
  Edara release line, and vice versa.
- Installer binaries are uploaded exactly as built; they are never renamed,
  modified, or rebuilt.
