# ino
Archivos de Arduino 

Para la construcción utilizamos dos arduinos, un Arduino UNO (Motor) y un arduino ESP32 (Luces). Para la configuración de ambos cabe destacar que la placa ESP32 si bien puede llegar a soportar como máximo 12V (De la fuente de poder que utilizamos) no es recomendable ni una buena práctica hacer directa conexión para suplir de poder a la placa, por ende, es necesario pensar en un modo de reducir el voltaje entre 5V a 7V para así evitar quemarla. En nuestro trabajo, le dimos solución conectándola a un cargador de celular de entrada tradicional que era capaz de suplir 5V desde la conección al sistema de corriente de la sala de exposición.

El motor utilizado es un Motor Paso A Paso Nema 23 de 200 Pasos, el cual necesita una alimentación de energía de 12V y el uso de un driver, en nuestro caso EasyDriver Driver que está diseñado para el uso de estos motores.
El motor fue controlado por un joystick, definiendo solamente el eje X del mismo.
Cables de conexión Macho-macho Hembra-Hembra y Hembra-Macho.
Las luces led utilizadas son Tira Cinta Led 2835 De 10 Mts RGB, una marca genérica que también necesita 12V para su funcionamiento y puede variar en la tonalidad (Uso del color). Estas fueron controladas por un sensor ultrasónico HC-sr04 con una lectura de >30cm.
