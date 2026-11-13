# --- ENGLISH ---

# Practice No. 1 — Matrices, Systems of Linear Equations and Geometry with Python

This practice uses Python (and R) to solve matrix equations, discuss and solve a linear system that depends on a parameter, and interpret its solutions geometrically.
It also covers 3D geometry, computing the orthogonal projection of a point onto a line and of a vector onto a direction vector.

## General Instructions

- Submissions must be made on **Blackboard**.
- Practices submitted more than **7 days** after the deadline will not be graded.
- Late submissions (7 days maximum) will receive a **20% penalty** on the final score.
- Grading will take into account both the solution and the definition of the functions used, in accordance with the material covered in class.
- The submission must include the **code** and a **PDF document** with the solutions.
- Any incomplete submission will be graded with **zero**.
- The practice must be completed in **groups of 2 students**.

---

## Problem 1 — Matrix Equations (3 points)

Implement in Python the setup and solution of the following matrix equations.

### Part (a)

Solve for X:

$$AX + 3B = -5X$$

Where the matrices A and B are:

$$A = \begin{pmatrix} -6 & -3 \\ 0 & -3 \end{pmatrix}, \quad B = \begin{pmatrix} -1 & 0 \\ 4 & -2 \end{pmatrix}$$

### Part (b)

Solve for X:

$$ACX + 3B = 10I - X$$

Where the matrices A, B, C and I are:

$$A = \begin{pmatrix} 1 & 2 \\ 0 & 2 \end{pmatrix}, \quad B = \begin{pmatrix} 2 & -1 \\ -1 & 5 \end{pmatrix}, \quad C = \begin{pmatrix} 2 & 6 \\ -1 & -0.5 \end{pmatrix}, \quad I = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$$

---

## Problem 2 — System of Linear Equations with a Parameter (3 points)

Given the following system of linear equations for the different real values of the parameter **a**:

$$\begin{cases} x + y - z = 1 \\ 3x + ay + az = 5 \\ 4x + ay = 5 \end{cases}$$

- Implement in **R** and in **Python** the discussion and solution of the system.
- Reason about and **geometrically interpret** the results.

---

## Problem 3 — Geometry in Space (4 points)

Given the points $P = (1, 2, -1)$, $Q = (1, 3, 2)$ and the line:

$$r \equiv \begin{cases} 2x + y - z = 6 \\ x - y + z = 1 \end{cases}$$

Compute:

**a)** The orthogonal projection of the point $P$ onto the line $r$.

**b)** The orthogonal projection of the vector $\overrightarrow{PQ}$ onto the direction vector of the line.

# --- SPANISH ---

# Práctica nº 1 — Matrices, sistemas de ecuaciones lineales y geometría con Python

## Instrucciones generales

- Las entregas se realizarán en **Blackboard**.
- No se calificarán prácticas entregadas con un retraso superior a **7 días** desde el plazo de finalización.
- Las entregas con retraso (máximo 7 días) tendrán una **penalización del 20%** sobre la puntuación final.
- En la calificación se tendrá en cuenta tanto la solución como la definición de las funciones utilizadas, de acuerdo a la materia vista en clase.
- La entrega se realizará en **código** y en **documento PDF** con soluciones.
- Cualquier entrega incompleta se calificará con **cero**.
- La práctica se realizará en **grupos de 2 alumnos**.

---

## Problema 1 — Ecuaciones matriciales (3 puntos)

Implementar en Python el planteamiento y resolución de las siguientes ecuaciones matriciales.

### Apartado (a)

Resolver para X:

$$AX + 3B = -5X$$

Donde las matrices A y B son:

$$A = \begin{pmatrix} -6 & -3 \\ 0 & -3 \end{pmatrix}, \quad B = \begin{pmatrix} -1 & 0 \\ 4 & -2 \end{pmatrix}$$

### Apartado (b)

Resolver para X:

$$ACX + 3B = 10I - X$$

Donde las matrices A, B, C e I son:

$$A = \begin{pmatrix} 1 & 2 \\ 0 & 2 \end{pmatrix}, \quad B = \begin{pmatrix} 2 & -1 \\ -1 & 5 \end{pmatrix}, \quad C = \begin{pmatrix} 2 & 6 \\ -1 & -0.5 \end{pmatrix}, \quad I = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$$

---

## Problema 2 — Sistema de ecuaciones lineales con parámetro (3 puntos)

Dado el siguiente sistema de ecuaciones lineales para los distintos valores reales del parámetro **a**:

$$\begin{cases} x + y - z = 1 \\ 3x + ay + az = 5 \\ 4x + ay = 5 \end{cases}$$

- Implementar en **R** y en **Python** la discusión y resolución del sistema.
- Razonar e **interpretar geométricamente** los resultados.

---

## Problema 3 — Geometría en el espacio (4 puntos)

Dados los puntos $P = (1, 2, -1)$, $Q = (1, 3, 2)$ y la recta:

$$r \equiv \begin{cases} 2x + y - z = 6 \\ x - y + z = 1 \end{cases}$$

Calcular:

**a)** La proyección ortogonal del punto $P$ sobre la recta $r$.

**b)** La proyección ortogonal del vector $\overrightarrow{PQ}$ sobre el vector director de la recta.
