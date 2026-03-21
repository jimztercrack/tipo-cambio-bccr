# tipo-cambio-bccr

Sitio estático para mostrar el tipo de cambio del dólar del BCCR usando GitHub Pages y GitHub Actions.

## Archivos
- `index.html`: página pública
- `tipocambio.json`: datos mostrados por la página
- `.github/workflows/actualizar-tipocambio.yml`: actualiza el JSON automáticamente

## Paso importante
Debes crear en GitHub el secret del repositorio:

- **Name:** `BCCR_TOKEN`
- **Value:** tu token del BCCR

Luego activa GitHub Pages desde la rama `main` y la carpeta raíz `/`.
