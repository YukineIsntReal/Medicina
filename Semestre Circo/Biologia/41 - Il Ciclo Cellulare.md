Il **ciclo cellulare** rappresenta la sequenza ordinata di eventi attraverso cui una cellula eucariotica cresce, duplica il proprio materiale genetico (DNA) e si divide in due cellule figlie geneticamente identiche (salvo errori). È un processo fondamentale per la crescita, il rinnovo tissutale e la riproduzione.

## Le Fasi del Ciclo Cellulare

Il ciclo cellulare si suddivide principalmente in due grandi fasi: l'**Interfase** e la **Fase M (Mitosi)**.

### Interfase

L'interfase è il periodo più lungo del ciclo, durante il quale la cellula svolge le sue normali funzioni metaboliche, cresce e si prepara alla divisione. Si suddivide in tre sottofasi:

1.  **Fase $G_1$ (Gap 1):**
    * È la fase di crescita cellulare post-mitotica.
    * La cellula è metabolicamente attiva, sintetizza proteine, lipidi e RNA.
    * Aumenta di dimensioni e produce nuovi organelli.
    * Verso la fine della $G_1$, la cellula raggiunge un punto di controllo critico (vedi sotto).
    * Le cellule che non si dividono (es. neuroni maturi) possono uscire dal ciclo ed entrare in una fase di quiescenza detta **Fase $G_0$**.

2.  **Fase $S$ (Sintesi):**
    * È la fase cruciale della **duplicazione del DNA**.
    * Ogni cromosoma, inizialmente formato da un singolo cromatidio, viene replicato. Alla fine della fase $S$, ogni cromosoma sarà composto da due **cromatidi fratelli** identici, uniti a livello del centromero.
    * Viene sintetizzata anche la maggior parte degli **istoni**, le proteine che impacchettano il DNA.

3.  **Fase $G_2$ (Gap 2):**
    * La cellula continua a crescere e a sintetizzare proteine e organelli.
    * Si prepara attivamente alla mitosi, accumulando energia e sintetizzando le molecole necessarie (es. tubulina per il fuso mitotico).
    * Vengono controllati eventuali errori nella duplicazione del DNA.

### Fase M (Mitosi)

È la fase della divisione cellulare vera e propria, che porta alla formazione di due nuclei figli identici. È seguita dalla **citodieresi** (divisione del citoplasma). La mitosi è un processo continuo, ma convenzionalmente suddiviso in quattro fasi principali (o cinque, includendo la prometafase).

---

## Punti di Controllo (Checkpoints)

Per garantire l'integrità del processo e prevenire errori (come la trasmissione di DNA danneggiato o una divisione incompleta), il ciclo cellulare è strettamente regolato da **punti di controllo** (checkpoints). Questi sono meccanismi di sorveglianza che "fermano" il ciclo se rilevano anomalie.

1.  **Checkpoint $G_1$ (o Punto di Restrizione):**
    * Situato verso la fine della $G_1$.
    * Controlla:
        * **Dimensioni cellulari:** La cellula è abbastanza grande?
        * **Nutrienti:** Ci sono sufficienti risorse?
        * **Segnali di crescita:** Sono presenti fattori mitogeni?
        * **Integrità del DNA:** Il DNA è danneggiato?
    * Se le condizioni non sono favorevoli o il DNA è danneggiato (attivazione di $p53$), la cellula si arresta in $G_1$ (o entra in $G_0$ o va in apoptosi). Se le condizioni sono idonee, supera il punto di restrizione e si impegna irreversibilmente ad entrare in fase $S$.

2.  **Checkpoint $G_2$/M:**
    * Situato alla transizione tra $G_2$ e Mitosi.
    * Controlla:
        * **Replicazione del DNA:** Il DNA è stato duplicato completamente?
        * **Danni al DNA:** Ci sono danni riparabili?
    * Se il DNA non è replicato correttamente o è danneggiato, il checkpoint impedisce l'ingresso in mitosi, dando tempo alla cellula di riparare i danni.

