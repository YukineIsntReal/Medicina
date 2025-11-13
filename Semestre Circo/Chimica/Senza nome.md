# Termodinamica e Bioenergetica

La **termodinamica** è la branca della fisica che studia gli scambi di energia (come calore e lavoro) tra un sistema e l'ambiente. In biologia e medicina, la **bioenergetica** applica questi principi per capire come i sistemi viventi estraggono, trasformano e utilizzano l'energia per vivere, crescere e compiere lavoro.

---

## 1. Sistemi Termodinamici

Un **sistema** è la porzione di universo che stiamo osservando. L'**ambiente** è tutto il resto.

* **Sistema Aperto:** Scambia sia energia (calore, lavoro) sia materia con l'ambiente.
    * *Esempio: Una cellula, o l'intero organismo umano (mangiamo, respiriamo, rilasciamo calore e scarti).*
* **Sistema Chiuso:** Scambia energia, ma non materia.
    * *Esempio: Una provetta sigillata, o una [[Lo Stato Liquido#Termoregolazione e Sudorazione|bolsa del ghiaccio]] (trasferisce freddo/calore ma non acqua).*
* **Sistema Isolato:** Non scambia né energia né materia.
    * *Esempio: Un thermos ideale. L'universo nel suo complesso è considerato un sistema isolato.*

> **Nota:** Gli organismi viventi sono sistemi **aperti** che mantengono uno stato stazionario (un *non-equilibrio* dinamico) consumando energia dall'ambiente.

---

## 2. Funzioni di Stato

Una **funzione di stato** è una proprietà di un sistema il cui valore dipende *solo* dallo stato attuale del sistema (P, V, T, n), e non dal percorso (la "storia") attraverso cui è stato raggiunto.

Quando un sistema passa da uno stato A a uno stato B, la variazione di una funzione di stato ($\Delta X$) è sempre:
$$\Delta X = X_{\text{finale}} - X_{\text{iniziale}}$$

* **Sono Funzioni di Stato:** Energia Interna ($U$), Entalpia ($H$), Entropia ($S$), Energia Libera di Gibbs ($G$).
* **NON Sono Funzioni di Stato:** Calore ($q$) e Lavoro ($w$). Il loro valore dipende dal *processo* specifico.

---

## 3. I Principi della Termodinamica

### Primo Principio (Conservazione dell'Energia)
L'energia totale di un sistema isolato è costante. L'energia non può essere creata né distrutta, ma solo convertita da una forma all'altra.

Per un sistema chiuso, la variazione della sua **Energia Interna ($\Delta U$)** — la somma di tutta l'energia cinetica e potenziale delle sue particelle — è data da:

$$\Delta U = q - w$$

* $q$ = calore fornito *al* sistema
* $w$ = lavoro fatto *dal* sistema sull'ambiente

(Nota: la convenzione dei segni può variare; questa è quella ingegneristica/IUPAC. A volte $w$ è il lavoro *fatto sul* sistema, quindi $\Delta U = q + w$).

### Secondo Principio (Direzione dei Processi)
Il Secondo Principio stabilisce la direzione dei processi spontanei. Introduce l'**Entropia ($S$)**.
Per qualsiasi processo spontaneo (irreversibile) in un sistema isolato, l'entropia totale (sistema + ambiente) **aumenta** sempre ($\Delta S_{\text{universo}} > 0$).

> **Enunciato di Clausius:** È impossibile che il calore fluisca spontaneamente da un corpo più freddo a uno più caldo.

### Terzo Principio
L'entropia di un cristallo perfetto è zero ($S=0$) allo zero assoluto ($T = 0 \text{ K}$). Fornisce un punto di riferimento assoluto per calcolare l'entropia.

---

## 4. Entalpia ($H$) - Il Calore di Reazione

L'**Entalpia ($H$)** è una funzione di stato estremamente utile per i chimici e i biologi, poiché la maggior parte dei processi (incluse le reazioni nel corpo) avviene a **pressione costante** (es. pressione atmosferica).

È definita come: $H = U + PV$
La sua variazione ($\Delta H$) corrisponde al **calore scambiato a pressione costante ($q_p$)**.

$$\Delta H = q_p$$

Questo ci permette di classificare le reazioni in base al calore:

### Trasformazioni Esotermiche ($\Delta H < 0$)
* La reazione **libera calore** nell'ambiente.
* $H_{\text{prodotti}} < H_{\text{reagenti}}$
* **Esempi:**
    * Combustione (es. metabolismo del glucosio: $\text{C}_6\text{H}_{12}\text{O}_6 \rightarrow 6\text{CO}_2 + 6\text{H}_2\text{O}$ + Calore)
    * Cambiamenti di stato: Congelamento, Condensazione.

### Trasformazioni Endotermiche ($\Delta H > 0$)
* La reazione **assorbe calore** dall'ambiente.
* $H_{\text{prodotti}} > H_{\text{reagenti}}$
* **Esempi:**
    * Fotosintesi (usa energia solare).
    * Cambiamenti di stato: Fusione, [[Lo Stato Liquido#Calore Latente di Evaporazione|Evaporazione]] (es. sudorazione per raffreddare il corpo).

---

## 5. Entropia ($S$) - Il Disordine

L'**Entropia ($S$)** è una funzione di stato che misura il **disordine** o la **dispersione dell'energia** in un sistema. A livello microscopico (Equazione di Boltzmann), è legata al numero di microstati ($W$) accessibili al sistema:

$$S = k_B \ln W$$

* Più modi ci sono per disporre le particelle (più microstati), maggiore è l'entropia.
* Un aumento di entropia ($\Delta S > 0$) è **favorevole** per la spontaneità.
* **Esempi di $\Delta S > 0$:**
    * Un solido che fonde ($\text{Solido} \rightarrow \text{Liquido}$)
    * Un liquido che evapora ($\text{Liquido} \rightarrow \text{Gas}$)
    * Un soluto che si scioglie in un solvente.
    * Una molecola complessa degradata in molecole più semplici (es. digestione).

---

## 6. Energia Libera di Gibbs ($G$) - Il Criterio di Spontaneità

In un sistema biologico (a $T$ e $P$ costanti), né $\Delta H$ da solo (tendenza all'energia minima) né $\Delta S$ da solo (tendenza al disordine massimo) sono sufficienti per predire se una reazione avverrà.

L'**Energia Libera di Gibbs ($G$)** è la funzione di stato che combina entrambi i fattori. È la metrica definitiva della **spontaneità** e dell'**energia "utile"** disponibile per compiere lavoro (es. lavoro chimico, meccanico, osmotico).

$$G = H - TS$$

Per un processo a $T$ e $P$ costanti, la variazione è:

$$\Delta G = \Delta H - T\Delta S$$

(Dove $T$ è la temperatura assoluta in Kelvin)

### Trasformazioni Reversibili e Irreversibili
Il segno di $\Delta G$ (riferito al sistema) ci dice la direzione del processo:

* **$\Delta G < 0$ (Negativo):**
    * Processo **spontaneo** e **irreversibile**.
    * La reazione è **ESOERGONICA** (libera energia utile).
    * Il sistema si muove verso uno stato di energia più bassa (più stabile).
    * *Esempio: Idrolisi dell'ATP $\rightarrow$ ADP + P$_i$*

* **$\Delta G > 0$ (Positivo):**
    * Processo **non spontaneo** nella direzione indicata. (È spontaneo nella direzione opposta).
    * La reazione è **ENDOERGONICA** (richiede un input di energia utile per avvenire).
    * *Esempio: Sintesi di ATP da ADP + P$_i$ (avviene solo perché *accoppiata* a processi esoergonici, come il catabolismo).*

* **$\Delta G = 0$ (Zero):**
    * Il sistema è all'**EQUILIBRIO**.
    * Non c'è flusso netto di reazione in nessuna direzione.
    * > **Importante:** L'equilibrio per un organismo vivente corrisponde alla **morte**. Gli esseri viventi mantengono $\Delta G \neq 0$ per i loro processi vitali.

### Energia Libera ed Equilibrio Chimico
Per una reazione generica: $aA + bB \rightleftharpoons cC + dD$

La variazione di energia libera ($\Delta G$) in condizioni *reali* (non standard) dipende dalle concentrazioni di reagenti e prodotti attraverso il **Quoziente di Reazione ($Q$)**:

$$\Delta G = \Delta G^\circ + RT \ln Q \quad \text{dove} \quad Q = \frac{[C]^c[D]^d}{[A]^a[B]^b}$$

* $\Delta G^\circ$ = Variazione di Energia Libera Standard (condizioni fisse: $1 \text{ M}, 1 \text{ atm}, 25\text{ }^\circ\text{C}$). È una costante per una data reazione.

All'**equilibrio**, sappiamo che $\Delta G = 0$. Il quoziente $Q$ diventa la **Costante di Equilibrio ($K_{eq}$)**.

$$0 = \Delta G^\circ + RT \ln K_{eq}$$
$$\Delta G^\circ = -RT \ln K_{eq}$$

Questa è una delle equazioni più importanti della biochimica:
* Ci dice che il $\Delta G^\circ$ (un valore tabulato) determina la *posizione* dell'equilibrio (il valore di $K_{eq}$).
* Se $K_{eq} > 1$ (equilibrio spostato ai prodotti) $\rightarrow \Delta G^\circ < 0$ (negativo).
* Se $K_{eq} < 1$ (equilibrio spostato ai reagenti) $\rightarrow \Delta G^\circ > 0$ (positivo).
* Se $K_{eq} = 1$ (equilibrio 50/50) $\rightarrow \Delta G^\circ = 0$.