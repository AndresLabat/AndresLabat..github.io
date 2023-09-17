# README - GAMEATING

GAMEATING es un sitio web que presenta un restaurante con una ambientación única inspirada en el mundo de los videojuegos. Este proyecto utiliza diversas tecnologías, como HTML, CSS, Bootstrap, Git y GitHub, para crear una experiencia de usuario inmersiva y atractiva.

## Contenido del Proyecto

El proyecto GAMEATING consta de varios archivos HTML y un archivo CSS:

1. **Index.html**: Página de inicio que muestra un carrusel de imágenes de platos del restaurante, información de contacto y redes sociales, y un pie de página con detalles del autor.

2. **Info.html**: Página "Conócenos" que proporciona información sobre la historia del restaurante, sus espacios únicos (zona de restaurante, área de consolas retro y pub gaming), y su oferta.

3. **Jobs.html**: Página "Trabaja con Nosotros" que permite a los usuarios completar un formulario para acceder a puestos de trabajo en el restaurante.

4. **Reservation.html**: Página "Reservar Mesa" con un formulario para que los usuarios puedan realizar reservas de mesa, incluyendo fecha, hora y datos de contacto.

5. **Carta.html**: Página que muestra la carta de platos del restaurante, con nombres creativos relacionados con juegos. También cuenta con un menú desplegable para facilitar la navegación por categorías.

## Tecnologías Utilizadas

- **HTML**: Utilizado para crear la estructura y el contenido de las páginas web.
- **CSS**: Aplicado para dar estilo y diseño a todas las páginas.
- **Bootstrap**: Empleado para lograr un diseño web responsive y aprovechar componentes como la barra de navegación y el carrusel de imágenes.
- **Git y GitHub**: Usados para el control de versiones y el alojamiento del proyecto en línea.

## Ramas del Repositorio

Este proyecto se desarrolló en una rama separada llamada "dev" que se creó desde la rama principal ("master"). Todos los commits se realizaron en la rama "dev" durante el desarrollo del proyecto.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local usando el siguiente comando: git clone.

2. Abre el archivo `Index.html` en tu navegador web para comenzar a explorar la aplicación.

3. Ahora puedes observar un carousel de presentación del restaurante y una barra de navegación para poder explorar el resto de archivos html.

## Funcionamiento

GAMEATING es un sitio web intuitivo y fácil de usar que ofrece las siguientes funcionalidades clave:

- **Navegación Sencilla**: La barra de navegación en la parte superior de cada página te permite moverte fácilmente entre las diferentes secciones del sitio web, como la página de inicio "Home", "Conócenos", "Trabaja con Nosotros", "Reservar Mesa" y "Carta". También incluye una función de búsqueda para encontrar rápidamente platos específicos, pero esto se implementará cuando veamos Javascript.

- **Explora el Menú**: Visita la página "Carta" para explorar la amplia variedad de platos del restaurante. Cada plato tiene un nombre creativo relacionado con videojuegos y una breve descripción, además de un hover que nos hara más facil reconocer la relación del plato con el juego en especifico al que se refiere.

- **Información y Reservas**: Obtén información detallada sobre el restaurante en la página "Conócenos". Si deseas hacer una reserva, visita la página "Reservar Mesa" y completa el formulario proporcionando la fecha, hora y tus datos de contacto.

- **Únete a Nuestro Equipo**: Si estás interesado en trabajar en GAMEATING, visita la página "Trabaja con Nosotros" y completa el formulario de solicitud de empleo.

- **Diseño Responsive**: GAMEATING está diseñado para funcionar perfectamente en una variedad de dispositivos y tamaños de pantalla, lo que garantiza una experiencia de usuario óptima en computadoras de escritorio, tabletas y teléfonos móviles.

Siéntete libre de explorar y disfrutar de todas las funcionalidades que GAMEATING tiene para ofrecer. Si tienes alguna pregunta o necesitas asistencia, no dudes en ponerte en contacto conmigo a través de la información de contacto proporcionada en la parte inferior de todas las secciones de la web.

¡Espero que disfrutes tu experiencia en GAMEATING!

## Diseño Responsive

Todo el diseño del sitio web es responsive, lo que significa que se adapta a diferentes dispositivos y tamaños de pantalla gracias al uso de Bootstrap y la propiedad CSS display flex. Esto garantiza una experiencia de usuario óptima tanto en computadoras de escritorio como en dispositivos móviles.

## Problemas y Soluciones

### 1. No puedo encontrar un plato específico en la carta

