# best-practices

Este es un documento vivo sobre convenciones y prácticas que recomendamos seguir a lo largo del curso.

## general

- Para nombrar archivos y carpetas, vamos a utilizar *lowercase* (minúsculas), separando palabras con guiones medios. Ej: `index.html`, `common-styles.css`.
- **LCS:** para cualquier código que escribamos, intentar, en lo posible, *optimizarlo* para que sea 
  - **L**egible
  - **C**onsistente
  - **S**imple 
- Nunca olvidarnos de que escribimos código para que lo lean otras personas. Debería ser *[simple de entender](https://www.oreilly.com/library/view/the-art-of/9781449318482/ch01.html)*.

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

- Estilar, en lo posible, usando clases.
- Si usamos HTML5, con tags más semánticos y no genéricos, vamos a escribir menos CSS, más legible y mantenible.
- Reutilizar estilos comunes entre componentes, utilizando la cascada.
- Componer estilos usando clases (ver por ejemplo cómo aplica esto [Tachyons](https://github.com/dwyl/learn-tachyons)).
- Reset: utilizar `box-sizing: border-box` para todos los elementos del sitio, al igual que empezar con `margin` y `padding` en 0.
- Es recomendable escribir los selectores más genéricos al principio para evitar pisar estilos.
- En lo posible, definir alguna convención para el nombre de los selectores y tratar de mantenerla. Ser consistentes.

## Git

- Escribir mensajes de commits en inglés.
- Escribir mensajes de commits descriptivos.
- En lo posible, comitear de forma frecuente.
- Intentar, en lo posible, realizar *[commits](https://seesparkbox.com/foundry/atomic_commits_with_git) [atómicos](http://www.pauline-vos.nl/atomic-commits/)*.
- Escribir los mensajes de commits en *[tiempo presente, modo imperativo](https://stackoverflow.com/a/3580764)*.

