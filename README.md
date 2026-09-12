# Algorithms and Data Structures

Coursework and algorithm-design notes from the University of Leeds **Algorithms** module (OCOM5102M).

I developed my understanding of stable matching, graph search, dynamic programming, AVL trees, hashing and NP-completeness, with an emphasis on explaining why an algorithm works and how its resource requirements grow.

## Public project

[`notebooks/graph-cycle-design.ipynb`](notebooks/graph-cycle-design.ipynb) preserves my pseudocode and complexity discussion for a graph exercise using adjacency lists, an adjacency matrix and common-neighbour indexing.

The procedure looks for an **induced four-cycle** in a simple undirected graph: two non-adjacent vertices with two non-adjacent common neighbours. It is not a general detector for every cycle. The notebook is an original design artefact written in pseudocode, not an executable Python package.

### Reading the original analysis

The original notebook is preserved as submitted. Its statement that a sparse graph always gives a linear sum of squared degrees is too strong: a star graph is a counterexample. Read that runtime discussion as coursework reasoning rather than a verified performance guarantee. This clarification was added for the public portfolio edition.

## Wider module learning

The assessment work also covered:

- stable matching and functions;
- graph representations, breadth-first search and search trees;
- divide-and-conquer recurrences;
- dynamic programming through Bellman-Ford;
- AVL balancing and rotations;
- linear probing, quadratic probing and double hashing; and
- reasoning about membership in NP and NP-completeness.

The notebook provides the public project artefact; this topic list describes the broader module, not separate implementations of every topic. The marked assessment export and university question/marking material remain outside this public edition.

## View the notebook

Open the notebook on GitHub, or use Jupyter locally. Its pseudocode cells are intended to be read rather than executed.

[Full portfolio](https://saqibsafdar.com/projects/) · [GitHub profile](https://github.com/saqibsafdar11)
