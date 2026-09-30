[Welcome-260929.md](https://github.com/user-attachments/files/32835461/Welcome-260929.md)
# Adivina el número

## Descripción

**Adivina el número** es un juego desarrollado en Python donde la computadora intenta adivinar el número que piensa el jugador.

El jugador debe pensar en un número entre **1 y 100**. La computadora realiza diferentes intentos y el jugador le indica si el número que propuso es **mayor, menor o correcto**. Con estas respuestas, el programa va reduciendo el rango hasta encontrar el número.

## Objetivo del proyecto

El objetivo es desarrollar un programa sencillo que permita aplicar conocimientos básicos de programación en Python, como:

- Variables
- Condicionales
- Ciclos
- Entrada de datos
- Operaciones matemáticas
- Control de intentos

## ¿Cómo funciona?

1. El jugador piensa en un número del **1 al 100**.
2. La computadora realiza su primer intento.
3. El jugador responde:
   - `mayor` si su número es mayor.
   - `menor` si su número es menor.
   - `correcto` si la computadora acertó.
4. El programa actualiza el rango según la respuesta.
5. La computadora realiza otro intento.
6. El proceso continúa hasta encontrar el número correcto.
7. Al final, se muestra el número de intentos realizados.

## Tecnologías utilizadas

- **Python**
- **Visual Studio Code**
- **GitHub**

## Archivo principal

El archivo principal del proyecto es:

`juego.py`

Este archivo contiene el código del juego.

## Ejemplo de funcionamiento

```text
Adivina al numero

Piensa en un numero del 1 al 100
Yo intentare adivinarlo

Mi intento es: 50
Escribe mayor, menor, correcto: mayor

Mi intento es: 75
Escribe mayor, menor, correcto: menor

Mi intento es: 62
Escribe mayor, menor, correcto: correcto

¡Adiviné el número!
Número de intentos: 3
