
> [!abstract] %%Oppsummering%%
Anta at et [[Førsteordens språk|førsteordens språk]] er gitt. [[Mengde|Mengden]] av førsteordens formler (eng.first-order formulas), eller bare formler (eng. formulas), er den minste mengden slik at:
$\bullet\quad$ Alle atomære formler er formler
$\bullet\quad$ Hvis $\varphi$ og $\psi$ er formler, er $\neg\varphi$, $(\varphi\wedge\psi)$, $(\varphi\vee\psi)$ og $(\varphi\to\psi)$ formler
$\bullet\quad$ Hvis $\varphi$ er en formel og $x$ er en variabel, er $\forall x\varphi$ og $\exists x\varphi$ formler

Alle forekomster av en variabel $x$ i $\varphi$ sies å være bundet (eng. bound) i formlene $\forall x\varphi$ og $\exists x\varphi$ og innenfor skopet (eng. scope) til den gjeldende kvantoren.


> [!example] %%Eksempel%%
> Noen sammensatte førsteordens formler i det enkle språket:
> 
> $Pa\wedge Px$        		$P$ er sann for $a$ og $x$                                             
$\exists xPx$               	Det finnes en $x$ slik at $Px$                                         
$\forall xPx$               	For alle $x$ er det slik at $Px$                                       
$\neg Rax$      				$a$ er ikke relatert til $x$                                           
$\forall x\forall yRxy$     		Relasjonen er universell/Alt er relatert til hverandre                 
$\exists x\exists yRxy$     		Relasjonen er ikke tom/Noe er relatert til noe annet                
$\neg\exists x\exists yRxy$ 			Relasjonen er tom/Ingenting er relatert                                
$\exists x\forall yRxy$     		Det finnes et element som er relatert til alle elementer      
$\forall x\exists yRxy$     		For alle elementer finnes det et element det er relatert til  
$\exists xRxx$     			Det finnes et element som er relatert til seg selv           
$\forall x(Px\to Rxx)$	Hvis $P$ er sann for et element, så er elementet relatert til seg selv 
$\forall x(Rxx\to Px)$	$P$ er sann for alle elementer som er relatert til seg selv.            

Velkjente egenskaper ved [[Relasjon|relasjoner]]:
$R$ er [[Refleksivitet|refleksiv]]     		$\forall xRxx$
$R$ er [[Diskret matte/Relasjoner/Symmetri|symmetrisk]] 		$\forall x\forall y(Rxy\to Ryx)$
$R$ er [[Transitivitet|transitiv]]			$\forall x\forall y\forall z(Rxy\wedge Ryz\to Rxz)$
$R$ er [[Irrefleksivitet|irrefleksiv]]			$\forall x\neg Rxx$
$R$ er asymmetrisk	$\forall x \forall y(Rxy\to \neg Ryx)$

[[Anti-symmetri|Anti-symmetri]] kan ikke beskrives fordi $=$ ikke er med:
$\forall x\forall y(Rxy \to Ryx \to x = y)$


> [!quote] %%Referanser%%
Antonsen, Roger. *Logiske metoder*. Universitetsforlaget, 2014.