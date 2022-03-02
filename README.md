# Trivial

## Problema 0

Extraemos el código duplicado a un único método "nuevaPosicioJugador", al que llamamos desde ambos sitios.
Creamos test unitario "si_al_principio_saco_un_1_voy_a_casilla_1"


## Problema 1

Creamos un condicional en el método "esJugable", en el que ponemos que si no hay 2 o más jugadores devuelva false.
Creamos un test unitario "menosDe2Jugadores"

## Problema 2

En el método "esJugable", en el condicional anterior agregamos con else, que si hay más de 6 jugadores devuelva false también.
Creamos un test unitario "jugadoresEntre2y6" 

## Problema 4

En la clase "GameLauncher" creamos un nuevo boolean (ganador), aplicando la lógica de lo que tenemos, cambiamos el while de "noGanador" a "!ganador", (que significaría lo mismo).

## Problema 5

En la clase "Game", extraemos el código repetido del método "fueRespuestaCorrecta" y creamos el método "pasarSiguienteJugador", el cual sustituimos para que no haya una redundancia. 