Def:
Delvis integrasjon er basert på produktregelen for [[Regneregler for derivasjon x|derivasjon]] og brukes når integrasjonen av produktet direkte er komplisert eller umulig. For to [[Funksjoner|funksjoner]]  $u(x)$ og $v(x)$, er formelen for delvis integrasjon gitt ved:
$$ \int u(x) \, dv(x) = u(x)v(x) - \int v(x) \, du(x) $$Formelen sier at integralet av produktet av $u$ og $dv$ er lik produktet av $u$ og $v$ minus integralet av produktet av $v$ og $du$. For å bruke delvis integrasjon, velger man $u(x)$ og $dv(x)$ slik at $du(x)$ og $v(x)$ er enklere å håndtere.

Eksempel:
La oss integrere $I = \int x e^x \, dx$ ved hjelp av delvis integrasjon.

1. Velg $u(x) = x$ og $dv(x) = e^x \, dx$. Da er $du(x) = dx$ og $v(x) = e^x$.
2. Sett inn i formelen for delvis integrasjon:
$$ I = x e^x - \int e^x \, dx $$
3. Løs integralet:
$$ I = x e^x - e^x + C $$

Her er $C$ integrasjonskonstanten. Resultatet av det opprinnelige integralet er $I = x e^x - e^x + C$.