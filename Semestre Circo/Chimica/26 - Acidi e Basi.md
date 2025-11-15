## Teorie Acido-Base

Esistono diverse teorie per definire acidi e basi, ognuna con un livello di generalità crescente.

### 1. Teoria di Arrhenius (circa 1887)

Questa teoria è limitata alle soluzioni acquose.
* **Acido:** Una sostanza che, sciolta in acqua, aumenta la concentrazione di ioni idrogeno ($H^+$). (Oggi sappiamo che $H^+$ reagisce immediatamente con $H_2O$ per formare lo ione idronio, $H_3O^+$).
    * *Esempio:* $HCl(g) + H_2O(l) \rightarrow H_3O^+(aq) + Cl^-(aq)$
* **Base:** Una sostanza che, sciolta in acqua, aumenta la concentrazione di ioni idrossido ($OH^-$).
    * *Esempio:* $NaOH(s) \rightarrow Na^+(aq) + OH^-(aq)$

### 2. Teoria di Brønsted-Lowry (1923)

Questa teoria è più generale e si concentra sul trasferimento di protoni. Non è limitata alle soluzioni acquose.
* **Acido:** Un donatore di protoni ($H^+$).
* **Base:** Un accettore di protoni ($H^+$).

Una reazione acido-base secondo Brønsted-Lowry coinvolge il trasferimento di un protone da un acido a una base, formando un **acido coniugato** e una **base coniugata**.

$HA + B \rightleftharpoons A^- + HB^+$
(Acido 1) + (Base 2) $\rightleftharpoons$ (Base Coniugata 1) + (Acido Coniugato 2)

* $A^-$ è la base coniugata dell'acido $HA$.
* $HB^+$ è l'acido coniugato della base $B$.

*Esempio:*
$NH_3 + H_2O \rightleftharpoons NH_4^+ + OH^-$
(Base) + (Acido) $\rightleftharpoons$ (Acido Coniugato) + (Base Coniugata)

### 3. Cenni sulla Teoria di Lewis (1923)

È la teoria più generale, focalizzata sulle coppie di elettroni.
* **Acido:** Un accettore di una coppia di elettroni (specie elettron-deficiente, elettrofilo).
* **Base:** Un donatore di una coppia di elettroni (specie ricca di elettroni, nucleofilo).

*Esempio:* La reazione tra trifluoruro di boro e ammoniaca.
$BF_3 + :NH_3 \rightarrow F_3B-NH_3$
(Acido di Lewis) + (Base di Lewis) $\rightarrow$ (Addotto)

---

## L'Acqua e la Scala di pH

### Reazione di Autoprotolisi (o Autoionizzazione) dell'Acqua

L'acqua è una sostanza **anfotera** (o anfiprotica), può comportarsi sia da acido che da base (secondo Brønsted-Lowry).

$H_2O(l) + H_2O(l) \rightleftharpoons H_3O^+(aq) + OH^-(aq)$
(Acido 1) + (Base 2) $\rightleftharpoons$ (Acido Coniugato 2) + (Base Coniugata 1)

Questa reazione è un equilibrio, descritto dal **prodotto ionico dell'acqua ($K_w$)**:

$K_w = [H_3O^+][OH^-]$

A 25°C, $K_w = 1.0 \times 10^{-14}$.
In acqua pura a 25°C: $[H_3O^+] = [OH^-] = \sqrt{K_w} = 1.0 \times 10^{-7} M$.

### Concetto di pH e pOH

Per evitare l'uso di numeri esponenziali molto piccoli, si utilizzano le scale logaritmiche (operatore $p = -\log_{10}$).

* **pH:** $pH = -\log[H_3O^+]$
* **pOH:** $pOH = -\log[OH^-]$

Relazione tra pH e pOH:
Applicando l'operatore $p$ all'equazione della $K_w$:
$-\log(K_w) = -\log([H_3O^+][OH^-]) = (-\log[H_3O^+]) + (-\log[OH^-])$
$pK_w = pH + pOH$

A 25°C: **$14.00 = pH + pOH$**

* Soluzione acida: $[H_3O^+] > [OH^-] \implies pH < 7$
* Soluzione neutra: $[H_3O^+] = [OH^-] \implies pH = 7$
* Soluzione basica: $[H_3O^+] < [OH^-] \implies pH > 7$

