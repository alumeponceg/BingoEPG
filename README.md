# BingoEPG

*Una web de bingo realizada con Bootstrap4, HTML, CSS y Javascript*

## Descripción

La web que se muestra a continuación esta formada por una página principal compuesta de un encabezado superior, un menú de navegación con acceso a 3 subpáginas 

1. Sobre nosotros: esta pestaña muestra en un modal una breve descripción de la web para atraer al usuario e incitar a su uso.

1. Iniciar Sesión: Es una subpágina existente con un formulario que permite recabar información sobre los credenciales de acceso, este apartado no es funcional por tanto al hacer click sobre el botón _iniciar sesion_ muestra un mensaje informativo de disculpa al usuario en el cual se le informa de que más adelante ese apartado será funcional y que actualmente el sitio web está en desarrollo.

1. Registrarse: Es una subpágina muy similar a la anterior con la misma funcionalidad, en este caso se le pide al usuario infromación para hacer el registro de su perfil en la web , como son el nombre completo, el email, el nombre de usuario, la contraseña y la confirmación de la misma. Del mismo modo que la anterior muestra un mensaje de web en desarrollo cuando se hace click en _registrarse_

Continuando con la descripción de la página princiapl, después del menú encontramos a la izquierda un panel de usuario, en el cual mostramos la imagen de perfil del usuario, su nombre de jugador, los créditos que tiene disponible, las partidas jugadas y los bingos cantados (Cabe destacar que la en pantallas medianas y pequeñas este panel de usuario cambiará su posición a la parte superior de la pantalla ocuando todo el ancho). 

A la derecha del panel de usuario encontramos dos botones uno de jugar partida y uno de finalizar partida, estos botones son funcionales y expliaremos su funcionamiento más adelante cuando hablemos de Javascript. 

Debajo de los botones nos encontramos los cuatro cartones de bingo, son responsivos, y se muestran en dos a dos en pantallas grandes y tablets y cuando volteamos nuestro dispositivo movil o tablet, y en cambio en pantallas moviles verticales se muestra uno por columna ocupando todo el ancho de la pantalla.

Lo último que encontramos en la página principal es un sencillo footer en el cual simplemente se muestra un mensaje de _gracias por visitar nuestro sitio web_ y _vuelve pronto_.

###### Los apartados encabezado, menú de navegacioón y footer se mantienen en cada una de las subpáginas.

## Bootstrap.

En cuanto al contenido bootstrap que hemos decidido añadir a nuestro sitio web se encuentra toda la disposición en filas y columnas que se verá en todo el recorrido de la página y además una serie de componentes que se exponen a continuacion 

* Navbar: Este elemento bootstrap se ha usado en el menú de navegación y nos permite que el usuario pueda desplazarse por la página con mayor facilidad con ello estamos aumentando la usabilidad de nuestra página.

* Navbar Collapse: Con este elemento se permite la optimización del menú cuando nos encontramos en una pantalla de ancho reducido proporcionando un menú desplegable mucho más cómodo y estético.

* Buttons: en diversos lugares de nuestra web se encuentran botones que contiene el elemento **btn** con ello se facilita la codificación de la página y el responsive.

* Modal: Tanto al hacer click en _Sobre nosotros_ como al enviar los formularios de inicio de sesión y de registro

* Formularios: Todos los formularios de la página han sido realizados con la clase **form group** para que la estética de nuestros formualarios sea mayor y además facilite el uso responsive.


## JavaScrit 

Para aumentar la funcionalidad de la web se ha añadido unas pequeñas funciones de JavaScript que aumentan el realismo de la misma. A continuación se explican las funcionalidades para que su uso y entendimiento sea mejor:

* Jugar Partida: Cuando hacemos click sobre el botón *Jugar partida* aparecerá un alert que nos informa de que una partida nueva ha comenzado, en ese mismo instante en nuestro panel de usuario se añade una partida jugada, y se nos quita 1 crédito de los 200 iniciales.

* Finalizar Partida: Cuando hagamos click sobre el botón *Finalizar Partida* un mensaje de alert que nos informa de que la partida ha terminado y por tanto no podremos usar nuestros cartones de bingo.

**_¿Qué ocurre si intentamos empezar una partida sin finalizar otra, o finalizar una partida sin haber empezado una ?_**

En ambos casos un mensaje de alerta nos informará de que ya hay una partida en curso o en su defecto de que no se puede finalizar una partida que no ha comenzado

* Cartones de bingo: Cuando hagamos click sobre uno de los números de nuestro cartón de bingo (_No hacer más de dos veces click en el mismo o el contador se desajusta_) en el caso de que no hayamos empezado una partida antes se nos informará de que debes empezar una partida, si por el contrario la partida esta comenzada podremos al hacer click sobre los números tacharlos y cuando tachemos los 15 numeros de un cartón un mensaje nos mostrará que hemos hecho bingo, nos sumará 2 créditos al panel de usuario, nos sumará 1 a bingos cantados del panel de usuario, y la partida finalizará.

* Limpiar carton: Cuando hagamos click en este botón todos los números del cartón que estuviesen tachados dejarán de estarlo.

## Diseño

Para realizar el diseño de esta página web se ha elegido una gama de colores llamativos para que capten la atención del usuario, son colores alegrez y que en su conjunto expresan positivismo, de esta manera cuando el usuario se encuentre en nuestra página tendrá la verdadera sensación de encontrarse ante una página de juego online, y sentirá esa _"energía y positividad"_ que le animarán a continuar jugando.


