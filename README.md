# 2048 Game - Flutter Implementation

This is a Flutter implementation of the classic single-player puzzle game 2048.

## Features

* Swipe gestures to move tiles
* Keyboard controls (arrow keys) for desktop support (optional)
* Smooth animations for tile movements and merging
* Scoreboard to track your progress
* Undo and restart buttons

### Demo

You can see a demonstration of the game in action here:
![Game Demo](Demo/demo.gif)

### Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/dcaayushd/2048-Game-Flutter.git
```

2.**Install dependencies:**

```bash
cd 2048_game
flutter pub get
```

3.**Run the app:**

```bash
flutter run
```

### How to Play

The goal of the game is to combine numbered tiles on the grid to create a tile with the number 2048. Swipe your finger (or use the arrow keys on desktop) to move the tiles in any direction. When two tiles with the same number collide, they merge into a single tile with the sum of their values.

The game ends when there are no more legal moves available, or when a 2048 tile is created.

### Using Keyboard Controls

On desktop platforms, you can use the arrow keys to move the tiles:

* Up arrow: Move tiles up
* Down arrow: Move tiles down
* Left arrow: Move tiles left
* Right arrow: Move tiles right

**Note:** Keyboard controls are currently optional and require enabling them in the code.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
