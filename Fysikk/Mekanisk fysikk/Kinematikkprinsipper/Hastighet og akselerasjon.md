
> [!abstract] %%Oppsummering%%
> Hastighet er endring i [[Koordinatsystem|posisjon]] per tidsenhet, og akselerasjon er endringen i hastighet per tidsenhet. For å finne momentan hastighet og akselerasjon bruker vi [[Definisjon av den deriverte|derivasjon]], hvor $v=\dot{r}$ og $a=\dot{v}=\ddot{r}$ :
> $$\vec{v}=\frac{d\vec{r}}{dt},\qquad\vec{a}=\frac{d\vec{v}}{dt}=\frac{d^2\vec{r}}{dt^2}$$

Gjennomsnittlig hastighet er $v=\frac{\Delta x}{\Delta t}$, hvor $\Delta x$ er en lengde på en akse, og $\Delta t$ er tidsendringen. Gjennomsnittlig akselerasjon er $a=\frac{\Delta v}{\Delta t}$, hvor $\Delta v$ er fartsendringen, og $\Delta t$ er tidsendringen. 

> [!example] %%Eksempel%%
> 

> [!quote] %%Referanser%%


You wish to tour the world and explore its rich history. However, you have a very strong compulsory thought. You need your information in chronological order. Thus, if you are to visit two places A and B where part of these two locations history partake in the same event, you need to visit the places in the same order as they occured. Thus, if you are visiting to locations where major battles in world war 2 occured, where location A's battle occurred before location B's, you must visit A before B. It is safe to assume there are no cyclic dependencies.

Along your tour, there are N major locations you must visit, and your job is to figure out how many other locations you must visit to be able to reach these N places, to see if you can visit any more.

**Input Format**

First you get two integers N and M, where N is the number of locations you want to visit and M are the number of dependencies. Then follows  lines of input, each of which is a place you want to visit Finally, it follows N lines of input of the form A B  which indicate that if you want to visit A, you must visit B first.

Integer S, the number of sites you must visit, including the N locations you wanted to visit.