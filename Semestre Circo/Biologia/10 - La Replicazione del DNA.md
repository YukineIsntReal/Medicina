La **replicazione del DNA** è il processo biologico fondamentale attraverso cui una cellula duplica il proprio [[DNA]] prima della divisione cellulare ([[Mitosi]] o [[Meiosi]]). È un processo che deve essere estremamente preciso e coordinato per garantire la stabilità del genoma.

## Il Meccanismo Semiconservativo

La replicazione del DNA è **semiconservativa**, come dimostrato dagli esperimenti di Meselson e Stahl.
Questo significa che ogni nuova molecola di DNA prodotta è un ibrido, composto da:
1.  Un filamento **parentale** (vecchio), che funge da stampo.
2.  Un filamento **neo-sintetizzato** (nuovo), complementare allo stampo.

## Origini di Replicazione e Forcella Replicativa

Il processo non inizia in punti casuali, ma in siti specifici chiamati **Origini di Replicazione** ($Ori$).
* **[[Procarioti]]**: Possiedono tipicamente una singola origine (es. *OriC* in *E. coli*).
* **[[Eucarioti]]**: Hanno genomi molto più grandi e lineari, quindi necessitano di **molteplici origini di replicazione** (migliaia) per duplicare l'intero genoma in un tempo ragionevole.

