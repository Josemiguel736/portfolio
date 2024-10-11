# Titulo del proyecto: Mi portfolio 

## Descripción

En este proyecto podrás encontrar una página web hecha solo con css y html, este proyecto ha sido creado con motivo de la práctica del modulo de HTML y CSS del bootcamp desarrollo web de KeepCoding.

Para esta práctica era un requisito desarrollarla mobile firts asi que **todo el diseño de la página se creo inicialmente optimizado para la versión movil y posteriormente se desarrolló para PC**, por lo que **todas las media query van a ajustar a la version pc**, el css sin media query esta pensado para verse en movil.

Destacar que salvo los iconos de redes sociales, y el vídeo background **todas las imágenes son responsive** generalmente con 7 tamaños diferentes.

## Secciones Index
### Header:
En el header de la versión movil podemos encontrar un **menú hamburguesa hecho solo con CSS y checkbox**, también consideré oportuno hacer que si clicamos en el logo que se encuentra en la parte superior izquierda del header nos envie al inicio de la página principal.

En la versión pc este header ya no dispone de menu hamburguesa si no que tiene las secciones **alineadas con display flex** de forma que queden a la derecha los elementos, también tienen en su **modo Hover un transition** que al clicar añade un background azul oscuro, cambia el peso del texto a bold y amplia un poco el enlace.

### Inicio:
En la sección inicio decidí que quería que mi diseño empezase ocupando el 100% del tamaño de la pantalla tanto en pc como en movil, así como que tuviese un video como background, también queria que fuese muy simple, tan solo con un pequeño saludo, un avatar y un boton que enviara a la sección sobre mi.

En la versión movil **todo esta alineado en columna usando flex**, el avatar se ve en un marco circular, mientras que en la versión pc están tanto el saludo como el avatar centrados pero en la misma linea, en este caso la imagen del avatar esta en un marco cuadrado.

El botón que encontramos en esta sección así como el que podremos encontrar en la sección sobre mí estan **suavizados mediante transiciones** y cambia en este caso el background a gris siguiendo un poco con la linea de estilos que le he querido dar a la página.

### Sobre mí:
En la sección sobre mí he querido completar dos requisitos que se nos habián pedido para la práctica, el primero que tuviera **una imágen en el background distinta entre la version movil y la versión pc**, en la versión movil se puede ver que es una textura estilo papel arrugado que me pegaba bastante con la estetica y los colores buscados. 

En la versión pc quería aprovechar esa misma textura pero obviamenrte no podia, tenia que cumplir el requisito de hacerlas distintas, así se me ocurrio la idea y en photoshop añadí el logo de keepcoding que además tenia sentido con el texto que acompaña a la sección y que por diseño quería que la version pc también tuviese una imagen acompañando al texto y me parecia muy adecuado que fuera la de la KeepCoding.

Con la imágen de KeepCoding se me ocurrió aprovecharme del responsive para que en versión movil no la descargue, en este caso solo tengo dos imágenes, una adaptada a pc y otra que si está adaptada para móvil, pero en los enlaces a esta lo puse mal a proposito buscando que no sepa desde donde descargarla.
Imagino que hay una forma mejor de hacerlo y agradecería saber si existe alguna forma sin usar Javascript.

El siguiente requisito eran las barras de progreso con mis aptitudes, las desarrollé con **animaciones css**, los porcentajes y duración los recogí en una clase adicional para poder aprovechar una sola clase con la animación y darle los valores que quería con otra, hice lo mismo para los colores, solo que buscando que sea mas escalable esta solo cambia los colores.

### Formulario:
Para el formulario puse las secciones que eran requisito, intenté en todas ellas hacerlas lo mas accesible posible para los **lectores de texto** y también tuve en cuenta que **cada input tuviera el tipo adecuado.**

En la versión móvil uso **flex para alinearlo todo al centro**, mientras que **en la versión pc decidí usar un grid**.

### Footer:
Para el Footer decidí incluir enlaces a mi github, instagram y linkedin, tuve en cuenta que son enlaces a páginas web externas así que implemente que **se abrieran en nuevas páginas además de añadir el "noopener noreferrer" en el código.** También le añadí el background de papel usado en la sección *"sobre mí."*

## Secciones Portfolio
### Vídeo:
Para el vídeo decidí que los formatos en los que se mostrase fuesen como el del ejemplo adjuntado por el profesor, 9:16 para móvil y 16:9 para pc.
Al cargar tiene **un suavizado con transiciones, autoplay y empieza muteado**, si he querido conservar los controles de youtube para que quien quiera pueda verlo y disfrutar de la gran charla que nos dió midudev!

### Portfolio:
En el portfolio directamente decidí crear **ambas versiones con display grid**, y con una media query hacer que **en la versión pc en vez de 2 columnas tenga 3.**
También quise darle a las imágenes en estado Hover una pequeña transición en la que le añado un borde de color azul y la hago mas pequeña.

## Páginas 404 y 500
Para las Páginas 404 y 500 quería hacer algo muy simple pero que tuviera sentido tanto entre ellas mismas como con la web, además de tratar de que fueran amigables con el usuario, así que generé 2 avatares que me encajaran en en esas páginas y traté de hacer una composición similar a la del inicio solo que sin el vídeo de fondo, en este caso opte por la textura de papel que uso en varios de los background.

## Extra
Le he agregado un **icono a la página**, y en la página de index también he añadido **metatags** para decorar mejor los enlaces externos que se puedan llevar generar hacia esta página.

También he realizado el despliegue en GitHub Pages, el enlace es el siguiente: https://josemiguel736.github.io/portfolio/index.html










