# dist

Aquí se publican los instaladores **`CL-Desktop-*.exe`** (rama `stage`), empujados por CI desde [client-lottery-app](https://github.com/pegarifa/client-lottery-app), junto con los APK (**`CL-Mobile-*.apk`**) y el manifiesto **`version.json`** (actualizar al publicar nuevas versiones).

No edites los `.exe` / `.apk` a mano si usás solo el workflow de publicación; el JSON del manifiesto sí se mantiene en git con los campos `latest`, URLs y hashes alineados a los binarios.
