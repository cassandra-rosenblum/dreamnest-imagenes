# Herramientas comerciales de Dream Nest

Biblioteca de las presentaciones, vídeos, folletos y páginas que el equipo usa con
clientes y colaboradores. El CRM (sección Herramientas) lee `catalogo.json` y la
muestra por categorías, con portada, explicación, enlace y descargas.

- `catalogo.json`: la lista. Cada herramienta tiene `id`, `categoria`, `titulo`,
  `que_es`, `para_que`, `cuando`, `portada`, `idiomas`, `enlace` (o `null`) y
  `descargas` (idioma, formato, etiqueta, url, peso en MB), `audiencia` (externa/interna)
  y `publico`: a quién va dirigida, con los ids de la lista `publicos` (todos los públicos,
  compradores internacionales, compradores de EE. UU., Realtors de EE. UU., inmobiliarias en
  España, promotoras, abogados, colaboradores, equipo). Toda herramienta nueva lleva su público. `aviso` lleva el flag
  LCCI cuando la pieza enseña tipos o cuotas.
- `archivos/`: los archivos descargables.
- `portadas/`: una imagen 960×540 por herramienta, con el mismo nombre que su `id`.

Regla de esta carpeta (compartida con el CRM): solo se añade. Una versión nueva de
un archivo sustituye al anterior con el mismo nombre; nunca se renombra ni se borra
algo que el CRM ya enlaza.
