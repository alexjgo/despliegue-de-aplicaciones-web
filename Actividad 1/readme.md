3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.


el token sirve para generar una contraseña de un solo uso que luego es validada por el servidor pero antes el usuario a de iniciar sesion una vez hecho el token se convierte en un dispositivo de confianza, el token se obtiene mediante una api (Las API son mecanismos que permiten a dos componentes de software comunicarse entre sí mediante un conjunto de definiciones y protocolos.)



4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?


HTTP se encuentra en la capa de red OSI o de Internet 

HTTP : 80

TCP se encuentra en la capa de red OSI o de Internet 

UDP : se encuentra en la capa intermedia entre la capa de red y la capa de aplicación

IP : se encuentra en la capa de Internet, también conocida como capa de red o capa IP



5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php

significa que el recurso solicitado ha sido movido temporalmente a la URL dada por las cabeceras Location en este caso : http://www.example.com/test/index2.php


6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

hay una captura en la carpeta actividad 1 llamada google donde se ve el wireshark y e puesto la ip de google y me a funcionado correctamente, ip: 142.250.184.13