La sintesi sul [[Ribosoma]] produce una catena polipeptidica lineare. Per diventare biologicamente attiva, questa catena deve assumere una specifica e complessa conformazione tridimensionale (3D), chiamata **struttura nativa**. Questo processo è il **ripiegamento proteico** (o *protein folding*).

## L'Importanza del Corretto Ripiegamento

La funzione di una [[Proteina]] (es. catalitica, strutturale, di legame) dipende interamente dalla sua struttura 3D.
* La sequenza primaria (gli amminoacidi) contiene tutta l'informazione necessaria per il corretto ripiegamento (come dimostrato dall'esperimento di Anfinsen).
* *In vivo*, tuttavia, l'ambiente cellulare (il citoplasma) è estremamente affollato ($\approx 300-400$ $g/L$ di macromolecole).
* In questo ambiente, le catene polipeptidiche nascenti (specialmente le loro regioni idrofobiche) tendono ad interagire in modo aspecifico tra loro, portando ad **aggregazione** e **ripiegamento errato** (misfolding).

## Le Proteine Chaperon (Chaperonine)

Per prevenire il misfolding e l'aggregazione, la cellula utilizza una classe di proteine altamente conservate chiamate **Chaperon** (o *Chaperonine*).

Gli chaperon non determinano la struttura finale della proteina (quella è dettata dalla sequenza amminoacidica), ma **assistono** il processo di folding, spesso utilizzando [[ATP]] come fonte di energia.

Esistono diverse famiglie di chaperon:

### 1. Chaperon $Hsp70$ (Heat Shock Protein 70)
* Agiscono **co-traduzionalmente**: si legano alla catena polipeptidica *mentre sta emergendo* dal ribosoma.
* Riconoscono e legano brevi segmenti idrofobici esposti.
* Impediscono il collasso prematuro o l'aggregazione della catena, "tenendola" in uno stato parzialmente dispiegato finché la sintesi non è completa.
* Utilizzano l'idrolisi di ATP per legarsi e staccarsi ciclicamente dal substrato.

### 2. Chaperonine (es. $GroEL/GroES$ nei procarioti; $Hsp60$ negli eucarioti)
* Agiscono **post-traduzionalmente** (dopo che la proteina è stata sintetizzata e rilasciata).
* Formano una complessa struttura a "barile" (doppio anello) composta da più subunità.
* **Meccanismo "Isolation Chamber"**:
    1.  La proteina misfolded (con regioni idrofobiche esposte) viene catturata all'interno della cavità centrale del barile ($GroEL$).
    2.  Un complesso a "coperchio" ($GroES$) si lega, sigillando la proteina all'interno (richiede ATP).
    3.  All'interno di questa "camera di isolamento", protetta dall'ambiente affollato, la proteina ha il tempo e lo spazio per tentare di ripiegarsi correttamente.
    4.  Dopo un ciclo (circa $10$ sec), il coperchio si apre (richiede ATP) e la proteina (ripiegata o meno) viene rilasciata. Se ancora misfolded, può iniziare un nuovo ciclo.



## Gli Errori di Ripiegamento delle Proteine (Misfolding)

Se i sistemi di chaperon falliscono o sono sopraffatti, o se una mutazione destabilizza la proteina, si verifica un ripiegamento errato.
Le proteine *misfolded* espongono regioni idrofobiche ("appiccicose") che portano all'**aggregazione proteica**.

Questi aggregati sono spesso resistenti alla degradazione (proteolisi) e sono tossici per la cellula (proteotossicità), interferendo con le normali funzioni cellulari.
La cellula tenta di eliminare queste proteine tramite il sistema [[Ubiquitina]]-[[Proteasoma]].

Il fallimento di questo controllo di qualità porta all'accumulo di aggregati proteici insolubili, spesso sotto forma di **fibrille amiloidi**. Questo è il meccanismo patogenetico alla base di molte malattie neurodegenerative, note come **Amiloidosi**:
* **Morbo di Alzheimer**: Aggregati di $\beta$-Amiloide (placche) e proteina Tau (grovigli).
* **Morbo di Parkinson**: Aggregati di $\alpha$-sinucleina (Corpi di Lewy).
* **Morbo di Huntington**: Aggregati di huntingtina (dovuti a [[Malattie da espansione di triplette]]).

## Cenni sui Prioni

I **prioni** rappresentano un caso unico e drammatico di errore di ripiegamento con conseguenze *infettive*.
* **Prione**: Acronimo per *Proteinaceous Infectious Only particle* (Particella Infettiva Solamente Proteica). L'agente infettivo è privo di acidi nucleici ([[DNA]] o [[RNA]]).
* **La Proteina $PrP$**: Esiste una proteina cellulare normale ($PrP^C$, *Cellular*), presente sulla superficie dei neuroni, ricca di struttura ad $\alpha$-elica.
* **La Conversione**: Per cause sconosciute (sporadiche, genetiche o per infezione), $PrP^C$ può cambiare conformazione e diventare $PrP^{Sc}$ (*Scrapie*).
    * $PrP^{Sc}$ è la forma patogenica: ha la stessa sequenza amminoacidica, ma una struttura 3D diversa, ricca di **foglietti-$\beta$**.
    * Questa conformazione la rende estremamente resistente alla proteolisi e tendente all'aggregazione.
* **Meccanismo Infettivo (Propagazione)**:
    1.  La $PrP^{Sc}$ (il prione) agisce come uno "stampo" patologico.
    2.  Quando incontra una $PrP^C$ normale, la *induce* (la forza) a cambiare conformazione e a diventare anch'essa $PrP^{Sc}$.
    3.  Questo innesca una reazione a catena esponenziale: le nuove $PrP^{Sc}$ convertono altre $PrP^C$.
    4.  L'accumulo di aggregati di $PrP^{Sc}$ porta alla morte neuronale e all'aspetto "spugnoso" del cervello.



Questo meccanismo è alla base delle **Encefalopatie Spongiformi Trasmissibili** (TSE):
* *Malattia di Creutzfeldt-Jakob* (CJD) nell'uomo.
* *BSE* ("Mucca pazza") nei bovini.
* *Scrapie* nelle pecore.