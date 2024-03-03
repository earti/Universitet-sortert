Def:
En [[Tallmengder|rasjonell]] [[Funksjoner|funksjon]] på formen $R(x) = P(x)/Q(x)$, hvor $P$ og $Q$ er polynomer, hvor graden til $P$ er mindre enn graden til $Q$. Funksjonen kan dekomponeres i delbrøker på formen:
$$
R(x) = \frac{A_1}{(x-a_1)^{n_1}} + \frac{A_2}{(x-a_2)^{n_2}} + \ldots + \frac{A_k}{(x-a_k)^{n_k}}
$$
hvor $A_i$ er konstanter, $a_i$ er de forskjellige nullpunktene til $Q(x)$, og $n_i$ er multiplisiteten til hvert nullpunkt. 
##### Eksempel
La oss ta et eksempel: $R(x) = \frac{4}{x^2 - 1}$

1. Faktoriser nevneren: $x^2 - 1 = (x - 1)(x + 1)$
2. Sett opp delbrøkene: $\frac{4}{x^2 - 1} = \frac{A}{x - 1} + \frac{B}{x + 1}$
3. Løs for $A$ og $B$: Ved å sammenligne koeffisientene, finner vi at $A = 2$ og $B = -2$
4. Skriv den forenklede brøken: Dermed blir $\frac{4}{x^2 - 1} = \frac{2}{x - 1} - \frac{2}{x + 1}$

Delbrøksoppspaltning er en nyttig teknikk for å forenkle komplekse rasjonale funksjoner, spesielt i beregninger som involverer integrasjon eller Laplace-transformasjoner.