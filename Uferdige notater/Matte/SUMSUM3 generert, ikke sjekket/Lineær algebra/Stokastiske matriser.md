
> [!abstract] %%Oppsummering%%
> 

> [!example] %%Eksempel%%
> 

> [!quote] %%Referanser%%
>


Regulært stokastiske

En stokastisk matrise, også kjent som en sannsynlighetsmatrise, er en matrise som brukes til å beskrive overgangene i en Markov-kjede. Hver rad i en stokastisk matrise representerer en sannsynlighetsfordeling, slik at alle elementene i raden er ikke-negative og summerer til 1.

Formel: En stokastisk matrise P er en kvadratisk matrise der hver rad p_i (for i = 1, 2, ..., n) er en sannsynlighetsvektor. Det vil si:

P = [p_1, p_2, ..., p_n]

hvor sum(p_ij) = 1 for alle i.

Stokastiske matriser er sentrale i studiet av stokastiske prosesser, spesielt Markov-kjeder.

Eksempel: En stokastisk matrise som representerer overgangene i en Markov-kjede med tre tilstander kan være:

P = [[0.7, 0.2, 0.1],
     [0.3, 0.4, 0.3],
     [0.2, 0.2, 0.6]]

Her representerer hver rad sannsynlighetsfordelingen for overgangene fra en tilstand til de andre. For eksempel, fra den første tilstanden er det 70% sannsynlighet for å forbli i samme tilstand, 20% sannsynlighet for å gå til den andre tilstanden, og 10% sannsynlighet for å gå til den tredje tilstanden.