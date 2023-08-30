
## Seštevanje:
- Večanje vrednosti števila za *n*
- Notranja operacija $\mathbb{N}$
- Seštevanec (2x) ;-; Vsota, seštevek, suma
- Nevtralni element oz. [[Lastnosti Rel.&Op.#Identiteta|Identiteta]]: $a + 0 = a$
- Lastnosti: [[Lastnosti Rel.&Op.#Komutativnost oz. zakon o zamenjavi|Komutativnost]],  [[Lastnosti Rel.&Op.#Asociativnost oz. zakon o združevanju|Asociativnost]]
  $$a + c = b + c \implies a = b$$
***
## Odštevanje
- Prištevanje nasprotnega števila *n*
- Notranja operacija $\mathbb{Z}$
- Zmanjševanec ;-; Odštevanec ;-; Razlika, diferenca
-  [[Lastnosti Rel.&Op.#Identiteta|Identiteta]]: $a - 0 = a$
- Lastnosti:  [[Lastnosti Rel.&Op.#Antikomutativnost|Antikomutativnost]]


***

## Množenje

- Prištevanje števila *n*-krat. ($\mathbb{N}$)
- Notranja operacija naravnih števil
- Množenec ;-; Množitelj ;-; Produkt
- [[Lastnosti Rel.&Op.#Identiteta|Identiteta]]: $a \cdot 1 = a$
- Lastnosti: [[Lastnosti Rel.&Op.#Komutativnost oz. zakon o zamenjavi|Komutativnost]],  [[Lastnosti Rel.&Op.#Asociativnost oz. zakon o združevanju|Asociativnost]],  [[Lastnosti Rel.&Op.#Distributivnost oz. zakon o razčlenjevanju|Distributivnost]]
$$ a \cdot 0 = 0 $$

##### Množenje in odštevanje
$$-(-a) = a$$
$$-a + (-b) \,=\, -a - b \,=\, -(a + b)$$
$$a \cdot (-1) \, = \, -a$$

$$(-a) \cdot (-b) = ab$$
$$(-a)\cdot b = -(ab)$$
***

## Deljenje

Relacija deljivosti:
Naravno število *b* imenujemo večkratnik naravnega števila *a* če lahko zapišemo:
$$k \cdot a = b;\; k \in \mathbb{N}$$
$$b = k \cdot a \implies b:a = k$$

Naravno število b je delitelj naravnega števila a, če obstaja naravno število k, da obstaja:
$${\color{green}k} \cdot{\color{yellow}{b}} = \color{orange}a$$

$\color{orange}a$  $\Rightarrow$ deljenec
$\color{yellow}b$ $\Rightarrow$ deljitelj (Mogoce lahko k in b zamenjamo) ?????????????????????
$\color{green}k$ $\Rightarrow$ količnik

Vsako $\mathbb{N}$ število ima vsaj dva deljitelja.??????????????????????
Imajo neskončno večkratnkov.
Vsako $\mathbb{N}$ število je deljitelj sebe in svojih večkratnikov.
Če število deli 2 naravni števili, deli tudi njuno vsoto, razliko, produkt in količnik

Deljivost je relacija med dvema številoma, število *a* je deljivo če je: 
$$a | b\iff b = ka;\; m,n,k\in\mathbb{N}$$
Lastnosti: [[Lastnosti Rel.&Op.#Refleksivnost|Refleksivnost]], [[Lastnosti Rel.&Op.#Antisimetričnost ?????????????|Antisimetričnost]], [[Lastnosti Rel.&Op.#Tranzitivnost|Tranzitivnost]]

Če je število deljivo z dva je *sodo*, če ni je *liho*.

#### 1. Osnovni izrek o deljenju
$${\color{green}k} \cdot{\color{yellow}{b}} + \color{white}r = \color{orange}a$$
$$ (r <b) \; \land \; (a, b, k \in \mathbb{N}) \;\land \;(r\in\mathbb{N}_0) $$

$\color{orange}a$  $\Rightarrow$ deljenec
$\color{yellow}b$ $\Rightarrow$ deljitelj (Mogoce lahko k in b zamenjamo) ?????????????????????
$\color{green}k$ $\Rightarrow$ količnik ( r < b, k ??????????????????????????????'')
$\color{white}r$ $\Rightarrow$ ostanek
***

#### 2. Deljenje s koreni

Pri deljenju s koreni je potrebna <span style="color:#87f7ae">racionalizacija</span> oz. se poskušamo znebiti korenov iz imenovalca.

$$\frac{a}{\sqrt[]a{}}=\frac{a\sqrt[]a{}}{a}$$

$$\color{light}\frac{a}{\sqrt[]a{}}=\frac{a \cdot \sqrt[]{a}}{\sqrt[]{a} \cdot \sqrt[]{a}} =\frac{a\sqrt[]a{}}{a}$$

***
#### 3. [[#Kompleksno Deljenje|Deljenje s kompleksnimi števili]]
***

## Računske operacije med ulomki
$$ $$
$$\frac{a}{b} + \frac{c}{d}= \frac{ad+cb}{bd}$$
$$\frac{a}{b} - \frac{c}{d}= \frac{ad-cb}{bd}$$
$$\frac{a}{b} \cdot \frac{c}{d}= \frac{ac}{bd}\;\;$$
$$\;\;\;\;\frac{a}{b}:\frac{c}{d}= \frac{a}{b}\cdot \left(\frac{c}{d}\right)^{-1}$$
$$\left(\frac{a}{b}\right)^{-1} = \left(\frac{b}{a}\right)$$
***

## [[Potenciranje & Korenjenje#Potence|Potenciranje]]

***

## [[Potenciranje & Korenjenje#Koreni|Korenjenje]]

***

## Logaritmiranje

$$\log_{\,a}{y} = x \iff a^{x} = y \;;\; a,\,y > 0 \land a  \neq 1 \land x \in \mathbb{R}$$
$a$ : osnova
$y$ : logaritmand
Pogosti logaritmi so: 
- desetiški logaritem, $\log_{\,10}{x}$
- binarni logaritem, $\log_{\,2}{x} \text{ oz. lb} \,x$
- naravni logaritem $\log_{\,e}{x} \text{ oz. ln} \, x$

### Računanje z logaritmi
$$\log_{\,a}{x} + \log_{\,a}{y} = \log_{\,a}{(x\cdot y)}$$
$$\log_{\,a}{x} - \log_{\,a}{y} = \log_{\,a}{\left(\frac{x}{y}\right)}$$
$$r \cdot \log_{\,a}{x} = \log_{\,a}{x^r}$$
$$\frac{\log_{\,x}{a}}{\log_{\,x}{b}}=\log_{\,b}{a}$$
$$\log_{\,a^{y}}{x} = \frac{1}{y}\log_{\,a}{x}$$
Lastnosti:
$$\log_{\,a}{1} = 0$$
$$\log_{\,a}{a^{y}}= y\color{light}\;;\;\log_{\,a}{a} = 1$$
$$a^{\log_{\,a}{x}} = x$$

[[Obravnava enačb in neenačb|Obravnavanje]]
[[Enačbe in neenačbe#Logaritemska enačba|Logaritemska enačba]]
[[Funckije#Logaritemska funkcija|Logaritemska funkcija]]


## Računske operacije med kompleksnimi števili:

#### Kompleksno Seštevanje & Odštevanje
$$z_{1}= a_{1}+b_{1}i \;;\; z_{2}= a_{2}+b_{2}i$$
$$
\begin{align*}
z_{1} \pm  z_{2}&= a_{1}+b_{1}i\pm (a_{2}+b_{2}i) \\
&= a_{1}\pm a_{2} + i (b_{1}\pm b_2)
\end{align*}$$
Lastnosti: [[Lastnosti Rel.&Op.#Komutativnost oz. zakon o zamenjavi|Komutativnost]], [[Lastnosti Rel.&Op.#Asociativnost oz. zakon o združevanju|Asociativnost]]
#### Kompleksno Množenje

$$z_{1}= a_{1}+b_{1}i \;;\; z_{2}= a_{2}+b_{2}i$$
$$
\begin{align*}
z_{1}\cdot z_2&=(a_1+b_1i)(a_2+b_2i)\\
&=a_{1}a_{2}-b_{1}b_{2}+i(a_{1}b_{2}+b_{1}a_{2})
\end{align*}$$

Lastnosti: [[Lastnosti Rel.&Op.#Komutativnost oz. zakon o zamenjavi|Komutativnost]], [[Lastnosti Rel.&Op.#Asociativnost oz. zakon o združevanju|Asociativnost]], [[Lastnosti Rel.&Op.#Distributivnost oz. zakon o razčlenjevanju|Distributivnost]]

#### Kompleksno Deljenje
Pri deljenju s kompleksnimi števili moramo <span style="color:#87f7ae">racionalizirati</span> rezultat oz. se znebiti katerihkoli kompleksnih komponent (in korenov). 

$$z^{-1}= \frac{1}{z} = \frac{1}{a+bi}$$
Racionalizacija:
$$\frac{z_{1}}{z_{2}}=\frac{z_{1}\cdot \overline{z_{2}}}{z_{2}\cdot \overline{z_{2}}}$$
***

## Računanje s funkcijami

#### Seštevanje
Funkcije seštejemo tako, da seštejemo njuni formuli.
$$(f+g)(x)= f(x) + g(x) $$
#### Odštevanje
Funkcije odštejemo tako, da odštejemo njuni formuli.
$$(f-g)(x)= f(x) - g(x) $$
#### Množenje
Funkcije množimo tako, da množimo njuni formuli.
$$(f \cdot  g)(x)= f(x) \cdot  g(x) $$
#### Deljenje
Funkcije delimo tako, da delimo njuni formuli.
$$\left(\frac{f}{g}\right)(x)= \frac{f(x)}{g(x)} $$
#### Kompozitum
... je sestavljena funkcija. Rezultat za poljuben $x$ najprej dobimo s funkcijo $g(x)$ in nato dobljeno vrednost

$$(f \circ g)(x) = f(g(x))$$

Rezultat kompozituma imenujemo tudi sestavljena funkcija.

V množici funkcij obstaja funkcija - <span style="color:#87f7ae">identična funkcija - $i(x)$</span>, ki je nevtralni element. <span style="color:#87f7ae">**Drugače ni komutativno!**</span>
$$i(x)=x$$
$$i(f(x))=f(x)$$
$$i \circ f = f$$
$$f \circ i= f$$
Lastnosti:

$$(f \circ g )^{-1} = f^{-1}\circ g^{-1}$$
$$f^{-1}\circ f=i(x)$$
- Ni [[Lastnosti Rel.&Op.#Komutativnost oz. zakon o zamenjavi|komutativen]]
- [[Lastnosti Rel.&Op.#Asociativnost oz. zakon o združevanju|Asociativnost]]

***

## Operacije med vektorji

#### Seštevanje
$$\vec{a} + \vec{b} = \vec{c}$$
![[0040.png|200]]