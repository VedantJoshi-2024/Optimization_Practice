## 1. Lagrangian Function  
The Lagrangian $$\mathcal{L}(x, y, \lambda)$$ combines the objective function $$f(x, y)$$ and the constraint $$g(x, y) = 0$$ using a Lagrange multiplier $$\lambda$$:  
$$
\mathcal{L}(x, y, \lambda) = f(x, y) - \lambda \cdot g(x, y)
$$

---

## 2. Necessary Conditions for a Stationary Point  
To find stationary points, solve the following system:  

### First-Order Partial Derivatives  
1. **With respect to $$x$$ and $$y$$**:  
   $$
   \frac{\partial \mathcal{L}}{\partial x} = \frac{\partial f}{\partial x} - \lambda \frac{\partial g}{\partial x} = 0 \\  
   \frac{\partial \mathcal{L}}{\partial y} = \frac{\partial f}{\partial y} - \lambda \frac{\partial g}{\partial y} = 0
   $$  
2. **With respect to $$\lambda$$** (original constraint):  
   $$
   g(x, y) = 0
   $$  

These equations ensure the gradients of $$f$$ and $$g$$ are parallel at the optimal point.

---

## 3. Practical Scenario: Budget-Constrained Optimization  
**Example**: A factory maximizes production output $$f(x, y)$$ (e.g., units produced) subject to a budget constraint $$g(x, y) = B - (c_1 x + c_2 y) = 0$$, where:  

- x, y = quantities of raw materials  
- c_1, c_2 = costs per unit  
- B = total budget  

**Solution**: Lagrange multipliers identify the optimal resource allocation $$(x^*, y^*)$$ that maximizes output without exceeding the budget. This method is widely used in:  

- Economics (utility maximization)  
- Machine learning (regularization)  
- Engineering (resource allocation)  
