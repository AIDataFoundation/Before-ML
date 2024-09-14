# System of Linear Equations
**Definition**

A system of linear equations is a set of two or more linear equations involving the same variables, where the equations are of the first order, meaning the highest power of the variables is 1. Such systems can involve one, two, three, or more variables.

**General Form of a System of Linear Equations**

A system of linear equations in <img src="https://i.upmath.me/svg/(n)" alt="(n)" /> variables <img src="https://i.upmath.me/svg/(%20x_1%2C%20x_2%2C%20...%2C%20x_n%20)" alt="( x_1, x_2, ..., x_n )" /> can be written as:

<img src="https://i.upmath.me/svg/%5B%0Aa_%7B11%7Dx_1%20%2B%20a_%7B12%7Dx_2%20%2B%20%5Cdots%20%2B%20a_%7B1n%7Dx_n%20%3D%20b_1%0A%5D" alt="[
a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1
]" />

<img src="https://i.upmath.me/svg/%5B%0Aa_%7B21%7Dx_1%20%2B%20a_%7B22%7Dx_2%20%2B%20%5Cdots%20%2B%20a_%7B2n%7Dx_n%20%3D%20b_2%0A%5D" alt="[
a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n = b_2
]" />

<img src="https://i.upmath.me/svg/%5B%0A%5Cvdots%0A%5D" alt="[
\vdots
]" />

<img src="https://i.upmath.me/svg/%5B%0Aa_%7Bn1%7Dx_1%20%2B%20a_%7Bn2%7Dx_2%20%2B%20%5Cdots%20%2B%20a_%7Bnn%7Dx_n%20%3D%20b_n%0A%5D" alt="[
a_{n1}x_1 + a_{n2}x_2 + \dots + a_{nn}x_n = b_n
]" />

Where:
- <img src="https://i.upmath.me/svg/(%20a_%7Bij%7D%20)" alt="( a_{ij} )" /> are the coefficients,
- <img src="https://i.upmath.me/svg/(%20x_i%20)" alt="( x_i )" /> are the variables,
- <img src="https://i.upmath.me/svg/(%20b_i%20)" alt="( b_i )" /> are constants.

**Matrix Form**

A system of linear equations can be represented in matrix form as:

<img src="https://i.upmath.me/svg/%5B%0AAX%20%3D%20B%5D" alt="[
AX = B]" />

Where:

- <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />  is the coefficient matrix,
- <img src="https://i.upmath.me/svg/(%20X%20)" alt="( X )" /> is the column vector of variables,
- <img src="https://i.upmath.me/svg/(%20B%20)" alt="( B )" /> is the column vector of constants.

**Solutions to Systems of Linear Equations**

A solution to the system is any set of values <img src="https://i.upmath.me/svg/(%20x_1%2C%20x_2%2C%20...%2C%20x_n%20)" alt="( x_1, x_2, ..., x_n )" /> that satisfies all the equations simultaneously. A system is **consistent** if it has one or more solutions, and **inconsistent** if it has no solution.

The system is **homogeneous** if <img src="https://i.upmath.me/svg/(%20B%20%3D%200%20)" alt="( B = 0 )" /> (all constant terms are zero), and **non-homogeneous** if <img src="https://i.upmath.me/svg/(%20B%20%5Cneq%200%20)" alt="( B \neq 0 )" />.

---

## Methods to Solve Systems of Linear Equations

### 1. Cramer's Rule

Cramer's Rule is applicable when the coefficient matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is a square matrix, and <img src="https://i.upmath.me/svg/(%20%7CA%7C%20%5Cneq%200%20)" alt="( |A| \neq 0 )" />.

**Example:**
Solve the system of equations:

<img src="https://i.upmath.me/svg/%5B%0Ax%20%2B%202y%20%3D%205%0A%5D" alt="[
x + 2y = 5
]" />

