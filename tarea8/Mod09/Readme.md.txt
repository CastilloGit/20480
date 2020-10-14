***Ejecicio 1: Almacenamiento en caché de datos sin conexión mediante la API de caché de aplicaciones***

Al principio no se ejecutaba el comportamiento que describe el laboratorio.

Únicamente he cambiado esta línea que en el texto aparecía con un salto y la he puesto continua y ha comenzado a funcionar

applicationCache.addEventListener("error", hideLinksThatRequireOnline, false);

applicationCache.addEventListener("error",
            hideLinksThatRequireOnline, false);


