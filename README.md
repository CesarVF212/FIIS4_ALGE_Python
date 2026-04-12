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
