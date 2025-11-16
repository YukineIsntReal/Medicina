# Cinematica del Punto Materiale

La **cinematica** è la branca della meccanica che descrive il moto dei corpi senza indagarne le cause (che sono invece oggetto della dinamica). Si concentra sulla descrizione della posizione, della velocità e dell'accelerazione di un punto materiale nel tempo.

## 1. Posizione, Spostamento e Traiettoria

Per descrivere il moto di un punto materiale, è necessario definire un sistema di riferimento (ad esempio, un sistema di assi cartesiani $Oxyz$).

### Posizione e Vettore Spostamento
La **posizione** del punto in un dato istante $t$ è individuata dal **vettore posizione** $\vec{r}(t)$, che va dall'origine $O$ al punto $P$:
$$\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j} + z(t)\hat{k}$$
dove $x(t)$, $y(t)$ e $z(t)$ sono le coordinate del punto e $\hat{i}, \hat{j}, \hat{k}$ sono i versori (vettori di modulo unitario) degli assi.

Lo **spostamento** $\Delta\vec{r}$ tra due istanti $t_1$ e $t_2$ è la variazione del vettore posizione:
$$\Delta\vec{r} = \vec{r}(t_2) - \vec{r}(t_1)$$
Lo spostamento è un vettore e non va confuso con la *distanza percorsa*, che è uno scalare.

### Traiettoria e Legge Oraria
La **traiettoria** è la linea geometrica descritta dal punto materiale durante il suo moto. È l'insieme di tutte le posizioni $\vec{r}(t)$ al variare del tempo $t$.

La **legge oraria** è la funzione vettoriale $\vec{r}(t)$ (o le sue componenti scalari $x(t), y(t), z(t)$) che definisce la posizione del punto in ogni istante di tempo.

---

## 2. Velocità

### Velocità Media
La **velocità vettoriale media** $\vec{v}_m$ in un intervallo di tempo $\Delta t = t_2 - t_1$ è il rapporto tra il vettore spostamento e l'intervallo di tempo:
$$\vec{v}_m = \frac{\Delta\vec{r}}{\Delta t} = \frac{\vec{r}(t_2) - \vec{r}(t_1)}{t_2 - t_1}$$
Ha la stessa direzione e verso del vettore spostamento $\Delta\vec{r}$.

### Velocità Istantanea
La **velocità vettoriale istantanea** $\vec{v}(t)$ è il limite della velocità media per $\Delta t$ che tende a zero. Corrisponde alla **derivata prima** del vettore posizione rispetto al tempo:
$$\vec{v}(t) = \lim_{\Delta t \to 0} \frac{\Delta\vec{r}}{\Delta t} = \frac{d\vec{r}(t)}{dt}$$
Il vettore velocità istantanea $\vec{v}(t)$ è sempre **tangente alla traiettoria** nel punto $\vec{r}(t)$.

Il suo modulo, $|\vec{v}(t)|$, è chiamato **velocità scalare** (o *speed*).

---

## 3. Accelerazione

### Accelerazione Media
L'**accelerazione vettoriale media** $\vec{a}_m$ in un intervallo $\Delta t$ descrive la rapidità con cui varia il vettore velocità:
$$\vec{a}_m = \frac{\Delta\vec{v}}{\Delta t} = \frac{\vec{v}(t_2) - \vec{v}(t_1)}{t_2 - t_1}$$

### Accelerazione Istantanea
L'**accelerazione vettoriale istantanea** $\vec{a}(t)$ è il limite dell'accelerazione media per $\Delta t$ che tende a zero. Corrisponde alla **derivata prima** della velocità (o alla **derivata seconda** della posizione) rispetto al tempo:
$$\vec{a}(t) = \lim_{\Delta t \to 0} \frac{\Delta\vec{v}}{\Delta t} = \frac{d\vec{v}(t)}{dt} = \frac{d^2\vec{r}(t)}{dt^2}$$
L'accelerazione descrive sia la variazione del *modulo* della velocità (accelerazione tangenziale) sia la variazione della *direzione* della velocità (accelerazione normale o centripeta).

---

## 4. Studio dei Moti

