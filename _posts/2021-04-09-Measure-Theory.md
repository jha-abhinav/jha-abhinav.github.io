---
layout: post
---
<link rel="stylesheet" href="https://latex.now.sh/style.css"> 
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

## Product Measure

<div class="definition"> 
A monotone class M is a collection of sets in which given any increasing(or decreasing) chain w.r.t inclusion,
the union(or intersection) of all the elements of the chain is in the set.
<br>
Eg. Any sigma algebra is a monotone class
</div>

<div class="lemma"> 
Intersection of an arbitrary collection of monotone classes is a monotone class.
</div>

<div class="theorem">
\(M \times N \) is the smallest monotone class which contains all elementary sets 
(finite disjoint union of m'ble rectangles).
</div>

<div class="definition">

Let \(f:X \times Y \to R \) be a fn, for each \( x \in X, y \in Y \) we define
\[f_x(y)=f(x,y), \quad f^y(x)=f(x,y) \] where the functions are defined on Y and X respectively.

</div>

<div class="theorem">

Let f be an \( M \times n \) m'ble function on \( X \times Y \) then:
<br>
1. For each \(x \in X, f_x\) is a N-m'ble function. <br>
2. For each \(y \in Y, f^y\) is a M-m'ble function.

</div>

<div class="theorem">

Let \( (X,M,\mu) \) and \( (Y,N,\lambda) \) be \( \sigma - finite \) measure spaces.
Suppose \( Q \in M \times N \). Define
\[ \phi(x)=\lambda(Q_x), \quad \psi(y)= \mu (Q^y) \]
for every \( x \in X \) and \(y \in Y \), then \(\phi \) is M-m'ble and \( \psi \) is N- m'ble, and
\[ \int_X \phi \,d\mu = \int_Y \psi \,d\lambda \]

Another form of the statement,

\[ \int_X \,d\mu \int_Y \chi_Q (x,y) \,d\lambda =  \int_Y \,d\lambda \int_X \chi_Q (x,y) \,d\mu  \]

</div>

<div class="definition">
Let \( (X,M,\mu) \) and \( (Y,N,\lambda) \) be \( \sigma - finite \) measure spaces.
Suppose \( Q \in M \times N \). Define
\[ (\mu \times \lambda) (Q) = \int_X \,d\mu \int_Y \chi_Q (x,y) \,d\lambda =  \int_Y \,d\lambda \int_X \chi_Q (x,y) \,d\mu  \]

</div>

<div class="lemma">
With above notations, \( \mu \times \lambda \) is a measure on \( M \times N \).
Further, \( \mu \times \lambda \) is \( \sigma - finite \).


<div class="theorem">
<b> (Fubini's Theorem) </b>
Let \( (X,M,\mu) \) and \( (Y,N,\lambda) \) be \( \sigma - finite \) measure spaces.
Let f be an \( M \times N \) measurable function on \( X \times Y \).
<br>
a. <b> (Torelli's Theorem) </b> If \( 0 \leq f \leq \infty \), and if
\[ \phi(x) := \int_Y f_x \,d\lambda, \quad \psi(y):= \int_X f^y d\mu \quad (x \in X, y \in Y), \]

then \(\phi\) is M-m'ble, \( \psi \) is N-m'ble, and 
\[ \int_X \phi \,d\mu = \int_{X \times Y} f \,d(\mu \times \lambda) = \int_{Y} \psi \,d\lambda. \] 

b. If f is a real/complex valued \( M \times N \) m'ble function and if
\[ \phi^{*} (x) = \int_Y |f|_x \,d\lambda \quad and \int_X \phi^{*} \,d\mu < \infty, \]
then \( f \in L^1 (\mu \times \lambda) \).
<br>
c. If \( f \in L^1 (\mu \times \lambda ) \), then \( f_x \in L^1 (\lambda) \) for almost all \( x \in X \), 
\( f_y \in L^1 (\mu) \) for almost all \( y \in Y \) ; the functions \( \phi\) and \( \psi \), defined by (a.) a.e.,
are in \( L^1 (\mu)\) and \( L^1 (\lambda)\), respectively, and
\[ \int_X \phi \,d\mu = \int_{X \times Y} f \,d(\mu \times \lambda) = \int_{Y} \psi \,d\lambda. \] 

</div>


