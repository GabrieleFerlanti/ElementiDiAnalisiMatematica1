# Capitolo1

### Insiemi numerici

$N$ insieme dei numeri naturali 1, 2, 3, 4, 5, ...
$Z$ insieme dei numeri interi relativi ..., -3, -2, -1, 1, 2, ...
$Q$ insieme dei numeri razionali 1/2, 7/6, -3/8, ...
$R$ insieme dei numeri relativi $\sqrt2$, 0, $\pi$, ...

### Densità di Q e di R
**Teorema** Siano a, b due numeri reali, con a < b. Allora, esistono infiniti numeri razionali $r$  e infiniti numeri irrazionali $s$ tali che a < $r$ < b, a < $s$ < b. 

*intervallo di estremi* [a,b]

#### Intervalli e interno

**Intervalli limitati** 
]a,b[ intervallo aperto
[a,b[
[a,b] intervallo chiuso
]a,b]

**Intervalli non limitati**
]a, +$\infty$[
]-$\infty$, b[
]-$\infty$,+$\infty$[ = $R$

**Interno**: ]c-r, c+r[ con c $\in R$ $r > 0$ è detto interno di $c$ di raggio $r$ e può essere denotato con un dei simboli $B(c,r)$ $I_r(c)$.

### Valore assoluto

Se $x \in R$, si chiama valore assoluto di $x$ il numero reale $|x|$ definito ponendo $|x| = x$ se $x \ge 0$, $|x| = -x$ se $x < 0$.

### Estremo inferiore ed estremo superiore

**minimo** : Un elemento $m \in X$ tale che $m \le x$ $\forall x \in X$.
**massimo**: Un elemento $M \in X$ tale che $M \ge x$ $\forall x \in X$.

**minorante**: Un elemento $h \in R$ tale che $h \le x$ $\forall x \in X$, denotiamo con $\underline M_X$ l'insieme dei minoranti di $X$.
**maggiorante**: Un elemento $k \in R$ tale che $k \ge x$ $\forall x \in X$, denotiamo con $\overline M_x$ l'insieme dei maggioranti di $X$.

**limitato inferiormente**: se $\underline M_x \ne \emptyset$.
**limitato superiormente**: se $\overline M_x \ne \emptyset$.

**estremo inferiore**: se $X$ è limitato inferiormente, si pone $infX = max\underline M_x$. Se non è limitato inferiormente $infX = -\infty$.
**estremo superiore**: se $X$ è limitato superiormente, si pone $supX = min\overline M_x$. Se non è limitato superiormente $supX = +\infty$.

### Nozioni di tipologia

**interno di X**: denotato con $int(x)$ è l'insieme dei punti interni di $X$, cioè i punti dell'intervallo aperto ]a,b[ di conseguenza $X = int(X)$.

**punto di frontiera**: un numero reale $c$ è detto punto di frontiera per $X$ se, $\forall r > 0$, nell’intorno $]c − r,c + r[$ ci sono elementi di $X$ ed elementi di $R$ \ $X$.

**punto di accumulazione**: un numero reale $c$ è detto punto di accumulazione per $X$ se, $\forall r > 0$, nell'intorno $]c-r,c+r[$ ci sono elementi di $X$ diversi da $c$. L'insieme dei punti è detto derivato di $X$ e si denota con $D(X)$.

*nota* -  un punto interno è un punto di accumulazione, un punto di frontiera può anche non esserlo. La chiusura di $X$ -> $\overline X  = X \cup D(X)$

### Numeri complessi 

$z=a+ib$ *forma algebrica*
$z=|z|(cos \alpha + i sin(\alpha))$ *forma trigonometrica*

**modulo di z**: $|z|=$$\sqrt{(x^2+y^2)}$ 
**coniugato di z**: $\overline z = a -ib$

#### Radici 

$w_k = \sqrt[n]{|z|}(cos(\frac{\alpha + 2k\pi}{n}) + isin(\frac{\alpha + 2k\pi}{n})$
k va da 0 a n-1 

### Valori delle funzioni goniometriche

|angolo|cos|sin|
|:---:|:---:|:---:|
|0|1|0|
|$\frac{\pi}{6}$|$\frac{\sqrt3}{2}$|$\frac{1}{2}$|
|$\frac{\pi}{4}$|$\frac{\sqrt2}{2}$|$\frac{\sqrt2}{2}$|
|$\frac{\pi}{3}$|$\frac{1}{2}$|$\frac{\sqrt3}{2}$|
|$\frac{\pi}{2}$|$0$|$1$|
|$\frac{2\pi}{3}$|$-\frac{1}{2}$|$\frac{\sqrt3}{2}$|
|$\frac{3\pi}{4}$|$-\frac{\sqrt2}{2}$|$\frac{\sqrt2}{2}$|
|$\frac{5\pi}{6}$|$-\frac{\sqrt3}{2}$|$\frac{1}{2}$|
|$\pi$|$-1$|$0$|
|$\frac{7\pi}{6}$|$-\frac{\sqrt3}{2}$|$-\frac{1}{2}$|
|$\frac{5\pi}{4}$|$-\frac{\sqrt2}{2}$|$-\frac{\sqrt2}{2}$|
|$\frac{4\pi}{3}$|$-\frac{1}{2}$|$-\frac{\sqrt3}{2}$|
|$\frac{3\pi}{2}$|$0$|$1$|
|$\frac{5\pi}{3}$|$\frac{1}{2}$|$-\frac{\sqrt3}{2}$|
|$\frac{7\pi}{4}$|$\frac{\sqrt2}{2}$|$-\frac{\sqrt2}{2}$|
|$\frac{5\pi}{6}$|$\frac{\sqrt3}{2}$|$-\frac{1}{2}$|

### Funzioni

**funzione pari**: Sia $f:]-\infty,+\infty[$. Si dice che f è una funzione pari se, $\forall x \in R$, si ha $f(-x) = f(x)$. 
*nota* -  Il suo grafico `e un insieme simmetrico rispetto all’asse delle ordinate

**funzione disapri**: Sia $f:]-\infty,+\infty[$. Si dice che f è una funzione dispari se, $\forall x \in R$, si ha $f(-x) = -f(x)$. 
*nota* -  Il suo grafico `e un insieme simmetrico rispetto all’origine

**funzione periodica**: $f$ si dice periodica se esiste un numero positivo $T$ (periodo) tale che, per ogni $x \in R$, si ha $f(x+T) = f(x)$.

#### Immagine

Si indica con $f(X)$ l'immagine di $f$, alcuni dei concetti legati ad $f(X)$ vengono per definizione attribuiti ad $f$.

$f$ può essere limitata, limitata inferiormente o limitata superiormente se lo è l'insieme numerico $f(X)$.

**estremo inferiore**: si indica con $inf_{x \in X} f(X)$
*nota* -  se $f$ ha il minimo, esso viene chiamato minimo assoluto di $f$ in $X$.

**estremo superiore**: si indica con $sup_{x \in X} f(X)$
*nota* -  se $f$ ha il massimo, esso viene chiamato massimo assoluto di $f$ in $X$.

**estremi relativi**

- un punto $c \in (a, b)$ è detto punto di minimo relativo per $f$ se esiste un suo intorno $I=]c-r,c+r[$ tale che $f(X) \ge f(c)$ $\forall x \in I$.
- un punto $c \in (a, b)$ è detto punto di massimo relativo per $f$ se esiste un suo intorno $I=]c-r,c+r[$ tale che $f(X) \le f(c)$ $\forall x \in I$.

*nota* - Un punto di estremo assoluto è anche di estremo relativo, ma non vale il viceversa.ù

#### Funzioni monotone 

$f$ nell'intervallo $(a, b)$ è monotona se verifica una delle seguenti condizioni:

- crescente se $x\lt y$ $\Rightarrow f(x) \le f(y)$
- strettamente crescente se $x\lt y$ $\Rightarrow f(x) < f(y)$
- decrescente se $\lt y$ $\Rightarrow f(x) \ge f(y)$
- strettamente decrescente se $x\lt y$ $\Rightarrow f(x) > f(y)$
- crescente se $x\lt y \Rightarrow f(x) \le f(y)$
- strettamente crescente se $x\lt y \Rightarrow f(x) < f(y)$
- decrescente se $x\lt y \Rightarrow f(x) \ge f(y)$
- strettamente decrescente se $x\lt y \Rightarrow f(x) > f(y)$

*nota* - le funzioni strettamente monotone sono iniettive.

**Teorema** La funzione $f$ è crescente (risp. decrescente) nel punto $c$ se e solo se esiste un intorno $I_s(c)$ tale che, per ogni $x \in I_s(c)$ \ $\{c\}$ si abbia $r(x) > 0.

**Dimostrazione** Supponiamo che $r(x)>0$ in $I_s(c)$ \ $\{c\}$. In $]c-s, c[$ il denominatore di $r$ è negativo, quindi lo è anche il numeratore: dunque $f(x) < f(c)$. In $]c, c+s[$ il denominatore di $r$ è positivo, quindi lo è anche il numeratore: dunque, $f(x)>f(c)$. Ne segue ceh $f$ è crescente nel punto c. IL viceversa si prova allo stesso modo.

#### Funzioni elementari

|funzione|intervallo di definizione|
|:---:|:---:|
|funzione costante|$]-\infty , + \infty[$|
|funzione identità|$]-\infty , + \infty[$|
|funzione esponenziale $x^{n}$|$]-\infty , + \infty[$|
|funzione esponenziale $x^{-n}$|$]-\infty , + \infty[$ \ $\{0\}$|
|funzione esponenziale $x^{\frac{m}{n}}$ $\frac{m}{n}>0$|$[0, +\infty[$|
|funzione esponenziale $x^{\frac{m}{n}} $| $\frac{m}{n}<0$|$]0, +\infty[$|
|funzione esponenziale $x^s$ $s \in R$ \ $Q$ $s\ge0$|$[0, +\infty[$|
|funzione esponenziale $x^s$ $s \in R$ \ $Q$ $s < 0$|$]0, +\infty[$|
|funzione esponenziale $a^x$ $a > 0, a \ne 1$|$]-\infty, + \infty[$|
|funzione logaritmica $log_a x, a > 0, a \ne 1 $|$]0, +\infty[$|
|coseno e seno |$]-\infty, +\infty[$|
|tangente|$]-\infty, + \infty[$ \ $\frac{\pi}{2} +2k\pi$|
|arcocoseno e arcoseno|$[-1,+1]$|
|arctangente|$]\frac{-\pi}{2}, +\frac{\pi}{2}[$|
