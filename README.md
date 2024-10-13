# Micromouse 

- I asked chat gpt for the best algorithms that we can use, so this is his answer; let's discover each one , try to implement and run it on simulations, ok?.

- I added links to help you understand every algorithm
-------------------------------------------------------------------------------------------------------------------------------------------------
Micromouse algorithms vary in complexity and speed. Below is a list of common algorithms used in micromouse competitions, ordered from fastest to slowest:

1. **Flood Fill (Optimized/Real-Time)**
   - **Speed:** Fastest
   - **Description:** The mouse dynamically updates its map of the maze and recalculates the shortest path in real-time. This approach is very efficient but requires more sophisticated programming and hardware.
   - Flood Fill can be implemented using BFS (or DFS, Depth-First Search)

  - **Helpful Links:**  
  - [Flood Fill Explained](https://www.youtube.com/watch?v=VuiXOc81UDM)  
  - [Flood Fill in Action](https://youtu.be/ldqAmkdthHY?si=XLgohyUDZdYd2DsR)  
  - [Simulator Demo](https://www.youtube.com/watch?v=V2KSZHkaBQY)

   
1. **A* (A-Star) Search Algorithm**
   - **Speed:** Fast
   - **Description:** A* is a popular pathfinding algorithm that finds the shortest path by evaluating both the cost to reach a point and the estimated cost to the goal. It's faster than basic flood-fill in many cases but can be computationally intense.

 
   - **Helpful Links:**  
  - [A* Algorithm Overview](https://www.youtube.com/watch?v=-L-WgKMFuhE)  





2. **Bellman-Ford Algorithm**
   - **Speed:** Fast
   - **Description:** This algorithm computes the shortest path from a single source to all other points in a maze. It's effective but less common due to its complexity compared to A* or flood fill.
  
- **Helpful Links:**  
  - [Bellman-Ford Breakdown](https://www.youtube.com/watch?v=j0OUwduDOS0)  
  - [Bellman-Ford Insights](https://www.youtube.com/watch?v=FtN3BYH2Zes)  



3. **Breadth-First Search (BFS)**
   - **Speed:** Moderate
   - **Description:** BFS explores all nodes at the present "depth" before moving on to nodes at the next depth level. It's straightforward but may take longer as it doesn't prioritize the most promising paths.
   - 
- **Helpful Links:**  
  - [BFS and DFS in Daily Life](https://www.youtube.com/watch?v=cPTgB3UeECk)  
  - [BFS Explained](https://www.youtube.com/watch?v=xlVX7dXLS64)  
  - [BFS Visualization](https://www.youtube.com/watch?v=JWP9EI88Yoo)  


4. **Wall-Following (Left or Right Hand Rule)**
   - **Speed:** Slow
   - **Description:** The mouse follows one wall of the maze until it finds the goal. This algorithm is simple and requires minimal computation but is not efficient and can take a long time to reach the goal.
  
 - **Helpful Links:**  
  - [Wall-Following Explained](https://www.youtube.com/watch?v=EPDAweXxKJ4)  

   


5. **Dead Reckoning**
   - **Speed:** Slowest
   - **Description:** The mouse moves in a predetermined pattern or direction until it hits a wall, then turns and continues. This method is rarely used as it’s highly inefficient and only suitable for very simple mazes.
     
   - **Helpful Links:**  
  - [Dead Reckoning Concept](https://www.youtube.com/watch?v=feKF-4Osl0U)  

   


The performance of these algorithms can also depend on the specific maze and the hardware capabilities of the micromouse.

