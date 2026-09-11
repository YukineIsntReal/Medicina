La **dinamica** è la branca della meccanica che studia le cause del moto, ovvero le **forze**. Mentre la [[Cinematica del Punto Materiale]] descrive *come* un corpo si muove (posizione, velocità, accelerazione), la dinamica spiega *perché* si muove in quel modo, analizzando le interazioni tra i corpi.

Il concetto fondamentale è la **forza** ($\vec{F}$), una grandezza vettoriale che rappresenta un'interazione capace di modificare lo stato di moto (cioè causare un'accelerazione) o di deformare un corpo. L'unità di misura nel SI è il **Newton** ($N$).

---

## 1. I Tre Principi della Dinamica (Leggi di Newton)

Le fondamenta della dinamica classica furono formulate da Isaac Newton.

### A. Primo Principio (Principio di Inerzia)
> "Un corpo persevera nel suo stato di quiete o di moto rettilineo uniforme finché non interviene una forza esterna netta a modificarne lo stato."

* Questo principio definisce l'**inerzia** come la tendenza dei corpi a opporsi alle variazioni del loro stato di moto.
* Introduce i **sistemi di riferimento inerziali**, ovvero quei sistemi in cui vale il primo principio.
* Stabilisce la condizione di **equilibrio traslazionale**: se la somma vettoriale (risultante) di tutte le forze agenti su un corpo è nulla, la sua accelerazione è zero.
    $$\sum \vec{F} = 0 \iff \vec{a} = 0$$
* Se $\vec{a} = 0$, il corpo è in **quiete** ($\vec{v} = 0$) o si muove di **moto rettilineo uniforme** ($\vec{v} = \text{costante}$). L'**equilibrio statico** è il caso particolare in cui $\vec{v} = 0$.

### B. Secondo Principio (Legge Fondamentale)
> "La forza risultante agente su un corpo è direttamente proporzionale all'accelerazione del corpo e ha la stessa direzione e verso."

La costante di proporzionalità è la **massa inerziale** ($m$) del corpo, che misura la sua resistenza all'accelerazione.

$$\sum \vec{F}_{\text{est}} = m\vec{a}$$

* Questa è la legge fondamentale che collega la causa (forza $\vec{F}$) all'effetto (l'accelerazione $\vec{a}$, definita in [[Cinematica del Punto Materiale]]).
* La legge è vettoriale e può essere scomposta lungo gli assi cartesiani:
    * $\sum F_x = ma_x$
    * $\sum F_y = ma_y$
    * $\sum F_z = ma_z$
* Da questa legge si definisce l'unità di misura: $1 \, \text{N} = 1 \, \text{kg} \cdot \frac{\text{m}}{\text{s}^2}$.

### C. Terzo Principio (Principio di Azione e Reazione)
> "Se un corpo A esercita una forza sul corpo B (azione, $\vec{F}_{AB}$), allora il corpo B esercita sul corpo A una forza uguale in modulo, stessa direzione, ma verso opposto (reazione, $\vec{F}_{BA}$)."

$$\vec{F}_{AB} = -\vec{F}_{BA}$$

* Le forze di azione e reazione agiscono sempre **su corpi diversi**.
* Non si annullano mai a vicenda, perché sono applicate a oggetti differenti.
* Tutte le forze in natura esistono in coppie azione-reazione.

---

## 2. Principali Tipi di Forze

### A. Forza Gravitazionale e Forza Peso
* **Legge di Gravitazione Universale:** Qualsiasi coppia di masse puntiformi ($m_1$, $m_2$) a distanza $r$ si attrae con una forza:
    $$F_g = G \frac{m_1 m_2}{r^2}$$
    dove $G \approx 6.674 \times 10^{-11} \, \text{N}\cdot\text{m}^2/\text{kg}^2$ è la costante di gravitazione universale.

* **Forza Peso ($\vec{P}$):** È un caso specifico della forza gravitazionale. È la forza con cui la Terra (massa $M_T$) attira un corpo di massa $m$ posto vicino alla sua superficie (raggio $R_T$).
    $$P = G \frac{M_T m}{R_T^2}$$
    Possiamo raggruppare i termini costanti in $g = G \frac{M_T}{R_T^2} \approx 9.81 \, \text{m/s}^2$.
    Si ottiene così la formula $\vec{P} = m\vec{g}$, dove $\vec{g}$ è il vettore **accelerazione di gravità**, diretto verso il centro della Terra. (Vedi [[Cinematica del Punto Materiale#C. Caduta Libera|Caduta Libera]]).

### B. Forze di Contatto (Reazione Vincolare)
Sono forze scambiate tra corpi a diretto contatto. Si scompongono in:
* **Reazione Normale ($\vec{N}$):** Forza esercitata da una superficie (un *vincolo*) su un corpo. È sempre **perpendicolare** alla superficie stessa. Impedisce la compenetrazione dei corpi.
* **Forza di Attrito ($\vec{f}_a$):** Forza parallela alla superficie di contatto, che si oppone al moto relativo (o alla tendenza al moto).

### C. Forza di Attrito
Esistono due tipi di attrito radente:
* **Attrito Statico ($\vec{f}_s$):** Agisce quando i corpi sono fermi l'uno rispetto all'altro. Si oppone alla forza esterna che tenta di avviare il moto.
    * Il suo modulo è variabile: $0 \le f_s \le f_{s, \text{max}}$.
    * Il valore massimo è $f_{s, \text{max}} = \mu_s N$, dove $\mu_s$ è il **coefficiente di attrito statico**.
    * Il moto inizia solo se la forza applicata supera $f_{s, \text{max}}$.

* **Attrito Dinamico (o Cinetico, $\vec{f}_d$):** Agisce quando i corpi sono in moto relativo. Si oppone al moto.
    * Il suo modulo è (approssimativamente) costante: $f_d = \mu_d N$, dove $\mu_d$ è il **coefficiente di attrito dinamico**.
    * Generalmente, $\mu_d \le \mu_s$.

### D. Tensione ($\vec{T}$)
È la forza esercitata da un filo, una fune o un cavo *tirati*.
* La tensione "tira" sempre lungo la direzione del filo, allontanandosi dal corpo a cui è applicata.
* In un filo ideale (massa trascurabile e inestensibile), la tensione si trasmette uniformemente lungo tutto il filo.

### E. Forza Elastica (Legge di Hooke)
È la forza esercitata da una molla (o un altro corpo elastico) quando viene deformata (allungata o compressa) rispetto alla sua posizione di equilibrio.
* **Legge di Hooke:** $\vec{F}_e = -k\vec{x}$
* $k$: **Costante elastica** della molla (in $N/m$), misura la sua "durezza".
* $\vec{x}$: Vettore spostamento dalla **posizione di equilibrio** (non dalla posizione iniziale!).
* Il segno $'-'$ indica che è una **forza di richiamo**: si oppone sempre allo spostamento $\vec{x}$, cercando di riportare il corpo all'equilibrio.
* Questa forza è la causa dinamica del [[Cinematica del Punto Materiale#C. Moto Armonico Semplice (MAS)|Moto Armonico Semplice]].