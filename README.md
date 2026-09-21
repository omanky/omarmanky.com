# omarmanky.com

Sitio personal de Omar Manky. Jekyll, tal como lo compila GitHub Pages: sin plugins propios, sin JavaScript, sin analítica.

- `_publicaciones/` — una ficha por publicación. Se generan desde el catálogo del autor; no se editan a mano.
- `_cuaderno/` — las notas del Cuaderno, una por archivo Markdown.
- `cuaderno/feed.xml` — el feed Atom del Cuaderno (RSS), con las notas completas. Es una plantilla: se actualiza solo con cada nota.
- `_data/` — temas, «Estos días», trabajos por tema, escritura pública y charlas.
- `_layouts/`, `_includes/`, `assets/` — plantillas, hoja de estilos, fuentes y foto.

Para verlo en local: `bundle install` y `bundle exec jekyll serve`.

Tipografías: Newsreader e IBM Plex Mono, ambas con licencia SIL Open Font License, servidas desde `assets/fonts/`.
