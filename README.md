# Maze.js

## Various algorithms for path traversal implemented in javascript

* DFS
* BFS

## Examples

```javascript
    // the map is represented by a two dimentinal array
    var map = 
        [
            [0, 0, 1, 0, 0, 0],
            [0, 0, 0, 0, 0, 1],
            [0, 1, 0, 0, 0, 1],
            [0, 1, 1, 0, 0, 0],
            [0, 0, 1, 1, 0, 1]
        ];
        
    var start = { x: 4, y: 0 };
    var end = { x: 1, y: 4 };

    // for DFS
    var dfsNodes = SearchAlgorithms.dfs(map, start, end);
    // for BFS
    var bfsNdes = SearchAlgorithms.dfs(map, start, end);

    // all algorithms return an array with all visited nodes
    // the nodes which exist in the path have the 'inPath' property true
```