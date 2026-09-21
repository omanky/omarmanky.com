source "https://rubygems.org"

# Las mismas versiones que usa GitHub Pages (https://pages.github.com/versions/, github-pages 232).
# No se usa la gema «github-pages» porque una de sus dependencias (commonmarker, que este sitio no necesita)
# no se instala con Ruby 4. El día de publicar, GitHub Pages compila con estas mismas versiones.
gem "jekyll", "3.10.0"
gem "liquid", "4.0.4"
gem "kramdown", "2.4.0"
gem "kramdown-parser-gfm", "1.1.0"
gem "rouge", "3.30.0"

group :jekyll_plugins do
  gem "jekyll-sitemap", "1.4.0"   # único plugin; está en la lista permitida de GitHub Pages
end

# Solo para trabajar en local con un Ruby reciente, que ya no trae estas bibliotecas incluidas.
gem "webrick"
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "ostruct"
