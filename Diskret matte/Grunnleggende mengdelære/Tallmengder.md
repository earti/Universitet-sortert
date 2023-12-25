Def:
$\mathbb{N}$ er [[Mengde|mengden]] av naturlige heltall (eng. natural numbers)
$\mathbb{Z}$ er [[Mengde|mengden]] av heltall (eng. integers)
$\mathbb{Q}$ er [[Mengde|mengden]] av rasjonale tall (eng. rational numbers)
$\mathbb{R}$ er [[Mengde|mengden]] av reelle tall (eng. real numbers)

###### Naturlige tall [[Induktivt definerte mengder|induktivt definert]]
$\bullet\quad$ $0\in \mathbb{N}$
$\bullet\quad$ $x\in\mathbb{N}\Rightarrow x+1\in\mathbb{N}$

###### Tall som mengder
La $\mathcal{O}$ være den minste mengden slik at $\emptyset\in \mathcal{O}$ og hvis $X\in \mathcal{O}$ så $X\cup\{X\}\in \mathcal{O}$. her er de minste, ikke-tomme elementene i $\mathcal{O}$:
$\begin{array}{rll}\emptyset&\cup&\{\emptyset\}   &=& \{\emptyset\}\in\mathcal{O}\\\{\emptyset\}&\cup&\{\{\emptyset\}\} &=&\{\emptyset,\{\emptyset\}\}\in\mathcal{O}\\\{\emptyset,\{\emptyset\}\}&\cup&\{\{\emptyset,\{\emptyset\}\}\}  &=& \{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\}\}\}\in\mathcal{O}\\\{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\}\}&\cup&\{\{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\}\}\}\}  &=& \{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\},\{\emptyset,\{\emptyset\}\}\}\}\in\mathcal{O}\end{array}$
Dette er tullete uoversiktlig og vanskelig å lese! La oss innføre noen forkortelser: $0$ står for $\emptyset$ og $1$ for $\{0\}$. Da sier det at det øverste punktet at $1\in\mathcal{O}.$ Vi lar $2$ stå for $\{0,1\}$. Vi ser da et mønster. Hver gang vi får et nytt element i $\mathcal{O}$, er dette mengden av alle de foregående elementene:

$\begin{array}{rll}\emptyset&\cup&\{0\}   &=& \{0\}&=&1\in\mathcal{O}\\\{0\}&\cup&\{1\} &=&\{0,1\}&=&2\in\mathcal{O}\\\{0,1\}&\cup&\{2\}  &=&\{0,1,2\}&=& 3\in\mathcal{O}\\\{0,1,2\}&\cup&\{3\}  &=& \{0,1,2,3\}&=& 4\in\mathcal{O}\end{array}$

Dette er en mengdeteoretisk måte å definere de naturlige tallene på. Ved å begynne med den tomme mengden kan vi definere de naturlige tallene. Mengder på denne formen kalles ordinaltall (eng. ordinal numbers) og er en viktig del av mengdelæren.