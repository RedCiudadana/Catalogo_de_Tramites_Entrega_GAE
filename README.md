# Catálogo de Trámites

Este proyecto está construido utilizando el generador de páginas estáticas [11ty](https://www.11ty.dev/), aprovechando las plantillas de [Nunjucks](https://mozilla.github.io/nunjucks/) y JavaScript para implementar filtros de búsqueda. Es una solución eficaz para crear sitios web optimizados y fáciles de mantener.

## Tecnologías Utilizadas

- **11ty:** Un generador de sitios estáticos que nos permite compilar plantillas y datos en páginas HTML.
- **Nunjucks:** Un motor de plantillas rico en características que proporciona un poderoso lenguaje de plantillas para JavaScript.
- **JavaScript:** Utilizado para añadir interactividad en el sitio, especialmente para los filtros de búsqueda.

## Estructura de Datos

La data del proyecto se maneja a través de la carpeta `_data`. Aquí es donde el proyecto se comunica con la API del sitio (base de datos) para obtener información sobre los servicios, instituciones y categorías disponibles. Esta estructura permite una fácil gestión y actualización de los contenidos del sitio sin necesidad de alterar el código fuente.

## Configuración y Uso

Para poner en marcha el proyecto, es necesario tener instalado [Node.js](https://nodejs.org/) y [npm](https://www.npmjs.com/). Una vez instalados, sigue los siguientes pasos:


1. Instala las dependencias del proyecto:
```
npm install
```
2. Para iniciar el proyecto y servirlo localmente, ejecuta:
```
npm start
```

Para más información sobre cómo utilizar 11ty y Nunjucks, consulta la documentación oficial de [11ty](https://www.11ty.dev/docs/) y [Nunjucks](https://mozilla.github.io/nunjucks/templating.html).
