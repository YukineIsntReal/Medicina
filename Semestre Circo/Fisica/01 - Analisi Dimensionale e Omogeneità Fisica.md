Le equazioni fisiche, chimiche e fisiologiche non sono semplici relazioni tra numeri puri. Sono relazioni tra **grandezze fisiche** misurabili.

L'**analisi dimensionale** è l'insieme di regole che ci permette di manipolare e verificare queste equazioni, assicurando che siano coerenti.

---

## 1. Principio di Omogeneità Dimensionale

Il principio fondamentale di qualsiasi equazione fisica valida è l'**omogeneità dimensionale**.

> **Principio di Omogeneità:** Un'equazione è fisicamente sensata solo se ogni termine sommato o uguagliato ha le *stesse dimensioni fisiche*.

Se un'equazione è nella forma:
$A + B = C$

Allora deve essere vero che le dimensioni di $A$, $B$, e $C$ sono identiche:
$[A] = [B] = [C]$

(Dove $[X]$ si legge "la dimensione di $X$").

**Esempio:**
Non è possibile sommare una massa a una lunghezza. L'espressione $5 \, \text{kg} + 2 \, \text{m}$ non ha alcun senso fisico.
L'analisi dimensionale previene questo tipo di errori.

---

## 2. Algebra delle Dimensioni

Le dimensioni fisiche (come $M$, $L$, $T$) seguono regole algebriche specifiche.

### Addizione e Sottrazione
Si possono sommare o sottrarre **solo** grandezze con le stesse dimensioni. Il risultato mantiene la stessa dimensione.
* $[L] + [L] = [L]$
* $[M \cdot L \cdot T^{-1}] - [M \cdot L \cdot T^{-1}] = [M \cdot L \cdot T^{-1}]$

### Moltiplicazione e Divisione
Le dimensioni si moltiplicano e si dividono come monomi algebrici.
* **Velocità ($v$):** $v = \frac{\text{spazio}}{\text{tempo}} \implies [v] = \frac{L}{T} = L \cdot T^{-1}$
* **Forza ($F$):** $F = m \cdot a \implies [F] = [m] \cdot [a] = M \cdot (L \cdot T^{-2}) = M \cdot L \cdot T^{-2}$

### Potenze e Radici
Le dimensioni sono elevate alla stessa potenza della grandezza.
* **Area ($A$):** $A = \text{lato}^2 \implies [A] = [L]^2 = L^2$
* **Volume ($V$):** $V = \text{lato}^3 \implies [V] = [L]^3 = L^3$
* **Periodo Pendolo ($T_p$):** $T_p \propto \sqrt{L} \implies [T_p] = [L]^{1/2} = L^{1/2}$ (in questo caso proporzionale alla radice della lunghezza)

### Costanti Numeriche e Argomenti di Funzioni
Le **costanti numeriche pure** (es. $2$, $\pi$, $\frac{1}{2}$) sono **adimensionali**.
* $[ \pi ] = 1$ (adimensionale)

**REGOLA CRITICA:** Gli argomenti di funzioni trascendentali (come $\log$, $\exp$, $\sin$, $\cos$) devono essere **adimensionali** (numeri puri).
* In un'equazione di decadimento $N(t) = N_0 \cdot e^{-\lambda t}$:
    * L'esponente $(-\lambda t)$ *deve* essere adimensionale: $[\lambda \cdot t] = 1$.
    * Poiché $[t] = T$, la costante di decadimento $\lambda$ deve avere dimensioni $[ \lambda ] = T^{-1}$ (unità: $\text{s}^{-1}$), in modo che $T^{-1} \cdot T = 1$.

---

## 3. Applicazioni in Medicina e Fisica

### 3.1 Controllo di Coerenza delle Equazioni
L'analisi dimensionale è il primo e più potente strumento per verificare la correttezza di una formula.

**Esempio:** Verifichiamo l'equazione del moto $s = v_0 t + \frac{1}{2} a t^2$
* $[s] = L$
* Termine 1: $[v_0 t] = [v_0] \cdot [t] = (L \cdot T^{-1}) \cdot T = L$
* Termine 2: $[\frac{1}{2} a t^2] = [\frac{1}{2}] \cdot [a] \cdot [t^2] = 1 \cdot (L \cdot T^{-2}) \cdot (T^2) = L$

Tutti i termini hanno dimensione $L$. L'equazione è dimensionalmente omogenea e corretta.

### 3.2 Deduzione delle Unità di Misura
Permette di trovare l'unità di misura di qualsiasi grandezza derivata nel [[Grandezze Fisiche e Misura#Sistema Internazionale (SI)|Sistema Internazionale]].

**Esempio: Pressione ($P$)**
La pressione è definita come Forza per unità di Area ($P = F/A$).
* $[F] = M \cdot L \cdot T^{-2}$
* $[A] = L^2$
* $[P] = \frac{[F]}{[A]} = \frac{M \cdot L \cdot T^{-2}}{L^2} = M \cdot L^{-1} \cdot T^{-2}$
* L'unità SI è il Pascal ($\text{Pa}$), che infatti corrisponde a $\frac{\text{kg}}{\text{m} \cdot \text{s}^2}$.

**Esempio Medico: Clearance ($Cl$)**
La *clearance* di una sostanza (es. creatinina) è definita come il volume di plasma "ripulito" dalla sostanza nell'unità di tempo.
* $\text{Clearance} = \frac{\text{Volume}}{\text{Tempo}}$
* $[Cl] = \frac{L^3}{T} = L^3 \cdot T^{-1}$
* L'unità di misura è infatti $\frac{\text{mL}}{\text{min}}$ o $\frac{\text{L}}{\text{h}}$.

---