---

## Forza degli Acidi e delle Basi

### Costanti di Dissociazione ($K_a$ e $K_b$)

La forza di un acido o di una base si misura dalla loro tendenza a dissociarsi (ionizzarsi) in acqua.

#### Acidi Forti e Deboli

* **Acidi Forti:** Si dissociano completamente in acqua ($HCl$, $H_2SO_4$, $HNO_3$, ecc.). La reazione non è un equilibrio (freccia singola).
    $HCl + H_2O \rightarrow H_3O^+ + Cl^-$
    Per un acido forte, $[H_3O^+]$ è uguale alla concentrazione iniziale dell'acido ($C_a$).
* **Acidi Deboli:** Si dissociano parzialmente (equilibrio). La forza è quantificata dalla **costante di dissociazione acida ($K_a$)**.
    $HA + H_2O \rightleftharpoons H_3O^+ + A^-$
    $K_a = \frac{[H_3O^+][A^-]}{[HA]}$

Più $K_a$ è grande, più l'acido è forte (equilibrio spostato a destra).

#### Basi Forti e Deboli

* **Basi Forti:** Si dissociano completamente (es. idrossidi dei metalli alcalini, $NaOH$, $KOH$).
    $NaOH(s) \rightarrow Na^+(aq) + OH^-(aq)$
    Per una base forte, $[OH^-]$ è uguale alla concentrazione iniziale della base ($C_b$).
* **Basi Deboli:** Reagiscono parzialmente con l'acqua (equilibrio). La forza è quantificata dalla **costante di dissociazione basica ($K_b$)**.
    $B + H_2O \rightleftharpoons HB^+ + OH^-$
    $K_b = \frac{[HB^+][OH^-]}{[B]}$

#### $pK_a$ e $pK_b$

Come per il pH, si usano le scale logaritmiche:
* $pK_a = -\log K_a$ (Nota: $K_a$ alta $\implies$ $pK_a$ bassa $\implies$ Acido forte)
* $pK_b = -\log K_b$ (Nota: $K_b$ alta $\implies$ $pK_b$ bassa $\implies$ Base forte)

Per una coppia acido-base coniugata:
$K_a \times K_b = K_w \implies pK_a + pK_b = pK_w = 14$

Questa relazione è fondamentale: più un acido è forte (basso $pK_a$), più la sua base coniugata è debole (alto $pK_b$).

### Indicatori di pH

Gli indicatori sono acidi o basi deboli la cui forma acida ($HIn$) e la forma basica coniugata ($In^-$) hanno colori diversi.
$HIn + H_2O \rightleftharpoons H_3O^+ + In^-$
(Colore A) $\rightleftharpoons$ (Colore B)

