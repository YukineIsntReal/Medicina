Lo **stato aeriforme (o gassoso)** è uno stato della materia in cui le particelle (atomi o molecole) possiedono un'elevata energia cinetica. Le forze di attrazione intermolecolari sono quasi nulle (nei gas perfetti) o comunque molto deboli.

Un gas non ha né forma né volume propri:
* **Comprimibilità:** Tende a espandersi fino a occupare tutto il volume disponibile.
* **Bassa Densità:** Le particelle sono molto distanti tra loro.

Per descrivere lo stato di un gas si usano quattro **variabili di stato**:
1.  **Pressione ($P$):** La forza esercitata dal gas per unità di superficie, dovuta agli urti delle particelle contro le pareti del contenitore (Unità SI: Pascal, $\text{Pa}$; altre: atmosfere, $\text{atm}$; $\text{mmHg}$).
2.  **Volume ($V$):** Il volume del contenitore (Unità SI: metro cubo, $\text{m}^3$; altre: Litro, $\text{L}$).
3.  **Temperatura ($T$):** Misura dell'energia cinetica media delle particelle.
4.  **Numero di moli ($n$):** Quantità di sostanza gassosa.

---

## Temperatura Assoluta

In termodinamica e nelle leggi dei gas, la temperatura deve essere espressa usando la **scala Kelvin (K)**, o **scala assoluta**.

Lo **zero assoluto** ($0 \text{ K}$) è la temperatura teorica più bassa possibile, alla quale l'energia cinetica delle particelle è minima (idealmente nulla).
$0 \text{ K} = -273.15 \text{ }^\circ\text{C}$

**Conversione:**
$$T(\text{K}) = T(^\circ\text{C}) + 273.15$$

L'uso della scala assoluta è necessario perché la pressione ($P$) e il volume ($V$) sono direttamente proporzionali alla temperatura assoluta ($T$), non a quella Celsius.

---

## Leggi Empiriche dei Gas (Gas Perfetti)

Un **gas perfetto (o ideale)** è un modello teorico in cui:
1.  Le particelle sono considerate puntiformi (volume trascurabile).
2.  Le interazioni (forze attrattive/repulsive) tra le particelle sono nulle.

### 1. Legge di Boyle-Mariotte (Processo Isotermo)
A **temperatura costante** ($T = \text{cost}$) e per una data quantità di gas ($n = \text{cost}$), la pressione e il volume sono **inversamente proporzionali**.

> $P \propto \frac{1}{V}$
> $$P \cdot V = k_1 \quad \text{(costante)}$$
> O anche: $P_1 V_1 = P_2 V_2$

### 2. Legge di Charles (Processo Isòbaro)
A **pressione costante** ($P = \text{cost}$) e per una data quantità di gas ($n = \text{cost}$), il volume è **direttamente proporzionale** alla temperatura assoluta.

> $V \propto T$
> $$\frac{V}{T} = k_2 \quad \text{(costante)}$$
> O anche: $\frac{V_1}{T_1} = \frac{V_2}{T_2}$

### 3. Legge di Gay-Lussac (Processo Isòcoro)
A **volume costante** ($V = \text{cost}$) e per una data quantità di gas ($n = \text{cost}$), la pressione è **direttamente proporzionale** alla temperatura assoluta.

> $P \propto T$
> $$\frac{P}{T} = k_3 \quad \text{(costante)}$$
> O anche: $\frac{P_1}{T_1} = \frac{P_2}{T_2}$

---

## Principio di Avogadro e Concetto di Mole

### La Legge di Avogadro
A **pressione e temperatura costanti** ($P, T = \text{cost}$), il volume di un gas è **direttamente proporzionale** al numero di moli (quantità di sostanza).

> $V \propto n$
> $$\frac{V}{n} = k_4 \quad \text{(costante)}$$

Questo implica che "Volumi uguali di gas diversi, nelle stesse condizioni di temperatura e pressione, contengono lo stesso numero di particelle (molecole)".

### Il Concetto di Mole e il Numero di Avogadro
* La **Mole ($\text{mol}$)** è l'unità di misura della quantità di sostanza. È definita come la quantità di sostanza che contiene un numero di entità elementari (atomi, molecole, ioni...) pari al numero di atomi presenti in $12 \text{ g}$ di Carbonio-12 ($^{12}\text{C}$).
* Questo numero è chiamato **Costante di Avogadro ($N_A$)**:
    $$N_A \approx 6.022 \times 10^{23} \text{ mol}^{-1}$$
    (Cioè, $6.022 \times 10^{23}$ particelle per mole).

