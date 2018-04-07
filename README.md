# Rediseño página web Cruz Roja e impletación de chatbot

Se nos solicitó como equipo analizar y rediseñar la página actual de la Cruz Roja con el fin de reducir la cantidad de llamadas que realizan los usuarios a la sucursal con respecto a dudas que deberían ser respondidas en la misma página. Además se solicitó la implementación de un asistente virtual con el fín de resolver dudas que surgen en emergencias.

Para el proceso de investigación trabajamos bajo la metodología de Design Thinking en donde fue fundamental la participación tanto del del cliente como del área de desarrollo.

![etapas](https://i.imgur.com/cvWT6gi.jpg)

## Investigación
Realizamos un análisis comparativo de páginas de Cruz Roja a nivel internacional y en paralelo testeamos la página actual de Cruz Roja Chile junto con analizar la arquitectura de la información.
Concluimos que la página actual chilena estaba sobrecargada de información, además la información no estaba al alcance inmediato, no hay información específica, con respecto a diseño visual la tipografía es pequeña, no hay contraste lo que ocasiona que algunos links parezcan deshabilitados y la jerarquía no está clara.

[Ver benchmark](https://docs.google.com/spreadsheets/d/1Yy3vw6XD_wauSyglQpm8u47Flvcbou9rA8MlJYGdVTc/edit#gid=0)

##### Página Actual
![etapas](https://i.imgur.com/rJ5oh5s.png)

Se realizó un **mapa de contenido** en donde se valida la sobre carga de información en ciertas secciones, lo difícil de llegar a la información, la repetición de algunas opciones y la jerarquía de contenidos no se respetaba.

#### Mapa de contenido

![etapas](https://i.imgur.com/Vx4WGyA.jpg)

### Entrevistas con expertos
La entrevista con expertos nos permitió definir la necesidad de ellos como Clientes, la cual es disminuir la cantidad de llamados que realizan los usuarios en situaciones de catástrofes, es decir que la página sea tan clara que los usuarios no tuviesen la necesidad de llamar.

## Análisis / definición
### Realización de persona
En conjunto con el equipo de desarrollo y los integrantes de la Cruz Roja realizamos el user persona y un mapa de empatía del usuario. Producto de esto logramos llegar a la problemática.

#### User Persona y mapa de empatía
![etapas](https://i.imgur.com/dSnln7J.jpg)
![etapas](https://i.imgur.com/fHJSPUI.jpg)

#### Personalidad del asistente virtual
Pudimos  generar una personalidad que permitiera empatizar con el usuario, dandole dos caracteristicas que son la confianza, por medio de una personalidad profesional y generar cercanía por medio de un lenguaje coloquial.

#### Problemática
Las personas que quieren ser voluntarias a partir de un evento de emergencia desconocen la información necesaria para poder inscribirse o de como poder ayudar (Voluntario desinformado).

#### Propuestas de valor
* La pagina logra ser cercana e intuitiva lo que hace disminuir las llamadas en episodios de emergencia.
* Contar con un asistente virtual con una personalidad enfocada en el usuario

## Ideación/Diseño

Gracias a la propuesta de valor, pudimos comenzar con los sketch, donde todas colaboramos con distintas ideas, respecto a las posibles soluciones de la web.

Una vez realizado los sketch decidimo por medio de votación seleccionar las soluciones más relevantes.

![etapas](https://i.imgur.com/1azpBRA.jpg)
![etapas](https://i.imgur.com/vFGGCse.jpg)

## Validación
Realizamos testeos de guerrilla en donde pudimos iterar el producto hasta llegar al MVP (Producto mínimo viable).
Como conclusión tuvimos que reorganizar la arquitectura de la información, principalmente en relación a la jerarquía y el diseño visual.
Los principales cambios fueron en relación a como entregar la información, conceptos confusos.

## MVP
![etapas](https://i.imgur.com/Bb24jNJ.jpg)

## Desarrollo de chatbot
Para desarrollar el proyecto de asistente virtual se utilizan otras tecnologías de IBM. Watson assistant para crear el flujo y contenido de los diálogos, Node-RED como herramienta de desarrollo que permite conectar la **API de Watson Assistant** con nuestra aplicación web, la que se interrumpe en la pagina como un iframe La aplicación web fue desarrollada con Javascript y jQuery, ademas de bootstrap 4 como framework.

### Equipo
#### UX Designers
* Angélica Órdenes
* Pabla Bazán
* Macarena Araos
* Natalia Espinoza
* Stephanie Rojo
* Lía Cubillos

#### Front-end developers
* Leticia Rodríguez
* Cynthia Isla
* Nadia Morales
* María José Barriga
* Natalia Albornoz
* Andrea Díaz

##### Proyecto desarrollado en para Cruz Roja Chile.
