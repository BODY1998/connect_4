# Connect 4

Connect 4 is a two-player board game in which players take turns dropping colored discs into a vertical grid. The objective is to be the first to connect four of one's own discs in a row, either horizontally, vertically, or diagonally. This implementation features both a player vs. player mode and a player vs. AI mode, where the AI can utilize Minimax or Alpha-Beta pruning strategies for decision-making.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Game Modes](#game-modes)
- [AI Modes](#ai-modes)
- [Gameplay](#gameplay)
- [Performance Measurement](#performance-measurement)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Player vs. Player Mode**: Compete against a friend.
- **Player vs. AI Mode**: Challenge an AI opponent that can use advanced strategies.
- **Graphical User Interface**: Intuitive interface built using Tkinter.
- **Multiple AI Algorithms**: Choose between Minimax and Alpha-Beta pruning algorithms for AI moves.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/BODY1998/connect_4.git
   cd connect_4
2. Ensure you have Python 3.x installed on your machine.

3. Install the required libraries:
   ```bash
   pip install matplotlib
   ```

4. Run the game:
   ```bash
   python connect4_gui.py
   ```

## Usage

Once the game is running, you will be prompted to select the AI depth and mode. The game will display the board, and you can click to drop your disc in the selected column.

## Game Modes

- **Player vs. Player**: Two players take turns clicking on the columns to drop their discs.
- **Player vs. AI**: One player competes against an AI opponent.

## AI Modes

- **Minimax**: A decision-making algorithm that minimizes the possible loss for a worst-case scenario.
- **Alpha-Beta Pruning**: An optimized version of Minimax that reduces the number of nodes evaluated.

## Gameplay

1. Upon starting the game, select the AI depth (between 1 and 10) and the AI mode (Minimax or Alpha-Beta).
2. The game board will appear, and players take turns making moves.
3. The game ends when one player connects four discs in a row or the board is full, resulting in a draw.

## Performance Measurement

The project includes a performance measurement feature to compare the execution time of the Minimax and Alpha-Beta algorithms. Run the `performance_measurement.py` file to visualize the results.

## Contributing

Contributions are welcome! If you would like to contribute, please fork the repository and submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to adjust any sections as needed!
