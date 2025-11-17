# Corrente Elettrica e Leggi di Ohm

Mentre in un [[Conduttori e Dielettrici#1. Conduttori|conduttore in equilibrio elettrostatico]] le cariche non si muovono e $V$ è costante, se applichiamo una **differenza di potenziale** ($\Delta V$) costante ai suoi estremi, le cariche libere si metteranno in moto, generando una **corrente elettrica**.

## 1. Intensità di Corrente ($I$)

L'**intensità di corrente elettrica** ($I$) è definita come la quantità di carica netta ($\Delta Q$) che attraversa una sezione trasversale di un conduttore nell'intervallo di tempo ($\Delta t$).

$I = \frac{\Delta Q}{\Delta t}$

L'unità di misura nel SI è l'**Ampere** ($A$), definito come $1 A = 1 C/s$.

* **Corrente Continua (CC o DC):** Si ha quando l'intensità di corrente $I$ è costante nel tempo.
* **Verso Convenzionale:** Per convenzione, il verso della corrente è quello in cui si muoverebbero le cariche positive (quindi da potenziale $V$ più alto a potenziale $V$ più basso).
    * Nei metalli, le cariche mobili sono elettroni (negativi) che si muovono nel verso opposto (da $V$ basso a $V$ alto), ma la corrente convenzionale $I$ è comunque definita come se fossero cariche positive.
    * Nelle soluzioni elettrolitiche (biologia), la corrente è data dal moto di *entrambi* i tipi di ioni (es. $Na^+$ e $K^+$ si muovono in un verso, $Cl^-$ nell'altro).

### Generatore di Tensione
Per mantenere una corrente costante, è necessario un dispositivo che mantenga una $\Delta V$ costante ai capi del conduttore (es. una pila, un alimentatore, o la pompa $Na^+/K^+$ nella cellula). Questo **generatore di tensione** (o *f.e.m.*, forza elettromotrice) fornisce l'energia necessaria per "pompare" le cariche contro il campo elettrico al suo interno, mantenendo il dislivello di potenziale.

---

## 2. Leggi di Ohm e Resistenza

### Prima Legge di Ohm
Per molti materiali, detti **conduttori ohmici**, si osserva sperimentalmente che la corrente $I$ che li attraversa è direttamente proporzionale alla differenza di potenziale $\Delta V$ applicata ai loro capi.

$\Delta V = R \cdot I \quad \text{(Prima Legge di Ohm)}$

La costante di proporzionalità $R$ è chiamata **Resistenza Elettrica**. Si misura in **Ohm** ($\Omega$), definito come $1 \Omega = 1 V / A$.

La resistenza $R$ è una misura di quanto il conduttore si *opponga* al passaggio della corrente.

### Seconda Legge di Ohm (Resistività)
La resistenza $R$ di un conduttore (es. un filo) dipende dalle sue proprietà geometriche e dal materiale di cui è fatto:

$R = \rho \frac{L}{A}$

Dove:
* $L$ è la lunghezza del conduttore.
* $A$ è l'area della sua sezione trasversale.
* $\rho$ (rho) è la **resistività**, una proprietà intrinseca del materiale (misurata in $\Omega \cdot m$).
    * I **conduttori** (rame, argento, soluzioni saline) hanno $\rho$ molto bassa.
    * Gli **isolanti** (gomma, vetro, *lipidi di membrana*) hanno $\rho$ molto alta.

La resistività (e quindi la resistenza) dipende dalla temperatura. Per i metalli, $R$ aumenta con l'aumentare della temperatura.

---

## 3. Potenza Elettrica ed Effetto Joule

Mentre le cariche $q$ si muovono attraverso un resistore, "cadono" da un potenziale $V_A$ a un potenziale $V_B < V_A$. L'energia potenziale persa ($\Delta U_E = q \Delta V$) non si trasforma in energia cinetica (le cariche si muovono a velocità media costante, detta *velocità di deriva*), ma viene dissipata, solitamente in **calore**.

Questo fenomeno di riscaldamento è detto **Effetto Joule**.

La **potenza elettrica** ($P$), cioè l'energia dissipata per unità di tempo, è data da:
$P = \frac{\Delta U_E}{\Delta t} = \frac{(I \cdot \Delta t) \cdot \Delta V}{\Delta t}$
$P = \Delta V \cdot I$

Combinando questa formula con la Prima Legge di Ohm ($\Delta V = IR$), si ottengono altre due espressioni utili per la potenza *dissipata* in una resistenza $R$:
1.  $P = (\Delta V) \cdot I = (I \cdot R) \cdot I \implies P = I^2 R$
2.  $P = (\Delta V) \cdot I = \Delta V \cdot (\frac{\Delta V}{R}) \implies P = \frac{(\Delta V)^2}{R}$

L'unità di misura della potenza è il **Watt** ($W$), definito come $1 W = 1 J/s = 1 V \cdot A$.

---

## 4. Combinazione di Resistenze (Circuiti)

Nei circuiti elettrici (e nei modelli di membrana), le resistenze possono essere combinate in due modi base.

### A. Resistenze in Serie
Due o più resistori ($R_1, R_2, ...$) sono in **serie** se sono connessi uno di seguito all'altro, senza bivi.
* **Stessa Corrente:** Sono attraversati dalla *stessa corrente* $I$.
* **$\Delta V$ si Somma:** La differenza di potenziale totale $\Delta V_{tot}$ ai capi della serie è la somma delle singole $\Delta V$.
    $\Delta V_{tot} = \Delta V_1 + \Delta V_2 + \dots$
    $I \cdot R_{eq} = I \cdot R_1 + I \cdot R_2 + \dots$

La **resistenza equivalente** ($R_{eq}$) di una serie è la somma delle singole resistenze:
$R_{eq} = R_1 + R_2 + \dots + R_n$

### B. Resistenze in Parallelo
Due o più resistori sono in **parallelo** se i loro "inizi" sono connessi tutti allo stesso punto $A$ e le loro "fini" sono connesse tutte allo stesso punto $B$.
* **Stessa $\Delta V$:** Sono tutti sottoposti alla *stessa differenza di potenziale* $\Delta V_{AB}$.
* **Corrente si Somma:** La corrente totale $I_{tot}$ che entra nel parallelo si suddivide tra i vari rami.
    $I_{tot} = I_1 + I_2 + \dots$
    $\frac{\Delta V}{R_{eq}} = \frac{\Delta V}{R_1} + \frac{\Delta V}{R_2} + \dots$

Il reciproco della **resistenza equivalente** ($R_{eq}$) è la somma dei reciproci delle singole resistenze:
$\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}$