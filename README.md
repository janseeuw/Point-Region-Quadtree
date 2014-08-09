#Quadtree

Typically location is represented by coordinate data. If we want to search data using the locations as key values,
we need data structures that efficiently represent selecting among more than two alternatives during a search.

One approach for 2D data is to use a quadtree.

A quadtree is a tree data structure in which each internal node has exactly four children. Quadtrees are most often used to partition a two-dimensional space by recursively subdividing it into four quadrants or regions.


#Point Region Quadtree

The Point Region Quadtree is a type of trie. Internal nodes do not store data. Leaf nodes hold a single data value.
We use a seperate class _Area_ to divide the coordinate space.
