# Capitolo 2

### Successioni di numeri reali

Una successione di numeri reali è una funzione reale  definita in $N$, $f:N \rightarrow R$. Se $n \in N$, si usa la notazione $a_n = f(n)$, in tal modo la successione viene identificata con l'insieme dei sui elementi : $\{a_n\}$. L'elemento generico $a_n$ viene detto elemento di posto $n$. Si dice che la successione verifica definitivamente una condizione $P$ se esiste $\alpha \in N$ tale che, per ogni $n > \alpha$, l'elemento $a_n$ verifica $p$.

*nota* -  La successione è limitata se lo è l'insieme dei suoi termini, il minimo, il massimo, estremo superiore ed inferiore di una successione conincidono con quelli relativi all'insieme dei suoi termini.

**Proposizione** Una successione $D$ limitata è limitata.
**Dimostrazione** Se si ha $h \le a_n \le k$ per ogni $n > \alpha $, posto $h' = min\{h, a_1, ..., a_\alpha\}$, $k' = max\{k, a_1, ..., a_\alpha\}$ si ha $h' \le a_n \le k'$ per ogni $n \in N$.

#### Successioni regolari 

**limite di una successione** Sia $l$ un numero reale. Si dice che la successione $\{a_n\}$ converge o tende ad $l$ o che $l$ è il limite della successione, e si scrive $a_n \rightarrow l$ o $ \lim{a_n} = l $ se è verificata la seguente condizione: $\forall \epsilon > 0$ $\exist \alpha \in N:n > a \Rightarrow |a_n-l| < \epsilon$.

*nota* - Se $l = 0$ la successione è detta infinitesima.

**Teorema dell'unicità del limite** Se una successione converge, il suo limite è unico.
**Dimostrazione** Supponiamo per assurdo che $a_n \rightarrow l e a_n \rightarrow L, con, ad esempio l < L$. Scelto $\epsilon$ tale che $0 < \epsilon \frac{L-l}{2}$, $D$ si ha $a_n < l + \epsilon < L- \epsilon < a_n$, assurdo.

**Teorema della permanenza del segno** Se $a_n \rightarrow l$ (risp. $l < 0$), allora $D$ si ha $a_n > 0$ (risp. $a_n < 0$).
**Dimostrazione** Supponiamo $l > 0$. Scelto $\epsilon$ tale che $0 < \epsilon < l$, $D$ si ha $a_n > l - \epsilon > 0$. Il caso $l<0$ si prova in modo simile. Generalizzando questo risultato, possiamo, affermare che se $a_n \rightarrow l$ e $h$ < $l$ (risp. $k >l$), $D$ si ha $a_n > h$ (risp. $a_n < k$).

**Teorema di confronto per successioni convergenti** Se $a_n \le b_n \le c_n$, per ogni $n \in N$ e $a_n \rightarrow l, c_n\rightarrow l$, allora $b_n \rightarrow l$.
**Dimostrazione** Dato che $D$ si ha sia $l - \epsilon < a_n < l+\epsilon$ che $l-\epsilon < c_n < l + \epsilon$, D si avrà $l-\epsilon < a_n \le n_n \le c_n < l+ \epsilon$.

**La successione diverge** Si dice che la successione $\{a_n\}$ diverge o tende a $+\infty$ (risp. $-\infty$), e si scrive $a_n \rightarrow +\infty$ o $\lim{a_n} = +\infty$ (risp. $-\infty$) se è verificata la seguente condizione: $\forall k > 0$ $\exist \alpha \in N: n > \alpha \Rightarrow a_n > k$ ($a_n < -k$).

**Teorema di confronto per successioni divergenti** Se $a_n \le b_n$ per ogni $n \in N$ e $a_n \rightarrow +\infty$,allora $b_n \rightarrow +\infty$; se $b_n \rightarrow -\infty$, allora $a_n \rightarrow -\infty$
**Dimostrazione** Se $a_n \rightarrow +\infty$, allora $D$ si ha $a_n >k $, ne segue cge $b_n \ge a_n > k$; l'altro caso si prova allo stesso modo.

**Successione regolare** Una successione è detta regolare se converge o diverge. Una funzione non regolare è detta oscillante.

**Successioni e valore assoluto** Si prova che:
1. Se $a_n \rightarrow l$, allora $|a_n| \rightarrow |l|$. Infatti è possibile provare che $||a_n|-|l|| \le |a_n-l|$.
2. Se $a_n \rightarrow +\infty$ oppure $a_n \rightarrow -\infty$, si ha $|a_n| \rightarrow +\infty$. Se $|a_n| \rightarrow +\infty$, la successione $\{a_n\}$ è detta infinitamente grande.

