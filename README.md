# Demonlist viewer

Frontend de una página para consultar niveles de la Global Demonlist de Geometry Dash.

## Instalación y ejecución

```bash
npm install
npm run dev
```

Abrí la dirección indicada en la terminal, en este caso `http://localhost:4321`.

## Herramientas usadas

- Astro 6 para la estructura y ejecución del frontend.
- JavaScript para consultar, buscar y seleccionar niveles.
- [Global Demonlist API](https://demonlist.org/api-docs), mediante `GET https://api.demonlist.org/level/classic/list`.

## Funcionalidad

- Página principal con sección de presentación, ranking, detalle y fuente de datos.
- Consumo directo de la API pública de Demonlist.
- Búsqueda instantánea por nombre de nivel y panel con el detalle del nivel seleccionado.
- Diseño adaptable para pantallas pequeñas.
