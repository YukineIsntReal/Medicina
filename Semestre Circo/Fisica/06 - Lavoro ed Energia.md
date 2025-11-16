Mentre la [[Dinamica del Punto Materiale]] analizza il moto attraverso la relazione $\vec{F}=m\vec{a}$, l'approccio energetico fornisce una prospettiva diversa e spesso più semplice, basata su grandezze scalari (come il lavoro e l'energia) anziché vettoriali.

---

## 1. Lavoro Meccanico ($L$)

Il **lavoro** $L$ è una misura del trasferimento di energia che avviene quando una [[Dinamica del Punto Materiale|forza]] $\vec{F}$ agisce su un corpo che subisce uno spostamento $\vec{s}$.

* **Per una forza costante $\vec{F}$:**
    Il lavoro è definito come il prodotto scalare tra la forza e il vettore spostamento $\vec{s}$:
    $$L = \vec{F} \cdot \vec{s} = |\vec{F}| |\vec{s}| \cos\theta$$
    dove $\theta$ è l'angolo tra $\vec{F}$ e $\vec{s}$.
    * $L > 0$: Lavoro **motore** (la forza favorisce lo spostamento, $\theta < 90^\circ$).
    * $L < 0$: Lavoro **resistente** (la forza ostacola lo spostamento, $\theta > 90^\circ$).
    * $L = 0$: Lavoro **nullo** (forza perpendicolare allo spostamento, $\theta = 90^\circ$).

* **Per una forza variabile $\vec{F}(\vec{r})$:**
    Si calcola il lavoro infinitesimo $dL = \vec{F} \cdot d\vec{s}$ lungo la traiettoria e si integra tra il punto iniziale A e il punto finale B:
    $$L_{A \to B} = \int_{A}^{B} \vec{F} \cdot d\vec{s}$$

L'unità di misura del lavoro (e dell'energia) nel SI è il **Joule** ($J$): $1 \, J = 1 \, N \cdot m$.

## 2. Potenza ($P$)

La **potenza** misura la rapidità con cui viene compiuto un lavoro (o trasferita energia).

* **Potenza media ($P_m$):** È il rapporto tra il lavoro $\Delta L$ e l'intervallo di tempo $\Delta t$ in cui è stato compiuto:
    $$P_m = \frac{\Delta L}{\Delta t}$$

* **Potenza istantanea ($P$):** È il limite della potenza media per $\Delta t \to 0$, ovvero la derivata del lavoro rispetto al tempo:
    $$P = \frac{dL}{dt}$$
    Usando $dL = \vec{F} \cdot d\vec{s}$ e sapendo che $\vec{v} = d\vec{s}/dt$ (vedi [[Cinematica del Punto Materiale]]), si ottiene:
    $$P = \frac{\vec{F} \cdot d\vec{s}}{dt} = \vec{F} \cdot \left( \frac{d\vec{s}}{dt} \right) = \vec{F} \cdot \vec{v}$$

L'unità di misura della potenza nel SI è il **Watt** ($W$): $1 \, W = 1 \, J/s$.

---

## 3. Energia Cinetica ($K$)

L'**energia cinetica** è l'energia associata allo stato di moto di un corpo. È una grandezza scalare definita come:
$$K = \frac{1}{2}mv^2$$
dove $m$ è la massa e $v$ è il modulo della [[Cinematica del Punto Materiale|velocità]] istantanea.

### Teorema dell'Energia Cinetica (o delle Forze Vive)
Questo teorema fondamentale lega il lavoro totale alla variazione dell'energia cinetica.

> "Il **lavoro totale** ($L_{\text{tot}}$) compiuto dalla **risultante** di tutte le forze agenti su un punto materiale, mentre si sposta da A a B, è uguale alla **variazione della sua energia cinetica** ($\Delta K$)."

$$L_{\text{tot}} = \Delta K = K_f - K_i$$
$$L_{\text{tot}} = \frac{1}{2}mv_f^2 - \frac{1}{2}mv_i^2$$

Questo teorema è sempre valido, indipendentemente dalla natura delle forze in gioco.

---

## 4. Forze Conservative ed Energia Potenziale

### Forze Conservative
Una forza si dice **conservativa** se il lavoro $L_{A \to B}$ che compie per spostare un corpo da A a B **non dipende dal percorso** seguito, ma solo dalle posizioni A e B.

Proprietà equivalenti:
1.  Il lavoro compiuto lungo un qualsiasi percorso chiuso è nullo: $\oint \vec{F}_{\text{cons}} \cdot d\vec{s} = 0$.
2.  È possibile definire una funzione scalare, l'**energia potenziale** $U$.

