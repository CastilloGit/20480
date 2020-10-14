**Comunicando con un servidor remoto**

1. **Nombres y apellidos:** José Carlos Castillo Villarino
2. **Fecha:** 08/10/2020
3. **Resumen del Ejercicio:** el objetivo del ejercicio es la conseguir gestionar la comunicación con un servidor web remoto.
4. **Dificultad o problemas presentados y como se resolvieron:** al meter el listener DOMContentLoaded lo hice al final después de la función asíncrona getPerson y de esta manera no era invocado y no hacía la función de crear los objetos y meterlos en la tabla con lo que no se veían. He recolocado el listener antes de la función asíncrona y ya funciona.