
> [!abstract] %%Oppsummering%%
> 

> [!example] %%Eksempel%%
> 

> [!quote] %%Referanser%%
>


Gram-Schmidt-prosessen er en metode i lineær algebra for å ortogonalisere et sett med vektorer i et indre produktrom, vanligvis det euklidske rommet R^n. Dette resulterer i et ortogonalt sett av vektorer. Hvis disse vektorene deretter normaliseres, blir resultatet et ortonormalt sett.

Formel: Gitt et sett med vektorer {v1, v2, ..., vn}, kan vi beregne et ortogonalt sett {u1, u2, ..., un} ved hjelp av følgende formel:
u1 = v1
u2 = v2 - proj(u1, v2)
u3 = v3 - proj(u1, v3) - proj(u2, v3)
...
un = vn - proj(u1, vn) - proj(u2, vn) - ... - proj(un-1, vn)

Her er proj(u, v) projeksjonen av v på u, som er gitt ved (u • v) / ||u||^2 * u, der • indikerer indre produkt og ||u|| er lengden av u.

Gram-Schmidt-prosessen er en grunnleggende teknikk i lineær algebra som brukes i mange forskjellige områder, inkludert numerisk lineær algebra, statistikk og kvantemekanikk.

Eksempel: La oss si at vi har vektorene v1 = [1, 0] og v2 = [1, 1] i R^2. Ved å bruke Gram-Schmidt-prosessen, kan vi beregne u1 = v1 = [1, 0] og u2 = v2 - proj(u1, v2) = [1, 1] - [1, 0] = [0, 1], som gir oss et ortogonalt sett {u1, u2}.