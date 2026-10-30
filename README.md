# Visor territorial · Entidades religiosas de Facatativá

Visor web (Leaflet) con trazo urbano, microterritorios, barrios, denominación,
tipo de entidad (ER / OBF), personería jurídica y foto de cada entidad.

## Estructura
- `index.html` → el visor (datos geográficos y de entidades incluidos)
- `fotos/` → una foto por entidad (JPG comprimido)
- `data/entidades.json` → datos de entidades en JSON (base para el dashboard)

## Publicar con GitHub Pages
1. Crear un repositorio nuevo en GitHub y subir todo el contenido de esta carpeta.
2. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
3. En 1–2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Próximos pasos (dashboard)
Cada Excel nuevo se convierte a JSON y se guarda en `data/`. El dashboard
se agrega como `dashboard.html` en la misma carpeta.
