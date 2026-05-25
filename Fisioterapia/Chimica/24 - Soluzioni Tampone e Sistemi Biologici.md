Una **soluzione tampone** (o semplicemente "tampone") è una soluzione acquosa in grado di **mantenere il proprio pH quasi invariato** anche in seguito all'aggiunta di moderate quantità di acidi forti o basi forti. 

Questa capacità di "ammortizzare" le variazioni di pH è fondamentale in ambito chimico e, soprattutto, nei sistemi biologici, dove gli enzimi e le proteine funzionano correttamente solo in range di pH estremamente ristretti.

---

## 1. Composizione di una Soluzione Tampone
Per funzionare, un tampone deve contenere due specie chimiche in equilibrio tra loro: una in grado di neutralizzare gli acidi (ioni $H^+$) e una in grado di neutralizzare le basi (ioni $OH^-$), senza che reagiscano tra di loro.

Le soluzioni tampone sono sempre formate da:
1. Un **acido debole** miscelato con un suo sale solubile (che fornisce la sua **base coniugata**).
   * *Esempio:* Acido acetico ($CH_3COOH$) e acetato di sodio ($CH_3COONa$).
2. *Oppure*, una **base debole** miscelata con un suo sale solubile (che fornisce il suo **acido coniugato**).
   * *Esempio:* Ammoniaca ($NH_3$) e cloruro di ammonio ($NH_4Cl$).

---

## 2. Come Funziona un Tampone? (Meccanismo d'Azione)
Il funzionamento si basa sul [[Principio di Le Chatelier]] applicato all'equilibrio della coppia acido/base debole. Prendiamo come esempio il tampone generico $HA / A^-$ (Acido debole / Base coniugata).

* **Se aggiungiamo un Acido Forte (ioni $H^+$):**
  La base coniugata del tampone reagisce con i protoni aggiunti, trasformandosi nell'acido debole.
  $$A^- + H^+ \rightarrow HA$$
  Gli ioni $H^+$ liberi "scompaiono" dalla soluzione, impedendo un crollo del pH.

* **Se aggiungiamo una Base Forte (ioni $OH^-$):**
  L'acido debole del tampone reagisce con gli ossidrili, neutralizzandoli e formando acqua.
  $$HA + OH^- \rightarrow A^- + H_2O$$
  Gli ioni $OH^-$ "scompaiono", impedendo un'impennata del pH.

> [!warning] Potere Tamponante e Limiti
> La capacità di un tampone non è infinita. Il "potere tamponante" è massimo quando le concentrazioni dell'acido e della sua base coniugata sono uguali ($[HA] = [A^-]$). Se si aggiunge troppo acido o troppa base, il tampone si "esaurisce" e il pH inizia a variare drasticamente.

---

## 3. Calcolo del pH: L'Equazione di Henderson-Hasselbalch
Nei test d'ingresso, per calcolare il pH di una soluzione tampone, non si risolvono equazioni complesse ma si utilizza una formula diretta, nota come equazione di Henderson-Hasselbalch:

$$pH = pK_a + \log \left( \frac{[A^-]}{[HA]} \right)$$
*Dove:*
* $pK_a = -\log(K_a)$ dell'acido debole.
* $[A^-]$ è la concentrazione della base coniugata (o del sale).
* $[HA]$ è la concentrazione dell'acido debole.

**Deduzione fondamentale per i quiz:** Se le concentrazioni dell'acido e del sale sono uguali ($[A^-] = [HA]$), il rapporto vale $1$. Poiché il logaritmo di $1$ è $0$, la formula si riduce a:
$$pH = pK_a$$

---

## 4. Importanza Biologica: Il Tampone Bicarbonato
I liquidi corporei umani, in particolare il plasma sanguigno, devono mantenere un pH rigorosamente costante. 

> [!danger] Valori Fisiologici da Memorizzare (Focus Test)
> Il pH del sangue arterioso in condizioni normali è compreso tra **7,35 e 7,45**.
> * Se il pH scende sotto 7,35 si parla di **Acidosi**.
> * Se il pH sale sopra 7,45 si parla di **Alcalosi**.

Il principale sistema che mantiene questo equilibrio nel sangue extracellulare è il **sistema tampone Acido Carbonico / Ione Bicarbonato ($H_2CO_3 / HCO_3^-$)**.

L'acido carbonico è un acido debole che si forma quando l'anidride carbonica ($CO_2$) prodotta dal metabolismo cellulare si discioglie nel sangue:
$$CO_2 + H_2O \rightleftharpoons H_2CO_3 \rightleftharpoons H^+ + HCO_3^-$$

Questo tampone è straordinario perché è un "sistema aperto", finemente regolato da due organi principali:
1. **I Polmoni (Regolazione Rapida):** Regolano la concentrazione di $CO_2$ tramite la respirazione. Aumentando la frequenza respiratoria (iperventilazione) si espelle più $CO_2$, spostando l'equilibrio a sinistra e alzando il pH del sangue (vedi [[Fisiologia della Respirazione]]).
2. **I Reni (Regolazione Lenta):** Regolano l'escrezione e il riassorbimento degli ioni bicarbonato ($HCO_3^-$) e dei protoni ($H^+$) nelle urine (vedi [[Fisiologia Renale e Nefrogenesi]]).

---
**Vedi anche:** [[Acidi e Basi: Le Tre Teorie Fondamentali]], [[Il pH: Concetti Fondamentali e Calcolo]], [[Principio di Le Chatelier]]