Il colore della soluzione dipende dal rapporto $[In^-]/[HIn]$, che è a sua volta determinato dal pH (secondo l'equazione di Henderson-Hasselbalch). L'indicatore cambia colore (vira) in un intervallo di pH centrato attorno al suo $pK_a$ (detto $pK_{In}$).

---

## Calcolo del pH

Sia $C_a$ la concentrazione iniziale dell'acido e $C_b$ la concentrazione iniziale della base.

1.  **Acido Forte:**
    La dissociazione è completa: $[H_3O^+] = C_a$
    $pH = -\log(C_a)$
    *(Attenzione: se $C_a$ è molto diluita, es. $10^{-8} M$, l'autoprotolisi dell'acqua non è trascurabile).*

2.  **Base Forte:**
    La dissociazione è completa: $[OH^-] = C_b$
    $pOH = -\log(C_b)$
    $pH = 14 - pOH$

3.  **Acido Debole ($HA$):**
    $HA + H_2O \rightleftharpoons H_3O^+ + A^-$
    All'equilibrio: $[HA] \approx C_a$; $[H_3O^+] = [A^-] = x$
    $K_a = \frac{x \cdot x}{C_a} \implies x^2 = K_a \cdot C_a \implies x = \sqrt{K_a \cdot C_a}$
    Formula approssimata: **$[H_3O^+] \approx \sqrt{K_a \cdot C_a}$**
    In forma logaritmica: **$pH \approx \frac{1}{2}(pK_a - \log C_a)$**

4.  **Base Debole ($B$):**
    $B + H_2O \rightleftharpoons HB^+ + OH^-$
    Formula approssimata: **$[OH^-] \approx \sqrt{K_b \cdot C_b}$**
    In forma logaritmica: **$pOH \approx \frac{1}{2}(pK_b - \log C_b)$**
    E poi $pH = 14 - pOH$.

### Acidi e Basi Poliprotici

Sono specie che possono donare o accettare più di un protone. Hanno costanti di dissociazione multiple ($K_{a1}, K_{a2}, ...$).
*Esempio: Acido Carbonico ($H_2CO_3$), importante nel sistema tampone bicarbonato.*

$H_2CO_3 + H_2O \rightleftharpoons HCO_3^- + H_3O^+ \qquad K_{a1} = 4.5 \times 10^{-7}$
$HCO_3^- + H_2O \rightleftharpoons CO_3^{2-} + H_3O^+ \qquad K_{a2} = 4.7 \times 10^{-11}$

Poiché $K_{a1} \gg K_{a2}$, la prima dissociazione è la fonte predominante di $H_3O^+$. Per il calcolo del pH di un acido poliprotico debole, si può spesso considerare solo la prima dissociazione, trattandolo come un acido debole monoprotico con $K_a = K_{a1}$.

---

## Relazione Struttura-Forza degli Acidi

1.  **Forza del Legame $H-X$:** Più il legame $H-X$ è debole, più l'acido è forte (è più facile rompere il legame e donare $H^+$).
    *Esempio (Idracidi, lungo un gruppo):* $HF < HCl < HBr < HI$. La forza del legame diminuisce scendendo nel gruppo, la forza acida aumenta.
2.  **Elettronegatività di $X$:** A parità di periodo, più $X$ è elettronegativo, più il legame è polarizzato ($H^{\delta+}-X^{\delta-}$) e più l'idrogeno è "acido".
    *Esempio (Lungo un periodo):* $CH_4 < NH_3 \ll H_2O < HF$.
3.  **Ossiacidi ($H-O-Y-$):**
    * *Elettronegatività di Y:* Più $Y$ è elettronegativo, più attira elettroni dal legame $O-H$, indebolendolo e rendendo l'acido più forte.
        *Esempio:* $H_3BO_3$ (debole) < $H_2CO_3$ (medio) < $HNO_3$ (forte).
    * *Numero di Ossigeni (non legati a H):* All'aumentare degli atomi di ossigeno legati a $Y$ (atomi elettronegativi), aumenta la delocalizzazione della carica della base coniugata (che si stabilizza) e aumenta la polarizzazione del legame $O-H$.
        *Esempio:* $HClO$ (ipocloroso, debolissimo) < $HClO_2$ (cloroso) < $HClO_3$ (clorico) < $HClO_4$ (perclorico, fortissimo).

---

## Sali e Idrolisi

I sali sono elettroliti forti che si dissociano completamente in acqua. Gli ioni risultanti possono reagire con l'acqua (reazione di **idrolisi**), modificando il pH.

1.  **Sale da Acido Forte + Base Forte (es. $NaCl$):**
    $NaCl \rightarrow Na^+ + Cl^-$
    $Na^+$ è l'acido coniugato della base forte $NaOH$ (è un acido nullo).
    $Cl^-$ è la base coniugata dell'acido forte $HCl$ (è una base nulla).
    Nessuno dei due ioni reagisce con l'acqua. **pH = 7 (Neutro)**.

2.  **Sale da Base Forte + Acido Debole (es. $CH_3COONa$ - Acetato di Sodio):**
    $CH_3COONa \rightarrow Na^+ + CH_3COO^-$
    $Na^+$ è neutro.
    $CH_3COO^-$ (Acetato) è la base coniugata dell'acido debole $CH_3COOH$. Reagisce con l'acqua (idrolisi basica):
    $CH_3COO^- + H_2O \rightleftharpoons CH_3COOH + OH^-$
    La soluzione produce ioni $OH^-$. **pH > 7 (Basico)**.
    La costante di questa reazione è la **costante di idrolisi ($K_h$)**, che non è altro che la $K_b$ della base coniugata: $K_h = K_b = \frac{K_w}{K_a(CH_3COOH)}$.

3.  **Sale da Base Debole + Acido Forte (es. $NH_4Cl$ - Cloruro d'Ammonio):**
    $NH_4Cl \rightarrow NH_4^+ + Cl^-$
    $Cl^-$ è neutro.
    $NH_4^+$ (Ammonio) è l'acido coniugato della base debole $NH_3$. Reagisce con l'acqua (idrolisi acida):
    $NH_4^+ + H_2O \rightleftharpoons NH_3 + H_3O^+$
    La soluzione produce ioni $H_3O^+$. **pH < 7 (Acido)**.
    La costante di idrolisi è la $K_a$ dell'acido coniugato: $K_h = K_a = \frac{K_w}{K_b(NH_3)}$.

4.  **Sale da Base Debole + Acido Debole (es. $NH_4CH_3COO$):**
    Entrambi gli ioni idrolizzano. Il pH dipende dalla forza relativa dell'acido e della base:
    * Se $K_a(NH_4^+) > K_b(CH_3COO^-) \implies$ pH < 7 (Acido)
    * Se $K_a(NH_4^+) < K_b(CH_3COO^-) \implies$ pH > 7 (Basico)
    * Se $K_a \approx K_b \implies$ pH $\approx$ 7 (Neutro)
    (In questo caso $K_a$ e $K_b$ sono molto simili, quindi il pH è circa 7).

---

## Solubilità e pH: Esempi di Interesse Biomedico

La solubilità di molti sali poco solubili è influenzata dal pH, specialmente se l'anione è la base coniugata di un acido debole.

### 1. Ossalato di Calcio ($CaC_2O_4$)

L'ossalato di calcio è il principale costituente di molti **calcoli renali**.
L'equilibrio di solubilità è:
$CaC_2O_4(s) \rightleftharpoons Ca^{2+}(aq) + C_2O_4^{2-}(aq)$

L'ione ossalato ($C_2O_4^{2-}$) è la base coniugata dell'acido ossalico ($H_2C_2O_4$), un acido debole.
Se il pH della soluzione diminuisce (diventa più acida, $[H_3O^+]$ aumenta), la base $C_2O_4^{2-}$ viene protonata:
$C_2O_4^{2-} + H_3O^+ \rightleftharpoons HC_2O_4^- + H_2O$

Secondo il **Principio di Le Chatelier**, la rimozione di $C_2O_4^{2-}$ (perché convertito in $HC_2O_4^-$) sposta l'equilibrio di solubilità verso destra, per produrre altro $C_2O_4^{2-}$.
**Conclusione:** L'ossalato di calcio è **più solubile in ambiente acido** (pH basso) rispetto all'acqua pura. Urine cronicamente acide possono (paradossalmente, in questo specifico caso) aiutare a prevenire la formazione di calcoli di ossalato, mentre urine alcaline la favoriscono.

### 2. Fosfato di Calcio (es. Idrossiapatite)

L'idrossiapatite, $Ca_5(PO_4)_3OH$, è il principale componente minerale delle **ossa** e dei **denti**.
$Ca_5(PO_4)_3OH(s) \rightleftharpoons 5Ca^{2+}(aq) + 3PO_4^{3-}(aq) + OH^-(aq)$

Entrambi gli anioni, fosfato ($PO_4^{3-}$) e idrossido ($OH^-$), sono basi (il $PO_4^{3-}$ è la base coniugata di $HPO_4^{2-}$, una base relativamente forte).

Se il pH del sangue diminuisce (condizione di **acidosi metabolica** o respiratoria), l'aumento di $[H_3O^+]$ consuma entrambe le basi:
$PO_4^{3-} + H_3O^+ \rightarrow HPO_4^{2-} + H_2O$
$OH^- + H_3O^+ \rightarrow 2 H_2O$

Per il Principio di Le Chatelier, la rimozione dei prodotti ($PO_4^{3-}$ e $OH^-$) sposta l'equilibrio di solubilità verso destra, ovvero **promuove la dissoluzione del minerale osseo**.
**Conclusione:** L'acidosi cronica (pH ematico basso) porta alla **demineralizzazione ossea**, poiché le ossa agiscono come "tampone" fornendo basi (fosfato e idrossido) per neutralizzare l'eccesso di acido, al costo della propria integrità strutturale.

---
