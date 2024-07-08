Def:
For en [[Rekker|rekke]] $\sum\limits_{n=1}^{\infty}a_n$ hvor $a_n$ ikke er null fra et visst punkt, bestemmes [[Konvergens av rekker x|konvergensen]] av rekken ved å betrakte [[Grenseverdier x|grenseverdien]] av forholdet mellom etterfølgende termer:
$$\rho = \lim_{n \to \infty}\left| \frac{a_{n+1}}{a_n} \right|$$
## Konvergenskriterier
Forholdstesten gir oss følgende kriterier for å bestemme konvergensen av en rekke:

1. Hvis $\rho < 1$, konvergerer rekken absolutt.
2. Hvis $\rho > 1$ eller $L$ er uendelig, divergerer rekken.
3. Hvis $\rho = 1$, er testen inkonklusiv, og rekken kan konvergere eller divergere.
##### Eksempel
La oss betrakte rekken:

$$\sum_{n=1}^{\infty}\frac{2^n}{n!}$$
For å bruke forholdstesten, ser vi på forholdet mellom etterfølgende termer:

$$\rho = \lim_{n \to \infty}\left| \frac{\frac{2^{n+1}}{(n+1)!}}{\frac{2^n}{n!}} \right| = \lim_{n \to \infty}\left| \frac{2}{n+1} \right| = 0$$
Siden $\rho < 1$, konvergerer rekken absolutt ifølge forholdstesten.
