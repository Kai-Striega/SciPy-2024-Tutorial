# Numerical Algorithms

Contributors:

* Kai Striega

## Short Description

Numerical methods are indispensable tools for scientists, enabling them to address complex problems, obtain approximate solutions, and gain insights into a wide range of phenomena across various disciplines. However despite their widespread use designing and implementing numerical algorithms is not a simple task and can lead to potentially catastrophic errors when not used with caution. This talk covers the foundations of designing numerical algorithms in a wide range of contexts. Furthermore the tutorial introduces the three pillars of accuracy, stability and efficiency when considering solutions. Understanding these basic properties of numerical algorithms should prevent the unwary from using software packages inappropriately or uncritically, and provide a foundation for devising methods for nonstandard problems. 

For maximal benefit, participants are expected to have experience writing for loops and working with NumPy arrays. The necessary syntax will be introduced in the tutorial, however having some familiarity will help. No knowledge of numerical algorithms is expected. An understanding of the underlying mathematics is assumed and should be covered by anyone having taken the standard first year mathematics curriculum. However, the most important and beneficial requirement is the ability to learn new things.

## Long Description

Numerical methods are indispensable tools for scientists, enabling them to address complex problems, obtain approximate solutions, and gain insights into a wide range of phenomena across various disciplines. However despite their widespread use designing and implementing numerical algorithms is not a simple task and can lead to potentially catastrophic errors when not used with caution. This talk covers the foundations of designing numerical algorithms in a wide range of contexts. Furthermore the tutorial introduces the three pillars of accuracy, stability and efficiency when considering solutions. Understanding these basic properties of numerical algorithms should prevent the unwary from using software packages inappropriately or uncritically, and provide a foundation for devising methods for nonstandard problems. 

The tutorial will be divided into four parts. The first will introduce floating point arithmetic with the remaining part focusing on numerical algorithms used in solving linear system of equations, numerical differentiation and integration respectively. Each part will be further split to cover selected algorithms related to that part. Each topic will be introduced mathematically after which participants will be asked to implement, experiment with and/or break the topic being covered. 


#### Part 1: Numbers, expressions and imprecision (30 minutes teaching time)

* From Real to Floating-Point numbers
* The IEEE-754 standard
* Using NumPy to represent Floating-Point numbers
* Example of Floating-Point errors


**Break (10 minutes)**

#### Part 2: Linear systems of equations (70 minutes teaching time)
 
* Mathematical background
* Gaussian Elimination
* Implement Gaussian Elimination in Python
* Problems with Gaussian elimination

**Break (10 minutes)**

* The Jacobi Method
* The Gauss-Seidel method
* Successive Over Relaxation
* The Conjugate Gradient Method

**Break (10 minutes)**

#### Part 3: Differentiation (50 minutes teaching time)



**Break (10 minutes)**

#### Part 4: Integration (50 minutes teaching time) 

* Mathematical Grounding: Integration 
* Quadrature in SciPy 
* Riemann sums/Trapezoidal Rule
* Newton-Cotes formula
* Gaussian Quadrature
