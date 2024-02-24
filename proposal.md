# Numerical Algorithms

Contributors:

* Kai Striega

## Short Description

Numerical algorithms are indispensable tools for scientists, enabling them to address complex problems, obtain approximate solutions, and gain insights into a wide range of phenomena across various disciplines. Despite their widespread use, designing and implementing numerical algorithms is not a simple task and can lead to potentially catastrophic errors when not used with caution. This tutorial covers the foundations of designing numerical algorithms. Understanding the basic properties of numerical algorithms should not only prevent the unwary from using software packages inappropriately or uncritically, but should also provide a foundation for devising methods for nonstandard problems.

For maximal benefit, participants are expected to have experience writing for loops and working with NumPy arrays. The necessary syntax will be introduced in the tutorial, however having some familiarity will help as well. No prior knowledge of numerical algorithms is expected to start this tutorial. An understanding of the underlying mathematics is assumed and should be covered by anyone having taken the standard first year mathematics curriculum. The most important and beneficial requirement is, however, the ability to learn new things.

## Long Description


### Tutorial Summary

Numerical algorithms are indispensable tools for scientists, enabling them to address complex problems, obtain approximate solutions, and gain insights into a wide range of phenomena across various disciplines. Despite their widespread use, designing and implementing numerical algorithms is not a simple task and can lead to potentially catastrophic errors when not used with caution. This tutorial covers the foundations of designing numerical algorithms. Understanding the basic properties of numerical algorithms should not only prevent the unwary from using software packages inappropriately or uncritically, but should also provide a foundation for devising methods for nonstandard problems.

### Expected Knowledge

For maximal benefit, participants are expected to have experience writing for loops and working with NumPy arrays. The necessary syntax will be introduced in the tutorial, however having some familiarity will help as well. No prior knowledge of numerical algorithms is expected to start this tutorial. An understanding of the underlying mathematics is assumed and should be covered by anyone having taken the standard first year mathematics curriculum. The most important and beneficial requirement is, however, the ability to learn new things.


### Tutorial Outline

#### Part 0: Introduction (10 minutes)

* Who am I, and why should you listen to me
* What are numerical algorithms?
* Introduction to today's problem

#### Part 1: Numbers, expressions and imprecision (50 minutes)

* From Real to Floating-Point numbers (10 minutes)
* The IEEE-754 standard (10 minutes)
* Practical Exercise: Sum of Floating Point numbers (5 minutes) 
* Using NumPy to represent Floating-Point numbers (5 minutes)
* Practical Exercise: Polynomial Evaluation (10 minutes)
* Practical Exercise: Finding the area of a triangle (10 minutes)

**Break (10 minutes)**

#### Part 2: Conditioning, Accuracy and Stability (50 minutes)

* Mathematical Definitions (10 minutes)
* Absolute and relative condition numbers (5 minutes)
* Practical Exercise: Well conditioned problems (10 minutes)
* Practical Exercise: Ill conditioned problems (10 minutes)
* Analysis: Roots of polynomials (5 minutes)
* Practical Exercise: Wilkinson's Example (10 minutes)

**Break (10 minutes)**


#### Part 3: Linear systems of equations (50 minutes)
 
* Mathematical background (10 minutes)
* Gaussian Elimination (5 minutes)
* Practical Exercise: Implement Gaussian elimination (10 minutes)
* Theoretical problems with Gaussian elimination (10 minutes)
* Practical Exercise: Breaking Gaussian elimination (15 minutes)

**Break (10 minutes)**

#### Part 4: Iterative Solutions (50 minutes)

* The Jacobi Method (5 minutes)
* Practical Exercise: Implementing the Jacobi method (10 minutes)
* The Gauss-Seidel method (5 minutes)
* Practical Exercise: Implementing the Gauss-Seidel method (10 minutes)
* Successive Over Relaxation (5 minutes)
* Practical Exercise: Adding SOR to our existing solvers (10 minutes)
* Practical Exercise: Evaluation of our solvers (5 minutes)

## Setup Instructions

All materials are available on GitHub: https://github.com/Kai-Striega/SciPy-2024-Tutorial. 

The dependencies for this tutorial are Python 3.12 and recent versions of the following packages:

* NumPy
* plotly
* jupyter lab

In this tutorial all the algorithms will be written from scratch, using only NumPy as an array datastructure and plotly for basic plotting. Jupyter Lab is required as the tutorial will be presented as a series of jupyter notebooks. Specific version of these requirements are provided.

**note**: It is highly recommended for participants to work in a virtual environment 

To allow reproducible builds, this tutorial uses [poetry](https://python-poetry.org/). It is expected that not all participants are familiar with or will want to use poetry. To be accessible to _all_ participants the lock file is exported into a `requirements.txt` file that is available with the repository. From here participants may install the exact requirements using pip. 

```shell
pip install -r requirements.txt
```
