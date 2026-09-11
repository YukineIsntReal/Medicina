L'**Autofagia** (dal greco "mangiare sé stessi") è un processo catabolico cellulare fondamentale e conservato evolutivamente. È il meccanismo "spazzino" e di controllo qualità della cellula, responsabile della degradazione e del riciclo di componenti citoplasmatici (proteine mal ripiegate, aggregati, organelli danneggiati) attraverso il **[[Lisosoma]]**.

Non è solo un sistema di pulizia, ma anche una strategia di sopravvivenza: in condizioni di stress (es. carenza di nutrienti), la cellula digerisce parti "non essenziali" di sé stessa per produrre amminoacidi ed energia ($ATP$) per sopravvivere.

Si distinguono tre meccanismi principali.

---

## 1. I Tre Tipi di Autofagia



### 1.1 Macroautofagia (La Via Principale)
È la forma di autofagia più studiata e quella a cui ci si riferisce comunemente parlando di "autofagia".
* **Meccanismo:** È un processo **non selettivo** (bulk-flow) o **selettivo** (per organelli specifici).
    1.  **Induzione:** In risposta a stress (es. carenza di nutrienti, attivazione di AMPK) o segnali di danno, il complesso inibitore **mTORC1** viene disattivato. Questo permette l'attivazione del complesso di inizio (es. ULK1).
    2.  **Nucleazione:** Si forma una membrana di isolamento (o *fagoforo*) nel citoplasma, spesso originata da domini del [[Reticolo Endoplasmatico]] o del Golgi.
    3.  **Elongazione:** Il fagoforo si espande e curva, inglobando una porzione di citoplasma (e/o organelli specifici). Questo processo richiede complessi proteici chiave (es. Beclin 1-VPS34) e la coniugazione della proteina **LC3** alla membrana (da LC3-I citosolica a LC3-II legata alla membrana, un marcatore chiave).
    4.  **Chiusura:** Il fagoforo si chiude su sé stesso, formando un **Autofagosoma**, una vescicola a *doppia membrana*.
    5.  **Fusione:** L'autofagosoma migra e si fonde con un **[[Lisosoma]]** (mediato da [[Proteine SNARE]] e Rab).
    6.  **Degradazione:** Il contenuto viene degradato dalle **idrolasi acide** lisosomiali. I prodotti (amminoacidi, acidi grassi) vengono rilasciati nel citosol per essere riutilizzati.

