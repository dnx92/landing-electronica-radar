Blog técnico
=================

Se agregó una carpeta /blog con artículos estáticos pensados para SEO y AdSense.

Archivos:

- blog/index.html -> listado de artículos
- blog/variadores.html
- blog/reparar-vs-comprar.html
- blog/probar-fuente-conmutada.html

Cómo agregar un artículo nuevo:

1. Crear `blog/mi-articulo-slug.html` con meta tags (title, description) y JSON-LD básico.
2. Incluir un slot de AdSense en el contenido (ver ejemplos existentes).
3. Añadir un enlace al artículo desde `blog/index.html` (opcional).
4. `git add blog && git commit -m "feat(blog): agregar articulo Mi Articulo" && git push`

Notas AdSense:
- El script global de AdSense ya está en `index.html` en el head.
- Usar `data-full-width-responsive="true"` y `data-ad-format="auto"` para mejor adaptabilidad móvil.
