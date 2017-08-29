# Problema1
Maze Problem

This program was done by me to solve a little problem. Made with Python 2.7.13

The problem:

	In order to find the end of a given maze, the program should receive 4 arguments on the command line, separated by spaces: # of maze lines, # of maze columns, a string representing the maze, and a string representing the starting point.
	Example: python programa.py 3 3 -1,0,-1,0,0,-1,-1,-1,-1 1,1

    - # of maze columns and lines will always be an integer
    - The string representing the labyrinth will always consist of integers, separated by commas, without spaces
        - the integer -1 represents a wall
        - the integer 0 represents a path
    - The string representing the starting point will always consist of 2 integers, separated by a comma, without spaces. Being row and column respectively

    For the current example, the representation in an array would be:

    -1  0 -1
     0  0 -1
    -1 -1 -1

    The program should return as output:
        - The representation of the maze in string, with the path of an input to an output marked with integer 1, if possible;
        - 0 if there is no solution.

    Example input 1: python programa.py 3 3 -1,0,-1,0,0,-1,-1,-1,-1 1,1

    Expected output: -1,1,-1,1,1,-1,-1,-1,-1

    Example input 2: python programa.py 3 3 -1,-1,-1,0,0,-1,-1,-1,-1 1,1
	
	Expected output: 0
	
	
On top of that, I added a command '-v' for verbose that shows the output matrix like a real matrix instead of a string. Just because it is easier to check if something wrong by doing this.
