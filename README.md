# pegarifa/releases

Repositorio público de **artefactos de distribución** (instaladores Windows, etc.) para Pegarifa.

## Windows — instalador Inno

- **Rama:** `stage`
- **Ruta:** `dist/Pegarifa-Setup-*.exe`

Los binarios los sube el workflow **Publish Windows installer to releases repo** del repo [client-lottery-app](https://github.com/pegarifa/client-lottery-app) (requiere el secret `RELEASES_REPO_TOKEN` allí).

**URL raw** para el manifiesto (`windows_installer_url`), ejemplo:

`https://github.com/pegarifa/releases/raw/stage/dist/Pegarifa-Setup-1.0.0-b3.exe`

Documentación: [client-lottery-app/docs/releases-repo-setup.md](https://github.com/pegarifa/client-lottery-app/blob/main/docs/releases-repo-setup.md)
