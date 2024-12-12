# Knight's Tour Project

This repository contains implementations and documentation for solving the Knight's Tour problem, an age-old mathematical and algorithmic challenge involving a knight's traversal of a chessboard.

## Project Overview

The Knight's Tour problem explores whether a knight can move to every square on a chessboard exactly once. Variations include open tours (ending on a different square) and closed tours (returning to the starting square). This repository contains multiple approaches to solving the problem, from naive algorithms to advanced heuristics.

### File Descriptions

1. **`Warnsdoff.ipynb`**
   - Implements and explores Warnsdorff's Rule, a heuristic for solving the Knight's Tour.
   - Contains visualizations of the knight's path and explains the logic of selecting moves with minimal degrees.
   - Provides comparisons between different tie-breaking rules to optimize the pathfinding process.

2. **`Universal.ipynb`**
   - Offers a universal solution framework for the Knight's Tour problem.
   - Explores the adaptability of algorithms for different board sizes, shapes, and dimensions.
   - Demonstrates how classical heuristics perform under various constraints.

3. **`3D_general.ipynb`**
   - Extends the Knight's Tour problem to three-dimensional chessboards.
   - Introduces new rules and visualizations for 3D movements.
   - Highlights the complexity added by extra dimensions and strategies to address it.

4. **`simple.py`**
   - A Python script implementing a depth-first search (DFS) algorithm for the Knight's Tour.
   - Includes a validation function to ensure moves remain within bounds and a backtracking mechanism for efficient traversal.
   - Demonstrates the solution for an 8x8 chessboard starting from the top-left corner.

5. **`Copy of Select an arbitrary starting point.pdf`**
   - A comprehensive guide on the Knight's Tour, including historical context, mathematical formulations, and different approaches.
   - Explains key concepts like Warnsdorff's Rule, degree-based heuristics, and tie-breaking strategies.
   - Provides detailed steps for algorithm implementation with diagrams and matrix overlays.

### Key Concepts

- **Warnsdorff's Rule**: A heuristic that prioritizes moving to squares with the fewest onward moves (minimum degree).
- **DFS Algorithm**: A brute-force method exploring all potential paths while backtracking when encountering dead ends.
- **Matrix Overlays**: A geometric approach using matrices to visualize and compute the knight's possible moves.
- **3D Chessboards**: Extends traditional algorithms to account for additional dimensions, increasing the problem's complexity.

### Getting Started

#### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook
- Libraries: `numpy`, `matplotlib` (for notebooks)

#### Running the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/knights-tour.git
   cd knights-tour
2. Run the python script:
    ```bash
    python simple.py
3. Open and execute Jupyter notebooks for detailed explorations:
    ```bash
    jupyter notebook Warnsdoff.ipynb

