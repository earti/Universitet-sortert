Let $G$ be a [[Group|group]] of [[Order of groups|order]] $p_{n}$ and let $X$ be a finite $G$-set. Then $|X|\equiv |X_{G}|\mod p$.
(Cauchy’s Theorem) Let $p$ be a [[Primtall|prime]]. Let $G$ be a finite [[Group|group]] and let $p$ divide $|G|$. Then $G$ has an element of [[Order of groups|order]] $p$ and, consequently, a [[Subgroup|subgroup]] of order $p$. 
(First Sylow Theorem) Let $G$ be a finite [[Group|group]] and let $|G|=p^{n}m$ where $n \geq 1$ and where $p$ does not divide $m$. Then 
1. $G$ contains a [[Subgroup|subgroup]] of [[Order of groups|order]] $p^{i}$ for each $i$ where $1 \leq i \leq n$,
2. Every subgroup $H$ of $G$ of order $p^{i}$ is a [[Normal|normal]] subgroup of a subgroup of order $p^{i+1}$ for $1 \leq i < n$.
(Second Sylow Theorem) Let $P_{1}$ and $P_{2}$ be [[Sylow p-subgroup|Sylow p-subgroups]] of a finite group $G$. Then $P_{1}$ and $P_{2}$ are [[Automorphism and conjugation|conjugate]] subgroups of $G$.
(Third Sylow Theorem) If $G$ is a finite [[Group|group]] and $p$ divides $|G|$, then the number of Sylow $p$-[[Subgroup|subgroups]] is congruent to $1$ modulo $p$ and divides $|G|$.

$$\begin{align}U^{(1)} &= U^n +
    \tau\bigl(  \mathbf{L}U^{(1)} +  \mathbf{N}(U^n)
    \bigr)\\
    U^{(2)} &= \alpha_{10} U^n + \alpha_{11} U^{(1)} +
    \beta_1 \tau\bigl(  \mathbf{L}U^{(2)} +  \mathbf{N}(U^{(1)})
    \bigr)\\
    
    U^{n+1} &= \alpha_{20} U^n + \alpha_{21} U^{(1)} + \alpha_{22} U^{(2)}
    +\beta_2 \tau\bigl(  \mathbf{L}U^{n+1} +  \mathbf{N}(U^{(2)})
    \bigr)
\end{align}$$

$U^{(1)}=U^{n} + \tau\left( \mathbf{L} U^{(1)}+ \mathbf{N}(U^{n})\right)$
$U^{(1)}=U^{n} + \tau \mathbf{L} U^{(1)}+ \tau \mathbf{N}(U^{n})$
$U^{(1)} - \tau \mathbf{L} U^{(1)}=U^{n} + \tau \mathbf{N}(U^{n})$

$\mathbf{L}$ er en lineæroperator, og vi kan skrive
$(1 - \tau \mathbf{L}) U^{(1)}=U^{n} + \tau \mathbf{N}(U^{n})$
$U^{(1)}=(1 - \tau \mathbf{L})^{-1}(U^{n} + \tau \mathbf{N}(U^{n}))$


$U^{(2)} = \alpha_{10} U^n + \alpha_{11} U^{(1)} +\beta_1 \tau\left(  \mathbf{L}U^{(2)} +  \mathbf{N}(U^{(1)})\right)$
$U^{(2)} = \alpha_{10} U^n + \alpha_{11} U^{(1)} +\beta_1 \tau  \mathbf{L}U^{(2)} + \beta_1\tau \mathbf{N}(U^{(1)})$
$U^{(2)}-\beta_1 \tau  \mathbf{L}U^{(2)} = \alpha_{10} U^n + \alpha_{11} U^{(1)} + \beta_1\tau \mathbf{N}(U^{(1)})$
$(1-\beta_1 \tau  \mathbf{L})U^{(2)} = \alpha_{10} U^n + \alpha_{11} U^{(1)} + \beta_1\tau \mathbf{N}(U^{(1)})$
$U^{(2)} =(1-\beta_1 \tau  \mathbf{L})^{-1}\left( \alpha_{10} U^n + \alpha_{11} U^{(1)} + \beta_1\tau \mathbf{N}(U^{(1)})\right)$


$U^{n+1} = \alpha_{20} U^{n} + \alpha_{21} U^{(1)} + \alpha_{22} U^{(2)}+\beta_2 \tau\left( \mathbf{L}U^{n+1} +  \mathbf{N}(U^{(2)})\right)$
$(1-\beta_2 \tau\mathbf{L})U^{n+1} = \alpha_{20} U^{n} + \alpha_{21} U^{(1)} + \alpha_{22} U^{(2)}+\beta_2 \tau  \mathbf{N}(U^{(2)})$
$U^{n+1} = (1-\beta_2 \tau\mathbf{L})^{-1}\left(\alpha_{20} U^{n} + \alpha_{21} U^{(1)} + \alpha_{22} U^{(2)}+\beta_2 \tau  \mathbf{N}(U^{(2)})\right)$