### Moti Rettilinei
Il moto avviene lungo una linea retta (es. l'asse $x$). I vettori diventano scalari.
$\vec{r}(t) = x(t)\hat{i}$, $\vec{v}(t) = v(t)\hat{i}$, $\vec{a}(t) = a(t)\hat{i}$.

#### A. Moto Rettilineo Uniforme (MRU)
* **Definizione:** Velocità costante ($v = \text{costante}$).
* **Accelerazione:** $a = 0$.
* **Legge oraria:** $x(t) = x_0 + v(t - t_0)$
    (Assumendo $t_0 = 0$: $x(t) = x_0 + vt$)

#### B. Moto Rettilineo Uniformemente Accelerato (MRUA)
* **Definizione:** Accelerazione costante ($a = \text{costante}$).
* **Legge della velocità:** $v(t) = v_0 + a(t - t_0)$
    (Assumendo $t_0 = 0$: $v(t) = v_0 + at$)
* **Legge oraria:** $x(t) = x_0 + v_0(t - t_0) + \frac{1}{2}a(t - t_0)^2$
    (Assumendo $t_0 = 0$: $x(t) = x_0 + v_0t + \frac{1}{2}at^2$)
* **Relazione (indipendente dal tempo):** $v_f^2 - v_i^2 = 2a\Delta x$

#### C. Caduta Libera
È un caso specifico di MRUA, dove l'accelerazione è l'**accelerazione di gravità** $\vec{g}$ (diretta verso il basso).
Scegliendo l'asse $y$ verticale verso l'alto:
* $a_y = -g \approx -9.81 \, \text{m/s}^2$
* $v_y(t) = v_{0y} - gt$
* $y(t) = y_0 + v_{0y}t - \frac{1}{2}gt^2$

### Moti Curvilinei

#### A. Moto Parabolico (Moto dei Proiettili)
È la composizione di due moti indipendenti (principio di sovrapposizione):
1.  **Asse $x$ (orizzontale):** MRU ($a_x = 0$)
2.  **Asse $y$ (verticale):** MRUA (con $a_y = -g$)

Dato un vettore velocità iniziale $\vec{v}_0$ con angolo $\theta$ rispetto all'orizzontale:
* $v_{0x} = v_0 \cos\theta$
* $v_{0y} = v_0 \sin\theta$

Leggi orarie (assumendo $x_0=0, y_0=0$):
* $x(t) = (v_0 \cos\theta) t$
* $y(t) = (v_0 \sin\theta) t - \frac{1}{2}gt^2$

Ricavando $t$ dalla prima ($t = \frac{x}{v_0 \cos\theta}$) e sostituendo nella seconda, si ottiene l'**equazione della traiettoria**:
$$y(x) = (\tan\theta)x - \left( \frac{g}{2v_0^2\cos^2\theta} \right)x^2$$
Questa è l'equazione di una **parabola** con concavità verso il basso.

#### B. Moto Circolare Uniforme (MCU)
* **Traiettoria:** Circonferenza di raggio $R$.
* **Velocità scalare:** Modulo della velocità $|\vec{v}| = v$ è **costante**.
* **Vettore velocità:** $\vec{v}$ cambia costantemente direzione (essendo sempre tangente alla circonferenza).
* **Accelerazione Centripeta:** A causa della variazione della *direzione* della velocità, esiste un'accelerazione. È diretta **verso il centro** della circonferenza ed è chiamata **accelerazione centripeta** ($a_c$).
* **Modulo:** $a_c = \frac{v^2}{R}$
    (Se si usa la velocità angolare $\omega = v/R$, allora $a_c = \omega^2 R$)

#### C. Moto Armonico Semplice (MAS)
Il moto armonico è un moto periodico fondamentale (es. un'oscillazione). Può essere visto come la proiezione di un moto circolare uniforme su un suo diametro.
* **Legge oraria:** $x(t) = A \cos(\omega t + \phi)$
* $A$: **Ampiezza** (massimo spostamento dall'origine).
* $\omega$: **Pulsazione** (o frequenza angolare), legata al periodo $T$ (tempo per un'oscillazione completa) da $\omega = \frac{2\pi}{T}$.
* $(\omega t + \phi)$: **Fase** del moto.
* $\phi$: **Fase iniziale** (o costante di fase), dipende dalla posizione all'istante $t=0$.

Derivando la posizione, si ottengono velocità e accelerazione:
* **Velocità:** $v(t) = \frac{dx}{dt} = -A\omega \sin(\omega t + \phi)$
* **Accelerazione:** $a(t) = \frac{dv}{dt} = -A\omega^2 \cos(\omega t + \phi)$

Si noti la relazione fondamentale del MAS:
$$a(t) = -\omega^2 x(t)$$
L'accelerazione è proporzionale e opposta allo spostamento (questa sarà la base per la *dinamica* del moto armonico, cfr. Legge di Hooke).