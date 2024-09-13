
# Matrices and Matrix Operations

## Matrices
A matrix is a collection of numbers or symbols arranged into a rectangular grid with rows and columns. Each entry in a matrix is known as an element, and it is uniquely identified by its row and column.

A matrix with **m** rows and **n** columns is called an **m×n matrix**.
An element of a matrix **A**, located at the i-th row and j-th column, is denoted as **a_ij**.

### Example: A 3×3 Matrix

$$[
A = \begin{pmatrix} 
a_{11} & a_{12} & a_{13} \\ 
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}
]$$

This matrix has 3 rows and 3 columns, and each **a_ij** represents an element of the matrix.

---

## Matrix Operations

### 1. Matrix Addition
Two matrices of the same dimension can be added by adding their corresponding elements.

$[
C = A + B
]$

where $( C_{ij} = A_{ij} + B_{ij} )$.

**Example:**

$$[
A = \begin{pmatrix} 
1 & 2 \\ 
3 & 4
\end{pmatrix}
\quad \text{and} \quad
B = \begin{pmatrix} 
5 & 6 \\ 
7 & 8
\end{pmatrix}
]$$

$$[
A + B = \begin{pmatrix} 
1 + 5 & 2 + 6 \\
3 + 7 & 4 + 8
\end{pmatrix} = \begin{pmatrix}
6 & 8 \\
10 & 12
\end{pmatrix}
]$$
### 2. Matrix Subtraction
Matrix subtraction involves subtracting corresponding elements of two matrices of the same dimension.

$[
D = A - B
]$

where $( D_{ij} = A_{ij} - B_{ij} )$.

**Example:**

$$[
A - B = \begin{pmatrix} 
1 - 5 & 2 - 6 \\
3 - 7 & 4 - 8
\end{pmatrix} = \begin{pmatrix} 
-4 & -4 \\
-4 & -4
\end{pmatrix}
]$$

### 3. Scalar Multiplication
Each element of a matrix can be multiplied by a scalar (a single number).

$$[
B = c \cdot A
]$$

where $( B_{ij} = c \cdot A_{ij} )$, and **c** is the scalar.

**Example:**

$$[
2 \cdot A = 2 \cdot \begin{pmatrix} 
1 & 2 \\ 
3 & 4
\end{pmatrix} = \begin{pmatrix} 
2 \cdot 1 & 2 \cdot 2 \\ 
2 \cdot 3 & 2 \cdot 4
\end{pmatrix} = \begin{pmatrix} 
2 & 4 \\ 
6 & 8
\end{pmatrix}
]$$

### 4. Matrix Multiplication
Matrix multiplication is more complex than element-wise operations. If **A** is an **m×n matrix** and **B** is an **n×p matrix**, the product **C = A × B** will be an **m×p matrix** where each element is calculated as:

$$[
C_{ij} = \sum_{k=1}^{n} A_{ik} \cdot B_{kj}
]$$

**Example:**

$$[
A = \begin{pmatrix} 
1 & 2 \\ 
3 & 4
\end{pmatrix}
, \quad
B = \begin{pmatrix} 
5 & 6 \\ 
7 & 8
\end{pmatrix}
]$$

$$[
C = A \times B = \begin{pmatrix} 
(1 \times 5 + 2 \times 7) & (1 \times 6 + 2 \times 8) \\
(3 \times 5 + 4 \times 7) & (3 \times 6 + 4 \times 8)
\end{pmatrix}
]$$

$$[
C = \begin{pmatrix} 
19 & 22 \\ 
43 & 50
\end{pmatrix}
]$$

### 5. Transpose of a Matrix
The transpose of a matrix **A**, denoted as **A^T**, is formed by swapping the rows and columns.

**Example:**

$$[
A = \begin{pmatrix} 
1 & 2 \\ 
3 & 4
\end{pmatrix}
, \quad A^T = \begin{pmatrix} 
1 & 3 \\ 
2 & 4
\end{pmatrix}
]$$

### 6. Determinant of a Matrix
The determinant is a scalar value that can be computed from a square matrix and offers important information, such as whether the matrix is invertible. For a **2×2 matrix**:

$$[
\text{det}(A) = a_{11} \cdot a_{22} - a_{12} \cdot a_{21}
]$$

**Example:**

$$[
A = \begin{pmatrix} 
1 & 2 \\ 
3 & 4
\end{pmatrix}
\quad \text{det}(A) = (1 \times 4) - (2 \times 3) = 4 - 6 = -2
]$$

### 7. Inverse of a Matrix
The inverse of a square matrix **A**, denoted **A^{-1}**, is such that **A ⋅ A^{-1} = I**, where **I** is the identity matrix. A matrix must be square and have a non-zero determinant to have an inverse.

**Example:**

The inverse of a **2×2 matrix** is computed using the formula:

$$[
A^{-1} = \frac{1}{\text{det}(A)} \cdot \begin{pmatrix} 
a_{22} & -a_{12} \\ 
-a_{21} & a_{11}
\end{pmatrix}
]$$

For 

$$[A = \begin{pmatrix} 1 & 2 \\ 3 & 4\end{pmatrix}]$$
 , we already computed $( \text{det}(A) = -2 )$, so:

$$[
A^{-1} = \frac{1}{-2} \cdot \begin{pmatrix} 
4 & -2 \\ 
-3 & 1
\end{pmatrix} = \begin{pmatrix} 
-2 & 1 \\ 
1.5 & -0.5
\end{pmatrix}
]$$

This is the inverse of matrix **A**.