<img src="https://i.upmath.me/svg/%5B%0A3x%20-%20y%20%3D%204%0A%5D" alt="[
3x - y = 4
]" />

**Solution:**

The system in matrix form is:

<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%0A1%20%26%202%20%0A%5C%5C%0A3%20%26%20-1%0A%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%0Ax%20%5C%5C%0Ay%0A%5Cend%7Bbmatrix%7D%3D%5Cbegin%7Bbmatrix%7D%0A5%20%0A%5C%5C%0A4%0A%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix}
1 &amp; 2 
\\
3 &amp; -1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}=\begin{bmatrix}
5 
\\
4
\end{bmatrix}
]" />

Using Cramer's Rule:

<img src="https://i.upmath.me/svg/%5B%0AD%20%3D%20%5Cbegin%7Bvmatrix%7D%201%20%26%202%20%5C%5C%203%20%26%20-1%20%5Cend%7Bvmatrix%7D%20%3D%201(-1)%20-%202(3)%20%3D%20-1%20-%206%20%3D%20-7%0A%5D" alt="[
D = \begin{vmatrix} 1 &amp; 2 \\ 3 &amp; -1 \end{vmatrix} = 1(-1) - 2(3) = -1 - 6 = -7
]" />

Now calculate <img src="https://i.upmath.me/svg/(%20D_x%20)" alt="( D_x )" /> and <img src="https://i.upmath.me/svg/(%20D_y%20)" alt="( D_y )" />:

<img src="https://i.upmath.me/svg/%5B%0AD_x%20%3D%20%5Cbegin%7Bvmatrix%7D%205%20%26%202%20%5C%5C%204%20%26%20-1%20%5Cend%7Bvmatrix%7D%20%3D%205(-1)%20-%202(4)%20%3D%20-5%20-%208%20%3D%20-13%0A%5D" alt="[
D_x = \begin{vmatrix} 5 &amp; 2 \\ 4 &amp; -1 \end{vmatrix} = 5(-1) - 2(4) = -5 - 8 = -13
]" />

<img src="https://i.upmath.me/svg/%5B%0AD_y%20%3D%20%5Cbegin%7Bvmatrix%7D%201%20%26%205%20%5C%5C%203%20%26%204%20%5Cend%7Bvmatrix%7D%20%3D%201(4)%20-%205(3)%20%3D%204%20-%2015%20%3D%20-11%0A%5D" alt="[
D_y = \begin{vmatrix} 1 &amp; 5 \\ 3 &amp; 4 \end{vmatrix} = 1(4) - 5(3) = 4 - 15 = -11
]" />

The solutions are:

<img src="https://i.upmath.me/svg/%5B%0Ax%20%3D%20%5Cfrac%7BD_x%7D%7BD%7D%20%3D%20%5Cfrac%7B-13%7D%7B-7%7D%20%3D%20%5Cfrac%7B13%7D%7B7%7D%0A%5D" alt="[
x = \frac{D_x}{D} = \frac{-13}{-7} = \frac{13}{7}
]" />

<img src="https://i.upmath.me/svg/%5B%0Ay%20%3D%20%5Cfrac%7BD_y%7D%7BD%7D%20%3D%20%5Cfrac%7B-11%7D%7B-7%7D%20%3D%20%5Cfrac%7B11%7D%7B7%7D%0A%5D" alt="[
y = \frac{D_y}{D} = \frac{-11}{-7} = \frac{11}{7}
]" />

---

### 2. Inverse Matrix Method

To solve <img src="https://i.upmath.me/svg/(%20AX%20%3D%20B%20)" alt="( AX = B )" /> using the inverse method, we compute <img src="https://i.upmath.me/svg/(%20X%20%3D%20A%5E%7B-1%7DB%20)" alt="( X = A^{-1}B )" />.

**Example:**
Solve the system of equations:

<img src="https://i.upmath.me/svg/%5B%0A2x%20%2B%203y%20%3D%208%0A%5D" alt="[
2x + 3y = 8
]" />

