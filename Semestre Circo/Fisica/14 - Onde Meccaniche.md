## Introduzione: Natura delle Onde Meccaniche

Un'**onda meccanica** è un fenomeno fisico che consiste nella propagazione di una **perturbazione** attraverso un **mezzo materiale** (solido, liquido o gassoso). È importante sottolineare che l'onda trasporta **energia** e **quantità di moto**, ma *non* trasporta materia: le particelle del mezzo oscillano attorno alla loro posizione di equilibrio, ma non si spostano insieme all'onda.

La propagazione è resa possibile dalle proprietà elastiche (che tendono a riportare le particelle all'equilibrio) e inerziali (che danno loro "inerzia" a continuare il moto) del mezzo.

## L'Oscillatore Armonico come Sorgente

Alla base della generazione di molte onde periodiche c'è un **oscillatore armonico**. Questo è un modello ideale (come una massa attaccata a una molla) che, se perturbato, oscilla attorno alla sua posizione di equilibrio con un moto periodico descritto da una funzione sinusoidale (o cosinusoidale).

Quando una sorgente (come un diapason, le corde vocali, o un trasduttore ecografico) vibra armonicamente, "costringe" le particelle del mezzo adiacente a fare lo stesso, innescando la propagazione dell'onda.

## Parametri Fondamentali dell'Onda

Un'onda armonica semplice è caratterizzata da alcuni parametri fondamentali:

* **Ampiezza ($A$):** Il massimo spostamento (elongazione) di una particella del mezzo dalla sua posizione di equilibrio. È legata all'energia trasportata dall'onda.
* **Periodo ($T$):** L'intervallo di tempo necessario affinché un punto del mezzo compia un'oscillazione completa. Si misura in secondi ($s$).
* **Frequenza ($f$):** Il numero di oscillazioni complete che un punto del mezzo compie nell'unità di tempo (1 secondo). Si misura in Hertz ($Hz$), dove $1 Hz = 1 s^{-1}$. È l'inverso del periodo: $f = 1/T$.
* **Pulsazione (o Frequenza Angolare, $\omega$):** Legata alla frequenza e comoda nelle equazioni. Si misura in radianti al secondo ($rad/s$). La relazione è: $\omega = 2\pi f = 2\pi / T$.
* **Lunghezza d'onda ($\lambda$):** La minima distanza spaziale tra due punti dell'onda che si trovano nella stessa fase (ad esempio, due creste consecutive). Rappresenta l'estensione spaziale di un ciclo completo. Si misura in metri ($m$).

## Propagazione dell'Onda

### Velocità di Propagazione ($v$)

La **velocità di propagazione** (o velocità di fase) è la velocità con cui la perturbazione (la "forma" dell'onda) si sposta nel mezzo. È *diversa* dalla velocità con cui oscillano le singole particelle del mezzo.

Questa velocità dipende esclusivamente dalle proprietà intrinseche del mezzo (elasticità e densità) e non dalla frequenza o ampiezza dell'onda sorgente.

Esiste una relazione fondamentale che lega velocità, frequenza e lunghezza d'onda:
$$
v = \lambda \cdot f
$$
Questo significa che, in un dato mezzo (dove $v$ è costante), frequenze più alte corrispondono a lunghezze d'onda più corte, e viceversa.

## Equazione dell'Onda Armonica Semplice

Per un'onda monodimensionale (che si propaga lungo un asse, ad esempio l'$x$), lo spostamento $y$ di una particella che si trova alla posizione $x$ al tempo $t$ può essere descritto dall'**equazione d'onda armonica**:

$$
y(x, t) = A \cdot \sin(kx - \omega t + \phi_0)
$$
o equivalentemente usando il coseno. Analizziamo i termini:
* $y(x, t)$: Spostamento dalla posizione di equilibrio.
* $A$: Ampiezza.
* $\omega$: Pulsazione (controlla l'oscillazione nel *tempo*).
* $\phi_0$: Fase iniziale (o costante di fase), dipende dalle condizioni iniziali ($t=0$, $x=0$).
* $k$: **Numero d'onda**.

Il segno davanti a $\omega t$ determina la direzione: $kx - \omega t$ per la propagazione nel verso positivo delle $x$, $kx + \omega t$ per il verso negativo.

## Vettore d'Onda (Numero d'Onda $k$)

Il **numero d'onda $k$** descrive l'aspetto *spaziale* dell'onda. È legato alla lunghezza d'onda $\lambda$ dalla relazione:
$$
k = \frac{2\pi}{\lambda}
$$
Indica quanti radianti di fase "occupa" un'onda per unità di lunghezza (si misura in $rad/m$).

Nello spazio tridimensionale, si generalizza nel **vettore d'onda** $\vec{k}$, un vettore che punta nella direzione di propagazione dell'onda e il cui modulo è $k = 2\pi/\lambda$.

## Esempi di Onde Meccaniche

### Onde Trasversali

Nelle onde trasversali, le particelle del mezzo oscillano in direzione **perpendicolare** alla direzione di propagazione dell'onda.
* **Esempio:** L'onda che si propaga su una corda tesa se la si scuote a un'estremità. Le sezioni della corda si muovono su e giù (verticalmente), mentre l'onda avanza orizzontalmente.
* La velocità di propagazione su una corda dipende dalla **tensione** ($T$) e dalla **densità lineare** ($\mu$, massa per unità di lunghezza): $v = \sqrt{T/\mu}$.

### Onde Longitudinali

Nelle onde longitudinali, le particelle del mezzo oscillano in direzione **parallela** alla direzione di propagazione dell'onda.
* **Esempio:** Il **suono** in un fluido (aria o acqua). Le molecole d'aria vibrano avanti e indietro *nella stessa direzione* in cui il suono si propaga, creando zone di **compressione** (alta densità e pressione) e **rarefazione** (bassa densità e pressione).
* **Rilevanza Medica:** Questa è la base del suono che udiamo e che usiamo per l'auscultazione. È anche il principio su cui si basa l'**ecografia**: un trasduttore invia onde sonore longitudinali (ultrasuoni, $f > 20 kHz$) nei tessuti corporei (che sono fluidi complessi) e l'analisi degli echi (onde riflesse) permette di ricostruire immagini diagnostiche.