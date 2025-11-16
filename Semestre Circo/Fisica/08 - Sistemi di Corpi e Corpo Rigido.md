Fino ad ora abbiamo considerato il "punto materiale". Ora analizziamo sistemi composti da più punti e i corpi estesi, che possono non solo traslare, ma anche ruotare ed eventualmente deformarsi.

---

## 1. Sistemi di Punti: il Centro di Massa (CM)

Un sistema di corpi è un insieme di $N$ punti materiali.

### Definizione del Centro di Massa
Il **Centro di Massa** ($\vec{r}_{CM}$) è un punto geometrico che rappresenta la posizione "media" della massa dell'intero sistema. È una media pesata delle posizioni $\vec{r}_i$ dei singoli punti, dove il "peso" è la loro massa $m_i$.

$$\vec{r}_{CM} = \frac{m_1\vec{r}_1 + m_2\vec{r}_2 + \dots + m_N\vec{r}_N}{m_1 + m_2 + \dots + m_N} = \frac{1}{M_{\text{tot}}} \sum_{i=1}^{N} m_i \vec{r}_i$$
dove $M_{\text{tot}} = \sum m_i$ è la massa totale del sistema.

### Moto del Centro di Massa
Derivando la posizione $\vec{r}_{CM}$ si ottengono la velocità $\vec{v}_{CM}$ e l'accelerazione $\vec{a}_{CM}$ del centro di massa.
* **Quantità di Moto Totale:** La [[Quantità di Moto]] totale del sistema è $\vec{p}_{\text{tot}} = \sum m_i \vec{v}_i = M_{\text{tot}} \vec{v}_{CM}$.
* **Dinamica del CM:** Applicando la [[Dinamica del Punto Materiale#B. Secondo Principio (Legge Fondamentale)|Seconda Legge di Newton]] al sistema, si scopre che le forze interne si annullano (per il [[Dinamica del Punto Materiale#C. Terzo Principio (Principio di Azione e Reazione)|Terzo Principio]]). Il moto del CM è determinato *solo* dalla risultante delle forze *esterne*.

$$\sum \vec{F}_{\text{est}} = M_{\text{tot}} \vec{a}_{CM}$$
> "Il centro di massa di un sistema si muove come un singolo punto materiale (con tutta la massa $M_{\text{tot}}$ del sistema) soggetto alla risultante di tutte le forze esterne."
Se $\sum \vec{F}_{\text{est}} = 0$ (sistema isolato), allora $\vec{a}_{CM} = 0$ e $\vec{v}_{CM} = \text{costante}$ (Conservazione della Quantità di Moto).

---

## 2. Il Corpo Rigido

Il **corpo rigido** è un modello ideale di corpo esteso in cui la distanza tra ogni coppia di punti rimane fissa e invariata.
Il moto di un corpo rigido può essere scomposto in:
1.  **Traslazione:** Il moto del suo centro di massa (descritto da $\sum \vec{F}_{\text{est}} = M_{\text{tot}} \vec{a}_{CM}$).
2.  **Rotazione:** Il moto attorno a un asse (spesso passante per il centro di massa).

Per descrivere la rotazione, servono nuovi concetti.

### Momento Torcente ($\vec{\tau}$)
Il **momento torcente** (o momento della forza) è l'equivalente rotazionale della [[Dinamica del Punto Materiale|forza]]. Misura la capacità di una forza $\vec{F}$ di indurre una rotazione attorno a un polo $O$.
È definito dal prodotto vettoriale:
$$\vec{\tau} = \vec{r} \times \vec{F}$$
* $\vec{r}$: Vettore posizione dal polo $O$ al punto di applicazione della forza $\vec{F}$.
* Il modulo è $\tau = |\vec{r}| |\vec{F}| \sin\theta$, dove $\theta$ è l'angolo tra $\vec{r}$ e $\vec{F}$.
* Alternativamente, $\tau = F \cdot b$, dove $b = r \sin\theta$ è il **braccio** (distanza perpendicolare tra il polo e la linea d'azione della forza).

### Equilibrio del Corpo Rigido
Un corpo rigido è in **equilibrio statico** (non trasla e non ruota) se sono soddisfatte due condizioni:
1.  **Equilibrio Traslazionale:** $\sum \vec{F}_{\text{est}} = 0$ (La [[Dinamica del Punto Materiale#A. Primo Principio (Principio di Inerzia)|Dinamica]] del CM è nulla).
2.  **Equilibrio Rotazionale:** $\sum \vec{\tau}_{\text{est}} = 0$ (La somma dei momenti torcenti esterni, calcolati rispetto a un *qualsiasi* polo, è nulla).

**Applicazione: Leve**
Una leva è un'applicazione diretta dell'equilibrio rotazionale. Per una leva incernierata in un fulcro $O$, l'equilibrio ($\tau_{\text{motore}} = \tau_{\text{resistente}}$) si scrive:
$$F_m \cdot b_m = F_r \cdot b_r$$
($m$ = motore, $r$ = resistente).

---

## 3. Dinamica Rotazionale

### Momento d'Inerzia ($I$)
Il **momento d'inerzia** $I$ è l'equivalente rotazionale della massa inerziale. Misura la **resistenza** di un corpo ad essere messo in rotazione (cioè a subire un'accelerazione angolare $\alpha$).
* Dipende non solo dalla massa $m$, ma anche da *come* la massa è distribuita rispetto all'asse di rotazione $r$.
* Per un punto singolo: $I = mr^2$
* Per un sistema discreto: $I = \sum m_i r_i^2$
* L'unità di misura nel SI è $\text{kg} \cdot \text{m}^2$.

### Leggi della Dinamica Rotazionale
Esiste un'analogia perfetta tra moto traslazionale e rotazionale:

| Grandezza Traslazionale | Grandezza Rotazionale |
| :--- | :--- |
| Forza $\vec{F}$ | Momento Torcente $\vec{\tau}$ |
| Massa $m$ | Momento d'Inerzia $I$ |
| Accelerazione $\vec{a}$ | Accelerazione Angolare $\vec{\alpha}$ |
| **Legge** $\sum \vec{F} = m\vec{a}$ | **Legge** $\sum \vec{\tau} = I \vec{\alpha}$ |

### Momento Angolare ($\vec{L}$)
Il **momento angolare** (o momento della quantità di moto) è l'equivalente rotazionale della [[Quantità di Moto]].
* Per un punto materiale: $\vec{L} = \vec{r} \times \vec{p} = \vec{r} \times (m\vec{v})$
* Per un corpo rigido che ruota con velocità angolare $\omega$: $L = I\omega$

La forma più generale della seconda legge rotazionale (l'analogo di $\vec{F} = d\vec{p}/dt$) è:
$$\sum \vec{\tau}_{\text{est}} = \frac{d\vec{L}_{\text{tot}}}{dt}$$

**Conservazione del Momento Angolare**
> "Se il momento torcente esterno totale $\sum \vec{\tau}_{\text{est}}$ agente su un sistema è nullo, il momento angolare totale $\vec{L}_{\text{tot}}$ del sistema si conserva."
$$\sum \vec{\tau}_{\text{est}} = 0 \implies \vec{L}_{\text{tot}} = \text{costante}$$
($I_i \omega_i = I_f \omega_f$). È il principio sfruttato da una pattinatrice che stringe le braccia per ruotare più velocemente (diminuisce $I$, aumenta $\omega$).

---

## 4. Corpi Deformabili (Elasticità)

Si abbandona l'ipotesi di corpo rigido. Le forze possono deformare i materiali.

* **Sforzo (Stress, $\sigma$):** Misura l'intensità della forza applicata *per unità di superficie*. È la causa della deformazione.
    $$\sigma = \frac{F_{\perp}}{A}$$
    (Unità di misura: $N/m^2 = \text{Pascal, Pa}$).

* **Deformazione (Strain, $\epsilon$):** Misura l'effetto della deformazione, come variazione relativa della dimensione (es. lunghezza). È adimensionale.
    $$\epsilon = \frac{\Delta L}{L_0}$$

### Legge di Hooke Generalizzata e Modulo di Young ($E$)
Per molti materiali, in un regime *elastico* (dove la deformazione è reversibile), sforzo e deformazione sono direttamente proporzionali.
$$\sigma = E \cdot \epsilon$$
* $E$ è il **Modulo di Young** (o modulo di elasticità). È una proprietà intrinseca del materiale (misurata in $Pa$) e ne definisce la rigidità (quanto è difficile deformarlo).
* Sostituendo le definizioni $\sigma$ e $\epsilon$:
    $$\frac{F}{A} = E \frac{\Delta L}{L_0} \implies F = \left( \frac{EA}{L_0} \right) \Delta L$$
* Questa è la [[Dinamica del Punto Materiale#E. Forza Elastica (Legge di Hooke)|Legge di Hooke]] ($F=k\Delta L$), dove la costante elastica $k = EA/L_0$ dipende dalla geometria ($A, L_0$) e dal materiale ($E$).

### Limiti del Materiale
* **Limite Elastico:** Lo sforzo massimo oltre il quale la deformazione diventa permanente (non più elastica).
* **Carico di Rottura:** Lo sforzo massimo ($\sigma_{\text{max}}$) che il materiale può sopportare prima di rompersi.