<img src="https://i.upmath.me/svg/%5B%0Ax%20-%20y%20%3D%202%0A%5D" alt="[
x - y = 2
]" />

**Solution:**

The matrix form is:

<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%0A2%20%26%203%20%5C%5C%0A1%20%26%20-1%0A%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%0Ax%20%5C%5C%0Ay%0A%5Cend%7Bbmatrix%7D%0A%3D%5Cbegin%7Bbmatrix%7D%0A8%20%5C%5C%0A2%0A%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix}
2 &amp; 3 \\
1 &amp; -1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
=\begin{bmatrix}
8 \\
2
\end{bmatrix}
]" />

Find the inverse of matrix $( A )$:

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bbmatrix%7D%202%20%26%203%20%5C%5C%201%20%26%20-1%20%5Cend%7Bbmatrix%7D%2C%20%5Cquad%20A%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B%5Ctext%7Bdet%7D(A)%7D%20%5Ctext%7Badj%7D(A)%0A%5D" alt="[
A = \begin{bmatrix} 2 &amp; 3 \\ 1 &amp; -1 \end{bmatrix}, \quad A^{-1} = \frac{1}{\text{det}(A)} \text{adj}(A)
]" />

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Bdet%7D(A)%20%3D%202(-1)%20-%203(1)%20%3D%20-2%20-%203%20%3D%20-5%0A%5D" alt="[
\text{det}(A) = 2(-1) - 3(1) = -2 - 3 = -5
]" />

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Badj%7D(A)%20%3D%20%5Cbegin%7Bbmatrix%7D%20-1%20%26%20-3%20%5C%5C%20-1%20%26%202%20%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\text{adj}(A) = \begin{bmatrix} -1 &amp; -3 \\ -1 &amp; 2 \end{bmatrix}
]" />

<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B-5%7D%20%5Cbegin%7Bbmatrix%7D%20-1%20%26%20-3%20%5C%5C%20-1%20%26%202%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B1%7D%7B5%7D%20%26%20%5Cfrac%7B3%7D%7B5%7D%20%5C%5C%20%5Cfrac%7B1%7D%7B5%7D%20%26%20%5Cfrac%7B-2%7D%7B5%7D%20%5Cend%7Bbmatrix%7D%0A%5D" alt="[
A^{-1} = \frac{1}{-5} \begin{bmatrix} -1 &amp; -3 \\ -1 &amp; 2 \end{bmatrix} = \begin{bmatrix} \frac{1}{5} &amp; \frac{3}{5} \\ \frac{1}{5} &amp; \frac{-2}{5} \end{bmatrix}
]" />

Now, multiply <img src="https://i.upmath.me/svg/(%20A%5E%7B-1%7D%20)" alt="( A^{-1} )" /> by <img src="https://i.upmath.me/svg/(%20B%20)" alt="( B )" />:

<img src="https://i.upmath.me/svg/%5B%0AX%20%3D%20A%5E%7B-1%7DB%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B1%7D%7B5%7D%20%26%20%5Cfrac%7B3%7D%7B5%7D%20%5C%5C%20%5Cfrac%7B1%7D%7B5%7D%20%26%20%5Cfrac%7B-2%7D%7B5%7D%20%5Cend%7Bbmatrix%7D%20%5Cbegin%7Bbmatrix%7D%208%20%5C%5C%202%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B8%7D%7B5%7D%20%2B%20%5Cfrac%7B6%7D%7B5%7D%20%5C%5C%20%5Cfrac%7B8%7D%7B5%7D%20-%20%5Cfrac%7B4%7D%7B5%7D%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B14%7D%7B5%7D%20%5C%5C%20%5Cfrac%7B4%7D%7B5%7D%20%5Cend%7Bbmatrix%7D%0A%5D" alt="[
X = A^{-1}B = \begin{bmatrix} \frac{1}{5} &amp; \frac{3}{5} \\ \frac{1}{5} &amp; \frac{-2}{5} \end{bmatrix} \begin{bmatrix} 8 \\ 2 \end{bmatrix} = \begin{bmatrix} \frac{8}{5} + \frac{6}{5} \\ \frac{8}{5} - \frac{4}{5} \end{bmatrix} = \begin{bmatrix} \frac{14}{5} \\ \frac{4}{5} \end{bmatrix}
]" />

