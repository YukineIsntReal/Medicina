Questa nota espande i principi di base dell'equilibrio chimico, introducendo concetti quantitativi (Q, Kps), distinzioni (omogeneo/eterogeneo, stato stazionario) e applicazioni biologiche.

## 1. Reazioni Reversibili ed Irreversibili

* **Reazioni Reversibili:** Sono reazioni che possono procedere in entrambe le direzioni (diretta e inversa) e sono indicate dalla doppia freccia ($\rightleftharpoons$). Raggiungono uno stato di equilibrio dinamico. La maggior parte delle reazioni biologiche è reversibile.
* **Reazioni Irreversibili:** Procedono essenzialmente a completamento in una sola direzione ($\rightarrow$). Spesso, sono reazioni termodinamicamente molto favorite (con un $\Delta G \ll 0$ o una $K_{eq}$ estremamente grande) o reazioni in cui un prodotto viene rimosso dal sistema (es. formazione di un gas che fugge).

---

## 2. Legge d'Azione di Massa e Costante di Equilibrio ($K_{eq}$)

Come visto in [[L'Equilibrio Chimico]], per una reazione generica all'equilibrio:
$$aA + bB \rightleftharpoons cC + dD$$

La **Legge di Azione di Massa** stabilisce che il rapporto tra il prodotto delle concentrazioni dei prodotti e il prodotto delle concentrazioni dei reagenti, ciascuno elevato al proprio coefficiente stoechiometrico, è una costante a una data temperatura. Questa è la **Costante di Equilibrio ($K_{eq}$)**.

$$K_{eq} = \frac{[C]^c [D]^d}{[A]^a [B]^b}$$

* Ricorda: $[ ]$ indica la concentrazione molare all'**equilibrio**.

---

## 3. Il Quoziente di Reazione ($Q_c$)

Il **Quoziente di Reazione ($Q_c$ o $Q$)** ha la *stessa forma matematica* della $K_{eq}$, ma utilizza le concentrazioni in un **qualsiasi istante $t$**, non necessariamente all'equilibrio.

$$Q_c = \frac{[C]^c [D]^d}{[A]^a [B]^b} \quad (\text{a un tempo } t)$$

Confrontare $Q_c$ con $K_{eq}$ ci permette di **prevedere la direzione** in cui la reazione si sposterà per raggiungere l'equilibrio:
* **$Q_c = K_{eq}$**: Il sistema è **all'equilibrio**. Non c'è spostamento netto.
* **$Q_c < K_{eq}$**: Il rapporto prodotti/reagenti è *troppo basso*. Per aumentare $Q_c$ fino a $K_{eq}$, la reazione deve **spostarsi verso destra ($\rightarrow$)**, consumando reagenti e formando prodotti.
* **$Q_c > K_{eq}$**: Il rapporto prodotti/reagenti è *troppo alto*. Per diminuire $Q_c$ fino a $K_{eq}$, la reazione deve **spostarsi verso sinistra ($\leftarrow$)**, consumando prodotti e formando reagenti.

Il $\Delta G$ (non-standard) è legato a $Q$ dalla relazione: $\Delta G = \Delta G^\circ + RT \ln Q_c$.
All'equilibrio, $\Delta G=0$ e $Q_c=K_{eq}$, il che ci porta a $\Delta G^\circ = -RT \ln K_{eq}$.

---

## 4. Equilibrio Omogeneo ed Eterogeneo

* **Equilibrio Omogeneo:** Tutti i reagenti e i prodotti si trovano nella **stessa fase** (es. tutti in soluzione acquosa $aq$, o tutti in fase gassosa $g$).
    * *Esempio (Estere):* $CH_3COOH(aq) + C_2H_5OH(aq) \rightleftharpoons CH_3COOC_2H_5(aq) + H_2O(l)$
* **Equilibrio Eterogeneo:** Reagenti e prodotti si trovano in **due o più fasi diverse** (es. $s$, $l$, $g$, $aq$).
    * **Regola Fondamentale:** Nell'espressione di $K_{eq}$ (e $Q_c$) si **om ettono** le concentrazioni (o pressioni parziali) dei **solidi puri ($s$)** e dei **liquidi puri ($l$)**, poiché la loro concentrazione (densità) è costante e incorporata in $K_{eq}$.
    * *Esempio:* $CaCO_3(s) \rightleftharpoons CaO(s) + CO_2(g)$
    * $K_{eq} = [CO_2]$ (o $K_p = P_{CO_2}$)

---

## 5. Differenza tra Equilibrio Chimico e Stato Stazionario

Questa è una distinzione *cruciale* in biologia.
* **Equilibrio Chimico:**
    * È uno stato di un **sistema chiuso** (non scambia materia).
    * Le velocità (diretta e inversa) sono uguali ($v_d = v_i$).
    * Non c'è flusso netto di materia.
    * La variazione di Energia Libera di Gibbs è zero ($\Delta G = 0$).
    * **Una cellula all'equilibrio chimico è una cellula morta.**
* **Stato Stazionario (Steady State):**
    * È uno stato di un **sistema aperto** (come una cellula, che scambia materia ed energia con l'ambiente).
    * Le **concentrazioni degli intermedi** rimangono costanti nel tempo, *non* perché le reazioni sono all'equilibrio, ma perché la velocità di **formazione** di un intermedio è uguale alla sua velocità di **consumo**.
    * C'è un **flusso netto** (flux) di materia attraverso il sistema (es. glucosio $\rightarrow$ piruvato).
    * Il sistema è *lontano* dall'equilibrio ($\Delta G < 0$).
    * *Analogia:* Un lavandino con il rubinetto aperto e lo scarico aperto. Il livello dell'acqua (concentrazione) può rimanere costante (stato stazionario), ma c'è un flusso continuo di acqua che entra ed esce (flusso metabolico).

---

## 6. Principio dell'Equilibrio Mobile (di Le Châtelier)

Come visto in [[L'Equilibrio Chimico]], questo principio afferma che quando un sistema all'equilibrio viene perturbato da un cambiamento (di concentrazione, pressione/volume, o temperatura), il sistema si sposterà nella direzione che **annulla o contrasta l'effetto** della perturbazione, ristabilendo un nuovo equilibrio.

---

## 7. Effetto della Temperatura sulla Costante di Equilibrio

La temperatura è l'unica perturbazione che **cambia il valore di $K_{eq}$**. L'effetto dipende dall'entalpia ($\Delta H$) della reazione.

* **Reazioni Endotermiche ($\Delta H > 0$):** Assorbono calore.
    $Reagenti + \text{Calore} \rightleftharpoons Prodotti$
    * Un **aumento di $T$** (aggiunta di "reagente") sposta l'equilibrio a **destra** ($\rightarrow$).
    * **$K_{eq}$ aumenta**.
* **Reazioni Esotermiche ($\Delta H < 0$):** Rilasciano calore.
    $Reagenti \rightleftharpoons Prodotti + \text{Calore}$
    * Un **aumento di $T$** (aggiunta di "prodotto") sposta l'equilibrio a **sinistra** ($\leftarrow$).
    * **$K_{eq}$ diminuisce**.
* *Quantitative:* La **Legge di van 't Hoff** descrive questa dipendenza:
    $$\ln\left(\frac{K_2}{K_1}\right) = -\frac{\Delta H^\circ}{R}\left(\frac{1}{T_2} - \frac{1}{T_1}\right)$$

---

## 8. Equilibri Multipli

Quando in un sistema avvengono più reazioni all'equilibrio contemporaneamente.
* **Reazioni Accoppiate:** Il prodotto di una reazione è un reagente per la successiva.
* **Regola:** Se una reazione complessiva è la *somma* di due o più reazioni, la sua $K_{eq}$ totale è il *prodotto* delle costanti di equilibrio delle singole reazioni.
* *Esempio (Acidi Poliprotici, vedi [[Acidi e Basi]]):*
    1.  $H_2CO_3 \rightleftharpoons H^+ + HCO_3^-$ \quad ($K_{a1}$)
    2.  $HCO_3^- \rightleftharpoons H^+ + CO_3^{2-}$ \quad ($K_{a2}$)
    * *Totale:* $H_2CO_3 \rightleftharpoons 2H^+ + CO_3^{2-}$ \quad ($K_{tot} = K_{a1} \cdot K_{a2}$)

---

## 9. Equilibri Eterogenei Solido-Liquido: Prodotto di Solubilità ($K_{ps}$)

Questo descrive l'equilibrio di un sale ionico "insolubile" (o poco solubile) che si dissolve in acqua.

* **Equilibrio di Solubilità:**
    $AgCl(s) \rightleftharpoons Ag^+(aq) + Cl^-(aq)$
* **Prodotto di Solubilità ($K_{ps}$ o $K_{sp}$):** È la costante di equilibrio per questa reazione. Essendo $AgCl$ un solido puro, viene omesso.
    $$K_{ps} = [Ag^+][Cl^-]$$
* Il $K_{ps}$ è una misura della solubilità di un composto: più piccolo è $K_{ps}$, meno solubile è il sale.
* **Solubilità Molare ($s$):** È la concentrazione molare ($mol/L$) del sale che si è sciolto all'equilibrio.
    * Per $AgCl \rightleftharpoons Ag^+ + Cl^-$, \quad $s = [Ag^+] = [Cl^-]$
        $K_{ps} = (s)(s) = s^2$
    * Per $CaF_2 \rightleftharpoons Ca^{2+} + 2F^-$, \quad $s = [Ca^{2+}]$, $[F^-] = 2s$
        $K_{ps} = [Ca^{2+}][F^-]^2 = (s)(2s)^2 = 4s^3$

---

## 10. Effetto dello Ione in Comune

È un'applicazione diretta del Principio di Le Châtelier all'equilibrio di solubilità.

> L'**effetto dello ione in comune** è la **diminuzione della solubilità** di un sale ionico quando alla soluzione viene aggiunto un altro composto che contiene uno ione in comune con il sale.

* *Esempio:* Cosa succede se aggiungo $NaCl$ (fonte di $Cl^-$) a una soluzione satura di $AgCl$?
    * *Equilibrio:* $AgCl(s) \rightleftharpoons Ag^+(aq) + Cl^-(aq)$
    * *Perturbazione:* Aumento di $[Cl^-]$ (lo ione $Cl^-$ è "in comune").
    * *Risposta (Le Châtelier):* Il sistema si oppone all'aumento di $[Cl^-]$ spostando l'equilibrio a **sinistra** ($\leftarrow$).
    * *Risultato:* Parte di $Ag^+(aq)$ e $Cl^-(aq)$ reagiscono, formando altro precipitato $AgCl(s)$. La solubilità di $AgCl$ **diminuisce**.

---

## 11. Rilevanza Biologica degli Equilibri Chimici

L'equilibrio chimico è il linguaggio della fisiologia.

1.  **Omeostasi Acido-Base (pH del sangue):**
    * Il sistema tampone bicarbonato/anidride carbonica è l'esempio perfetto di equilibri multipli, omogenei ed eterogenei:
        $$CO_2(g) \rightleftharpoons CO_2(aq)$$
        $$CO_2(aq) + H_2O(l) \rightleftharpoons H_2CO_3(aq)$$
        $$H_2CO_3(aq) \rightleftharpoons H^+(aq) + HCO_3^-(aq)$$
    * La respirazione (che controlla $CO_2(g)$, Principio di Le Châtelier) e la funzione renale (che controlla $[HCO_3^-]$) mantengono il $[H^+]$ (pH) in un range ristrettissimo.

2.  **Formazione e Riassorbimento Osseo:**
    * L'osso è fatto di Idrossiapatite, $Ca_5(PO_4)_3(OH)(s)$.
    * Questo solido è in un equilibrio $K_{ps}$ con gli ioni $Ca^{2+}$ e $PO_4^{3-}$ nel plasma.
    * $Ca_5(PO_4)_3(OH)(s) \rightleftharpoons 5Ca^{2+}(aq) + 3PO_4^{3-}(aq) + OH^-(aq)$
    * Gli ormoni (paratormone, calcitonina) regolano questo equilibrio alterando le concentrazioni ioniche (effetto ione in comune) o il pH (che influenza la protonazione del fosfato), portando a deposizione ossea o riassorbimento.

3.  **Trasporto di Ossigeno:**
    * Il legame dell'ossigeno all'emoglobina ($Hb$) è un equilibrio:
        $Hb + 4O_2 \rightleftharpoons Hb(O_2)_4$
    * Nei polmoni, l'alta $P_{O_2}$ (alta "concentrazione" di $O_2$) sposta l'equilibrio a destra (caricamento).
    * Nei tessuti, la bassa $P_{O_2}$ sposta l'equilibrio a sinistra (rilascio).
    * Questo equilibrio è influenzato da altri equilibri (equilibri multipli), come quello del pH (Effetto Bohr), dove un aumento di $[H^+]$ (ambiente acido) sposta l'equilibrio a sinistra, favorendo il rilascio di $O_2$.