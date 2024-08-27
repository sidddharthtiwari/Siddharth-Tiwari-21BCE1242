# 🧩 Hitwicket Turn-based Chess-like Game

Welcome to the **Hitwicket Turn-based Chess-like Game**! 🎮 This project showcases a strategic, turn-based game inspired by chess, featuring unique characters and moves. Built with **HTML**, **CSS**, **JavaScript**, and **Bootstrap**, the game delivers a seamless and engaging experience.

## 🌟 Features

- **Real-time Gameplay**: Enjoy smooth, turn-based action using WebSocket for real-time communication.
- **5x5 Grid Game Board**: A compact and challenging battlefield for strategic minds.
- **Unique Characters**: 
  - **Pawn**: Moves one block in any direction.
  - **Hero1**: Moves two blocks straight, eliminating any opponent in its path.
  - **Hero2**: Moves two blocks diagonally, eliminating any opponent in its path.
- **Responsive UI**: Built with Bootstrap for a clean, mobile-friendly interface.
- **Interactive Controls**: Clickable pieces with highlighted valid moves.

## 🛠️ Tech Stack

- **Frontend**: 
  - **HTML** for the structure
  - **CSS** for styling and layout
  - **JavaScript** for game logic and interactions
  - **Bootstrap** for responsive design

## 🎯 Game Rules

1. **Game Setup**:
   - The game is played on a 5x5 grid by two players.
   - Each player controls a team of 5 characters: Pawns, Hero1, and Hero2.

2. **Character Movement**:
   - **Pawn**: Moves one block in any direction (L, R, F, B).
   - **Hero1**: Moves two blocks straight (L, R, F, B), eliminating any opponent in its path.
   - **Hero2**: Moves two blocks diagonally (FL, FR, BL, BR), eliminating any opponent in its path.

3. **Game Flow**:
   - Players alternate turns, making one move per turn.
   - Characters are eliminated upon collision with an opponent's character.

4. **Winning**:
   - The game ends when one player eliminates all the opponent's characters.

## 🚀 Getting Started

Follow these steps to get the game up and running locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd your-repo-name
   ```
3. **Open `index.html` in your browser** to start the game.

## 🧩 How to Play

1. Open the game in your browser.
2. Deploy your characters on the starting row.
3. Take turns with your opponent, selecting and moving characters strategically.
4. The first player to eliminate all opponent characters wins!

## 🎨 User Interface

- The 5x5 grid is prominently displayed with clear character positions.
- Player turn indication and move history are shown on the screen.
- Clickable pieces and valid move options are highlighted for easy gameplay.

## 🎉 Bonus Features

- **Dynamic Team Composition**: Choose your character mix at the start.
- **AI Opponent**: Practice against a computer-controlled player.
- **Spectator Mode**: Watch ongoing games live!