Esempi: [[Dinamica del Punto Materiale#A. Forza Gravitazionale e Forza Peso|Forza peso]], [[Dinamica del Punto Materiale#E. Forza Elastica (Legge di Hooke)|Forza elastica]].

### Forze Non Conservative (o Dissipative)
Una forza è **non conservativa** se il lavoro che compie **dipende dal percorso** seguito.
Esempio: La [[Dinamica del Punto Materiale#C. Forza di Attrito|Forza di Attrito]]. Il lavoro dell'attrito è sempre negativo e dipende dalla lunghezza del cammino.

### Energia Potenziale ($U$)
L'**energia potenziale** è una forma di energia "immagazzinata" in un sistema, associata alla configurazione (posizione) delle sue parti. Può essere definita *solo* per le forze conservative.

La variazione di energia potenziale $\Delta U$ è definita come l'**opposto del lavoro** compiuto dalla forza conservativa associata:
$$\Delta U = U_f - U_i = -L_{\text{cons}, i \to f}$$
Questo implica che il lavoro della forza conservativa è: $L_{\text{cons}} = -\Delta U = U_i - U_f$.

* La forza conservativa tende a compiere lavoro positivo (spostare il corpo) "spendendo" energia potenziale (portando il sistema da $U_i$ a $U_f < U_i$).
* L'energia potenziale è sempre definita a meno di una costante additiva (dipende dalla scelta del "livello zero").

---

## 5. Esempi di Energia Potenziale

### A. Energia Potenziale Gravitazionale
Associata alla [[Dinamica del Punto Materiale#A. Forza Gravitazionale e Forza Peso|Forza Peso]] $\vec{P} = m\vec{g}$.
Il lavoro fatto dalla forza peso per andare da $y_i$ a $y_f$ è $L_P = -mg(y_f - y_i)$.
Poiché $\Delta U_g = -L_P$, si ha:
$$\Delta U_g = mg(y_f - y_i)$$
Scegliendo $U_g = 0$ al livello $y=0$, la formula dell'energia potenziale gravitazionale (vicino alla superficie terrestre) è:
$$U_g(y) = mgy$$

### B. Energia Potenziale Elastica
Associata alla [[Dinamica del Punto Materiale#E. Forza Elastica (Legge di Hooke)|Forza Elastica]] $F_x = -kx$.
Il lavoro fatto dalla molla per andare da $x_i$ a $x_f$ è $L_e = -(\frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2)$.
Poiché $\Delta U_e = -L_e$, si ha:
$$\Delta U_e = \frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2$$
Scegliendo $U_e = 0$ nella posizione di equilibrio ($x=0$), la formula dell'energia potenziale elastica è:
$$U_e(x) = \frac{1}{2}kx^2$$

---

## 6. Energia Meccanica e sua Conservazione

L'**energia meccanica totale** ($E_{\text{mec}}$) di un sistema è la somma della sua energia cinetica e della sua energia potenziale totale (somma di tutte le energie potenziali).
$$E_{\text{mec}} = K + U = K + (U_g + U_e + \dots)$$

### Teorema Lavoro - Energia Meccanica
Possiamo scomporre il lavoro totale (dal Teorema dell'Energia Cinetica) in lavoro delle forze conservative ($L_{\text{cons}}$) e lavoro delle forze non conservative ($L_{\text{non-cons}}$):
$$L_{\text{tot}} = L_{\text{cons}} + L_{\text{non-cons}}$$
Dal Teorema dell'Energia Cinetica: $L_{\text{tot}} = \Delta K$.
Dalla definizione di Energia Potenziale: $L_{\text{cons}} = -\Delta U$.

Sostituendo:
$$-\Delta U + L_{\text{non-cons}} = \Delta K$$
$$L_{\text{non-cons}} = \Delta K + \Delta U = \Delta(K + U)$$

Si ottiene il **Teorema dell'Energia Meccanica**:
> "Il lavoro compiuto dalle **sole forze non conservative** è uguale alla variazione dell'**energia meccanica totale**."
> $$L_{\text{non-cons}} = \Delta E_{\text{mec}}$$

### Teorema di Conservazione dell'Energia Meccanica
Questo è un caso speciale, ma fondamentale, del teorema precedente.
Se un sistema è "ideale" (non ci sono forze non conservative come l'attrito) o se le forze non conservative presenti non compiono lavoro (es. la reazione normale $\vec{N}$ in un moto su piano orizzontale):
$$L_{\text{non-cons}} = 0$$

Allora:
$$\Delta E_{\text{mec}} = 0 \implies E_{\text{mec, f}} = E_{\text{mec, i}}$$

> "In assenza di forze non conservative che compiono lavoro, l'energia meccanica totale di un sistema si conserva."
> $$K_f + U_f = K_i + U_i$$
> $$\frac{1}{2}mv_f^2 + U_f = \frac{1}{2}mv_i^2 + U_i$$