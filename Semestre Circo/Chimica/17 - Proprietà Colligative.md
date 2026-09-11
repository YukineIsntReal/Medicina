Le **proprietà colligative** (dal latino *colligare*, "legare insieme") sono proprietà fisiche delle soluzioni che **non dipendono dalla natura chimica** (tipo, massa, carica) del soluto, ma unicamente dal **numero di particelle** di soluto (molecole o ioni) presenti in una data quantità di solvente.

Sono proprietà fondamentali in biologia e medicina perché governano il movimento dell'acqua attraverso le membrane (osmosi) e determinano il comportamento dei fluidi corporei.

---

## 1. Interazioni Solvente-Soluto (La Causa Fisica)

L'aggiunta di un soluto **non volatile** (come sale o glucosio) a un solvente (come l'acqua) altera le proprietà del solvente stesso. La causa fisica di tutte le proprietà colligative è l'**interazione tra le particelle di soluto e le molecole di solvente**.

1.  **Riduzione della Frazione Molare del Solvente:** Il soluto, dissolvendosi, "occupa spazio". La frazione molare ($X_A$) del solvente (A) diminuisce perché ora il numero totale di particelle ($n_{tot}$) è aumentato.
    $$X_A = \frac{n_{solvente}}{n_{solvente} + n_{soluto}}$$

