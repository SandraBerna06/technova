# TechNova — Sistema de diseño (para agentes IA)

## Estilo
Minimalismo premium inspirado en Apple.com: mucho espacio en blanco, tipografía limpia, producto como protagonista.
Layout solo con **Flexbox** (sin Grid ni floats). Contenedor de ancho variable: `1000px`–`2000px`.

## Colores (`:root`)
| Variable | Valor | Uso |
|---|---|---|
| `--bg` | `#f5f5f7` | Fondo de página, hero y aside |
| `--white` | `#ffffff` | Contenedor y tarjetas |
| `--text` | `#1d1d1f` | Texto principal (nunca `#000`) |
| `--muted` | `#6e6e73` | Texto secundario |
| `--accent` | `#0066cc` | Botones y enlaces |
| `--accent-hover` | `#0077ed` | Hover |
| `--border` | `#d2d2d7` | Bordes |

## Tipografía
`Inter` (Google Fonts). H1: 3.5rem / 700 / `letter-spacing: -1.5px`. H2-H3: 600. Párrafo: 400, 16px.

## Unidades
- **Absolutas (px):** ancho del contenedor, cabecera (60px), márgenes del layout, aside (280px).
- **Relativas (rem, %):** tipografía, botones, tarjetas.

## Componentes
- **Botón:** fondo acento, texto blanco, `border-radius: 20px`.
- **Tarjeta:** fondo blanco, `border-radius: 16px`, sombra suave, sube 5px en hover.
- **Menú:** submenú con `opacity` + `visibility` al pasar el ratón. Transiciones `0.3s ease`.
- **Botón fijo:** `position: fixed; bottom: 20px; right: 20px;`.
- **Iconos:** Font Awesome 6. **Imágenes:** siempre con `alt`, sin recortar (`height: auto`).

## Estructura de carpetas
```
index.html
design.md
css/styles.css
img/*.svg
```