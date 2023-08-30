
Največji skupni delitelj a in b $\color{green}(D(a, \,b))$ je največje število, ki hkrati deli a in b.

Najmanjši skupni večkratnik a in b $\color{green}(v(a, \,b))$ je najmanjše število, ki je večkratnik a in b hkrati oz. najmanjše število katerega še delita obe števili.

$$D(a,b) \cdot v(a,b) = a \cdot b$$

### Evklidov algoritem

je postopek za določanje največjega delitelja dveh naravnih števil z uporabo osnovnega izreka o deljenju.

$$
\begin{align*}
&D(123, 344):\\
&344 = 2 \cdot {\color{green}123} + {\color{yellow}98}\\
&{\color{green}123} = 1 \cdot{\color{yellow}98}+{\color{orange}25}\\
&{\color{yellow}89} = 3 \cdot{\color{orange}25}+{\color{green}14}\\
&{\color{orange}25} = 1 \cdot{\color{green}14}+{\color{yellow}11}\\
&{\color{green}14} = 1 \cdot{\color{yellow}11}+{\color{orange}3}\\
&{\color{yellow}11} = 3 \cdot{\color{orange}3}+{\color{green}2}\\
&{\color{orange}3} = 1 \cdot{\color{green}2}+{\color{yellow}1}\\
&{\color{green}2} = 2 \cdot{\color{yellow}1}+{\color{orange}0}\\
\end{align*}
$$
Največji skupni delitelj je $\color{yellow}1$. Končamo ko je ostanek enak 0 za rešitev pa vzamemo delitelja oz. količnik.
Še najmanjši skupni večkratnik:
$$v(a,\, b) = \frac{123\cdot344}{1}$$
$$\color{green}v(a, \, b) = \frac{a\cdot b}{D\,(a, b)}$$
Prav tako velja:
$$\color{green}D(a, b) = \frac{a\cdot b}{v(a,b)}$$

##### Tuji števili
...sta števili a in b kjer $\color{green}D(a, b) = 1.$