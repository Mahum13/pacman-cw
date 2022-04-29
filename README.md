# pacman-cw
Coursework for an Artificial Intelligence module at King's College London based on the game 'Pacman'. The program, written in python, makes pacman win on its own without any player controls on two different sized grids.

This program follows a 'reward' system mechanic, where the three different states - nameley an empty cell, a cell with a ghost in it and a cell with food in it - are given a numerical reward value.
Pacman is then taught to go to nearest cell with the highest reward, which means it will first go to a cell with food in it, then a cell that is empty, and finally the cell with a ghost is of least priority.

This program runs the Pacman AI game in two grid sizes, small and medium.
