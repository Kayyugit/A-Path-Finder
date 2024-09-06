# A-Path-Finder
 Code for visulising A * finding algorithm

This code is from a tutorial I learnt online. I'll eventually add an explainer notebook giving a step-by-step breakdown on how the code words. 

# What is an A*Path Finder algorithm?
The A* Pathfinding Algorithm is a widely used and efficient method for finding the shortest path between two points in a grid or graph. It combines the actual cost of reaching a node from the start (g) with an estimated cost to the goal (h), calculated by a heuristic. The total cost for each node (f) is the sum of these two values (f = g + h).

The algorithm explores nodes in the grid by evaluating the one with the lowest f value, using an open set to track nodes to explore and a closed set for nodes already processed. A* continues until it finds the goal, reconstructing the shortest path or stopping if no path exists.

The A* Pathfinding Algorithm is useful because it effectively balances **optimality** (finding the shortest path) with **efficiency** (exploring fewer unnecessary nodes), making it one of the best algorithms for practical applications where pathfinding or navigation is needed. Here's why A* is particularly valuable:

### 1. **Guaranteed Shortest Path:**
   - A* guarantees that it will find the shortest path from the start to the goal as long as the heuristic function is admissible (i.e., it never overestimates the cost to the goal). This makes it a reliable algorithm for scenarios where accuracy is critical.

### 2. **Efficient Search:**
   - Unlike other algorithms like Dijkstra’s, which explore all possible paths equally, A* uses a heuristic to guide the search toward the goal, making it faster. It reduces unnecessary exploration, especially in large or complex grids, by prioritizing nodes that seem to be closer to the goal.

### 3. **Adaptable to Different Environments:**
   - A* can be adapted to a wide variety of environments, whether it’s a 2D grid, a 3D space, or a more complex graph. This flexibility allows it to be applied in fields like robotics, game AI, and network routing.

### 4. **Obstacle Handling:**
   - A* works well with environments that contain obstacles. It efficiently finds paths around barriers or blocked areas, making it ideal for real-world applications like robot navigation, where obstacles may frequently change or be added.

### 5. **Heuristic Flexibility:**
   - The algorithm allows for different heuristic functions, enabling customization based on the specific problem. For example, in a grid, the Manhattan distance heuristic is used, but other heuristics like Euclidean distance can be applied depending on the context.

### 6. **Widely Used in Real-Time Systems:**
   - In video games, A* is often used to guide characters or objects toward goals in real time while avoiding obstacles. Its efficiency and adaptability make it suitable for dynamic environments where the path may need to be recalculated frequently.

### 7. **Balances Speed and Accuracy:**
   - A* strikes a balance between the fast but potentially suboptimal Greedy Best-First Search (which focuses only on the heuristic) and Dijkstra's Algorithm (which finds the shortest path but explores all nodes). A* minimizes exploration while ensuring accuracy.

This was a really fun project because it focused on visualizing how it works. In the future, I'll also be adding projects where I use this algorithm in other programs.
