### Polinom

... je zapis oblike
$$a_{n}x^{n} + a_{n-1}x^{n-1}+\; ...\, +a_{1}x^{1}+a_{0}x^{0} \;;\; a\in \mathbb{C}, n\in \mathbb{N}_0$$

$a_{0}$ - prosti člen
$a_{n}x^{n}$ - vodilni člen
$a_{n}$ - vodilni koeficient
**<span style="color:#87f7ae">$n$ - stopnja</span>**

$D_{\!f} = \mathbb{R}$

Dva polinoma sta enaka, če imata enako stopnjo in koeficient ob istoležnih členih.

$f(x) = 0$ - Ničelni polinom
$f(x)=c \;;\; c\in \mathbb{R}$ - Konstantni polinom
$f(x)=bx + c \;;\; b, c\in \mathbb{R}$ - Linearni polinom
$f(x)=ax^{2} + bx + c \;;\; a,b,c\in \mathbb{R}$ - Kvadratni polinom
### Operacije med polinomi
$$ $$
$$p(x) = a_{n}x^{n} + a_{n-1}x^{n-1}+\; ...\, +a_{1}x^{1}+a_{0}x^{0}$$
$$q(x) = b_{m}x^{m} + b_{m-1}x^{m-1}+\; ...\, +b_{1}x^{1}+b_{0}x^{0}$$
##### Seštevanje in odštevanje polinomov
$$ $$
$$ p(x) \pm q(x) = b_{m}x^{m} \pm ... \pm (a_{n} + b_{n})x^{n} \pm ... \pm (a_{1} + b_{1})x^{1} \pm (a_{0}+b_{0})x^{0}$$
$$ $$
$$ 0 \le \text{st}(p\pm q) $$ 
$$\text{max}\{m,n\} \le \text{st}(p+q)$$
$$\text{max}\{m,n\} \ge \text{st}(p-q)$$

##### Množenje polinomov
$$ p(x)\cdot  q(x) =$$
$$ a_{n}b_{m}x^{n+m} + ... + a_{n}b_{0}x^{n} + a_{n-1}b_{m}x^{n+m} + ... + a_{n-1}b_{0}x^{n-1} \;\;\;\cdot \cdot \;\cdot$$
$$ $$
$$ \text{st}(p \cdot q) = m + n$$

##### Deljenje

Osnovni izrek o deljenju polinomov:
$$\text{st}(p) \ge \text{st}(q)$$
$$ $$
$${\color{green}p(x) = q(x)\cdot  k(x) + r(x)} \iff \color{orange}\frac{p(x)}{q(x)}=k(x) + \frac{r(x)}{q(x)}$$
$$ $$

$$\begin{align*}
&\;\;\;\;({\color{green}x^{2}} + 3x -1) : ({\color{green}x+2}) = {\color{green}x} + 1\\
&{\color{green}-}\;\,\; {\color{green}x^{2} + 2x}\\
&\;\;\;\;\;\;\;\;\;\;\;\;\;\,\;\,x - 1\\
&{\color{light}-}\;\;\;\;\,\;\;\;\;\;\;\;\,x + 2\\
&\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;-3

\end{align*}$$

$$\begin{align*}
&\;\;\;\;(x^{2} + 3x -1) : ({\color{orange}x+2}) = x + {\color{orange}1}\\
&{\color{light}-}\;\,\; {\color{}x^{2} + 2x}\\
&\;\;\;\;\;\;\;\;\;\;\;\;\;\,\;\,{\color{orange}x} - 1\\
&{\color{orange}-}\;\;\;\;\,\;\;\;\;\;\;\;\,{\color{orange}x + 2}\\
&\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;-3

\end{align*}$$


##### Hornerjev algoritem

Za razcep:
- Možnosti:$\pm\frac{4}{4},\,\pm\frac{4}{2},\,\pm\frac{4}{1},\,\pm\frac{1}{4},\,\pm\frac{1}{2};$

$$ p(x) = 4x^{4} -20x^{3} +15x^{2} +5x -4$$

![[0068.png|380]]


**<span style="color:#87f7ae">4 je ena od ničel:</span>**
$$ p(x) = (x + \frac{1}{2})(x-\frac{1}{2})(x-1)(x-4)$$

### Ničle polinomov

... je kompleksno število, ki reši enačbo $$p(x) = 0$$

Vsak nekonstanten polinom s kompleksnimi koeficienti ima vsaj 1 kompleksno ničlo.

Št. ničel polinomov ne presega stopnje polinoma. Polinom stopnje $n$ ima natanko $n$ kompleksnih ničel.

<span style="color:#87f7ae">**Ničelna oblika polinoma**</span>:
$$ p(x) = a_{n}(x-x_{1})(x-x_{2})\cdot\, ... \cdot (x - x_{n})$$
$$x_{i} \in \mathbb{C}\;;\; i \in \{1, 2,... n\}$$

Ničla $k$-te stopnje:
$$p(x) = a_{n}(x-x_{1})^{k}\, ...(x-x_{m}) $$

Če je ničla soda se graf odbije.
Če je ničla liha se graf ne odbije.
### Polinomska funkcija
... je funkcija oblike
$$f(x) = a_{n}x^{n} + a_{n-1}x^{n-1}+\; ...\, +a_{1}x^{1}+a_{0}x^{0}\;;\; a \in \mathbb{C}, n \in \mathbb{N}_0$$

##### Graf polinoma

... je nepretrgana krivulja

Za risanje grafa moramo poznati:
- $f(0)$
- $x_{1,2,...}$
- $a_{n}x^n$ - Obnašanje v neskončnosti (Lihi sodi eksponent)
- $E_{1,2,...}$ - Ekstremi:

$$ p(x) = 4x^{4} -20x^{3} +15x^{2} +5x -4$$
$$ \downarrow $$
$$ p^{\prime}= 16x^{3}  - 60x^{2} +30x + 5$$
Iskanje ničel pri $p^{\prime}$.
Za vsak $x$ izračunamo $y$.

- Če je ničla soda se graf odbije.
- Če je ničla liha se graf ne odbije.

### Bisekcija

1. Najdemo 2 točki kjer sta vrednosti $f(x)$ pozitivna in negativna.
2. Poiščemo $x$ vrednosti in definiramo interval.
3. $f(\frac{x_{1}+x_{2}}{2})$ ... $x_{3}$ ...
4. Ko je $f(x_{n}) = 0$ končamo.**

### Polinomska enačba

Pri enačbah pišemo tudi kompleksne rešitve.

Vrste nalog:
- *Računanje ničel s podano ničlo*



### [[Funkcije#Racionalna funkcija|Racionalna funkcija]]

