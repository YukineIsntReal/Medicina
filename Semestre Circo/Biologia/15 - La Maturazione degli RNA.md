Nei [[Procarioti]], l'[[mRNA]] viene tradotto in proteina non appena viene trascritto (processi accoppiati). Negli [[Eucarioti]], il trascritto primario (chiamato **pre-mRNA** o *hnRNA*, RNA eterogeneo nucleare) deve subire una serie di modifiche complesse all'interno del nucleo prima di poter essere esportato nel citoplasma e tradotto. Questo processo è noto come **Maturazione (o Processamento) dell'RNA**.

Questi passaggi sono fondamentali per la stabilità, il trasporto e la corretta traduzione dell'mRNA.

## 1. Il Capping (Incappucciamento) al $5'$

Non appena la [[RNA Polimerasi II]] ha sintetizzato i primi $\approx 20-30$ nucleotidi del pre-mRNA, l'estremità $5'$ viene modificata.
* **Processo**: Viene aggiunto un nucleotide modificato, una **7-metilguanosina ($m^7G$)**.
* **Legame**: Questo cappuccio è legato al primo nucleotide del trascritto attraverso un legame atipico **$5' \to 5'$ trifosfato**.
* **Funzioni**:
    1.  **Stabilità**: Protegge l'mRNA dalla degradazione da parte di esonucleasi $5' \to 3'$.
    2.  **Trasporto**: Agisce come segnale per l'esportazione dal nucleo.
    3.  **Traduzione**: È essenziale per il riconoscimento da parte del [[ribosoma]] (complesso di inizio della traduzione) nel citoplasma.

## 2. La Poliadenilazione al $3'$

Questo processo segna la fine della trascrizione per la Pol II e aggiunge una coda all'estremità $3'$.
* **Processo**:
    1.  L'RNA Pol II trascrive un **segnale di poliadenilazione** ($AAUAAA$) sul pre-mRNA.
    2.  Un complesso enzimatico (endonucleasi) riconosce questo segnale e taglia l'RNA $\approx 10-30$ nucleotidi *a valle* di esso.
    3.  Un altro enzima, la **Poli-A Polimerasi (PAP)**, aggiunge (senza bisogno di uno stampo) una lunga catena di $\approx 50-250$ residui di Adenina, formando la **Coda di Poli-A**.
* **Funzioni**:
    1.  **Stabilità**: Protegge l'mRNA dalla degradazione da parte di esonucleasi $3' \to 5'$. La sua lunghezza è un "timer" per la vita media dell'mRNA.
    2.  **Trasporto**: Facilita l'esportazione dal nucleo.
    3.  **Traduzione**: Promuove l'efficienza della traduzione interagendo (tramite proteine leganti) con il cappuccio $5'$.

## 3. Lo Splicing (Rimozione degli Introni)

I geni eucariotici sono "interrotti": contengono sequenze codificanti (**[[Esoni]]**) intervallate da sequenze non codificanti (**[[Introni]]**). Lo splicing è il processo che rimuove gli introni e "cuce" (liga) gli esoni in una sequenza codificante continua (CDS).

