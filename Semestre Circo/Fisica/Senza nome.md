# Capacità e Condensatori

Un **condensatore** è un sistema costituito da due conduttori (chiamati *armature*) posti a breve distanza, separati da un materiale isolante (un [[Conduttori e Dielettrici#2. Dielettrici (Isolanti)|dielettrico]] o il vuoto).

Il suo scopo è quello di **immagazzinare carica** e, di conseguenza, **energia potenziale elettrica**.

## 1. Capacità Elettrica ($C$)

Se si applica una [[Potenziale Elettrico#3. Differenza di Potenziale (ΔV)|differenza di potenziale]] $\Delta V$ tra le due armature (es. collegandole a un generatore), una carica $+Q$ si accumulerà su un'armatura e una carica $-Q$ si accumulerà sull'altra (per [[Conduttori e Dielettrici#Induzione Elettrostatica|induzione]]).

Si definisce **capacità** ($C$) di un condensatore il rapporto (costante) tra il modulo della carica $Q$ su una delle armature e il modulo della differenza di potenziale $\Delta V$ tra di esse:
$C = \frac{Q}{\Delta V}$

La capacità è una misura di "quanta carica" il condensatore può immagazzinare *per ogni Volt* di d.d.p. applicata. È una proprietà puramente geometrica (dipende da forma, dimensione e distanza delle armature) e dal dielettrico interposto.

L'unità di misura è il **Farad** ($F$), definito come $1 F = 1 C / V$.

## 2. Il Condensatore Piano

Il modello più semplice è il condensatore piano: due armature piane e parallele di area $A$, poste a distanza $d$.

### Capacità nel Vuoto ($C_0$)
Se tra le armature c'è il vuoto (o l'aria, con buona approssimazione), la capacità $C_0$ è:
$C_0 = \epsilon_0 \frac{A}{d}$
Dove $\epsilon_0$ è la costante dielettrica del vuoto.

### Effetto del Dielettrico
Se lo spazio tra le armature viene riempito con un materiale dielettrico di **costante dielettrica relativa** $\kappa$ (kappa), il fenomeno della [[Conduttori e Dielettrici#Polarizzazione|polarizzazione]] attenua il campo elettrico interno.

A parità di carica $Q$ sulle armature, la $\Delta V$ tra di esse si riduce di un fattore $\kappa$ ($\Delta V = \Delta V_0 / \kappa$). Di conseguenza, la capacità *aumenta* di un fattore $\kappa$:
$C = \frac{Q}{\Delta V} = \frac{Q}{(\Delta V_0 / \kappa)} = \kappa \frac{Q}{\Delta V_0} = \kappa \cdot C_0$

La formula della capacità di un condensatore piano con dielettrico diventa:
$C = \kappa \epsilon_0 \frac{A}{d} = \epsilon \frac{A}{d}$
(dove $\epsilon = \kappa \epsilon_0$ è la *permettività* del materiale).

## 3. Energia Immagazzinata ($U_E$)

Per caricare un condensatore, il generatore deve compiere un lavoro per spostare le cariche da un'armatura all'altra, "vincendo" la repulsione delle cariche già presenti. Questo lavoro viene immagazzinato come **energia potenziale elettrica** $U_E$ nel campo elettrico tra le armature.

L'energia immagazzinata è data da:
$U_E = \frac{1}{2} Q \Delta V = \frac{1}{2} C (\Delta V)^2 = \frac{1}{2} \frac{Q^2}{C}$

## 4. Combinazione di Condensatori

#### A. Condensatori in Parallelo
Due o più condensatori sono in **parallelo** se sono tutti connessi tra gli stessi due punti (stesso $\Delta V$).
* **Stessa $\Delta V$:** La d.d.p. è la stessa per tutti.
* **Carica si Somma:** La carica totale $Q_{tot}$ fornita dal generatore è la somma delle cariche su ciascun condensatore.
    $Q_{tot} = Q_1 + Q_2 + \dots$
    $C_{eq} \Delta V = C_1 \Delta V + C_2 \Delta V + \dots$

La **capacità equivalente** ($C_{eq}$) è la somma delle singole capacità:
$C_{eq} = C_1 + C_2 + \dots + C_n$
(Aumentare l'area totale)

#### B. Condensatori in Serie
Due o più condensatori sono in **serie** se sono connessi uno di seguito all'altro, senza bivi.
* **Stessa Carica:** La carica $Q$ è la *stessa* su tutte le armature (per induzione).
* **$\Delta V$ si Somma:** La d.d.p. totale $\Delta V_{tot}$ è la somma delle singole d.d.p.
    $\Delta V_{tot} = \Delta V_1 + \Delta V_2 + \dots$
    $\frac{Q}{C_{eq}} = \frac{Q}{C_1} + \frac{Q}{C_2} + \dots$

Il reciproco della **capacità equivalente** ($C_{eq}$) è la somma dei reciproci delle singole capacità:
$\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_n}$
(Aumentare la distanza totale $d$)

> **Nota:** I collegamenti dei condensatori sono l'*opposto* di quelli delle [[Corrente e Leggi di Ohm#4. Combinazione di Resistenze (Circuiti)|resistenze]].

---

## 5. Carica e Scarica (Circuito RC)

Consideriamo un circuito con un generatore ($\Delta V$), una [[Corrente e Leggi di Ohm#2. Leggi di Ohm e Resistenza|resistenza]] $R$ e un condensatore $C$ in serie (Circuito RC).

### Carica
Quando si chiude l'interruttore (al tempo $t=0$), il condensatore è scarico ($q(0)=0$) e inizia a caricarsi.
* La corrente $I(t)$ è massima all'inizio ($I_{max} = \Delta V / R$) e diminuisce esponenzialmente.
* La carica $q(t)$ sulle armature cresce da 0 fino al valore massimo $Q_{max} = C \Delta V$.

$q(t) = Q_{max} (1 - e^{-t / \tau})$
$V_C(t) = \Delta V (1 - e^{-t / \tau})$

### Scarica
Se un condensatore carico ($q(0)=Q_{max}$) viene cortocircuitato su una resistenza $R$, inizia a scaricarsi.
* La carica $q(t)$ e la tensione $V_C(t)$ diminuiscono esponenzialmente da $Q_{max}$ e $\Delta V$ fino a 0.

$q(t) = Q_{max} \cdot e^{-t / \tau}$
$V_C(t) = \Delta V \cdot e^{-t / \tau}$

### Costante di Tempo ($\tau$)
In entrambi i processi, il parametro $\tau$ (tau) è la **costante di tempo** del circuito RC:
$\tau = R \cdot C$
Rappresenta il tempo necessario per caricare il condensatore al 63% (cioè $1 - 1/e$) del suo valore massimo, o per scaricarlo al 37% ($1/e$) del suo valore iniziale.