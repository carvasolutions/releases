# dist

Aquí se publican los instaladores **`CL-Desktop-*.exe`** (rama `stage`), empujados por CI desde [client-lottery-app](https://github.com/carvasolutions/client-lottery-app), los instaladores Win7 **`CL-Desktop-*-win7.exe`** desde [client-lottery-desktop-legacy](https://github.com/carvasolutions/client-lottery-desktop-legacy), los APK (**`CL-Mobile-*.apk`**) y los manifiestos:

- **`version.json`** — Flutter / Android / Windows 10+ (sin campos `*_win7`)
- **`version-win7.json`** — CL Legacy Win7 (canal independiente)

No edites los `.exe` / `.apk` a mano si usás solo el workflow de publicación; los JSON del manifiesto sí se mantienen en git con los campos `latest`, URLs y hashes alineados a los binarios.
