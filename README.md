# pathfindingAlgo
4st project, : I try something new and explore algorithm
Little program made in pair programming.
The objectif was to learned how to implemented from scratch a pathfinding algorithm.

## structure
only 2 function is important, the other is only here to obtain a visual effect.
- walk
- getDirectionsFromHeuristic

### walk 
Start in the inital position.
Add in the frontier list the pos of evey border cell sorted by distance.
The frontier list contain 4 cell, we remove the initial cell to add in the visited list
Explore the 4 cell like previously.

The visited list will grow again and again.
When the frontier list explore the objectif.
it will triger the end of the loop and 
retrace the path with the cell contained in the visited path 
(every cell in this function contain their pos and the pos of the previously explored cell)

### getDirectionsFromHeuristic
sort cell based on the distance with the help of pythagore.

We learn after that this method is call breath search.

## lesson learned 
I learned a lot in relation of algoritm and pair programming.
It's help me interract with better dev and sharpen my edge.
