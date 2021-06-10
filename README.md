# Frozen-Lake
Using Reinforcement Learning to solve the Frozen Lake Problem

Imagine there is a frozen lake stretching from our home to  office; we have to walk on the frozen lake to reach your office. But oops! There are holes in the frozen lake so we have to be careful while walking on the frozen lake to avoid getting trapped in the holes.
![frozen-lake](https://static.packt-cdn.com/products/9781788836524/graphics/49f3e058-2f32-40e8-9992-b53d1f57d138.png)


Two task we have to do here:

*   Implement a frozen lake scenario given the inputs, number of holes (M) and size of the lake (N) (Assuming the lake is square). Starting point will be (0, 0) and goal will be to reach at (N-1, N-1)
*   Implement Q-learning method to learn a path from start to goal.
*   Use the following reward scheme: 50 points on reaching the goal, -50 points on stepping on a hole.

#### Q-learning
 `Q[state, action]` gives  an action state pair to get an optimal policy.The Q-Loss equation becomes:
$E = ||r + \gamma \cdot \max_{a'} Q(s', a') - Q(s, a)||^2$

Using gradient descent to minimise $E$ and work out a learning rule for $Q(s, a)$. 
