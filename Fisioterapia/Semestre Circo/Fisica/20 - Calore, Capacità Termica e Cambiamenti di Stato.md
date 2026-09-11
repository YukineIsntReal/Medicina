## Calore ($Q$)

Il **calore** non è un'energia *posseduta* da un corpo, ma piuttosto un modo in cui l'energia viene *trasferita* tra un sistema e l'ambiente (o tra due sistemi) a causa di una differenza di temperatura.

* È una forma di **energia in transito**.
* Il flusso di calore avviene spontaneamente dal corpo a temperatura maggiore a quello a temperatura minore.
* Nel Sistema Internazionale (SI) si misura in **Joule ($J$)**. Spesso si usa anche la **caloria ($cal$)**, definita come la quantità di calore necessaria per aumentare la temperatura di 1 grammo d'acqua da 14.5°C a 15.5°C. ($1 cal \approx 4.186 J$).

---

## Capacità Termica ($C$)

La **capacità termica** di un corpo è una misura della quantità di calore necessaria per aumentare la sua temperatura di un'unità (es. 1 Kelvin o 1 Grado Celsius).

$C = \frac{Q}{\Delta T}$

* $Q$ è il calore assorbito o ceduto.
* $\Delta T$ è la variazione di temperatura ($T_{finale} - T_{iniziale}$).
* Unità di misura: $J/K$ o $J/°C$.
* È una proprietà *estensiva*: dipende dalla massa e dalla natura del materiale. Un corpo più grande ha una capacità termica maggiore.

## Calore Specifico ($c$)

Il **calore specifico** (o capacità termica specifica) è una proprietà *intensiva* della sostanza, ovvero non dipende dalla quantità di materiale. È la capacità termica per unità di massa.

$c = \frac{C}{m} = \frac{Q}{m \cdot \Delta T}$

Da cui la **Legge Fondamentale della Calorimetria**:

$Q = m \cdot c \cdot \Delta T$

* Unità di misura: $J/(kg·K)$ o $J/(g·°C)$.
* L'acqua, ad esempio, ha un calore specifico molto elevato (circa $4186 J/(kg·K)$), il che la rende un eccellente "serbatoio" termico, fondamentale per la termoregolazione corporea.

### Calori Specifici dei Gas Ideali

Per i gas, il calore specifico dipende dal tipo di trasformazione (processo) che subiscono:

1.  **Calore Specifico a Volume Costante ($C_v$):**
    Misura il calore scambiato quando il volume del gas è mantenuto costante (es. in un contenitore rigido). Tutto il calore fornito aumenta solo l'energia interna ($U$).
    $Q_v = n C_{v,m} \Delta T$ (dove $C_{v,m}$ è il calore specifico molare)

2.  **Calore Specifico a Pressione Costante ($C_p$):**
    Misura il calore scambiato quando la pressione è costante. Il calore fornito non solo aumenta l'energia interna, ma compie anche lavoro ($W = P\Delta V$) per espandere il gas.
    $Q_p = n C_{p,m} \Delta T$
    *Nota:* Per un gas ideale, $C_p > C_v$ perché serve più calore per aumentare la temperatura, dovendo anche compiere lavoro.

---

## Cambiamenti di Stato Fisico

Un cambiamento di stato (o transizione di fase) è il processo in cui una sostanza passa da uno stato di aggregazione (solido, liquido, gassoso) a un altro.

* **Importante:** Durante un cambiamento di stato, la temperatura del sistema rimane **costante** finché l'intera sostanza non ha completato la transizione.

Principali transizioni (quelle che assorbono calore sono *endotermiche*):
* **Fusione:** Solido $\rightarrow$ Liquido (Endotermica)
* **Vaporizzazione (o Evaporazione/Ebollizione):** Liquido $\rightarrow$ Gas (Endotermica)
* **Sublimazione:** Solido $\rightarrow$ Gas (Endotermica)
* **Solidificazione:** Liquido $\rightarrow$ Solido (Esotermica)
* **Condensazione:** Gas $\rightarrow$ Liquido (Esotermica)
* **Brinamento:** Gas $\rightarrow$ Solido (Esotermica)

## Calore Latente ($L$)

Il **calore latente** è la quantità di calore necessaria per far cambiare di stato una unità di massa di una sostanza, a temperatura costante.

$Q = m \cdot L$

* $m$ è la massa della sostanza che cambia stato.
* $L$ è il calore latente specifico della transizione (es. $L_f$ per la fusione, $L_v$ per la vaporizzazione).
* Unità di misura: $J/kg$ o $cal/g$.
* Questo calore non aumenta l'energia cinetica (temperatura) delle molecole, ma viene utilizzato per rompere (o formare, nelle transizioni esotermiche) i legami intermolecolari.

---

## Calorimetria

La **calorimetria** è la branca della fisica che si occupa della misurazione delle quantità di calore scambiate durante processi fisici o chimici.

### Principio Base
Si basa sulla conservazione dell'energia. Si utilizza un **calorimetro**, un dispositivo progettato per essere il più vicino possibile a un [[Concetti Fondamentali di Termodinamica#Sistema e Ambiente|sistema isolato]] (minimi scambi di calore con l'esterno).

In un sistema isolato (calorimetro) dove avvengono scambi di calore tra due o più corpi a temperature diverse, la somma algebrica dei calori scambiati è nulla (principio dell'equilibrio termico):

$\sum Q_i = 0$

Ovvero:
$|Q_{assorbito}| = |Q_{ceduto}|$

### Metodi Sperimentali
Un calorimetro semplice (come il "calorimetro delle mescolanze") è un contenitore termicamente isolato (es. un thermos) con un coperchio, un agitatore e un termometro.
Per misurare, ad esempio, il calore specifico $c_x$ di una sostanza sconosciuta:
1.  Si misura la massa d'acqua ($m_{acqua}$) e la sua temperatura iniziale ($T_{acqua}$).
2.  Si misura la massa della sostanza ($m_x$) e la si scalda a una temperatura nota ($T_x$).
3.  Si immerge la sostanza nell'acqua.
4.  Si misura la temperatura di equilibrio finale ($T_e$) raggiunta dal sistema.
5.  Applicando il principio $\sum Q_i = 0$:
    $Q_{acqua} + Q_{sostanza} + Q_{calorimetro} = 0$
    (Spesso, se il calorimetro ha una bassa capacità termica, $Q_{calorimetro}$ può essere trascurato in prima approssimazione).
    $m_{acqua} \cdot c_{acqua} \cdot (T_e - T_{acqua}) + m_x \cdot c_x \cdot (T_e - T_x) = 0$
6.  Risolvendo l'equazione, si può ricavare $c_x$.