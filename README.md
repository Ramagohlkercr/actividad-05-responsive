# Actividad 05 - Diseño Responsive

Réplica de una noticia real de un diario online aplicando **HTML semántico**,
**CSS externo**, **media queries** (desktop, tablet y mobile) y **Box Model**.

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Réplica de la noticia con estructura HTML semántica. |
| `styles.css` | Hoja de estilos externa con media queries (desktop/tablet/mobile) y Box Model. |

## URL de la noticia original

- *Could humanoid robots be heading for the battlefield?* (BBC News, Technology of Business):
  https://www.bbc.com/news/articles/cedpxwe26l1o

## Diseño responsive

La página presenta cambios visibles entre tres tamaños de pantalla mediante
media queries:

- **Desktop:** layout de dos columnas (artículo + barra lateral).
- **Tablet (≤ 992px):** una sola columna; la barra lateral pasa debajo del artículo y muestra sus elementos en dos columnas.
- **Mobile (≤ 600px):** todo apilado en una columna, navegación apilada, tipografías y espaciados reducidos.

Se utilizan propiedades del **Box Model** (márgenes, padding, bordes, anchos y altos)
para lograr una composición ordenada en cada dispositivo.

## Flujo de trabajo con Git

1. Branch específica `actividad-05` para el desarrollo.
2. Commits descriptivos.
3. Push al repositorio remoto.
4. Pull Request hacia `main`.
5. Revisión, merge y verificación de la integración.
