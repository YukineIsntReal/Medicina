Le onde meccaniche, pur non trasportando materia, sono un meccanismo fondamentale per il **trasporto di energia**. L'energia viene fornita dalla sorgente al mezzo e si propaga insieme alla perturbazione.

## 1. Energia Associata all'Onda

L'energia di un'onda meccanica è la somma dell'energia cinetica e dell'energia potenziale delle particelle del mezzo che oscillano.

1.  **Energia Cinetica ($K$):** Le particelle del mezzo (di massa $m$) non sono ferme, ma oscillano attorno alla loro posizione di equilibrio con una velocità $v_y$ (per un'onda trasversale sull'asse $y$). La loro energia cinetica è $K = \frac{1}{2} m v_y^2$.
2.  **Energia Potenziale ($U$):** Il mezzo è elastico. Spostare una particella dalla sua posizione di equilibrio (allungando/comprimendo il mezzo circostante) equivale a compiere un lavoro, che viene immagazzinato come energia potenziale elastica.

Per un'onda armonica, sia $K$ che $U$ variano nel tempo e nello spazio, ma l'energia totale ($E = K + U$) che la sorgente "immette" nel mezzo per generare l'onda è costante.

Un risultato fondamentale è che l'energia trasportata da un'onda armonica è **proporzionale al quadrato della sua ampiezza ($A^2$)** e al **quadrato della sua frequenza ($f^2$ o $\omega^2$)**.
$$
E \propto A^2 \omega^2
$$

## 2. Potenza ($P$)

In fisica ondulatoria, siamo più interessati al *tasso* con cui l'energia viene trasportata, piuttosto che all'energia totale. Questa grandezza è la **potenza ($P$)**.

La **Potenza** è definita come l'energia trasportata dall'onda attraverso una sezione del mezzo per unità di tempo ($P = dE/dt$). Si misura in **Watt ($W$)**, dove $1 W = 1 J/s$.

Anche la potenza oscilla nel tempo. È più utile definire la **Potenza Media ($\bar{P}$)**, che è la potenza mediata su un ciclo completo ($T$).

Per un'onda armonica monodimensionale (es. su una corda) di densità lineare $\mu$ (massa/lunghezza), la potenza media è:
$$
\bar{P} = \frac{1}{2} \mu \omega^2 A^2 v
$$
Dove:
* $\mu$ è la densità lineare del mezzo.
* $\omega$ è la pulsazione ($2\pi f$).
* $A$ è l'ampiezza.
* $v$ è la velocità di propagazione dell'onda nel mezzo.

Questo conferma che la potenza (l'energia al secondo) trasferita è proporzionale al quadrato di ampiezza e frequenza.

## 3. Intensità ($I$)

La Potenza descrive l'energia totale al secondo, ma in tre dimensioni (come per il suono) questa energia si distribuisce su un'area. La grandezza fisica più rilevante e misurabile è l'**Intensità ($I$)**.

L'**Intensità** è definita come la **Potenza media ($\bar{P}$) che attraversa un'area ($S$) perpendicolare alla direzione di propagazione dell'onda, divisa per l'area stessa**.
$$
I = \frac{\bar{P}}{S}
$$
* **Unità di Misura:** Si misura in **Watt su metro quadro ($W/m^2$)**.

L'intensità è la grandezza che descrive quanto "forte" è un'onda in un certo punto. Poiché $\bar{P} \propto A^2$, l'Intensità è a sua volta proporzionale al quadrato dell'ampiezza:
$$
I \propto A^2
$$
Questo significa che per raddoppiare l'ampiezza di un'onda, dobbiamo fornire un'energia quattro volte maggiore.

### Legge dell'Inverso del Quadrato (Onde Sferiche)

Se un'onda si propaga uniformemente in tutte le direzioni da una sorgente puntiforme (onda sferica, come il suono di una voce in aria), la potenza $\bar{P}$ della sorgente si distribuisce sulla superficie di una sfera di raggio $r$.

L'area della sfera è $S = 4\pi r^2$. L'intensità a distanza $r$ è:
$$
I = \frac{\bar{P}}{4\pi r^2}
$$
Questo mostra che l'intensità **diminuisce con il quadrato della distanza ($I \propto 1/r^2$)**.
* **Significato Pratico:** Se raddoppiamo la distanza dalla sorgente, l'intensità che percepiamo (e misuriamo) diventa $1/4$. Se la triplichiamo, diventa $1/9$. Questo è il motivo per cui il suono si attenua rapidamente con la distanza.