# Data Dashboard

## Preámbulo

En Laboratoria, las Training Managers (TMs) hacen un gran trabajo al analizar la
mayor cantidad de datos posibles respecto al desempeño de las estudiantes para
apoyarlas en su aprendizaje. Para revisar esta data, las TMs, normalmente,
tienen que revisar muchos documentos de excel (Google Spreadsheets) que están
localizados en distintas carpetas y ubicaciones. Muchas veces pierden tiempo
localizando estos documentos y _ejecutando_ fórmulas para obtener los datos que
necesitan.

Para poder optimizar su tiempo, las TMs han solicitado que construyamos una
herramienta web donde puedan ver estos datos fácil y rápidamente.

## Objetivos

El objetivo principal de aprendizaje de este proyecto es construir una
_interfaz_ web donde podamos visualizar y manipular data.

Tópicos: _arrays_, _objects_,  _bucles_, _condicionales_, _métodos para manipular objects y arrays_, _dom_, _funciones_...

## Consideraciones generales

Este proyecto se debe "resolver" en parejas.

La lógica del proyecto debe estar implementada completamente en JavaScript
(ES6), HTML y CSS. En este proyecto NO está permitido usar librerías o
frameworks, solo [vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

No se debe utilizar la _pseudo-variable_ `this`.

Para comenzar este proyecto tendrás que hacer un _fork_ y _clonar_ este
repositorio que contiene el _boilerplate_.

El _boilerplate_ contiene una estructura de archivos como punto de partida así
como toda la configuración de dependencias y tests de ejemplo:

```text
./

├── .eslintrc
├── README.md
├── index.html
├── assets
│   ├── images
├── css
|   ├── main.css
├── js
    ├── app.js
    ├── data.js
```

## Parte obligatoria

### Definición del producto

En el `README.md` cuéntanos cómo pensaste y te acercaste a los usuarios al
desarrollar tu producto y cuál fue tu proceso para definir el producto final a
nivel de experiencia y de interfaz. Si tienes fotos de entrevistas,
cuestionarios y/o sketches compártelos. Además, detalla:

* quiénes son los principales usarios de producto
* cuáles son los objetivos de estos usarios en relación con el producto
* cuáles son los dato más relevantes que el usuario quiere ver en la interfaz y
  por qué. Cómo los descubriste.
* cuándo es que el usuario revisar normalmente estos datos
* cómo crees que el producto que estás creando les está resolviendo sus
  problemas
* cómo fue tu proceso de diseño

### UI

La interfaz debe permitir al usuario:

- El total de estudiantes presentes por sede y generación.
- El porcentaje de deserción de estudiantes.
- La cantidad de estudiantes que superan la meta de puntos en promedio de todos
  los sprints cursados. La meta de puntos es 70% del total de puntos en HSE y en tech.
- El porcentaje que representa el dato anterior en relación al total de
  estudiantes.
- El Net Promoter Score (NPS) promedio de los sprints cursados. El NPS se
  calcula en base a la encuesta que las estudiantes responden al respecto de
  la recomendación que darían de Laboratoria, bajo la siguiente fórmula:

  ```text
  [Promoters] = [Respuestas 9 o 10] / [Total respuestas] * 100
  [Passive] = [Respuestas 7 u 8] / [Total respuestas] * 100
  [Detractors] = [Respuestas entre 1 y 6] / [Total respuestas] * 100

  [NPS] = [Promoters] - [Detractors]
  ```
- La cantidad y el porcentaje que representa el total de estudiantes que superan
  la meta de puntos técnicos en promedio y por sprint.
- La cantidad y el porcentaje que representa el total de estudiantes que superan
  la meta de puntos de HSE en promedio y por sprint.
- El porcentaje de estudiantes satisfechas con la experiencia de Laboratoria.
- La puntuación promedio de l@s profesores.
- La puntuación promedio de l@s jedi masters.

Además, la interfaz deberá seguir los fundamentos de visual design como
contraste, alineación, jerarquía, entre otros.

## Calentamiento previo-opcional

![Alt text](https://shareitmaybe.com/wp-content/uploads/2016/10/apps-para-entrenar-el-cerebro.jpg?raw=true)

Te sugerimos que calientes el cerebro y domines algunas de las habilidades que necesitas para resolver este proyecto indagando en los tópicos necesarios y prácticando en los siguientes links.

Para ello los tópicos que te sugerimos revisar en el lms son:

### Creando Interacción con Javascript(Topic Browser)

Necesitas que tu marcado y diseño tengan funcionalidad para ello necesitas entrenar en:

-Dom

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/01-dom-traversing

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/01-dom

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/02-bom

-Manipulando el DOM

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/02-dom-manipulation

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/03-dom-manipulation

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/03-browser-reflow

-Los eventos en el DOM

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/04-events

-Data Attributes

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/05-data-attributes

- Ejercicios resueltos

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/06-practical-cases

- Prueba lo aprendindo

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/browser/02-dom/11-code-challenges

### Manipulación y visualización de data (Topic JavaScript)


https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/01-basics

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/02-flow-control

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/03-functions

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/04-arrays


https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/05-objects

https://github.com/Laboratoria/curricula-js/tree/v2.x/topics/javascript/06-strings/01-strings

- Ejercicios

https://lms.laboratoria.la/cohorts/cdmx-2018-05-bc-core-am/courses/javascript/05-objects/06-practice

https://lms.laboratoria.la/cohorts/cdmx-2018-05-bc-core-am/courses/javascript/04-arrays/06-practice

Habilidades blandas:

* Esperamos que en este proyecto puedas pensar en el cliente, entendiendo cuál
  es mejor sistema de visualización del data dashboard según sus necesidades.
* Nos interesa que logres entender a las necesidades de los usuarios para los
  que crearás el producto y los ayudes a resolver esas necesidades.
* Además, que puedas trabajar de manera colaborativa con tu pareja, buscando
  feedback constante para realizar el proyecto.