3.  **Checkpoint del Fuso (o Checkpoint Metafase-Anafase):**
    * Agisce durante la metafase.
    * Controlla:
        * **Corretto assemblaggio del fuso mitotico.**
        * **Corretto attacco dei cinetocori:** Tutti i cromatidi fratelli sono correttamente attaccati ai microtubuli del fuso provenienti da poli opposti?
    * Impedisce l'inizio dell'anafase (la separazione dei cromatidi fratelli) finché tutti i cromosomi non sono allineati correttamente all'equatore. Questo previene aneuploidie (numero errato di cromosomi nelle cellule figlie).

---

## Regolazione: Cicline e Chinasi Ciclina-Dipendenti (CDK)

Il motore molecolare che guida la transizione tra le fasi del ciclo è costituito da una famiglia di enzimi chiamati **Chinasi Ciclina-Dipendenti (CDK)**.

* **Chinasi Ciclina-Dipendenti (CDK):** Sono enzimi (proteine chinasi) che attivano o disattivano altre proteine bersaglio (coinvolte nel ciclo) aggiungendo loro un gruppo fosfato (fosforilazione). Le CDK sono presenti a livelli relativamente costanti durante tutto il ciclo, ma sono *inattive* se non legate a una ciclina.

* **Cicline:** Sono proteine regolatrici la cui concentrazione *varia ciclicamente* (da cui il nome) durante le diverse fasi. Sono loro ad attivare le CDK.

**Modulazione dell'attività CDK-Ciclina:**

L'attività dei complessi Ciclina-CDK è finemente regolata:

1.  **Sintesi e Degradazione delle Cicline:** La concentrazione delle diverse cicline (es. Ciclina D, E, A, B) aumenta nella fase in cui servono e diminuisce bruscamente quando non sono più necessarie, grazie alla degradazione mediata dall'**ubiquitina** e dal **proteasoma**.
2.  **Fosforilazione Inibitoria/Attivatoria:** Le CDK stesse possono essere fosforilate in siti specifici. Alcune fosforilazioni sono attivatorie, altre (spesso transitorie) sono inibitorie (es. fosforilazione da parte di Wee1).
3.  **Inibitori delle CDK (CKI):** Esistono proteine inibitrici (es. famiglia $p21$, $p27$, $p16$) che si legano ai complessi Ciclina-CDK e ne bloccano l'attività, spesso in risposta a segnali di arresto (come danni al DNA).

**Principali Complessi Ciclina-CDK:**

* **Ciclina D - CDK4/6:** Agiscono nella fase $G_1$ precoce/media. Fosforilano la proteina **$Rb$ (Retinoblastoma)**.
* **Ciclina E - CDK2:** Agiscono nella $G_1$ tardiva. Completano la fosforilazione di $Rb$, permettendo il superamento del punto di restrizione e l'attivazione dei geni per la fase $S$.
* **Ciclina A - CDK2/CDK1:** Agiscono durante la fase $S$ e $G_2$. Sono essenziali per l'inizio e la progressione della replicazione del DNA.
* **Ciclina B - CDK1 (o MPF):** È il "M-phase Promoting Factor". Si accumula in $G_2$ e, una volta attivato (rimuovendo una fosforilazione inibitoria), guida l'ingresso e la progressione della Mitosi.

---

## Le Fasi della Mitosi

La Mitosi è il processo di divisione nucleare.

### 1. Profase
* **Condensazione dei Cromosomi:** La cromatina si spiralizza e condensa enormemente, grazie all'azione delle **condensine**. I cromosomi diventano visibili al microscopio ottico come strutture distinte, ciascuna composta da due cromatidi fratelli.
* **Formazione del Fuso Mitotico:** I **centrosomi** (duplicati in fase $S$) migrano ai poli opposti della cellula. Da essi si irradiano i microtubuli che iniziano a formare il fuso mitotico.
* **Scomparsa del Nucleolo:** Il nucleolo si disgrega.

