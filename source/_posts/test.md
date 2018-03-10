---
layout: w
title: test
date: 2018-03-10 09:58:23
tags:
    - Open Courses
    - Mathematics
    - Linear Algebra
    - MIT 18.06SC Linear Algebra
toc: true
---

Hmmm... I'm learning [MIT 18.06SC Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/index.htm) at [MIT OpenCourseWare](https://ocw.mit.edu/index.htm).

OK, here we go!

Unit I: $A\boldsymbol{x} = \boldsymbol{b}$ and the Four Subspaces
============

Session 1.1: The Geometry of Linear Equations
----------------

We have a system of equations:
$$
\left\{
\begin{aligned}
2x - y &= 0 \\
-x + 2y &= 3
\end{aligned}
\right .
$$

### Row Picture

Line $2x - y = 0$ and line $-x + 2y = 0$ intersects at the point $(1, 2)$, so $(1, 2)$ is the solution of the system of equations.

>Maybe I should draw a X-Y coordinates here...

### Column Picture

We rewrite the system of linear equations as a single equation:

$$
x\begin{bmatrix}2 \\ -1\end{bmatrix} + y\begin{bmatrix}-1 \\ 2\end{bmatrix} = \begin{bmatrix}0 \\ 3\end{bmatrix}
$$

We see $x$ and $y$ as scalars of column vectors: $\boldsymbol{v_1} = \begin{bmatrix}2 \\ -1\end{bmatrix}$ and $\boldsymbol{v_2} = \begin{bmatrix}-1 \\ 2\end{bmatrix}$, and the sum $x\boldsymbol{v_1} + y\boldsymbol{v_2}$ is called a *linear combination* of $\boldsymbol{v_1}$ and $\boldsymbol{v_2}$.

Geometrically, we can find one copy of $\boldsymbol{v_1}$ added to two copies of $\boldsymbol{v_2}$ just equals the vector $\begin{bmatrix}0 \\ 3\end{bmatrix}$. Then the solution should be $x = 1, y =2$.

>I will add a figure when time is available \>\_\>

### Matrix Picture

We rewrite the equations in our example as a compact form,

$$
A\boldsymbol{x} = \boldsymbol{b},
$$

that is

$$
\begin{bmatrix}2 & -1 \\ -1 & 2\end{bmatrix}\begin{bmatrix}x \\ y\end{bmatrix} = \begin{bmatrix}0 \\ 3\end{bmatrix}
$$

### Matrix Multiplication

$$
\begin{aligned}
\begin{bmatrix}2 & -1 \\ -1 & 2\end{bmatrix} \begin{bmatrix}1 \\ 2\end{bmatrix} = 1\begin{bmatrix}2 \\ -1\end{bmatrix} + 2\begin{bmatrix}-1 \\ 2\end{bmatrix} = \begin{bmatrix}0 \\ 3\end{bmatrix}
\end{aligned}
$$

A matrix times by a vector is just **a linear combination of the column vectors of the matrix**.
