Le **onde acustiche**, o **suono**, sono il caso più importante di onde meccaniche longitudinali per la biologia e la medicina. Consistono nella propagazione di zone di compressione e rarefazione attraverso un mezzo materiale.

## 1. Propagazione del Suono

Il suono, essendo un'onda meccanica, **non si propaga nel vuoto**. Ha bisogno di un mezzo (solido, liquido o gas) per trasmettere la perturbazione.

La **velocità del suono ($v$)** non dipende dalla sorgente (né dalla frequenza, né dall'intensità), ma solo dalle proprietà del mezzo:
* **Modulo di comprimibilità ($B$):** Misura la "rigidità" del mezzo, ovvero quanto si oppone alla compressione. Un mezzo più rigido (alto $B$) trasmette il suono più velocemente.
* **Densità ($\rho$):** Misura l'inerzia del mezzo. Un mezzo più denso (alta $\rho$) è più "lento" da mettere in moto e trasmette il suono più lentamente.

La relazione generale è: $v = \sqrt{B / \rho}$

### Velocità del Suono in Mezzi Diversi

La rigidità (B) ha generalmente un impatto maggiore della densità ($\rho$). Per questo, contrariamente a quanto si potrebbe intuitivamente pensare, il suono viaggia molto più velocemente nei solidi e nei liquidi che nei gas.

| Mezzo | Velocità del Suono (approssimativa) | Rilevanza Medica |
| :--- | :--- | :--- |
| **Aria** (a $20^\circ C$) | $v \approx 343 \, m/s$ | Mezzo standard per l'udito e la fonazione. |
| **Acqua** (pura) | $v \approx 1480 \, m/s$ | Il corpo umano è composto per $\approx 60\%$ d'acqua. |
| **Tessuti Molli** | $v \approx 1540 \, m/s$ | Valore di riferimento standard usato in **Ecografia**. |
| **Osso** | $v \approx 4000 \, m/s$ | Conduzione ossea del suono (udibile). |

## 2. Intensità Acustica e Percezione

Come abbiamo visto, l'**Intensità ($I$)** è la misura fisica oggettiva dell'energia trasportata dall'onda (in $W/m^2$).

Tuttavia, la **percezione sonora** umana (chiamata *loudness* o "volume") non è lineare rispetto all'intensità. L'orecchio umano percepisce gli aumenti di intensità su una **scala logaritmica**.

* **Esempio:** Per percepire un suono come "doppiamente forte", l'intensità fisica ($I$) deve aumentare di un fattore circa 10.

Per questo motivo, per descrivere l'intensità sonora percepita si usa una scala logaritmica: il **Decibel ($dB$)**.

## 3. Livello di Intensità Sonora ($\beta$) in Decibel

Il **livello di intensità sonora ($\beta$)** non misura un'intensità assoluta, ma confronta (rapporta) l'intensità $I$ di un suono con un'intensità di riferimento standard, chiamata **soglia uditiva**.

### Soglia Uditiva ($I_0$)

La **soglia uditiva** è la minima intensità sonora che un orecchio umano medio, sano, può percepire (alla frequenza di $1000 Hz$, dove l'udito è più sensibile).
$$
I_0 = 1.0 \times 10^{-12} \, W/m^2
$$

### Definizione del Decibel

Il livello di intensità sonora $\beta$ in decibel ($dB$) è definito come:
$$
\beta \, (\text{dB}) = (10 \, \text{dB}) \cdot \log_{10} \left( \frac{I}{I_0} \right)
$$
Dove $\log_{10}$ è il logaritmo in base 10.

* Se $I = I_0$ (il suono è alla soglia uditiva), $\beta = 10 \cdot \log_{10}(1) = 0 \, \text{dB}$. La soglia uditiva corrisponde a 0 dB per definizione.
* Se l'intensità $I$ **aumenta di 10 volte** ($I' = 10 \cdot I$), il livello $\beta$ **aumenta di +10 dB**.
* Se l'intensità $I$ **aumenta di 100 volte** ($I' = 100 \cdot I$), il livello $\beta$ **aumenta di +20 dB**.
* Se l'intensità $I$ **raddoppia** ($I' = 2 \cdot I$), il livello $\beta$ **aumenta di circa +3 dB** (poiché $\log_{10}(2) \approx 0.3$).

## 4. Limiti di Udibilità dell'Orecchio Umano

L'udito umano è limitato sia in intensità che in frequenza.

### Limiti di Intensità
* **Soglia Uditiva:** $0 \, \text{dB}$ ($10^{-12} W/m^2$). Al di sotto di questo livello, l'orecchio non percepisce il suono.
* **Soglia del Dolore:** $\approx 120 \, \text{dB}$ ($1 \, W/m^2$). A questa intensità (un miliardo di miliardi di volte più intensa della soglia uditiva), il suono provoca dolore fisico e danno immediato all'apparato uditivo.
    * $85-90 \, \text{dB}$: Esposizione prolungata (ore) può causare danni permanenti (ipoacusia).

### Limiti di Frequenza
L'orecchio umano può percepire solo un intervallo specifico di frequenze:
* **Range Uditivo:** Da $\approx 20 \, \text{Hz}$ a $\approx 20,000 \, \text{Hz}$ (o $20 \, \text{kHz}$).
* **Infrasuoni:** Frequenze $f < 20 \, \text{Hz}$. Non sono udibili ma possono essere percepiti dal corpo come vibrazioni.
* **Ultrasuoni:** Frequenze $f > 20,000 \, \text{Hz}$. Non sono udibili dall'uomo (ma lo sono da altri animali, come cani e pipistrelli).
    * **Rilevanza Medica:** Gli ultrasuoni sono la base dell'imaging ecografico (tipicamente $2-15 \, \text{MHz}$, cioè milioni di Hz).

*Nota: Il range uditivo, specialmente per le alte frequenze (sopra i $15,000 Hz$), si riduce fisiologicamente con l'avanzare dell'età (presbiacusia).*