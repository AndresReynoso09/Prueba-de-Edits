#### 7.2.1.2. Sprint Backlog 1

#### Sprint Backlog 1 Consumer

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US01 | Registro de Consumidor | Como consumidor quiero crear una cuenta para acceder a la aplicación. | CA1: Dado que el consumidor se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el consumidor se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo Y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el consumidor se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”. | E1: El consumidor quiere registrarse en la aplicación. E2: El consumidor no completa los campos obligatorios. E3: El consumidor intenta registrarse, pero no completa con datos correctos los campos obligatorios. |Andres Reynoso| 3 | Done|
| US02 | Monitorear el perfil | Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos. | Dado que el consumidor quiere ver su perfil. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces la aplicación muestra la información del perfil del consumidor. | El consumidor quiere ver su perfil. | |Andres Reynoso| 3 | In Progress|
| US03 | Cerrar sesión de consumidor | Como consumidor quiero cerrar sesión para salir de mi cuenta.| CA1: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción sí para cerrar la sesión. CA2: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el botón de cerrar sesión. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción no para mantener iniciada la sesión. | E1:  El consumidor quiere cerrar sesión en el sistema. E2: El consumidor presiona por error el botón de “Cerrar sesión “.| |Claudia Rozas| 2 | In Progress|
| US04 | Pagar el envío de productos | Como consumidor quiero pagar el envio del pedido. | CA1: Dado que el consumidor se encuentra en la ventana “Pago”. Cuando se llena el campo de número de cuenta correctamente y presione el botón de Pagar. Entonces la aplicación mostrará un icono de verificado. CA2:  Dado que el consumidor se encuentra en la ventana “Pago”. Cuando no se llena el campo de número de cuenta correctamente Y presione el botón de Pagar. Entonces la aplicación mostrará un mensaje de error y el borde del campo se volverá rojo.| E1: El consumidor desea colocar su cuenta bancaria. E2: El consumidor rellena el campo de su cuenta bancaria incorrectamente. |
| US05 | Visualizar todas las notificaciones | Como consumidor, quiero visualizar las notificaciones para estar informado sobre las ofertas que ofrezcan los restaurantes. | Dado que el consumidor se encuentra en la aplicación, cuando ingresa a la sección de notificaciones, entonces le aparecen las notificaciones realizadas por los restaurantes registrados en la aplicación. |  Ver ofertas publicadas por restaurantes. |
| US06 | Fijar favoritos | Como consumidor quiero guardar la información de mis productos favoritos | CA1: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón vacío que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se añaden los datos del producto a la sección de favoritos y el icono de corazón vacío cambia por uno lleno. CA2: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón lleno que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se eliminan los datos del producto a la sección de favoritos y el icono de corazón lleno cambia por uno vacío. | E1: Guardar productos favoritos. E2: Eliminar producto de favoritos |
| US07 | Visualizar productos y sus datos | Como consumidor quiero ver la lista de los productos publicados por los restaurantes registrados en la aplicación para poder comprarlos. | CA1: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar los productos organizados con sus respectivas fotos y ciertos datos puntuales como descripción. CA2: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar el mensaje: “No hay productos publicados”. | E1: El consumidor quiere visualizar algunos productos para comprarlos. E2: El consumidor quiere visualizar algunos productos para comprarlos, pero no hay productos. |
| US08 | Filtrar restaurante | Como consumidor quiero filtrar la lista de restaurantes registrados en la aplicación para poder encontrar rápidamente los productos de mi restaurante de preferencia. | CA1: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del restaurante en la barra de navegación ubicado en la parte superior, entonces se mostrarán los datos de los productos de los restaurantes registrados en la aplicación. CA2: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del restaurante en la barra de navegación ubicado en la parte superior, entonces se mostrará el mensaje: “Restaurante no encontrado”. | E1: El consumidor visualiza los restaurantes deseados. E2: No hay restaurantes registrados en la aplicación con el nombre del usuario. |
| US09 | Compartir comentario| Como consumidor quiero redactar un comentario sobre un determinado restaurante acerca de mi experiencia con ellos para poder compartir mi opinión con los demás.| Dado que el consumidor se encuentra en la ventana de reseñas, cuando ingrese su comentario y presione el botón de publicar entonces se publicará el comentario. | El consumidor exceda el límite de caracteres permitidos. |
| US10 | Filtrar productos | Como consumidor quiero filtrar la lista de productos registrados en la aplicación para poder encontrar rápidamente el producto que deseo. | CA1: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del producto en la barra de navegación ubicado en la parte superior, entonces se mostrarán los datos de los productos de los restaurantes registrados en la aplicación. CA2: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del producto en la barra de navegación ubicado en la parte superior, entonces se mostrará el mensaje: “Producto no encontrado”. | E1: El consumidor visualiza los productos deseados. E2: No hay productos registrados en la aplicación con el nombre del usuario. |

