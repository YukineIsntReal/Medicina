# 

## Il Concetto di Gene

Il concetto di **gene** si è evoluto nel tempo. Se un tempo era definito come l'unità ereditaria che determina un singolo carattere (approccio Mendeliano), la definizione molecolare moderna è più precisa.

Un **gene** è una sequenza specifica di nucleotidi lungo una molecola di [[DNA]] (o [[RNA]] in alcuni virus) che funge da unità funzionale. Questa unità contiene le istruzioni per sintetizzare un prodotto funzionale, che può essere:
1.  Una **catena polipeptidica** (che diventerà una [[Proteina]]).
2.  Una molecola di **[[RNA]] funzionale** (non tradotta), come l'[[rRNA]] (RNA ribosomiale) o il [[tRNA]] (RNA transfer).

Un gene non include solo la sequenza codificante (CDS - CoDing Sequence), ma anche tutte le sequenze di DNA necessarie per la sua corretta espressione: le regioni regolative (come i [[promotori]]) e le sequenze non codificanti (come gli [[introni]]).

## Anatomia del Gene: Procarioti vs Eucarioti

L'organizzazione genica differisce profondamente tra procarioti ed eucarioti.

### Il Gene Procariotico e l'Operone (Policistronico)

Nei [[Procarioti]], i geni che codificano per proteine coinvolte in una stessa via metabolica sono spesso raggruppati e trascritti insieme sotto il controllo di un singolo promotore.

* **Geni Policistronici**: Un singolo [[mRNA]] (chiamato *mRNA policistronico*) trasporta l'informazione per **più** proteine diverse.
* **Operone**: L'intera unità funzionale (promotore + regioni regolative + geni strutturali) è chiamata **[[Operone]]**. Un esempio classico è l'[[Operone Lac]].
* **Struttura**:
    * **[[Promotore]]**: Sito di legame per la [[RNA Polimerasi]].
    * **Operatore**: Sequenza regolativa (elemento *in cis*) dove si legano proteine regolatrici (repressori).
    * **Geni Strutturali**: Le sequenze codificanti per le varie proteine (es. *lacZ, lacY, lacA*).
* **Caratteristiche**: I geni procariotici sono quasi interamente codificanti, privi di introni. La trascrizione e la traduzione sono accoppiate (avvengono simultaneamente).



[Image of prokaryotic operon structure]


### Il Gene Eucariotico (Monocistronico)

Negli [[Eucarioti]], i geni sono strutturalmente più complessi e la loro regolazione è più fine.

* **Geni Monocistronici**: Un singolo gene viene trascritto in un mRNA che codifica (generalmente) per **una sola** proteina.
* **Geni Interrotti (Split Genes)**: La sequenza codificante è interrotta da regioni non codificanti.
* **Struttura**:
    * **Regioni Regolative**: (Vedi sezione successiva). Include il [[Promotore]] e altri elementi come enhancers/silencers.
    * **Sito di Inizio della Trascrizione ($+1$)**: Il punto in cui inizia la sintesi dell'RNA.
    * **$5'$ UTR (Untranslated Region)**: Regione trascritta ma non tradotta, posta all'inizio dell'mRNA. Contiene segnali per l'aggancio del [[ribosoma]] (es. sequenza di Kozak).
    * **[[Esoni]]**: Le sequenze che vengono *espresse*, ovvero che contengono l'informazione codificante (o che fanno parte delle UTR).
    * **[[Introni]]**: Le sequenze *intervenienti*, non codificanti, che vengono rimosse dal trascritto primario di RNA (pre-mRNA) durante il processo di **[[Splicing]]**.
    * **$3'$ UTR**: Regione trascritta ma non tradotta alla fine dell'mRNA. Contiene segnali per la stabilità dell'mRNA e il segnale di poliadenilazione (es. $AAUAAA$) che determina l'aggiunta della coda di Poli-A.



Nei geni eucariotici, il trascritto primario (pre-mRNA) deve subire una **maturazione** (Capping al $5'$, Splicing degli introni, Poliadenilazione al $3'$) nel nucleo prima di essere esportato nel citoplasma per la traduzione.

## Promotori ed Elementi Regolativi in Cis

La regolazione genica dipende dall'interazione tra *elementi in trans* (fattori mobili, come le proteine [[Fattori di Trascrizione]]) ed *elementi in cis* (sequenze di DNA).

Gli **elementi regolativi *in cis*** sono sequenze di DNA localizzate sullo **stesso cromosoma** (e spesso molto vicine) del gene che controllano.

1.  **[[Promotori]]**:
    * Sono elementi *in cis* essenziali, posti immediatamente a monte ($upstream$) del sito di inizio della trascrizione.
    * È il sito dove si assembla il complesso di trascrizione basale, inclusa la **[[RNA Polimerasi]]**.
    * *Procarioti*: Contengono sequenze consenso come la *Pribnow box* (a $-10$) e la sequenza a $-35$.
    * *Eucarioti*: (Core promoter) Spesso contengono la **TATA box** (a circa $-25/-30$), legata dalla proteina TBP (TATA-Binding Protein), fondamentale per il posizionamento della Polimerasi II.

2.  **Enhancers (Intensificatori)**:
    * Elementi *in cis* che **aumentano** drasticamente il livello di trascrizione di un gene.
    * Legano proteine *attivatori* (fattori di trascrizione).
    * Caratteristica unica: possono essere localizzati molto lontano dal promotore (migliaia di $bp$), sia a monte, sia a valle, sia *all'interno* di un introne.
    * Funzionano "ripiegando" il [[DNA]] (looping) per mettere gli attivatori legati all'enhancer a contatto fisico con il complesso del promotore. 

3.  **Silencers (Silenziatori)**:
    * Simili agli enhancers, ma legano proteine *repressori* che **inibiscono** la trascrizione.

4.  **Operatori** (Procarioti):
    * Elementi *in cis*, tipici degli operoni, spesso sovrapposti al promotore.
    * Legano proteine repressori specifiche (es. il repressore *lac* si lega all'operatore *lac*), bloccando fisicamente l'accesso della RNA Polimerasi.