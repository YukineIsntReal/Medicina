# Il Controllo dell'Espressione Genica negli Eucarioti

Negli [[Eucarioti]], l'espressione genica è regolata a molteplici livelli, dal [[DNA]] impacchettato nella [[Cromatina]] fino alla degradazione della proteina finale. Questo controllo multistadio permette alla cellula di rispondere in modo fine e specifico a segnali interni ed esterni, ed è alla base del differenziamento cellulare.

I principali livelli di controllo sono:
1.  Controllo Trascrizionale (nel nucleo)
2.  Controllo Post-Trascrizionale (nel nucleo e nel citoplasma)
3.  Controllo Traduzionale (nel citoplasma)
4.  Controllo Post-Traduzionale (nel citoplasma e in altri compartimenti)

## 1. Controllo Trascrizionale

È il livello di controllo più importante e più finemente regolato. Determina **se** e **quanto** un [[gene]] viene trascritto in [[RNA]].

### A. Accessibilità della Cromatina (Controllo Epigenetico)
Prima che un gene possa essere trascritto, la [[RNA Polimerasi]] e i [[Fattori di Trascrizione]] devono accedere fisicamente al promotore.
* **[[Eterocromatina]]**: (Condensata) Trascrizionalmente silente.
* **[[Eucromatina]]**: (Rilassata) Trascrizionalmente attiva.

Questo passaggio è regolato da:
1.  **Modificazioni degli Istoni**: Le code N-terminali degli istoni vengono modificate (PTM).
    * **Acetilazione** (da parte delle **HAT** - Istone Acetiltransferasi): Neutralizza la carica positiva delle lisine, rilassa la cromatina (eucromatina) $\to$ **Attivazione**.
    * **Deacetilazione** (da parte delle **HDAC** - Istone Deacetilasi): Rimuove l'acetilazione, compatta la cromatina (eterocromatina) $\to$ **Repressione**.
    * **Metilazione**: Può attivare o reprimere a seconda del residuo (es. $H3K9me3$ $\to$ Repressione; $H3K4me3$ $\to$ Attivazione).
2.  **Metilazione del DNA**: La metilazione delle citosine nelle isole CpG (vedi [[Metilazione del DNA]]) nei promotori è quasi sempre associata al silenziamento genico a lungo termine.
3.  **Complessi di Rimodellamento della Cromatina**: (es. $SWI/SNF$) Usano ATP per far scivolare o espellere i [[nucleosomi]], esponendo il DNA ai fattori di trascrizione.



### B. Regolazione da parte di Fattori di Trascrizione
Una volta che il DNA è accessibile, l'inizio della trascrizione è controllato da proteine chiamate **[[Fattori di Trascrizione]]** (TF).
* **TF Generali (Basali)**: Si legano al *core promoter* (es. TATA box) e sono necessari per reclutare la [[RNA Polimerasi II]]. Permettono un livello *basale* di trascrizione.
* **TF Specifici (Attivatori e Repressori)**: Si legano a elementi regolativi *in cis* per modulare finemente il tasso di trascrizione.
    * **[[Enhancer]] (Intensificatori)**: Siti distanti (anche migliaia di $bp$) che legano *Attivatori*. Tramite il ripiegamento del DNA (looping), interagiscono con il complesso basale al promotore per **aumentare** la trascrizione.
    * **[[Silencer]] (Silenziatori)**: Siti che legano *Repressori* per **diminuire** o bloccare la trascrizione.

La combinazione unica di TF specifici presenti in un dato tipo cellulare (il "codice" di fattori) determina quali geni vengono attivati o spenti, portando al differenziamento.

## 2. Controllo Post-Trascrizionale

Una volta che il gene è stato trascritto nel **pre-mRNA** (trascritto primario), questo deve essere processato prima di diventare un mRNA maturo e funzionale.

### A. Maturazione dell'mRNA (nel Nucleo)
* **Capping $5'$**: Aggiunta di un cappuccio (7-metilguanosina) all'estremità $5'$. È essenziale per la stabilità dell'mRNA e per il riconoscimento da parte del [[ribosoma]].
* **Poliadenilazione $3'$**: Aggiunta di una coda di Poli-A (decine/centinaia di adenine) all'estremità $3'$. È cruciale per la stabilità e per l'esportazione dal nucleo.
* **[[Splicing]]**: Rimozione degli [[introni]] (non codificanti) e unione degli [[esoni]] (codificanti).

