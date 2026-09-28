# omarmanky.com

Sitio personal de Omar Manky. Jekyll, tal como lo compila GitHub Pages: sin plugins propios. El único JavaScript es el contador de Cloudflare Web Analytics (sin cookies), en `_layouts/default.html`.

- `_publicaciones/` — una ficha por publicación. Se generan desde el catálogo del autor; no se editan a mano.
- `_cuaderno/` — las notas del Cuaderno, una por archivo Markdown. Cada nota puede llevar `bajada` y `bajada_en`, la frase que sale bajo su título en la portada.
- `cuaderno/feed.xml` — el feed Atom del Cuaderno (RSS), con las notas completas. Es una plantilla: se actualiza solo con cada nota.
- `_data/` — temas, «Estos días», trabajos por tema, escritura pública, charlas y `textos.yml` (las cadenas de la interfaz en español e inglés).
- `en/` — la versión en inglés: portada, About, Publications y Notebook. Una página es inglesa si declara `lang: en`; `traduccion:` apunta a su hermana en el otro idioma.
- `_layouts/`, `_includes/`, `assets/` — plantillas, hoja de estilos, fuentes y las dos fotos (la de la portada y la fija del bloque «Del cuaderno», declarada en `_data/textos.yml`).

Para verlo en local: `bundle install` y `bundle exec jekyll serve`.

Tipografías: Newsreader e IBM Plex Mono, ambas con licencia SIL Open Font License, servidas desde `assets/fonts/`.
