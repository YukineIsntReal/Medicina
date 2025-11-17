Il **Primo Principio della Termodinamica** è una formulazione della **legge di conservazione dell'energia**. Afferma che l'energia non può essere né creata né distrutta, ma solo trasformata da una forma all'altra.

In un sistema termodinamico, questo principio stabilisce una relazione precisa tra le tre grandezze fondamentali: Energia Interna ($U$), Calore ($Q$) e Lavoro ($W$).

---

## Energia Interna, Calore e Lavoro

* **Energia Interna ($U$):** Come definito in [[Concetti Fondamentali di Termodinamica#Energia Interna ($U$)|precedenza]], è una **funzione di stato**. La sua variazione, $\Delta U$, dipende solo dallo stato iniziale e finale del sistema, non dal percorso seguito.
* **Calore ($Q$):** Come definito in [[Calore, Capacità Termica e Cambiamenti di Stato#Calore ($Q$)|precedenza]], è energia in transito dovuta a una differenza di temperatura.
* **Lavoro ($W$):** È l'altra forma di energia in transito. In termodinamica, si riferisce spesso al **lavoro di espansione (o compressione)** di un gas, calcolato come $W = P \cdot \Delta V$ (a pressione costante).

Sia il calore ($Q$) che il lavoro ($W$) **non sono funzioni di stato**. Dipendono dal "percorso", cioè dalla specifica trasformazione che il sistema subisce per passare dallo stato A allo stato B.

## Definizione del Primo Principio

La variazione dell'energia interna ($\Delta U$) di un sistema è uguale alla differenza tra il calore ($Q$) fornito al sistema e il lavoro ($W$) compiuto dal sistema sull'ambiente.

$\Delta U = Q - W$

**Convenzione dei segni:**
* $Q > 0$: Calore **assorbito** dal sistema (dall'ambiente).
* $Q < 0$: Calore **ceduto** dal sistema (all'ambiente).
* $W > 0$: Lavoro **compiuto dal** sistema (sull'ambiente, es. espansione).
* $W < 0$: Lavoro **subito dal** sistema (dall'ambiente, es. compressione).

**Significato fisico:** Il bilancio energetico di un sistema. L'energia che "entra" (come calore $Q$) o "esce" (come lavoro $W$) deve bilanciare la variazione delle riserve energetiche interne del sistema ($\Delta U$).

---

## Trasformazioni Reversibili e Irreversibili

* **Trasformazione Reversibile:** Un processo ideale, teorico. Avviene in modo infinitamente lento, passando attraverso una successione di stati di [[Concetti Fondamentali di Termodinamica#Stato Termodinamico|equilibrio termodinamico]]. In qualsiasi momento, il processo può essere invertito (sia per il sistema che per l'ambiente) senza lasciare alcun cambiamento netto nell'universo.
* **Trasformazione Irreversibile:** Qualsiasi processo reale. Avviene in un tempo finito e passa attraverso stati di non-equilibrio. Non può essere invertito per riportare sia il sistema che l'ambiente allo stato iniziale. (Es. un'espansione libera, la conduzione di calore tra due corpi a $T$ diverse).

---

## Applicazione ai Gas Ideali (Trasformazioni Canoniche)

Analizziamo come si applica $\Delta U = Q - W$ a un gas ideale in quattro trasformazioni reversibili fondamentali.
*Ricorda:* Per un gas ideale, l'energia interna dipende solo dalla temperatura: $\Delta U = n C_v \Delta T$.

### 1. Trasformazione Isoterma ($T = costante$)

Il sistema mantiene una temperatura costante.
* $\Delta T = 0 \implies$ **$\Delta U = 0$** (poiché $U$ dipende solo da $T$)
* Dal primo principio: $0 = Q - W \implies$ **$Q = W$**
* **Significato:** Tutto il calore assorbito dal sistema viene interamente convertito in lavoro compiuto dal sistema (espansione isoterma), o tutto il lavoro subito dal sistema viene ceduto come calore (compressione isoterma).
* $W = nRT \ln(\frac{V_{finale}}{V_{iniziale}})$

### 2. Trasformazione Isocora ($V = costante$)

Il sistema mantiene un volume costante (es. un contenitore rigido).
* $\Delta V = 0 \implies$ **$W = 0$** (poiché $W = P\Delta V$)
* Dal primo principio: $\Delta U = Q - 0 \implies$ **$\Delta U = Q_v$**
* **Significato:** Tutto il calore fornito (o ceduto) si traduce in una variazione (aumento o diminuzione) dell'energia interna del sistema.
* $Q_v = nC_v\Delta T$

### 3. Trasformazione Isobara ($P = costante$)

Il sistema mantiene una pressione costante (es. un cilindro con pistone mobile).
* $W = P \cdot \Delta V = nR\Delta T$ (lavoro non nullo)
* $\Delta U = nC_v\Delta T$ (variazione di energia interna non nulla)
* Dal primo principio: $Q_p = \Delta U + W = nC_v\Delta T + nR\Delta T$
* $Q_p = n(C_v + R)\Delta T \implies$ **$Q_p = nC_p\Delta T$** (usando la Relazione di Mayer $C_p = C_v + R$)
* **Significato:** Il calore fornito viene utilizzato *sia* per aumentare l'energia interna (scaldare il gas) *sia* per compiere lavoro (espandere il gas).

### 4. Trasformazione Adiabatica ($Q = 0$)

Il sistema è perfettamente isolato termicamente (nessun scambio di calore).
* **$Q = 0$** (per definizione)
* Dal primo principio: $\Delta U = 0 - W \implies$ **$\Delta U = -W$**
* **Significato:** Se il sistema compie lavoro (espansione adiabatica), lo fa a spese della propria energia interna $\implies$ **il gas si raffredda** ($\Delta U$ negativo). Se il sistema subisce lavoro (compressione adiabatica), questo lavoro incrementa l'energia interna $\implies$ **il gas si riscalda**.
* Equazione del processo: $P V^{\gamma} = costante$ (dove $\gamma = C_p/C_v$)

---

### Confronto Qualitativo (Diagramma P-V)

In un diagramma Pressione-Volume, partendo da uno stesso stato A:

* **Isocora (A $\rightarrow$ B):** Linea verticale (volume costante). Lavoro = 0.
* **Isobara (A $\rightarrow$ C):** Linea orizzontale (pressione costante). Lavoro = Area sotto $AC$.
* **Isoterma (A $\rightarrow$ D):** Curva (iperbole, $P \propto 1/V$). Lavoro = Area sotto $AD$.
* **Adiabatica (A $\rightarrow$ E):** Curva (simile all'isoterma, $P \propto 1/V^\gamma$). È **più ripida** dell'isoterma perché $\gamma > 1$. Durante l'espansione il gas si raffredda, quindi la pressione cala più velocemente.



A parità di espansione in volume, il lavoro (area sotto la curva) è massimo per l'isobara, seguito dall'isoterma e infine dall'adiabatica.
$W_{isobara} > W_{isoterma} > W_{adiabatica}$