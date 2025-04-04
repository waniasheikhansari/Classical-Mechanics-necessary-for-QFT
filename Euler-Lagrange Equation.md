### Why do we need the Euler-Lagrange Equation?

1. Newton’s mechanics become complex when dealing with systems that involve generalized coordinates.  
2. The Lagrangian formulation give the simpler solution by focusing on scalar quantities instead of vector forces.
---
### Derivation of the Euler-Lagrange Equation:

y(x) is the function that makes the action S stationary, where:

S = ∫ f(y, y', x) dx    from x1 to x2  

where, y' = dy/dx

Assume a small variation in y(x):

y(x) → y(x) + ε * η(x)

where,
η(x1) = η(x2) = 0

δS = d/dε [ ∫ f(y + εη, y' + εη', x) dx ] at ε = 0

Using Taylor expansion and keeping first-order terms:

δS = ∫ [ (∂f/∂y) * η(x) + (∂f/∂y') * η'(x) ] dxq

∫ (∂f/∂y') * η'(x) dx  
= [ (∂f/∂y') * η(x) ] from x1 to x2 - ∫ d/dx(∂f/∂y') * η(x) dx

Since η(x1) = η(x2) = 0, the boundary term disappears.

δS = ∫ [ (∂f/∂y) - d/dx(∂f/∂y') ] * η(x) dx

For δS = 0 for any η(x), the integrand must be zero:

(∂f/∂y) - d/dx(∂f/∂y') = 0

d/dx ( ∂f/∂y' ) - ∂f/∂y = 0
