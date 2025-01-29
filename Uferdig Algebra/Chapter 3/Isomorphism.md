
> [!abstract] %%Oppsummering%%
> Let $\langle S,\ast\rangle$ and $\langle S',\ast'\rangle$ be binary algebraic structures. An isomorphism of $S$ with $S'$ is a [[Bijektiv|one-to-one function]] $\phi$ mapping $S$ onto $S'$ such that $\phi(x \ast y) = \phi(x)\ast\phi(y)$ for all $x, y \in S$. This is the homomorphism property. If such a map $\phi$ exists, then $S$ and $S'$ are isomorphic binary structures, which we denote by $S\simeq S'$,omitting the $\ast$ and $\ast'$ from the notation.

How to Show That Binary Structures Are Isomorphic
1. Define the function $\phi$ that gives the isomorphism of $S$ with $S'$. Now this means that we have to describe, in some fashion, what $\phi(s)$ is to be for every $s \in S$. 
2. Show that $\phi$ is a one-to-one function. That is, suppose that $\phi(x) = \phi(y)$ in $S$ and deduce from this that $x = y$ in $S$. 
3. Show that $\phi$ is onto $S$. That is, suppose that $s \in S$ is given and show that there does exist $s \in S$ such that $\phi(s) = s$.
4. Showthat $\phi(x \ast y) = \phi(x)\ast\phi(y)$ for all $x, y \in S$. This is just a question of computation. Compute both sides of the equation and see whether they are the same.

> [!example] %%Eksempel%%
> Let us show that the binary structure $\langle \mathbb{R},+\rangle$ with operation the usual addition is isomorphic to the structure $\langle \mathbb{R}^{+},\cdot\rangle$ where $\cdot$ is the usual multiplication.

1. We have to somehow convert an operation of addition to multiplication. Recall from $a^{b+c} = (a^{b})(a^{c})$ that addition of exponents corresponds to multiplication of two quantities. Thus we try defining $\phi : \mathbb{R} \to \mathbb{R}^{+}$ by $\phi(x) = e^{x}$ for $x \in \mathbb{R}$. Note that $e^{x} > 0$ for all $x \in \mathbb{R}$, so indeed, $\phi(x) \in \mathbb{R}^{+}$. 
2. If $\phi(x) = \phi(y)$, then $e^{x} = e^{y}$. Taking the natural logarithm, we see that $x = y$, so $\phi$ is indeed one to one. 
3. If $r \in \mathbb{R}^{+}$, then $\ln(r) \in \mathbb{R}$ and $\phi(\ln r) = e^{\ln r} = r$. Thus $\phi$ is onto $\mathbb{R}^{+}$. 
4. For $x,y \in\mathbb{R}$, we have $\phi(x + y) = e^{x+y} = e^{x} \cdot e^{y} = \phi(x)\cdot\phi(y)$. Thus we see that $\phi$ is indeed an isomorphism.

> [!quote] %%Referanser%%
> Fraleigh, John B. _A First Course in Abstract Algebra_. 7th ed., Pearson, 2003.



