# Multiplayer-Games-with-Web-Sockets

Website that allows you to play multiplayer games like Tic Tac Toe and Rock Paper Scissors with your friends!
It uses Socket.IO to facilitate a real time connection between the two connected players.

Our platform uses the power of WebSockets to ensure instant communication between players, creating an engaging and dynamic gaming experience. Get ready to test your skills, enjoy friendly rivalry, and create memories with our interactive multiplayer games. Let the games begin!

## How to play the game:
When a player starts a game, emit a 'start game' event to the server.
The server pairs up two players who want to play the same game.
Players make their moves and send them to the server.
The server validates the moves, updates the game state, and broadcasts the updated state to both players.
The game continues until a win or draw condition is met.
The server sends a 'game over' event to both players.


## How to run:

1. Clone the repository
2. Run `npm install` to install all the dependencies
3. Run `npm start` to start the server
4. Open `localhost:3000` in your browser


# Technology used:

- JavaScript
- Node.JS
- HTML
- CSS
- Socket.IO
- Tailwind CSS
