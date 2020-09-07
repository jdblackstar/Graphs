# Breadth-first vs. Depth-fist

### Breadth
- good to find the shortest path
- if the graph is really wide, we'll have to store the entire thing: not good

### Depth
- used to tell us if a path even exists
- might even end up taking the longest path, but won't use up as much memory

Essentially, walking through a maze until we hit a dead-end, walk back and find another path we haven't been down yet. Repeat.


