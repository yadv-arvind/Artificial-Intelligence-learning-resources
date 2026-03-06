Search Problem
- Initial State
- Actions
- Transition model
- Goal test
- Path cost function

Solution
- A sequence of action that leads from initial state to goal state

Optimal Solution
- A solution that has the lowest path cost among all solutions
- There can be multiple optimal solution

Node
a datastructure that keeps track of a
- a state
- a parent (node that generated this node)
- an action (action applied to parent to get node)
- a path cost (from initial state to node)


Approach
- start with frontier that contains initial state
- Repeat
   - If frontier is empty then no solution
   - Remove a node from frontier
   - If node contains goal state, return solution
   - Expand node, add resulting node to the frontier. Expand noed means look all node we can get to from this node
 
