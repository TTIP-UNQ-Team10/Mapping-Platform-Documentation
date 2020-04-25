# Mapping-Platform

## En qué consiste?

**Mapping-Platform** es un producto de mapeo, una plataforma web de tipo _marca blanca_ que permite, de manera estandarizada, realizar el mapeo de distintas necesidades que una entidad u ONG requiera. Tambien tiene la posibilidad de centralizar informacion de otra índole que no involucre un mapeo, relacionada a necesidades sociales, o cuestiones que generen impacto social.

## Cuál fue nuestra motivación?
El proyecto surgió a partir de la idea de centralizar productos de mapeo que Wingu contiene, creando un producto estándar para que cualquier organización que tenga una necesidad de mapeo en particular (por ej. realizar un relevamiento de asentamientos informales) la pueda satisfacer con la plataforma, pudiendo personalizar su información a gusto.


## Arquitectura
**Mapping-Platform** está desarrollada en 2 módulos:

- Backend: A través de una API maneja la lógica de las necesidades de mapeo y provee la información necesaria a la plataforma. Construida con el framework ***NodeJs*** y con ***Typescript*** como lenguaje.
 Se utilizan las siguientes tecnologías:
  - ***TypeORM*** para el mapeo del modelo de datos a la BD.
  - ***MySQL*** como motor de base de datos.
  - ***Docker*** como contenedor de la base de datos.
  - ***Mocha*** para el desarrollo de unit tests.
 
- Frontend: Tenemos un cliente desarrollado en ***ReactJs*** que consume la API para generar los mapeos, y contiene los estilos personalizables para cada cliente.
Se utilizan las siguientes tecnologías:
  - ***ReactJs*** para el manejo de las pantallas.
  - ***Leaflet*** para el renderizado de los mapas.
  - ***algo mas???***
  
  ## Para el Desarrollador
  
  ### Backend
  Si querés contribuir, te tenés que clonar el [repositorio de la API](https://github.com/TTIP-UNQ-Team10/Mapping-Platform-Backend)
  
  #### Requerimientos
  - [NPM](https://www.npmjs.com/get-npm)
  - [NodeJs](https://nodejs.org/)
  - [Docker](https://docs.docker.com/engine/installation/)
  - [Docker Compose](https://docs.docker.com/compose/install/)
  - [Typescript](https://www.typescriptlang.org/index.html#download-links)
