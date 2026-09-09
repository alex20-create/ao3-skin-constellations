# Skin AO3 — Constelaciones doradas

Un site skin oscuro para Archive of Our Own (AO3), con acentos dorados, tags codificados por color y una versión adicional con la página de lectura en blanco para mayor legibilidad.

Esta skin es una **modificación de un skin base** que ya existía (fondo navy oscuro, acentos dorados y una imagen de cabecera de constelaciones), sobre el que se ha reescrito y ampliado prácticamente todo el CSS: nueva paleta de colores por categoría de tag, rediseño de botones, panel de filtros, paginación, cabecera del blurb, y más.

Parte del código que sustituye los iconos de clasificación (rating/warnings/category/estado) por texto legible está adaptado del snippet `removes-icons.css` del repositorio [Ao3-modular-skins de electricalice](https://github.com/electricalice/Ao3-modular-skins), usado originalmente en el skin oficial "Plain Text" de AO3.

## Archivos

- **`skin_ao3_actualizado.css`** — la skin principal, con tema oscuro en toda la página.
- **`skin_ao3_lectura_blanca.css`** — la misma skin, pero con la zona de lectura del capítulo en fondo blanco y texto negro para mayor comodidad de lectura. El resto de la página (header, tags, navegación) se mantiene igual.

## Características

- Paleta de colores diferenciada por categoría de tag (fandom, relationships, characters, freeform, category, warnings), incluyendo distinción entre relaciones románticas y no románticas.
- Botones, paginación y panel de filtros (Sort and Filter) rediseñados para mantener coherencia visual.
- Símbolos de clasificación (rating, warnings, categoría, estado) mostrados como texto legible en vez de iconos, agrupados en una caja discreta con separadores.
- Cabecera de resultados de búsqueda reorganizada: fecha, título, fandom y clasificación con espaciado propio.
- Texto de los fics justificado.

## Instalación

1. Copia el contenido del archivo `.css` que prefieras.
2. En AO3, ve a **My Preferences → Skins → My Skins → Create Skin**.
3. Pega el código en el campo CSS.
4. Guarda y selecciónalo como tu skin activo desde Preferencias.

## Apoyo
Puedes apoyarme en: [ko-fi/alex_create](https://ko-fi.com/alex_create).

## Créditos

- Skin base original: constelaciones doradas sobre fondo oscuro (autor original desconocido/no especificado).
- Fragmento de reseteo de iconos de clasificación: [electricalice/Ao3-modular-skins](https://github.com/electricalice/Ao3-modular-skins) (`removes-icons.css`), basado a su vez en el skin oficial "Plain Text" de AO3.
- Resto de personalizaciones: propias.

## Licencia

Sin restricciones específicas — siéntete libre de adaptarlo, siempre que mantengas los créditos de las partes reutilizadas mencionadas arriba.
