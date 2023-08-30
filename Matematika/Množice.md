Množica je zbirka matematičnih objektov z nekaterimi skupnimi lastnostmi. Natančno določena je takrat, ko lahko naštejemo vse njene elemente oz. poznamo pravilo ki pove kakšni elementi ji pripadajo.

Moč množice / št. elementov:
$$m(A) = 2\,;\:m(A) = \infty$$

Množici sta enaki ko imata isto moč in vsebujeta iste elemente.


$$A = \{ a \in \mathbb{Z}\, ; \;a > 0 \}$$
a ; elementi množice 
a > 0; pogoj

Prazna množica: $$ A = \{\} $$

Presek množice: $$ A \cap B = \{ x; (x \in A) \land (x \in B) \}$$ $$\,^\ast m(A \cap B) = m(A) + m(B) - m(A \cup B)$$

Unija množice: $$ A \cup B = \{ x; (x \in A) \lor (x \in B) \}$$ $$\,^\ast m(A \cup B) = m(A) + m(B) - m(A \cap B)$$

Razlika množice: $$ A - B = \{ x; (x \in A) \land (x \notin B) \}$$

Komplement množice: $$ A^\prime = \{ x; (x \in \mathbb{U}) \land (x \notin A) \}$$

Potenca množice: $$ P(A) = \{ X; X \subseteq A \}\,;\; m(A) = n\,;\; m\,(P\,(A)) = 2^n$$

Kartezični produkt A in B: $$A \times B = \{  a, \,b\,; (a\in A) \land (b \in B) \}$$
$$\,^\ast m(A \times B) = p \cdot q;\; p = m(A),\, q = m(B)$$
\* a, b - Urejen par ;-; Množica urejenih parov množic A in B
***
# Številske množice
***
## Naravna števila

So števila s katerimi štejemo
$$\mathbb{N} = \{  1, 2, 3, 4,... \};\; m(\mathbb{N}) = \infty \; (Števna\; neskončnost) $$ 
 $$\mathbb{N}_0 = \mathbb{N} \cup \{  0 \}$$
Peanovi aksiomi
- Vsako naravno število ima svojega naslednika
- Število 0 je naravno število, ki ni naslednik nobenega $\mathbb{N}$; 0 je najmanjše naravno število
- Če sta dva naslednika dveh naravnih števil enaka sta originalni naravni števili enaki.
- Če množica vsebuje 0 in naslednika vsakega števila vsebuje vsa naravna števila, kar pomeni, da če neka trditev/enačba velja za 0 in naslednika vsakega števila velja za vsa naravna števila ;-; načelo je znano kot matematična indukcija, ker se lahko uporabi za matematične dokaze za vsa števila brez potrebe po neskončnih dokazih 

##### Računske operacije v naravnih številih oz. notranje operacije

Rezultat *notranje operacije*  bo vedno element $\mathbb{N}$.

