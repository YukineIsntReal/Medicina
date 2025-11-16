Dopo aver distinto gli Enantiomeri (immagini speculari non sovrapponibili), dobbiamo classificare tutti gli altri rapporti stereoisomerici e imparare a dare un nome univoco alla configurazione 3D.

## 1. Classificazione degli Stereoisomeri Configurazionali

### Diastereoisomeri
Sono **stereoisomeri che *non* sono immagini speculari l'uno dell'altro**.

* **Definizione:** Questa è una definizione "per esclusione". Se due molecole sono stereoisomeri ma non sono enantiomeri, sono diastereoisomeri.
* **Caratteristiche:** Si verifica in molecole con **due o più centri chirali**.
* **Proprietà:** A differenza degli enantiomeri (che hanno proprietà fisiche identiche), i diastereoisomeri hanno **proprietà chimico-fisiche diverse** (punti di fusione, ebollizione, solubilità, reattività) e possono essere separati con tecniche chimiche standard (es. cromatografia).
* **Esempio:** L'acido (2R, 3R)-Tartarico e l'acido (2R, 3S)-Tartarico sono diastereoisomeri.

### Epimeri
Sono **diastereoisomeri che differiscono per la configurazione di *un solo* centro chirale**, in una molecola che ne contiene molteplici.

* **Definizione:** È una sottoclasse specifica di diastereoisomeri.
* **Rilevanza:** È un termine usato quasi esclusivamente nella **chimica dei carboidrati**.
* **Esempio:**
    * Il **D-Glucosio** e il **D-Mannosio** sono *Epimeri al C-2*.
    * Il **D-Glucosio** e il **D-Galattosio** sono *Epimeri al C-4*.
    * (Nota: D-Mannosio e D-Galattosio sono diastereoisomeri, ma *non* epimeri, perché differiscono a due centri, C-2 e C-4).

### Anomeri
Sono una sottoclasse di **epimeri** che si forma specificamente durante la **ciclizzazione degli zuccheri**.

* **Definizione:** Gli anomeri differiscono per la configurazione del **carbonio anomerico**.
* **Carbonio Anomerico:** È il carbonio che *era* il carbonile (aldeidico o chetonico) nella forma lineare e che *diventa* un nuovo centro chirale (il carbonio emiacetalico) nella forma ciclica.
* **Nomenclatura ($\alpha$ e $\beta$):**
    * **$\alpha$ (alfa):** Nelle proiezioni di Haworth, l'ossidrile ($-OH$) sul carbonio anomerico è in posizione *trans* (lato opposto) rispetto al gruppo $-CH_2OH$ (al C-5 per gli aldoesosi).
    * **$\beta$ (beta):** L'ossidrile ($-OH$) sul carbonio anomerico è in posizione *cis* (stesso lato) rispetto al gruppo $-CH_2OH$.
* **Esempio:** $\alpha$-D-Glucosio e $\beta$-D-Glucosio sono anomeri.



---

## 2. Composti Speciali e Miscele

### Composti Meso
È un composto **achirale** (non otticamente attivo) che tuttavia **possiede centri chirali**.

* **Definizione:** È un'eccezione alla regola "centro chirale = molecola chirale".
* **Caratteristiche:** Un composto meso ha una struttura tale (di solito 2 centri chirali con sostituenti identici) da possedere un **piano di simmetria interno** che rende la molecola sovrapponibile alla sua immagine speculare.
* **Esempio:** L'acido **meso-tartarico** (acido (2R, 3S)-tartarico). Ha due centri chirali (C2 e C3), ma un piano di simmetria taglia la molecola a metà. È achirale e otticamente inattivo. È un diastereoisomero delle forme D-(-) e L-(+) dell'acido tartarico.

### Miscela Racemica (o Racemo)
È una **miscela equimolare (50:50) di due enantiomeri** ($+$ e $-$).

* **Proprietà:** Una miscela racemica è sempre **otticamente inattiva** ($[\alpha] = 0$). La rotazione destrogira di una molecola è perfettamente annullata dalla rotazione levogira del suo enantiomero.
* **Nomenclatura:** Si indica con il prefisso **($\pm$)** o **(d,l)-**. Esempio: ($\pm$)-Ibuprofene.
* **Formazione:** Molte reazioni chimiche di sintesi che creano un centro chirale a partire da reagenti achirali producono sempre una miscela racemica, poiché l'attacco del reagente da "sopra" o da "sotto" è statisticamente identico.

---

## 3. Nomenclatura Assoluta (Regole CIP)

Per superare l'ambiguità della convenzione D/L (che è relativa) e d/l (che è sperimentale), è stato creato un sistema universale per descrivere la configurazione 3D assoluta: il **Sistema Cahn-Ingold-Prelog (CIP)**.

### Le Regole di Priorità (Cahn-Ingold-Prelog)
Il sistema si basa sull'assegnare una **priorità** (1=massima, 4=minima) ai quattro sostituenti legati a un centro chirale o a un doppio legame.

1.  **Numero Atomico:** La priorità più alta va all'atomo con **numero atomico (Z) maggiore** direttamente legato al centro.
    * Esempio: $-I > -Br > -Cl > -S > -F > -O > -N > -C > -H$.
2.  **Parità (Atomi Uguali):** Se due atomi sono identici, si passa lungo la catena al "primo punto di differenza".
    * Esempio: $-CH_2CH_3$ (Etile) ha priorità su $-CH_3$ (Metile). Perché?
        * Entrambi legano un $C$. Si guarda cosa legano questi $C$.
        * Metile: $(H, H, H)$.
        * Etile: $(C, H, H)$.
        * $C$ batte $H$, quindi l'Etile vince.
3.  **Legami Multipli:** Sono trattati come se fossero legati a più atomi singoli.
    * $C=O$ (Carbonile) $\rightarrow$ il $C$ è trattato come legato a *due* $O$.
    * $C=C$ $\rightarrow$ ogni $C$ è trattato come legato a *due* $C$.

### Convenzione E/Z (per Isomeria Geometrica)
Sostituisce la vecchia nomenclatura *cis/trans*, che fallisce se i sostituenti sono tutti diversi. Si applica ai doppi legami $C=C$.

1.  Si assegnano le priorità (1 e 2) ai due sostituenti *su ciascun carbonio* del doppio legame.
2.  Si osserva la posizione dei due gruppi a **priorità 1**:
    * **Z (Zusammen = Insieme):** I due gruppi a priorità 1 sono dallo *stesso lato* del doppio legame.
    * **E (Entgegen = Opposto):** I due gruppi a priorità 1 sono da *lati opposti*.



### Convenzione R/S (per Centri Chirali)
Assegna un nome univoco (R o S) a un centro chirale.

1.  **Assegnare le Priorità:** Si assegnano le priorità da 1 (max) a 4 (min) ai quattro sostituenti del centro chirale.
2.  **Orientare la Molecola:** Si orienta mentalmente la molecola in modo che il gruppo a **priorità 4 (minima)** sia rivolto **lontano dall'osservatore** (sul retro).
3.  **Tracciare l'Arco:** Si traccia un arco che va dal gruppo 1 $\rightarrow$ 2 $\rightarrow$ 3.
    * **R (Rectus = Destra):** L'arco va in senso **orario**.
    * **S (Sinister = Sinistra):** L'arco va in senso **antiorario**.

*Trucco Veloce (se 4 è davanti):* Se il gruppo 4 è rivolto *verso* l'osservatore (cuneo pieno), si determina il senso (orario o antiorario) e poi si **inverte il risultato** (Es. se sembra R, in realtà è S).