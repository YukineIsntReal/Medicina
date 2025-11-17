Il magnetismo è un fenomeno strettamente legato all'elettricità. Non esistono "cariche magnetiche" isolate (monopoli magnetici); i campi magnetici sono sempre generati da **cariche elettriche in movimento** (cioè, correnti).

## 1. Origine del Campo Magnetico (Esperimento di Oersted)

Nel 1820, Hans Christian Oersted scoprì che un filo percorso da [[Corrente e Leggi di Ohm#1. Intensità di Corrente (I)|corrente elettrica]] ($I$) genera un campo magnetico ($\vec{B}$) nello spazio circostante.
* Se un ago di una bussola (un piccolo magnete) viene posto vicino al filo, esso si orienta perpendicolarmente al filo stesso.
* Le linee di campo del campo magnetico $\vec{B}$ generato da un filo rettilineo sono circonferenze concentriche, centrate sul filo.

Il verso di $\vec{B}$ si determina con la **regola della mano destra**: puntando il pollice nel verso della corrente $I$, le dita si chiudono nel verso delle linee di campo $\vec{B}$.

## 2. Forza di Lorentz (su una carica in moto)

Un campo magnetico $\vec{B}$ esercita una forza, chiamata **Forza di Lorentz**, *solo* su cariche elettriche $q$ che sono *in movimento* con velocità $\vec{v}$.
La forza è data dal prodotto vettoriale:
$\vec{F}_B = q (\vec{v} \times \vec{B})$

Il modulo della forza è:
$F_B = |q| v B \sin(\theta)$
dove $\theta$ è l'angolo tra il vettore velocità $\vec{v}$ e il vettore campo magnetico $\vec{B}$.

### Proprietà della Forza di Lorentz
1.  **Direzione:** La forza $\vec{F}_B$ è sempre **perpendicolare** sia a $\vec{v}$ che a $\vec{B}$ (si trova con la regola della mano destra).
2.  **Nessuna Forza se $\vec{v} \parallel \vec{B}$:** Se la carica si muove parallelamente al campo ($\theta=0^\circ$ o $\theta=180^\circ$), $\sin(\theta)=0$ e la forza è **nulla**.
3.  **Nessuna Forza se $\vec{v}=0$:** La forza è nulla su cariche ferme.
4.  **Nessun Lavoro:** Poiché $\vec{F}_B$ è sempre perpendicolare allo spostamento (che è lungo $\vec{v}$), la forza magnetica **non compie lavoro** ($W = \int \vec{F} \cdot d\vec{s} = 0$). Di conseguenza, un campo magnetico *non può cambiare l'energia cinetica* ($K$) di una particella; può solo cambiarne la **direzione** (cioè defletterla).

Se sono presenti sia un [[Fondamenti di Elettrostatica#3. Il Campo Elettrico|campo elettrico]] $\vec{E}$ che un campo magnetico $\vec{B}$, la forza totale sulla carica $q$ è la somma delle due forze (Forza di Lorentz generalizzata):
$\vec{F}_{tot} = \vec{F}_E + \vec{F}_B = q\vec{E} + q(\vec{v} \times \vec{B})$

## 3. Moto Circolare in Campo Magnetico Uniforme

Consideriamo una carica $q$ che entra con velocità $\vec{v}$ in una regione con un campo $\vec{B}$ uniforme, in direzione perpendicolare al campo ($\vec{v} \perp \vec{B}$, quindi $\theta=90^\circ$ e $\sin(90^\circ)=1$).

1.  La forza ha modulo costante: $F_B = |q| v B$.
2.  La forza è sempre perpendicolare a $\vec{v}$.
3.  Una forza di modulo costante, sempre perpendicolare alla velocità, è la definizione di **forza centripeta**.

La particella è quindi costretta a muoversi in un **moto circolare uniforme**. La forza di Lorentz fornisce la forza centripeta ($F_c = m v^2 / r$) necessaria:
$F_B = F_c \implies |q| v B = \frac{m v^2}{r}$

Risolvendo per il raggio $r$ dell'orbita:
$r = \frac{m v}{|q| B}$
Il raggio è proporzionale alla quantità di moto ($mv$) e inversamente proporzionale alla carica e al campo.

## 4. Forza su un Filo percorso da Corrente

Una corrente $I$ in un filo di lunghezza $L$ non è altro che un insieme di cariche $q$ in movimento. La forza magnetica totale su quel filo, immerso in un campo $\vec{B}$ uniforme, è:
$\vec{F} = I (\vec{L} \times \vec{B})$

Dove $\vec{L}$ è un vettore che ha:
* **Modulo:** la lunghezza $L$ del filo.
* **Direzione:** la stessa della corrente convenzionale $I$.

Il modulo della forza è $F = I L B \sin(\theta)$.

## 5. Momento Torcente su una Spira (Dipolo Magnetico)

Consideriamo una spira rettangolare (lati $a$ e $b$) percorsa da corrente $I$, immersa in un campo $\vec{B}$ uniforme parallelo al piano della spira.
* Le forze sui lati $b$ (paralleli a $\vec{B}$) sono nulle ($\theta=0$).
* Le forze sui lati $a$ (perpendicolari a $\vec{B}$) sono uguali e opposte ($\vec{F}$ e $-\vec{F}$, modulo $F = I a B$), ma non giacciono sulla stessa linea d'azione.
* Questa coppia di forze genera un **momento torcente** ($\vec{\tau}$) che fa ruotare la spira, tendendo ad allinearla perpendicolarmente al campo $\vec{B}$.

### Momento di Dipolo Magnetico ($\vec{\mu}$)
Per generalizzare, si definisce il **momento di dipolo magnetico** $\vec{\mu}$ della spira:
$\vec{\mu} = I \cdot \vec{A}$

Dove:
* $\vec{A}$ è il vettore Area (modulo $A=ab$, direzione perpendicolare al piano della spira, data dalla regola della mano destra seguendo la corrente $I$).
* $I$ è la corrente.
L'unità di misura è $A \cdot m^2$.

Il **momento torcente** $\vec{\tau}$ che il campo $\vec{B}$ esercita sulla spira è:
$\vec{\tau} = \vec{\mu} \times \vec{B}$

Questa è l'esatta analoga della formula per il dipolo elettrico ($\vec{\tau} = \vec{p} \times \vec{E}$).

L'**energia potenziale** $U$ del dipolo magnetico nel campo $\vec{B}$ è:
$U = - \vec{\mu} \cdot \vec{B} = - \mu B \cos(\theta)$
L'energia è minima ($U_{min}$) quando $\vec{\mu}$ è allineato a $\vec{B}$ ($\theta=0^\circ$, equilibrio stabile) ed è massima ($U_{max}$) quando è anti-allineato ($\theta=180^\circ$, equilibrio instabile).