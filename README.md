# 📘 Project: Chess System Java

## 📖 General Overview
> This project is a chess game made entirely with Java. It was made mainly as a way for me to practive OOP fundamentals.
> The entire game is made to run on the CMD, highlighting white and black pieces (represented by yellow in this project) and mapping out each piece's possible moves

## 📁 Project Structure

├── src/

│   ├── application/
│   ├── boardgame/
│   ├── chess/
|   |   ├── pieces/

The project is made with layer architecture. The application package contains the Program and the UI classes, which are responsible for loading the board and the pieces.
The boardgame package has the basic class related to the board, such as Board, Piece and Position
The chess package is where the logic behind the actual game is. It contains all the pieces and its possible moves and the methods required to do chess related operations.
