Nel precedente capitolo abbiamo visto gli **Isomeri Configurazionali**, molecole che non possono essere interconvertite senza rompere legami. La classe più importante di questi isomeri è quella degli **Isomeri Ottici**.

## Chiralità e Centri Chirali

* **Molecola Chirale:** Una molecola che **non è sovrapponibile** alla sua immagine speculare. Le due immagini speculari non sovrapponibili sono chiamate **Enantiomeri**. (Es. le nostre mani destra e sinistra).
* **Molecola Achirale:** Una molecola che *è sovrapponibile* alla sua immagine speculare (spesso perché possiede un piano di simmetria interno).
* **Centro Chirale (o Stereocentro):** La causa più comune di chiralità. È un atomo di carbonio ibridato $sp^3$ legato a **quattro sostituenti diversi** tra loro.



Gli enantiomeri hanno proprietà fisiche identiche (punti di fusione, ebollizione, solubilità) *tranne* per una: il modo in cui interagiscono con la luce polarizzata.

---

## Attività Ottica e Potere Rotatorio

### 1. Luce Polarizzata e Polarimetro
La luce normale vibra in tutti i piani. Un filtro polarizzatore la fa passare solo su un piano: questa è la **luce polarizzata piana**.
Un **polarimetro** è uno strumento che fa passare la luce polarizzata piana attraverso un campione.

### 2. Sostanze Otticamente Attive
* Le molecole **achirali** *non* interagiscono con la luce polarizzata; il piano non ruota. Sono otticamente inattive.
* Le molecole **chirali** (gli enantiomeri) sono **otticamente attive**: ruotano il piano della luce polarizzata.
    * Un enantiomero ruoterà la luce di un certo angolo $x$.
    * Il suo enantiomero speculare ruoterà la luce *esattamente* dello stesso angolo $x$, ma nella direzione opposta ($-x$).

### 3. Convenzione Destrogira ($+$) / Levogira ($-$)
Questa convenzione descrive la *direzione* della rotazione misurata sperimentalmente:
* **Destrogiro (d) o ($+$):** L'isomero ruota il piano della luce verso **destra** (senso orario).
* **Levogiro (l) o ($-$)**: L'isomero ruota il piano della luce verso **sinistra** (senso antiorario).

* **Miscela Racemica (o Racemo):** Una miscela 50:50 dei due enantiomeri ($+$ e $-$). È otticamente **inattiva** ($0^\circ$), perché le due rotazioni opposte si annullano a vicenda.

### 4. Potere Ottico Rotatorio Specifico $[\alpha]$
La rotazione osservata ($\alpha$) dipende dalla concentrazione e dalla lunghezza del tubo del polarimetro. Per standardizzare questa misura, si definisce il **Potere Ottico Rotatorio Specifico**, $[\alpha]$, che è una costante fisica caratteristica di una molecola chirale (come un punto di fusione).

La formula è:
$$[\alpha]^T_\lambda = \frac{\alpha}{l \cdot c}$$

Dove:
* $[\alpha]$ = Potere rotatorio specifico.
* $\alpha$ = Rotazione osservata in gradi.
* $l$ = Lunghezza del cammino ottico (del tubo portacampione) in **decimetri ($dm$)**.
* $c$ = Concentrazione del campione in **grammi per millilitro ($g/mL$)**.
* $T$ = Temperatura (solitamente $20^\circ C$).
* $\lambda$ = Lunghezza d'onda della luce (solitamente la linea D del Sodio, $589 \text{ nm}$).

---

## Convenzione di Fischer e Configurazione D/L

L'attività ottica ($+/-$) ci dice *come* la molecola ruota la luce, ma non ci dice nulla della sua *struttura* 3D (quale è la "destra" e quale la "sinistra" strutturale).

Negli anni '50, Emil Fischer sviluppò un metodo per rappresentare le molecole chirali (soprattutto i carboidrati) in 2D.

### Proiezioni di Fischer
* **Regola:** Si disegna una croce.
    * Il carbonio chirale è al centro.
    * Le **linee orizzontali** rappresentano i legami che **vengono verso l'osservatore** (cunei pieni).
    * Le **linee verticali** rappresentano i legami che **si allontanano dall'osservatore** (tratteggiati).

### Convenzione D/L (Configurazione Relativa)
Fischer usò la **Gliceraldeide** (l'aldoso chirale più semplice) come molecola standard per definire una **configurazione relativa**.


* **Standard (Gliceraldeide):**
    * Si posiziona il carbonio più ossidato (l'aldeide, $-CHO$) in alto.
    * Si guarda l'unico centro chirale ($C-2$).
    * Se l'ossidrile ($-OH$) è a **destra**, la molecola è chiamata **D-Gliceraldeide**.
    * Se l'ossidrile ($-OH$) è a **sinistra**, la molecola è chiamata **L-Gliceraldeide**.

Questa convenzione (D/L) è stata poi estesa a tutti i carboidrati e agli amminoacidi per analogia strutturale.
* **Per gli Zuccheri:** Si guarda il centro chirale *più lontano* dal gruppo carbonilico. Se l' $-OH$ è a destra, è un D-zucchero.
* **Per gli Amminoacidi:** Si guarda il centro chirale $\alpha$. Se il gruppo amminico ($-NH_2$) è a sinistra, è un L-amminoacido.

---

## Attenzione: D/L $\neq$ d/l (ovvero $\pm$)

Questo è il punto più importante da non confondere:
* **D e L (Convenzione di Fischer):** Indicano la **Configurazione Relativa**. È un nome che assegniamo alla struttura (all'arrangiamento 3D) basandoci sulla sua somiglianza con la Gliceraldeide. È una convenzione, si legge "sul foglio".
* **d e l (o $+$ e $-$):** Indicano l'**Attività Ottica**. È una **proprietà fisica misurata sperimentalmente** con un polarimetro.

**Non c'è una correlazione diretta!**

* La **D-Gliceraldeide** (configurazione D) è *casualmente* anche **destrogira ($+$)**.
* L'**Acido D-Lattico** (configurazione D) è **levogiro ($-$)**.
* Quasi tutti gli **L-Amminoacidi** (configurazione L) sono, *casualmente*, **levogiri ($-$)** (ma L-Cisteina è destra).

In biochimica:
* Quasi tutti gli zuccheri naturali sono della serie **D** (es. D-Glucosio, D-Fruttosio).
* Quasi tutti gli amminoacidi naturali (tranne la Glicina, achirale) sono della serie **L** (es. L-Alanina, L-Leucina).