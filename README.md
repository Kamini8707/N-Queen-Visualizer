# N-Queen Visualizer

This N-Queen visualizer is an interactive tool to visualize the solutions for the N-Queens problem on a chessboard. It combines algorithmic problem-solving with front-end development, offering a clear visualization and user interaction.

## Project Overview

### **HTML File**
- **Structure**: Defines the layout of the web page.
- **Input Fields**: Includes an input box to specify the number of queens and a slider to control animation speed.
- **Buttons**: Provides a play button to start the visualization.
- **Containers**: Contains div elements (`n-queen-board`, `queen-arrangement`) to display chessboards and queen arrangements.

### **CSS File**
- **Styling**: Adds styles to elements for a modern and clean appearance.
- **Chessboard Colors**: Alternates cell colors for a checkerboard effect.
- **Slider & Button Styling**: Customizes the appearance of controls like the slider and play button.
- **Responsive Layout**: Ensures the design adapts to different screen sizes.

### **JavaScript File**
- **Logic Implementation**: Contains the core logic for solving the N-Queens problem using a backtracking approach.
- **Visualization**:
  - Dynamically creates chessboards for all possible solutions.
  - Animates the placement of queens with visual feedback.
  - Colors cells to indicate valid and invalid moves.
- **Interactivity**: Handles input validation, speed control via the slider, and play button functionality.

#### **Classes**
- **Queen**: Encapsulates the solution and visualization logic.
  - Methods like `isValid`, `solveQueen`, and `clearColor` manage chessboard states and animations.

#### **Algorithm**
- **Backtracking Algorithm**: Implements the recursive backtracking method to solve the N-Queens problem.

### **Features**
- **Dynamic Chessboard Creation**: Boards are generated based on the user input.
- **Visualization Feedback**: Highlights valid/invalid moves and placed queens.
- **Input Validation**: Ensures only valid values for the number of queens (1–8) are accepted.
- **Multiple Solutions**: Displays all possible arrangements for the given `n`.

## Summary
This project is a great example of combining algorithmic problem-solving with front-end development to create an engaging and functional visualization tool.
