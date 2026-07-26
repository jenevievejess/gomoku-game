# Java Gomoku Game

A classic Gomoku (five in a row) game built in Java using Maven and JavaFX.


## How to Run

Requires Java and Maven (with JavaFX configured via the project's `pom.xml`).

**Running with IntelliJ IDEA**
Open the project in IntelliJ and run `GomokuGameFX.java`.

**Running from the Command Line**
Navigate to the project directory and run
```bash
mvn clean javafx:run
```


## Features

- Graphical user interface built with JavaFX
- Two-player gameplay on a Gomoku board
- Win detection for five in a row
- Restart and pause functionality


## Game Rules

Two players take turns placing stones on the board, and the first player to align five consecutive pieces horizontally, vertically, or diagonally wins.


## Screenshots

### Gameplay
![Gameplay](screenshots/gameplay.png)

### Winning Game
![Winning Game](screenshots/win.png)

