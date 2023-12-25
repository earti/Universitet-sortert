Notasjon:
$\cases{x \equiv a \mod m\\ x \equiv b \mod n}$

Siden vi antar at $m \perp n$, vet vi fra tidligere at det finnes heltall $u$ og $v$ slik at $mu + nv = 1$.

$\begin{aligned}mu \equiv 0 \mod m\qquad nv&\equiv 1 \mod m\\ mu \equiv 1 \mod n\;\qquad nv&\equiv 0 \mod n\end{aligned}$

La $c$ være følgende tall $c = anv + bmu$. Da er $c$ en løsning av systemet, siden vi har
$\begin{aligned}c = anv + bmu &\equiv a \cdot 1 + b \cdot 0 = a \mod m\\ c = anv + bmu &\equiv a \cdot 0 + b \cdot 1 = b \mod n\end{aligned}$

Fra [[Parvis primiske likinger|parvis primiske likninger]] kan vi hente en formel or vilkårlige mange likninger:
$x \equiv \sum\limits_{i=1}^r  a_iM_ik_i \mod M$