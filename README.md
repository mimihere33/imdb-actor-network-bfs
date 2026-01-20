# Degrees of Separation in Movie Networks

This project models the IMDB movie dataset as a graph and computes the shortest
connection path between two actors using Breadth-First Search (BFS).

## Dataset
- Actors are represented as nodes
- Movies act as edges connecting actors who starred together
- Data sourced from IMDB CSV files
- Note: Dataset files are excluded from this repository due to size.

### Dataset Size
- Actors: 1044499
- Movies: 344276

## Approach
- Formulated as a graph search problem
- BFS guarantees the shortest path (minimum degrees of separation)
- Each state represents an actor and transitions represent co-starring movies

## Output
- Number of degrees of separation
- Actor-to-actor path
- Movies connecting each step

## Tech Stack
- Python
- Graph Search (BFS)
- CSV-based data processing

## Notes
Inspired by CS50’s AI course, with independent implementation and extensions.
