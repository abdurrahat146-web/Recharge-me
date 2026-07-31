# Recharge Please! ⚡

A 100-level puzzle game clone — drag colored plugs through the grid to matching sockets without crossing wires.

## How to get your APK (no local build needed)

1. Create a **new GitHub repo** (public or private).
2. Upload **all files in this folder** (keep the folder structure — especially the `.github/workflows/build-apk.yml` file and the `www/` folder).
3. GitHub Actions will run automatically on push. Or go to your repo → **Actions tab** → "Build APK" → **Run workflow**.
4. Wait ~3-5 minutes for the build to finish (green checkmark).
5. Click on the finished run → scroll to **Artifacts** → download **recharge-please-apk** (a zip containing the `.apk`).
6. Unzip it, transfer `app-debug.apk` to your phone, and install it (you may need to allow "install from unknown sources").

## Play in browser instead (zero install)

Just open `www/index.html` in any browser — works instantly, no APK needed, no storage used.

## Notes

- The APK is a **debug build** — small, unsigned, fine for personal use.
- 100 levels are **procedurally generated** from a fixed seed, so they're the same every time but don't need to be hand-authored/stored.
- Progress (unlocked levels) is saved in the browser/app's local storage.
