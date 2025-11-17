## Principio di Sovrapposizione

Quando due o più onde meccaniche si incontrano nello stesso punto di un mezzo, l'effetto risultante è determinato dal **Principio di Sovrapposizione**.

Per molti sistemi fisici (incluso il corpo umano per le onde sonore e ultrasoniche, purché l'ampiezza non sia estrema), vale il **principio di sovrapposizione lineare**:
> Lo spostamento totale ($y_{tot}$) di una particella del mezzo, in un dato istante $t$ e in una data posizione $x$, è la **somma algebrica** (o vettoriale, se gli spostamenti non sono collineari) degli spostamenti che ogni singola onda ($y_1$, $y_2$, ...) produrrebbe individualmente.

$$
y_{tot}(x, t) = y_1(x, t) + y_2(x, t) + \dots
$$

Dopo essersi incontrate e sovrapposte, le onde continuano a propagarsi indipendentemente, senza essersi modificate a vicenda.

## Interferenza

L'**interferenza** è il fenomeno che deriva dalla sovrapposizione di due o più onde *coerenti* (onde che mantengono una relazione di fase costante tra loro, solitamente perché hanno la stessa frequenza e provengono da sorgenti sincrone).

Consideriamo due onde armoniche $y_1$ e $y_2$ con stessa ampiezza $A$, stessa pulsazione $\omega$ e stesso numero d'onda $k$, che si propagano nella stessa direzione, ma con una differenza di fase $\Delta\phi$:
$y_1 = A \sin(kx - \omega t)$
$y_2 = A \sin(kx - \omega t + \Delta\phi)$

Applicando il principio di sovrapposizione $y_{tot} = y_1 + y_2$, e usando le formule di prostaferesi, l'onda risultante è:
$$
y_{tot}(x, t) = \left[ 2A \cos\left(\frac{\Delta\phi}{2}\right) \right] \cdot \sin\left(kx - \omega t + \frac{\Delta\phi}{2}\right)
$$
Questa è ancora un'onda armonica, ma la sua ampiezza $A_{ris} = |2A \cos(\Delta\phi/2)|$ dipende criticamente dalla differenza di fase $\Delta\phi$.

### 1. Interferenza Costruttiva

Si ha quando l'ampiezza risultante è massima (pari a $2A$). Questo accade quando i contributi delle onde si "sommano" perfettamente.
* **Condizione di Fase:** Avviene quando $\cos(\Delta\phi/2) = \pm 1$.
    $$
    \Delta\phi = 2n\pi \quad (n = 0, 1, 2, \dots)
    $$
    Le onde sono "in fase".
* **Differenza di Cammino ($\Delta x$):** Se la differenza di fase è dovuta a una diversa distanza percorsa dalle sorgenti, la condizione equivale a una differenza di cammino pari a un numero intero di lunghezze d'onda.
    $$
    \Delta x = n\lambda
    $$

### 2. Interferenza Distruttiva

Si ha quando l'ampiezza risultante è minima (pari a $0$, se le ampiezze iniziali sono uguali). Questo accade quando i contributi delle onde si "cancellano" a vicenda.
* **Condizione di Fase:** Avviene quando $\cos(\Delta\phi/2) = 0$.
    $$
    \Delta\phi = (2n+1)\pi \quad (n = 0, 1, 2, \dots)
    $$
    Le onde sono "in opposizione di fase".
* **Differenza di Cammino ($\Delta x$):** La differenza di cammino è pari a un numero intero di mezze lunghezze d'onda.
    $$
    \Delta x = \left(n + \frac{1}{2}\right)\lambda
    $$

---

## Onde Stazionarie

Le **onde stazionarie** sono un caso particolare e fondamentale di interferenza. *Non* sono onde di propagazione (non trasportano energia netta lungo il mezzo), ma piuttosto un "pattern" di oscillazione stabile.

### Condizioni di Formazione

Si formano quando due onde armoniche, con **stessa frequenza e stessa ampiezza**, si propagano **in direzioni opposte** nello stesso mezzo.
Questo si verifica tipicamente quando un'onda viene **riflessa** da un ostacolo e l'onda incidente e quella riflessa si sovrappongono.

Consideriamo:
* Onda incidente (verso $+x$): $y_1 = A \sin(kx - \omega t)$
* Onda riflessa (verso $-x$): $y_2 = A \sin(kx + \omega t)$

Sommandole $y_{tot} = y_1 + y_2$, e usando nuovamente le formule di prostaferesi, otteniamo l'equazione dell'onda stazionaria:
$$
y_{tot}(x, t) = \left[ 2A \sin(kx) \right] \cdot \cos(\omega t)
$$

### Significato Fisico e Struttura

Analizziamo l'equazione:
* Il termine $\cos(\omega t)$ indica che ogni particella del mezzo (ogni $x$) oscilla nel tempo con la stessa legge oraria (moto armonico).
* Il termine $[2A \sin(kx)]$ agisce come un'**ampiezza** che *dipende dalla posizione $x$*. Non è un'onda che viaggia, ma un'oscillazione stazionaria.

Questa struttura crea punti caratteristici:

* **Nodi (N):** Punti dello spazio che sono *sempre fermi* ($y_{tot} = 0$ per ogni $t$).
    * **Condizione:** L'ampiezza posizionale è nulla: $\sin(kx) = 0$.
    * **Posizione:** $kx = n\pi \implies \frac{2\pi}{\lambda}x = n\pi \implies x = n \frac{\lambda}{2}$ (con $n=0, 1, 2, \dots$).
    * I nodi sono distanziati tra loro di mezza lunghezza d'onda ($\lambda/2$).

* **Venti (V) o Antinodi:** Punti dello spazio che oscillano con la *massima ampiezza possibile* ($2A$).
    * **Condizione:** L'ampiezza posizionale è massima: $|\sin(kx)| = 1$.
    * **Posizione:** $kx = (n + \frac{1}{2})\pi \implies x = (n + \frac{1}{2})\frac{\lambda}{2}$ (con $n=0, 1, 2, \dots$).
    * I ventri si trovano esattamente a metà strada tra due nodi.

### Onde Stazionarie e Risonanza

Se il mezzo è confinato (ad esempio, una corda fissata ai due estremi, o la colonna d'aria nel condotto uditivo), l'onda stazionaria può formarsi stabilmente solo se la lunghezza del mezzo ($L$) è compatibile con la posizione dei nodi.

Se la corda ha lunghezza $L$ ed è fissata ai due estremi, questi estremi *devono* essere dei nodi.
* La condizione è $L = n (\lambda/2)$, dove $n$ è un numero intero positivo ($n = 1, 2, 3, \dots$).
* Questo significa che solo specifiche lunghezze d'onda sono "permesse": $\lambda_n = \frac{2L}{n}$.
* Di conseguenza, solo specifiche frequenze sono permesse (le **frequenze di risonanza** o **armoniche**):
    $$
    f_n = \frac{v}{\lambda_n} = \frac{v}{2L/n} = n \left( \frac{v}{2L} \right)
    $$
* $n=1$: $f_1 = v/2L$ (Frequenza fondamentale o prima armonica).
* $n=2$: $f_2 = 2 \cdot f_1$ (Seconda armonica).
* $n=3$: $f_3 = 3 \cdot f_1$ (Terza armonica), e così via.

Il fenomeno delle onde stazionarie e della risonanza è cruciale per la comprensione degli strumenti musicali, ma anche per la biofisica dell'udito (la membrana basilare nella coclea risponde a frequenze diverse in posizioni diverse, in modo analogo a un sistema di risonatori).