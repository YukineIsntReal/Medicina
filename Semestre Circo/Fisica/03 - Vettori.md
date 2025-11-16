## 1. Definizione e Rappresentazione

Mentre una grandezza scalare è definita solo da un numero (magnitudine), una **grandezza vettoriale** è un'entità matematica definita da tre proprietà:

1.  **Modulo (o Magnitudine):** Un numero reale positivo che rappresenta l'intensità della grandezza (es. $10 \, \text{N}$). Si indica con $|\vec{v}|$ o $v$.
2.  **Direzione:** La retta geometrica su cui giace il vettore.
3.  **Verso:** L'orientamento lungo la retta (uno dei due sensi possibili).

Si rappresenta graficamente come una **freccia**.

> Un vettore $\vec{v}$ è diverso da un vettore $\vec{w}$ se differisce in *almeno una* di queste tre proprietà.

---

## 2. Componenti Cartesiane e Versori

Per descrivere un vettore analiticamente (cioè con numeri), lo si scompone lungo un sistema di assi cartesiani ortogonali (es. $x, y, z$).

Si definiscono i **versori** degli assi: vettori di modulo unitario ($|\vec{v}|=1$) che indicano la direzione e il verso positivi di ciascun asse.
* $\hat{\imath}$: versore dell'asse $x$
* $\hat{\jmath}$: versore dell'asse $y$
* $\hat{k}$: versore dell'asse $z$

Un qualsiasi vettore $\vec{v}$ può essere scritto come la somma delle sue **componenti** lungo gli assi:
$$\vec{v} = v_x \hat{\imath} + v_y \hat{\jmath} + v_z \hat{k}$$

Dove $v_x$, $v_y$ e $v_z$ sono numeri reali (scalari) che rappresentano la "proiezione" del vettore su ciascun asse.

### Modulo
Il modulo (lunghezza) del vettore si calcola applicando il Teorema di Pitagora nello spazio:
$$|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$$

---

## 3. Operazioni con i Vettori

### 3.1 Prodotto per uno Scalare
Moltiplicare un vettore $\vec{v}$ per uno scalare $k$ (un numero reale) produce un nuovo vettore $k\vec{v}$:
$$k\vec{v} = (k v_x) \hat{\imath} + (k v_y) \hat{\jmath} + (k v_z) \hat{\k}$$

* Il **modulo** viene moltiplicato per $|k|$.
* La **direzione** non cambia.
* Il **verso** rimane lo stesso se $k>0$, si inverte se $k<0$.

### 3.2 Somma e Differenza di Vettori
La somma (o differenza) di due vettori $\vec{a}$ e $\vec{b}$ si ottiene sommando (o sottraendo) le loro componenti omologhe. Il risultato è un nuovo vettore.

Siano $\vec{a} = a_x \hat{\imath} + a_y \hat{\jmath} + a_z \hat{k}$ e $\vec{b} = b_x \hat{\imath} + b_y \hat{\jmath} + b_z \hat{k}$.

**Somma:** $\vec{s} = \vec{a} + \vec{b}$
$$\vec{s} = (a_x + b_x) \hat{\imath} + (a_y + b_y) \hat{\jmath} + (a_z + b_z) \hat{k}$$
*(Graficamente: regola del parallelogramma o metodo punta-coda)*

**Differenza:** $\vec{d} = \vec{a} - \vec{b}$
$$\vec{d} = (a_x - b_x) \hat{\imath} + (a_y - b_y) \hat{\jmath} + (a_z - b_z) \hat{k}$$

---

## 4. Prodotti tra Vettori

Esistono due modi diversi di "moltiplicare" due vettori, con risultati profondamente diversi.

### 4.1 Prodotto Scalare (Dot Product)
Il prodotto scalare tra $\vec{a}$ e $\vec{b}$ **restituisce uno SCALARE** (un numero).

**Definizione Geometrica:**
$$\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$$
dove $\theta$ è l'angolo compreso tra i due vettori.

**Definizione Analitica (Componenti):**
$$\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z$$

> **Significato Fisico:** Misura la proiezione di un vettore sull'altro.
> L'esempio più importante è il **Lavoro** di una forza: $L = \vec{F} \cdot \vec{s}$.
>
> **Proprietà chiave:** Se $\vec{a} \cdot \vec{b} = 0$ (e $\vec{a}, \vec{b} \neq 0$), significa che $\cos(\theta)=0$, quindi i due vettori sono **perpendicolari (ortogonali)**.

### 4.2 Prodotto Vettoriale (Cross Product)
Il prodotto vettoriale tra $\vec{a}$ e $\vec{b}$ **restituisce un nuovo VETTORE** $\vec{c}$.

$$\vec{c} = \vec{a} \times \vec{b}$$

Il vettore $\vec{c}$ ha le seguenti proprietà:
1.  **Modulo:**
    $$|\vec{c}| = |\vec{a}| |\vec{b}| \sin(\theta)$$
    (Corrisponde all'area del parallelogramma formato da $\vec{a}$ e $\vec{b}$).
2.  **Direzione:** $\vec{c}$ è perpendicolare sia ad $\vec{a}$ che ad $\vec{b}$ (è perpendicolare al piano che li contiene).
3.  **Verso:** Dato dalla **regola della mano destra**. (Se si allinea il pollice con $\vec{a}$ e l'indice con $\vec{b}$, il medio indica il verso di $\vec{c}$).

> **Significato Fisico:** Usato per grandezze che dipendono da una "rotazione" o un "momento".
> In fisica è il **Momento di una forza** ($\vec{M} = \vec{r} \times \vec{F}$). In biomeccanica, questo rappresenta il **torque** (momento torcente) che causa la rotazione di un'articolazione.
>
> **Proprietà chiave:** È anti-commutativo: $\vec{a} \times \vec{b} = - (\vec{b} \times \vec{a})$.

---
## Collegamenti
- [[Grandezze Fisiche e Misura]]