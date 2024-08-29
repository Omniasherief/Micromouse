# Micromouse 
<p style="color:red;">-I asked chat gpt for the best algorithms we can use, so this is the answer. The idea is to move on to the next topic and try to develop a simulation for each one of them to implement the algorithm</p>
![Algorithm](https://img.shields.io/badge/Algorithm-Best%20Choices-brightgreen)


Micromouse algorithms vary in complexity and speed. Below is a list of common algorithms used in micromouse competitions, ordered from fastest to slowest:

1. **Flood Fill (Optimized/Real-Time)**
   - **Speed:** Fastest
   - **Description:** The mouse dynamically updates its map of the maze and recalculates the shortest path in real-time. This approach is very efficient but requires more sophisticated programming and hardware.

2. **A* (A-Star) Search Algorithm**
   - **Speed:** Fast
   - **Description:** A* is a popular pathfinding algorithm that finds the shortest path by evaluating both the cost to reach a point and the estimated cost to the goal. It's faster than basic flood-fill in many cases but can be computationally intense.

3. **Bellman-Ford Algorithm**
   - **Speed:** Fast
   - **Description:** This algorithm computes the shortest path from a single source to all other points in a maze. It's effective but less common due to its complexity compared to A* or flood fill.

4. **Breadth-First Search (BFS)**
   - **Speed:** Moderate
   - **Description:** BFS explores all nodes at the present "depth" before moving on to nodes at the next depth level. It's straightforward but may take longer as it doesn't prioritize the most promising paths.

5. **Wall-Following (Left or Right Hand Rule)**
   - **Speed:** Slow
   - **Description:** The mouse follows one wall of the maze until it finds the goal. This algorithm is simple and requires minimal computation but is not efficient and can take a long time to reach the goal.

6. **Dead Reckoning**
   - **Speed:** Slowest
   - **Description:** The mouse moves in a predetermined pattern or direction until it hits a wall, then turns and continues. This method is rarely used as it’s highly inefficient and only suitable for very simple mazes.

The performance of these algorithms can also depend on the specific maze and the hardware capabilities of the micromouse.
