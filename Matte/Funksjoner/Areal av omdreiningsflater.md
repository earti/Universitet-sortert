Def:
Areal av en omdreiningsflate er arealet av en flate som oppstår når en kurve roteres rundt en akse. For en kurve beskrevet av [[Funksjoner|funksjonen]] $y = f(x)$, som roteres rundt $x$-aksen mellom $a$ og $b$, er arealet av omdreiningsflaten gitt ved integralformelen:
$$ A = 2\pi \int_{a}^{b} y \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx $$
Og omdreiningsflaten rundt $y$-aksen er gitt ved:
$$ A = 2\pi \int_{a}^{b} |x| \sqrt{1 + \left(\frac{dy}{dx}\right)^2} \, dx $$
Formelen tar utgangspunkt i at hvert lille segment av kurven, når det roteres, danner en "ring" eller "skive" med en liten overflate. Lengden av kurven (beregnet ved hjelp av pytagoreisk teorem for å inkludere kurvens helning) multipliseres med omkretsen av ringen ($2\pi y$) for å finne overflatearealet av hvert segment. Integralet summerer så disse små arealene over det gitte intervallet.

Eksempel:
La oss finne arealet av omdreiningsflaten som oppstår når kurven $y = \sqrt{x}$ roteres rundt x-aksen fra $x = 0$ til $x = 1$.

1. Først finner vi derivasjonen av $y$ med hensyn på $x$: $\frac{dy}{dx} = \frac{1}{2\sqrt{x}}$.
2. Deretter setter vi inn i formelen for arealet:
$$ A = 2\pi \int_{0}^{1} \sqrt{x} \sqrt{1 + \left(\frac{1}{2\sqrt{x}}\right)^2} \, dx $$
3. Forenkle uttrykket under rottegnet og løs integralet for å finne arealet.