### Lo Spliceosoma e gli snRNA
Lo splicing della maggior parte dei pre-mRNA è catalizzato da un enorme e dinamico complesso macromolecolare chiamato **[[Spliceosoma]]**.
* **Composizione**: È composto da circa $50-100$ proteine e $5$ piccoli RNA nucleari (**[[snRNA]]** - *small nuclear RNA*): $U1, U2, U4, U5, U6$.
* **snRNPs**: Gli snRNA non sono liberi, ma complessati con proteine a formare le **snRNP** (small nuclear ribonucleoproteins, "snurps").
* **Meccanismo**:
    1.  Le snRNP riconoscono le sequenze consenso ai confini esone-introne (i *siti di splicing* $5'$ e $3'$) e un **punto di ramificazione** (un'Adenina, $A$) all'interno dell'introne.
    2.  $U1$ lega il sito $5'$, $U2$ lega il punto di ramificazione.
    3.  $U4, U5, U6$ si uniscono per formare lo spliceosoma attivo, che porta i siti di reazione vicini.
    4.  Avvengono due **reazioni di transesterificazione** (trasferimento di legami fosfodiesterici):
        * **1° Reazione**: L'ossidrile $2'-OH$ dell'Adenina del punto di ramificazione attacca il sito di splicing $5'$. L'introne forma una struttura a cappio ( **lariat**).
        * **2° Reazione**: L'ossidrile $3'-OH$ (ora libero) del primo esone attacca il sito di splicing $3'$.
    5.  **Risultato**: I due esoni vengono uniti e l'introne viene rilasciato come lariat, per poi essere degradato.



### I Ribozimi e lo Splicing Autocatalitico
Non tutto lo splicing richiede lo spliceosoma. Esistono RNA (principalmente in organismi inferiori o negli organelli) che possono catalizzare il proprio splicing.
* **[[Ribozimi]]**: Sono molecole di RNA con attività catalitica (enzimi a RNA).
* **Introni Autocatalitici** (es. Gruppo I e II): L'RNA intronico stesso si ripiega in una struttura 3D complessa che catalizza le reazioni di transesterificazione per la propria rimozione. Questa scoperta ha supportato l'ipotesi del "Mondo a RNA" (RNA World Hypothesis).

## 4. Lo Splicing Alternativo

Questo è un meccanismo fondamentale di [[Regolazione Genica]]. Un singolo pre-mRNA contenente più esoni può essere processato in modi diversi.
* **Processo**: A seconda del tipo cellulare o dello stimolo, specifici *fattori di splicing* (proteine) possono legarsi all'RNA e "mascherare" o "promuovere" l'uso di certi siti di splicing.
* **Risultato**: Vengono inclusi o esclusi differenti esoni, generando dalla **stessa [[gene]]** diverse isoforme di mRNA maturo, che a loro volta codificheranno per **diverse [[Proteine]]** (isoforme proteiche), spesso con funzioni o localizzazioni distinte. È uno dei motivi principali della complessità eucariotica.

## 5. Editing dell'RNA

È un processo (meno comune dello splicing) in cui la sequenza dell'RNA viene *chimicamente modificata* dopo la trascrizione, cambiando l'informazione codificante rispetto a quella del DNA.
* **Tipo 1: Sostituzione di base**: (Es. Deaminazione)
    * **Esempio Classico ($C \to U$)**: Il gene per l'Apolipoproteina B ($ApoB$) nell'uomo.
        * *Fegato*: L'mRNA non è editato. Viene tradotto il codone $CAA$ (Glutammina) $\to$ Proteina $ApoB-100$ (lunga).
        * *Intestino*: Una deaminasi *edita* la $C$ in $U$. Il codone $CAA$ diventa $UAA$ (un **codone di stop**). $\to$ Proteina $ApoB-48$ (corta), con una diversa funzione nel trasporto dei lipidi.
* **Tipo 2: Inserzione/Delezione**: (Es. nei Tripanosomi, guidato da *guide RNA*).

## 6. La Regolazione della Stabilità del Messaggero (Turnover)

La quantità di proteina prodotta non dipende solo dalla trascrizione, ma anche da quanto *a lungo* l'mRNA sopravvive nel citoplasma.

### Deadenilazione e Decapucciamento
La via di degradazione principale (turnover) dell'mRNA:
1.  **Deadenilazione**: La Coda di Poli-A $3'$ viene lentamente "mangiata" (accorciata) da enzimi chiamati *deadenilasi*.
2.  Quando la coda è sufficientemente corta, l'mRNA è destabilizzato.
3.  **Decapucciamento (Decapping)**: Il cappuccio $5'$ ($m^7G$) viene rimosso da un *decapping enzyme*.
4.  L'mRNA (ora esposto ad entrambe le estremità) viene rapidamente degradato da esonucleasi ($5' \to 3'$ e $3' \to 5'$ dall'esosoma).

### miRNA e RNA Interference (RNAi)
Questa è una via di *regolazione specifica* e di silenziamento genico.
* **[[miRNA]] (microRNA)**: Sono piccoli RNA non codificanti (circa $22$ nucleotidi) che la cellula produce per regolare interi set di geni.
* **Processo**:
    1.  Un miRNA maturo (a singolo filamento) viene caricato nel complesso **RISC** (RNA-Induced Silencing Complex).
    2.  Il miRNA (in RISC) agisce da "guida" e si appaia (spesso in modo imperfetto) a sequenze complementari, tipicamente localizzate nella regione **$3'-UTR$** (regione non tradotta) degli mRNA bersaglio.
* **Risultato**:
    1.  **Repressione della Traduzione**: Il legame di RISC impedisce al ribosoma di tradurre l'mRNA.
    2.  **Degradazione accelerata**: RISC recluta anche gli enzimi di deadenilazione, portando alla rapida distruzione dell'mRNA.