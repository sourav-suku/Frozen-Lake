## Frozen-Lake-Problem
• Implemented a frozen lake scenario given the inputs, number of holes (M) and size of the lake (N) (Assumed the lake is square). Starting point will be (0, 0) and goal will be to reach at (N-1, N-1)

• Used Reinforcement Learning and Q - learning  method to solve this Frozen Lake Problem.

### Steps:

• Each time our RL agent chooses to either explore or exploit. It would randomly chose a move if exploring or else it would use already calculated q-values to make its move.

• BellMan Optimality equation gives the optimal q-value for each state action pair. The agent calculates the difference between q-value of its action at that state and the optimal q-value and learn from it.

• After 3000 iterations the RL agent is able to learn pretty well that the moves it make are the optimal moves at that state and thus it successfully finds a path from source to goal



