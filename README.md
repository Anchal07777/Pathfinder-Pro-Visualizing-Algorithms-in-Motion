# Pathfinder Pro - Algorithm Visualization in Motion

Welcome to **Pathfinder Pro**! This application was created to explore and visualize the workings of popular pathfinding algorithms, bringing these abstract concepts to life. I hope you enjoy experimenting with Pathfinder Pro as much as I enjoyed building it!

**Try it out here (best experienced on Google Chrome):** [ DEMO : Pathfinder Pro](https://pathfinder-pro-visualizing-algorithms-in.onrender.com/)

---

## Supported Pathfinding Algorithms

Pathfinder Pro offers a range of algorithms to visualize and understand their behavior in action:

- **Dijkstra's Algorithm (weighted)**: Known as the "original" pathfinding solution, Dijkstra’s is thorough and guarantees the shortest path.

- **A* Search (weighted)**: A highly efficient algorithm that combines pathfinding with heuristics, A* guarantees the shortest path faster than Dijkstra’s.

- **Greedy Best-First Search (weighted)**: A faster, more heuristic-heavy version of A*, which sacrifices the guarantee of the shortest path for speed.

- **Swarm Algorithm (weighted)**: A unique blend of Dijkstra's and A*, balancing exploration between the start and target nodes. This algorithm does not guarantee the shortest path.

- **Convergent Swarm Algorithm (weighted)**: An optimized version of the Swarm Algorithm, with a stronger heuristic focus. It is faster but also does not guarantee the shortest path.

- **Bidirectional Swarm Algorithm (weighted)**: Swarm operates from both the start and target nodes in this version, again without guaranteeing the shortest path.

- **Breadth-First Search (unweighted)**: An optimal choice for unweighted grids, guaranteeing the shortest path.

- **Depth-First Search (unweighted)**: Although useful in some contexts, DFS is not ideal for pathfinding, as it does not guarantee the shortest path.

## Maze Generation

Pathfinder Pro also includes a **Recursive Division Maze Generation** tool, which creates mazes to test and observe each pathfinding algorithm’s strengths and weaknesses in different scenarios.

---

## The Swarm Algorithm: An In-Depth Look

The **Swarm Algorithm** is a unique pathfinding approach that I developed in collaboration with a friend, Hussein Farah. This algorithm blends the comprehensive reach of **Dijkstra's Algorithm** with the heuristic-driven focus of **A* Search**. The Swarm Algorithm continually adjusts each node’s distance from the start while factoring in the estimated distance to the target. This dual focus allows it to converge on the target efficiently while exploring surrounding areas, resulting in a distinctive triangular search pattern. We named it "Swarm" because, like a player tracking both a primary target and nearby obstacles, the algorithm maintains awareness of surrounding nodes while progressing toward the target.

---

Pathfinder Pro is your gateway to understanding these powerful algorithms—so dive in, visualize, and enjoy discovering how pathfinding algorithms navigate complex paths!