---

## Equazione di Stato dei Gas Perfetti

Combinando le quattro leggi (Boyle, Charles, Gay-Lussac, Avogadro) si ottiene un'unica equazione che lega tutte le variabili di stato: l'**Equazione di Stato dei Gas Perfetti**.

$$PV = nRT$$

Dove:
* $P$ = Pressione
* $V$ = Volume
* $n$ = Numero di moli
* $T$ = Temperatura (in Kelvin)
* **$R$ = Costante universale dei gas**. Il suo valore dipende dalle unità usate per P e V.
    * $R = 0.0821 \text{ L}\cdot\text{atm} / (\text{mol}\cdot\text{K})$
    * $R = 8.314 \text{ J} / (\text{mol}\cdot\text{K})$ (Unità SI)

---

## Cenni sulla Teoria Cinetica dei Gas

La teoria cinetica dei gas spiega il comportamento macroscopico dei gas (P, V, T) partendo dal movimento microscopico delle particelle.

**Postulati (per un gas ideale):**
1.  Il gas è composto da un numero enorme di particelle (atomi/molecole) identiche.
2.  Le particelle sono puntiformi (volume $V_{\text{particelle}} \approx 0$ rispetto a $V_{\text{contenitore}}$).
3.  Le particelle sono in moto costante, rapido, caotico e rettilineo.
4.  Gli urti tra le particelle e con le pareti sono perfettamente elastici (l'energia cinetica totale si conserva).
5.  Non esistono forze intermolecolari (né attrattive né repulsive).

Da questi postulati si ricava che:
* La **Pressione ($P$)** è il risultato degli urti delle particelle sulle pareti.
* La **Temperatura ($T$)** è una misura dell'**energia cinetica media ($E_k^{\text{media}}$)** delle particelle del gas.
    $$E_k^{\text{media}} = \frac{1}{2} m \overline{v^2} = \frac{3}{2} k_B T$$
    Dove $k_B$ è la **Costante di Boltzmann** ($k_B = R / N_A$).

---

## La Legge di Maxwell-Boltzmann

La teoria cinetica ci dice l'energia cinetica *media*, ma non tutte le particelle si muovono alla stessa velocità. Alcune sono veloci, altre lente.

La **distribuzione di Maxwell-Boltzmann** è una funzione di probabilità che descrive la distribuzione delle velocità delle particelle in un gas a una data temperatura $T$.



* La curva non è simmetrica.
* Mostra che esiste una velocità più probabile, una velocità media e una velocità quadratica media.
* All'**aumentare della temperatura ($T$)**:
    * La curva si "appiattisce" e si "allarga".
    * Il picco (velocità più probabile) si sposta verso velocità più elevate.
    * La frazione di particelle con alta energia/velocità aumenta significativamente. (Questo è fondamentale, ad esempio, per la velocità delle reazioni chimiche).

---

## I Gas Reali e l'Equazione di Van der Waals

I gas reali (quelli che esistono in natura) si discostano dal comportamento ideale descritto da $PV=nRT$, specialmente ad **alte pressioni** e **basse temperature**.

Perché? I postulati del gas ideale non sono più validi:
1.  **Le particelle hanno un volume proprio** (non sono puntiformi).
2.  **Esistono forze intermolecolari** (soprattutto attrattive, come le forze di Van der Waals).

Per descrivere meglio i gas reali, **Johannes Van der Waals** propose un'equazione corretta:

$$\left( P + a\frac{n^2}{V^2} \right) (V - nb) = nRT$$

Dove:
* **Termine ($V - nb$):** Correzione per il **volume proprio** delle particelle. $b$ è il "covolume", che rappresenta il volume effettivamente occupato da una mole di particelle. Il volume "libero" a disposizione del gas è minore ($V_{\text{ideale}} = V_{\text{misurato}} - nb$).
* **Termine ($P + a\frac{n^2}{V^2}$):** Correzione per le **forze di attrazione**. Le particelle che si attraggono urtano le pareti con meno forza rispetto a un gas ideale. La pressione misurata ($P$) è quindi *inferiore* a quella ideale. Aggiungiamo un termine ($a\frac{n^2}{V^2}$) per compensare questa attrazione (il fattore $a$ è specifico per ogni gas e misura l'intensità delle attrazioni).