[[Operacije#Seštevanje|Seštevanje]], [[Operacije#Množenje|Množenje]]
***
## Cela števila

Vsebujejo vsa naravna števila, njuna nasprotna števila in nič.

$$\mathbb{Z} = \mathbb{N} \cup \{0\}\cup\{-\mathbb{N}\}$$

Nasprotno število $k$ je število, ki ga prištejemo številu $n$ da dobimo 0.
Nasprotno število števila 0 je 0. ^36b2b8

##### Notranje operacije
[[Operacije#Seštevanje|Seštevanje]], [[Operacije#Množenje|Množenje]], [[Operacije#Odštevanje|Odštevanje]]

#### Urejenost $\mathbb{N}$ in $\mathbb{Z}$ števil
*Množica celih števil je urejena z relacijo, kar pomeni da za različni celi števili a in b velja ena od naslednjih možnosti:*
\
$$\text{Zakon o trihotomiji}$$

$$a < b\;\; |\; \; a > b\;\; |\; \;a = b$$
$$(a, b \in \mathbb{Z}) \implies (a > b)\vee(a <b )\vee(a = b)$$
$$\text{Za vsak par števil v množici velja ena od teh relacij.}$$
\
$$a > b \iff a - b > 0$$
$$a < b \iff a - b < 0$$
$$a = b \iff a - b = 0$$
\
Z relacijo je množica $\mathbb{Z}$ linearno urejena.
$$a \in \mathbb{Z}\; je \;pozitivno\;če\; je\; a > 0$$
$$a \in \mathbb{Z}\; je \;negativno\;če\; je\; a < 0$$
$$a \in \mathbb{Z}\; je \;nenegativno\;če\; je\; a \geq 0$$
$$a \in \mathbb{Z}\; je \;nepozitivno\;če\; je\; a \leq 0$$

***
## Racionalna števila

Množica vseh okrajšanih ulomkov: $a$, in $b$ sta celi števili, $b$ ni nič in sta si [[Največji skupni delitelj in najmanjši skupni večkratnik#Tuji števili|tuji]].

$$\mathbb{Q} = \{ \frac{a}{b}; a,b \in \mathbb{Z} \land b \neq 0 \land D(a, b) = 1  \}$$

Množica racionalnih števil je $\color{green}\text{gosta}$. Med dvoji racionalnimi števili je vsaj eno vmes.
Notranje operacije:
[[Operacije#Seštevanje|Seštevanje]], [[Operacije#Množenje|Množenje]], [[Operacije#Odštevanje|Odštevanje]]

Ni notranja operacija, ker je deljenje z nič nedefinirano:
[[Operacije#Deljenje|Deljenje]]

##### Ulomki
Ulomek je izraz oblike $\frac{a}{b}$ kjer sta $a$ in $b$ celi števili in $b\neq 0$.

$a \Rightarrow$ števec
$b \Rightarrow$ imenovalec

Če je $b = 0$ je ulomek nedefiniran. Če je $a = 0$ je ulomek enak nič.

$$\frac{a}{b}= \frac{d}{c}\iff ad = bc\; ; \; b,d\neq0$$

Ulomek $\frac{a}{b}$ razširimo z neničelnim celim številom $k$ tako, da pomnožimo $a$ in $b$ s $k$.
$$\frac{a}{b}= \frac{a\cdot k}{b\cdot k}$$
Najmanjši skupni imenovalec dveh ulomkov je enak $v(a, b)$.
Ulomek je okrajšan ko sta si $a$ in $b$ [[Največji skupni delitelj in najmanjši skupni večkratnik#Tuji števili|tuji si števili]].

Urejeni z realcijo $\lt$. Za ulomka $\frac{a}{b}$ in $\frac{c}{d}$ velja ena od treh možnosti:
$$\frac{a}{b}\gt \frac{c}{d} \iff ad \gt bc$$
$$\frac{a}{b}\lt \frac{c}{d} \iff ad \lt bc$$
$$\frac{a}{b} = \frac{c}{d} \iff ad = bc$$

[[Operacije#Računske operacije med ulomki|Računske operacije med ulomki]]

#### Obratna vrednost
Vsakemu od 0 različnemu celemu številu lahko priredimo obratno število.

Obratna vrednost ulomka je ulomek, katerega števec in imenovalec sta med seboj zamenjana. 

\
$$a^{-1}$$

$$a^{-1} \cdot a =  1$$
\
Lastnosti obratne vrednosti:
1. Ker 0 nima obratne vrednosti je deljenje z 0 prepovedano, $\frac{0}{0}$ pa je prepovedano.
2. 1 deljen s katerimkoli poljubnim od nič različnim celim številom $n$ je enak obratnemu številu $n^{-1}$.
3. Količnik poljubnega števila $n$  s številom 1 je enak $n$.
4. Število 1 je samemu sebi obratna vrednost.
5. Za poljubni števili $a$ in $b$ velja $(ab)^{-1} = a^{-1}\cdot b^{-1}$.
6. Pri celemu številu $a \neq 0$ je obratnost vzajemna: $(a^{-1})^{-1} = a$

Za vsako racionalno število obstaja [[Množice#^36b2b8|nasprotno]] št.
Za vsako racionalno število obstaja obratno št. razen 0.

[[Decimalni zapis racionalnega števila]]
***
## Iracionalna števila

$$\mathbb{Q}^\prime = \mathbb{R} - \mathbb{Q}$$
Iracionalna števila so vsa števila ki jih ne moramo izraziti z zapisom: $\frac{a}{b}; b\neq 0$

Če poskusimo zapisati iracionalna števila v decimalni obliki, bi dobili neskončno zaporedje neperiodičnih decimalk.

<span style="color:#87f7ae">Neskončen zapis brez periode.</span>

#### Algebrska števila
Število, ki je rešitev neke polinomske enačbe z racionalnimi koeficienti.
#### Transcendentna števila
Števila, ki niso algebrska. Ne da se jih zapisati z ulomkom ali korenom.
$$\pi ,\,e,\, \log_{a}\!b, \,\sin(a),...$$


***

## Realna števila
Števila s katerimi merimo enodimenzionalne količine npr. dolžino, temperaturo,...

$$\mathbb{R} = \mathbb{Q} \cup \mathbb{Q}^\prime$$


Vsebuje poleg množice racionalnih števil še iracionalna števila.

#### Urejenost realnih števil

$$a > b \iff a - b > 0$$
$$a \ge b \iff a - b \ge 0$$

[[#Urejenost $ mathbb{N}$ in $ mathbb{Z}$ števil|Urejenost v množici naravnih in celih števil]] velja tudi tukaj.

#### Lastnosti računanja
$$ - \cdot - \implies +$$
$$ + \cdot - \implies -$$
$$ + \cdot + \implies +$$

#### Številska premica in intervali

Množico vseh realnih števil na številski premici med $a$ in $b$ imenujemo interval. Poznamo dve vrsti intervalov.:
- $[]$ : zaprti interval
- $()$ : odprti interval
$$x \in [n, m]\;;\; n \le x \le m$$
$$x \in (a, b)\;;\; a < x < b$$
\
![[0029.png|380]]
![[0030.png|380]]
#### Absolutna vrednost v $\mathbb{R}$

Absolutna vrednost $n$ je <span style="color:#87f7ae">nenegativna</span> vrednost $n$ oz. je razdalja do izhodišča številske premice oz. 0.
$$|n| = 
\begin{cases}
n \;;\; n \ge 0 \\
-n \;;\; n < 0
\end{cases}$$
$$|n| = \sqrt[]{n^{2}}$$
Lastnosti:
$$|a| \ge 0$$
$$|-a|=|a|$$
$$|a \cdot b| = |a| \cdot |b|$$
$$|a + b| \le |a| + |b|$$
[[Absolutna vrednost v enačbah in neenačbah]]
[[Kartezični koordinatni sistem]]
***
## Kompleksna števila
$$\mathbb{C}\in \{a+b\cdot i \;;\; a, b \in \mathbb{R}, i \in \mathbb{I} \}$$
$$i^2=-1$$
$$i = \sqrt[]{-1}$$
Kompleksno število $z$:
$$z = a +bi = Re(z) + Im(z)$$
$a \text{ / Re(z)}$ : realna komponenta
$b \text{ / Im(z)}$ : imaginarna komponenta

$$b = 0 \implies z \in \mathbb{R}$$
$$a = 0 \implies z \in \mathbb{I}$$
$$\mathbb{C = \mathbb{I} \cup \mathbb{R}}$$

Kompleksni koordinatni sistem / Gaussova ravnina / Polarni koord. sistem
![[School/Matematika/GraphRenders/0001.png|380]]



















Potence imaginarne enote:

- $i^{0}=1$
- $i^{1}=i$
- $i^{2}=-1$
- $i^{3}=-i$

### [[Operacije#Računske operacije med kompleksnimi števili|Računanje s kompleksnimi števili]]:
- [[Operacije#Kompleksno Seštevanje & Odštevanje|Seštevanje]]
- [[Operacije#Kompleksno Seštevanje & Odštevanje|Odštevanje]]
- [[Operacije#Kompleksno Množenje|Množenje]]
- [[Operacije#Kompleksno Deljenje|Deljenje]]
### Konjugirana vrednost
... je definirana kot:
$$z = a + bi$$
$$\overline{z} = a- bi$$
$$\color{light}{}-z = -a-bi$$

Lastnosti:

$$\overline{\overline{z}} = z$$
$$\overline{z_{1}} + \overline{z_{2}} = \overline{z_{1}+ z_{2}}$$
$$\overline{z_{1}} \cdot  \overline{z_{2}} = \overline{z_{1}\cdot  z_{2}}$$
$$- \overline{z} = \overline{(-z)}$$
$$z \in \mathbb{R} \implies z = \overline{z}$$

### Absolutna vrednost kompleksnega števila

Tako kot pri realnih številih je absolutna vrednost kompleksnega števila razdalja od izhodišča kompleksnega koord. sistema.
$$ $$
$$|z|=\sqrt[]{z^2}$$
$$|z| = |a + b\cdot i| = \sqrt[]{(a+b\cdot i)^{2}} = \sqrt[]{a^2 + b^2}$$
$$\color{light}|z| = |Re(z) + Im(z)\cdot i| = \sqrt[]{(Re(z)+Im(z)\cdot i)^{2}} = \sqrt[]{Re(z)^2 + Im(z)^2}$$

$$\color{light}{{z \cdot \overline{z} = a^{2}+ b^{2}}}\iff |z|=\sqrt[]{z \cdot \overline{z}} $$
\
![[0002.png|280]]
$$
\begin{align*}
r^{2}&= a^{2}+ b^{2}\\
r &= \sqrt[]{a^{2}+b^{2}}
\end{align*}
$$
Dolžina do koord. izhodišča
$$ \color{green}{}|z| = r$$
Krog s središčem  $S(a, b)$ oz. razdalja med dvema kompleksnima številoma.
$$r = |(x-a) + i(y - b)|$$

