Le variazioni del genoma sono alla base della diversità biologica, dell'evoluzione e dell'insorgenza di numerose patologie. Si possono classificare in base alla loro scala e al loro effetto.

---

## Tipi di Mutazioni Geniche (Puntiformi)

Le mutazioni geniche interessano una o poche basi nucleotidiche.

* **Sostituzione di Nucleotidi:** Un nucleotide viene rimpiazzato con un altro.
    * **Transizioni:** Sostituzione di una purina (A, G) con un'altra purina, o di una pirimidina (C, T) con un'altra pirimidina. Sono più frequenti.
    * **Transversioni:** Sostituzione di una purina con una pirimidina, o viceversa.
* **Inserzione:** Aggiunta di uno o più nucleotidi in una sequenza.
* **Delezione:** Rimozione di uno o più nucleotidi da una sequenza.

**Effetti delle mutazioni puntiformi:**
* **Mutazioni Silenti (Sinonime):** La sostituzione non cambia l'amminoacido codificato (grazie alla degenerazione del codice genetico).
* **Mutazioni Missenso:** La sostituzione porta alla codifica di un amminoacido diverso. L'effetto sulla proteina può essere nullo, parziale o totale.
* **Mutazioni Non-Senso:** La sostituzione introduce un codone di stop ($UAA$, $UAG$, $UGA$), portando a una proteina troncata e solitamente non funzionale.
* **Mutazioni Frameshift (Sfasamento della Lettura):** Causate da inserzioni o delezioni che *non* sono multipli di tre. Alterano completamente il quadro di lettura ($reading frame$) a valle della mutazione, portando quasi sempre a una proteina non funzionale.

---

## Classificazione su Larga Scala

### Mutazioni Geniche
Come descritto sopra, alterazioni confinate all'interno di un singolo gene.

### Mutazioni Cromosomiche
Alterazioni che coinvolgono segmenti di DNA molto più grandi, interi cromosomi o l'intero corredo cromosomico.

* **Mutazioni Cromosomiche Strutturali:**
    * **Delezione:** Perdita di un segmento di cromosoma.
    * **Duplicazione:** Presenza di una copia extra di un segmento cromosomico.
    * **Inversione:** Un segmento di cromosoma viene escisso, ruotato di $180^\circ$ e reintegrato.
    * **Traslocazione:** Un segmento di cromosoma si stacca e si attacca a un altro cromosoma non omologo (traslocazione reciproca se c'è scambio, robertsoniana se fonde due cromosomi acrocentrici).
* **Mutazioni Cromosomiche Numeriche (Aneuploidie):**
    * **Monosomia:** Perdita di un singolo cromosoma (es. Sindrome di Turner, $45, X0$).
    * **Trisomia:** Presenza di un cromosoma in più (es. Sindrome di Down, Trisomia 21).

---

## Espansione di Sequenze Ripetute

Questo fenomeno riguarda specifiche regioni del genoma contenenti sequenze di DNA ripetute in tandem (spesso triplette, es. $CAG$, $CGG$).

* **Concetto:** Durante la replicazione del DNA, queste regioni sono instabili e il numero di ripetizioni può aumentare (espandersi) da una generazione all'altra o tra tessuti diversi.
* **Anticipazione Genetica:** Fenomeno per cui le malattie causate da espansione di triplette tendono a manifestarsi con maggiore gravità e in età più precoce nelle generazioni successive (correlato all'aumento del numero di ripetizioni).
* **Esempi di Patologie:**
    * **Corea di Huntington:** Espansione di $CAG$ nel gene *HTT*.
    * **Sindrome dell'X Fragile:** Espansione di $CGG$ nel gene *FMR1*.

---

## Meccanismi di Riparazione del DNA

Il DNA è costantemente sottoposto a danni (agenti chimici, radiazioni UV, errori di replicazione). La cellula possiede sistemi di riparazione altamente efficienti.

### Riparazione del Danno a Singolo Filamento (SSB)

* **BER (Base Excision Repair):** Riparazione per Escissione di Basi. Corregge danni a singole basi (es. deaminazione, ossidazione). Una DNA glicosilasi rimuove la base danneggiata, creando un sito AP (apurinico/apirimidinico), che viene poi processato e riempito.
* **NER (Nucleotide Excision Repair):** Riparazione per Escissione di Nucleotidi. Riconosce distorsioni della doppia elica (es. dimeri di timina indotti da UV). Un complesso proteico taglia un intero oligonucleotide contenente il danno, che viene poi risintetizzato.
* **MMR (Mismatch Repair):** Riparazione degli Appaiamenti Errati. Corregge errori di appaiamento sfuggiti al *proofreading* della DNA polimerasi durante la replicazione. Riconosce il filamento neosintetizzato (in E. coli tramite metilazione, negli eucarioti con meccanismi più complessi) e corregge l'errore.

### Riparazione del Danno a Doppio Filamento (DSB)

Le rotture del doppio filamento (DSB) sono estremamente pericolose.

* **NHEJ (Non-Homologous End Joining):** Unione delle Estremità Non Omologhe. Meccanismo principale nelle cellule eucariotiche, attivo in tutte le fasi del ciclo cellulare. È "rapido e sporco": lega direttamente le due estremità spezzate. Spesso è mutageno, in quanto può introdurre piccole inserzioni o delezioni ($indels$) nel punto di giunzione.
* **HR (Homologous Recombination):** Ricombinazione Omologa. Meccanismo ad alta fedeltà, attivo solo nelle fasi S e G2 del ciclo cellulare, poiché richiede la presenza del cromatidio fratello come stampo per la riparazione. Garantisce una riparazione accurata e non mutagena.

---

## Correlazioni con l'Invecchiamento Cellulare

L'accumulo di danno al DNA è una delle principali cause (secondo la *teoria del danno*) dell'invecchiamento cellulare e dell'organismo.

1.  **Instabilità Genomica:** Con il tempo, l'efficienza dei sistemi di riparazione può diminuire, o il tasso di danno può superare la capacità di riparazione.
2.  **Accumulo di Mutazioni:** L'accumulo di mutazioni (sia puntiformi che cromosomiche) nel DNA somatico può compromettere la funzione cellulare.
3.  **Senescenza Cellulare:** Cellule con un danno al DNA eccessivo (specialmente DSB) attivano un blocco permanente del ciclo cellulare (senescenza) o vanno in apoptosi. L'accumulo di cellule senescenti contribuisce all'invecchiamento dei tessuti.
4.  **Accorciamento dei Telomeri:** I telomeri, le regioni terminali dei cromosomi, si accorciano ad ogni divisione cellulare. Questo processo (una forma di "danno" programmato) protegge dalla perdita di informazione genica, ma quando i telomeri diventano criticamente corti, la cellula entra in senescenza. I sistemi di riparazione (come NHEJ) possono erroneamente fondere telomeri corti, portando a instabilità cromosomica.