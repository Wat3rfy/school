<span style="color:#87f7ae">Funkcija</span> je predpis, ki vsakemu elementu iz množice A priredi natanko ene element iz množice B.
Lahko jo izrazimo: 
- z funkcijskim predpisom, 
- puščičnim diagramom, 
- v stavku,
- s tabelo

Graf funkcije je množica vseh urejenih parov $(x, f(x))$ kjer prvi element $x$ preteče celotno $D_{\!f}$, drugi element pa je predpis $f(x)$

<span style="color:#87f7ae">Realna funkcija</span> je funkcija, katere zaloga vrednosti vsebuje le realna števila. ^dd2aec

Lastnosti funkcij:
- Definicijsko območje$$D_f=A$$
- Zaloga vrednosti:$$Z_f=B$$
- Ničle: $$f(x) = 0 \iff x_{i}= n$$
- Začetna vrednost: $$f(0)=m$$
- Naraščajoča:$$ x_{1}< x_{2} \;;\; f(x_{1})<f(x_{2})$$$$x \in [n, m]$$
- Padajoča:$$ x_{1}< x_{2} \;;\; f(x_{1})>f(x_{2})$$$$x \in [i, j]$$
- Pozitivna & Negtivna:$$f(x) > 0 $$$$ f(x)< 0$$
- Nepozitivna & Nenegativna:$$f(x) \le 0$$$$f(x)\ge 0$$
- Injektivna $$f:X\rightarrow Y;\;\forall a, b \in D_{f}\,,  f(a) = f(b) \implies a = b$$
- Surjektivna** $$f:X\rightarrow Y;\;Z_{f}= Y$$
$$\text{ali}$$$$\forall \, y \, \in Y\!,\,\, \exists\, x \in X,\, f(x) = y$$
- Bijektivna $$f:X\rightarrow Y;\;{\color{green}(Z_{f}=Y)} \land {\color{yellow}(\forall a, b \in D_{f}\,,  f(a) = f(b) \implies a = b)} $$
- Neomejena**$$f: A \rightarrow \mathbb{R}$$ $${\color{green}\forall x \in A, \, \nexists\, m,\,|f(x)| \le m} \;;\; {\color{light}m\in \mathbb{R}} $$
- Omejena $$f: A \rightarrow \mathbb{R}$$ $${\color{green}\forall x \in A, \, \exists\, m,\,|f(x)| \le m} \;;\; {\color{light}m\in \mathbb{R}} $$
- Omejena navzgor $$f: A \rightarrow \mathbb{R}$$ $${\color{green}\forall x \in A, \, \exists\, m,\,f(x) \le m} \;;\; {\color{light}m\in \mathbb{R}} $$
- Omejena navzdol$$f: A \rightarrow \mathbb{R}$$ $${\color{green}\forall x \in A, \, \exists\, m,\,f(x) \ge m} \;;\; {\color{light}m\in \mathbb{R}} $$
- Sodost (Simetrija čez ordinatno os)$$f(x) = f(-x)$$
- Lihost (Simetrija čez koord. izhodišče) $$-f(x) = f(-x) \iff \color{green} f(x) = -f(-x)$$
   Definicijski območje simetrično??????????????????

## [[Operacije#Računanje s funkcijami|Računanje s funkcijami]]

Izračun funkcijske vrednosti pri danem št. $a$. Zapišemo $f(a)$.

## Inverzna funkcija

... je funkcija, ki preslika vse vrednosti iz zaloge vrednosti nazaj v originalne vrednosti originalne množice. Funkcija ima inverzno funkcijo, le ko je injektivna.
$$f: x \rightarrow f(x)$$
$$f^{-1}:f(x) \rightarrow x$$
$$D_{f^{-1}} = Z_{f}\,, Z_{f^{-1}} = D_f$$ 


Graf med seboj inverznih funkcij sta simetrična glede na simetralo lihih kvadrantov. Graf $f(x)^{-1}$ dobimo z zrcaljenjem grafa čez simetralo lihih kvadrantov.
$$f^{-1}(x) \neq (f(x))^{-1} = \frac{1}{f(x)}^{**}$$

***
## Transformacije funkcij

Zrcaljenje preko abscisne osi $$f(x) = -f(x)$$
![[0008.png|380]]















