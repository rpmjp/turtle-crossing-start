# Turtle Crossing Game 🐢

This is a simple Turtle Crossing game created using Python's Turtle Graphics. The objective of the game is to help the turtle cross the road safely while avoiding cars.

## 📝 Description

In this game, the player controls a turtle that moves upward using the **Up** arrow key. Cars move horizontally across the screen, and the player needs to avoid collisions. Every successful crossing increases the speed of the cars and the player's level.

## 🚀 Features

- **Leveling System**: Each successful crossing increases the level, making cars move faster.
- **Collision Detection**: The game ends if the turtle collides with a car.
- **Dynamic Car Creation**: Cars appear randomly from the sides of the screen.

## 🕹️ How to Play

1. Clone this repository:
   ```bash
   git clone https://github.com/rpmjp/turtle-crossing-game.git
   ```
2. Run the game using Python:
   ```bash
   python main.py
   ```
3. Control the turtle with the **Up** arrow key to cross the road.

## 📂 Project Structure

```bash
turtle-crossing-game/
│
├── car_manager.py      # Handles car creation and movement
├── main.py             # Main game logic
├── player.py           # Handles player (turtle) movement
├── scoreboard.py       # Manages level and game over display
├── LICENSE             # License information
└── README.md           # Project documentation
```

## 📝 License

This project is released under the [MIT License](LICENSE).
