---
layout: post
title: "Polynomial Rings"
---
<link rel="stylesheet" href="https://latex.now.sh/style.css"> 
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 
<div class="abstract">
   <h2> Abstract </h2>
<p>I'm too bored to study for an exam today at 4, so I thought revising and writing it out here would be fun.</p>
</div>
A Ring $$R$$, is a three tuple  $$(R,+,.)$$ that satisfies the following three axioms:
1. $$(R,+)$$ is an Abelian Group.
2. Multiplication is associative.
3. Distributive Laws: $$a.(b+c)=a.b + a.c \quad (b+c).a=b.a+c.a \quad \forall a,b,c \in R$$

<div class="theorem">
<b>(Eisenstein Criterion)</b> Let \(p \in \mathbb{Z}\) be a prime. Suppose that 
$$f(x)=a_{n}x^{n} + \ldots + a_{0} \in \mathbb{Z}[x],$$
and \(a_{n} \neq 0\) (mod p), but \(a_{i}= 0\)(mod p) for all i < n, with \(a_{0} \neq 0\) (mod \(p^2\)).
Then \(f(x)\) is irreducible over \(\mathbb{Q}\).
</div>

<div class="definition">
A <b>maximal ideal</b> of a ring \(R\) is an ideal \(M\) different from \(R\) and \({0}\)
such that there's no ideal \(N\) of \(R\) which properly contains \(M\).
</div>

<div class="definition">
A <b> prime ideal </b> of a ring \(R\) is an ideal \(N\) such that
if \(ab \in N\) then either \(a \in N\) or \(b \in N\).
</div>

<div class="definition">
An <b>integral domain</b> D is a commutative ring with unity \(1 \neq 0\) and containing no divisors of zero.
</div>

<div class="theorem">
For a commutative ring \(R\) with unity: <br>
1. An ideal \(M\) of \(R\) is maximal iff \(R/M\) is a field. <br>
2. An ideal \(N\) of \(R\) is prime iff \(R/N\) is an integral domain. <br>
3. Every maximal ideal of \(R\) is a prime ideal.
</div>

<div class="definition">
An integral domain D is a <b>unique factorization domain</b> (abbreviated UFD) if: <br>
1. Every element of D that is neither 0 nor a unit can be factored into a product of finite number of irreducibles. <br>
2. If \(p_{1}\ldots p_r\) and \(q_1\ldots q_s \) are two factorizations of the same element of D into irreducibles, 
then \( r= s\) and \(q_j\)'s can be renumbered so that \(p_i\) and \(q_i\) are associates.
</div>

<div class="definition">
An integral domain D is <b> principal ideal domain</b>(PID) if every ideal in D is a principal ideal.
<label for="sn-1" class="sidenote-toggle sidenote-number"></label>
<input type="checkbox" id="sn-1" class="sidenote-toggle" />
<span class="sidenote">Principal ideal \( < a > \), consists of all multiples of \(a\). </span>
</div>

<div class="theorem">
In a PID:<br>
1. An ideal \(< p >\) is maximal iff \(p\) is an irreducible. <br>
2. If \(p\) is irreducible then \(p\) is a prime.
<label for="sn-1" class="sidenote-toggle sidenote-number"></label>
<input type="checkbox" id="sn-1" class="sidenote-toggle" />
<span class="sidenote left"> In an Integral Domain, a prime is always an irreducible. </span> <br>
3. Any ascending chain of ideals is finite. (Ascending Chain Condition)
</div>

<div class="theorem">
Every PID is a UFD.
</div>

<div class="theorem">
If \(D\) is an UFD, then \(D[x]\) is an UFD.
</div>



