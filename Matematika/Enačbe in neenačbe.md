<span style="color:#87f7ae">**Matematični izraz**</span>, zapis ki ga lahko sestavljajo števila, simboli, matematičnimi znaki in oklepaji, kjer so vsi smiselno postavljeni.

Enačba je zapis dveh matematičnih izrazov med katerega postavimo znak za enakost $(=)$.

Neenačba je zapis dveh matematičnih izrazov med katerega postavimo znak za neenakost $(\gt,\;\lt,\;\geq,\;\leq)$. 

[[Lastnosti Rel.&Op.|Lastnosti]] relacije $(\lt)$:
$$\text{Obračanje in ohranjanje neenačaja pri operacijah}$$$$\begin{align*}
a<b &\implies a+c<b+c \\
a < b \land c > 0 &\implies a \cdot c < b \cdot c \\
a < b \land c < 0 &\implies a \cdot c > b \cdot c \\
\end{align*}$$ ^e56e51



### Algebra

Algebrski izraz je zapis, ki vsebuje znake za operacije, oklepaje, števila in spremenljivke v smiselnem redu.

Algebrska enačba je enakost 2 algebrskih izrazov, kjer je ena od spremenljivk določena kot neznana količina oz. neznanka.

#### Linearna enačba
...je enačba oblike$$kx + n = 0\;;\; k,n\in \mathbb{R}$$
Rešitve so vse vrednosti, ki zadoščajo enačbi, teh pa je toliko, kot je spremenljivk. <span style="color:#87f7ae">Vse spremenljivke imajo eksponent $1$</span>.

Enačbi z isto rešitvijo sta ekvivalentni enačbi.

Preoblikovana enačba je ekvivalentna prvotni če:
- Na obeh straneh prištejemo enako število,
- Obe strani pomnožimo z istim številom

Delitev enačb glede na njihove rešitve
1. Identične enačbe: $R = \mathbb{R}$
2. Enačba brez rešitve: $R = \{\,\}$
3. Enačba, ki ima končno mnogo rešitev: $R = \{x\}$

Množica rešitev ($R$) je množica vseh števil, ki ustrezajo enačbi.

#### Linearna neenačba
... nastane, ko med izraze postavimo relacijo neenakosti

$$kx + n < 0$$

Dve neenačbi sta ekvivalentni če določata isto množico rešitev. Rešitve so [[Množice#Številska premica in intervali|intervali]].

[[#^e56e51|Ohranjanje in obračanje neenačaja]].

#### Razcepna enačba

... je če je izraz $A(x)$ razcepen in v njem nastopajo potence neznanke $x$, stopnje več kot 1. (Enakost z nič)$$A(x)=0$$ 
$$(x+1)(x-1)= 0\;;\; x+1=0\lor x-1=0$$
$$\color{green}a \cdot b = 0 \iff a=0\lor b=0$$

***Razcepna enačba ima največ toliko rešitev, kot je največja stopnja.***

#### Iracionalna enačba

... je enačba pri kateri nastopa neznanka [[Potenciranje & Korenjenje#Koreni|pod korenom.]]

Iracionalna enačba: $\sqrt[]{x} + 2=0$
Linearna enačba: $x + \sqrt[]{2} = 0$

Obvezna [[Obravnava enačb in neenačb#^06c374|obravnava]].
*Iracionalno enačbo smo obravnavali pred iracionalnimi števili.*

#### Kvadratna enačba

... je enačba oblike:
$$ax^{2}+ bx + c = 0; a \neq 0$$
[[Funckije#^576ff4|Ničle kvadratne funkcije & Diskriminanta]]

Št. rešitev oz. korenov lahko razberemo s pomočjo diskriminante:
- $D > 0 \implies 2$
- $D = 0 \implies 1$
- $D < 0 \implies 0 \;;\;$ oz. 2 kompleksni konjugirani rešitvi oz. korena. 

Ne pozabi [[Obravnava enačb in neenačb|obravnav]].

#### Kvadratna neenačba

$$
\begin{align*}
ax^{2}+ bx + c &< 0\\
&>\\
&\ge\\
&\le\\
\end{align*}
$$
Rešitve neenačb so ponavadi [[Množice#Številska premica in intervali|intervali]].

Take enačbe rešujemo s pomočjo skice [[Funckije#Kvadratna funkcija|grafa funkcije]].
[[Funckije#^0ed8e0|Vietovi formuli]]

Reševanje s premicami:
![[0023.png|320]]
$$x^{2}- 1 = (x+1)(x-1)$$
$$x_{1,2} = \pm \,1$$
$$k > 0\text{, zato je premica vzpenjajoča}$$
$$ $$
![[0024.png|380]]

$$- \cdot - \implies +$$
$$+ \cdot - \implies -$$
$$+ \cdot + \implies +$$
$$ $$
$$f(x)>0\;;\; x\in(-\infty,-1)\cap(1, \infty)$$

Sistemi neenačb npr.:
$$0 < x^{2}+ 2,$$
$$0 > x^{2} - 1;$$
rešimo tako, da poiščemo unijo $(x < x^{2}+ 2 \cup x > x^{2} - 1)$ .

#### Eksponentna enačba

... je enačba kjer spremenljivka nastopa v eksponentu.
$$a^{x}= 0$$

Reševanje:
1. Postavljanje na skupno osnovo
$$a^{f(x)}=a^{g(x)}\iff f(x) = g(x)\;;\; a > 0$$
2. Na skupno potenco
$$a^{f(x)}=b^{f(x)}\iff f(x) = 0$$
4. Grafično
5. Z [[Operacije#Logaritmiranje|logaritmiranjem]]

[[Funckije#Eksponentna funkcija|Eksponentna funkcija]]

#### Logaritemska enačba
[[Funckije#Logaritemska funkcija|Logaritmeska funkcija]]


... je enačba, ki ima neznanko v osnovi logaritma ali logaritmandu

$$\log_{\,n}{x} = 0\;;\;n > 0 \land x \ge 0$$

Reševanje:
1. Reševanje z definicijo logaritma
	$$\log_{\,2}{x} = 3$$
	$$x = 2^3=8$$
1. Antilogaritmiranje
	$$\log_{\,}{x} + \log_{\,}{(x+1)} = \log_{\,}{6}$$
	$$\log_{\,}{x(x+1)} = \log_{\,}{6}$$
	$$x(x+1) = 6$$
	$$R=\begin{cases} x_{1}= 2\;;\;2>0\land3 >0\\ x_{2} = -3_{ / / } < 0\end{cases}$$
1. Eksponentna enačba, ki jo rešimo z logaritmiranjem
$$3^x= 25$$
$$\log_{\,}{3}^x=\log_{\,}{25}$$
$$ x \cdot \log_{\,}{3} = \log_{\,}{25}$$
$$ x = \frac{\log_{\,}{25}}{\log_{\,}{3}}$$
$$ x = \log_{\,3}{25}$$
$$\log_{\,3}{9} < \log_{\,3}{25} < \log_{\,3}{81}$$
$$\log_{\,3}{3^2} < \log_{\,3}{25} < \log_{\,3}{3^3}$$
$$x \approx 2,7$$
[[Obravnava enačb in neenačb|Obravnava]] & [[Operacije#Logaritmiranje|Logaritmiranje]]

#### Logaritemska neenačba

Vključuje tudi graf. Najdemo ničlo in zapišemo rezultat.