Thus, <img src="https://i.upmath.me/svg/(%20x%20%3D%20%5Cfrac%7B14%7D%7B5%7D%20)" alt="( x = \frac{14}{5} )" />, and <img src="https://i.upmath.me/svg/(%20y%20%3D%20%5Cfrac%7B4%7D%7B5%7D%20)" alt="( y = \frac{4}{5} )" />.

---

### 3. Gauss-Jordan Method

In the Gauss-Jordan method, we transform the augmented matrix into reduced row echelon form.

**Example:**
Solve the system:

<img src="https://i.upmath.me/svg/%5B%0Ax%20%2B%202y%20%3D%205%0A%5D" alt="[
x + 2y = 5
]" />

<img src="https://i.upmath.me/svg/%5B%0A3x%20-%20y%20%3D%204%0A%5D" alt="[
3x - y = 4
]" />

**Solution:**

The augmented matrix is:

<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%0A1%20%26%202%20%26%20%7C%20%26%205%20%5C%5C%0A3%20%26%20-1%20%26%20%7C%20%26%204%0A%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix}
1 &amp; 2 &amp; | &amp; 5 \\
3 &amp; -1 &amp; | &amp; 4
\end{bmatrix}
]" />

Perform row operations to get the identity matrix on the left-hand side:

- <img src="https://i.upmath.me/svg/(%20R2%20%5Cleftarrow%20R2%20-%203R1%20)" alt="( R2 \leftarrow R2 - 3R1 )" /> 
: 

<img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%26%20%7C%20%26%205%20%5C%5C%200%20%26%20-7%20%26%20%7C%20%26%20-11%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} 1 &amp; 2 &amp; | &amp; 5 \\ 0 &amp; -7 &amp; | &amp; -11 \end{bmatrix} )" />

- <img src="https://i.upmath.me/svg/(%20R2%20%5Cleftarrow%20R2%20%2F%20-7%20)" alt="( R2 \leftarrow R2 / -7 )" /> 
: 

<img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%26%20%7C%20%26%205%20%5C%5C%200%20%26%201%20%26%20%7C%20%26%20%5Cfrac%7B11%7D%7B7%7D%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} 1 &amp; 2 &amp; | &amp; 5 \\ 0 &amp; 1 &amp; | &amp; \frac{11}{7} \end{bmatrix} )" />

- <img src="https://i.upmath.me/svg/(%20R1%20%5Cleftarrow%20R1%20-%202R2%20)" alt="( R1 \leftarrow R1 - 2R2 )" />

:

 <img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%201%20%26%200%20%26%20%7C%20%26%20%5Cfrac%7B13%7D%7B7%7D%20%5C%5C%200%20%26%201%20%26%20%7C%20%26%20%5Cfrac%7B11%7D%7B7%7D%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} 1 &amp; 0 &amp; | &amp; \frac{13}{7} \\ 0 &amp; 1 &amp; | &amp; \frac{11}{7} \end{bmatrix} )" />

Thus, <img src="https://i.upmath.me/svg/(%20x%20%3D%20%5Cfrac%7B13%7D%7B7%7D%20)" alt="( x = \frac{13}{7} )" />, and <img src="https://i.upmath.me/svg/(%20y%20%3D%20%5Cfrac%7B11%7D%7B7%7D%20)" alt="( y = \frac{11}{7} )" />.

---

### 4. Gauss Elimination Method

