# Data Dashboard

## Preámbulo

En Laboratoria, las Training Managers (TMs) hacen un gran trabajo al analizar la
mayor cantidad de datos posibles respecto al desempeño de las estudiantes para
apoyarlas en su aprendizaje.

Desde hace unos meses tenemos un sistema donde nuestras estudiantes acceden a
contenidos de aprendizaje (lecturas, ejercicios, quizzes, ...), nuestro LMS, el
cual acumula data sobre quién leyó qué, qué ejercicios se han completado y los
resultados de los quizzes, ...

El LMS por ahora no implementa una visualización de esta data que permita a las TMs ver fácilmente el avance de las estudiantes con respecto a estos contenidos. Así que nos han pedido que construyamos una interfaz donde pueden _ver_ y _usar_ esa data y que así puedan tomar decisiones de una forma más informada. 

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

Los tests unitarios deben cubrir un mínimo del 70% de _statements_, _functions_
y _lines_, y un mínimo del 50% de _branches_. El _boilerplate_ ya contiene el
setup y configuración necesaria para ejecutar los tests (pruebas) usando el
comando `npm test`.

Para comenzar este proyecto tendrás que hacer un _fork_ y _clonar_ este
repositorio que contiene el _boilerplate_.

El _boilerplate_ contiene una estructura de archivos como punto de partida así
como toda la configuración de dependencias y tests de ejemplo:

```text
./
├── .editorconfig
├── .eslintrc
├── .gitignore
├── README.md
├── data
│   ├── cohorts
│   │   └── lim-2018-03-pre-core-pw
│   │       ├── progress.json
│   │       └── users.json
│   └── cohorts.json
├── package.json
├── src
    ├── data.js
    ├── index.html
    ├── main.js
    └── style.css
```

La carpeta `data/` dentro del _boilerplate_ incluye un extracto de la data que usaremos en la interfaz.

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

* Listar/seleccionar cohorts
* Dentro de cada cohort:
  - Listar alumnas
  - Para cada alumna:
    + Calcular porcentaje de completitud de todos los _cursos_ por alumna.
    + Calcular grado de completitud de _lecturas_, _ejercicios autocorregidos_,
      y _quizzes_.
  - Filtrar/buscar alumnas por nombre
* Mostrar los datos más relevantes primero
* Utiliza la interfaz sin problemas desde distintos tamaños de pantallas:
  móviles, tablets, desktops

Además, la interfaz deberá seguir los fundamentos de visual design como
contraste, alineación, jerarquía, entre otros.


##Referencias en el LMS

https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/01-dom

https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/03-dom-manipulation

https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/04-events

https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/05-data-attributes

##Ejercicios recomendados como calentamiento

Te sugerimos que calientes el cerebro y domines algunas de las habilidades que necesitas para resolver este proyecto prácticando en los siguientes links. 

##Manipulación y visualización de data

https://lms.laboratoria.la/cohorts/cdmx-2018-05-bc-core-am/courses/javascript/05-objects/06-practice

https://lms.laboratoria.la/cohorts/cdmx-2018-05-bc-core-am/courses/javascript/04-arrays/06-practice

##Manipulación de DOM
https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/10-guided-exercises

https://github.com/Laboratoria/curricula-js/tree/master/03-interactive-site/01-making-your-site-interactive/11-code-challenges

Habilidades blandas:

* Esperamos que en este proyecto puedas pensar en el cliente, entendiendo cuál
  es mejor sistema de visualización del data dashboard según sus necesidades.
* Nos interesa que logres entender a las necesidades de los usuarios para los
  que crearás el producto y los ayudes a resolver esas necesidades.
* Además, que puedas trabajar de manera colaborativa con tu pareja, buscando
  feedback constante para realizar el proyecto.