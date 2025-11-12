La sintesi proteica (traduzione) avviene sui ribosomi nel **citosol**. Tuttavia, la maggior parte delle proteine svolge la propria funzione all'interno di specifici organelli (es. nucleo, mitocondri) o deve essere secreta all'esterno.
Lo **smistamento proteico** (o *protein targeting*) è il processo biologico che indirizza le proteine neosintetizzate al loro corretto compartimento cellulare.

---

## 1. Compartimenti Cellulari e Relazioni Topologiche

Per capire il trasporto, dobbiamo raggruppare i compartimenti cellulari in base alla loro "topologia" (la loro relazione con il citosol e la membrana).

1.  **Nucleo e Citosol:** Sono topologicamente *continui* (o equivalenti). Sebbene separati dall'involucro nucleare, comunicano attraverso "cancelli" (i pori nucleari) senza che le macromolecole debbano attraversare una membrana.
2.  **La Via Secretoria/Endocitica:** (Reticolo Endoplasmatico, Apparato di Golgi, Endosomi, Lisosomi, Vescicole di trasporto). L'interno (lume) di questi organelli è topologicamente *equivalente* all'**ambiente extracellulare**. Una proteina che entra nel lume del RE non dovrà più attraversare una membrana per essere secreta.
3.  **Compartimenti Separati:** (Mitocondri, Perossisomi). Sono organelli circondati da membrane che non comunicano tramite vescicole con la via secretoria. Topologicamente sono isolati sia dal citosol sia dall'esterno.

Questa suddivisione topologica definisce i 3 meccanismi di trasporto.

---

## 2. Segnali di Indirizzamento (Sequenze Segnale)

Come fa la cellula a sapere dove va una proteina? La proteina stessa porta un "codice di avviamento postale" molecolare.

* **Sequenza Segnale:** È una specifica sequenza di amminoacidi (spesso 15-60 aa) all'interno della proteina.
* **Posizione:** Può essere all'N-terminale (comune per ER, mitocondri), al C-terminale (perossisomi) o interna (per il nucleo).
* **Destino:** Spesso viene rimossa (clivata) da una *peptidasi del segnale* una volta che la proteina ha raggiunto la destinazione (es. ER, mitocondri), ma non sempre (es. segnale nucleare).
* **Recettori:** Queste sequenze sono riconosciute da specifici **recettori di smistamento** che legano la proteina e la guidano al traslocatore corretto.

| Destinazione | Segnale Tipico | Destino del Segnale |
| :--- | :--- | :--- |
| **Reticolo Endopl.** | Sequenza N-terminale idrofoba | Clivato |
| **Mitocondrio** | Elica anfipatica N-terminale | Clivato |
| **Nucleo** | Sequenza interna (NLS) ricca di $Lys$, $Arg$ | Non clivato |
| **Perossisoma** | Sequenza C-terminale (es. $-SKL$) | Non clivato |
| **Ritorno al RE** | Sequenza C-terminale ($KDEL$) | Non clivato |

---

## 3. I Tre Meccanismi di Trasporto

### 3.1 Trasporto Regolato (Attraverso Pori Nucleari)

È il trasporto tra **citosol e nucleo** (topologicamente equivalenti).

* **Struttura:** **Complesso del Poro Nucleare (NPC)**. È un "cancello" sofisticato, un'enorme struttura proteica (fatta di *nucleoporine*) che perfora l'involucro nucleare.
* **Come funziona:**
    1.  **Importazione:** Una proteina "cargo" con un **Segnale di Localizzazione Nucleare (NLS)** viene riconosciuta nel citosol da un **Recettore di Importazione Nucleare** (es. *Importina*).
    2.  L'Importina lega il cargo e interagisce con le *nucleoporine FG* (ricche di Fenilalanina-Glicina) all'interno del poro, "scivolando" attraverso.
    3.  La proteina passa attraverso il poro nel suo stato **ripiegato (folded)**.
    4.  **Rilascio:** All'interno del nucleo, l'Importina lega **Ran-GTP** (una piccola GTPasi). Questo legame causa un cambio conformazionale che fa rilasciare il cargo.
    5.  **Riciclo:** L'Importina-Ran-GTP torna nel citosol, dove Ran-GAP (una proteina accessoria) idrolizza GTP $\rightarrow$ Ran-GDP, che si stacca, rendendo l'Importina pronta per un altro ciclo.