In this method, we reduce the system to an upper triangular matrix and then perform back substitution.

**Example:**
Solve the system:

<img src="https://i.upmath.me/svg/%5B%0A2x%20%2B%203y%20%3D%208%0A%5D" alt="[
2x + 3y = 8
]" />

<img src="https://i.upmath.me/svg/%5B%0Ax%20-%20y%20%3D%202%0A%5D" alt="[
x - y = 2
]" />

**Solution:**

Step 1: Create the augmented matrix:

<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%0A2%20%26%203%20%26%20%7C%20%26%208%20%5C%5C%0A1%20%26%20-1%20%26%20%7C%20%26%202%0A%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix}
2 &amp; 3 &amp; | &amp; 8 \\
1 &amp; -1 &amp; | &amp; 2
\end{bmatrix}
]" />

**Step 2: Eliminate <img src="https://i.upmath.me/svg/(%20x%20)" alt="( x )" /> from the second equation:**

- <img src="https://i.upmath.me/svg/(%20R2%20%5Cleftarrow%20R2%20-%20%5Cfrac%7B1%7D%7B2%7DR1%20)" alt="( R2 \leftarrow R2 - \frac{1}{2}R1 )" />


<img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%202%20%26%203%20%26%20%7C%20%26%208%20%5C%5C%200%20%26%20-%5Cfrac%7B5%7D%7B2%7D%20%26%20%7C%20%26%20-2%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} 2 &amp; 3 &amp; | &amp; 8 \\ 0 &amp; -\frac{5}{2} &amp; | &amp; -2 \end{bmatrix} )" />

**Step 3: Solve by back substitution:**

- From the second equation: 

<img src="https://i.upmath.me/svg/(%20y%20%3D%20%5Cfrac%7B4%7D%7B5%7D%20)" alt="( y = \frac{4}{5} )" />
- Substitute <img src="https://i.upmath.me/svg/(%20y%20)" alt="( y )" /> into the first equation: <img src="https://i.upmath.me/svg/(%20x%20%3D%20%5Cfrac%7B14%7D%7B5%7D%20)" alt="( x = \frac{14}{5} )" />

---

#### **5. LU Decomposition**

In LU Decomposition, we decompose the coefficient matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> into a product of a lower triangular matrix <img src="https://i.upmath.me/svg/(%20L%20)" alt="( L )" /> and an upper triangular matrix <img src="https://i.upmath.me/svg/(%20U%20)" alt="( U )" />.

**Example:**
Solve the system:

<img src="https://i.upmath.me/svg/%5B%0Ax%20%2B%202y%20%3D%205%0A%5D" alt="[
x + 2y = 5
]" />

<img src="https://i.upmath.me/svg/%5B%0Ax%20%3D%20%5Cfrac%7B13%7D%7B7%7D%2C%20%5Cquad%20y%20%3D%20%5Cfrac%7B11%7D%7B7%7D%0A%5D" alt="[
x = \frac{13}{7}, \quad y = \frac{11}{7}
]" />

<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5C%5C%203%20%26%20-1%20%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%20x%20%5C%5C%20y%20%5Cend%7Bbmatrix%7D%0A%3D%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%204%20%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix} 1 &amp; 2 \\ 3 &amp; -1 \end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix}
=\begin{bmatrix} 5 \\ 4 \end{bmatrix}
]" />

**Step 1: Write the system in matrix form**

The system of equations can be represented as:

<img src="https://i.upmath.me/svg/%5B%5Cbegin%7Bbmatrix%7D%0A1%20%26%202%20%5C%5C%0A3%20%26%20-1%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%0Ax%20%5C%5C%20y%5Cend%7Bbmatrix%7D%0A%3D%20%5Cbegin%7Bbmatrix%7D5%20%5C%5C%204%5Cend%7Bbmatrix%7D%5D" alt="[\begin{bmatrix}
1 &amp; 2 \\
3 &amp; -1\end{bmatrix}
\begin{bmatrix}
x \\ y\end{bmatrix}
= \begin{bmatrix}5 \\ 4\end{bmatrix}]" />

