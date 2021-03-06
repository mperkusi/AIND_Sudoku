# Diagonal Sudoku Solver

Q: How do we use constraint propagation to solve the naked twins problem?  
A: We use the concept of naked twins to restrict the possible values of boxes in the same unit in which the naked twins were found. With this restriction, we reduce the search space.

Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: We used three strategies, namely, elimination, only choice and naked twins, to reduce possible values of the boxes, consequently, reducing the search space. The only difference when comparing to standard sudoku was to add the diagonals as units.

### Install

This project requires **Python 3**.

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 
Please try using the environment we provided in the Anaconda lesson of the Nanodegree.

##### Optional: Pygame

Optionally, you can also install pygame if you want to see your visualization. If you've followed our instructions for setting up our conda environment, you should be all set.

If not, please see how to download pygame [here](http://www.pygame.org/download.shtml).

### Code

* `solutions.py` - You'll fill this in as part of your solution.
* `solution_test.py` - Do not modify this. You can test your solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing your solution.
* `visualize.py` - Do not modify this. This is code for visualizing your solution.

### Visualizing

To visualize your solution, please only assign values to the values_dict using the ```assign_values``` function provided in solution.py

### Data

The data consists of a text file of diagonal sudokus for you to solve.
