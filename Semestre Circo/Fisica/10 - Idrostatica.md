L'**idrostatica** è la branca della fisica dei fluidi che studia i fluidi in condizioni di equilibrio statico, ovvero in quiete.

---

## Legge di Stevino
La Legge di Stevino descrive la variazione della pressione all'interno di un fluido in quiete, dovuta alla gravità.

Afferma che la pressione ($P$) a una certa profondità ($h$) in un fluido omogeneo e incomprimibile è data dalla somma della pressione esercitata sulla superficie libera del fluido ($P_0$, solitamente la pressione atmosferica) e la pressione dovuta al peso della colonna di fluido soprastante (pressione idrostatica).

* **Formula**: $P(h) = P_0 + \rho g h$
* **Dove**:
    * $P(h)$ è la pressione assoluta alla profondità $h$.
    * $P_0$ è la pressione alla superficie (es. $P_{atm}$).
    * $\rho$ (rho) è la densità del fluido.
    * $g$ è l'accelerazione di gravità.
    * $h$ è la profondità (o altezza della colonna di fluido).

**Nota**: La differenza di pressione $\Delta P = P(h) - P_0 = \rho g h$ è chiamata **pressione relativa** o **pressione idrostatica**. Questa legge spiega perché la pressione aumenta linearmente con la profondità.

---

## Principio di Pascal
Il Principio di Pascal (o legge di Pascal) descrive la trasmissione della pressione nei fluidi incomprimibili in quiete.

Afferma che una variazione di pressione applicata a un punto qualsiasi di un fluido confinato e incomprimibile si trasmette **integralmente e istantaneamente** a ogni altro punto del fluido e alle pareti del contenitore.

* **Applicazione**: Questo principio è alla base del funzionamento del torchio idraulico e dei sistemi frenanti idraulici. In medicina, spiega come le variazioni di pressione in un compartimento fluido (es. liquor cerebrospinale) si distribuiscano.

---

## Principio di Archimede e Galleggiamento

### Principio di Archimede
Il Principio di Archimede descrive la forza (spinta) che un fluido esercita su un corpo immerso in esso.

Afferma che un corpo immerso (totalmente o parzialmente) in un fluido riceve una **spinta idrostatica** ($F_A$, o Spinta di Archimede) verticale, diretta dal basso verso l'alto, la cui intensità è pari al **peso del volume di fluido spostato** dal corpo.

* **Formula**: $F_A = \rho_{fluido} \cdot g \cdot V_{immerso}$
* **Dove**:
    * $F_A$ è la spinta idrostatica.
    * $\rho_{fluido}$ è la densità del fluido.
    * $g$ è l'accelerazione di gravità.
    * $V_{immerso}$ è il volume della parte del corpo immersa nel fluido (che corrisponde al volume di fluido spostato).

### Analisi delle Condizioni di Galleggiamento
Le condizioni di galleggiamento dipendono dal confronto tra la spinta di Archimede ($F_A$) e la forza peso del corpo ($F_P = m_{corpo} \cdot g = \rho_{corpo} \cdot g \cdot V_{corpo}$).

Considerando un corpo omogeneo completamente immerso ($V_{immerso} = V_{corpo}$):

1.  **Il corpo affonda**: Se il peso del corpo è maggiore della spinta di Archimede.
    * $F_P > F_A \implies \rho_{corpo} > \rho_{fluido}$
2.  **Il corpo rimane in equilibrio (neutro)**: Se il peso del corpo è uguale alla spinta di Archimede.
    * $F_P = F_A \implies \rho_{corpo} = \rho_{fluido}$
3.  **Il corpo galleggia (emerge)**: Se il peso del corpo è minore della spinta di Archimede.
    * $F_P < F_A \implies \rho_{corpo} < \rho_{fluido}$
    * Il corpo emerge parzialmente fino a raggiungere una nuova condizione di equilibrio in cui $F_A = F_P$. In questa condizione, $V_{immerso}$ sarà solo una frazione del $V_{corpo}$ totale, tale che:
        $\rho_{fluido} \cdot g \cdot V_{immerso} = \rho_{corpo} \cdot g \cdot V_{corpo}$
        $\frac{V_{immerso}}{V_{corpo}} = \frac{\rho_{corpo}}{\rho_{fluido}}$

---

## Strumenti e Metodi per la Misura della Pressione

### Esperimento di Torricelli (Barometro)
L'esperimento di Evangelista Torricelli (1643) ha portato all'invenzione del **barometro a mercurio**, il primo strumento capace di misurare la pressione atmosferica.

* **Funzionamento**: Un tubo di vetro, chiuso a un'estremità, viene riempito di mercurio ($Hg$) e capovolto in una vaschetta contenente altro mercurio.
* La colonna di mercurio nel tubo scende fino a un'altezza $h$ (circa $760 \, mm$ a livello del mare), lasciando il vuoto (o quasi) nella parte superiore del tubo (camera barometrica).
* L'equilibrio si raggiunge quando la pressione idrostatica della colonna di mercurio ($P_{Hg} = \rho_{Hg} \cdot g \cdot h$) eguaglia la pressione atmosferica ($P_{atm}$) che agisce sulla superficie libera della vaschetta.
* $P_{atm} = \rho_{Hg} \cdot g \cdot h$
* **Unità di misura**: Da qui derivano unità come il $mmHg$ (millimetro di mercurio) o $Torr$ ($1 \, Torr \approx 1 \, mmHg$).

### Manometro
Il manometro è uno strumento utilizzato per misurare la **pressione relativa** (differenza tra la pressione di un fluido e quella atmosferica).

* **Manometro a tubo a U**: La forma più semplice. Un tubo a U contiene un liquido (spesso mercurio o acqua).
    * Un'estremità è connessa al fluido di cui si vuole misurare la pressione ($P_{fluido}$).
    * L'altra estremità è aperta all'atmosfera ($P_{atm}$) o a un riferimento.
    * La differenza di pressione $\Delta P = P_{fluido} - P_{atm}$ è proporzionale al dislivello ($h$) del liquido nelle due branche del tubo, secondo la legge di Stevino ($\Delta P = \rho_{liquido} \cdot g \cdot h$).
* **Sfigmomanometro**: Lo strumento medicale per misurare la pressione arteriosa è un tipo di manometro (storicamente a mercurio, oggi più spesso aneroide o digitale).