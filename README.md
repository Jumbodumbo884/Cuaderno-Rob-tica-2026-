# CONNECTING THE WORLD (ROBOT MAQUEEN).
En este proyecto tendremos que superar un circuito de obstáculos propuesto por el profesor con la finalidad de que sea el propio robot el que supere el circuito.

## PROGRAMA MAESTRO (ISAAC).
<img width="442" height="308" alt="Maestro isaac" src="https://github.com/user-attachments/assets/e98f8144-f486-4d66-9dfd-9c3bea74bcb0" />
Al iniciar el programa el maestro en este caso la placa debera enviar a su esclavo en decir a Maqueen todas la señales a través del canal de radio 2. Seguidamente cuando presiones el botón A enviará a través del canal de radio enviara el número 1, de la misma manera al pulsar el botón B enviara por el canal radio el número 2, una vez más cuándo esta vez pulsemos A+B por el canal de radio se enviara el número 3 y para finalizar si agitamos la placa a través del canal de radio se enviara el número 4. Todo esta información se hace llegar al esclavo que  procederemos a explicar a continuación.

## PROGRAMA ESCLAVO (YO).
<img width="824" height="488" alt="Esclavo guille" src="https://github.com/user-attachments/assets/533c1b59-b63f-44a1-94b0-108d46a6c67a" />
Al iniciar este programa deberemos conectarnos al mismo canal de radio que el maestro en este caso el canal 2. Seguidamente necesitaremos recibir el canal de radio. A continuación utlizaremos un bloque de logica por el cual el programa empieza a dar sus inicios. Si recibir número = 1 el motor derecho avanzará a velocidad 35 mientras que el izquierdo se para ccon lo cual el robot se momería para la izquierda, en este caso si recibir número = 2 el motor de la izquierda avanza a velocidad 35 mientras que el derecho se para con lo cual el robot se moverá a la derecha, seguidamente si recibir número = 3 los dos motores se paran y finalmente si recibir número = 4 los dos motores avanzaran a velocidad 60 y en segundo plano se podrá escuchar una melodía mientras que va para adelante.



## RESULTADO FINAL
[![](https://img.youtube.com/vi/IepE1G6CZ/0.jpg)](https://www.youtube.com/watch?v=IepE1G6CZ)
