La **[[Traduzione]]** è il processo cellulare attraverso cui l'informazione genetica (contenuta in una sequenza di [[mRNA]]) viene "tradotta" nella sequenza di amminoacidi che compone una [[Proteina]]. Questo processo avviene nel citoplasma ad opera di complessi macromolecolari chiamati **[[Ribosomi]]**.

## Il Codice Genetico

Il **codice genetico** è il "dizionario" che stabilisce la corrispondenza tra la sequenza di nucleotidi sull'mRNA e la sequenza di amminoacidi.

* **[[Codoni]]**: L'unità base del codice è il **codone**, una tripletta di $3$ nucleotidi consecutivi sull'mRNA (es. $AUG$, $GUC$, $CCA$).
* **Anticodoni**: Il codone sull'mRNA viene letto (per appaiamento complementare) dall'**anticodone**, una tripletta presente su una molecola di [[tRNA]].
* **Combinazioni**: Con $4$ basi ($A, U, G, C$), esistono $4^3 = 64$ possibili codoni.
    * $61$ codoni specificano per i $20$ amminoacidi.
    * $3$ codoni ($UAA, UAG, UGA$) sono **Codoni di Stop**, che segnalano la fine della traduzione.
    * $1$ codone ($AUG$) è il **Codone di Inizio** (specifica per la Metionina).

### Proprietà del Codice Genetico
1.  **Non Ambiguità**: Un singolo codone specifica *sempre e solo* per un amminoacido (es. $GUC$ codifica *solo* per la Valina).
2.  **Degenerazione (o Ridondanza)**: Un amminoacido può essere specificato da *più* codoni (es. la Leucina è codificata da $6$ codoni diversi: $UUA, UUG, CUU, CUC, CUA, CUG$).
    * La degenerazione è spesso dovuta alla terza base del codone, un fenomeno noto come *vacillamento* (wobble).
3.  **Universalità**: Il codice è (quasi) identico in tutti gli organismi viventi, dai batteri all'uomo. (Le principali eccezioni si trovano nel DNA mitocondriale).

## Gli Attori della Traduzione

### 1. mRNA (RNA Messaggero)
È lo stampo (template). Porta l'informazione copiata dal [[DNA]] sotto forma di codoni. Viene letto dal ribosoma in direzione $5' \to 3'$.

### 2. tRNA (RNA Transfer)
È la molecola "adattatrice". Ha il compito di *legare* un amminoacido specifico e di *riconoscere* il codone corrispondente sull'mRNA.
* **Struttura**: Ha una struttura 3D a "L" (spesso disegnata a "trifoglio" in 2D). 

* **Siti chiave**:
    * **Ansa dell'Anticodone**: Contiene la tripletta (anticodone) che si appaia al codone sull'mRNA.
    * **Estremità $3'$ (Sito Accettore)**: Termina sempre con la sequenza $CCA$. È il punto in cui viene legato (caricato) l'amminoacido.
* **Sintesi e Maturazione (Eucarioti)**: I geni per i tRNA sono trascritti dalla [[RNA Polimerasi III]]. Il pre-tRNA subisce un notevole processamento: rimozione di sequenze (introni), modifiche chimiche estese delle basi (es. pseudouridina, diidrouridina) e aggiunta enzimatica del $CCA$ al $3'$.

### 3. Ribosomi e rRNA (RNA Ribosomiale)
Sono la "fabbrica" della sintesi proteica. Il ribosoma è un complesso enorme di [[rRNA]] e proteine.
* **Struttura**: È diviso in due subunità:
    * **Procarioti**: $70S$ (composta da $50S$ + $30S$).
    * **Eucarioti**: $80S$ (composta da $60S$ + $40S$).
* **Ruolo dell'rRNA**: L'rRNA non è solo strutturale; è l'rRNA della subunità maggiore ($23S$ nei procarioti, $28S$ negli eucarioti) che possiede l'attività catalitica per formare il legame peptidico. È un **[[Ribozima]]**.
* **Sintesi e Maturazione rRNA (Eucarioti)**: I geni $18S, 5.8S, 28S$ sono trascritti dalla [[RNA Polimerasi I]] nel [[nucleolo]] come un unico lungo *pre-rRNA*. Questo viene poi tagliato (clivato) e processato. L'rRNA $5S$ è trascritto dalla Pol III.

