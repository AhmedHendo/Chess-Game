# Chess Game

A desktop chess game built with Java Swing. The project separates the chess interface from the chess rules and game state, making it a small example of a Java GUI application with a dedicated game core.

## Features

- Interactive chessboard with chess pieces
- Classic chess move validation and turn tracking
- Castling and pawn promotion
- Game status tracking, including check, wins, stalemate, and insufficient material

## Requirements

- Java Runtime Environment (JRE) or Java Development Kit (JDK)

## Run

From the repository root, run:

```bash
java -cp . ChessGui.ChessGui
```

The repository currently includes compiled Java `.class` files and the NetBeans GUI form, but does not include the `.java` source files. As a result, the checked-in files can be run with a compatible Java runtime, but the project cannot be rebuilt or modified from source using this repository alone.

## Project Structure

```text
ChessCore/   Chessboard, pieces, moves, and game-state logic
ChessGui/    Swing user interface and NetBeans form
```
