
## Capítulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

Usaremos un set de herramientas que nos permitiran desarrollar las distitas soluciones que ofrecemos. Para una mejor visualicion, lo hemos separado en caterogias. En la siguiente lista podran observar las herramientas con sus enlaces de cada categoria.

**Editores:**

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
- [Visual Studio code](https://code.visualstudio.com/)

**SDKs y Runtimes:**

- [.Net 6 LTS](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
- [Node 18.18.2 Hydrogen LTS](https://nodejs.org/en/download/releases)

**Frameworks:**

- [ASP.Net 6 LTS](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
- [Vue 3](https://vuejs.org/)

**Engines:**

- [Unity LTS Release 2022.3.12f1](https://unity.com/releases/editor/qa/lts-releases)

**Bases de datos:**

- [MySql](https://www.mysql.com/)

**Control de versiones:**

- [Git](https://git-scm.com/)

### 7.1.2. Source Code Management

Par nuestro control de versiones usaremos [Git](https://git-scm.com/). Asimismo, usaremos [Github](https://github.com) para almacenar nuestros repositorios de git. Para una mayor organizacion, hemos creado una organizacion donde tendremos nuestros repositorios. Tambien nos facilitara crear equipos y restringir permisos. El enlace a la organizacion es el siguiente: [Organizacion](https://github.com/Arquitectura-Software-2023)

| Desarrollo                | Repositorio                         | Enlace |
|---------------------------|-------------------------------------|--------|
| Proyecto                  | Project-Report                      | [Repositorio](https://github.com/Arquitectura-Software-2023/Project-Report) |
| Landing Page              | TastyPoint-landing-page             | [Repositorio](https://github.com/Arquitectura-Software-2023/TastyPoint-landing-page) |
| Aplicacion Web - Frontend | TastyPoint-FrontEnd-Web-Application | [Repositorio](https://github.com/Arquitectura-Software-2023/TastyPoint-FrontEnd-Web-Application) |
| Aplicacion Web - Backend | Web-Services-TastyPoint             | [Repositorio](https://github.com/Arquitectura-Software-2023/Web-Services-TastyPoint) |
| Aplicacion VR |              |  |

### 7.1.3. Source Code Style Guide & Conventions

Para nuestro Code Style, optamos por escoger los lineamientos de [Google](https://google.github.io/styleguide/). Esta decision fue tomada pues el equipo ya ha trabajdo anteriormente con esta guia de estimos.Asimismo, debido a la relevancia de esta guia de estilo, existen muchas herramientas que se encargan de asegurar que se cumpla atravez de linters y style checkers. Esto facilitada nuestra implementacion de nuestro pipeline de integracion continua. Finalmente, durante el desarrollo, agregaremos reglas especiales que solo se aplican a nuestro proyecto.

### 7.1.4. Software Deployment Configuration

Nuestro deployment se dara con distinta herramientas dependiendo del producto. Esto se debe a que poseemos creditos en ellas, lo cual nos permite lanzar un primer release sin elevar los costos planificados.

| Desarrollo                | Nube                                 |
|---------------------------|--------------------------------------|
| Proyecto                  | [Github](https://github.com)         |
| Landing Page              | [Azure](https://azure.microsoft.com) |
| Aplicacion Web - Frontend |[Netlify](https://netlify.com) |
| Aplicacion Web - Backtend |[Azure](https://azure.microsoft.com) |
| Aplicacion VR | [Unity](https://unity.com/) |

## 7.2. Solution Implementation

### 7.2.1. Sprint 1

#### 7.2.1.1. Sprint Planning 1

| Sprint Planning | 1 |
|-----------------|---|
| Fecha | 16/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Software Development Environment Configuration, Source Code Management, Source Code Style Guide & Conventions, Software Deployment Configuration y Spring Backlog 1 |

#### 7.2.1.2. Sprint Backlog 1

#### Sprint Backlog 1 Web Application

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| | | | | | | | |

#### Sprint Backlog 1 Mobile Application

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| | | | | | | | |

#### Sprint Backlog 1 Landing Page

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US27 | Visualizar la sección home del landing page | Como usuario quiero ver la sección “home” para ver la información principal. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de home, entonces visualiza una breve descripción de la aplicación e información de sus segmentos. | Usuario se dirige a la sección “home” de la landing page.| Adrian Marquina | 5 | En progreso |
| US28 | Visualizar la sección "about us" en landing page | Como usuario quiero ver la sección “about us” para saber porque TastyPoint es innovadora en el área de comida a domicilio. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de about us”, entonces visualizará la información de TastyPoint. | Usuario se dirige a la sección “about us” de la landing page. | Adrian Marquina | 5 | En progreso |
| US29 |Visualizar la sección "segments" en landing page | Como usuario quiero ver la sección “segments” para conocer a quienes está dirigida la aplicación y sus beneficios.|Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de “segments”, entonces visualiza el público objetivo de TastyPoint y las características de la aplicación en cada uno.|Usuario se dirige a la sección “segments” de la landing page | Adrian Marquina | 5 | En progreso |

#### 7.2.1.3. Development Evidence for Sprint Review

#### Sprint Backlog 1 Development Evidence Web Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
|TastyPoint-FrontEnd-Web-Application| | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |
|TastyPoint-FrontEnd-Web-Application | | | |

#### Sprint Backlog 1 Development Evidence Mobile Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| | | | |

#### Sprint Backlog 1 Development Evidence Landing Page

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| TastyPoint-landing-page | 6b030de0613ebd540511da021b7676f0df59fd50 | deployment | Adrian Marquina |
| TastyPoint-landing-page | 23e4521efa2576a0232de0137b222a713d7a5beb | deployment | Adrian Marquina |
| TastyPoint-landing-page | 1d3be24bfa01f2e8557296521813c6cc5a8e5245 | ci: add Azure Static Web Apps workflow file  | Adrian Marquina |
| TastyPoint-landing-page | 41c4739bf813d86a54acaf676c793a47bd5800e7 | Content | Adrian Marquina |
| TastyPoint-landing-page | cbc186bb2bd2515e01c50154c6923fc859cd35ec | added first sections structure | Adrian Marquina |
| TastyPoint-landing-page | 689cdbac816d305867a4ff38f96a488ebb915f4f | tailwind primary colors | Adrian Marquina |
| TastyPoint-landing-page | 0a894b01ba1989dc38dca560cc713ce0bbae22d0 | setup | Adrian Marquina |
| TastyPoint-landing-page | 8e80881e245e2cb91a165634d3f673cadbc294ff | first commit | Adrian Marquina |

#### 7.2.1.4. Testing Suite Evidence for Sprint Review

#### Sprint Backlog 1 Testing Suite Evidence Consumer

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| | | | | | | |

#### Sprint Backlog 1 Testing Suite Evidence Business

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| | | | | | | |

#### Sprint Backlog 1 Testing Suite Evidence Landing Page

Para el sprint 1, solo se construyo la matriz de pruebas.

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T1           | US27     | Verificar la visualización de la sección "home" en la landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "home" o desplazarse hasta ella | El usuario debería ver una breve descripción de la aplicación e información de sus segmentos                          | Adrian Marquina         | Pendiente           |
| T2           | US28     | Verificar la visualización de la sección "about us" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "about us" o desplazarse hasta ella | El usuario debería ver la información sobre por qué TastyPoint es innovadora en el área de comida a domicilio         | Adrian Marquina         | Pendiente           |
| T3           | US29     | Verificar la visualización de la sección "segments" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "segments" o desplazarse hasta ella | El usuario debería ver información sobre el público objetivo de TastyPoint y las características de la aplicación     | Adrian Marquina         | Pendiente           |

#### 7.2.1.5. Execution Evidence for Sprint Review

#### Sprint Backlog 1 Execution Evidence Consumer

Execution

#### Sprint Backlog 1 Execution Evidence Business

Execution

#### Sprint Backlog 1 Execution Evidence Landing Page

![Landing Execution](Images/sprint-1-landing-execution-1.png)

#### 7.2.1.6. Services Documentation Evidence for Sprint Review

#### Sprint Backlog 1 Documentation Evidence Consumer

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| | | |  |  | | |

#### Sprint Backlog 1 Documentation Evidence Business

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| | | |  |  | | |

#### Sprint Backlog 1 Documentation Evidence Landing Page

Para el sprint 1 solo se logro desarrollar la matriz de documentos.

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------------------|------------|
| D1              | US27     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "home" en la landing page. | Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D2              | US28     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "about us" en la landing page. | Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D3              | US29     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "segments" en la landing page.| Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D4              | US27     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "home" en la landing page.| Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D5              | US28     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "about us" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D6              | US29     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "segments" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D7              | US27     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "home" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |
| D8              | US28     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "about us" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |
| D9              | US29     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "segments" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |

#### 7.2.1.7. Software Deployment Evidence for Sprint Review

#### Sprint Backlog 1 Deployment Evidence Consumer

Documentation

#### Sprint Backlog 1 Deployment Evidence Business

Documentation

#### Sprint Backlog 1 Deployment Evidence Landing Page

Se implemento el pipeline de despliegue continuo con azure. Acontinuacion, se adjunta la evidencia del despliegue del landing page: [Url](https://jolly-field-04c7e7710.4.azurestaticapps.net/)

Deployment
![Github Action detail](Images/sprint-1-landing-deployment-1.png)
![Azure portal](Images/sprint-1-landing-deployment-2.png)
![Deployed landing page](Images/sprint-1-landing-deployment-3.png)

#### 7.2.1.8. Team Collaboration Insights during Sprint

| Sprint Review | 1 |
|-----------------|---|
| Fecha | 20/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 40% de lo comprometido |

| Sprint Review | 2 |
|-----------------|---|
| Fecha | 27/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 80% de lo comprometido |

## 7.3. Validation Interviews

### 7.3.1. Registro de Entrevistas
### 7.3.2. Evaluaciones segun Heuristicas

## 7.4. Video About the Product
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjAzMDkyMDQ0LDIwOTc5NDI5ODUsLTg3NT
QyNzQ5Ml19
-->