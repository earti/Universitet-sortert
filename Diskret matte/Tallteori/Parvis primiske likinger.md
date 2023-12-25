Def:
La $n_1, n_2, \ldots , n_r$ være en liste med [[Tallmengder|tall]]. Vi sier at disse tallene er parvis [[Relativt primiske tall|relativt primiske]] dersom $n_i$ er relativt primisk til $n_j$ for alle $i \neq j$.

La $m_1, m_2,\ldots, m_r$ være naturlige tall som er parvis relativt primiske, og la $M = m_1 \cdot m_2 \ldots m_r.$ For alle heltall $a$ og $b$ har vi at 

$a \equiv b \mod M \Longleftrightarrow\cases{ a \equiv b \mod m_1\\ a \equiv b \mod m_2\\ \vdots \\ a \equiv b \mod m_r}$ 

Siden $m_i\mid M$ og $M\mid (a − b)$, gir det at $m_i\mid(a − b)$

##### [[Det kinesiske restteoremet]] med vilkårlig mange likninger:

$\cases{ x \equiv a_1 \mod m_1\\ x \equiv a_2 \mod m_2\\ \vdots \\ x \equiv a_r \mod m_r}$

Vi kan finne løsningen av systemet på følgende måte. For hver $i \in {1, 2, . . . , r}$: La $M_i = M/m_i$, og la $k_i$ være en invers til $M_i$ modulo $m_i$. Løsningen av systemet er da gitt ved: $x \equiv \sum\limits_{i=1}^r  a_iM_ik_i \mod M$.