Zrcaljenje preko ordinatne osi $$f(x) = f(-x)$$
![[0009.png|380]]















Zrcaljenje preko izhodišča $$-f(x) = f(-x) \iff \color{green}f(x)=-f(-x)$$
![[0010.png|380]]











Premik za vektor $\vec{v}\,(p, 0); p=-2$
$$g(x) = f(x+2) \;;\; \color{green} g(x) = f(x-p)$$
![[0011.png|380]] 
















Premik za vektor $\vec{v}\,(0, q); q=3$
$$g(x) = f(x) - 3 \;;\; \color{green}g(x) =f(x) -q$$
![[0012.png|380]]














$$\color{green}g(x) = f(x-p) +q \;;\; p = -2, q = -3$$
![[0013.png|380]]













Razteg vzdolž ordinatne osi
$$g(x) = f(x)\cdot k \;;\; 0 < k < 1 \;;\; \text{Krčenje}$$
$$g(x) = f(x)\cdot k \;;\; 1 < k \;;\; \text{Razteg}$$
$$\color{light} f(x) = x^3;D_{f,g}=[-1^\cdot 25,1^\cdot 25]$$
![[0015.png|480]]



















Razteg vzdolž abscisne osi
$$g(x)=f(x \cdot k) \;;\; 1 <k \;;\; \text{Krčenje}$$
$$g(x)=f(x \cdot k) \;;\; 0 < k < 1 \;;\;\text{Razteg}$$
![[0014.png|480]]


















Absolutna funkcija
$$g(x) = |f(x)|$$
\
![[0016.png|380]]















Funkcija z absolutnimi spremenljivkami
$$g(x) = f(|x|)$$
\
![[0017.png|380]]











***
# Konstantna funkcija
$$f(x) = n$$
***
# Linearna funkcija
... je realna funkcija oblike $$f(x) = kx + n \;;\;k, n \in \mathbb{R} \land k\neq0 $$
$kx$ : linearni člen
$n$ : prosti člen
Njen graf je premica.
![[0020.png]]














Koeficient oz. vpliva na vzpenjanje oziroma padanje. Vzpenja se, ko je $\color{green}k > 0$. In pada, ko je $\color{blue}k < 0$.
![[0021.png|380]]














Ko je $k$ pri različnih linearnih funkcijah enak so vzporedne. Ko je prosti člen enak so sekalnice. Če je $k$ nasprotna in obratna vrednost linearnega koeficienta neke druge linearne funkcije hkrati, sta pravokotni.
***
# Potenčna funkcija