- **Problema**: Si no puedes encontrar un plato específico en la carta es porque esa función aun no ha sido implementada.

   - **Solución**: Cuando veamos en clase Javascript se le añadirá dicha función.

### 2. No ocurre nada al enviar el formulario de reserva ni el de trabaja con nosotros

- **Problema**: Al igual que en el caso anterior, aun no esta implementada esta función, podría haber añadido un button de formulario para que al menos me indique si los campos obligatorios estan rellenos, pero decidí hacerlo custom con un div para que fuera mas llamativo visualmente. Aún no se como conseguir que haga lo mismo que un button predeterminado.

   - **Solución**: Aún no puedo decir cuando, pero será implementado en cuanto adquiera los conocimientos necesarios.

### 3. Problemas de visualización en dispositivos móviles

- **Problema**: Si experimentas problemas de visualización en dispositivos móviles, como elementos superpuestos o mal alineados, asegúrate de que tu navegador esté actualizado a la última versión. GAMEATING está diseñado para ser responsive, pero algunos problemas pueden surgir debido a diferencias en los navegadores móviles.

   - **Solución**: Intenta abrir el sitio web en otro navegador o dispositivo para ver si el problema persiste. Si el problema persiste, por favor, informa sobre el problema para que pueda investigarlo y solucionarlo. Pese a que su diseño tiene esa intención, dista mucho de ser perfecto debido a mis limitaciones técnicas, por lo que también es posible que sea un fallo de diseño cometido por mi.

### 4. Problemas en la barra de navegación debido a hipervinculos en los carousel

- **Problema**: He tenido dificultades a la hora de implementar anclas en algunas zonas de la web, en ocasiones eran mucho mas grandes de lo esperado y se solapaban con otras por lo que se perdía la posibilidad de una correcta interconexión entre elementos.

   - **Solución**: Revisar cada uno de los div que contenian a su vez a otros div, de forma que me he dado cuenta que he puesto las anclas en elementos padre, y de esa manera ocupaban mucho más espacio del esperado.

### 5. Problemas de visualización en los titulos de los platos al activarse el hover

- **Problema**: No he conseguido que los hovers de los platos de la carta hagan que en determinadas ocasiones en las que el fondo se vuelve mas oscuro o verdoso, las letras del titulo se vuelvan blancas debido a falta de tiempo.

   - **Solución**: Revisar cual es el div correcto y agregarle una clase que haga que cuando se active el hover cambien las letras a color blanco, dandole la propiedad color:white en Css.

### 6. Dudas o problemas técnicos

- **Problema**: Si tienes cualquier otra duda o experimentas problemas técnicos que no se mencionan aquí, por favor, no dudes en contactarme a través de la información de contacto proporcionada en la parte inferior de cada sección de la página. Estoy aquí para aprender y resolver cualquier problema que puedas tener.

Esperamos que estas soluciones te ayuden a resolver cualquier problema que puedas encontrar mientras utilizas GAMEATING. Si necesitas asistencia adicional, no dudes en ponerte en contacto con nosotros.

## Cómo Contribuir

Si deseas contribuir a este proyecto, puedes realizar un fork del repositorio en GitHub, hacer tus cambios y enviar una solicitud de extracción (pull request). Tu contribución será revisada y, si es apropiada, se fusionará con la rama principal.

Puedes hacer esto de la siguiente forma:

1. Haz un fork de este repositorio.
2. Crea una nueva rama para tu contribución: `git checkout -b tu-nueva-caracteristica`
3. Realiza tus cambios y commitea: `git commit -m "Añade una nueva característica"`
4. Envía tus cambios al repositorio: `git push origin tu-nueva-caracteristica`
5. Crea una solicitud de extracción en GitHub.

## Licencia

Este proyecto está bajo la Licencia MIT License. Puedes ver más detalles en el archivo `LICENSE`.

## Autor

- **Nombre**: Andrés Labat Beltrán
- **Fecha de Comienzo del Proyecto**: 14/09/2023
- **Teléfono de Contacto**: 650 68 29 61
- **Email**: andreslabat89@gmail.com.
- **Linkedin**: www.linkedin.com/in/andres-labat-beltran-99a082292.

## Agradecimientos

Agradecimentos a GeeksHubs Academy por los conocimientos que he podido adquirir esta semana y que han hecho posible este proyecto, en especial a nuestro querido profesor David Ochando Blasco.

¡Gracias por visitar GAMEATING y explorar nuestro proyecto!