## La Carica del tRNA: Sintesi degli Aminoacil-tRNA

Perché la traduzione sia corretta, ogni tRNA deve essere legato all'amminoacido *giusto*.
* **Enzimi**: **Aminoacil-tRNA Sintetasi**.
* **Specificità**: Esiste un enzima specifico per ognuno dei $20$ amminoacidi. Questo enzima riconosce in modo univoco sia l'amminoacido sia il/i tRNA corrispondente/i (spesso tramite l'anticodone).
* **Processo (richiede ATP)**:
    1.  $Amminoacido + ATP \to Amminoacido-AMP + PPi$
    2.  $Amminoacido-AMP + tRNA \to$ **Aminoacil-tRNA** $+ AMP$
* Il tRNA "carico" (ora chiamato aminoacil-tRNA) porta l'amminoacido al ribosoma. L'alta energia del legame estere tra tRNA e amminoacido verrà usata per formare il legame peptidico.

## Il Meccanismo della Traduzione

Il ribosoma possiede tre "siti" per i tRNA:
* **Sito A** (Aminoacil): Dove entra il nuovo aminoacil-tRNA carico.
* **Sito P** (Peptidil): Dove si trova il tRNA che tiene la catena polipeptidica in crescita.
* **Sito E** (Exit): Dove transita il tRNA scarico prima di essere rilasciato.



### 1. Inizio (Iniziazione)
Richiede **Fattori di Inizio** ($IFs$ nei procarioti, $eIFs$ negli eucarioti).
1.  La **subunità minore** del ribosoma si lega all'mRNA.
    * *Procarioti*: La subunità $30S$ riconosce la sequenza **Shine-Dalgarno** (sul mRNA), posizionando il codone $AUG$ d'inizio nel sito P.
    * *Eucarioti*: La subunità $40S$ (già legata a $eIFs$ e al tRNA iniziatore) riconosce il **Capping $5'$** e *scansiona* l'mRNA ($scanning$) fino a trovare il primo $AUG$ (spesso in una sequenza $Kozak$).
2.  Il **tRNA iniziatore** (che porta la Metionina, *fMet* nei procarioti) si lega al codone $AUG$ nel **sito P**. È l'unico tRNA che entra direttamente in P.
3.  La **subunità maggiore** si unisce al complesso, idrolizzando $GTP$. Il ribosoma è assemblato e pronto per l'elongazione.

### 2. Elongazione (Allungamento)
Richiede **Fattori di Elongazione** ($EFs$ / $eEFs$) e $GTP$. È un ciclo a tre fasi:
1.  **Ingresso dell'Aminoacil-tRNA (Sito A)**: Un nuovo aminoacil-tRNA (scortato da $EF-Tu/eEF1A$ e $GTP$) entra nel sito A e si appaia al codone. L'idrolisi del $GTP$ assicura la correttezza dell'appaiamento.
2.  **Formazione del Legame Peptidico**: L'attività **peptidil-transferasica** (rRNA della subunità maggiore) catalizza la formazione di un legame peptidico: la catena polipeptidica nel sito P viene staccata dal suo tRNA e legata all'amminoacido sul tRNA nel sito A.
3.  **Traslocazione**: Il ribosoma si sposta di *un codone* (richiede $EF-G/eEF2$ e $GTP$).
    * Il tRNA scarico (che era in P) si sposta nel sito E e viene espulso.
    * Il tRNA che era in A (ora legato a tutta la catena) si sposta nel sito P.
    * Il sito A è ora vuoto, pronto per un nuovo ciclo.



### 3. Terminazione
1.  L'elongazione prosegue finché uno dei $3$ **Codoni di Stop** ($UAA, UAG, UGA$) entra nel sito A.
2.  Non esistono tRNA con anticodoni per lo stop. Al loro posto, i **Fattori di Rilascio** (**Release Factors**, $RFs$ / $eRFs$) si legano al sito A.
3.  I RFs inducono l'idrolisi del legame tra la catena polipeptidica e il tRNA nel sito P.
4.  La proteina neosintetizzata viene rilasciata.
5.  I componenti (le due subunità, l'mRNA, i fattori) si dissociano, pronti per un nuovo ciclo di traduzione.