... je [[Funkcije#^dd2aec|realna funkcija]] oblike:
$$f(x) = x^{n}\;;\;n\neq0$$ ^1956a8

$n = {\color{green}2k} \;;\; n, k \in \mathbb{N} \land {\color{orange}k>0}$
\
![[School/Matematika/GraphRenders/0003.png|380]]













$n = {\color{yellow}2k + 1} \;;\; n, k \in \mathbb{N}\land {\color{orange}k>0}$
\
![[0004.png|380]]













\
$n = {\color{green}2k} \;;\; n, k \in \mathbb{N}\land {\color{blue}k<0}$
\
![[0006.png|370]]













\
$n = {\color{yellow}2k +1} \;;\; n, k \in \mathbb{N}\land {\color{blue}k<-1}$
![[0007.png|400]]














***
# Korenska funkcija
- ... je inverzna funkcija k [[Funkcije#Potenčna funkcija|potenčni funkciji]] z naravnim eksponentom oz.
- ... je [[Funkcije#^dd2aec|realna funkcija]] oblike: $$f(x) = x^{\frac{1}{n}}\;;\;n \in \mathbb{N}, n>1$$
- Korenska funkcija je inverzna funkcija potenčnih funkcij z lihim eksponentom in inverzna funkcija potenčnih funkcij s sodim eksponentom s takim $D_{\!f}$, da je injektivna.

Korenska funkcija s <span style="color:#87f7ae">sodim eksponentom</span>$$f(x) = \sqrt[n]{x} \;;\; n = 2k, k\in \mathbb{N}$$
![[0018.png|400]]














Korenska funkcija z <span style="color:#87f7ae">lihim eksponentom</span>$$f(x) = \sqrt[n]{x} \;;\; n = 2k +1, k\in \mathbb{N}$$
![[0019.png|380]]














*** 
# Kvadratna funkcija

... je polinomska funkcija 2. stopnje, ki jo lahko zapišemo na tri načine: 

### Eksplicitna oblika oz. splošna oblika
$$f(x) = {\color{green}ax^{2}}+ {\color{blue}bx} + {\color{orange}c} \;;\; a, b, c \in \mathbb{R} \land a \neq 0$$
${\color{green}ax^{2}\text{ : vodilni člen}}$
${\color{blue}bx\text{ : linearni člen}}$
${\color{orange}c\text{ : prosti člen}}$
\
$a,\, b,\, c \in \mathbb{R}$ : koeficienti
***
### Temenska oblika  
$$f(x) = {\color{green}a}(x-{\color{blue}p})^{2} + {\color{orange}q}$$
${\color{green}a\text{ : razteg oz. vodilni koeficient}}$
${\color{blue}p\text{ : premik po osi x}}$
${\color{orange}q\text{ : premik po osi y}}$

Osnovana je na legi temena $T(p ,\,q)$.

Iz eksplicitne oblike lahko izpeljemo temensko in dobimo enačbi za $T(p,\, q)$. ( Pretvorba iz temenske v eksplicitno in obratno! )
$$ $$
$$ax^{2}+ bx + c$$
$$a(x^{2}+ \frac{bx}{a}) + c$$
$$a(x + \frac{b}{2a})-\frac{b^{2}}{4a}+c$$
$$a(x + \frac{b}{2a})-\frac{b^{2} - 4ac}{4a}$$
$$ $$
$$a(x -p)+q \iff a(x + \frac{b}{2a})-\frac{b^{2} - 4ac}{4a}$$
$$ $$
$${\color{green}p = -\frac{b}{2a}},\, {\color{orange}q=\frac{4ac - b^{2}}{4a}}$$
$$ $$
Definiramo lahko tudi diskriminanto$(D)$.
$$D = b^{2}- 4ac \iff p = -\frac{D}{4a}$$ ^576ff4

<span style="color:#87f7ae">Teme je presečišče grafa funkcije in njene simetrale.</span> Ordinata temena je spodnja oz. zgornja meja funkcije, če je $a > 0$ oz. $a < 0$.
\
![[0022.png|380]]
















***
### Ničelna oblika
$$f(x) = {\color{green}a}(x - x_{1})(x + x_{2})$$
${\color{green}a\text{ : vodilni koeficient}}$
${x_{1}, x_{2} \text{ : ničli funkcije}}$

Iz temenske oblike lahko izpeljemo enačbo za računanje ničel.
$$a(x-p)^{2}+q = 0$$
$$a(x-p)^{2} = -\,q$$
$$(x-p)^{2} = -\frac{q}{a}$$
$$(x-p) = {\color{green}\pm} \sqrt[]{- \frac{q}{a}}$$
$$x = p\; {\color{green}\pm}\, \sqrt[]{- \frac{q}{a}}\;;\; {\color{green}p = -\frac{b}{2a}},\, {\color{orange}q=\frac{4ac - b^{2}}{4a}}$$
$$ $$
$$ \color{green} x_{1,2} = - \frac{2b}{a} {\color{sky}\pm} \sqrt[]{\frac{b^{2} - 4ac}{4a}}$$ ^10e540


Št. ničel lahko razberemo s pomočjo diskriminante: ^b7e9b6
- $D > 0 \implies 2$
- $D = 0 \implies 1$
- $D < 0 \implies 0 \;;\;$ oz. 2 kompleksni konjugirani ničli.
***
Vodilni koeficient oz. ${\color{green}a}$ se ohranja enak pri vseh oblikah.

Med koeficienti in ničlami poznamo tudi dve povezavi - <span style="color:#87f7ae">Vietovi formuli</span>:
$$x_{1}+x_{2}=-\frac{b}{a}$$
$$x_{1}x_{2}=\frac{c}{a}$$ ^0ed8e0

***
Graf kvadratne funkcije je ***parabola***.
Za risanje grafa potrebujemo: ^96dfd4
- $\color{green}f(0)\color{light}\text{\;\;\;\;\;\;\;\;\;zač.vrednost,}$
- $\color{green}x_{1,2}\color{light}\text{\;\;\;\;\;\;\;\;\;\;ničle,}$
- $\color{green}a\color{light}\text{\;\;\;\;\;\;\;\;\;\;\;\;\;vodilni koeficient,}$ 
- $\color{green}T(p,\, q)\color{light}\text{\;\;\; teme;}$

\
[[Enačbe in neenačbe#Kvadratna enačba|Kvadratna enačba]] & [[Enačbe in neenačbe#Kvadratna neenačba|Kvadratna neenačba]]

***
# Eksponentna funkcija

... je funkcija oblike:
$$f(x) = a^{x}; a>0 \land a \neq 1$$
$$ $$
Če je $a$ manjši od 0 se zgodi $\sqrt[2]{-1}$. 
Netransformirana funkcija ima asimptoto $y = 0$.
Osnova $1 < a$:
![[0025.png|380]]
Osnova $0 < a< 1$ :
![[0026.png|380]]

Za risanje grafa eksponentne funkcije potrebujemo:
- $\color{green}f(0)\color{light}\text{\;\;\;\;\;\;\;\;\;zač.vrednost,}$
- $\color{green}x_{1,2}\color{light}\text{\;\;\;\;\;\;\;\;\;\;ničle,}$
- $\color{green}a\color{light}\text{\;\;\;\;\;\;\;\;\;\;\;\;\;osnovo,}$ 
- $\color{green}V.A.\color{light}\text{\;\;\;\;\,\: vodoravno asimptoto;}$

[[Enačbe in neenačbe#Eksponentna enačba|Eksponentna enačba]]

***
# Logaritemska funkcija

... je inverzna funkcija k eksponentni oz. je realna funkcija oblike:
$$f(x) = \log_{\,a}{x}\;;\;a > 0 \land a \neq 1$$
Osnova $a < 1$:
![[0027.png|380]]
Osnova $a > 1$
![[0028.png|380]]
[[Enačbe in neenačbe#Logaritemska enačba|Logaritemska enačba]]

# [[Kotne funkcije in vektorji#Grafi kotnih funkcij|Kotne funkcije]]

# [[Polinomi#Polinomska funkcija|Polinomska funkcija]]

# Racionalna funkcija

...je kvoecient 2 okrajšanih polinomov.

$$f(x) = \frac{p(x)}{q(x)}\;;\;q(x)\neq0$$
$$D_{\!f} = \mathbb{R} - \{q(x) = 0\}$$

Poli so ničle imenovalca (navpične asimptote) - $q(x) = 0$.
$p(x), q(x)$ sta tuji števili.

#### Poševna asimptota

$$\frac{p(x)}{q(x)}={\color{green}k(x)} +\frac{r(x)}{q(x)}$$
Poševna asimptota je polinom ki nam pove kako se racionalna funkcija obnaša v pozitivni in negativni neskončnosti $k(x)$.

$$f(x) = \frac{x^{3}-8}{x^{2}-5}=x + 5 + \frac{25x-8}{x^{2}-5}$$
$$P.A.\!:\: y = x + 5$$

Poševna asimptota glede na stopnje
$$\frac{a_{n}x^{n}}{b_{m}x^{m}}$$
$$n<m \;;\; y=0 $$
$$n=m \;;\; y=\frac{a_{n}}{b_{m}} $$
$$n>m \;;\; y = k(x) $$
Presečišče grafa s poševno asimptoto dobimo če števec ostanka enačimo z 0: 
$$25x - 8 = 0$$
$$x = \frac{8}{25}$$


Za risanje grafa racionalne funkcije potrebujemo:
- $f(0)$
- $f(x) = 0$
- $\frac{a_{n}x^{n}}{b_{m}x^{m}}$ - Obnašanje v neskončnosti
- $q(x) = 0$ - Poli oz. ničle imenovalca
- $r(x)$ - Poševna asimptota


Pri sodih ničlah se funkcija odbije, pri lihih pa ne.
Pri lihih asimptotah se funkcija vrne na nasprotni strani pri sodih pa na isti.

[[Enačbe in neenačbe#Racionalna enačba|Racionalne enačbe]]




