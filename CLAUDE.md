# IA House Bienes Raíces · landings

Landings de propiedades de Alejandro Blanco (Director Comercial, IA House Bienes Raíces, Toluca).
Contacto en todas las páginas: WhatsApp 722 516 01 88 (wa.me/527225160188). Slogan: "Invierte Inteligente".

## Reglas de marca
- Solo colores del manual: navy #0E2A47, deep #0A1F35, acero #2F5F8F, gris #A9B4C2 y siempre el toque vino #8F3A3A. Nada de rosa.
- Logo sin fondo blanco (monograma en SVG dentro de cada index.html).
- Cifras completas ($10,500,000), nunca "10.5M" o "15K".
- Sin espacios blancos a los lados; fotos nítidas.
- Textos en español, cortos, con llamada a la acción a WhatsApp.

## Estructura
- `index.html` redirige a la landing activa.
- `mexicaltzingo/` Residencia campestre con caballerizas, Col. San Isidro, Mexicaltzingo.
  - `hero.mp4` loop sin audio; `recorrido.mp4` video completo (vertical 1080x1440 reducido).
  - `img/` fotos (por ahora fotogramas del video; reemplazar con las fotos nuevas del shooting).
  - En el `<script>` final: `YOUTUBE_ID` (pega el ID y el video de YouTube reemplaza al mp4).
  - En el `<head>`: lugar para el código del Píxel de Meta. Eventos ya conectados: `Lead` (formulario) y `Contact` (clic en WhatsApp).

## Datos de la propiedad (Mexicaltzingo)
- Precio $10,500,000 · venta de contado · régimen ejidal · calle de llegada de terracería.
- 2,496 m² de terreno bardeado · casa de 2 niveles 270 m² · caballerizas y anexos 160 m² · 3 recámaras (planta alta).
- Pisos de parota y duela, muros de sillar, columnas de cantera, techos de madera, vitral, vidrios blindados.
- Pozo propio, cisterna, caseta, portón, jardines y terraza techada. Construcción de 4–5 años.
- Estimación de valor (oct 2026): reposición $12,277,579; rango de mercado $10.07–$10.80 M; comparable quinta Zinacantepec $10,600,000.
- Usos comerciales (restaurante, eventos) sujetos a permisos municipales.

## Publicación en Vercel
- Proyecto: `campestre-iahouse` → https://campestre-iahouse.vercel.app
- En Vercel: Add New › Project › importar `IAHOUSE/ia-house` › Project Name `campestre-iahouse` › Root Directory `mexicaltzingo` › Framework "Other" › Deploy.
- Cada push a `main` vuelve a publicar solo.

## Pendiente
- Fotos y videos nuevos del shooting (dron 16:9 al atardecer, caballerizas, acabados, pozo/caseta/portón, cada espacio).
- Link de YouTube del recorrido horizontal.
- Píxel de Meta y publicación en dominio propio (o GitHub Pages).
- Reels cortos 9:16 (≤30 s) y versión 4:5 (≤15 s) para la campaña de Facebook e Instagram.
