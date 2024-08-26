This repository contains the qiskit code used in support of my master's thesis "Quantum Subroutines for Ellipsoid Method" by Benjamin Hanzsek-Brill.

The Ellipsoid Method(EM) is used in convex optimization. Given an $m \times n$ matrix $A$ and a vector $b$ of length $m$, the EM will find a vector $x$ such that $Ax >= b$ if it exists. It will then find a feasible $x^* $ which minimizes the function $f(x) = c^T x$. That is, EM generates $x* \in P = \{x\ in R^n: Ax \geq b\}$ such that there does not exist $y \in P$ where $f(y) < f(x*)$ or EM states $P$ is empty.
