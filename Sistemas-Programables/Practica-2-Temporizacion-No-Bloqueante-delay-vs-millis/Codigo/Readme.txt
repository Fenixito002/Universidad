Codigo fuente de la practica. Son dos programas para el MISMO circuito:

  ParpadeoDelay/ParpadeoDelay.ino    - Parte 1: los tres LEDs con delay() (el antipatron).
                                       Compila y corre, pero los LEDs NO llevan los ritmos
                                       pedidos; eso es lo que se quiere mostrar.
  ParpadeoMillis/ParpadeoMillis.ino  - Parte 2: los tres LEDs con millis(), cada uno con
                                       su periodo, mas la cuarta tarea del reto opcional
                                       (mensaje por serial cada 3 s).

En ParpadeoMillis los periodos estan en el arreglo leds[] arriba del .ino; para agregar
otro LED basta con agregar un renglon ahi. El periodo del serial es PERIODO_SERIAL_MS.

Cada .ino va dentro de una carpeta con su mismo nombre porque asi lo exige el IDE de Arduino.
Placa requerida en el Gestor de Tarjetas: "Arduino UNO R4 Boards".
