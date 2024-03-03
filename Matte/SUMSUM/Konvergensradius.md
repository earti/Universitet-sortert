Def:
For en gitt [[Potensrekker x|potensrekke]] $\sum\limits_{n=0}^{\infty} a_n (x - c)^n$, er konvergensradius $R$ definert som:
$$R = \frac{1}{\limsup\limits_{n\to\infty} \sqrt[n]{|a_n|}}$$
hvor $\limsup$ betegner [[Grenseverdier x|grenseverdien]] for det største leddet når $n$ går mot uendelig.

Konvergensradius gir oss intervallet for hvilke $x$-verdier potensrekken konvergerer. Hvis $R$ er konvergensradiusen, vil rekken konvergere for alle $x$ slik at $|x - c| < R$. Den vil divergere for alle $x$ slik at $|x - c| > R$. For $|x - c| = R$ kan rekken enten konvergere, divergere eller begge deler, avhengig av de spesifikke verdiene av $a_n$.

##### Eksempel
La oss se på potensrekken $\sum\limits_{n=0}^{\infty} \frac{(x - 1)^n}{n!}$. Her er $a_n = \frac{1}{n!}$, så vi kan beregne konvergensradiusen som:
$$R = \frac{1}{\limsup\limits_{n\to\infty} \sqrt[n]{\frac{1}{n!}}}$$Siden $\limsup_{n\to\infty} \sqrt[n]{\frac{1}{n!}} = 0$, får vi at $R = \infty$. Dette betyr at potensrekken konvergerer for alle reelle tall $x$.
