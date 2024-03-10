Def:
En tilordning av [[Sannhetsverdier og sannhetsverditabell|sannhetsverdier]] til alle [[Utsagnslogiske formler fix plz|utsagnslogiske formler]] som er slik at [[Tolkning av utsagnslogiske formler|disse]] tabellene overholdes, kalles en valuasjon (eng. valuation).

###### [[Rekursivt definert funksjon|Rekursiv def]]:
La $t$ være en tilordning av sannhetsverdier til [[Utsagnsvariabel|utsagnsvariabler]], det vil si en [[Funksjoner|funksjon]] fra [[Mengde|mengden]] av utsagnsvariabler til $\{0,1\}$. En valuasjon kan nå defineres rekursivt som funksjonen $v$ fra utsagnslogiske formler til $\{0,1\}$ på følgende måte:
$\bullet\quad$ $v(P)=1$ hviss $t(P)=1$, for alle utsagnsvariabler $P$. Dette er basistilfellet i definisjonen.
$\bullet\quad$ $v(\neg F)=1$ hviss $v(F)=0$ 
$\bullet\quad$ $v(F\wedge G)=1$ hviss $v(F)=1$ og $v(G)=1$ 
$\bullet\quad$ $v(F\vee G)=1$ hviss $v(F)=1$ eller $v(G)=1$ 
$\bullet\quad$ $v(F\to G)=1$ hviss $v(F)=1$ impliserer $v(G)=1$ 

Disse fire punktene utgjør rekursjonssteget i definisjonen.

> [!quote] %%Referanser%%
Antonsen, Roger. *Logiske metoder*. Universitetsforlaget, 2014.