Notasjon:
$$\sum_{n=1}^{\infty}a_n$$
Def:
En rekke er en uendelig sum av tall eller [[Funksjoner|funksjoner]], hvor $a_n$ representerer det n-te leddet i [[Følger|følgen]].

## Konvergens og Divergens
[[Konvergens av rekker x|Konvergens]] av en rekke betyr at summen av dens ledd nærmer seg en bestemt [[Grenseverdier x|grenseverdi]] når antall ledd går mot uendelig. Divergens betyr at summen ikke nærmer seg noen spesifikk verdi.

##### Kriterier for Konvergens

1. **n-te ledds test:** Hvis $\lim_{n \to \infty}a_n \neq 0$, divergerer rekken.
2. **Integraltesten:** Hvis $\int_{1}^{\infty} f(x) dx$ konvergerer, da gjør også $\sum_{n=1}^{\infty}f(n)$ det, gitt at $f(x)$ er positiv, kontinuerlig og avtagende.
3. **Sammenligningstesten:** En rekke konvergerer hvis den er mindre enn en annen kjent konvergent rekke ledd for ledd.
4. **[[Forholdstesten|Forholdstesten:]]** Hvis $\lim_{n \to \infty} |a_{n+1}/a_n| < 1$, konvergerer rekken absolutt.
5. **Rot-testen:** Hvis $\lim_{n \to \infty} \sqrt[n]{|a_n|} < 1$, konvergerer rekken absolutt.
6. **[[Alternerende rekke|Alternerende Rekketest:]]** En rekke av formen $\sum_{n=1}^{\infty}(-1)^{n+1}a_n$ konvergerer hvis $a_n$ er avtagende og $\lim_{n \to \infty}a_n = 0$.

##### Typer Rekker

- **Geometriske Rekker:** En rekke hvor forholdet mellom etterfølgende ledd er konstant.
- **Harmoniske Rekker:** En rekke av formen $\sum_{n=1}^{\infty}\frac{1}{n}$, som divergerer.
- **[[Alternerende rekke|Alternerende Rekker:]]** Rekker hvor fortegnene til leddene veksler mellom positivt og negativt.
- **[[Potensrekker x|Potensrekker:]]** Rekker som representerer en funksjon som en sum av potenser av en variabel.
