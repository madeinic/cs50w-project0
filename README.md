# Project 0

Web Programming with Python and JavaScript

Mi proyecto trata de una página de peliculas clasificadas en 4 tipos de plataformas: Netflix, HBO, Prime Video y Disney+ las cuales están en 4 plantillas diferentes: netflix.html, hbo.html, disney+.html y prime.html que muestran las películas e información adicional de acuerdo a la plataforma en que se encuentre, nombre y el año de lanzamiento.

El index.html contiene la plantilla principal  donde estan todas las peliculas con el navbar donde se incluye el nombre de la página como tal "MOVIESPAGE" y las 4 secciones por medio de una lista desordenada, al lado derecho está un buscador el cual no tiene ninguna funcionalidad más que estética, y al final de este se encuentra una tabla con los servicios de las plataformas disponibles y sus precios.

En disney.html, hbo.html, netflix.html y prime.html se encuentra la misma plantilla nada más lo que se cambia es el contenido ya que llevan peliculas especificas que pertenecen a cada plataforma. 

Para el navbar y las cards se utilizó una plantilla de bootstrap y se editó sobre ella segun el contenido que se quiere ingresar y mostrar al usuario, insertando imagenes e información.

Se hizo un footer sencillo donde se dan los creditos de autor y el nombre de la página.

En la carpeta static existe el archivo main.css y main.scss donde se crearon propiedades css con selectores de clase y id, en el archivo scss se declararon variables para poderlas usar dentro de ciertas clases y propiedades, también se utilizo herencia para utilizar el mismo grosor y tipo de letra en varias partes de la pagina, , varios anidamientos para respetar el orden de las propiedades y por último se utilizó un selector responsivo media query con el navbar para que se aplique un color diferente en pantalla mas pequeññas que no se lograba distinguir.