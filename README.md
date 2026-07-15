# Carlos Guerra - Sitio Web

Sistemas de ventas digitales, growth hacking y marketing digital.
Speaker, mentor y capacitador.

## Estructura del sitio

| URL | Archivo | Descripcion |
|-----|---------|-------------|
| `/` | `index.html` | Home = calculadora de fugas (VER NOTA ABAJO) |
| `/sobre-mi/` | `sobre-mi/index.html` | Pagina de speaker / mentor / capacitador |
| `/taller-ventas-digitales-ia/` | `taller-ventas-digitales-ia/index.html` | Landing del taller de 6 dias |

## IMPORTANTE: la home (`/`)

El `index.html` de la raiz es **temporal** y solo redirige a `/sobre-mi/`.
La home real es la **calculadora de fugas**, que vive fuera de este repo.

Para dejarla lista:
1. Reemplaza `index.html` con el HTML de la calculadora de fugas.
2. Pegale los 4 bloques de `snippet-conexion-fugas.html`
   (pixel de Meta, tracking de Lead, schema SEO y enlaces internos).

## Meta Pixel

Las paginas `/sobre-mi/` y `/taller-ventas-digitales-ia/` ya incluyen:
- Pixel de Meta (ID `267313755144016`) con `PageView`.
- Evento `Lead` que se dispara al hacer clic en botones de WhatsApp.

La calculadora de fugas necesita que le pegues el mismo pixel
(esta en `snippet-conexion-fugas.html`).

## Como publicar en GitHub Pages

1. Crea un repo nuevo en GitHub (ej. `carlosguerra-web`).
2. Sube todos los archivos de esta carpeta a la rama `main`.
3. En el repo: **Settings -> Pages**.
4. En "Source" elige la rama `main` y carpeta `/ (root)`. Guarda.
5. GitHub Pages publicara el sitio en unos minutos.

### Dominio propio (carlosguerraoficial.com)

- El archivo `CNAME` ya apunta a `carlosguerraoficial.com`.
- En tu proveedor de dominio, configura los DNS de GitHub Pages:
  - Registros `A` a: `185.199.108.153`, `185.199.109.153`,
    `185.199.110.153`, `185.199.111.153`
  - O un `CNAME` de `www` a `<tu-usuario>.github.io`.
- En **Settings -> Pages** activa "Enforce HTTPS" cuando el dominio verifique.

## Archivos de apoyo

- `sitemap.xml` - mapa del sitio para buscadores.
- `robots.txt` - permite indexacion + apunta al sitemap.
- `snippet-conexion-fugas.html` - bloques para pegar en la calculadora.
- `.nojekyll` - evita el procesamiento Jekyll de GitHub.

## Marca

- Negro `#0d0d0d` / Amarillo `#FFC107` / Blanco / Grises.
- Tipografia: Montserrat.
