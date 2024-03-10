
> [!abstract] %%Oppsummering%%
Et bevis (eng. proof) for en [[Formodninger|påstand]] fra en [[Mengde|mengde]] gitte antakelser er en rekke logiske beslutninger som viser hvordan vi kommer fra antakelsene til påstanden. For hvert steg må konklusjonen være en [[Logisk konsekvens|logisk konsekvens]] av antakelsene.

Et bevis starter med kjente fakta, som aksiomer og tidligere beviste setninger, og bruker disse til å vise at en ny påstand er [[Sannhetsverdier og sannhetsverditabell|sann]]. Bevis kan være direkte (hvor vi viser at påstanden følger direkte fra de kjente fakta), indirekte (hvor vi antar at påstanden er usann og viser at dette fører til en kontradiksjon), eller konstruktive (hvor vi faktisk bygger et eksempel som viser at påstanden er sann). 


> [!example] %%Eksempel%%
$$\sum\limits_{i=0}^{n}i = \frac{n(n+1)}{2}$$

Vi kan bevise dette ved [[Matematisk induksjon|induksjon]]. 
1. For $n=1$, er påstanden sann, fordi $\frac{1\cdot1+1}{2} = 1$. 
2. Anta at påstanden er sann for $n=k$. Da er summen av de første $k$ tallene $\frac{k\cdot(k+1)}{2}$. 
3. Hvis vi legger til det neste tallet, $k+1$, blir summen $\frac{k\cdot(k+1)}{2} + k+1 = \frac{(k+1)\cdot(k+2)}{2}$. 
Dermed er påstanden også sann for $n=k+1$. Så ved induksjon, er påstanden sann for alle naturlige tall $n$.


> [!quote] %%Referanser%%
Antonsen, Roger. *Logiske metoder*. Universitetsforlaget, 2014.
