
###  AI-Based Self-Driving Car
#  Project Description
This project simulates an AI-based self-driving car within a grid environment, incorporating various search algorithms and heuristics to navigate and achieve goals efficiently. The system models a grid-based world where the car (agent) can move, encounter obstacles, and interact with dynamic elements such as goals and hazards.

#  Features
  # Grid Environment Class:
        
        #  Grid Representation: Creates a grid environment where agents navigate through.
        #  Grid Elements: Supports grid creation with specified dimensions, obstacles, goals, coins, and potholes.
        #  Agent Movement: Agents can move in the grid in four possible directions: up, down, left, and right.
        #  Pathfinding: Implements multiple search algorithms to find paths to goals in the grid.
  
  #  Search Algorithms:
        #  Breadth-First Search (BFS): Explores all possible paths level by level to find the shortest path.
        #  Depth-First Search (DFS): Explores paths by diving deeper into the grid until it reaches the goal or a dead end.
        #  Hill Climbing Search: Continuously moves towards the direction of the greatest increase in the heuristic value.
        #  A Search:* Utilizes both path cost and heuristic estimates to find the most efficient path to the goal.
        #  Local Beam Search: Explores multiple paths from the current state and selects the best among them.
        #  Greedy Best-First Search: Chooses paths based on the heuristic alone, aiming for the quickest path to the goal.
        
  # Heuristics:
        #  Adversarial Search: Implements Minimax with Alpha-Beta Pruning to simulate and evaluate multiple agents' interactions in the grid.
        #  Euclidean Distance: Measures the straight-line distance between points.
        #  Manhattan Distance: Computes the distance between points by only moving along grid lines.
        #  Chebyshev Distance: Calculates the maximum of the horizontal and vertical distances between points.
        
  #  Other Functionality:
        #  Evaluation Function: Assesses rewards and penalties based on agent actions and grid configuration.
        #  Constraint Satisfaction Problem (CSP) Solver: Solves constraints within the grid, ensuring that agents adhere to specific rules and conditions.
        #  Adversarial Search: Simulates and evaluates interactions among multiple agents using minimax with alpha-beta pruning.
        #  Display Functions: Provides formatted output to visualize the grid and search results.
  
  #  Input Handling:
      #  Grid Configuration: Allows users to specify grid dimensions, number of goals, agents, and their starting positions.
      #  Search Parameters: Users can choose heuristics and adjust parameters for search algorithms.