#### Sprint Backlog 1 Business

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US11 | Registro de Cliente | Como cliente quiero crear una cuenta para acceder a la aplicación. |CA1:  Dado que el cliente se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el cliente se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el cliente se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”.| E1: El cliente quiere registrarse en la aplicación. E2: El cliente no completa los campos obligatorios. E3: El cliente intenta registrarse, pero no completa con datos correctos los campos obligatorios.|
| US12 | Pago de suscripción | Como cliente deseo poder pagar la suscripción desde la aplicación para acceder a más beneficios. | CA1: Dado que el cliente ya se encuentra registrado. Cuando el cliente desee usar alguna función de la aplicación. Entonces la aplicación le mostrará una pantalla con las opciones de suscripción al servicio. CA2: Dado que el cliente visualiza las opciones de suscripción. Cuando el cliente selecciona una de las opciones. Entonces la aplicación lo redirigirá a una pantalla en la que podrá ingresar la tarjeta de crédito o débito con la que realizará el pago. CA3: Dado que el cliente ya ingresó los datos necesarios para el pago. Cuando el cliente seleccione el botón Pagar. Entonces la aplicación le mostrará un mensaje de “Pago realizado con éxito”. Y el cliente podrá utilizar la aplicación. CA4: Dado que el cliente ya ingresó los datos necesarios para el pago. Cuando el cliente seleccione el botón Pagar. Y la aplicación detecte algún inconveniente. Entonces la aplicación le mostrará un mensaje de “El pago no se pudo realizar. Inténtelo de nuevo más tarde”. | E1: Visualización de las opciones de suscripción E2: El cliente ingresa los datos de su tarjeta. E3: Realización exitosa del pago E4: Realización fallida del pago |
| US13 | Publicación de platos sobrantes | Como cliente deseo poder publicar los platos que me sobraron en el día para poder vender lo máximo posible. | CA1: Dado que el cliente posee excedentes de platos del día. Y el cliente se encuentra en la ventana de “Catálogo” y desea publicar sus excedentes. Cuando el cliente seleccione la opción Publicar. Entonces la aplicación le preguntará qué desea publicar (platos de comida o insumos) CA2: Dado que el cliente se encuentra en la pantalla de elección de plato o insumo. Cuando el cliente escoja la opción de plato de comida. Entonces la aplicación le pedirá que ingrese una serie de datos sobre el plato (nombre del plato, cantidad, precio verdadero, precio ofrecido, entre otros). CA3: Dado que el cliente se encuentra en la pantalla de completado de datos del plato de comida. Cuando el cliente complete correctamente los datos. Y seleccione la opción publicar. Entonces la aplicación le mostrará un mensaje “Publicación realizada”.| E1: Cliente selecciona producto a publicar E2: Cliente ingresa los datos del plato E3: Cliente realiza la publicación |
| US14 | Publicación de insumos sobrantes | Como cliente quiero publicar los insumos sobrantes del día para reducir al mínimo los desperdicios de estos. | CA1: Dado que el cliente posee excedentes de insumos del día. Y el cliente se encuentra en la ventana “Catálogo” y desea publicar sus excedentes. Cuando el cliente seleccione la opción Publicar. Entonces la aplicación le preguntará qué desea publicar (platos de comida o insumos) CA2: Dado que el cliente se encuentra en la pantalla de elección de plato o insumo. Cuando el cliente escoja la opción de insumo. Entonces la aplicación le pedirá que ingrese los datos del insumo (nombre del insumo, porciones, precio estimado, entre otros). CA3: Dado que el cliente se encuentra en la pantalla de completado de datos del insumo. Cuando el cliente complete correctamente los datos. Y seleccione la opción publicar. Entonces la aplicación le mostrará un mensaje “Publicación realizada”.| E1: Cliente selecciona producto a publicar E2: Cliente ingresa descripción del insumo E3: Cliente realiza la publicación |
| US15 | Medios de contacto | Como cliente quiero enlazar todos los medios de comunicación que poseo para permitir a mis consumidores contactarse directamente con nosotros. | Dado que el cliente se encuentra en la ventana “Perfil”, cuando selecciona “Agregar redes sociales” y los agrega, entonces la aplicación mostrará un mensaje “Se agregó con éxito”. | Añadir redes sociales |
| US16 | Ver opciones disponibles | Como cliente quiero ver las opciones que ofrece Tasty Point para conocer el funcionamiento de la app y elegir alguna de sus opciones disponibles. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y desea ver las opciones disponibles de la app. Cuando el cliente seleccione el símbolo listo. Entonces la aplicación mostrará las opciones disponibles: "Inicio", "Agregar", "Catálogo", "Perfil”, en formato de lista. | El cliente ingresa correctamente a la lista de opciones. |
| US17 | Ver pedidos |Como cliente quiero ver la lista de pedidos solicitados en mi restaurante, para conocer la demanda a través de la App web. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y hace clic en la sección “Órdenes”, cuando el cliente se encuentre en dicha sección, entonces aparecerá una lista con los nombres de los consumidores que realizaron un pedido en específico con fecha, hora y cantidad ordenada. | El cliente ingresa al registro de pedidos. |
| US18 | Ver el catálogo de platos e insumos | Como cliente quiero ver el catálogo actual de platos e insumos ofrecidos por mi establecimiento para corroborar que los datos de la App coincidan con mi inventario. | CA1: Dado que el cliente ha iniciado sesión, se encuentra en la lista de opciones ofrecida de Tasty point y desea revisar su catálogo. Cuando el cliente seleccione la opción "Catálogo". Entonces la aplicación mostrará la totalidad de platos e insumos registrados por el cliente, junto a datos pertinentes como: la cantidad actual, reservas hechas y tipo de recojo o envío disponible. CA2: Dado que el cliente se encuentra en la lista de platos e insumos disponibles ofrecidos por su establecimiento, y desea ver sólo los platos o insumos ofrecidos por su establecimiento. Cuando el cliente seleccione la opción filtro y elija la opción “platos” o “insumos”. Entonces la aplicación listará solo platos o solo insumos (dependiendo de la opción del cliente) junto a sus datos pertinentes. | E1: El cliente elige la opción catálogo. E2: El cliente elige ver solo platos o solo insumos del catálogo. |
| US19 | Abrir vista de consumidor | Como cliente quiero contar con la vista de consumidor para asegurar que mis productos se vean atractivos para los consumidores. | Dado que el cliente se encuentra en la ventana “Catálogo”, Cuando el cliente presione la opción: “Vista de consumidor”. Entonces la aplicación mostrará la ventana “Vista de consumidor” con los productos organizados de la forma en las que se le presenta al cliente. | El cliente ingresa a “vista de consumidor” |
| US20 | Editar las características de un plato o insumo |Como cliente quiero ser capaz de editar las características que coloqué sobre algún plato o insumo para corregir errores o actualizar la información. | CA1: Dado que el cliente se encuentra en la ventana “Catálogo” y quiera editar algún dato presentado. Cuando el cliente seleccione el botón editar del plato a editar. Entonces la aplicación permitirá la edición de los datos o multimedia ingresados (Nombre del plato, precio real, precio ofrecido, tipo de recojo o envío, foto del plato/insumo, etc). CA2: Dado que el cliente ha terminado de editar los datos requeridos y quiere guardar los cambios. Cuando el cliente elija el botón aceptar. Entonces se guardará y actualizará la información ofrecida; y se mostrará una ventana emergente de “Se han guardado los cambios”. | E1: El cliente ingresa correctamente al modo edición. E2: El cliente guarda correctamente los datos editados. |
| US21 | Contar con un CTA (Call To Action) potencialmente atractivo | Como cliente es de mi interés que las ventas aumenten, por lo tanto, es de suma importancia que dentro de la app exista algún botón o enlace que los direccione a la carta disponible en mi restaurante y asegurar su compra. | Dado que el cliente se encuentra dentro de la aplicación cuando decida qué platillo consumir, entonces aparecen CTA atractivos de los restaurantes asociados a la aplicación, apareciendo botones con enlaces que los envía a la página del restaurante. | El cliente asegura una venta y se guarda el registro del platillo, siendo así que para la compra futura se recomiendan platillos similares. |
| US22 | Poder leer los comentarios de los usuarios. | Como cliente quiero leer el feedback de los comensales para mejorar. | Dado que el cliente se encuentra dentro de la ventana “Reseñas de consumidores” cuando se dirige al área de opiniones, entonces puede leer los comentarios de los consumidores. | El cliente entra en la sección de consumidores y visualiza quiénes han hecho comentarios. 

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
|TastyPoint-FrontEnd-Web-Application|a470f5737dae15a63a0080aea951bc398af104c4 |Added Web Application, currently missing features | Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |0379cc63d954d4fa82a0dd7381dcfd2a569f552a |Added Layout Segment |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |2542129dcb4ff17f51db920d04c20e35c42b2224 |Added Layout |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |696ce9bb78812e9521b8e084e503ac532542eef5 |Added Orders component |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |69a58e3e6e8c1d938b34d077c80e40d3e597f091 |Added Profile |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |38f092cc28157843bf12b4966efafc3f135db803 |added security |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |73842ea48ff9220629ef0462928c4ba10524c765 |added selling |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |2e21e5ed70651353dc83ca0daa3262e9b951ab87 |Added Publishing |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |4d53fb3046adf4e08ad4bfe3ad35bfc25c72223b |added selling |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |885b8946b84a9c25a23d421dff403563e76d2323 |added shared | Claudia Rozas|
|TastyPoint-FrontEnd-Web-Application |ede4361d9f255c6039cb4e6fba140dc981e40be7 |added social |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |e1594fb0bffeffaf5fb09af99adacb7f30c8f37e |Fixed Routes |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |e97b5f65586ad8fe94619aa01c078a90811d6775 |Fixed routes and uses fake API |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |419c5538e26b57224ce5abe97e12899c30be2cb0 |Fixed styles for security to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |249a54f1e60911a7a79c96837c97221ee2327ad4 |Added styles for consumers to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |96773931332614fea1c26f7d7c523f645b1500c2 |Fixed settings for business, also added new styles | Andres Reynoso|

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

#### Sprint Backlog 1 Execution Evidence Web Application

Execution

#### Sprint Backlog 1 Execution Evidence Mobile Application

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

#### Sprint Backlog 1 Deployment Evidence Web Application

Documentation

#### Sprint Backlog 1 Deployment Evidence Mobile Application

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
eyJoaXN0b3J5IjpbLTgwNDI2MTczMiwtMTYxNDEzMDYzMiwyMD
k5NTY4NDcyLDIwOTc5NDI5ODUsLTg3NTQyNzQ5Ml19
-->