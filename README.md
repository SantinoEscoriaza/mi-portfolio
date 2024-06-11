/// PROYECTO PORTFOLIO SANTINO ESCORIAZA ///
// DETALLES //
/ El proyecto busca crear un sitio-web de tipo landing page, basandose en el siguiente diseño de Behance: https://www.behance.net/gallery/199548441/Portfolio-Web-Design
En el proceso, se hizo un analisis de este diseño para tener ciertas consideraciones a la hora de plasmarlo en codigo. que se detallan a continuación /


// MODIFICACIONES RESPECTO AL DISEÑO ORIGINAL //
/ HEADER Y NAVBAR: En el diseño original se esperaba que la barra de navegación sea transparente de tal forma que puediera verse la imagen de fondo que se encuentra en el hero. Esto implicaria que al hacer un "re-size" más grande o más chico de la página, el texto de la barra cambiase de color para hacer contraste y que sea legible. Por cuestiones de practicidad, y en parte falta de conocimientos sobre como llegar al resultado esperado, esto se descartó, dejando en su lugar un color fijo de fondo, acorde a la paleta de colores del sitio web, habiendo preguntado previamente si esto era válido /

/ HERO: 
1- En el diseño original, el título principal es una frase motivadora, que también como debía suceder en el header, el color del texto cambiaría segun el fondo para poder hacer contraste. Esta frase se reemplazó por una presentación personal, que es más acorde al formato de portfolio, y nuevamente, se descartó la superposición del texto con la imagen de fondo para poder dejarlo directamente de un solo color.
2- En el diseño original se encontraba lo que parece ser un boton que reproduce un video al ser presionado, con forma circular y texto en todo su alrededor. Buscando como lograr al menos el efecto de texto con forma circular, parece que la unica forma de hacerlo es con el uso de JavaScript, por lo que esto fue descartado. /

/ ICONOS DE REDES SOCIALES: Por cuestiones de privacidad, los iconos de Facebook, Instagram y X fueron programados para redirigir a los sitios web oficiales de cada red social respectivamente. En caso de que tuviese redes sociales solo de caracter profesional, como el caso de LinkedIn, estos deberian redirigir a ellas. /

/ SECCIÓN "Latest News & Blog": Esta sección que se encontraba originalmente en el diseño de Behance fue descartada del proyecto, ya que parece no tener un sentido realmente en lo que es un portfolio personal y estaría de más /

/ SECCIÓN TESTIMONIOS: El testimonio con la imagen colocada son unicamente de referencia. Considero que es una sección valida para el portfolio pero que si quedase vacia no tendría sentido y no podría reflejarse la idea de la sección. /

/ SECCIÓN CONTACTO: Los botones que deberían redirigir al gmail y whatsapp personal estan programados para redirigir al sitio web oficial de cada uno respectivamente, y el boton que deberia enviar el mensaje al correo personal no tiene ningún funcionamiento programado. Esto por falta de conocimiento en el uso de JavaScript. /

// OBSERVACIONES A TENER EN CUENTA //
/ IMAGENES USADAS: Las imagenes usadas en el hero y about son de referencia, ya que casualmente tenía esas fotos con vestimenta de colores muy acordes a la paleta de colores usada en el sitio-web. Soy conciente de que no son las ideales y preferentemente habría que reemplazarlas por algunas de caracter más profesional. /

/ SELECTORES: En la sección de Testimonios, y en los estilos responsive de la sección habilidades y proyectos solo para anchos de pantalla menores a 768px, se han colocado botones con lineas que hacen de selector o representan visualmente el testimonio, habilidad o proyecto que estamos viendo. La clase .selected hace que el que se supone está seleccionado tenga un color distinto para poder visualizarlo. Todo esto debería ser programado de manera más acorde, imagino que con el uso de un carrusel y de JavaScript, pero para que se entienda la idea se colocaron estos detalles. De la misma manera, los botones no tendrian sentido en pantallas menores a 768px, y deberian ser reemplazados por un navegador scroleable horizontalmente para que directamente naveguemos entre testimonios, habilidades o proyectos usando el TouchScreen de nuestro celular / tablet. /
