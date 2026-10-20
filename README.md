# Asado Crush (web build)

Playable browser build of Asado Crush, a simplified Candy Crush made in Java Swing by a team of three for the Programming Technology course (Tecnología de Programación) at Universidad Nacional del Sur, Argentina, in the second term of 2023.

Play it at https://agusvilla.dev.ar/candy-crush/

Pick a skin and clear five levels with three lives for the whole game. Each level adds a new kind of candy and gives you less time or fewer moves: regular candies, cross-striped candies, frosting, a bomb with a countdown and jelly. The game's text is in Spanish.

Move the cursor with the arrow keys and swap candies with W, A, S and D. It needs a keyboard, so play it on a computer.

## Authors

- Martin Agnello
- Maximo Fernandez
- Agustín Villamil

## About this repository

This repository only holds the web build: `CandyCrush.jar` (the game compiled for Java 8, with resized images) and `index.html`, which runs the jar in the browser with [CheerpJ](https://cheerpj.com/). The game's source code stays in the course's private repository.

You can also play it on a desktop with Java 8 or later:

```bash
java -jar CandyCrush.jar
```
