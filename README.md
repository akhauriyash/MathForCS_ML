# Algebra, Topology, Differential Calculus, and Optimization Theory for Computer Science and Machine Learning 
### Jean Gallier and Jocelyn Quaintance
Contains important notes/definitions/propositions from the book **Algebra, Topology, Differential Calculus, and Optimization Theory for Computer Science and Machine Learning Jean Gallier and Jocelyn Quaintance.**
The book can be found [here.](https://www.cis.upenn.edu/~jean/gbooks/geomath.html)



# Table of contents

- [Introduction](#Ch1)
- [Groups, Rings, and Fields](#Ch2)
- [Vector Spaces, Bases, Linear Maps](#Ch3)
- [Matrices and Linear Maps](#Ch4)
- [Haar Bases, Haar Wavelets, Hadamard Matrices](#Ch5)
- [Direct Sums](#Ch6)
- [Determinants](#Ch7)
- [Gaussian Elimination, LU, Cholesky, Echelon Form](#Ch8)
- [Vector Norms and Matrix Norms](#Ch9)
- [Iterative Methods for Solving Linear Systems](#Ch10)
- [The Dual Space and Duality](#Ch11)
- [Euclidean Spaces](#Ch12)
- [QR-Decomposition for Arbitrary Matrices](#Ch13)
- [Hermitian Spaces](#Ch14)
- [Eigenvectors and Eigenvalues](#Ch15)
- [Unit Quaternions and Rotations in SO(3)](#Ch16)
- [Spectral Theorems](#Ch17)
- [Computing Eigenvalues and Eigenvectors](#Ch18)
- [Introduction to The Finite Elements Method](#Ch19)
- [Graphs and Graph Laplacians; Basic Facts](#Ch20)
- [Spectral Graph Drawing](#Ch21)
- [Singular Value Decomposition and Polar Form](#Ch22)
- [Applications of SVD and Pseudo-Inverses](#Ch23)
- [Basics of Affine Geometry](#Ch24)
- [Embedding an Affine Space in a Vector Space](#Ch25)
- [Basics of Projective Geometry](#Ch26)
- [The Cartan–Dieudonn´e Theorem](#Ch27)
- [Isometries of Hermitian Spaces](#Ch28)
- [The Geometry of Bilinear Forms; Witt’s Theorem](#Ch29)
- [Polynomials, Ideals and PID’s](#Ch30)
- [Annihilating Polynomials; Primary Decomposition](#Ch31)
- [UFD’s, Noetherian Rings, Hilbert’s Basis Theorem](#Ch32)
- [Tensor Algebras](#Ch33)
- [Exterior Tensor Powers and Exterior Algebras](#Ch34)
- [Introduction to Modules; Modules over a PID](#Ch35)
- [Normal Forms; The Rational Canonical Form](#Ch36)
- [Topology](#Ch37)
- [A Detour On Fractals](#Ch38)
- [Differential Calculus](#Ch39)
- [Extrema of Real-Valued Functions](#Ch40)
- [Newton’s Method and Its Generalizations](#Ch41)
- [Quadratic Optimization Problems](#Ch42)
- [Schur Complements and Applications](#Ch43)
- [Convex Sets, Cones, H-Polyhedra](#Ch44)
- [Linear Programs](#Ch45)
- [The Simplex Algorithm](#Ch46)
- [Linear Programming and Duality](#Ch47)
- [Basics of Hilbert Spaces](#Ch48)
- [General Results of Optimization Theory](#Ch49)
- [Introduction to Nonlinear Optimization](#Ch50)
- [Subgradients and Subdifferentials](#Ch51)
- [Dual Ascent Methods; ADMM](#Ch52)
- [Ridge Regression and Lasso Regression](#Ch53)
- [Positive Definite Kernels](#Ch54)
- [Soft Margin Support Vector Machines](#Ch55)
- [Total Orthogonal Families in Hilbert Spaces](#Ch56)
- [Zorn’s Lemma; Some Applications](#Ch57)

### Introduction <a name="Ch1"></a>

These are just meant to be notes for personal use, you may find them useful. I have very limited background in mathematics, so there may be mistakes here. 
You will most definitely need to keep the book open on the side as this mentions specific definitions/propositions by reference for brevity. 

I may give up on this endeavor at any moment I find better ways to condense knowledge for myself. 

### Groups, Rings, and Fields <a name="#Ch2"></a>

![def2.1](images/def2.1.png)

**Abelian**:
A group G is *abelian* (or commutative) if:
![abel](images/abel.png)

**Monoid**:
Set M with operation MxM -> M and element 'e' satisfying (G1) and (G2) is a monoid. Not necessarily a group.

**General Linear Group GL(n, R) or GL(n, C)** : 
1. N x N Invertible with Real/Complex Coefficients
2. Group under MatMul
3. Identity element In

**Special Linear Group SL(n, R) or GL(n, R)**:
1. Sub-group of GL with det(matrix) = 1

**Orthogonal Group O(n)**:
1. Set of N x N invertible matrices (Q) with real coefficients 
2. QQ' = Q'Q = In

**Special Orthogonal Group SO(n)**:
1. Sub-group of O(n) with Det(Q) = 1

**Proposition 2.7:** For finite group G, subgroup H of G, orcer of H divides order of G.

**Rings**

![def2.16](images/def2.16.png)

**Fields**

![def2.22](images/def2.22.png)

### Vector Spaces, Bases, Linear Maps <a name="Ch3"></a>


### Matrices and Linear Maps <a name="Ch4"></a>


### Haar Bases, Haar Wavelets, Hadamard Matrices <a name="Ch5"></a>


### Direct Sums <a name="Ch6"></a>


### Determinants <a name="Ch7"></a>


### Gaussian Elimination, LU, Cholesky, Echelon Form <a name="Ch8"></a>


### Vector Norms and Matrix Norms <a name="Ch9"></a>


### Iterative Methods for Solving Linear Systems <a name="Ch10"></a>


### The Dual Space and Duality <a name="Ch11"></a>


### Euclidean Spaces <a name="Ch12"></a>


### QR-Decomposition for Arbitrary Matrices <a name="Ch13"></a>


### Hermitian Spaces <a name="Ch14"></a>


### Eigenvectors and Eigenvalues <a name="Ch15"></a>


### Unit Quaternions and Rotations in SO(3 <a name="Ch16"></a>


### Spectral Theorems <a name="Ch17"></a>


### Computing Eigenvalues and Eigenvectors <a name="Ch18"></a>


### Introduction to The Finite Elements Method <a name="Ch19"></a>


### Graphs and Graph Laplacians; Basic Facts <a name="Ch20"></a>


### Spectral Graph Drawing <a name="Ch21"></a>


### Singular Value Decomposition and Polar Form <a name="Ch22"></a>


### Applications of SVD and Pseudo-Inverses <a name="Ch23"></a>


### Basics of Affine Geometry <a name="Ch24"></a>


### Embedding an Affine Space in a Vector Space <a name="Ch25"></a>


### Basics of Projective Geometry <a name="Ch26"></a>


### The Cartan–Dieudonn´e Theorem <a name="Ch27"></a>


### Isometries of Hermitian Spaces <a name="Ch28"></a>


### The Geometry of Bilinear Forms; Witt’s Theorem <a name="Ch29"></a>


### Polynomials, Ideals and PID’s <a name="Ch30"></a>


### Annihilating Polynomials; Primary Decomposition <a name="Ch31"></a>


### UFD’s, Noetherian Rings, Hilbert’s Basis Theorem <a name="Ch32"></a>


### Tensor Algebras <a name="Ch33"></a>


### Exterior Tensor Powers and Exterior Algebras <a name="Ch34"></a>


### Introduction to Modules; Modules over a PID <a name="Ch35"></a>


### Normal Forms; The Rational Canonical Form <a name="Ch36"></a>


### Topology <a name="Ch37"></a>


### A Detour On Fractals <a name="Ch38"></a>


### Differential Calculus <a name="Ch39"></a>


### Extrema of Real-Valued Functions <a name="Ch40"></a>


### Newton’s Method and Its Generalizations <a name="Ch41"></a>


### Quadratic Optimization Problems <a name="Ch42"></a>


### Schur Complements and Applications <a name="Ch43"></a>


### Convex Sets, Cones, H-Polyhedra <a name="Ch44"></a>


### Linear Programs <a name="Ch45"></a>


### The Simplex Algorithm <a name="Ch46"></a>


### Linear Programming and Duality <a name="Ch47"></a>


### Basics of Hilbert Spaces <a name="Ch48"></a>


### General Results of Optimization Theory <a name="Ch49"></a>


### Introduction to Nonlinear Optimization <a name="Ch50"></a>


### Subgradients and Subdifferentials <a name="Ch51"></a>


### Dual Ascent Methods; ADMM <a name="Ch52"></a>


### Ridge Regression and Lasso Regression <a name="Ch53"></a>


### Positive Definite Kernels <a name="Ch54"></a>


### Soft Margin Support Vector Machines <a name="Ch55"></a>


### Total Orthogonal Families in Hilbert Spaces <a name="Ch56"></a>


### Zorn’s Lemma; Some Applications <a name="Ch57"></a>

