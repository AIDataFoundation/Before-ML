# Matrices and Matrix Operations

## Matrices
A matrix is a collection of numbers or symbols arranged into a rectangular grid with rows and columns. Each entry in a matrix is known as an element, and it is uniquely identified by its row and column.

A matrix with **m** rows and **n** columns is called an **m×n matrix**.
An element of a matrix **A**, located at the i-th row and j-th column, is denoted as **a_ij**.

### Example: A 3×3 Matrix

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0Aa_%7B11%7D%20%26%20a_%7B12%7D%20%26%20a_%7B13%7D%20%5C%5C%20%0Aa_%7B21%7D%20%26%20a_%7B22%7D%20%26%20a_%7B23%7D%20%5C%5C%0Aa_%7B31%7D%20%26%20a_%7B32%7D%20%26%20a_%7B33%7D%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix} 
a_{11} &amp; a_{12} &amp; a_{13} \\ 
a_{21} &amp; a_{22} &amp; a_{23} \\
a_{31} &amp; a_{32} &amp; a_{33}
\end{pmatrix}
]" />

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

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%20%0A3%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5Cquad%20%5Ctext%7Band%7D%20%5Cquad%0AB%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A5%20%26%206%20%5C%5C%20%0A7%20%26%208%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix} 
1 &amp; 2 \\ 
3 &amp; 4
\end{pmatrix}
\quad \text{and} \quad
B = \begin{pmatrix} 
5 &amp; 6 \\ 
7 &amp; 8
\end{pmatrix}
]" />

<img src="https://i.upmath.me/svg/%5B%0AA%20%2B%20B%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%2B%205%20%26%202%20%2B%206%20%5C%5C%0A3%20%2B%207%20%26%204%20%2B%208%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%0A6%20%26%208%20%5C%5C%0A10%20%26%2012%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A + B = \begin{pmatrix} 
1 + 5 &amp; 2 + 6 \\
3 + 7 &amp; 4 + 8
\end{pmatrix} = \begin{pmatrix}
6 &amp; 8 \\
10 &amp; 12
\end{pmatrix}
]" />
### 2. Matrix Subtraction
Matrix subtraction involves subtracting corresponding elements of two matrices of the same dimension.

$[
D = A - B
]$

where $( D_{ij} = A_{ij} - B_{ij} )$.

**Example:**

<img src="https://i.upmath.me/svg/%5B%0AA%20-%20B%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20-%205%20%26%202%20-%206%20%5C%5C%0A3%20-%207%20%26%204%20-%208%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A-4%20%26%20-4%20%5C%5C%0A-4%20%26%20-4%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A - B = \begin{pmatrix} 
1 - 5 &amp; 2 - 6 \\
3 - 7 &amp; 4 - 8
\end{pmatrix} = \begin{pmatrix} 
-4 &amp; -4 \\
-4 &amp; -4
\end{pmatrix}
]" />

### 3. Scalar Multiplication
Each element of a matrix can be multiplied by a scalar (a single number).

<img src="https://i.upmath.me/svg/%5B%0AB%20%3D%20c%20%5Ccdot%20A%0A%5D" alt="[
B = c \cdot A
]" />

where $( B_{ij} = c \cdot A_{ij} )$, and **c** is the scalar.

**Example:**

<img src="https://i.upmath.me/svg/%5B%0A2%20%5Ccdot%20A%20%3D%202%20%5Ccdot%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%20%0A3%20%26%204%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A2%20%5Ccdot%201%20%26%202%20%5Ccdot%202%20%5C%5C%20%0A2%20%5Ccdot%203%20%26%202%20%5Ccdot%204%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A2%20%26%204%20%5C%5C%20%0A6%20%26%208%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
2 \cdot A = 2 \cdot \begin{pmatrix} 
1 &amp; 2 \\ 
3 &amp; 4
\end{pmatrix} = \begin{pmatrix} 
2 \cdot 1 &amp; 2 \cdot 2 \\ 
2 \cdot 3 &amp; 2 \cdot 4
\end{pmatrix} = \begin{pmatrix} 
2 &amp; 4 \\ 
6 &amp; 8
\end{pmatrix}
]" />

### 4. Matrix Multiplication
Matrix multiplication is more complex than element-wise operations. If **A** is an **m×n matrix** and **B** is an **n×p matrix**, the product **C = A × B** will be an **m×p matrix** where each element is calculated as:

<img src="https://i.upmath.me/svg/%5B%0AC_%7Bij%7D%20%3D%20%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%20A_%7Bik%7D%20%5Ccdot%20B_%7Bkj%7D%0A%5D" alt="[
C_{ij} = \sum_{k=1}^{n} A_{ik} \cdot B_{kj}
]" />

