# graph-php

A mathematical graph/network library written in PHP

## Install

The recommended way to install this library is [through composer](http://getcomposer.org). [New to composer?](http://getcomposer.org/doc/00-intro.md)

```JSON
{
    "require": {
        "clue/graph": "dev-master"
    }
}
```

## Examples

Looking for more example scripts? Check out [flos/graph](https://github.com/flos/graph).

## Features

* Loading graphs (from plain text adjacency lists or edge lists)
* Run algorithms
 * Deep-/Breadth search
 * Travelling salesman
 * Minimal spanning tree: Kruskal, Prim
 * Shortest path: Dijkstra, Moore-Bellman-Ford
 * Maximum flow: Edmonds-Karp
 * Minimum cost flow: Cycle cancelling, Successive shortest path
 * .. more to come
* Plotting with GraphViz (local installation needet)

## Tests

To run the test suite, you need PHPUnit. Go to the project root and run:
````
$ phpunit
````
