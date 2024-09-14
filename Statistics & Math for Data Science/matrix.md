# Matrices 

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
## Types of Matrices
- **Row Matrix**: A matrix with a single row.
  <img src="https://i.upmath.me/svg/%5B%0A%20%20R%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%20%20r_1%20%26%20r_2%20%26%20r_3%0A%20%20%5Cend%7Bpmatrix%7D%0A%20%20%5D" alt="[
  R = \begin{pmatrix}
  r_1 &amp; r_2 &amp; r_3
  \end{pmatrix}
  ]" />
- **Column Matrix**: A matrix with a single column.
  <img src="https://i.upmath.me/svg/%5B%0A%20%20C%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%20%20c_1%20%5C%5C%0A%20%20c_2%20%5C%5C%0A%20%20c_3%0A%20%20%5Cend%7Bpmatrix%7D%0A%20%20%5D" alt="[
  C = \begin{pmatrix}
  c_1 \\
  c_2 \\
  c_3
  \end{pmatrix}
  ]" />
- **Square Matrix**: A matrix with the same number of rows and columns.
  <img src="https://i.upmath.me/svg/%5B%0A%20%20S%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%20%20s_%7B11%7D%20%26%20s_%7B12%7D%20%5C%5C%0A%20%20s_%7B21%7D%20%26%20s_%7B22%7D%0A%20%20%5Cend%7Bpmatrix%7D%0A%20%20%5D" alt="[
  S = \begin{pmatrix}
  s_{11} &amp; s_{12} \\
  s_{21} &amp; s_{22}
  \end{pmatrix}
  ]" />
- **Zero Matrix**: A matrix in which all elements are zero.
  <img src="https://i.upmath.me/svg/%5B%0A%20%20Z%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%20%200%20%26%200%20%5C%5C%0A%20%200%20%26%200%0A%20%20%5Cend%7Bpmatrix%7D%0A%20%20%5D" alt="[
  Z = \begin{pmatrix}
  0 &amp; 0 \\
  0 &amp; 0
  \end{pmatrix}
  ]" />
- **Identity Matrix**: A square matrix with ones on the diagonal and zeros elsewhere.
  <img src="https://i.upmath.me/svg/%5B%0A%20%20I%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%20%201%20%26%200%20%5C%5C%0A%20%200%20%26%201%0A%20%20%5Cend%7Bpmatrix%7D%0A%20%20%5D" alt="[
  I = \begin{pmatrix}
  1 &amp; 0 \\
  0 &amp; 1
  \end{pmatrix}
  ]" />

---

## Matrix Operations

###  Matrix Addition
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

**Properties of Matrix Addition and Multiplication**

Properties followed by Multiplication and Addition of Matrices is listed below:

<img src="https://i.upmath.me/svg/(A%20%2B%20B%20%3D%20B%20%2B%20A)" alt="(A + B = B + A)" /> (Commutative)

<img src="https://i.upmath.me/svg/((A%20%2B%20B)%20%2B%20C%20%3D%20A%20%2B%20(B%20%2B%20C))" alt="((A + B) + C = A + (B + C))" /> (Associative)

<img src="https://i.upmath.me/svg/(AB%20%E2%89%A0%20BA)" alt="(AB ≠ BA)" /> 
(Not Commutative)

<img src="https://i.upmath.me/svg/((AB)%20C%20%3D%20A%20(BC))" alt="((AB) C = A (BC))" /> (Associative)

<img src="https://i.upmath.me/svg/(A%20(B%2BC)%20%3D%20AB%20%2B%20AC)" alt="(A (B+C) = AB + AC)" /> (Distributive)

###  Matrix Subtraction
Matrix subtraction involves subtracting corresponding elements of two matrices of the same dimension.

<img src="https://i.upmath.me/svg/%5B%0AD%20%3D%20A%20-%20B%0A%5D" alt="[
D = A - B
]" />

where 
<img src="https://i.upmath.me/svg/(%20D_%7Bij%7D%20%3D%20A_%7Bij%7D%20-%20B_%7Bij%7D%20)" alt="( D_{ij} = A_{ij} - B_{ij} )" /> 

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

### Scalar Multiplication
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

###  Matrix Multiplication
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

###  Transpose of a Matrix
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

**Properties of the Transpose of a Matrix**

