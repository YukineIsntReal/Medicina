## 1. La Carica Elettrica

La **carica elettrica** è una proprietà fondamentale della materia. Esistono due tipi di carica: **positiva** e **negativa**.
* Cariche dello stesso segno si respingono.
* Cariche di segno opposto si attraggono.

### Unità di Misura e Carica Elementare
L'unità di misura della carica nel Sistema Internazionale (SI) è il **Coulomb** ($C$).

La carica fondamentale, o **carica elementare** ($e$), è la minima quantità di carica osservata in natura (portata da protoni ed elettroni). Il suo valore assoluto è:
$e = 1.602 \times 10^{-19} C$
* Carica del protone: $q_p = +e$
* Carica dell'elettrone: $q_e = -e$

La carica è **quantizzata**: qualsiasi carica $q$ osservabile è sempre un multiplo intero della carica elementare ($q = n \cdot e$, con $n$ intero).

### Conservazione della Carica
Un principio fondamentale è la **conservazione della carica elettrica**: in un sistema isolato, la somma algebrica delle cariche elettriche rimane costante. La carica non si crea né si distrugge, può solo essere trasferita da un corpo all'altro.

---

## 2. Interazione tra Cariche: Legge di Coulomb

La **Legge di Coulomb** descrive quantitativamente la forza ($\vec{F}$) che si esercita tra due cariche puntiformi ($q_1$ e $q_2$) poste a una distanza ($r$).

### Forma Scalare
Il modulo della forza è:
$F = k \frac{|q_1 q_2|}{r^2}$

Dove $k$ è la **costante di Coulomb**, che nel vuoto vale:
$k = \frac{1}{4 \pi \epsilon_0} \approx 8.99 \times 10^9 \frac{N \cdot m^2}{C^2}$
(Dove $\epsilon_0$ è la costante dielettrica del vuoto).

### Forma Vettoriale
La forza che la carica $q_1$ esercita sulla carica $q_2$ ($\vec{F}_{12}$) è un vettore:
$\vec{F}_{12} = k \frac{q_1 q_2}{r_{12}^2} \hat{r}_{12}$
Dove $\hat{r}_{12}$ è il **versore** (vettore unitario di modulo 1) che punta da $q_1$ a $q_2$.
* Se $q_1$ e $q_2$ hanno lo stesso segno, il prodotto $q_1 q_2$ è positivo e la forza ($\vec{F}_{12}$) è repulsiva (ha la stessa direzione di $\hat{r}_{12}$).
* Se $q_1$ e $q_2$ hanno segno opposto, il prodotto $q_1 q_2$ è negativo e la forza ($\vec{F}_{12}$) è attrattiva (ha direzione opposta a $\hat{r}_{12}$).

---

## 3. Il Campo Elettrico

Il **campo elettrico** ($\vec{E}$) è una modificazione dello spazio generata da una o più cariche (dette *sorgenti*). È un campo vettoriale: associa a ogni punto dello spazio un vettore $\vec{E}$.

### Definizione Operativa
Operativamente, il campo elettrico in un punto $P$ è definito come il rapporto tra la forza ($\vec{F}$) che agisce su una *carica di prova* positiva ($q_0$, sufficientemente piccola da non perturbare le sorgenti) posta in $P$, e la carica di prova stessa:
$\vec{E} = \frac{\vec{F}}{q_0}$

L'unità di misura del campo elettrico è $\frac{N}{C}$ (Newton su Coulomb), che, come vedremo, è equivalente a $\frac{V}{m}$ (Volt su metro).

### Rappresentazione: Linee di Forza
Le **linee di forza** (o linee di campo) sono uno strumento grafico per visualizzare il campo elettrico:
1.  Sono orientate: escono dalle cariche positive ed entrano in quelle negative.
2.  La tangente alla linea in ogni punto ha la stessa direzione del vettore $\vec{E}$ in quel punto.
3.  La densità delle linee (quanto sono fitte) è proporzionale all'intensità (modulo) del campo elettrico in quella regione.
4.  Le linee di forza non si incrociano mai (altrimenti $\vec{E}$ avrebbe due direzioni nello stesso punto, il che è impossibile).

---

## 4. Campo Elettrico generato da Cariche Puntiformi

### Campo di una singola Carica Puntiforme
Applicando la definizione di $\vec{E}$ e la Legge di Coulomb, il campo generato da una singola carica sorgente $q$ a distanza $r$ da essa è:
$\vec{E}(P) = k \frac{q}{r^2} \hat{r}$
Dove $\hat{r}$ è il versore che punta dalla sorgente $q$ al punto $P$. Il campo è radiale (repulsivo se $q>0$, attrattivo se $q<0$).

### Principio di Sovrapposizione (Distribuzione di più cariche)
Se sono presenti più cariche puntiformi ($q_1, q_2, ..., q_n$), il campo elettrico totale ($\vec{E}_{tot}$) in un punto $P$ è la **somma vettoriale** dei campi generati da ciascuna singola carica in quel punto $P$, come se le altre non ci fossero:
$\vec{E}_{tot}(P) = \vec{E}_1(P) + \vec{E}_2(P) + ... + \vec{E}_n(P) = \sum_{i=1}^{n} \vec{E}_i(P)$

---

## 5. Moto di una Carica in un Campo Elettrico Uniforme

Un campo elettrico si dice **uniforme** quando il vettore $\vec{E}$ è costante (stesso modulo, direzione e verso) in tutti i punti di una regione di spazio (es. all'interno di un condensatore piano ideale).

Una carica $q$ di massa $m$ immersa in questo campo subisce una forza **costante**:
$\vec{F} = q\vec{E}$

Per il secondo principio della dinamica ($\vec{F} = m\vec{a}$), l'accelerazione della carica è anch'essa **costante**:
$\vec{a} = \frac{q\vec{E}}{m}$

Il moto della particella è quindi un **moto uniformemente accelerato**.
* Se la velocità iniziale ($\vec{v}_0$) è nulla o parallela a $\vec{E}$, il moto è rettilineo uniformemente accelerato.
* Se $\vec{v}_0$ non è parallela a $\vec{E}$, il moto è parabolico (perfettamente analogo al moto di un proiettile nel campo gravitazionale uniforme, dove $q\vec{E}$ sostituisce $m\vec{g}$).