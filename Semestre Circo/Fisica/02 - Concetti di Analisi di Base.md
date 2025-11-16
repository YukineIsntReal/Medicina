Questa nota introduce i concetti matematici fondamentali del Calcolo (Derivate e Integrali) e le funzioni base per descrivere i fenomeni periodici (Funzioni Trigonometriche).

---

## 1. Funzioni Trigonometriche Elementari

Le funzioni trigonometriche (o goniometriche) descrivono la relazione tra gli angoli e i lati di un triangolo. In fisica e biologia, sono fondamentali per descrivere **fenomeni periodici e oscillatori** (es. onde sonore, segnali elettrici, pendoli).

Si definiscono a partire dalla **circonferenza goniometrica**: una circonferenza di raggio $r=1$ centrata nell'origine degli assi cartesiani.

Dato un angolo $\theta$ (misurato in **radianti**), questo identifica un punto $P(x, y)$ sulla circonferenza.
* **Seno:** $\sin(\theta) = y$ (l'ordinata del punto $P$)
* **Coseno:** $\cos(\theta) = x$ (l'ascissa del punto $P$)
* **Tangente:** $\tan(\theta) = \frac{y}{x} = \frac{\sin(\theta)}{\cos(\theta)}$

### Grafici e Proprietà
* **Periodicità:** Seno e Coseno sono periodiche con periodo $2\pi$.
    * $\sin(\theta + 2\pi) = \sin(\theta)$
    * $\cos(\theta + 2\pi) = \cos(\theta)$
* **Grafico (Sinusoide):**
    * Il grafico di $y = \sin(x)$ parte da $0$, cresce fino a $1$ (a $x=\pi/2$), torna a $0$ (a $x=\pi$), scende a $-1$ (a $x=3\pi/2$) e torna a $0$ (a $x=2\pi$).
    * Il grafico di $y = \cos(x)$ è identico, ma "sfasato" (traslato) di $\pi/2$ a sinistra. Parte da $1$ (a $x=0$), scende a $0$ (a $x=\pi/2$), ecc.
* **Identità Fondamentale:** Deriva dal Teorema di Pitagora ($x^2 + y^2 = 1$):
    $$\sin^2(\theta) + \cos^2(\theta) = 1$$

---

## 2. Concetto di Derivata

La derivata misura la **velocità istantanea di variazione** di una funzione.

Concettualmente, la derivata $f'(x)$ di una funzione $f(x)$ in un punto $x_0$ risponde alla domanda: "Quanto velocemente sta cambiando $f(x)$ *esattamente* nel punto $x_0$?"

Geometricamente, la derivata $f'(x_0)$ è il **coefficiente angolare (pendenza) della retta tangente** al grafico di $f(x)$ nel punto $(x_0, f(x_0))$.

### Definizione Formale (Limite del Rapporto Incrementale)
La derivata prima $f'(x)$ (notata anche $\frac{df}{dx}$) è definita come:
$$f'(x) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

Dove $\frac{f(x+h) - f(x)}{h}$ è il coefficiente angolare della retta *secante* tra due punti vicini. Man mano che i punti si avvicinano ($h \to 0$), la secante diventa la tangente.

### Significato Fisico
* Se $s(t)$ è la posizione al tempo $t$, $s'(t) = v(t)$ è la **velocità istantanea**.
* Se $v(t)$ è la velocità al tempo $t$, $v'(t) = a(t)$ è l'**accelerazione istantanea**.
* In medicina, $\frac{dC}{dt}$ può rappresentare il tasso di variazione della concentrazione $C$ di un farmaco nel plasma.

### Derivate Fondamentali
| Funzione $f(x)$ | Derivata $f'(x)$ |
| :--- | :--- |
| $k$ (costante) | $0$ |
| $x^n$ | $n \cdot x^{n-1}$ |
| $\sin(x)$ | $\cos(x)$ |
| $\cos(x)$ | $-\sin(x)$ |
| $e^x$ | $e^x$ |
| $\ln(x)$ | $\frac{1}{x}$ |

---

## 3. Concetto di Integrale

L'integrazione è l'operazione inversa della derivazione. Ha due significati principali:

### 3.1 Integrale Indefinito (Antiderivata)
L'integrale indefinito di una funzione $f(x)$ (indicato con $\int f(x) \,dx$) è l'insieme di tutte le funzioni $F(x)$ la cui derivata è $f(x)$.
$$\int f(x) \,dx = F(x) + C \quad \iff \quad F'(x) = f(x)$$
La costante $C$ (costante di integrazione) è necessaria perché la derivata di una costante è zero (es. sia $(x^2+3)$ che $(x^2+10)$ hanno come derivata $2x$).

### 3.2 Integrale Definito (Area)
L'integrale definito di $f(x)$ da $a$ a $b$ (indicato con $\int_{a}^{b} f(x) \,dx$) calcola l'**area netta** compresa tra il grafico di $f(x)$ e l'asse $x$, nell'intervallo $[a, b]$.

### Teorema Fondamentale del Calcolo
Questo teorema lega i due concetti in modo potente: se $F(x)$ è un'antiderivata di $f(x)$, allora:
$$\int_{a}^{b} f(x) \,dx = F(b) - F(a)$$
Permette di calcolare l'area (un concetto geometrico) usando l'antiderivata (un concetto algebrico).

### Significato Fisico
* Se $v(t)$ è la velocità, $\int_{t_1}^{t_2} v(t) \,dt = s(t_2) - s(t_1)$ è lo **spostamento totale** (l'area sotto la curva della velocità).
* In fisiologia, l'integrale del flusso sanguigno nel tempo $\int \text{Flusso}(t) \,dt$ dà il **volume total
e** di sangue passato (Gittata Cardiaca).