* **Gradiente Ran:** Il trasporto è direzionale grazie al **gradiente di Ran**: alta [Ran-GTP] nel nucleo (mantenuta da Ran-GEF) e alta [Ran-GDP] nel citosol (mantenuta da Ran-GAP).
* **Esportazione:** Funziona in modo inverso, usando **Segnali di Esportazione Nucleare (NES)** e *Esportine* (che legano il cargo solo in presenza di Ran-GTP).
  
### 3.2 Trasporto Transmembrana (Tramite Traslocatori)

È il trasporto dal **citosol** verso **mitocondri, RE o perossisomi** (topologicamente diversi). La proteina deve *attraversare* una o più membrane.

* **Struttura:** **Traslocatori proteici** (canali proteici specializzati, es. $TOM/TIM$ nei mitocondri, $Sec61$ nel RE).
* **Meccanismo:** La proteina viene trasportata in stato **non ripiegato (unfolded)**, come un filo che passa attraverso una cruna.
* **Chaperoni:** Proteine (es. $Hsp70$) legano la proteina nel citosol per mantenerla "distesa" (unfolded) e pronta per il trasporto.

**Due modalità principali:**

1.  **Trasporto Post-Traduzionale (es. Mitocondri):**
    1.  La proteina è sintetizzata *completamente* nel citosol e mantenuta distesa da $Hsp70$.
    2.  La sequenza segnale N-terminale è riconosciuta dal complesso **TOM** (membrana esterna mitocondriale).
    3.  La proteina passa attraverso TOM e poi attraverso **TIM** (membrana interna).
    4.  All'interno della matrice, la *Hsp70 mitocondriale* (che usa $ATP$) "tira" attivamente la proteina all'interno e aiuta il ripiegamento.
    5.  La sequenza segnale viene clivata.

2.  **Trasporto Co-Traduzionale (es. Reticolo Endoplasmatico):**
    1.  La sintesi *inizia* nel citosol. Appena la sequenza segnale N-terminale (idrofoba) emerge dal ribosoma, viene riconosciuta dalla **Particella di Riconoscimento del Segnale (SRP)**.
    2.  SRP *blocca* la traduzione e guida l'intero complesso (ribosoma + mRNA + proteina nascente) al **Recettore per SRP** sulla membrana del RE.
    3.  Il ribosoma si aggancia al traslocatore **Sec61**. SRP si stacca.
    4.  La traduzione *riprende* e la proteina viene "iniettata" (traslocata) nel lume del RE *mentre viene sintetizzata*.
    5.  La *peptidasi del segnale* (sul lato luminale) taglia la sequenza segnale.
    6.  (Per le proteine di membrana, il traslocatore Sec61 le inserisce lateralmente nel bilayer).



### 3.3 Trasporto Vescicolare

È il trasporto tra compartimenti della **via secretoria** (ER, Golgi, endosomi, ecc.) e la membrana plasmatica (topologicamente equivalenti).

* **Struttura:** **Vescicole di trasporto**. Piccole "bolle" di membrana che gemmano da un compartimento (donatore) e si fondono con un altro (accettore).
* **Meccanismo:** Le proteine *non* attraversano mai una membrana. Vengono trasportate come "passeggeri" all'interno del lume della vescicola o come parte della membrana della vescicola stessa.
* **Fasi chiave:**
    1.  **Gemmazione (Budding):** Formazione della vescicola. Richiede **proteine di rivestimento (Coat)** che si assemblano sul lato citosolico, curvano la membrana e *selezionano il cargo*.
        * **COPII:** Trasporto Anterogrado ($RE \rightarrow Golgi$).
        * **COPI:** Trasporto Retrogrado ($Golgi \rightarrow RE$).
        * **Clatrina:** ($Golgi \rightarrow Endosoma$) e (Membrana $\rightarrow Endosoma$, *Endocitosi*).
    2.  **Trasporto:** Le vescicole (ora nude, perso il coat) si muovono (spesso lungo il citoscheletro).
    3.  **Aggancio (Tethering) e Fusione (Fusion):**
        * **Proteine Rab (GTPasi):** Agiscono come "codici postali" specifici. Rab-GTP sulla vescicola lega *Tethering factors* sul bersaglio.
        * **Proteine SNARE:** Mediano la fusione. Una **v-SNARE** (sulla vescicola) si avvolge (come una cerniera) con una **t-SNARE** (sul bersaglio), forzando l'unione dei due doppi strati lipidici e il rilascio del contenuto.