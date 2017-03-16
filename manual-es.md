# Buscaminas

## Objetivo del juego

A pesar del nombre, el juego consiste en descubrir todas las casillas del tablero que **no** contienen minas, evitando las que sí 
tienen la tienen.

## Como se juega

- Para abrir una casilla simplemente pulsa sobre ella, podrás ver que ha cambiado su contenido por:
  - **Un número** entre el 1 y el 8: Hay ese número de minas cerca de la celda. 
  - **Vacío**: No hay minas cerca. Se abren automáticamente celdas hasta encontrar celdas "con número".
  - **Una mina con fondo rojo**: Mala suerte :( Has tocado una mina y has perdido.
- Puedes bloquear una celda haciendo una pulsación larga y aparecerá una bandera. 
Para poder abrir la celda vuelve a hacer una pulsación larga.
- Para empezar una nueva partida pulsa en el botón de la cara.

## Modos de juego

Este juego dispone de 3 niveles predefinidos diferentes y la posibilidad de crear nuevas configuraciones con las limitaciones 
(por cuestiones de usabilidad) que aparecen en la siguiente tabla: 

| Nivel  | Tamaño | Minas | % Minas |
| --- |---|---|---|
|     Fácil     |    8   |       6        |    9.375%    |
|  Intermedio   |   10   |       15       |     15%     |
|    Experto    |   12   |       30       |   20.83%    |
| Personalizado | 3 - 20 | 1 - 80% celdas | 0.25% - 80% |

## Sonidos
Si has pulsado en una celda sin mina escucharás un sonido que identifica el contenido de la celda.
- Si oyes un pitido, hay un número impar de minas cerca.
- Si oyes 2 pitidos, hay un número par de minas cerca.
- Cuantas más minas haya más agudo será. Por lo tanto, los sonidos más graves son para 1 o 2 minas, y los más agudos para 7 u 8 minas.
- Si pulsas en una celda vacía oirás una escala con los 4 sonidos usados en el los casos anteriores (de grave a agudo).

Cuando acaba la partida también oirás una escala de sonidos, de grave a agudo si ganas o de agudo a grave si pierdes.
