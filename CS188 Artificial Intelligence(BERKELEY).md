# Lecture 1 : State spaces&uninformed search
  ## Search problems
  * Search problem is to find a solution which is a sequence of actions(a plan) that transforms the start state into a goal state
  * Reflect agent (consider the current state or its memory/do not consider future consequences)
  * planning agent (must have a model of how the world evovles in response to the actions took)
  1. Depth First Search (not the optimal solution/low effciency/takes small space)
  2. Breadth First Search (optimal/takes large space)
  3. Uniform Cost Search(UCS/optimal)

-------
# Lecture 2 : Informed Search
  ## Heuristic
  * heristic is a function that estimates how close a state is to a goal

  1. Greedy Search : Expand the nodes that seems closest(by heuristic function)
    Q:In Greedy Search, there is a problem that why don't we use the actual cost in heuristic function?
    A:Cause if you use actual cost, you can find the optimal solution, but we now are trying to find the optimal plan using the Greedy Search instead of  directly using the optimal plan.

    To remember GS may not find the best solution.

    So you can sense the difference betweeen UCS and GS
  2. 