# carvasolutions/releases

Repositorio público de **artefactos de distribución** (instaladores Windows, APK, manifiesto) para **CL** (Carvasolutions).

## Windows — instalador Inno

- **Rama:** `stage`
- **Ruta:** `dist/CL-Desktop-*.exe`

Los binarios los sube el workflow **Publish Windows installer to releases repo** del repo [client-lottery-app](https://github.com/carvasolutions/client-lottery-app) (requiere el secret `RELEASES_REPO_TOKEN` allí).

**URL raw** para el manifiesto (`windows_installer_url`), ejemplo:

`https://github.com/carvasolutions/releases/raw/stage/dist/CL-Desktop-1.0.0-b3.exe`

Documentación: [client-lottery-app/docs/releases-repo-setup.md](https://github.com/carvasolutions/client-lottery-app/blob/main/docs/releases-repo-setup.md)
