# Vectors and Scalars in Mathematics

## Table of Contents
1. [Scalars](#scalars)
2. [Vectors](#vectors)
3. [Vector Space Properties](#vector-space-properties)

---

## Scalars

**Scalars** are quantities that are fully described by a magnitude (numerical value) alone. They do not have any direction.

### Examples of Scalars:
- **Mass** (e.g., 5 kg)
- **Temperature** (e.g., 30°C)
- **Speed** (e.g., 60 km/h)
- **Energy** (e.g., 100 Joules)

### Operations on Scalars:
- **Addition/Subtraction**: Standard arithmetic applies (e.g., $(5 + 3 = 8)$).
- **Multiplication/Division**: Follow basic arithmetic rules (e.g., $(5 \times 3 = 15)$).

---

## Vectors

**Vectors** are quantities that have both a magnitude and a direction.

### Examples of Vectors:
- **Displacement** (e.g., 5 meters north)
- **Velocity** (e.g., 60 km/h east)
- **Force** (e.g., 10 Newtons upward)

### Operations on Vectors:
- **Addition**: Two vectors are added component-wise.
$(\vec{a} = (a_1, a_2, a_3),\vec{b} = (b_1, b_2, b_3)$
$(\vec{a} + \vec{b} = (a_1 + b_1, a_2 + b_2, a_3 + b_3))
$

- **Scalar Multiplication**: A vector is multiplied by a scalar by multiplying each component by the scalar.

$(k \cdot \vec{a} = (k \cdot a_1, k \cdot a_2, k \cdot a_3))$
 
- **Dot Product**: The dot product of two vectors is a scalar.
 
  $$
  \vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2 + a_3 b_3
  
  $$

- **Cross Product**: The cross product of two vectors is a vector that is perpendicular to both original vectors.

  $(\vec{a} \times \vec{b} = (a_2 b_3 - a_3 b_2, a_3 b_1 - a_1 b_3, a_1 b_2 - a_2 b_1))$

---

## Vector Space Properties

A **vector space** consists of vectors and scalars and must satisfy several important properties.

### 1. Closure under Addition
If $(\vec{u})$ and $( \vec{v} )$ are vectors in the vector space \( V \), then their sum $( \vec{u})$ + $( \vec{v} )$ is also in \( V \)$

### 2. Closure under Scalar Multiplication
If $( \vec{v} )$ is a vector in $( V )$ and $( c )$ is a scalar, then $( c\vec{v} )$ is also in $( V )$.

### 3. Additive Identity (Zero Vector)
There exists a vector $( \vec{0} )$ such that for any vector $( \vec{v} \in V )$, $( \vec{v} + \vec{0} = \vec{v} )$.

### 4. Additive Inverse
For each vector $( \vec{v} \in V )$, there exists a vector $( -\vec{v} ) $such that$ ( \vec{v} + (-\vec{v}) = \vec{0} )$.

### 5. Associativity and Commutativity of Vector Addition
- **Associativity**: $( (\vec{u} + \vec{v}) + \vec{w} = \vec{u} + (\vec{v} + \vec{w}) )$
- **Commutativity**: $( \vec{u} + \vec{v} = \vec{v} + \vec{u} )$

### 6. Scalar Associativity and Distributivity
- **Scalar Associativity**: $( c(d\vec{v}) = (cd)\vec{v} )$
- **Distributivity over Vector Addition**: $( c(\vec{u} + \vec{v}) = c\vec{u} + c\vec{v} )$
- **Distributivity over Scalar Addition**: $( (c + d)\vec{v} = c\vec{v} + d\vec{v} )$

### 7. Scalar Multiplicative Identity
There exists a scalar $( 1 )$ such that $( 1\vec{v} = \vec{v} )$ for any vector $( \vec{v} \in V )$.