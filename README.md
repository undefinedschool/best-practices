# best-practices

Este es un documento vivo sobre convenciones y prácticas que recomendamos seguir a lo largo del [curso de Desarrollo Web Full Stack](http://undefinedschool.io).


## Contenido

- [Disclaimer](#disclaimer)
- [General](#general)
- [HTML5](#html5)
- [CSS3](#css3)
- [Git](#git)
- [JavaScript](#javascript)

## Disclaimer

Las buenas prácticas son convenciones que adoptamos para _estandarizar_ nuestra forma de desarrollar, utilizar ciertos patrones que nos permitan evitar algunos errores comunes y escribir código de mayor calidad, más legible, mantenible, escalable, etc. 

- **No son reglas**. Siempre debemos tener en cuenta el _contexto_ y no aplicarlas ciegamente.
- **Son subjetivas**. Resulta fundamental por eso, en lo posible, seguir las guías de buenas prácticas y estilos del proyeto en el que estemos trabajando y si no las tiene, buscar la oportunidad de discutirlas y definirlas.

## General

- Para nombrar archivos y carpetas, vamos a utilizar *lowercase* (minúsculas), separando palabras con guiones medios. Ej: `index.html`, `common-styles.css`.
- **LCS:** para cualquier código que escribamos, intentar, en lo posible, *optimizarlo* para que sea 
  - **L**egible
  - **C**onsistente
  - **S**imple 
- Nunca olvidarnos de que escribimos código para que lo lean otras personas. Debería ser *[simple de entender](https://www.oreilly.com/library/view/the-art-of/9781449318482/ch01.html)*. Como diría el gran Kyle Simpson, _[Code is for Humans](https://frontendmasters.com/teachers/kyle-simpson/code-is-for-humans/)_. Salvo que estemos programando compiladores, claro.

## HTML5

- Definir/planificar la estructura de nuestro sitio en secciones o *componentes*, **antes de empezar a escribir el código**. Lápiz y papel!
- Separar el *contenido/estructura* de la *presentación*. Para los estilos usamos CSS, evitar tags como `b`ó `i` por ejemplo.
- Evitar, en lo posible, utilizar estilos *inline* e `!important`.
- Usar HTML5 y tags *semánticos*. No abusar del `div`.
- Usar los distintos tipos de *headings* cuando corresponda (`h1`...`h6`), para darle jerarquía al contenido de nuestro sitio y facilitarle el trabajo a screen-readers y buscadores.
- Evitar, en lo posible, los contenedores genéricos. No abusar del `div`.
- Siempre declarar el DOCTYPE.
- Agregarle al tag `html`el atributo `lang`, con el valor correspondiente.
- Siempre agregarle el atributo `alt` a las imágenes, con un texto descriptivo.
- Indentar nuestro código apropiadamente en el editor, para escribir código más legible, facilitar la colaboración y el trabajo en equipo.

## CSS3

- Estilar, en lo posible, usando clases. De esta forma obtenemos mayor control sobre la _especificidad_ y resulta más fácil componer estilos.
- Si usamos HTML5, con tags más semánticos y no genéricos, vamos a escribir menos CSS, más legible y mantenible.
- Reutilizar estilos comunes entre componentes, utilizando la cascada.
- Componer estilos usando clases (ver, por ejemplo, cómo aplica esto [Tachyons](https://github.com/dwyl/learn-tachyons)).
- Reset: utilizar `box-sizing: border-box` para todos los elementos del sitio, al igual que empezar con `margin` y `padding` en 0.
- Es recomendable escribir los selectores más genéricos al principio para evitar pisar estilos.
- En lo posible, definir alguna convención para el nombre de los selectores y tratar de mantenerla. Ser consistentes.

## Git

- Escribir mensajes de commits en inglés.
- Escribir mensajes de commits descriptivos.
- En lo posible, _comitear_ de forma frecuente.
- Intentar, en lo posible, realizar *[commits](https://seesparkbox.com/foundry/atomic_commits_with_git) [atómicos](http://www.pauline-vos.nl/atomic-commits/)*.
- Escribir los mensajes de commits en *[tiempo presente, modo imperativo](https://stackoverflow.com/a/3580764)*.

## Comentarios

- Utilizar, en lo posible, _comentarios minimales_. Para ver de qué se trata esto, leer la sección _Minimal Comments_ del artículo [The Exceptional Beauty of Doom 3's Source Code](https://kotaku.com/the-exceptional-beauty-of-doom-3s-source-code-5975610).

## JavaScript

-
