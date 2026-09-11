La maggior parte delle reazioni biologiche non procede fino al completamento, ma raggiunge uno stato di **equilibrio chimico**. Questo è uno stato **dinamico**, non statico.

## 1. Definizione di Equilibrio Dinamico

Come introdotto in [[Principi Fondamentali e Tipi di Reazioni#2 Reversibilità ed Equilibrio Chimico|Reversibilità]], una reazione all'equilibrio è indicata dalla doppia freccia ($\rightleftharpoons$).

Per la reazione generica:
$$aA + bB \rightleftharpoons cC + dD$$

L'equilibrio chimico è lo stato in cui:
1.  La **velocità della reazione diretta** ( $v_d$, reagenti $\rightarrow$ prodotti) è **uguale** alla **velocità della reazione inversa** ( $v_i$, prodotti $\rightarrow$ reagenti).
    $$v_d = v_i$$
2.  Di conseguenza, le **concentrazioni** di reagenti e prodotti rimangono **costanti nel tempo**.
3.  Le reazioni (diretta e inversa) non si fermano, ma continuano ad avvenire alla stessa velocità.

## 2. La Legge di Azione di Massa e la Costante di Equilibrio ($K_{eq}$)

La **Legge di Azione di Massa** descrive quantitativamente la relazione tra le concentrazioni di reagenti e prodotti all'equilibrio.

Per la reazione generica $aA + bB \rightleftharpoons cC + dD$, la **costante di equilibrio ($K_{eq}$)** è definita come:

$$K_{eq} = \frac{[C]^c [D]^d}{[A]^a [B]^b}$$

Dove:
* $[A], [B], [C], [D]$ sono le concentrazioni molari ($mol/L$) delle specie all'**equilibrio**.
* $a, b, c, d$ sono i rispettivi coefficienti stoechiometrici.
* **Importante:** Nell'espressione di $K_{eq}$ si includono solo specie in fase gassosa ($g$) o in soluzione acquosa ($aq$). Si **om mettono** sempre i solidi puri ($s$) e i liquidi puri ($l$), poiché la loro "concentrazione" (densità) è considerata costante.

### $K_c$ e $K_p$
* **$K_c$**: È la costante di equilibrio espressa in termini di **concentrazioni** molari (come quella vista sopra).
* **$K_p$**: Per le reazioni gassose, è spesso più comodo usare le **pressioni parziali** ($P$) invece delle concentrazioni.
    $$K_p = \frac{(P_C)^c (P_D)^d}{(P_A)^a (P_B)^b}$$
* **Relazione:** $K_p = K_c (RT)^{\Delta n}$, dove $\Delta n$ è la (somma moli gas prodotti) - (somma moli gas reagenti).

### Cosa ci dice il valore di $K_{eq}$?
Il valore di $K_{eq}$ (a una data temperatura) indica la "posizione" dell'equilibrio, cioè quanto la reazione è spostata verso i prodotti o i reagenti.

* **$K_{eq} > 1$**: All'equilibrio, la concentrazione dei prodotti è maggiore di quella dei reagenti. La reazione è **spostata verso destra** (favosice i prodotti).
* **$K_{eq} < 1$**: All'equilibrio, la concentrazione dei reagenti è maggiore di quella dei prodotti. La reazione è **spostata verso sinistra** (favosice i reagenti).
* **$K_{eq} \approx 1$**: All'equilibrio, ci sono quantità significative sia di reagenti che di prodotti.

---

## 3. Il Principio di Le Châtelier (Fattori che influenzano l'Equilibrio)

Il **Principio di Le Châtelier** afferma:

> "Quando un sistema all'equilibrio viene sottoposto a una perturbazione (stress), il sistema reagirà in modo da opporsi alla perturbazione e ristabilire un nuovo stato di equilibrio."

È il principio fondamentale dell'omeostasi.

### A. Effetto della Concentrazione
* **Aggiunta di una specie (reagente o prodotto):** L'equilibrio si sposta nella direzione che **consuma** la specie aggiunta.
    * Aggiungo $A$ o $B \rightarrow$ Equilibrio si sposta a **destra** ($\rightarrow$) per consumare $A$ e $B$.
    * Aggiungo $C$ o $D \rightarrow$ Equilibrio si sposta a **sinistra** ($\leftarrow$) per consumare $C$ e $D$.
* **Rimozione di una specie:** L'equilibrio si sposta nella direzione che **produce** la specie rimossa.
    * Rimuovo $C$ o $D \rightarrow$ Equilibrio si sposta a **destra** ($\rightarrow$) per rimpiazzare $C$ e $D$.
    * Rimuovo $A$ o $B \rightarrow$ Equilibrio si sposta a **sinistra** ($\leftarrow$) per rimpiazzare $A$ e $B$.

### B. Effetto della Pressione e del Volume (solo per i gas)
Una variazione di pressione (o volume) perturba l'equilibrio *solo se* il numero di moli gassose dei reagenti è diverso da quello dei prodotti ($\Delta n \neq 0$).

* **Aumento Pressione (o Diminuzione Volume):** Il sistema si sposta nella direzione dove ci sono **meno moli di gas** per ridurre la pressione.
* **Diminuzione Pressione (o Aumento Volume):** Il sistema si sposta nella direzione dove ci sono **più moli di gas** per aumentare la pressione.
* *Esempio (Sintesi Ammoniaca):* $N_2(g) + 3H_2(g) \rightleftharpoons 2NH_3(g)$
    * Reagenti: $1+3 = 4$ moli di gas
    * Prodotti: $2$ moli di gas
    * Un **aumento di $P$** sposta l'equilibrio a **destra** (verso $NH_3$), dove ci sono meno moli.

### C. Effetto della Temperatura
La temperatura è l'unico fattore che **cambia il valore della costante $K_{eq}$**. Dobbiamo considerare l'entalpia ($\Delta H$) della reazione.

* **Reazioni Endotermiche ($\Delta H > 0$):** Assorbono calore.
    $Reagenti + \text{Calore} \rightleftharpoons Prodotti$
    * **Aumento $T$ (aggiungo calore):** Il sistema consuma il calore aggiunto spostandosi a **destra** ($\rightarrow$). $K_{eq}$ **aumenta**.
    * **Diminuzione $T$ (tolgo calore):** Il sistema produce calore spostandosi a **sinistra** ($\leftarrow$). $K_{eq}$ **diminuisce**.
* **Reazioni Esotermiche ($\Delta H < 0$):** Rilasciano calore.
    $Reagenti \rightleftharpoons Prodotti + \text{Calore}$
    * **Aumento $T$ (aggiungo calore):** Il sistema consuma il calore aggiunto spostandosi a **sinistra** ($\leftarrow$). $K_{eq}$ **diminuisce**.
    * **Diminuzione $T$ (tolgo calore):** Il sistema produce calore spostandosi a **destra** ($\rightarrow$). $K_{eq}$ **aumenta**.

### D. Effetto di un Catalizzatore
Come già visto in [[Cinetica Chimica#7 I Catalizzatori|Cinetica]] e [[Gli Enzimi: Catalizzatori Biologici]], i catalizzatori **NON** modificano la posizione dell'equilibrio e **NON** alterano il valore di $K_{eq}$.

> I catalizzatori (inclusi gli enzimi) **aumentano la velocità** con cui l'equilibrio viene raggiunto, accelerando *sia* la reazione diretta *che* quella inversa nella stessa misura.

---

## 4. Equilibrio e Energia Libera ($\Delta G$)

Il $\Delta G$ (Energia Libera di Gibbs) è la misura della spontaneità di una reazione. La sua relazione con l'equilibrio è fondamentale:

* **$\Delta G < 0$**: Reazione spontanea (procede verso destra).
* **$\Delta G > 0$**: Reazione non spontanea (procede verso sinistra).
* **$\Delta G = 0$**: La reazione è all'**equilibrio**.

La relazione tra $\Delta G$ in condizioni standard ($\Delta G^\circ$) e la costante di equilibrio è:
$$\Delta G^\circ = -RT \ln K_{eq}$$

Dove:
* $R$ è la costante dei gas
* $T$ è la temperatura in Kelvin
* $\ln$ è il logaritmo naturale

Questa equazione lega la termodinamica ($\Delta G^\circ$) all'equilibrio ($K_{eq}$).