# ¡ A VOLAR !
Este proyecto consiste en superar un circuito propuesto por el profesor que consta de hacer un símbolo de un infinito pasando entre dos columnas y empezar y finalizar en el mismo sitio.

## DESCRIPCIÓN DEL DRON
<img width="638" height="398" alt="image" src="https://github.com/user-attachments/assets/b6243e1f-94a3-4d7e-9c69-944e28010774" />
<img width="495" height="261" alt="image" src="https://github.com/user-attachments/assets/b67a33c4-adbe-4155-998a-1c530516a24b" />
1. Hélices
2. Motores
3. Indicador de estado de la aeronave
4. Cámara
5. Botón de encendido
6. Antenas
7. Sistema de posicionamiento visual
8. Batería de Vuelo
9. Puerto Micro USB
10. Protectores para las hélices

## NORMATIVA EUROPEA DE VUELO
La normativa europea de drones (Reglamentos 2019/947 y 2019/945), actualizada en España con el Real Decreto 517/2024 y vigente en 2026, explica y clasifica los vuelos por riesgo (abierta, específica) y obliga a registrarse como operador si el dron tiene cámara o pesa >250g. Se debe volar a menos de 120m de altura, mantener contacto visual y respetar zonas geográficas. 
Drones clase 0: MTOW menor a 250g y su VELOCIDAD MÁXIMA DE 19m/s
Dron TELLO: Peso (incluidos los protectores para las hélices): 87 g
Velocidad máxima: 28,8 km/h (17,8 mph)
Tiempo de vuelo máx. 13 minutos (sin viento a 15 km/h [9 mph] sostenidos)

## ¿CÓMO TE DEBES CONECTAR AL DRON PARA PODER CONTROLARLO?
Para poder conectarte al dron debes activar la conexión Wi-Fi en su dispositivo electrónico y seleccione la red TELLO-XXXXXX seguidamente buscar la matricula correspondiente al dron para conectarte al mismo. La conexión se
habrá establecido cuando se muestre la vista de la cámara en directo en el dispositivo electrónico.

## MANUAL BÁSICO DE PROGRAMACIÓN CON DRONEBLOCKS
<img width="567" height="627" alt="image" src="https://github.com/user-attachments/assets/9ce54b24-9909-468a-8cc0-9c91f73bbb6a" />
En esta imagen podemos ver el primer programa de prueba para superar el reto que se ha propuesto hacer con el dron. A continuación veremos en que consiste:
El programa comienza con el bloque takeoff, que hace que el dron despegue y se mantenga flotando a una altura estable para que pueda empezar a moverse.

A continuación, el dron realiza un giro de 45 grados hacia la derecha. Este giro sirve para colocarlo en dirección diagonal respecto a las baldosas. Después avanza 84,5 cm dos veces es decir, recorre dos diagonales de baldosa seguidas.

Después el dron gira 45 grados hacia la izquierda, recuperando una orientación paralela a los lados de las baldosas, y avanza 60 cm, que es igual a recorrer el ancho de la baldosa.

Seguidamente el dron gira 90 grados hacia la izquierda, cambiando  de dirección para desplazarse hacia otras baldosas. Después avanza 60 cm dos veces es decir, recorre dos lados de baldosa seguidos.

Tras esto el dron vuelve a girar 45 grados hacia la izquierda para colocarse otra vez en diagonal. A continuación avanza 84,5 cm cuatro veces es decir que cruza cuatro baldosas seguidas en diagonal.

Más adelante el dron empieza a cambiar nuevamente su orientación mediante varios giros de 45 grados hacia la derecha, intercalados con desplazamientos de 60 cm, que corresponden a avanzar de una baldosa a la siguiente por sus lados.

Después vuelve a avanzar varias veces 84,5 cm, lo que indica que otra vez está desplazándose por diagonales de baldosas.

En la parte final del programa el dron realiza otro giro de 45 grados hacia la derecha, avanza 60 cm (un lado de baldosa) y finalmente ejecuta el bloque fly down 35 cm, que hace que el dron descienda 35 cm, probablemente para prepararse para el aterrizaje y finalizar el recorrido.

