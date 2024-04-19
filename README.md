![banner](./documentation/images/banner1.webp)

# Gestión de Productos y Servicios

## Contenido

- [Introducción](#introducción)
- [Prerrequisitos](#prerrequisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Cómo contribuir](#cómo-contribuir)
- [Requisitos del Sistema](#re)
- [Licencia](#licencia)

## Introducción

El presente respositorio (monorepo) contiene un proyecto de gestión de categorías, productos, inventario y precios separados en microservicios.

Este proyecto es un ejercicio realizado con el fin de mostrar a algunos jóvenes colegas una aproximación de cómo se puede resolver este tipo de necesidades, aclaro, es una de muchas formas posibles, y, cómo la arquitectura se puede ir evolucionando con el tiempo.

Ocasionalmente alguien me contacta por [Linkedin] o por medio de otro amigo, para realizarme alguna consulta sobre cómo hacer tal o cual cosa en un sistema, así que, motivado por estas consultas, he decidido crear un pequeño sistema dividido en microservicios, que responde a esas preguntas que ocasionalmente he respondido.

No es un sistema exhaustivo,seguro en el tintero quedarán muchas más cosas que contar, pero trataremos ir respondiendo preguntas por medio de este proyecto.

## Prerrequisitos

Este proyecto y los documentos asociados, incluyendo guías, artículos y ejemplos de código, asumen que el lector tiene conocimientos fundamentales en programación y lógica, así como una comprensión sólida del entorno de ejecución Node.js y los lenguajes JavaScript y TypeScript. Este material se centra en principios, patrones y buenas prácticas de desarrollo de software, por lo que no se abordarán los conceptos básicos de estos lenguajes y tecnologías. Asegúrate de estar familiarizado con estos aspectos antes de proceder.

### Tecnologías

Acontinuación se listan las tecnologías empleadas en el desarrollo y ejecución del proyecto:

Los microservicios serán desarrollados en su totalidad con [TypeScript][ts] para ser ejecutado en [NodeJS][node] y utilizando [Express][express] para la gestión de las peticiones HTTP,

- [Docker][docker]
- [Docker Compose][compose]
- [Express][express]
- [Git][git]
- [GitHub][github]
- [MongoDB][mongo]
- [NodeJS][node]
- [TypeScript][ts]: Será el lenguaje empleado para escribir todo el código para Node.js, que luego será transpilado, ya que Node.js solo comprende [JavaScript][js]

## Instalación

Antes de instalar el proyecto en nuestro equipo, se requiere contar con algunas herramientas previamente instaladas, como en la mayoría de los casos, la instalación difiere de una plataforma a otra y, el proceso escapa de la cobertura de este proyecto, les dejaré los requerimientos mínimos y el link a sus respectivas páginas para que se remitan a la documentación y puedan ver cual es el proceso de instalación.

Para instalar este proyecto y comenzar a usarlo, sigue los pasos detallados a continuación:

1. **Clonar el repositorio**

```sh
git clone git@github.com:jeastman19/products-example.git
```

## Uso

Para desplegar en local el proyecto en su totalidad, utilizamos en [docker-compose][compose]

```
docker-compose up -d
```

## Cómo contribuir

- Compartir este proyecto con todo aquel a quien le pueda ser de utilidad
- Realizar consultas sobre cualquier parte del proyecto, las explicaciones que se dejen como respuesta, seguro serán de gran utilidad a otros
- Sugerir cambios
- Realizando pull-request

## Requisitos del Sistema

Con el fin de ayudar a comprender mejor lo que el sistema hace (o más bien, debería hacer), se agregan una serie de documentos en los cuales se analizan los [requisitos funcionales y no funcionales][requisitos] del proyecto.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Esto significa que tienes amplia libertad para distribuir, modificar, incluir en proyectos privados y más, siempre y cuando incluyas el archivo original de la licencia y los derechos de autor en cualquier distribución. Para más información, consulta el archivo [LICENSE][license] en este repositorio.

[compose]: https://docs.docker.com/compose/
[docker]: https://www.docker.com/
[express]: https://expressjs.com/es/
[git]: https://git-scm.com/
[github]: https://github.com/
[js]: https://developer.mozilla.org/es/docs/Web/JavaScript
[license]: ./LICENSE
[mongo]: https://www.mongodb.com/es
[node]: https://nodejs.org/en
[ts]: https://www.typescriptlang.org/
[requisitos]: ./documentation/001%20-%20requisitos.md
