# Tres en Raya

Este programa implementa un **juego de tres en raya** en Java, donde el jugador humano compite contra la máquina. El objetivo es alinear tres fichas del mismo tipo (en horizontal, vertical o diagonal) en un tablero de 3x3 antes que el oponente.

## Características principales
- **Modo de juego humano vs máquina**: El jugador compite contra la máquina, que toma decisiones aleatorias para sus movimientos.
- **Tablero dinámico**: El tablero se actualiza y se muestra en cada turno.
- **Reglas del juego**: 
  - El jugador humano utiliza las fichas `X`, mientras que la máquina usa las fichas `O`.
  - Los turnos alternan entre el jugador y la máquina.
  - El juego termina cuando:
    - Un jugador alinea tres fichas.
    - El tablero está lleno sin un ganador (empate).

## Instrucciones de uso
1. **Ejecutar el programa**: Inicie la aplicación y siga las instrucciones en la consola.
2. **Iniciar el juego**:
   - Ingrese `S` para comenzar el juego o `N` para salir.
3. **Colocar fichas**:
   - Durante el turno del jugador, ingrese las coordenadas de la fila y columna (del 0 al 2) donde desea colocar su ficha.
   - Ejemplo: `0 1` para colocar una ficha en la fila 0, columna 1.
4. **Turno de la máquina**: La máquina colocará su ficha aleatoriamente en una casilla vacía.
5. **Final del juego**:
   - El programa anunciará al ganador (jugador o máquina) o un empate, y luego terminará.

## Controles
- El jugador introduce las coordenadas en el formato: `<fila> <columna>`.
- Para salir del juego al inicio, ingrese `N`.

## Reglas del juego
- El jugador comienza siempre el primer turno.
- Las coordenadas del tablero van desde 0 hasta 2 tanto para filas como para columnas.
- El objetivo es alinear tres fichas antes que el oponente.

## Ejemplo de juego
1. Inicia el programa y acepta jugar (`S`).
2. El tablero se muestra inicialmente vacío:


|   #   |   #   |   #   |
|-------|-------|-------|
|   #   |   #   |   #   |
|-------|-------|-------|
|   #   |   #   |   #   |


3. Durante el turno del jugador, ingresa las coordenadas, por ejemplo, `0 0` para colocar su ficha en la esquina superior izquierda.
4. La máquina responde colocando su ficha en una casilla vacía seleccionada aleatoriamente.
5. El juego continúa hasta que haya un ganador o un empate.

## Requisitos
- **Java 8** o superior.
- Un entorno de desarrollo como **Eclipse**, **IntelliJ IDEA**, o la línea de comandos con el compilador de Java.

## Créditos
Este programa fue desarrollado como un ejercicio de implementación de lógica de juegos en Java. Es una versión simplificada de un juego clásico que pone en práctica conceptos básicos de programación orientada a objetos.

¡Disfruta del desafío! 🎮
