
> [!abstract] %%Oppsummering%%
> 1. Start med det første elementet: Anta at det første elementet i listen allerede er sortert.
> 2. Ta det neste elementet: Velg det neste elementet i listen og sammenlign det med elementene i den sorterte delen.
> 3. Flytt elementer: Flytt elementene i den sorterte delen som er større enn det valgte elementet ett sted til høyre.
> 4. Sett inn elementet: Flytt elementer mot høyre til det valgte elementet på riktig plass i den sorterte delen.
> 5. Gjenta: Gjenta trinn 2-4 for hvert av de gjenværende usorterte elementene.

> [!warning] %%Begrensninger%%

``` python
i = 1
while i < length(A):
    j = i
    while j > 0 and A[j-1] > A[j]:
        temp = A[j]
        A[j] = A[j-1]
        A[j-1] = temp
        j = j - 1
    i = i + 1
```

> [!info] %%Kjøretid og annen info%%
> Tidskompleksitet: 
> $\bullet\quad$ Best case: O(n)
> $\bullet\quad$ Average case: O(n^2)
> $\bullet\quad$ Worst case: O(n^2)
> Plasskompleksitet: O(1)
> Stabilitet: Stabil

> [!success] %%Fordeler%%
> $\bullet\quad$ Enkel implementasjon
> $\bullet\quad$ [[Online|Online]]
> $\bullet\quad$ [[Stabil|Stabil]]
> $\bullet\quad$ [[På-stedet|På-stedet]]

> [!failure] %%Ulemper%%