In questi siti, proteine specifiche (l'**Iniziatore**, es. DnaA nei procarioti, il complesso **ORC** - Origin Recognition Complex - negli eucarioti) legano il DNA e reclutano altre proteine per formare il **complesso d'inizio**.
L'apertura della doppia elica in questi punti crea due strutture a forma di Y, chiamate **forcelle replicative**, che si muovono in direzioni opposte (replicazione bidirezionale).

## Lo Srotolamento del DNA: Elicasi e Topoisomerasi

Perché i filamenti possano fungere da stampo, la doppia elica deve essere srotolata.

* **[[DNA Elicasi]]**: È un enzima ATP-dipendente che si muove lungo il DNA e "rompe" i legami idrogeno tra le basi azotate, separando fisicamente i due filamenti.
* **[[Topoisomerasi]]**: Lo srotolamento da parte dell'elicasi introduce un superavvolgimento (tensione torsionale) nel DNA a monte della forcella. Le topoisomerasi (come la *GIRASI* nei procarioti, o Topo I e Topo II negli eucarioti) risolvono questa tensione "tagliando" e "ricucendo" i filamenti di DNA, permettendo alla replicazione di procedere.

Una volta separati, i singoli filamenti vengono stabilizzati da proteine (SSB, Single-Strand Binding proteins) che impediscono loro di riassociarsi.

## La Primasi e l'Innesco (Primer)

Le [[DNA Polimerasi]] (gli enzimi principali della sintesi) non sono in grado di iniziare a sintetizzare un filamento *de novo*. Hanno bisogno di un'estremità $3'-OH$ libera a cui aggiungere nucleotidi.

Questo "innesco" è fornito dalla **[[Primasi]]**, un tipo speciale di [[RNA Polimerasi]] che sintetizza un corto frammento di [[RNA]] (circa $5-10$ nucleotidi) complementare allo stampo. Questo frammento è chiamato **primer** (o innesco).

## Le DNA Polimerasi e Correzione degli Errori

Le **[[DNA Polimerasi]]** sono gli enzimi responsabili dell'allungamento del nuovo filamento. Leggono lo stampo e aggiungono deossiribonucleotidi trifosfato ($dNTPs$) complementari all'estremità $3'-OH$ del primer (o del filamento in crescita).

La sintesi avviene sempre in direzione **$5' \to 3'$**.

Le DNA Polimerasi principali sono:
* Procarioti: $Pol III$ (sintesi principale), $Pol I$ (rimozione primer e riparazione).
* Eucarioti: $Pol \delta$ (filamento ritardato), $Pol \epsilon$ (filamento guida), $Pol \alpha$ (associata alla primasi, inizia la sintesi).

### Correzione degli Errori (Proofreading)
Le DNA Polimerasi replicative (come $Pol III, \delta, \epsilon$) sono estremamente precise. Oltre all'attività polimerasica $5' \to 3'$, possiedono un'**attività esonucleasica $3' \to 5'$** (proofreading o "correzione di bozze").
Se la polimerasi inserisce un nucleotide errato, rileva la distorsione, torna indietro (attività $3' \to 5'$), rimuove l'errore e inserisce il nucleotide corretto prima di procedere.

## Filamento Continuo e Discontinuo (Frammenti di Okazaki)

La natura antiparallela del DNA ($5'-3'$ e $3'-5'$) e il fatto che le polimerasi sintetizzino solo in $5' \to 3'$ pongono un problema alla forcella replicativa.

1.  **Filamento Guida (Leading strand)**:
    * È il filamento sintetizzato sullo stampo $3' \to 5'$.
    * La sua sintesi è **continua**, poiché la polimerasi segue la stessa direzione di apertura della forcella.
    * Richiede un solo primer iniziale.
    * 

[Image of DNA leading strand synthesis]


2.  **Filamento Ritardato (Lagging strand)**:
    * È il filamento sintetizzato sullo stampo $5' \to 3'$.
    * La polimerasi deve muoversi in direzione *opposta* all'apertura della forcella.
    * La sintesi è **discontinua**: la primasi sintetizza un nuovo primer man mano che la forcella si apre, e la polimerasi sintetizza piccoli frammenti all'indietro.
    * Questi frammenti sono chiamati **Frammenti di Okazaki** (lunghi $1000-2000$ $bp$ nei procarioti, $100-200$ $bp$ negli eucarioti).
    * 

[Image of DNA lagging strand synthesis]


## Rimozione dell'RNA e DNA Ligasi

Alla fine della sintesi, il filamento ritardato è un mosaico di DNA e primer a RNA.
1.  **Rimozione del Primer**: I primer a RNA vengono rimossi (negli eucarioti da enzimi come *RNasi H* e *FEN1*).
2.  **Sostituzione**: La DNA Polimerasi (es. $Pol \delta$ eucarioti, $Pol I$ procarioti) riempie il "buco" (gap) lasciato dal primer, usando il $3'-OH$ del frammento di Okazaki precedente.
3.  **Saldatura**: Rimane un'ultima interruzione ("nick") nello scheletro zucchero-fosfato tra il $3'-OH$ del nuovo DNA e il $5'-P$ del frammento successivo. Questo legame fosfodiesterico è creato dalla **[[DNA Ligasi]]** (un processo che richiede energia, ATP negli eucarioti).

## La Funzione dei Telomeri e delle Telomerasi (Solo Eucarioti)

Negli eucarioti, i cromosomi sono lineari. Il meccanismo di replicazione del filamento ritardato crea un problema: il primer a RNA all'estremità $5'$ del filamento neosintetizzato, una volta rimosso, non può essere sostituito (manca un $3'-OH$ a cui attaccarsi).
Questo porta a un accorciamento progressivo del cromosoma ad ogni divisione cellulare (il **"problema della replicazione terminale"**).

Per proteggere le regioni codificanti da questo accorciamento, le estremità dei cromosomi (i **[[Telomeri]]**) sono composte da lunghe sequenze di DNA ripetute e non codificanti (nell'uomo: $TTAGGG$).

Per contrastare questo accorciamento in alcune cellule, esiste l'enzima **[[Telomerasi]]**.
* È una **trascrittasi inversa**: un enzima composto da una parte proteica (TERT) e uno stampo di RNA (TERC).
* La telomerasi utilizza il suo stampo di RNA per **allungare l'estremità $3'$ del filamento parentale** (lo stampo del filamento ritardato), aggiungendo nuove ripetizioni telomeriche.
* Questo permette alla primasi di sintetizzare un nuovo primer su questa estensione, consentendo alla DNA polimerasi di completare la replicazione senza perdita netta di materiale genetico.



La telomerasi è attiva principalmente:
* Nelle cellule germinali (per garantire la lunghezza telomerica alla prole).
* Nelle cellule staminali.
* In molte cellule tumorali (che acquisiscono immortalità replicativa).

## I Telomeri e la Senescenza Replicativa

Nella maggior parte delle cellule somatiche umane, l'attività della telomerasi è molto bassa o assente.
Ad ogni divisione cellulare, i telomeri si accorciano. Quando raggiungono una lunghezza critica, la cellula interpreta questa estremità come un danno al DNA (una rottura a doppio filamento).
Questo innesca una risposta (mediata da $p53$ e $pRb$) che porta a un arresto permanente del ciclo cellulare, uno stato chiamato **[[Senescenza Replicativa]]** (o limite di Hayflick).
Questo meccanismo è considerato una forma di soppressione tumorale (impedisce a cellule potenzialmente danneggiate di proliferare all'infinito), ma contribuisce anche all'invecchiamento cellulare dell'organismo.