Let:

- <img src="https://i.upmath.me/svg/(%20A%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5C%5C%203%20%26%20-1%20%5Cend%7Bbmatrix%7D%20)" alt="( A = \begin{bmatrix} 1 &amp; 2 \\ 3 &amp; -1 \end{bmatrix} )" /> 

(Coefficient matrix)

- <img src="https://i.upmath.me/svg/(%20B%20%3D%20%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%204%20%5Cend%7Bbmatrix%7D%20)" alt="( B = \begin{bmatrix} 5 \\ 4 \end{bmatrix} )" />

(Constant matrix)

**Step 2: Perform LU Decomposition**

We decompose <img src="https://i.upmath.me/svg/(A)" alt="(A)" /> into the product of a lower triangular matrix <img src="https://i.upmath.me/svg/(L)" alt="(L)" /> and an upper triangular matrix <img src="https://i.upmath.me/svg/(U)" alt="(U)" />.

Let:
<img src="https://i.upmath.me/svg/(%20A%20%3D%20LU%20)" alt="( A = LU )" />

Where:

- <img src="https://i.upmath.me/svg/(L)" alt="(L)" /> is a lower triangular matrix of the form 

<img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%201%20%26%200%20%5C%5C%20l_%7B21%7D%20%26%201%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} 1 &amp; 0 \\ l_{21} &amp; 1 \end{bmatrix} )" />


- <img src="https://i.upmath.me/svg/(U)" alt="(U)" /> is an upper triangular matrix of the form 

<img src="https://i.upmath.me/svg/(%20%5Cbegin%7Bbmatrix%7D%20u_%7B11%7D%20%26%20u_%7B12%7D%20%5C%5C%200%20%26%20u_%7B22%7D%20%5Cend%7Bbmatrix%7D%20)" alt="( \begin{bmatrix} u_{11} &amp; u_{12} \\ 0 &amp; u_{22} \end{bmatrix} )" /> 



**Compute <img src="https://i.upmath.me/svg/(L)" alt="(L)" /> and <img src="https://i.upmath.me/svg/(U)" alt="(U)" />**

We perform row operations on $(A)$ to make it upper triangular:

- Start with 

<img src="https://i.upmath.me/svg/(%20A%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5C%5C%203%20%26%20-1%20%5Cend%7Bbmatrix%7D%20)" alt="( A = \begin{bmatrix} 1 &amp; 2 \\ 3 &amp; -1 \end{bmatrix} )" />

- Perform the row operation <img src="https://i.upmath.me/svg/(%20R_2%20%5Cleftarrow%20R_2%203R_1%20)" alt="( R_2 \leftarrow R_2 3R_1 )" />


<img src="https://i.upmath.me/svg/(%20R_2%20%3D%20%5Cbegin%7Bbmatrix%7D%203%20%26%20-1%20%5Cend%7Bbmatrix%7D%20-%203%20%5Ctimes%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%200%20%26%20-7%20%5Cend%7Bbmatrix%7D%20)" alt="( R_2 = \begin{bmatrix} 3 &amp; -1 \end{bmatrix} - 3 \times \begin{bmatrix} 1 &amp; 2 \end{bmatrix} = \begin{bmatrix} 0 &amp; -7 \end{bmatrix} )" />


Thus:

- <img src="https://i.upmath.me/svg/(%20U%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5C%5C%200%20%26%20-7%20%5Cend%7Bbmatrix%7D%20)" alt="( U = \begin{bmatrix} 1 &amp; 2 \\ 0 &amp; -7 \end{bmatrix} )" />

