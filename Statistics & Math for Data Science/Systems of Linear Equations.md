# System of Linear Equations
**Definition**

A system of linear equations is a set of two or more linear equations involving the same variables, where the equations are of the first order, meaning the highest power of the variables is 1. Such systems can involve one, two, three, or more variables.

**General Form of a System of Linear Equations**

A system of linear equations in $$(n)$$ variables $$( x_1, x_2, ..., x_n )$$ can be written as:

$$[
a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1
]$$

$$[
a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n = b_2
]$$

$$[
\vdots
]$$

$$[
a_{n1}x_1 + a_{n2}x_2 + \dots + a_{nn}x_n = b_n
]$$

Where:
- $$( a_{ij} )$$ are the coefficients,
- $$( x_i )$$ are the variables,
- $$( b_i )$$ are constants.

**Matrix Form**

A system of linear equations can be represented in matrix form as:

$$[
AX = B]$$

Where:
- $$( A )$$ is the coefficient matrix,
- $$( X )$$ is the column vector of variables,
- $$( B )$$ is the column vector of constants.

**Solutions to Systems of Linear Equations**

A solution to the system is any set of values $$( x_1, x_2, ..., x_n )$$ that satisfies all the equations simultaneously. A system is **consistent** if it has one or more solutions, and **inconsistent** if it has no solution.

The system is **homogeneous** if $$( B = 0 )$$ (all constant terms are zero), and **non-homogeneous** if $$( B \neq 0 )$$.

---

## Methods to Solve Systems of Linear Equations

### 1. Cramer's Rule

Cramer's Rule is applicable when the coefficient matrix $$( A )$$ is a square matrix, and $$( |A| \neq 0 )$$.

**Example:**
Solve the system of equations:

$$[
x + 2y = 5
]$$

$$[
3x - y = 4
]$$

**Solution:**

The system in matrix form is:

$$[
\begin{bmatrix}
1 & 2 \\
3 & -1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}=\begin{bmatrix}
5 \\
4
\end{bmatrix}
]$$

Using Cramer's Rule:

$$[
D = \begin{vmatrix} 1 & 2 \\ 3 & -1 \end{vmatrix} = 1(-1) - 2(3) = -1 - 6 = -7
]$$

Now calculate $$( D_x )$$ and $$( D_y )$$:

$$[
D_x = \begin{vmatrix} 5 & 2 \\ 4 & -1 \end{vmatrix} = 5(-1) - 2(4) = -5 - 8 = -13
]$$

$$[
D_y = \begin{vmatrix} 1 & 5 \\ 3 & 4 \end{vmatrix} = 1(4) - 5(3) = 4 - 15 = -11
]$$

The solutions are:

$$[
x = \frac{D_x}{D} = \frac{-13}{-7} = \frac{13}{7}
]$$

$$[
y = \frac{D_y}{D} = \frac{-11}{-7} = \frac{11}{7}
]$$

---

### 2. Inverse Matrix Method

To solve $$( AX = B )$$ using the inverse method, we compute $$( X = A^{-1}B )$$.

**Example:**
Solve the system of equations:

$$[
2x + 3y = 8
]$$

$$[
x - y = 2
]$$

**Solution:**

The matrix form is:

$$[
\begin{bmatrix}
2 & 3 \\
1 & -1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
=\begin{bmatrix}
8 \\
2
\end{bmatrix}
]$$

Find the inverse of matrix $( A )$:

$$[
A = \begin{bmatrix} 2 & 3 \\ 1 & -1 \end{bmatrix}, \quad A^{-1} = \frac{1}{\text{det}(A)} \text{adj}(A)
]$$

$$[
\text{det}(A) = 2(-1) - 3(1) = -2 - 3 = -5
]$$

$$[
\text{adj}(A) = \begin{bmatrix} -1 & -3 \\ -1 & 2 \end{bmatrix}
]$$

$$[
A^{-1} = \frac{1}{-5} \begin{bmatrix} -1 & -3 \\ -1 & 2 \end{bmatrix} = \begin{bmatrix} \frac{1}{5} & \frac{3}{5} \\ \frac{1}{5} & \frac{-2}{5} \end{bmatrix}
]$$

Now, multiply $$( A^{-1} )$$ by $$( B )$$:

$$[
X = A^{-1}B = \begin{bmatrix} \frac{1}{5} & \frac{3}{5} \\ \frac{1}{5} & \frac{-2}{5} \end{bmatrix} \begin{bmatrix} 8 \\ 2 \end{bmatrix} = \begin{bmatrix} \frac{8}{5} + \frac{6}{5} \\ \frac{8}{5} - \frac{4}{5} \end{bmatrix} = \begin{bmatrix} \frac{14}{5} \\ \frac{4}{5} \end{bmatrix}
]$$

Thus, $$( x = \frac{14}{5} )$$, and $$( y = \frac{4}{5} )$$.

---

### 3. Gauss-Jordan Method

In the Gauss-Jordan method, we transform the augmented matrix into reduced row echelon form.

**Example:**
Solve the system:

$$[
x + 2y = 5
]$$

$$[
3x - y = 4
]$$

**Solution:**

The augmented matrix is:

$$[
\begin{bmatrix}
1 & 2 & | & 5 \\
3 & -1 & | & 4
\end{bmatrix}
]$$

Perform row operations to get the identity matrix on the left-hand side:

