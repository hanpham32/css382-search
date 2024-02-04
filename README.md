# search

Q1: Using Stack(LIFO)to keep track of the states that need to be explored. It initializes the stack with the initial state and an empty path. Additionally, set visited is to keep track of visited states so that we can avoid revisiting the same state.
Q2: Using Queue(FIFO) to keep track of the states that need to be explored. It initializes the queue with the initial state and an empty path. Additionally, set visited is to keep track of visited states so that we can avoid revisiting the same state.
Q3: explores states with the lowest cumulative path cost first, ensuring next move is found in terms of cost.
Q4: Implementation of A* search by using nullHeuristic function.
Q5: Implement function that tell Pacman the next move when reaching each walls
Q6:Using max() and manhattanDistance() to estimate the distance between pacman and each cornerto help the heuristic iteratively selects the nearest unvisited corner. returning updated distance by summing these distances, providing a lower bound estimate on the shortest path from the current state to the goal state where all corners are visited. 
Q7:Using max() and mazeDistance() to estimate the distance between pacman and each dots to help the heuristic iteratively selects the farthest remaining food. The total distance is updated by considering the maximum of the distances, providing an estimation on the shortest path from the current state to the goal state where all food pellets are consumed."
Q8:Complete the isGoalState() by returning the goal test
