# STA 141C Additional Readings

> **Warning**
>
> Following are additional readings for STAT 141C Lecture Notes by Prof. Ning.

> **Note**
> 
> * [Python Source Code Analysis - Chinese](https://flaggo.github.io/python3-source-code-analysis/)
> * [Python Cookbook 3rd Edition Documentation - Chinese](https://python3-cookbook.readthedocs.io/zh_CN/latest/index.html)
> * [Python Cookbook 3rd Edition - English pdf](http://bedford-computing.co.uk/learning/wp-content/uploads/2015/10/Python-Cookbook-3rd-Edition.pdf)
> * [Python Programming And Numerical Methods: A Guide For Engineers And Scientists](https://pythonnumericalmethods.berkeley.edu/notebooks/Index.html)
> * [Scientific Computing with Python](https://caam37830.github.io/book/index.html)
> * [Pattern-Recognition-Books Lists](https://github.com/manjunath5496/Pattern-Recognition-Books)

- [STA 141C Additional Readings](#sta-141c-additional-readings)
  - [Lecture 2-1](#lecture-2-1)
  - [Lecture 2-2](#lecture-2-2)
  - [Lecture 3-1](#lecture-3-1)
  - [Lecture 3-2](#lecture-3-2)

## Lecture 2-1
* [Floating-point Number System](https://www.dspguide.com/ch4/3.htm)
* [Overflow and Underflow](https://www.educative.io/answers/what-are-overflow-and-underflow)
* [Catastrophic cancellation - mathematics](https://www.cs.utexas.edu/users/flame/laff/alaff/a2appendix-catastrophic-cancellation.html)
* [Python - Floating Point Arithmetic: Issues and Limitations](https://docs.python.org/3/tutorial/floatingpoint.html)
* **More readings of floating point numbers:**
  * *Python Cookbook 3rd Edition* - Chapter 3.3
  * *Python Programming and Numerical Methods - A Guide for Engineers and Scientists* - Chapter 9.2

## Lecture 2-2

**BLAS**:
> * **Basic Linear Algebra Subprograms (BLAS)** is a specification that prescribes a set of low-level routines for performing common linear algebra operations such as vector addition, scalar multiplication, dot products, linear combinations, and matrix multiplication.
> * They are the de facto (in reality) standard low-level routines for linear algebra libraries; the routines have bindings for both C ("CBLAS interface") and Fortran ("BLAS interface").

**LAPACK**:
> * **LAPACK ("Linear Algebra Package")** is a standard software library for numerical linear algebra. It provides routines for solving systems of linear equations and linear least squares, eigenvalue problems, and singular value decomposition. It also includes routines to implement the associated matrix factorizations such as LU, QR, Cholesky and Schur decomposition.

* [BLAS - Official Documentation](https://netlib.org/blas/)
* [LAPACK - Official documentation](https://netlib.org/lapack/)
* [BLAS and LAPACK](https://caam37830.github.io/book/02_linear_algebra/blas_lapack.html)

## Lecture 3-1
* Optional: [Pipelined adders](https://ieeexplore.ieee.org/document/485573)
* Optional: [Arithmetic-Logic Unit (ALU)](https://www.techtarget.com/whatis/definition/arithmetic-logic-unit-ALU)
* Review Readings: [Linear Algebra and Its Applications - 4th Edition.pdf](https://github.com/alfords/Linear-Algebra-and-Its-Applications/blob/master/Linear%20Algebra%20and%20Its%20Applications%20-%204th%20Edition.pdf)
* [scipy.linalg in python](https://docs.scipy.org/doc/scipy/tutorial/linalg.html)

> **`.solve()` in R:**
>
>$$
\begin{aligned}
    \underbrace{X}_{L U} \,\, \beta &= y\\
    L \,\, \underbrace{\boxed{U \beta}}_{\alpha}&= y\\\,\\
\end{aligned}
$$
> 1. $L \alpha = y$: $O(n^2)$ (solve $\alpha$)
> 2. $U \beta = \alpha$: $O(n^2)$ (solve $\beta$)
> 
> Combine (1) and (2), we can get $\hat{\beta}$

## Lecture 3-2
* [LU Decomposition 1](https://www.math.ucdavis.edu/~linear/old/notes11.pdf)
* [LU Decomposition 2](https://www.math.ucdavis.edu/~anne/WQ2007/mat67-Ln-LU_Factorization.pdf)
* [Exact Flop-Count for the LU Decomposition](https://cscproxy.mpi-magdeburg.mpg.de/mpcsc/lehre/2016_WS_SC/handouts/handout_LU_counting.pdf)
