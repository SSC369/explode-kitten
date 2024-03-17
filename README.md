# Explode Kitten

Explode Kitten is a web-based single-player card game inspired by the popular card game "Exploding Kittens". The objective of the game is to draw all 5 cards from a deck without drawing an exploding kitten card.

## Features

- A deck of 5 cards consisting of cat cards, defuse cards, shuffle cards, and exploding kitten cards.
- Clicking on the deck reveals a card, which is then removed from the deck.
- The game continues until all 5 cards are drawn or an exploding kitten card is drawn.
- Defuse cards can be used to defuse an exploding kitten card.
- Shuffle cards restart the game with a new deck.
- Automatically saves the game for a user at every stage so the user can continue from where he left off last time.
- Real-time update of points on the leaderboard for all the users if they are playing simultaneously.


## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running

### Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/SSC369/explode-kitten.git
   cd explode-kitten/backend
Install backend dependencies:
- npm install
Set up environment variables:
- Create a .env file in the backend directory and add the following variables:
- **MONGODB_URI=your_mongodb_uri**
Start the backend server:
**node server.js**
change start script in package.json to nodemon server.js then use below command:
run command: **npm start**
     
### Frontend
Navigate to the frontend directory:
cd ../frontend

Install frontend dependencies:
npm install

create a .env file in your frontend file and add key VITE_SERVER = //your server link//

Start the frontend server:
npm run dev (vite react app)
npm start (react app)

This will automatically open your default web browser to http://localhost:3000 or http://localhost:5137 if your app is from vite react.

Usage
Click the "Play" button to begin.
Click on the deck to reveal a card.

Follow the rules mentioned below to play the game.

Rules
Draw all 5 cards from the deck to win the game.
If you draw an exploding kitten card, you lose the game.
Defuse cards can be used to defuse an exploding kitten card.
Cat cards and defuse cards are removed from the deck when drawn.
Shuffle cards restart the game with a new deck.