### B. Splicing Alternativo (La chiave della complessità)
Questo è un meccanismo di controllo cruciale. Un singolo gene (un singolo pre-mRNA) può essere "tagliato e cucito" (spliced) in modi diversi, includendo o escludendo specifici esoni.
**Risultato**: Da un singolo gene, la cellula può produrre **diverse isoforme proteiche**, spesso con funzioni diverse o localizzazioni cellulari differenti. Questo aumenta enormemente la capacità codificante del genoma.

### C. Controllo della Stabilità dell'mRNA (nel Citoplasma)
La "vita media" di un mRNA nel citoplasma determina quante proteine possono essere tradotte da esso.
* Le sequenze nella regione $3'-UTR$ dell'mRNA (spesso) reclutano proteine che ne promuovono la degradazione (rimozione della coda di Poli-A e del cappuccio).

### D. RNA Interference (RNAi)
Un meccanismo di silenziamento genico post-trascrizionale altamente specifico mediato da piccoli RNA non codificanti.
* **[[miRNA]] (microRNA)**: Piccoli RNA (circa $22$ nucleotidi) che si legano a mRNA bersaglio (spesso nel $3'-UTR$).
* Questo legame recluta il complesso **RISC** (RNA-Induced Silencing Complex).
* **Risultato**: Se l'appaiamento è perfetto, RISC taglia l'mRNA (degradazione). Se è imperfetto (più comune nell'uomo), RISC blocca la traduzione (controllo traduzionale).



## 3. Controllo Traduzionale

Determina **se**, **quando** e **quanto** un mRNA maturo (presente nel citoplasma) viene effettivamente tradotto in proteina dai ribosomi.

* **Controllo dell'Inizio**: È il punto di controllo principale. La traduzione spesso richiede **Fattori di Inizio Eucariotici** ($eIFs$).
    * *Esempio*: In condizioni di stress (es. carenza di nutrienti), la cellula può **fosforilare** il fattore $eIF2$. Questo blocca l'inizio della traduzione per la maggior parte degli mRNA, conservando energia.
* **Repressori Traduzionali**: Proteine che si legano all'mRNA (spesso nelle UTR) e impediscono fisicamente al ribosoma di assemblarsi o avanzare.
    * *Esempio*: La sintesi della **Ferritina** (che immagazzina ferro) è controllata a livello traduzionale. In *assenza* di ferro, la proteina IRP si lega all'mRNA della ferritina ($5'-UTR$) e ne blocca la traduzione. In *presenza* di ferro, il ferro si lega a IRP, che si stacca, permettendo la sintesi di ferritina per immagazzinare l'eccesso di ferro.

## 4. Controllo Post-Traduzionale

La proteina è stata sintetizzata, ma non è necessariamente attiva o stabile.

* **Modificazioni Post-Traduzionali (PTM)**: La proteina viene modificata chimicamente per alterarne la funzione, localizzazione o stabilità.
    * **Fosforilazione**: (Chinasi/Fosfatasi) Agisce come un interruttore on/off (es. cascate di segnale).
    * **Glicosilazione**: Aggiunta di zuccheri (importante per proteine di membrana o secrete).
    * ...e molte altre (Acetilazione, Metilazione, etc.).
* **Folding (Ripiegamento)**: Le proteine devono assumere la loro corretta struttura 3D per essere funzionali, spesso aiutate da [[Chaperonine]].
* **Attivazione Proteolitica**: Alcune proteine (es. enzimi digestivi, ormoni come l'insulina) sono sintetizzate come precursori inattivi (es. *Proinsulina*) e devono essere "tagliate" (clivaggio) per diventare attive.
* **Degradazione (Turnover Proteico)**: La concentrazione di una proteina dipende anche dalla sua velocità di degradazione.
    * **[[Ubiquitina]]**: Una piccola proteina che agisce come "etichetta della morte".
    * La poli-ubiquitinazione (l'aggiunta di una catena di ubiquitine) indirizza la proteina al **[[Proteasoma]]**, un complesso macromolecolare che la degrada (riciclando gli amminoacidi).