2.  **Interferenza Fisica:** Le particelle di soluto (spesso idratate, cioè circondate da molecole d'acqua) si posizionano sull'interfaccia liquido-vapore.
    * **Effetto:** Le molecole di soluto "bloccano" fisicamente una parte della superficie del solvente.
    * **Conseguenza:** Un minor numero di molecole di solvente si trova sulla superficie libera e ha l'energia sufficiente per passare allo stato di vapore (evaporare).

Questa interferenza è la causa diretta dell'**abbassamento della pressione di vapore**, che a sua volta causa l'innalzamento ebullioscopico e l'abbassamento crioscopico.



---

## 2. Abbassamento della Tensione di Vapore e Legge di Raoult

La **tensione (o pressione) di vapore** è la pressione esercitata dal vapore di un liquido in equilibrio con il liquido stesso a una data temperatura (in un contenitore chiuso).

* **Solvente Puro:** Ha una certa tensione di vapore ($P^\circ_A$).
* **Soluzione:** A causa dell'interferenza del soluto (vedi sopra), la tensione di vapore della soluzione ($P_A$) è **sempre più bassa** di quella del solvente puro.

### Legge di Raoult

La Legge di Raoult quantifica questo abbassamento per un soluto **non volatile**:

> La tensione di vapore ($P_A$) di un solvente in una soluzione ideale è uguale alla tensione di vapore del solvente puro ($P^\circ_A$) moltiplicata per la sua frazione molare ($X_A$) nella soluzione.

$$P_A = X_A \cdot P^\circ_A$$

* Poiché $X_A$ è sempre $< 1$ in una soluzione, $P_A$ sarà sempre $< P^\circ_A$.
* L'**abbassamento relativo della tensione di vapore** ($\Delta P / P^\circ_A$) è una proprietà colligativa e dipende solo dalla frazione molare del *soluto* ($X_B$).
    $$\Delta P = P^\circ_A - P_A = P^\circ_A - (X_A \cdot P^\circ_A) = P^\circ_A (1 - X_A)$$
    Poiché $X_A + X_B = 1$, allora $1 - X_A = X_B$.
    $$\Delta P = X_B \cdot P^\circ_A$$
    $$\frac{\Delta P}{P^\circ_A} = X_B$$

---

## 3. Innalzamento Ebullioscopico (della Temperatura di Ebollizione)

* **Definizione di Ebollizione:** Un liquido bolle quando la sua tensione di vapore eguaglia la pressione atmosferica esterna (es. $760$ mmHg al livello del mare).
* **Effetto del Soluto:** Poiché la tensione di vapore della soluzione è più bassa, essa non raggiungerà la pressione esterna alla temperatura di ebollizione normale del solvente puro (es. $100^\circ$C per l'acqua).
* **Conseguenza:** Bisogna fornire **più calore** (aumentare la temperatura) affinché la tensione di vapore della soluzione salga fino a eguagliare la pressione esterna.

L'**innalzamento ebullioscopico** ($\Delta T_{eb}$) è l'aumento della temperatura di ebollizione della soluzione rispetto al solvente puro. È proporzionale alla **molalità** ($m$) della soluzione.

$$\Delta T_{eb} = T_{eb, soluzione} - T_{eb, solvente} = K_{eb} \cdot m$$

* $\Delta T_{eb}$: Innalzamento ebullioscopico (in $^\circ$C o K).
* $K_{eb}$: **Costante ebullioscopica molale**, una proprietà specifica del *solvente* (per l'acqua: $0.512$ $^\circ$C$\cdot$kg/mol).
* $m$: **Molalità** della soluzione (moli soluto / kg solvente). Si usa la molalità e non la molarità perché la molalità non dipende dalla temperatura.

---

## 4. Abbassamento Crioscopico (della Temperatura di Congelamento)

* **Definizione di Congelamento:** È la temperatura alla quale un liquido si solidifica, formando un reticolo cristallino ordinato.
* **Effetto del Soluto:** Le particelle di soluto (es. ioni $Na^+$ e $Cl^-$ idratati) interferiscono fisicamente con la formazione del reticolo cristallino del solvente (es. la struttura esagonale del ghiaccio).
* **Conseguenza:** È necessaria una temperatura **più bassa** per "costringere" le molecole di solvente a rallentare abbastanza da organizzarsi nel solido, espellendo il soluto.

L'**abbassamento crioscopico** ($\Delta T_{cr}$) è la diminuzione della temperatura di congelamento della soluzione rispetto al solvente puro. È proporzionale alla **molalità** ($m$) della soluzione.

$$\Delta T_{cr} = T_{cr, solvente} - T_{cr, soluzione} = K_{cr} \cdot m$$

* $\Delta T_{cr}$: Abbassamento crioscopico (in $^\circ$C o K).
* $K_{cr}$: **Costante crioscopica molale**, specifica del *solvente* (per l'acqua: $1.86$ $^\circ$C$\cdot$kg/mol).
* $m$: **Molalità** della soluzione (moli soluto / kg solvente).

### Il Coefficiente di van 't Hoff ($i$): Correzione per Elettroliti

Le formule viste sopra ($\Delta T = K \cdot m$) funzionano per soluti **non elettroliti** (come glucosio o urea), dove $1$ mole di soluto produce $1$ mole di particelle.

Ma gli **elettroliti** (come $NaCl$) si dissociano:
$NaCl \rightarrow Na^+ + Cl^-$ ($1$ mole di soluto $\rightarrow 2$ moli di particelle)
$CaCl_2 \rightarrow Ca^{2+} + 2Cl^-$ ($1$ mole di soluto $\rightarrow 3$ moli di particelle)

Poiché le proprietà colligative dipendono dal *numero* di particelle, l'effetto è raddoppiato o triplicato.

Si introduce il **coefficiente di van 't Hoff ($i$)**:
$i = \frac{\text{moli di particelle effettive in soluzione}}{\text{moli di soluto (formula) disciolte}}$

* Per non elettroliti (glucosio): $i = 1$
* Per elettroliti forti (valore teorico):
    * $NaCl \rightarrow i = 2$
    * $CaCl_2 \rightarrow i = 3$
    * $K_2SO_4 \rightarrow i = 3$

Le formule corrette per le proprietà colligative (indispensabili in medicina) sono:

> $$\Delta T_{eb} = i \cdot K_{eb} \cdot m$$
>
> $$\Delta T_{cr} = i \cdot K_{cr} \cdot m$$

L'abbassamento crioscopico è particolarmente importante in laboratorio medico per misurare la concentrazione totale di particelle nel siero o nelle urine (vedi **Osmolalità**).