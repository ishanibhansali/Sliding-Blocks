# Sliding-Blocks

Implemented A* Search Algorithm to find the minimum number of moves required to solve a sliding blocks puzzle.

Example start board = [[1,2,3], [4,0,5]]
                                        
Solved board = [[1,2,3], [4,5,0]]              

A move comprises of swapping zero with any of its neighbors.

Example move = [[1,2,3], [4,0,5]]      ->    [[1,2,3],[4,5,0]]
                                           
Illegal move = [[1,2,3], [0,4,5]]      ->    [[1,2,0], [3,4,5]]                            

Minimum number of moves required to solve the example start board is 1.

A* Search makes use of admissible heuristic to find the best path while opimizing the amount of work done.