Properties of the transpose of a matrix are mentioned below:

<img src="https://i.upmath.me/svg/(A%5ET)%5ET%20%3D%20A)" alt="(A^T)^T = A)" />
<img src="https://i.upmath.me/svg/((A%2BB)%5ET%20%3D%20A%5ET%20%2B%20B%5ET)" alt="((A+B)^T = A^T + B^T)" />
<img src="https://i.upmath.me/svg/((AB)%5ET%20%3D%20B%5ET%20A%5ET)" alt="((AB)^T = B^T A^T)" />


### Determinant of a Matrix
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

### Cofactor

The cofactor of an element in a matrix is a signed minor. The minor of an element is the determinant of the submatrix that remains after removing the row and column of that element. The sign of the cofactor depends on the position of the element in the matrix.

The cofactor <img src="https://i.upmath.me/svg/(%20C_%7Bij%7D%20)" alt="( C_{ij} )" /> of an element <img src="https://i.upmath.me/svg/(%20a_%7Bij%7D%20)" alt="( a_{ij} )" /> in a matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is given by:
<img src="https://i.upmath.me/svg/%5B%0AC_%7Bij%7D%20%3D%20(-1)%5E%7Bi%2Bj%7D%20M_%7Bij%7D%0A%5D" alt="[
C_{ij} = (-1)^{i+j} M_{ij}
]" />
where <img src="https://i.upmath.me/svg/(%20M_%7Bij%7D%20)" alt="( M_{ij} )" /> is the minor of the element <img src="https://i.upmath.me/svg/(%20a_%7Bij%7D%20)" alt="( a_{ij} )" /> .


**Cofactor Matrix**

The cofactor matrix of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is a matrix where each element is the cofactor of the corresponding element in <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />.

For the matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />:

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%0A1%20%26%202%20%26%203%20%5C%5C%0A0%20%26%204%20%26%205%20%5C%5C%0A1%20%26%200%20%26%206%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix}
1 &amp; 2 &amp; 3 \\
0 &amp; 4 &amp; 5 \\
1 &amp; 0 &amp; 6
\end{pmatrix}
]" />

The cofactor matrix \( C \) is:

<img src="https://i.upmath.me/svg/%5B%0AC%20%3D%20%5Cbegin%7Bpmatrix%7D%0AC_%7B11%7D%20%26%20C_%7B12%7D%20%26%20C_%7B13%7D%20%5C%5C%0AC_%7B21%7D%20%26%20C_%7B22%7D%20%26%20C_%7B23%7D%20%5C%5C%0AC_%7B31%7D%20%26%20C_%7B32%7D%20%26%20C_%7B33%7D%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
C = \begin{pmatrix}
C_{11} &amp; C_{12} &amp; C_{13} \\
C_{21} &amp; C_{22} &amp; C_{23} \\
C_{31} &amp; C_{32} &amp; C_{33}
\end{pmatrix}
]" />

Where each <img src="https://i.upmath.me/svg/(%20C_%7Bij%7D%20)" alt="( C_{ij} )" /> is the cofactor of the element <img src="https://i.upmath.me/svg/(%20a_%7Bij%7D%20)" alt="( a_{ij} )" />.

**Example of Cofactor Matrix Calculation**

Let's calculate the cofactor matrix for <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />:

1. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B11%7D%20)" alt="( C_{11} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B11%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%204%20%26%205%20%5C%5C%0A%20%20%200%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(4%20%5Ccdot%206)%20-%20(5%20%5Ccdot%200)%20%3D%2024%0A%20%20%20%5D" alt="[
   M_{11} = \begin{vmatrix}
   4 &amp; 5 \\
   0 &amp; 6
   \end{vmatrix} = (4 \cdot 6) - (5 \cdot 0) = 24
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B11%7D%20%3D%20(-1)%5E%7B1%2B1%7D%20%5Ccdot%2024%20%3D%2024%0A%20%20%20%5D" alt="[
   C_{11} = (-1)^{1+1} \cdot 24 = 24
   ]" />

2. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B12%7D%20)" alt="( C_{12} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B12%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%200%20%26%205%20%5C%5C%0A%20%20%201%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(0%20%5Ccdot%206)%20-%20(5%20%5Ccdot%201)%20%3D%20-5%0A%20%20%20%5D" alt="[
   M_{12} = \begin{vmatrix}
   0 &amp; 5 \\
   1 &amp; 6
   \end{vmatrix} = (0 \cdot 6) - (5 \cdot 1) = -5
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B12%7D%20%3D%20(-1)%5E%7B1%2B2%7D%20%5Ccdot%20(-5)%20%3D%205%0A%20%20%20%5D" alt="[
   C_{12} = (-1)^{1+2} \cdot (-5) = 5
   ]" />

3. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B13%7D%20)" alt="( C_{13} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B13%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%200%20%26%204%20%5C%5C%0A%20%20%201%20%26%200%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(0%20%5Ccdot%200)%20-%20(4%20%5Ccdot%201)%20%3D%20-4%0A%20%20%20%5D" alt="[
   M_{13} = \begin{vmatrix}
   0 &amp; 4 \\
   1 &amp; 0
   \end{vmatrix} = (0 \cdot 0) - (4 \cdot 1) = -4
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B13%7D%20%3D%20(-1)%5E%7B1%2B3%7D%20%5Ccdot%20(-4)%20%3D%20-4%0A%20%20%20%5D" alt="[
   C_{13} = (-1)^{1+3} \cdot (-4) = -4
   ]" />

4. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B21%7D%20)" alt="( C_{21} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B21%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%202%20%26%203%20%5C%5C%0A%20%20%200%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(2%20%5Ccdot%206)%20-%20(3%20%5Ccdot%200)%20%3D%2012%0A%20%20%20%5D" alt="[
   M_{21} = \begin{vmatrix}
   2 &amp; 3 \\
   0 &amp; 6
   \end{vmatrix} = (2 \cdot 6) - (3 \cdot 0) = 12
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B21%7D%20%3D%20(-1)%5E%7B2%2B1%7D%20%5Ccdot%2012%20%3D%20-12%0A%20%20%20%5D" alt="[
   C_{21} = (-1)^{2+1} \cdot 12 = -12
   ]" />

5. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B22%7D%20)" alt="( C_{22} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B22%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%203%20%5C%5C%0A%20%20%201%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%206)%20-%20(3%20%5Ccdot%201)%20%3D%203%0A%20%20%20%5D" alt="[
   M_{22} = \begin{vmatrix}
   1 &amp; 3 \\
   1 &amp; 6
   \end{vmatrix} = (1 \cdot 6) - (3 \cdot 1) = 3
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B22%7D%20%3D%20(-1)%5E%7B2%2B2%7D%20%5Ccdot%203%20%3D%203%0A%20%20%20%5D" alt="[
   C_{22} = (-1)^{2+2} \cdot 3 = 3
   ]" />

6. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B23%7D%20)" alt="( C_{23} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B23%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%202%20%5C%5C%0A%20%20%201%20%26%200%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%200)%20-%20(2%20%5Ccdot%201)%20%3D%20-2%0A%20%20%20%5D" alt="[
   M_{23} = \begin{vmatrix}
   1 &amp; 2 \\
   1 &amp; 0
   \end{vmatrix} = (1 \cdot 0) - (2 \cdot 1) = -2
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B23%7D%20%3D%20(-1)%5E%7B2%2B3%7D%20%5Ccdot%20(-2)%20%3D%202%0A%20%20%20%5D" alt="[
   C_{23} = (-1)^{2+3} \cdot (-2) = 2
   ]" />

7. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B31%7D%20)" alt="( C_{31} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B31%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%202%20%26%203%20%5C%5C%0A%20%20%204%20%26%205%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(2%20%5Ccdot%205)%20-%20(3%20%5Ccdot%204)%20%3D%2010%20-%2012%20%3D%20-2%0A%20%20%20%5D" alt="[
   M_{31} = \begin{vmatrix}
   2 &amp; 3 \\
   4 &amp; 5
   \end{vmatrix} = (2 \cdot 5) - (3 \cdot 4) = 10 - 12 = -2
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B31%7D%20%3D%20(-1)%5E%7B3%2B1%7D%20%5Ccdot%20(-2)%20%3D%20-2%0A%20%20%20%5D" alt="[
   C_{31} = (-1)^{3+1} \cdot (-2) = -2
   ]" />

8. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B32%7D%20)" alt="( C_{32} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B32%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%203%20%5C%5C%0A%20%20%200%20%26%205%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%205)%20-%20(3%20%5Ccdot%200)%20%3D%205%0A%20%20%20%5D" alt="[
   M_{32} = \begin{vmatrix}
   1 &amp; 3 \\
   0 &amp; 5
   \end{vmatrix} = (1 \cdot 5) - (3 \cdot 0) = 5
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B32%7D%20%3D%20(-1)%5E%7B3%2B2%7D%20%5Ccdot%205%20%3D%20-5%0A%20%20%20%5D" alt="[
   C_{32} = (-1)^{3+2} \cdot 5 = -5
   ]" />

9. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B33%7D%20)" alt="( C_{33} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B33%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%202%20%5C%5C%0A%20%20%200%20%26%204%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%204)%20-%20(2%20%5Ccdot%200)%20%3D%204%0A%20%20%20%5D" alt="[
   M_{33} = \begin{vmatrix}
   1 &amp; 2 \\
   0 &amp; 4
   \end{vmatrix} = (1 \cdot 4) - (2 \cdot 0) = 4
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B33%7D%20%3D%20(-1)%5E%7B3%2B3%7D%20%5Ccdot%204%20%3D%204%0A%20%20%20%5D" alt="[
   C_{33} = (-1)^{3+3} \cdot 4 = 4
   ]" />

So, the cofactor matrix <img src="https://i.upmath.me/svg/(%20C%20)" alt="( C )" /> is:

<img src="https://i.upmath.me/svg/%5B%0AC%20%3D%20%5Cbegin%7Bpmatrix%7D%0A24%20%26%205%20%26%20-4%20%5C%5C%0A-12%20%26%203%20%26%202%20%5C%5C%0A-2%20%26%20-5%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
C = \begin{pmatrix}
24 &amp; 5 &amp; -4 \\
-12 &amp; 3 &amp; 2 \\
-2 &amp; -5 &amp; 4
\end{pmatrix}
]" />



### Inverse of a Matrix

The inverse of a matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is denoted by <img src="https://i.upmath.me/svg/(%20A%5E%7B-1%7D%20)" alt="( A^{-1} )" /> and is defined as the matrix that, when multiplied by <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />, yields the identity matrix <img src="https://i.upmath.me/svg/(%20I%20)" alt="( I )" />. Not all matrices have inverses; a matrix must be square and have a non-zero determinant to have an inverse.

The formula for the inverse of a matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is:
<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B%5Ctext%7Bdet%7D(A)%7D%20%5Ctext%7Badj%7D(A)%0A%5D" alt="[
A^{-1} = \frac{1}{\text{det}(A)} \text{adj}(A)
]" />
where <img src="https://i.upmath.me/svg/(%5Ctext%7Bdet%7D(A))" alt="(\text{det}(A))" /> is the determinant of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> and <img src="https://i.upmath.me/svg/(%5Ctext%7Badj%7D(A))" alt="(\text{adj}(A))" /> is the  adjoint of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />.

### Adjoint Matrix

The adjoint matrix <img src="https://i.upmath.me/svg/(%5Ctext%7Badj%7D(A))" alt="(\text{adj}(A))" /> of a matrix <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is the transpose of the cofactor matrix of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" />. The cofactor matrix is formed by replacing each element <img src="https://i.upmath.me/svg/(%20a_%7Bij%7D%20)" alt="( a_{ij} )" /> of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> with its cofactor <img src="https://i.upmath.me/svg/(%20C_%7Bij%7D%20)" alt="( C_{ij} )" />.


**Example**

Let's consider a 3x3 matrix \( A \):

<img src="https://i.upmath.me/svg/%5B%0AA%20%3D%20%5Cbegin%7Bpmatrix%7D%0A1%20%26%202%20%26%203%20%5C%5C%0A0%20%26%204%20%26%205%20%5C%5C%0A1%20%26%200%20%26%206%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A = \begin{pmatrix}
1 &amp; 2 &amp; 3 \\
0 &amp; 4 &amp; 5 \\
1 &amp; 0 &amp; 6
\end{pmatrix}
]" />

**Step 1: Find the Determinant**

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Bdet%7D(A)%20%3D%201%20%5Ccdot%20(4%20%5Ccdot%206%20-%205%20%5Ccdot%200)%20-%202%20%5Ccdot%20(0%20%5Ccdot%206%20-%205%20%5Ccdot%201)%20%2B%203%20%5Ccdot%20(0%20%5Ccdot%200%20-%204%20%5Ccdot%201)%0A%5D" alt="[
\text{det}(A) = 1 \cdot (4 \cdot 6 - 5 \cdot 0) - 2 \cdot (0 \cdot 6 - 5 \cdot 1) + 3 \cdot (0 \cdot 0 - 4 \cdot 1)
]" />

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Bdet%7D(A)%20%3D%201%20%5Ccdot%2024%20-%202%20%5Ccdot%20(-5)%20%2B%203%20%5Ccdot%20(-4)%0A%5D" alt="[
\text{det}(A) = 1 \cdot 24 - 2 \cdot (-5) + 3 \cdot (-4)
]" /> 

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Bdet%7D(A)%20%3D%2024%20%2B%2010%20-%2012%20%3D%2022%0A%5D" alt="[
\text{det}(A) = 24 + 10 - 12 = 22
]" />

**Step 2: Calculate the Cofactor Matrix**

1. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B11%7D%20)" alt="( C_{11} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B11%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%204%20%26%205%20%5C%5C%0A%20%20%200%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(4%20%5Ccdot%206)%20-%20(5%20%5Ccdot%200)%20%3D%2024%0A%20%20%20%5D" alt="[
   M_{11} = \begin{vmatrix}
   4 &amp; 5 \\
   0 &amp; 6
   \end{vmatrix} = (4 \cdot 6) - (5 \cdot 0) = 24
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B11%7D%20%3D%20(-1)%5E%7B1%2B1%7D%20%5Ccdot%2024%20%3D%2024%0A%20%20%20%5D" alt="[
   C_{11} = (-1)^{1+1} \cdot 24 = 24
   ]" />

2. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B12%7D%20)" alt="( C_{12} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B12%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%200%20%26%205%20%5C%5C%0A%20%20%201%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(0%20%5Ccdot%206)%20-%20(5%20%5Ccdot%201)%20%3D%20-5%0A%20%20%20%5D" alt="[
   M_{12} = \begin{vmatrix}
   0 &amp; 5 \\
   1 &amp; 6
   \end{vmatrix} = (0 \cdot 6) - (5 \cdot 1) = -5
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B12%7D%20%3D%20(-1)%5E%7B1%2B2%7D%20%5Ccdot%20(-5)%20%3D%205%0A%20%20%20%5D" alt="[
   C_{12} = (-1)^{1+2} \cdot (-5) = 5
   ]" />

3. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B13%7D%20)" alt="( C_{13} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B13%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%200%20%26%204%20%5C%5C%0A%20%20%201%20%26%200%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(0%20%5Ccdot%200)%20-%20(4%20%5Ccdot%201)%20%3D%20-4%0A%20%20%20%5D" alt="[
   M_{13} = \begin{vmatrix}
   0 &amp; 4 \\
   1 &amp; 0
   \end{vmatrix} = (0 \cdot 0) - (4 \cdot 1) = -4
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B13%7D%20%3D%20(-1)%5E%7B1%2B3%7D%20%5Ccdot%20(-4)%20%3D%20-4%0A%20%20%20%5D" alt="[
   C_{13} = (-1)^{1+3} \cdot (-4) = -4
   ]" />

4. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B21%7D%20)" alt="( C_{21} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B21%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%202%20%26%203%20%5C%5C%0A%20%20%200%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(2%20%5Ccdot%206)%20-%20(3%20%5Ccdot%200)%20%3D%2012%0A%20%20%20%5D" alt="[
   M_{21} = \begin{vmatrix}
   2 &amp; 3 \\
   0 &amp; 6
   \end{vmatrix} = (2 \cdot 6) - (3 \cdot 0) = 12
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B21%7D%20%3D%20(-1)%5E%7B2%2B1%7D%20%5Ccdot%2012%20%3D%20-12%0A%20%20%20%5D" alt="[
   C_{21} = (-1)^{2+1} \cdot 12 = -12
   ]" />

5. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B22%7D%20)" alt="( C_{22} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B22%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%203%20%5C%5C%0A%20%20%201%20%26%206%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%206)%20-%20(3%20%5Ccdot%201)%20%3D%203%0A%20%20%20%5D" alt="[
   M_{22} = \begin{vmatrix}
   1 &amp; 3 \\
   1 &amp; 6
   \end{vmatrix} = (1 \cdot 6) - (3 \cdot 1) = 3
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B22%7D%20%3D%20(-1)%5E%7B2%2B2%7D%20%5Ccdot%203%20%3D%203%0A%20%20%20%5D" alt="[
   C_{22} = (-1)^{2+2} \cdot 3 = 3
   ]" />

6. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B23%7D%20)" alt="( C_{23} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B23%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%202%20%5C%5C%0A%20%20%201%20%26%200%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%200)%20-%20(2%20%5Ccdot%201)%20%3D%20-2%0A%20%20%20%5D" alt="[
   M_{23} = \begin{vmatrix}
   1 &amp; 2 \\
   1 &amp; 0
   \end{vmatrix} = (1 \cdot 0) - (2 \cdot 1) = -2
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B23%7D%20%3D%20(-1)%5E%7B2%2B3%7D%20%5Ccdot%20(-2)%20%3D%202%0A%20%20%20%5D" alt="[
   C_{23} = (-1)^{2+3} \cdot (-2) = 2
   ]" />

7. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B31%7D%20)" alt="( C_{31} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B31%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%202%20%26%203%20%5C%5C%0A%20%20%204%20%26%205%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(2%20%5Ccdot%205)%20-%20(3%20%5Ccdot%204)%20%3D%2010%20-%2012%20%3D%20-2%0A%20%20%20%5D" alt="[
   M_{31} = \begin{vmatrix}
   2 &amp; 3 \\
   4 &amp; 5
   \end{vmatrix} = (2 \cdot 5) - (3 \cdot 4) = 10 - 12 = -2
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B31%7D%20%3D%20(-1)%5E%7B3%2B1%7D%20%5Ccdot%20(-2)%20%3D%20-2%0A%20%20%20%5D" alt="[
   C_{31} = (-1)^{3+1} \cdot (-2) = -2
   ]" />

8. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B32%7D%20)" alt="( C_{32} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B32%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%203%20%5C%5C%0A%20%20%200%20%26%205%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%205)%20-%20(3%20%5Ccdot%200)%20%3D%205%0A%20%20%20%5D" alt="[
   M_{32} = \begin{vmatrix}
   1 &amp; 3 \\
   0 &amp; 5
   \end{vmatrix} = (1 \cdot 5) - (3 \cdot 0) = 5
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B32%7D%20%3D%20(-1)%5E%7B3%2B2%7D%20%5Ccdot%205%20%3D%20-5%0A%20%20%20%5D" alt="[
   C_{32} = (-1)^{3+2} \cdot 5 = -5
   ]" />

9. **Cofactor <img src="https://i.upmath.me/svg/(%20C_%7B33%7D%20)" alt="( C_{33} )" />:**

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20M_%7B33%7D%20%3D%20%5Cbegin%7Bvmatrix%7D%0A%20%20%201%20%26%202%20%5C%5C%0A%20%20%200%20%26%204%0A%20%20%20%5Cend%7Bvmatrix%7D%20%3D%20(1%20%5Ccdot%204)%20-%20(2%20%5Ccdot%200)%20%3D%204%0A%20%20%20%5D" alt="[
   M_{33} = \begin{vmatrix}
   1 &amp; 2 \\
   0 &amp; 4
   \end{vmatrix} = (1 \cdot 4) - (2 \cdot 0) = 4
   ]" />

   <img src="https://i.upmath.me/svg/%5B%0A%20%20%20C_%7B33%7D%20%3D%20(-1)%5E%7B3%2B3%7D%20%5Ccdot%204%20%3D%204%0A%20%20%20%5D" alt="[
   C_{33} = (-1)^{3+3} \cdot 4 = 4
   ]" />

So, the cofactor matrix <img src="https://i.upmath.me/svg/(%20C%20)" alt="( C )" /> is:

<img src="https://i.upmath.me/svg/%5B%0AC%20%3D%20%5Cbegin%7Bpmatrix%7D%0A24%20%26%205%20%26%20-4%20%5C%5C%0A-12%20%26%203%20%26%202%20%5C%5C%0A-2%20%26%20-5%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
C = \begin{pmatrix}
24 &amp; 5 &amp; -4 \\
-12 &amp; 3 &amp; 2 \\
-2 &amp; -5 &amp; 4
\end{pmatrix}
]" />

**Step 3: Transpose the Cofactor Matrix to Get the Adjoint Matrix**

<img src="https://i.upmath.me/svg/%5B%0A%5Ctext%7Badj%7D(A)%20%3D%20C%5ET%20%3D%20%5Cbegin%7Bpmatrix%7D%0A24%20%26%20-12%20%26%20-2%20%5C%5C%0A5%20%26%203%20%26%20-5%20%5C%5C%0A-4%20%26%202%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
\text{adj}(A) = C^T = \begin{pmatrix}
24 &amp; -12 &amp; -2 \\
5 &amp; 3 &amp; -5 \\
-4 &amp; 2 &amp; 4
\end{pmatrix}
]" />

**Step 4: Multiply the Adjugate Matrix by \(\frac{1}{\text{det}(A)}\)**

<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cfrac%7B1%7D%7B22%7D%20%5Cbegin%7Bpmatrix%7D%0A24%20%26%20-12%20%26%20-2%20%5C%5C%0A5%20%26%203%20%26%20-5%20%5C%5C%0A-4%20%26%202%20%26%204%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A^{-1} = \frac{1}{22} \begin{pmatrix}
24 &amp; -12 &amp; -2 \\
5 &amp; 3 &amp; -5 \\
-4 &amp; 2 &amp; 4
\end{pmatrix}
]" />

So, the inverse of <img src="https://i.upmath.me/svg/(%20A%20)" alt="( A )" /> is:

<img src="https://i.upmath.me/svg/%5B%0AA%5E%7B-1%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%5Cfrac%7B24%7D%7B22%7D%20%26%20%5Cfrac%7B-12%7D%7B22%7D%20%26%20%5Cfrac%7B-2%7D%7B22%7D%20%5C%5C%0A%5Cfrac%7B5%7D%7B22%7D%20%26%20%5Cfrac%7B3%7D%7B22%7D%20%26%20%5Cfrac%7B-5%7D%7B22%7D%20%5C%5C%0A%5Cfrac%7B-4%7D%7B22%7D%20%26%20%5Cfrac%7B2%7D%7B22%7D%20%26%20%5Cfrac%7B4%7D%7B22%7D%0A%5Cend%7Bpmatrix%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%0A%5Cfrac%7B12%7D%7B11%7D%20%26%20%5Cfrac%7B-6%7D%7B11%7D%20%26%20%5Cfrac%7B-1%7D%7B11%7D%20%5C%5C%0A%5Cfrac%7B5%7D%7B22%7D%20%26%20%5Cfrac%7B3%7D%7B22%7D%20%26%20%5Cfrac%7B-5%7D%7B22%7D%20%5C%5C%0A%5Cfrac%7B-2%7D%7B11%7D%20%26%20%5Cfrac%7B1%7D%7B11%7D%20%26%20%5Cfrac%7B2%7D%7B11%7D%0A%5Cend%7Bpmatrix%7D%0A%5D" alt="[
A^{-1} = \begin{pmatrix}
\frac{24}{22} &amp; \frac{-12}{22} &amp; \frac{-2}{22} \\
\frac{5}{22} &amp; \frac{3}{22} &amp; \frac{-5}{22} \\
\frac{-4}{22} &amp; \frac{2}{22} &amp; \frac{4}{22}
\end{pmatrix} = \begin{pmatrix}
\frac{12}{11} &amp; \frac{-6}{11} &amp; \frac{-1}{11} \\
\frac{5}{22} &amp; \frac{3}{22} &amp; \frac{-5}{22} \\
\frac{-2}{11} &amp; \frac{1}{11} &amp; \frac{2}{11}
\end{pmatrix}
]" />

**Properties Inverse of Matrix**
- <img src="https://i.upmath.me/svg/((A%5E%7B-1%7D)%5E%7B-1%7D%20%3D%20A)" alt="((A^{-1})^{-1} = A)" />

- <img src="https://i.upmath.me/svg/((AB)%5E%7B-1%7D%20%3D%20B%5E%7B-1%7DA%5E%7B-1%7D%20)" alt="((AB)^{-1} = B^{-1}A^{-1} )" />

- only a non-singular square matrix can have an inverse. 






