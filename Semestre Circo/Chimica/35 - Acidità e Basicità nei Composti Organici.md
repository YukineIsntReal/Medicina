## Definizioni di Acidi e Basi

1.  **Teoria di Brønsted-Lowry (la più usata in organica):**
    * **Acido:** Un donatore di protoni ($H^+$).
    * **Base:** Un accettore di protoni ($H^+$).
    * **Reazione:** $HA + B \rightleftharpoons A^- + BH^+$
        * $HA$ (acido) perde $H^+$ e diventa $A^-$ (**Base Coniugata**).
        * $B$ (base) accetta $H^+$ e diventa $BH^+$ (**Acido Coniugato**).
    * **Nota:** L'acqua ($H_2O$) è **anfotera**: può agire sia da base (accettando $H^+$ $\rightarrow H_3O^+$) sia da acido (donando $H^+$ $\rightarrow OH^-$).

2.  **Teoria di Lewis (più generale):**
    * **Acido di Lewis:** Un accettore di una coppia di elettroni (un [[Rottura di un legame: omolitico ed eterolitico. Carbocationi e carboanioni. Stabilità dei carbocationi. Nucleofili ed elettrofili.#Elettrofili ($E^+$)|Elettrofilo]]).
    * **Base di Lewis:** Un donatore di una coppia di elettroni (un [[Rottura di un legame: omolitico ed eterolitico. Carbocationi e carboanioni. Stabilità dei carbocationi. Nucleofili ed elettrofili.#Nucleofili ($Nu:$)|Nucleofilo]]).
    * **Collegamento:** Tutte le basi di Brønsted sono basi di Lewis (usano un *lone pair* per accettare $H^+$). Non tutti gli acidi di Brønsted sono acidi di Lewis, ma il protone $H^+$ stesso è un acido di Lewis.

---

## Forza degli Acidi: $K_a$ e $pK_a$

La forza di un acido $HA$ si misura quantitativamente dalla sua **costante di dissociazione acida ($K_a$)** in acqua:

$$HA + H_2O \rightleftharpoons A^- + H_3O^+$$
$$K_a = \frac{[A^-][H_3O^+]}{[HA]}$$

* **$K_a$ alta:** L'equilibrio è spostato a destra. L'acido è **forte** (si dissocia molto).
* **$K_a$ bassa:** L'equilibrio è spostato a sinistra. L'acido è **debole** (si dissocia poco).

Per praticità si usa il **$pK_a$**:
$$pK_a = -\log(K_a)$$

**Relazione Inversa:**
* **$pK_a$ Basso** $\rightarrow$ $K_a$ Alta $\rightarrow$ **Acido Forte**
* **$pK_a$ Alto** $\rightarrow$ $K_a$ Bassa $\rightarrow$ **Acido Debole**

> **Regola Fondamentale:** La forza di un acido ($HA$) dipende dalla **stabilità della sua base coniugata ($A^-$)**.
> *Più la base coniugata $A^-$ è stabile, più l'acido $HA$ sarà forte (e avrà un $pK_a$ basso)*.

Il nostro obiettivo diventa quindi: capire cosa stabilizza la base coniugata $A^-$.

---

## Fattori Strutturali che Influenzano l'Acidità

### 1. Elettronegatività

L'acidità aumenta all'aumentare dell'elettronegatività dell'atomo ($A$) che porta la carica negativa nella base coniugata.
* **Periodo (sinistra $\rightarrow$ destra):** L'elettronegatività è il fattore dominante.
* **Esempio:** Confronto tra $CH_4$, $NH_3$, $H_2O$, $HF$.
    * Basi coniugate: $CH_3^-, NH_2^-, OH^-, F^-$
    * Stabilità: $F^-$ > $OH^-$ > $NH_2^-$ > $CH_3^-$ (il Fluoro, più elettronegativo, "sopporta" meglio la carica negativa).
    * Acidità: **$HF > H_2O > NH_3 > CH_4$**

### 2. Dimensione (Polarizzabilità)

Quando si confrontano acidi nello stesso **gruppo** (colonna) della tavola periodica, la dimensione dell'atomo è più importante dell'elettronegatività.
* **Gruppo (alto $\rightarrow$ basso):** L'acidità aumenta scendendo nel gruppo.
* **Esempio:** Confronto tra $HF, HCl, HBr, HI$.
    * Basi coniugate: $F^-, Cl^-, Br^-, I^-$
    * Stabilità: $I^-$ > $Br^-$ > $Cl^-$ > $F^-$. La carica negativa su $I^-$ (Ioduro) è "spalmata" su una nuvola elettronica molto più grande (maggiore polarizzabilità) rispetto a $F^-$, risultando più stabile.
    * Acidità: **$HI > HBr > HCl > HF$**

### 3. Effetto Induttivo ($I$)

Gli [[Reazioni Organiche ed Effetti Elettronici#1. Effetto Induttivo ($I$)|effetti induttivi]] modificano l'acidità stabilizzando o destabilizzando la base coniugata.

* **Effetto $-I$ (Elettron-Attrattori):** Gruppi come gli alogeni, $-NO_2$, $-OH$ *stabilizzano* la base coniugata $A^-$ attirando densità elettronica e disperdendo la carica negativa.
    * **AUMENTANO l'acidità** (abbassano il $pK_a$).
    * **Esempio:** Acidi Carbossilici Sostituiti.
        * Acido Acetico ($CH_3COOH$): $pK_a \approx 4.75$
        * Acido Cloroacetico ($Cl-CH_2COOH$): $pK_a \approx 2.86$ (il $Cl$ con effetto $-I$ stabilizza l'anione $Cl-CH_2COO^-$).
        * Acido Tricloroacetico ($Cl_3C-COOH$): $pK_a \approx 0.65$ (effetto $-I$ molto forte).

* **Effetto $+I$ (Elettron-Donatori):** Gruppi come gli alchilici ($R$) *destabilizzano* la base coniugata $A^-$ "spingendo" altra densità elettronica sulla carica negativa già presente.
    * **DIMINUISCONO l'acidità** (alzano il $pK_a$).
    * **Esempio:** Alcoli.
        * Metanolo ($CH_3OH$): $pK_a \approx 15.5$
        * Etanolo ($CH_3CH_2OH$): $pK_a \approx 15.9$
        * *tert*-Butanolo ($(CH_3)_3COH$): $pK_a \approx 18$ (i tre gruppi metilici $+I$ destabilizzano fortemente l'anione alcossido).

### 4. Risonanza (Effetto Mesomero, $M$)

La delocalizzazione della carica negativa sulla base coniugata tramite [[Reazioni Organiche ed Effetti Elettronici#2. Effetto Mesomero (o Risonanza, $M$)|risonanza]] è un potentissimo fattore stabilizzante.

* **AUMENTA drasticamente l'acidità.**
* **Esempio 1: Alcol vs Acido Carbossilico**
    * Etanolo ($CH_3CH_2OH$), $pK_a \approx 16$.
    * Base coniugata: $CH_3CH_2O^-$ (anione Etossido). La carica $^-$ è **localizzata** sull'ossigeno.
    * Acido Acetico ($CH_3COOH$), $pK_a \approx 4.75$.
    * Base coniugata: $CH_3COO^-$ (anione Acetato). La carica $^-$ è **delocalizzata** per risonanza sui due atomi di ossigeno. L'anione è *molto* più stabile.

* **Esempio 2: Alcol vs Fenolo**
    * Cicloesanolo (alcol), $pK_a \approx 18$.
    * Base coniugata: Anione Cicloesilossido (carica localizzata su $O$).
    * Fenolo (anello aromatico + $OH$), $pK_a \approx 10$.
    * Base coniugata: Anione Fenato (o Fenossido). La carica $^-$ sull'ossigeno è **delocalizzata** nell'anello aromatico (effetto $+M$ del gruppo $-O^-$) su 4 atomi (l'$O$ e i carboni in *orto* e *para*).

### 5. Ibridazione

Maggiore è il **carattere $s$** dell'orbitale ibrido che ospita il doppietto elettronico nella base coniugata, più gli elettroni sono vicini al nucleo (e quindi stabilizzati).

* **Carattere $s$:**
    * [[Proprietà e ibridazione del carbonio. I gruppi funzionali. Rappresentazione dei composti carboniosi.#Ibridazione $sp$ (Lineare)|Ibridazione $sp$]]: 50% $s$
    * [[Proprietà e ibridazione del carbonio. I gruppi funzionali. Rappresentazione dei composti carboniosi.#Ibridazione $sp^2$ (Trigonale Planare)|Ibridazione $sp^2$]]: 33% $s$
    * [[Proprietà e ibridazione del carbonio. I gruppi funzionali. Rappresentazione dei composti carboniosi.#Ibridazione $sp^3$ (Tetraedrica)|Ibridazione $sp^3$]]: 25% $s$

* **Stabilità base coniugata (carboanione):** $sp > sp^2 > sp^3$
* **Acidità del legame $C-H$:**
    * Alc**hini** (es. Acetilene, $sp$): $pK_a \approx 25$ (relativamente acido)
    * Alc**heni** (es. Etene, $sp^2$): $pK_a \approx 44$
    * Alc**ani** (es. Etano, $sp^3$): $pK_a \approx 50$ (praticamente non acido)

---

## Forza delle Basi

La forza di una base è l'inverso della forza del suo acido coniugato.

* Una **base forte** (es. $OH^-$) ha un acido coniugato **molto debole** (es. $H_2O$, $pK_a \approx 15.7$).
* Una **base debole** (es. $Cl^-$) ha un acido coniugato **molto forte** (es. $HCl$, $pK_a < 0$).

**Basi Organiche Comuni: Ammine**
Le ammine ($R-NH_2$) sono le basi organiche più comuni. La loro basicità dipende dalla disponibilità del *lone pair* sull'azoto ($N$) per accettare un $H^+$.

* **Ammine Alifatiche** (es. $CH_3NH_2$): Sono più basiche dell'ammoniaca ($NH_3$) grazie all'effetto [[Reazioni Organiche ed Effetti Elettronici#1. Effetto Induttivo ($I$)|elettron-donatore ($+I$)]] dei gruppi alchilici, che "spingono" elettroni sull'azoto, rendendo il *lone pair* più disponibile.
* **Ammine Aromatiche** (es. Anilina, $C_6H_5NH_2$): Sono *molto meno* basiche. Il *lone pair* dell'azoto è delocalizzato nell'anello aromatico per [[Reazioni Organiche ed Effetti Elettronici#2. Effetto Mesomero (o Risonanza, $M$)|risonanza ($+M$)]] ed è quindi meno disponibile per legare un $H^+$.