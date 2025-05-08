# Question 1

- Define what an optimization problem is, and list two examples from data science
- Describe why optimization problems are important in applications such as recommendation systems or supply chain management
- In your own words, explain one challenge (e.g., scalability, non-convexity, interpretability) that might arise in real-world optimization scenarios

## Answer

An optimization problem involves finding the best possible solution from all feasible solutions by either minimizing or maximizing an objective function subject to given constraints. In data science, two prominent examples are:

1. **Linear Regression**: Minimizing the mean squared error between predicted and actual values to find optimal model parameters
2. **Gradient Descent**: Finding the optimal weights in neural networks by minimizing the loss function iteratively

Optimization problems are crucial in modern applications:

- In **recommendation systems**, optimization helps maximize user satisfaction while minimizing computational resources by:
  - Finding the optimal balance between user preferences and item features
  - Maximizing relevance while maintaining diversity in recommendations
  - Minimizing response time while handling large-scale user-item matrices
- In **supply chain management**, optimization enables:
  - Efficient inventory management by minimizing storage costs and stockouts
  - Optimal route planning for logistics
  - Resource allocation across different stages of the supply chain
  - Demand forecasting and production planning

A significant challenge in real-world optimization scenarios is **scalability**. As systems grow:

- The number of variables and constraints increases exponentially
- Computational resources become a bottleneck
- Real-time optimization becomes challenging with large datasets
- The problem space becomes more complex, often requiring distributed computing solutions
- Traditional optimization algorithms may not scale efficiently with big data

Additionally, real-world data often contains noise, missing values, and outliers, making it harder to maintain optimization performance at scale while ensuring solution quality.
