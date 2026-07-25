La **meccanica dei fluidi** (che comprende liquidi e gas) studia il comportamento dei mezzi continui deformabili. Essendo di vitale importanza per comprendere l'emodinamica e la fisiologia della respirazione, è un argomento frequentissimo nei test per le professioni sanitarie.

## Grandezze Fondamentali nei Fluidi

### Densità (o Massa Volumica)
La densità $d$ (o $\rho$) è il rapporto tra la massa di un corpo e il volume che esso occupa:
$$ d = \frac{m}{V} $$
- **Unità di misura (SI):** $\text{kg/m}^3$. Spesso nei test troverai sottomultipli come $\text{g/cm}^3$ o $\text{kg/L}$.
- *Nota vitale per i quiz:* $1 \, \text{g/cm}^3 = 1000 \, \text{kg/m}^3$. L'acqua distillata a $4^\circ\text{C}$ ha una densità di $1000 \, \text{kg/m}^3$ (o $1 \, \text{kg/L}$).

### Pressione ($P$)
La pressione è una grandezza **scalare** definita come il rapporto tra il modulo della forza perpendicolare $F_{\perp}$ esercitata su una superficie e l'area $S$ della superficie stessa:
$$ P = \frac{F_{\perp}}{S} $$
- **Unità di misura (SI):** Il Pascal ($\text{Pa}$), dove $1 \, \text{Pa} = 1 \, \text{N/m}^2$.
- **Altre unità di misura frequenti e conversioni:**
  - Atmosfera ($\text{atm}$): $1 \, \text{atm} \approx 101325 \, \text{Pa}$ (spesso approssimato a $10^5 \, \text{Pa}$ nei calcoli rapidi).
  - Millimetro di mercurio ($\text{mmHg}$ o $\text{Torr}$): $1 \, \text{atm} = 760 \, \text{mmHg}$. Questa è l'unità standard utilizzata in medicina per la misurazione della pressione arteriosa!
  - Bar: $1 \, \text{bar} = 10^5 \, \text{Pa}$.

---

## Le Leggi Fondamentali dell'Idrostatica

### 1. Principio di Pascal
Una variazione di pressione prodotta sulla superficie di un fluido incomprimibile (come i liquidi) in equilibrio si trasmette inalterata a ogni punto del fluido e alle pareti del recipiente che lo contiene.
- **Applicazione (Il Torchio Idraulico o Elevatore Idraulico):**
  $$ \frac{F_1}{S_1} = \frac{F_2}{S_2} $$
  Questo principio ci permette di sollevare grandi carichi applicando forze modeste, sfruttando pistoni con aree di superficie diverse.

### 2. Legge di Stevino
La pressione idrostatica esercitata da un fluido incomprimibile a una profondità $h$ è direttamente proporzionale alla profondità stessa, alla densità del fluido $d$ e all'accelerazione di gravità $g$:
$$ P_h = d \cdot g \cdot h $$
- **Pressione Totale (o Assoluta):** Se la superficie del liquido è esposta all'atmosfera o a un'altra pressione esterna $P_0$, la pressione totale a profondità $h$ si calcola sommando le componenti:
  $$ P_{tot} = P_0 + d \cdot g \cdot h $$
> **Nota Medica per il Test:** Questo principio spiega fisicamente perché l'ago di una fleboclisi (flebo) deve essere posizionato a una certa altezza $h$ rispetto al braccio del paziente; il liquido deve superare la pressione venosa per poter entrare in circolo.

### 3. Principio di Archimede
Un corpo immerso (totalmente o parzialmente) in un fluido riceve una spinta verso l'alto (chiamata Forza di Galleggiamento o Spinta di Archimede, $F_A$) pari al peso del volume di fluido spostato.
$$ F_A = d_f \cdot V_{imm} \cdot g $$
Dove:
- $d_f$ è la densità del **fluido** (attenzione ai distrattori nei test: non è la densità del corpo!).
- $V_{imm}$ è il volume del corpo immerso (il volume di fluido spostato).
- $g$ è l'accelerazione di gravità.

**Condizioni di Galleggiamento:**
Confrontando la densità del corpo ($d_c$) con la densità del fluido ($d_f$):
- Se $d_c > d_f$: Il corpo **affonda**. La forza peso è maggiore della spinta di Archimede massima.
- Se $d_c = d_f$: Il corpo resta in **equilibrio** (galleggiamento neutro) in qualsiasi punto si trovi immerso.
- Se $d_c < d_f$: Il corpo **galleggia**. Una parte del corpo emergerà, in modo tale che la spinta fornita dalla sola parte immersa sia sufficiente ad eguagliare l'intero peso del corpo.

---
**Suggerimenti per la tua Wiki (Interconnessioni):**
- Ti suggerisco di creare il link al concetto di accelerazione e massa che abbiamo definito in `[[Dinamica: Leggi di Newton, Lavoro, Energia, Potenza e Conservazione]]`. 
- Sarebbe utilissimo creare una nota ponte intitolata `[[Applicazioni Mediche della Fisica]]`. Lì potrai aggregare concetti biologici e fisici, richiamando specifici blocchi da questo testo. Ad esempio, per spiegare il funzionamento dello sfigmomanometro, ti basterà digitare `[[Meccanica dei Fluidi: Pressione, Principi di Archimede, Stevino e Pascal#^]]` e selezionare dal menu a tendina il blocco della Legge di Stevino!