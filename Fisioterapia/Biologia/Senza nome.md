# Dal DNA alle Proteine

Il flusso dell'informazione genetica segue il **Dogma Centrale della Biologia Molecolare**: il DNA si replica, viene trascritto in RNA e l'RNA viene tradotto in proteine.

## 1. Duplicazione (Replicazione) del DNA
La duplicazione del [[DNA]] è un processo **semiconservativo**: ogni nuova molecola di DNA è formata da un filamento vecchio (parentale) e da un filamento di nuova sintesi. Avviene durante la fase S del [[Ciclo cellulare]].

### Enzimi e Meccanismo
Il processo inizia nelle origini di replicazione, dove la doppia elica viene aperta formando la *forcella di replicazione*.
* **Elicasi**: Srotola e separa i due filamenti di DNA rompendo i legami a idrogeno tra le basi azotate.
* **Topoisomerasi**: Impedisce il superavvolgimento del DNA a valle della forcella.
* **Primasi**: È una RNA polimerasi che sintetizza un breve tratto di RNA detto **primer** (o innesco), necessario perché la DNA polimerasi non può iniziare a sintetizzare dal nulla.
* **DNA Polimerasi**: Aggiunge i nuovi nucleotidi complementari. Regola d'oro per i test: **lavora SEMPRE E SOLO in direzione 5' -> 3'**. Ha anche un'attività di *proofreading* (correzione di bozze) per correggere eventuali errori.
* **Ligasi**: Unisce i frammenti di DNA appena sintetizzati.

### Filamento Guida e Filamento Lento
Poiché i due filamenti del DNA sono antiparalleli e la DNA Polimerasi lavora solo in direzione 5' -> 3':
* Il **filamento guida** (veloce) è sintetizzato in modo continuo.
* Il **filamento lento** (ritardato) è sintetizzato in modo discontinuo sotto forma di corti segmenti chiamati **Frammenti di Okazaki**, che verranno poi uniti dalla Ligasi. ^frammenti-okazaki

---

## 2. Trascrizione (dal DNA all'mRNA)
La trascrizione è il processo di sintesi di una molecola di RNA messaggero (mRNA) a partire da uno stampo di DNA. 
* **Enzima chiave**: L'**[[RNA Polimerasi]]**. Si lega a specifiche sequenze di DNA chiamate **promotori** (nei test è famosa la *TATA box*).
* Non c'è bisogno di primer: l'RNA Polimerasi apre l'elica e inizia a copiare un solo filamento (il filamento stampo). Al posto della Timina (T), nell'RNA viene inserito l'Uracile (U).
* **Maturazione dell'mRNA (solo negli Eucarioti)**: Prima di uscire dal nucleo, il pre-mRNA subisce modifiche:
    1.  *Capping*: Aggiunta di un "cappuccio" al terminale 5'.
    2.  *Poliadenilazione*: Aggiunta di una coda di adenine (coda poli-A) al terminale 3'.
    3.  *Splicing*: Rimozione degli **introni** (parti non codificanti) e unione degli **esoni** (parti codificanti).

---

## 3. Il Codice Genetico
Il codice genetico è il "vocabolario" che traduce la sequenza di nucleotidi dell'mRNA nella sequenza di amminoacidi di una proteina. L'informazione è letta in gruppi di tre nucleotidi, chiamati **codoni** (o triplette).
Essendoci 4 basi azotate lette a gruppi di 3, ci sono $4^3 = 64$ combinazioni possibili.
* **Codone di START**: AUG (codifica per la Metionina).
* **Codoni di STOP**: UAA, UAG, UGA (non codificano per nessun amminoacido, segnano la fine della traduzione).

### Caratteristiche Fondamentali (Domande frequenti ai test!)
1.  **Universale**: È identico in quasi tutti gli organismi viventi (dai batteri all'uomo).
2.  **Ridondante (o Degenerato)**: Un singolo amminoacido può essere codificato da più codoni diversi (es. ci sono 6 codoni per la Leucina). Questo protegge dalle mutazioni.
3.  **Univoco (Non ambiguo)**: Un singolo codone codifica per **uno e un solo** amminoacido.
4.  **Senza punteggiatura**: Viene letto in modo continuo, senza sovrapposizioni o salti. ^caratteristiche-codice

---

## 4. Traduzione (Sintesi Proteica)
È il processo in cui l'mRNA viene letto per assemblare una catena polipeptidica. Avviene nel citoplasma.

### I protagonisti
* **[[mRNA]]**: Porta l'informazione dal nucleo al citoplasma.
* **[[tRNA]] (RNA transfer)**: Funziona da interprete. Ha una forma a trifoglio; a un'estremità lega un amminoacido specifico, dall'altra espone un **anticodone** (tre basi complementari al codone dell'mRNA).
* **[[Ribosomi]]**: Organuli composti da rRNA e proteine. Formati da due subunità (maggiore e minore). La subunità maggiore ha tre siti:
    * **Sito A (Amminoacilico)**: Accoglie il nuovo tRNA carico dell'amminoacido.
    * **Sito P (Peptidilico)**: Ospita il tRNA che trattiene la catena polipeptidica in crescita.
    * **Sito E (Exit)**: Da dove il tRNA "scarico" esce dal ribosoma.

### Fasi della Traduzione
1.  **Inizio**: La subunità minore del ribosoma si lega all'mRNA. Scorre fino a trovare il codone di START (AUG). Il tRNA con la Metionina si lega e si unisce la subunità maggiore.
2.  **Allungamento**: Un nuovo tRNA entra nel sito A. Si forma un legame peptidico tra l'amminoacido nel sito P e quello nel sito A. Il ribosoma scorre (traslocazione) di un codone.
3.  **Terminazione**: Quando il ribosoma incontra un codone di STOP, un *fattore di rilascio* si lega al sito A. La proteina appena formata viene liberata e il ribosoma si disassembla.