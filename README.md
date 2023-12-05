# Personaje_Navideno

## Nombre del Personaje
Angel con trompeta

## Materiales utilizados
|Nombre del componente | Descripción | Cantidad | Precio |
| - | - | - | - | 
|ESP32|Microcontrolador con comuncicación serial, wifi, bluetooth|1|$140.00|
|Cables Dupont|Cables MM HH MH para conexión de prototipos|50|$60.00|
|Tela|Tela de color blanco para vestimenta|1/2 m|$20|
|Servo|Motor que permite generar movimiento|1|$60|
|Alambron|Alambre que dará soporte al angel|1 m|$10|
|Muñeco|Extremidades para el angel|1|$60|
|Rollo de hilo blanco|Hilo para bordar extremidades y ropa|1|$10|
|Buzzer|Reproducira la melodia|1|$55|
|Foco RGB|Iluminar al angel|1|$15|
|Bolsa de algodon|Material para rellenar alas|1|$5|
|1 hoja de papel dorado|Material para aureola y trompeta|1|$3|



## Software utilizado
|Nombre de software|Versión|Tipo|
|-|-|-|
|Thonny|4.1.2|Software libre|
|SQLite|3|Software Libre|
|Visual Studio Code (Alternativa)|1.82|Software libre|
|MySQL|8.0|Software libre|

## Dibujo del prototipo a desarrollar
![Prototipo ](https://github.com/Alejandrox666/Personaje_Navideno/blob/main/WhatsApp%20Image%202023-09-28%20at%205.13.07%20PM%20(1).jpeg)


## Comunicación
-utilizaremos una placa ESP32 la cual ira conectada a un controlador, el cual controlará el motor, tambien se agregará un buzzer y un RGB 
todo esto controlado por medio de la ESP32 mediante WI-FI

## Arquitectura
-El angel principalmente contará con la placa ESP32 la cual sera la que dará ordenes a nuestros actuadores, los actuadores que utilizaremos son los siguientes:
-Foco RGB
-Servo
-Buzzer
Al dar una orden especifica el angel actuará de acuerdo a la orden dada.
![Arquitectura de angel](https://github.com/Alejandrox666/Personaje_Navideno/blob/main/WhatsApp%20Image%202023-09-28%20at%205.13.07%20PM.jpeg)

## Base de datos
![Base de datos ](https://github.com/Alejandrox666/Personaje_Navideno/blob/main/WhatsApp%20Image%202023-09-28%20at%205.13.08%20PM.jpeg)

## Proceso de realización
*Adherimos cuatro palos de madera y los amarramos para que fuera el cuerpo del angel.                                
*Pegamos los cuatro palos a una base de unicel fijandolos con silicón.
*Con la tela que compramos himimos dos brazos, y dos manos.
*Rellenamos las manos para posteriormente unirlas con hilo a los brazos.
*Rellenamos los brazos.
*Cortamos dos pedazos de alambre y los metimos dentro de ellos para darles forma y soporte.
*Uno de ellos lo amarramos a la estructura ya creada.
*Para continuar con lo siguiente realizamos las conexiones pertinentes con nuestros componentes.
*Conectamos nuestra placa ESP32 a la protoboard.
*Conectamos un servo. 
*Conectamos 5 leds.
*Conectamos un sensor de proximidad.
*Conectamos un buzer.
*Despues de estas conexiones pegamos un servo a la estructura, a la altura de los brazos para pegar el brazo restante a él y que el brazo realize un movimiento el cual consite en levantar su brazo para tocar la trompeta.
*Creamos la tropeta con cartulina y la pegamos al brazo del angel.
*Construimos una base de palitos dentro de la estructura del angel para poner todos nuestros componentes junto con la protoboard.
*Hicimos un agujero en la placa de unicel para pasar los 5 focos por debajo de ella y volver a sacarlos más enfrente.
*Pegamos un buzer a la misma estructura para que no se moviera.
*Pegamos la cabeza en la parte superior del angel con ayuda de silicon y una base de plastico, con ello quedó bien fijado.
*Hasta el momento fue todo lo que hicimos con estos componentes, despúes de tener todo en su lugar cargamos el código en la placa ESP32 para hacer ajustes respecto al funcionamiento (este código fue realizado por los miembros del equipo.
*Al quedar lista la primera parte de componentes procedimos a vestir de la parte de enfrente a nuestro angel, pues lo vestimos en partes.
*Conectamos una segunda ESP32 en ella conectamos un segundo servo y tambien un led.
*Continuamos con el mecanismo de las alas, para ello formamos dos alas con ayuda de alambre, adherimos unas bases pegadas a la espalda de la estructura y en ellas pusimos las alas dandoles estabilidad, a ellas hicimos que un par de alambre las jalará desde la parte de abajo con un servo lo cual iba a hacer que estas se abrieran y se cerraran.
*Pegamos un led a la cabeza del angel que hará parecer que es una corona del angel
*Cargamos el código en la ESP32 utilizando Arduino, al estar cargado realizamos los ajustes necesarios para un correcto funcionamiento de las alas.
*Añadimos la comunicación bluetooth al código ya cargado, el cual nos ayudará a mantener una correcta comunicación y control de la función del movimiento de las alas y el led que agregamos al final.
*Vestimos por completo al angel.
*Pintamos la cara del angel.
*Pegamos relleno en las alas para que simularan unas alas de un angel.
*Pegamos relleno en la base del angel para que simulara que estaba sobre las nubes.
*Hicimos nuestras pruebas finales

*