### 2. Prometafase
* **Rottura dell'Involucro Nucleare:** L'involucro nucleare si frammenta (spesso grazie alla fosforilazione delle lamine nucleari da parte di CDK1).
* **Attacco dei Microtubuli:** I microtubuli del fuso (chiamati microtubuli del cinetocore) possono ora accedere ai cromosomi e legarsi a strutture proteiche specializzate sui centromeri, chiamate **cinetocori**.
* I cromosomi iniziano a muoversi verso il centro della cellula.

### 3. Metafase
* **Allineamento:** I cromosomi raggiungono il massimo grado di condensazione. Vengono "tirati" dalle forze opposte dei microtubuli e si allineano perfettamente lungo la **piastra metafasica** (o piano equatoriale), una linea immaginaria equidistante dai due poli.
* È la fase in cui agisce il **Checkpoint del Fuso**.

### 4. Anafase
* **Separazione dei Cromatidi Fratelli:** L'enzima **separasi** (attivato dal complesso APC/C dopo il superamento del checkpoint) taglia le **coesine** che tenevano uniti i cromatidi fratelli.
* I cromatidi fratelli, ora considerati cromosomi figli indipendenti, vengono trascinati dai microtubuli (che si accorciano) verso i poli opposti del fuso.
* I poli del fuso si allontanano ulteriormente, contribuendo alla separazione.

### 5. Telofase
* **Riformazione dei Nuclei:** I cromosomi figli raggiungono i poli opposti.
* **Decondensazione:** I cromosomi iniziano a decondensarsi, tornando allo stato di cromatina.
* **Riformazione dell'Involucro Nucleare:** Frammenti del vecchio involucro e vescicole del RE si riassociano attorno ai due gruppi di cromosomi, formando due nuovi involucri nucleari.
* **Ricomparsa del Nucleolo:** I nucleoli si riformano.
* Il fuso mitotico si disassembla.

### Citodieresi
Solitamente inizia durante l'anafase o la telofase, ma è un processo distinto dalla mitosi (divisione nucleare).
* **Cellule Animali:** Si forma un **anello contrattile** di actina e miosina a livello equatoriale. Contraendosi, "strozza" il citoplasma formando un solco di clivaggio, fino a separare le due cellule figlie.
* **Cellule Vegetali:** Si forma una **piastra cellulare** al centro, che cresce verso l'esterno fino a fondersi con la parete cellulare esistente.

---

## Ingresso in Mitosi e Condensazione dei Cromosomi

L'**ingresso in mitosi** è guidato principalmente dall'attivazione del complesso **Ciclina B - CDK1 (MPF)**. Sebbene la Ciclina B si accumuli durante la $G_2$, il complesso è tenuto inattivo da una fosforilazione inibitoria (es. da parte della chinasi Wee1). Al momento opportuno, la fosfatasi $Cdc25$ rimuove questo fosfato inibitorio, attivando bruscamente MPF.

L'MPF attivo fosforila una miriade di substrati, innescando:
1.  **Condensazione dei Cromosomi:** MPF attiva le **condensine**, complessi proteici che impacchettano la cromatina in strutture compatte.
2.  **Rottura dell'Involucro Nucleare:** MPF fosforila le **lamine** (proteine del filamento intermedio che sostengono l'involucro), causandone la depolimerizzazione e la frammentazione dell'involucro.
3.  **Formazione del Fuso:** MPF contribuisce alla riorganizzazione dei microtubuli e alla separazione dei centrosomi.
4.  **Disgregazione del Nucleolo e del RE/Golgi:** (Anche se i meccanismi sono complessi).

La **condensazione dei cromosomi** è un processo vitale per evitare che i lunghi filamenti di DNA si aggroviglino o si rompano durante la segregazione. È mediato da due complessi simili:
* **Coesine:** Tengono uniti i cromatidi fratelli dalla fase $S$ fino all'anafase.
* **Condensine:** Sono responsabili dell'impacchettamento e della spiralizzazione di *ciascun* cromatidio fratello durante la profase.