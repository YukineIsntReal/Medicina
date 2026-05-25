Le **proprietà colligative** sono quattro proprietà chimico-fisiche delle soluzioni che **dipendono esclusivamente dal numero totale di particelle di soluto** presenti nell'unità di volume (cioè dalla concentrazione totale) e **non dalla natura chimica del soluto** stesso. ^definizione-colligative

* **Principio fondamentale per i quiz:** Una mole di molecole di glucosio, una mole di urea e una mole di saccarosio esercitano esattamente lo stesso effetto colligativo se sciolte nello stesso volume di solvente, poiché contengono lo stesso identico numero di particelle ($6,022 \cdot 10^{23}$, Numero di Avogadro). Al contrario, le sostanze che si dissociano modificano questo equilibrio (vedi il [[#4. Il Coefficiente di van 't Hoff (i)|Coefficiente di van 't Hoff]]).

---

## 1. Abbassamento della Tensione di Vapore (Legge di Raoult)
La tensione (o pressione) di vapore è la pressione esercitata dal vapore in equilibrio con il proprio liquido puro a una determinata temperatura. Quando un soluto non volatile viene sciolto in un solvente liquido, le sue particelle occupano parte della superficie libera del liquido, riducendo lo spazio disponibile per l'evaporazione delle molecole del solvente. ^legge-raoult

La **Legge di Raoult** definisce matematicamente questo fenomeno:
> *La tensione di vapore di una soluzione ($P_{\text{soluz}}$) è pari alla tensione di vapore del solvente puro ($P^\circ_{\text{solv}}$) moltiplicata per la frazione molare del solvente ($\chi_{\text{solv}}$).*

* **Formula lineare:** $P_{\text{soluz}} = P^\circ_{\text{solv}} \cdot \chi_{\text{solv}}$
* **Formula dell'abbassamento di tensione ($\Delta P$):**
  $\Delta P = P^\circ_{\text{solv}} - P_{\text{soluz}} = P^\circ_{\text{solv}} \cdot \chi_{\text{soluto}} \cdot i$

---

## 2. Innalzamento Ebullioscopico e Abbassamento Crioscopico
A causa dell'abbassamento della tensione di vapore descritto dalla Legge di Raoult, i punti di transizione di stato della soluzione si spostano rispetto a quelli del solvente puro. ^variazioni-termiche



### A) Innalzamento Ebullioscopico ($\Delta T_e$)
Un liquido bolle quando la sua tensione di vapore eguaglia la pressione atmosferica esterna. Poiché la tensione di vapore della soluzione è più bassa, sarà necessario riscaldare maggiormente il sistema per raggiungere l'ebollizione. La soluzione bolle quindi a una temperatura più alta del solvente puro.
* **Formula:** $\Delta T_e = T_{\text{ebollizione, soluz}} - T_{\text{ebollizione, solv}} = K_e \cdot m \cdot i$
* $K_e$ = Costante ebullioscopica molale (per l'acqua vale $0,512 \, ^\circ\text{C} \cdot \text{kg/mol}$).
* $m$ = [[Concentrazione delle Soluzioni#2. Molalità (m)|Molalità]] della soluzione.
* $i$ = Coefficiente di van 't Hoff.

### B) Abbassamento Crioscopico ($\Delta T_c$)
Le particelle di soluto disciolte disturbano la formazione del reticolo cristallino solido del solvente. Per consentire il congelamento, è necessario sottrarre più energia, abbassando la temperatura rispetto al normale punto di congelamento.
* **Formula:** $\Delta T_c = T_{\text{congelamento, solv}} - T_{\text{congelamento, soluz}} = K_c \cdot m \cdot i$
* $K_c$ = Costante crioscopica molale (per l'acqua vale $1,86 \, ^\circ\text{C} \cdot \text{kg/mol}$).
* *Attenzione ai segni:* L'acqua pura congela a $0 \, ^\circ\text{C}$. Una soluzione acquosa congelerà a un valore negativo corrispondente a $T_{\text{congelamento, soluz}} = 0 - \Delta T_c$.

---

## 3. Pressione Osmotica ($\pi$)
L'**osmosi** è il flusso spontaneo di molecole di solvente (acqua) attraverso una **membrana semipermeabile** (che permette il passaggio del solvente ma blocca il soluto), muovendosi da una soluzione più diluita (ipotona) verso una soluzione più concentrata (ipertona). ^osmosi

La **pressione osmotica** ($\pi$) è definita come la pressione idrostatica da applicare alla soluzione più concentrata per bloccare perfettamente questo flusso spontaneo. ^pressione-osmotica

* **Equazione di van 't Hoff:** $\pi = M \cdot R \cdot T \cdot i$
  * $M$ = [[Concentrazione delle Soluzioni#1. Molarità (M)|Molarità]] della soluzione ($mol/L$).
  * $R$ = Costante universale dei gas ($0,0821 \, \text{L} \cdot \text{atm} / \text{mol} \cdot \text{K}$).
  * $T$ = Temperatura assoluta espressa in **Kelvin** ($K = ^\circ\text{C} + 273,15$).
  * $i$ = Coefficiente di van 't Hoff.

### Tonicità delle Soluzioni e Risvolti Fisiologici (Domanda Classica)
La classificazione delle soluzioni in base alla pressione osmotica è fondamentale in biologia cellulare, specialmente studiando il comportamento delle emazie (globuli rossi):

* **Soluzioni Isotoniche:** Hanno la **stessa pressione osmotica** (stessa concentrazione totale di particelle). Il flusso netto di acqua è nullo. La soluzione fisiologica ($NaCl$ allo $0,9\% \, m/V$) è isotonica rispetto al citoplasma cellulare umano (~300 mOsm/L).
* **Soluzioni Ipertoniche:** Hanno una pressione osmotica **maggiore** (più concentrate dell'ambiente interno cellulare). Se un globulo rosso viene immerso in una soluzione ipertonica, l'acqua esce dalla cellula per osmosi, causandone il rimpicciolimento e il raggrinzimento (**crenazione**).
* **Soluzioni Ipotoniche:** Hanno una pressione osmotica **minore** (più diluite dell'ambiente interno cellulare). Se un globulo rosso viene posto in acqua distillata (ipotonica), l'acqua entra massivamente nella cellula, gonfiandola fino a causarne la rottura (**emolisi**).

---

## 4. Il Coefficiente di van 't Hoff ($i$)
Il coefficiente $i$ è un fattore correttivo adimensionale che indica il numero totale di moli di particelle (ioni o molecole) che si formano effettivamente in soluzione dalla dissociazione di una mole di soluto. ^coefficiente-van-thoff

* **Per i non-elettroliti (soluti che non si dissociano):** $i = 1$
  * *Esempi:* Glucosio ($C_6H_{12}O_6$), Saccarosio ($C_{12}H_{22}O_{11}$), Urea ($CO(NH_2)_2$), Etanolo ($C_2H_5OH$).
* **Per gli elettroliti forti (sostanze ioniche o acidi/basi forti che si dissociano al 100%):** $i$ equivale al numero totale di ioni liberati dalla formula.
  * Cloruro di sodio: $NaCl \rightarrow Na^+ + Cl^- \implies i = 2$
  * Cloruro di calcio: $CaCl_2 \rightarrow Ca^{2+} + 2Cl^- \implies i = 3$
  * Solfato di sodio: $Na_2SO_4 \rightarrow 2Na^+ + SO_4^{2-} \implies i = 3$
  * Idrossido di alluminio: $Al(OH)_3 \rightarrow Al^{3+} + 3OH^- \implies i = 4$

* **Esempio pratico per i quiz:** Una soluzione $1 \, M$ di $NaCl$ ($i=2$) genera una concentrazione di particelle pari a $2 \, Osm/L$. Avrà un innalzamento ebullioscopico, un abbassamento crioscopico e una pressione osmotica **doppie** rispetto a una soluzione $1 \, M$ di glucosio ($i=1$).