**Regolarità e limitatezza** Si hanno le seguenti affermazioni:

- Una successione convergente è limitata.
- Una successione che diverge a $+\infty$ è limitata inferiormente e non è limitata superiormente.
- UNa successione che diverge a $-\infty$ è limitata superiormente e non è limitata inferiormente.

**Successioni monotone** Si dice che la successione $\{a_n\}$ è monotona se, per ogni $n \in N$ o definitivamente, verifica una delle seguenti condizioni:

- $a_n > a_{n+1}$ (successione strettamente decrescente)
- $a_n \ge a_{n+1}$ (successione decrescente)
- $a_n < a_{n+1}$ (successione strettamente crescente)
- $a_n \le a_{n+1}$ (successione crescente)

*nota* - Le successioni monotone costituiscono una categoria di successioni sicuramente regolari.

*nota* - Osserviamo che per una successione crescente il termine a1 è il minimo, per una successione decrescente è il massimo.

**Operazioni con i limiti delle successioni** I seguenti risultati saranno molto utili per calcolare i limiti di successioni la cui legge di definizione ` e espressa mediante operazioni elementari fra altre successioni delle quali sia noto il comportamento al limite.

1. Sia $\{a_n\}$ una successione regolare e sia $c$ un numero reale. Prendiamo in considerazione la successione $\{ca_n\}$

- se $a_n \rightarrow l$, allora $ca_n \rightarrow cl$.
  - Se $c = 0$, la tesi è ovvia. Se $c \ne 0$, per ottenere $|ca_n − cl| < \epsilon$ basta osservare che $D$ si ha $|a_n −l| < \frac{\epsilon}{|c|}$.
- se $a_n \rightarrow +\infty e c >0$, allora $ca_n \rightarrow +\infty$.
  - Per ottenere $ca_n > k$ basta osservare che $D$ si ha $a_n > \frac{k}{c}$.
- se $a_n \rightarrow +\infty$ e $c < 0$, allora $ca_n \rightarrow −\infty$.
  - Per ottenere $ca_n < −k$ basta osservare che $D$ si ha $a_n > \frac{−k}{c}$.
- se $a_n \rightarrow −\infty$ e $c>0$, allora $ca_n \rightarrow −\infty$.
- se $a_n \rightarrow −\infty$ e $c<0$, allora $ca_n \rightarrow +\infty$.

2. Date due successioni {$a_n$} e {$b_n$} prendiamo in considerazione la successione somma {$a_n+b_n$}

- Se $a_n \rightarrow l$ e $b_n \rightarrow L$, allora $a_n + b_n \rightarrow l + L$.
  - Fissato $\epsilon >0$, esistono $\alpha, \beta \in N $ tali che per $n > \alpha$ si ha |$a_n - l$| $< \frac{\epsilon}{2}$ e per $n > \beta $ si ha |$b_n - L$| $< \frac{\epsilon}{2}$. per $n > max(\alpha,\beta)$ si ha |$(a_n + b_n)- (l -L)$| $\le |a_n -l| + |b_n -L| < \epsilon$.
- Se $a_n \rightarrow +\infty$ ed esiste un numero $h \le b_n$ per ogni $n \in N$, allora $a_n + b_n \rightarrow \infty$.
  - Si ha $a_n + b_n \ge a_n +h$ quindi, dato che $d$ si ha $a_n > k -h$, ne segue $a_n + b_n>k$.

3. Date due successioni {$a_n$} e {$b_n$} prendiamo in considerazione la successione prodotto {$a_n b_n$}

- Se $a_n \rightarrow l$ e $b_ \rightarrow L$, allora $a_n b_n \rightarrow l L$.
- Se $a_n \rightarrow 0$ e {$b_n$} è limitata, allora $a_n \rightarrow l$.
  - Sia $M \ge |b_n|$ per ogni $n$, allora $|a_n b_n| \le |a_n|M < \epsilon$ appena $|a_n| < \frac{\epsilon}{M}$ 
- Se $a_n \rightarrow +\infty$ ed esiste un numero positivo $h \le b_n$ per ogni $n \in N$, allora $a_n b_n \rightarrow +\infty$.
  - Basta osservare che $a_n b_n \ge a_n h > k$ appena $a_n > \frac{k}{h}$.

4. Sia $\{a_n\}$ una successione regolare e D non nulla, prensdiamo in considerazione la successione reciproca {$\frac{1}{a_n}$}

- Se $a_n \rightarrow l \ne 0$, allora $\frac{1}{a_n} \rightarrow \frac{1}{l}$.
- Se $a_n \rightarrow 0$, allora $\frac{1}{a_n} \rightarrow \infty$.
- Se $a_n \rightarrow \infty$, allora $\frac{1}{a_n} \rightarrow 0$.

5. Date due successioni {$a_n$} e {$b_n$}, con $b_n \ne 0$, prendiamo in considerazione la successione quoziente {$\frac{a_n}{b_n}$}. Essa viene studiata utilizzando scrivendola nella forma $a_n \frac{1}{b_n}$.

#### Funzioni elementari comuni

- Successione potenza {$n^x$}, $x \in R$
  - Se x = 0, la successione è costante.
  - Se x > 0, si ha $n^x \rightarrow +\infty$.
  - Se x < 0, si ha $n^x=\frac{1}{n^-x} \rightarrow 0$.
- Successioni in forma di polinomio $x_n = a_0 n^p + a_1n^{p-1}+...+ a_p$
  - $x_n = n^p(a_0 + \frac{a_1}{n}+...+\frac{a_p}{n^p})$ si ha $n^p \rightarrow +\infty$ e la parentesi tende ad $a_0$ $x_n \rightarrow +infty se a_0 > 0, x_n \rightarrow - \infty$ se $a_0 < 0$.
- Successione in forma di funzione razionale $x_n = \frac{a_0n^p+a_1n^{p-1}+...+a_p}{b_0n^q+b_1n^{p-1}+...+b_p}$
  - $x_n = n^{p-q} (\frac{a_0+\frac{a_1}{n}+...+\frac{a_p}{n^p}}{b_0+\frac{b_1}{n}+...+\frac{b_q}{n^q}})$ se $p = q$ si ha $x_n \rightarrow \frac{a_0}{b_0}$; se $p < q$ $x_n \rightarrow 0$; se p > q $x_n \rightarrow +\infty$ se $a_0, b_0$ hanno lo stesso segno $x_n \rightarrow -\infty$.

- Successione geometrica {$a^n$}
  - a > 1, $a^n \rightarrow +\infty$.
  - a = 1, $a^n \rightarrow 1$
  - 0 < a < 1, $a^n \rightarrow 0$
  - a < -1, $a^n \rightarrow \infty$.

- Successione {$a^{x_n}$}
  - $x_n \rightarrow l, a^{x_n} \rightarrow a^l$.
  - a > 1, $x_n \rightarrow +\infty, a^{x_n} \rightarrow +\infty$.
  - a > 1, $x_n \rightarrow -\infty, a^{x_n} \rightarrow 0$.
  - a < 1, $x_n \rightarrow +\infty, a^{x_n} \rightarrow 0$.
  - a < 1, $x_n \rightarrow -\infty, a^{x_n} \rightarrow +\infty$.

- Successione {$\log_a x_n$}
  - $x_n \rightarrow l > 0$, si ha $\log_a x_n \rightarrow \log_a l $.
  - a > 1,$x_n \rightarrow +\infty$, $\log_a x_n \rightarrow +\infty$.
  - a > 1,$x_n \rightarrow 0$, $log_a xn → −\infty$.
  - a < 1,$x_n \rightarrow +\infty$, $log_a x_n \infty$.
  - a < 1,$x_n \rightarrow 0$, $log_a x_n \rightarrow +\infty$.

- Il numero $e$ 
  - $(1+\frac{1}{x_n})^{x_n} \rightarrow e$.
  - $\frac{\log(1+x_n)}{x_n} \rightarrow 1$.
  - $\frac{\log(1-x_n)^\alpha-1}{x_n} \rightarrow \alpha$.

- Funzioni trigonometriche
  - $\frac{\sin a_n}{a_n} \rightarrow 1$.
  - $\frac{\tan a_n}{a_n} \rightarrow 1$.
  - $\frac{\arctan a_n}{a_n} \rightarrow 1$.
  - $\frac{\arcsin a_n}{a_n} \rightarrow 1$.
  - $\frac{1-\cos a_n}{a_n} \rightarrow 0$.
  - $\frac{1-\cos a_n}{(a_n)^2} \rightarrow \frac{1}{2}$.

#### Successioni definite per ricorrenza

Una successione si dice definita per riccorenza se viene dato il suo primo termine e viene fornita una legge che calcola ciascun termine in funzione del precedente.

**esempio** nella forma $a_{n+1} = f(a_n)$

$
\begin{cases}
  a_1 = 4 \\
  a_{n+1} = \sqrt{a_n}  
\end{cases}
$

- Si studia la monotonia.
- Si individua il numero $l$ che potrebbe essere l'estremo inferiore o superiore.
- $l = \lim a_n = \lim a_{n+1}$
- Si risolve l'equazione $f(l) = l$ e tra le soluzioni si cerca $l$
- se non si trova un numero $l$ la successione diverge.