### 1.2 Microautofagia
* **Meccanismo:** È un processo **diretto** e più semplice.
    * La membrana del lisosoma (o dell'endosoma tardivo) stessa si *invagina* o protrude per inglobare direttamente piccole porzioni di citoplasma.
    * È un processo spesso costitutivo (continuo) che contribuisce al normale turnover dei componenti citosolici.

### 1.3 Autofagia Mediata da Chaperon (CMA)
È una forma di autofagia **altamente selettiva** che degrada *proteine specifiche* una per una, senza richiedere la formazione di vescicole.
* **Meccanismo:**
    1.  **Riconoscimento (Citosol):** La proteina "cargo" da degradare deve esporre una specifica sequenza segnale (un pentapeptide, motivo **KFERQ**).
    2.  Il complesso [[Chaperone]] citosolico **Hsc70** (un membro della famiglia $Hsp70$) riconosce e lega il motivo KFERQ.
    3.  **Aggancio (Lisosoma):** Il complesso [Hsc70-Cargo] viene guidato alla membrana del lisosoma, dove si lega a un recettore transmembrana specifico: **LAMP2A**.
    4.  **Traslocazione:** Il legame con LAMP2A (che forma un complesso di traslocazione) induce lo *srotolamento* (unfolding) della proteina cargo.
    5.  La proteina (ora lineare) viene traslocata direttamente attraverso la membrana lisosomiale nel lume, dove viene immediatamente degradata dalle idrolasi.

| Caratteristica | Macroautofagia | Microautofagia | Autofagia Mediata da Chaperon (CMA) |
| :--- | :--- | :--- | :--- |
| **Cargo** | Organelli, aggregati, citosol | Citosol (piccole porzioni) | Proteine solubili specifiche |
| **Selettività** | Non selettiva (bulk) o Selettiva (es. Mitofagia) | Generalmente non selettiva | Altamente selettiva (motivo KFERQ) |
| **Vescicole** | Sì (Autofagosoma a doppia membrana) | No (Invaginazione lisosomiale) | No (Traslocazione diretta) |
| **Recettore di Membrana** | - | - | **LAMP2A** |
| **Chaperoni** | - | - | **Hsc70** |

---

## 2. Esempio di Autofagia Selettiva: La Mitofagia

La **Mitofagia** è la macroautofagia selettiva dei [[Mitocondri]]. È un meccanismo di controllo qualità essenziale per rimuovere i mitocondri danneggiati (es. con basso potenziale di membrana, $\Delta\psi$) che produrrebbero specie reattive dell'ossigeno (ROS) tossiche.

* **Meccanismo (Via PINK1/Parkin):**
    1.  **Segnale di Danno:** In un mitocondrio *sano*, la chinasi **PINK1** viene continuamente importata nella membrana interna e degradata.
    2.  Quando un mitocondrio è *danneggiato* (e perde il suo potenziale di membrana $\Delta\psi$), l'importazione di PINK1 si blocca.
    3.  **Accumulo:** PINK1 si accumula sulla **membrana mitocondriale esterna (MME)**.
    4.  **Reclutamento:** PINK1 (accumulata) recluta l'E3 ubiquitina ligasi **Parkin** (o *Parkina*), che normalmente è citosolica.
    5.  **Attivazione:** PINK1 attiva Parkin fosforilandola (e fosforilando molecole di ubiquitina).
    6.  **Marcatura (Ubiquitinazione):** Parkin (ora attiva) "etichetta" massicciamente le proteine della MME con catene di **[[Ubiquitinazione]]**.
    7.  **Riconoscimento:** Queste catene di ubiquitina vengono riconosciute da **Recettori di Autofagia** (es. *p62/Sequestosome 1*).
    8.  **Aggancio:** I recettori (come p62) legano sia l'ubiquitina sul mitocondrio sia la proteina **LC3** sulla membrana del fagoforo in formazione.
    9.  **Degradazione:** Questo "ponte" assicura che il mitocondrio danneggiato venga selettivamente inglobato dall'autofagosoma e degradato.



---

## 3. Conseguenze delle Alterazioni della Via Autofagica

Un'autofagia difettosa (troppo bassa o eccessiva) è implicata in una vasta gamma di patologie umane, poiché porta all'accumulo di "spazzatura" cellulare (aggregati proteici, organelli disfunzionali).

* **Malattie Neurodegenerative:**
    * **Causa:** I neuroni sono cellule *post-mitotiche* (non si dividono) e sono estremamente longeve. Non possono diluire i danni cellulari attraverso la divisione e dipendono criticamente dall'autofagia per la pulizia.
    * **Morbo di Parkinson:** Spesso associato a mutazioni nei geni **PINK1** o **Parkin**. La mitofagia fallisce, portando all'accumulo di mitocondri danneggiati nei neuroni dopaminergici, stress ossidativo e morte cellulare.
    * **Morbo di Alzheimer:** L'autofagia è coinvolta nella clearance sia della proteina Tau anomala sia dei peptidi Amiloide-$\beta$ (A$\beta$). Un suo difetto contribuisce all'accumulo di placche e grovigli.
    * **Morbo di Huntington:** La proteina Huntingtina mutata (mHtt) si aggrega e "sequestra" componenti chiave della via autofagica, bloccandola.

* **Cancro:**
    * Il ruolo è duale. Nelle fasi iniziali, l'autofagia agisce come **soppressore tumorale** (rimuove organelli danneggiati, previene l'instabilità genomica).
    * Nelle fasi avanzate, i tumori (spesso in condizioni di ipossia e scarsità di nutrienti) possono "dirottare" l'autofagia a loro vantaggio, usandola per **sopravvivere** allo stress e resistere alla chemioterapia.

* **Malattie Infettive e Immunità:**
    * L'autofagia (spesso chiamata *xenofagia*) è un meccanismo di difesa innata per catturare e degradare patogeni intracellulari (batteri, virus).
    * Un'autofagia difettosa (es. nei macrofagi) può compromettere la capacità di eliminare infezioni (es. *B. cepacia* nella [[Fibrosi Cistica]]).

* **Invecchiamento (Aging):**
    * L'efficienza di tutte le vie autofagiche (soprattutto CMA e macroautofagia) **declina con l'età**.
    * Questo declino porta all'accumulo di danni (proteine aggregate, mitocondri disfunzionali, lipofuscina), che è un *hallmark* (caratteristica fondamentale) dell'invecchiamento cellulare e contribuisce alle malattie legate all'età.