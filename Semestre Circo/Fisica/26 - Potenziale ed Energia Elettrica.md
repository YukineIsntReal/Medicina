Mentre il [[Fondamenti di Elettrostatica#3. Il Campo Elettrico|campo elettrico]] $\vec{E}$ è un campo vettoriale che descrive la *forza*, il **potenziale elettrico** $V$ è un campo *scalare* (un numero per ogni punto dello spazio) che descrive l'**energia**. È spesso molto più semplice lavorare con gli scalari che con i vettori.

## 1. Energia Potenziale Elettrica ($U_E$)

La forza elettrica è **conservativa**. Come la forza di gravità, compie un lavoro che non dipende dal percorso ma solo dalla posizione iniziale e finale. Possiamo quindi definire un'**energia potenziale elettrica** ($U_E$).

L'energia potenziale $U_E$ di un sistema di due cariche puntiformi $q_1$ e $q_2$ a distanza $r$ è definita (ponendo lo zero $U_E=0$ a distanza infinita $r=\infty$) come:
$U_E = k \frac{q_1 q_2}{r}$
Dove $k = \frac{1}{4 \pi \epsilon_0}$.

* Se le cariche hanno lo stesso segno ($q_1 q_2 > 0$), $U_E > 0$. Il sistema è instabile (le cariche si respingono). Serve lavoro *esterno* per avvicinarle.
* Se le cariche hanno segno opposto ($q_1 q_2 < 0$), $U_E < 0$. Il sistema è stabile (le cariche si attraggono). Le cariche "cadono" l'una verso l'altra.

Per un sistema di più cariche, l'energia potenziale totale è la somma delle energie di tutte le possibili coppie (prestando attenzione a non contare due volte):
$U_{tot} = \sum_{i<j} k \frac{q_i q_j}{r_{ij}}$

## 2. Potenziale Elettrico ($V$)

Il **potenziale elettrico** ($V$) è una proprietà dello spazio generata dalle cariche sorgente, definita in ogni punto. Rappresenta l'energia potenziale *per unità di carica*.

È definito operativamente come il rapporto tra l'energia potenziale $U_E$ che una carica di prova $q_0$ *avrebbe* in un punto $P$, e la carica $q_0$ stessa:
$V(P) = \frac{U_E(P)}{q_0}$

L'unità di misura del potenziale è il **Volt** ($V$), che si definisce come **Joule / Coulomb** ($1 V = 1 J/C$).

### Potenziale generato da Cariche
* **Carica puntiforme $q$:** Il potenziale $V$ generato da $q$ in un punto a distanza $r$ è:
    $V = k \frac{q}{r}$
    (Nota: $V$ è uno scalare, quindi se $q$ è negativa, $V$ è negativo).

* **Principio di Sovrapposizione:** Per un sistema di più cariche puntiformi, il potenziale totale in un punto $P$ è la **somma algebrica** (non vettoriale!) dei potenziali generati da ciascuna carica in $P$:
    $V_{tot}(P) = \sum_{i} V_i(P) = \sum_{i} k \frac{q_i}{r_i}$
    (Dove $r_i$ è la distanza tra la carica $q_i$ e il punto $P$).

## 3. Differenza di Potenziale ($\Delta V$)

In fisica e in biologia, la quantità più importante non è il potenziale assoluto $V$ (che dipende da dove poniamo lo zero), ma la **differenza di potenziale** (d.d.p. o $\Delta V$) tra due punti.

La differenza di potenziale $\Delta V_{AB}$ tra un punto $A$ e un punto $B$ è definita come:
$\Delta V_{AB} = V_B - V_A$

Questa $\Delta V$ è legata al lavoro ($W$) che il campo elettrico compie per spostare una carica $q_0$ da $A$ a $B$:
$W_{A \to B} = - \Delta U_E = - q_0 (V_B - V_A) = - q_0 \Delta V_{AB}$

La d.d.p. è anche chiamata **tensione** ed è ciò che viene misurato da un voltmetro.

## 4. Conservazione dell'Energia

Poiché la forza elettrica è conservativa, l'**energia meccanica totale** ($E_{mec} = K + U_E$) di una particella carica $q$ che si muove in un campo elettrico si conserva (se non agiscono altre forze non conservative come l'attrito).

$E_{mec} = K + U_E = \text{costante}$
$\Delta K + \Delta U_E = 0$

Sostituendo $\Delta U_E = q \Delta V$, otteniamo:
$\Delta K = - q \Delta V$
$\frac{1}{2} m v_B^2 - \frac{1}{2} m v_A^2 = - q (V_B - V_A)$

* Se una carica **positiva** ($q > 0$) si muove verso un potenziale **minore** ($V_B < V_A \implies \Delta V < 0$), il termine $-q \Delta V$ è positivo. La carica **accelera** ($\Delta K > 0$), convertendo energia potenziale in energia cinetica. (Es. un protone "cade" da un potenziale alto a uno basso).
* Se una carica **negativa** ($q < 0$) si muove verso un potenziale **maggiore** ($V_B > V_A \implies \Delta V > 0$), il termine $-q \Delta V$ è positivo (perché $q$ è negativo). La carica **accelera**. (Es. un elettrone "risale" da un potenziale basso a uno alto).

---

## 5. Dipolo Elettrico

Un **dipolo elettrico** è un sistema di due cariche uguali e opposte, $+q$ e $-q$, separate da una distanza $d$.
È un modello fondamentale in fisica e biologia (es. molecole polari come l'acqua $H_2O$, o la separazione di cariche attraverso la membrana cellulare).

### Momento di Dipolo Elettrico ($\vec{p}$)
Si definisce un vettore, il **momento di dipolo** $\vec{p}$, con:
* **Modulo:** $p = qd$ (dove $d$ è la distanza tra le cariche).
* **Direzione:** Dal centro della carica negativa al centro della carica positiva.

L'unità di misura è $C \cdot m$.

Un dipolo genera un proprio campo e potenziale elettrico (che diminuiscono rapidamente con la distanza, $\propto 1/r^3$ per $\vec{E}$ e $\propto 1/r^2$ per $V$).

### Dipolo in un Campo Elettrico Esterno $\vec{E}$
Se un dipolo è immerso in un campo $\vec{E}$ *uniforme*:
1.  **Forza Netta:** La forza totale sul dipolo è **nulla** (la forza $q\vec{E}$ su $+q$ è cancellata dalla forza $-q\vec{E}$ su $-q$). Il dipolo non trasla.
2.  **Momento Torcente ($\vec{\tau}$):** Le due forze formano una coppia che genera un **momento torcente** che tende ad allineare il dipolo al campo:
    $\vec{\tau} = \vec{p} \times \vec{E}$
3.  **Energia Potenziale ($U$):** L'energia potenziale del dipolo nel campo $\vec{E}$ è minima quando è allineato ($\vec{p} \parallel \vec{E}$) e massima quando è anti-allineato:
    $U = - \vec{p} \cdot \vec{E} = - p E \cos(\theta)$