- $$( R2 \leftarrow R2 - 3R1 )$$: $$( \begin{bmatrix} 1 & 2 & | & 5 \\ 0 & -7 & | & -11 \end{bmatrix} )$$
- $$( R2 \leftarrow R2 / -7 )$$: $$( \begin{bmatrix} 1 & 2 & | & 5 \\ 0 & 1 & | & \frac{11}{7} \end{bmatrix} )$$
- $$( R1 \leftarrow R1 - 2R2 )$$: $$( \begin{bmatrix} 1 & 0 & | & \frac{13}{7} \\ 0 & 1 & | & \frac{11}{7} \end{bmatrix} )$$

Thus, $$( x = \frac{13}{7} )$$, and $$( y = \frac{11}{7} )$$.

---

### 4. Gauss Elimination Method

In this method, we reduce the system to an upper triangular matrix and then perform back substitution.

**Example:**
Solve the system:

$$[
2x + 3y = 8
]$$

$$[
x - y = 2
]$$

**Solution:**

Step 1: Create the augmented matrix:

$$[
\begin{bmatrix}
2 & 3 & | & 8 \\
1 & -1 & | & 2
\end{bmatrix}
]$$

**Step 2: Eliminate $$( x )$$ from the second equation:**

- $$( R2 \leftarrow R2 - \frac{1}{2}R1 )$$: $$( \begin{bmatrix} 2 & 3 & | & 8 \\ 0 & -\frac{5}{2} & | & -2 \end{bmatrix} )$$

**Step 3: Solve by back substitution:**

- From the second equation: $$( y = \frac{4}{5} )$$
- Substitute $$( y )$$ into the first equation: $$( x = \frac{14}{5} )$$

---

#### **5. LU Decomposition**

In LU Decomposition, we decompose the coefficient matrix $$( A )$$ into a product of a lower triangular matrix $$( L )$$ and an upper triangular matrix $$( U )$$.

**Example:**
Solve the system:

$$[
x + 2y = 5
]$$

$$[
x = \frac{13}{7}, \quad y = \frac{11}{7}
]$$

$$[
\begin{bmatrix} 1 & 2 \\ 3 & -1 \end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix}
=\begin{bmatrix} 5 \\ 4 \end{bmatrix}
]$$

**Step 1: Write the system in matrix form**

The system of equations can be represented as:

$$[\begin{bmatrix}
1 & 2 \\
3 & -1\end{bmatrix}
\begin{bmatrix}
x \\y\end{bmatrix}
= \begin{bmatrix}5 \\4\end{bmatrix}]$$

Let:
- $$( A = \begin{bmatrix} 1 & 2 \\ 3 & -1 \end{bmatrix} )$$ (Coefficient matrix)
- $$( B = \begin{bmatrix} 5 \\ 4 \end{bmatrix} )$$ (Constant matrix)

**Step 2: Perform LU Decomposition**

We decompose $$(A)$$ into the product of a lower triangular matrix $$(L)$$ and an upper triangular matrix $$(U)$$.

Let:
$$( A = LU )$$

Where:
- $$(L)$$ is a lower triangular matrix of the form $$( \begin{bmatrix} 1 & 0 \\ l_{21} & 1 \end{bmatrix} )$$
- $$(U)$$ is an upper triangular matrix of the form $$( \begin{bmatrix} u_{11} & u_{12} \\ 0 & u_{22} \end{bmatrix} )$$ 

**Compute $$(L)$$ and $$(U)$$**

We perform row operations on $(A)$ to make it upper triangular:

- Start with $$( A = \begin{bmatrix} 1 & 2 \\ 3 & -1 \end{bmatrix} )$$.
- Perform the row operation $( R_2 \leftarrow R_2 - 3R_1 )$:

  $$( R_2 = \begin{bmatrix} 3 & -1 \end{bmatrix} - 3 \times \begin{bmatrix} 1 & 2 \end{bmatrix} = \begin{bmatrix} 0 & -7 \end{bmatrix} )$$

Thus:
- $$( U = \begin{bmatrix} 1 & 2 \\ 0 & -7 \end{bmatrix} )$$
- $$( L = \begin{bmatrix} 1 & 0 \\ 3 & 1 \end{bmatrix} )$$

**Step 3: Solve $$(LY = B)$$**

Now, solve the system $$(LY = B)$$, where $$( Y = \begin{bmatrix} y_1 \\ y_2 \end{bmatrix} )$$:

$$[
\begin{bmatrix} 1 & 0 \\ 3 & 1 \end{bmatrix}
\begin{bmatrix} y_1 \\ y_2 \end{bmatrix}
=\begin{bmatrix} 5 \\ 4 \end{bmatrix}
]$$

From the first row:

$$(y_1 = 5)$$

Substitute $$(y_1 = 5)$$ into the second row equation:

$$(3(5) + y_2 = 4 \quad \Rightarrow \quad y_2 = 4 - 15 = -11)$$

Thus:

$$(Y = \begin{bmatrix} 5 \\ -11 \end{bmatrix})$$

**Step 4: Solve $(UX = Y)$**

Next, solve $(UX = Y)$, where $$(X = \begin{bmatrix} x \\ y \end{bmatrix})$$:

$$[
\begin{bmatrix} 1 & 2 \\ 0 & -7 \end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix}
=\begin{bmatrix} 5 \\ -11 \end{bmatrix}
]$$


From the second row:

$$(-7y = -11 \quad \Rightarrow \quad y = \frac{11}{7})$$

Substitute $(y = \frac{11}{7})$ into the first row equation:

$$(x + 2\left(\frac{11}{7}\right) = 5 \quad \Rightarrow \quad x + \frac{22}{7} = 5 \quad \Rightarrow \quad x = 5 - \frac{22}{7} = \frac{35}{7} - \frac{22}{7} = \frac{13}{7})$$

## Solution:

Thus, the solution to the system of equations is:

$$(x = \frac{13}{7}, \quad y = \frac{11}{7})$$