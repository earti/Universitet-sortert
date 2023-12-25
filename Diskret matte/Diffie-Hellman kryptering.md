Alice og Bob blir enige om noen offentlige parametre som alle får tilgang til: 
$\bullet\quad$ [[Primtall|primtallet]] $q$ 
$\bullet\quad$ basen $g$

Alice og Bob trekker hver sitt tilfeldige tall $a$ og $b$ i $[2, q − 2]$ (om vi velger $0$ så er $g^0 = 1$, velger $1$ så er $g^1 = g$ og velger $q − 1$ så er $g^{q−1} = 1 \mod q$). 
Alice og Bob ender opp med en delt nøkkel $k = g^{a\cdot b} \mod q$.

Det vanskelig for Eva å finne $a$ dersom Alice publiserer $A = g^a \mod q$. Tilsvarende er det vanskelig for Eva å finne $b$ i $B = g^b \mod q$. Alice og Bob sender $A$ og $B$ til hverandre, og kan enkelt beregne den delte nøkkelen uten å lære den andre sin hemmelige potens $k = g^{a\cdot b} = A^b = B^a \mod q$. Men Eva må vite $a$ eller $b$ for å kunne beregne $k$, fordi det er ikke mulig å beregne $k$ fra kun $A$ og $B$ alene.

Når Alice og Bob har blitt enige om $k$ så kan de bruke denne nøkkelen til å kryptere meldinger ved å bruke symmetrisk kryptografi.

