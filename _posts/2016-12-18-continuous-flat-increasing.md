---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: post
title: Making pathological functions using measure theory
author: William H. Guss
---

Over the past year I've been studying measure theory and functional analysis at UC Berkeley. One of the best parts of this subject is getting a glimmer of *just how weird infinity is*. **Assuming some measure theory knowledge**, we're going to do the following today.

**Construct a nondecreasing function $f:\mathbb{R}\to\mathbb{R}$
with the property that $f$ is discontinuous at $x\in\mathbb{R}$
if and only if $x\in\mathbb{Q}$.**	

*Pretty pathological right?* We just need to count infinities.





We will define a function $H$ which is continuous from the left at ever $x \in [0,1]$ but is only continuous from the right at the irrationals. To build such a function we need the folliowing scaffolding.

First let $\psi: \mathbb{N} \to \mathbb{Q} \cap [0,1]$ be a bijection enumerating the rationals in the interval $[0,1]$. Then define $B(x) = \{n : \psi(n)< x\}$ or equivalently $B(x) = \psi^{-1}([0,x))$. Finally let $\mu: P(\mathbb{N}) \to \overline{\mathbb{R}}$ be the counting measure. We additionally define a measure $\nu: P(\mathbb{N}) \to \mathbb{R}$ such that 

$$\nu(A) = \int_A 2^{-n} d \mu(n).$$


The measure $\nu$ has the additional property that $\nu \ll \mu$ and 

$$\nu(\mathbb{N}) = \sum_{n \in \mathbb{N}} 2^{-n} \mu({n}) = 1 < \infty.$$

We claim that the function $H(x) = \nu(B(x))$ has the properties of $f$ in the statement of the problem. We will first show that for
every $x \in [0,1]$ the function $H(x)$ is left continuous. Take a sequence of $x_k \to x$ from the left, we can then rearrange the sequence to be strict monotonic. It follows that if $k > m$ then $B(x_m) = \{n: \psi(n) < x_m < x_k < x\} \subset \{n: \psi(n) < x_k < x\} = B(x_k)$. By the 
finiteness of $\nu$ we have that by upward measure continuity

$$\lim_{k \to \infty} H(x_k) = \lim_{k \to \infty} \nu(B(x_k)) = \nu\left(\bigcup_{k=1}^\infty B(x_k) \right)$$ 

$$\;\;\;\;\;\;\;\;\;\; = \nu(\left \{n: \psi(n) < x\}\right ) = H(x).$$

Note that if $ n \in \bigcup B(x_k)$  there is an $K$ so that $\psi(n) < x_k < x $ so any $n$ with $\psi(n) < x$ is in $\bigcup B(x_k).$

Next we claim that $H$ is only right continuous only when $x$ is irrational. Take a sequence of $x_k \to x$ from the right and rearrange the sequence to be  strict montonic. It follows that if $k > m$ then $B(x_m) = \{n: \psi(n) < x_m\} \supset \{n: \psi(n) < x_k < x_m\} = B(x_k)$. By finiteness of $\nu$ and downard measure continuity


$$\lim_{k \to \infty} H(x_k) = \lim_{k \to \infty} \nu(B(x_k)) = \nu\left(\bigcap_{k=1}^\infty B(x_k) \right) $$ 

$$\;\;\;\;\;\;= \nu(\left \{n: \psi(n) < x_k\ \forall k\}\right ).$$

If $x$ is irrational then $m \in \{n: \psi(n) < x_k\ \forall k\}$ implies that $\psi(m) < x$ and if $\psi(m) < x$ then $\psi(m) < x_k$ for all $k$ so $\{n: \psi(n) < x_k\ \forall k\} = B(x)$ and $H(x_k) \to H(x)$ from the right. If $x$ is rational then $x= \psi(q)$ for some
$q \in \mathbb{N}.$ Thus $x < x_k \forall k$ implies that $\{n: \psi(n) < x_k\ \forall k\} = B(x) + \{q\} = D$. It follows that $\nu(D) = \nu(B(x)) + 2^{-q} > H(x)$. So $H(x_k) \to H(x) + 2^{-q} \neq H(x)$ from the right, and so $H$ is not right continuous at the rationals.

We have thus shown that for any $x \in [0,1] \setminus \mathbb{Q}$, any sequence $x_k \to x$ has the property $\lim H(x_k) = x$ from the left and the right, and if $x \in [0,1] \cap \mathbb{Q}$ then if $x_k \to x$, $\lim H(x_k)$ does not exist. Therefore $H$ is continuous at every irrational and discontinuous at every rational.