**Example:**

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%20%0A3%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%2C%20%5Cquad%0AB%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A5%20%26%206%20%5C%5C%20%0A7%20%26%208%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix} 
1 &amp; 2 \\ 
3 &amp; 4
\end{pmatrix}
, \quad
B = \begin{pmatrix} 
5 &amp; 6 \\ 
7 &amp; 8
\end{pmatrix}
]" />

<img src="https://i.upmath.me/svg/%5B%0AC%20%3D%20A%20%5Ctimes%20B%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A(1%20%5Ctimes%205%20%2B%202%20%5Ctimes%207)%20%26%20(1%20%5Ctimes%206%20%2B%202%20%5Ctimes%208)%20%5C%5C%0A(3%20%5Ctimes%205%20%2B%204%20%5Ctimes%207)%20%26%20(3%20%5Ctimes%206%20%2B%204%20%5Ctimes%208)%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
C = A \times B = \begin{pmatrix} 
(1 \times 5 + 2 \times 7) &amp; (1 \times 6 + 2 \times 8) \\
(3 \times 5 + 4 \times 7) &amp; (3 \times 6 + 4 \times 8)
\end{pmatrix}
]" />

<img src="https://i.upmath.me/svg/%5B%0AC%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A19%20%26%2022%20%5C%5C%20%0A43%20%26%2050%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
C = \begin{pmatrix} 
19 &amp; 22 \\ 
43 &amp; 50
\end{pmatrix}
]" />

### 5. Transpose of a Matrix
The transpose of a matrix **A**, denoted as **A^T**, is formed by swapping the rows and columns.

**Example:**

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%20%0A3%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%2C%20%5Cquad%20A%5ET%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%203%20%5C%5C%20%0A2%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix} 
1 &amp; 2 \\ 
3 &amp; 4
\end{pmatrix}
, \quad A^T = \begin{pmatrix} 
1 &amp; 3 \\ 
2 &amp; 4
\end{pmatrix}
]" />

### 6. Determinant of a Matrix
The determinant is a scalar value that can be computed from a square matrix and offers important information, such as whether the matrix is invertible. For a **2×2 matrix**:

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Bdet%7D(A)%20%3D%20a_%7B11%7D%20%5Ccdot%20a_%7B22%7D%20-%20a_%7B12%7D%20%5Ccdot%20a_%7B21%7D%0A%5D" alt="[
\text{det}(A) = a_{11} \cdot a_{22} - a_{12} \cdot a_{21}
]" />

**Example:**

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%20%0A3%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5Cquad%20%5Ctext%7Bdet%7D(A)%20%3D%20(1%20%5Ctimes%204)%20-%20(2%20%5Ctimes%203)%20%3D%204%20-%206%20%3D%20-2%0A%5D" alt="[
A = \begin{pmatrix} 
1 &amp; 2 \\ 
3 &amp; 4
\end{pmatrix}
\quad \text{det}(A) = (1 \times 4) - (2 \times 3) = 4 - 6 = -2
]" />

### 7. Inverse of a Matrix
The inverse of a square matrix **A**, denoted **$A^{-1}$**, is such that **$A ⋅ A^{-1} = I$**, where **I** is the identity matrix. A matrix must be square and have a non-zero determinant to have an inverse.

**Example:**

The inverse of a **2×2 matrix** is computed using the formula:

<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B%5Ctext%7Bdet%7D(A)%7D%20%5Ccdot%20%5Cbegin%7Bpmatrix%7D%20%0Aa_%7B22%7D%20%26%20-a_%7B12%7D%20%5C%5C%20%0A-a_%7B21%7D%20%26%20a_%7B11%7D%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A^{-1} = \frac{1}{\text{det}(A)} \cdot \begin{pmatrix} 
a_{22} &amp; -a_{12} \\ 
-a_{21} &amp; a_{11}
\end{pmatrix}
]" />

For

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A1%20%26%202%20%5C%5C%0A3%20%26%204%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix} 
1 &amp; 2 \\
3 &amp; 4\end{pmatrix}
]" />

,we already computed $(det(A)=-2)$.

<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B-2%7D%20%5Ccdot%20%5Cbegin%7Bpmatrix%7D%20%0A4%20%26%20-2%20%5C%5C%20%0A-3%20%26%201%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%20%0A-2%20%26%201%20%5C%5C%20%0A1.5%20%26%20-0.5%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A^{-1} = \frac{1}{-2} \cdot \begin{pmatrix} 
4 &amp; -2 \\ 
-3 &amp; 1
\end{pmatrix} = \begin{pmatrix} 
-2 &amp; 1 \\ 
1.5 &amp; -0.5
\end{pmatrix}
]" />

This is the inverse of matrix **A**.

