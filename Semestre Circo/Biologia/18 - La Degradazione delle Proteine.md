Il turnover proteico è essenziale per l'omeostasi cellulare. La via di degradazione principale per le proteine regolatorie a breve emivita e per quelle danneggiate/misfolded è il **Sistema Ubiquitina-Proteasoma** (UPS).

Questo sistema si basa su due componenti chiave:
1.  **L'Ubiquitina**: Una piccola proteina (76 amminoacidi) altamente conservata, che agisce come una "etichetta" (un *tag*) per la degradazione.
2.  **Il Proteasoma**: Un enorme complesso proteolitico (un "trita-documenti" molecolare) che riconosce le proteine etichettate e le distrugge.

## Degradazione Proteasomica Ubiquitina-Dipendente

Il processo non è un singolo passaggio, ma una cascata enzimatica precisa (e che richiede ATP) per "etichettare" (ubiquitinare) il substrato.

### La Cascata dell'Ubiquitinazione
L'aggiunta di ubiquitina (Ub) a una proteina bersaglio (spesso su un residuo di Lisina, $K$) richiede tre enzimi:

1.  **E1 (Enzima Attivante l'Ubiquitina)**:
    * Utilizza [[ATP]] per adenilare una molecola di Ub.
    * Trasferisce l'Ub su un proprio residuo di Cisteina, formando un legame tioestere ad alta energia. ( $Ub + E1 + ATP \to E1-S \sim Ub$ )

2.  **E2 (Enzima Coniugante l'Ubiquitina)**:
    * L'Ub attivata viene trasferita da E1 a un residuo di Cisteina sull'enzima E2. ( $E1-S \sim Ub + E2 \to E2-S \sim Ub + E1$ )
    * Esistono diverse varianti di E2, che iniziano a conferire specificità.

3.  **E3 (Ubiquitina Ligasi)**:
    * Questo è l'enzima chiave per la **specificità**.
    * Esistono centinaia di E3 ligasi diverse nella cellula, ognuna capace di riconoscere uno specifico substrato (o un set di substrati) da degradare (spesso riconoscono segnali di degradazione, *degrons*, sulla proteina bersaglio).
    * La E3 ligasi agisce come un "ponte": lega contemporaneamente l'E2 (carico di Ub) e la proteina substrato.
    * Catalizza il trasferimento finale dell'Ub dalla E2 alla Lisina ($K$) della proteina substrato.

### La Poli-ubiquitinazione
Una singola molecola di Ub (mono-ubiquitinazione) *non* è un segnale di degradazione (è spesso un segnale regolativo, es. per il trafficking).

Per indirizzare una proteina al proteasoma, è necessaria una **catena di poli-ubiquitina**.
* Le E3 ligasi (spesso con l'aiuto di fattori E4) aggiungono molecole di Ub successive, non solo al substrato, ma *sull'ubiquitina* precedentemente attaccata.
* L'ubiquitina stessa ha diverse Lisine. Il segnale "canonico" per la degradazione è una catena (di almeno $4$ Ub) legata tramite la **Lisina $48$ ($K48$)** dell'ubiquitina precedente.
* (Altre catene, es. $K63$, servono per segnali non degradativi come la riparazione del DNA).

### Il Proteasoma
Una volta che la proteina è etichettata con la catena $K48-poliUb$, viene riconosciuta dal **Proteasoma $26S$**.
* **Struttura**: È un complesso cilindrico formato da:
    * **Core $20S$ (Particella Catalitica)**: È il "barile" interno. Ha attività proteasica (taglia i legami peptidici) ma la sua entrata è stretta.
    * **Due Cap $19S$ (Particelle Regolatorie)**: Riconoscono la catena di poli-Ub, legano la proteina (richiedendo ATP), rimuovono e riciclano l'ubiquitina (attività DUBs - Deubiquitinating enzymes), **svolgono** (unfold) la proteina (richiede ATP) e la "infilano" nel core $20S$.
* **Degradazione**: All'interno del core $20S$, la proteina (ora lineare) viene fatta a pezzi in piccoli peptidi (circa $7-9$ amminoacidi), che vengono poi rilasciati nel citoplasma e riciclati.

## Proteine Simili all'Ubiquitina (UBLs)

L'ubiquitinazione non è l'unica modifica di questo tipo. Esistono altre piccole proteine (Ubiquitin-Like Proteins, UBLs) che possono essere attaccate ai substrati in modo simile.

Usano anch'esse una cascata E1-E2-E3, ma con enzimi *specifici* per ciascuna.

La differenza fondamentale è la **conseguenza**:
* **Ubiquitinazione ($K48$)** $\to$ Degradazione.
* **Modifica con UBLs** $\to$ Regolazione (non degradativa).

Esempio principale: **SUMO (Small Ubiquitin-related Modifier)**
* Il processo è chiamato **SUMOilazione**.
* Non porta alla degradazione.
* È una modifica post-traduzionale (come la [[Fosforilazione]]) che altera la funzione, la localizzazione o le interazioni della proteina bersaglio.
* *Esempio*: La SUMOilazione della proteina $RanGAP1$ è necessaria per il suo corretto posizionamento ai pori nucleari. La SUMOilazione di fattori di trascrizione può modularne l'attività.



Altre UBLs includono $NEDD8$ (coinvolto nell'attivazione di alcune E3 ligasi) e $ISG15$ (coinvolto nella risposta antivirale).