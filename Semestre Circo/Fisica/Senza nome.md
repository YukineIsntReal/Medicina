# Legge di Biot-Savart

La **Legge di Biot-Savart** è una legge fondamentale che descrive il contributo infinitesimo $d\vec{B}$ al campo magnetico generato da un elemento infinitesimo $d\vec{l}$ di un filo percorso da una corrente stazionaria $I$.

## 1. Enunciato (Contributo Infinitesimo)

Il contributo $d\vec{B}$ generato nel punto $P$ dall'elemento $d\vec{l}$ (un vettore orientato come la corrente $I$) è dato da:

$d\vec{B} = \frac{\mu_0}{4\pi} \frac{I (d\vec{l} \times \hat{r})}{r^2}$

Dove:
* $\mu_0$ è la **permeabilità magnetica del vuoto** ($\mu_0 = 4\pi \times 10^{-7} T \cdot m / A$).
* $I$ è l'intensità della corrente.
* $d\vec{l}$ è il vettore spostamento infinitesimo lungo il filo, nel verso della corrente $I$.
* $r$ è la distanza tra l'elemento $d\vec{l}$ e il punto $P$.
* $\hat{r}$ è il versore (vettore unitario) che punta da $d\vec{l}$ a $P$.

La direzione di $d\vec{B}$ è data dal prodotto vettoriale, ed è quindi perpendicolare sia a $d\vec{l}$ (il filo) sia a $\hat{r}$ (la direzione $d\vec{l} \to P$).

### Principio di Sovrapposizione
Per trovare il campo magnetico totale $\vec{B}$ generato da un intero circuito, si deve integrare (sommare vettorialmente) i contributi $d\vec{B}$ lungo tutto il filo:
$\vec{B} = \int_{\text{filo}} d\vec{B} = \frac{\mu_0 I}{4\pi} \int_{\text{filo}} \frac{d\vec{l} \times \hat{r}}{r^2}$

---

## 2. Esempi e Applicazioni

Mentre l'integrale può essere complesso, per configurazioni ad alta simmetria produce risultati noti.

### A. Filo Rettilineo Infinito
Come già accennato nell'[[Magnetismo e Forze Magnetiche#1. Origine del Campo Magnetico (Esperimento di Oersted)|esperimento di Oersted]], un filo infinito percorso da corrente $I$ genera un campo $\vec{B}$ a una distanza perpendicolare $R$ dal filo.

* **Orientamento:** Le linee di campo sono circonferenze concentriche centrate sul filo. Il verso è dato dalla **regola della mano destra** (pollice nel verso di $I$, le dita indicano il verso di $\vec{B}$).
* **Modulo:** L'integrazione della legge di Biot-Savart porta al risultato:
    $B = \frac{\mu_0 I}{2\pi R}$

### B. Spira Circolare (nel centro)
Consideriamo una spira circolare di raggio $R$ percorsa da corrente $I$. Vogliamo calcolare il campo $\vec{B}$ esattamente nel suo centro.

* **Analisi:** Nel centro, ogni elemento $d\vec{l}$ della spira è:
    1.  Alla stessa distanza $R$.
    2.  Perpendicolare al versore $\hat{r}$ (che punta da $d\vec{l}$ al centro). Quindi $\sin(90^\circ) = 1$.
* **Orientamento:** Applicando la regola della mano destra a ogni $d\vec{l}$, si scopre che ogni contributo $d\vec{B}$ al centro punta nella stessa direzione (lungo l'asse della spira).
* **Calcolo:** L'integrale diventa una semplice somma di moduli:
    $B = \int |d\vec{B}| = \int \frac{\mu_0 I}{4\pi} \frac{|d\vec{l} \times \hat{r}|}{R^2} = \frac{\mu_0 I}{4\pi R^2} \int dl$
    L'integrale $\int dl$ su tutta la spira è semplicemente la circonferenza ($2\pi R$).
    $B = \frac{\mu_0 I}{4\pi R^2} (2\pi R)$
* **Risultato:**
    $B = \frac{\mu_0 I}{2R}$

### C. Solenoide Ideale
Un **solenoide** è un avvolgimento elicoidale di filo (una "molla"). Un solenoide *ideale* è molto lungo rispetto al suo diametro ed è avvolto fittamente.
Sia $N$ il numero totale di spire e $L$ la lunghezza del solenoide. Si definisce la densità di spire $n = N/L$.

* **Distribuzione del Campo:** Applicando la sovrapposizione (e calcoli più complessi, o la Legge di Ampère), si trova che:
    1.  **Campo Interno:** Il campo $\vec{B}$ all'interno del solenoide ideale è **forte, uniforme e parallelo all'asse** del solenoide.
    2.  **Campo Esterno:** Il campo $\vec{B}$ all'esterno del solenoide ideale è **nullo** ($B \approx 0$).
* **Orientamento:** Si usa la regola della mano destra "modificata": si avvolgono le dita della mano destra nel verso in cui scorre la corrente $I$ nelle spire; il pollice punterà automaticamente nella direzione del campo $\vec{B}$ all'interno del solenoide.
* **Modulo (Interno):**
    $B = \mu_0 n I = \mu_0 \frac{N}{L} I$