# Connect 4 Game

## Description
Connect 4 is a classic two-player connection game where players take turns dropping colored discs into a vertical grid. The objective is to be the first to form a horizontal, vertical, or diagonal line of four discs. This implementation includes both a player vs. player mode and an AI mode, where players can compete against a computer opponent.

## Features
- **Two Player Mode:** Play against a friend.
- **AI Opponent:** Play against an AI using Minimax or Alpha-Beta pruning algorithms.
- **GUI:** A graphical user interface built with Tkinter.
- **Game State Display:** Current game board is displayed after each move.
- **Result Announcement:** The game announces the winner or if the game ends in a draw.

## Installation
To install and run the Connect 4 game locally, follow these steps:

### Prerequisites
- Python 3.x installed on your system.

### Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/BODY1998/connect_4
   ```
2. Navigate to the project directory:
   ```bash
   cd connect4
   ```
3. Run the game:
   ```bash
   python connect4_gui.py
   ```

## Usage
- Click on the desired column to drop your disc in the player vs. player mode.
- In the AI mode, the AI will make its move automatically based on the selected algorithm (Minimax or Alpha-Beta).
- The game continues until one player connects four discs or the board is full, resulting in a draw.

### AI Modes
- **Minimax:** A decision-making algorithm that minimizes the possible loss.
- **Alpha-Beta Pruning:** An optimization technique for the minimax algorithm that reduces the number of nodes evaluated.

## AI Depth
- At the start of the game, you will be prompted to select the AI depth (an integer between 1 and 10). This depth determines how many moves ahead the AI will analyze.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- Thanks to the contributors of the original Connect 4 game concept.
- Special thanks to the Tkinter library for the GUI interface and the game AI concepts utilized.

## Screenshots
![Game Screenshot](![image](https://github.com/user-attachments/assets/8b4aa5d2-c1f5-4335-80e2-d52bc25bc1af)
)