- <img src="https://i.upmath.me/svg/(%20L%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%200%20%5C%5C%203%20%26%201%20%5Cend%7Bbmatrix%7D%20)" alt="( L = \begin{bmatrix} 1 &amp; 0 \\ 3 &amp; 1 \end{bmatrix} )" />

**Step 3: Solve <img src="https://i.upmath.me/svg/(LY%20%3D%20B)" alt="(LY = B)" />**

Now, solve the system <img src="https://i.upmath.me/svg/(LY%20%3D%20B)" alt="(LY = B)" />, where 

<img src="https://i.upmath.me/svg/(%20Y%20%3D%20%5Cbegin%7Bbmatrix%7D%20y_1%20%5C%5C%20y_2%20%5Cend%7Bbmatrix%7D%20)" alt="( Y = \begin{bmatrix} y_1 \\ y_2 \end{bmatrix} )" />


<img src="https://i.upmath.me/svg/%5B%0A%5Cbegin%7Bbmatrix%7D%201%20%26%200%20%5C%5C%203%20%26%201%20%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%20y_1%20%5C%5C%20y_2%20%5Cend%7Bbmatrix%7D%0A%3D%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%204%20%5Cend%7Bbmatrix%7D%0A%5D" alt="[
\begin{bmatrix} 1 &amp; 0 \\ 3 &amp; 1 \end{bmatrix}
\begin{bmatrix} y_1 \\ y_2 \end{bmatrix}
=\begin{bmatrix} 5 \\ 4 \end{bmatrix}
]" />

From the first row:

<img src="https://i.upmath.me/svg/(y_1%20%3D%205)" alt="(y_1 = 5)" />

Substitute <img src="https://i.upmath.me/svg/(y_1%20%3D%205)" alt="(y_1 = 5)" /> into the second row equation:

<img src="https://i.upmath.me/svg/(3(5)%20%2B%20y_2%20%3D%204%20%5Cquad%20%5CRightarrow%20%5Cquad%20y_2%20%3D%204%20-%2015%20%3D%20-11)" alt="(3(5) + y_2 = 4 \quad \Rightarrow \quad y_2 = 4 - 15 = -11)" />

Thus:

<img src="https://i.upmath.me/svg/(Y%20%3D%20%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%20-11%20%5Cend%7Bbmatrix%7D)" alt="(Y = \begin{bmatrix} 5 \\ -11 \end{bmatrix})" />

**Step 4: Solve <img src="https://i.upmath.me/svg/(UX%20%3D%20Y)" alt="(UX = Y)" />**

Next, solve <img src="https://i.upmath.me/svg/(UX%20%3D%20Y)" alt="(UX = Y)" />, where

<img src="https://i.upmath.me/svg/(%20X%20%3D%20%5Cbegin%7Bbmatrix%7D%20x%20%5C%5C%20y%20%5Cend%7Bbmatrix%7D%20)" alt="( X = \begin{bmatrix} x \\ y \end{bmatrix} )" /> 



<img src="https://i.upmath.me/svg/%5B%0A(%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%5C%5C%200%20%26%20-7%20%5Cend%7Bbmatrix%7D%0A%5Cbegin%7Bbmatrix%7D%20x%20%5C%5C%20y%20%5Cend%7Bbmatrix%7D%3D%5Cbegin%7Bbmatrix%7D%205%20%5C%5C%20-11%20%5Cend%7Bbmatrix%7D)%0A%5D" alt="[
(\begin{bmatrix} 1 &amp; 2 \\ 0 &amp; -7 \end{bmatrix}
\begin{bmatrix} x \\ y \end{bmatrix}=\begin{bmatrix} 5 \\ -11 \end{bmatrix})
]" />


From the second row:

<img src="https://i.upmath.me/svg/(-7y%20%3D%20-11%20%5Cquad%20%5CRightarrow%20%5Cquad%20y%20%3D%20%5Cfrac%7B11%7D%7B7%7D)" alt="(-7y = -11 \quad \Rightarrow \quad y = \frac{11}{7})" />