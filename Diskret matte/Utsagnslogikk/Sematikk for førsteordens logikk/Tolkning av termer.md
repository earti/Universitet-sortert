
> [!abstract] %%Oppsummering%%
La et [[Førsteordens språk|førsteordens språk]] være gitt, og la $\mathcal{M}$ være en [[Modell|modell]] for dette språket. Da tolker vi en [[Lukket term|lukket term]] $f(t_{1},\ldots,t_{n})$ som $f(t_{1},\ldots,t_{n})^{\mathcal{M}}=f^{\mathcal{M}}(t_{1}^{\mathcal{M}},\ldots,t_{n}^{\mathcal{M}})$.

Dette er et eksempel på en [[Rekursivt definert funksjon|rekursivt definert funksjon]]. Modellen $\mathcal{M}$ gir en tolkning av konstant- og funksjonssymboler, og dette er basistilfellet for rekursjonen.


> [!example] %%Eksempel%%
> La $\mathcal{M}$ være en modell med domene $\{0,1,2,3,4\}$ slik at:
> $\bullet\quad$ Konstantsymbolet $a$ tolkes som $3$, og vi skriver $a^{\mathcal{M}}=3$.
> $\bullet\quad$ Konstantsymbolet $b$ tolkes som $4$, og vi skriver $b^{\mathcal{M}}=4$.
> $\bullet\quad$ Funksjonssymbolet $f$ med aritet én tolkes som en [[Funksjoner|funksjon]] på $\{0,1,2,3,4\}$, som gir $0$ hvis argumentet er partall og $1$ hvis argumentet er oddetall.
> $$f(a)^{\mathcal{M}}=1$$
> $$f(b)^{\mathcal{M}}=0$$

Dette er fordi $f(a)^{\mathcal{M}}=f^{\mathcal{M}}(a^{\mathcal{M}})=f^{\mathcal{M}}(3)=1$. $f(b)^{\mathcal{M}}=f^{\mathcal{M}}(b^{\mathcal{M}})=f^{\mathcal{M}}(4)=0$.


> [!quote] %%Referanser%%
> Antonsen, Roger. *Logiske metoder*. Universitetsforlaget, 2014. 



