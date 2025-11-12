La **[[Trascrizione]]** negli [[Eucarioti]] è il processo di sintesi di [[RNA]] a partire da uno stampo di [[DNA]], catalizzato da enzimi chiamati [[RNA Polimerasi]]. A differenza dei procarioti che ne hanno una sola, gli eucarioti ne possiedono tre distinte, ognuna specializzata nella trascrizione di diverse classi di geni.

## Le Tre RNA Polimerasi Eucariotiche

| Polimerasi | Localizzazione | Geni Trscritti (Prodotti Principali) | Sensibilità all'$\alpha$-amanitina* |
| :--- | :--- | :--- | :--- |
| **[[RNA Polimerasi I]]** | Nucleolo | Maggior parte dei geni per **[[rRNA]]** (RNA ribosomiali): $18S$, $5.8S$, $28S$ | Insensibile |
| **[[RNA Polimerasi II]]** | Nucleoplasma | Tutti i geni che codificano per **proteine** ( $\to$ [[mRNA]]), più alcuni **snRNA**, **snoRNA** e **[[miRNA]]** | **Molto sensibile** (bloccata) |
| **[[RNA Polimerasi III]]** | Nucleoplasma | Geni per **[[tRNA]]** (RNA transfer), **rRNA $5S$**, e altri piccoli RNA (es. *U6 snRNA*) | Sensibile a concentrazioni elevate |

*\* (L' $\alpha$-amanitina è una tossina fungina (es. *Amanita phalloides*) usata sperimentalmente per distinguere le polimerasi)*

## Inizio della Trascrizione (Polimerasi II)

Il processo di inizio per la Pol II (la più studiata, data la sua centralità) è complesso e richiede l'assemblaggio di un grande complesso proteico sul promotore.

### 1. Fattori di Trascrizione Generali (GTFs)
La RNA Pol II non è in grado di riconoscere da sola il promotore. Richiede un set di proteine chiamate **[[Fattori di Trascrizione Generali]]** (GTFs), designate come $TFII$ (Triscription Factor for Pol II), es: $TFIIA, TFIIB, TFIID...$

### 2. Promotore (Core Promoter) e TATA Box
Il **Promotore Basale** (Core Promoter) è la regione minima di DNA sufficiente per avviare la trascrizione basale.
* Contiene il sito di inizio della trascrizione ($+1$).
* Spesso ($\approx 25\%$ dei geni) contiene una sequenza consenso chiamata **[[TATA Box]]** (sequenza $\approx 5'-TATAAA-3'$), localizzata a circa $-25$/$-30$ $bp$ a monte del sito $+1$.

L'assemblaggio del **Complesso di Pre-Inizio** (PIC) inizia quando **$TFIID$** (un GTF) lega la TATA Box tramite una sua subunità, la **TBP** (TATA-Binding Protein). Questo legame "piega" il DNA e funge da piattaforma per reclutare gli altri GTFs e, infine, la RNA Polimerasi II.

### 3. Promotori Prossimali e Distali (Regolazione)
Oltre al promotore basale, l'efficienza della trascrizione è determinata da elementi *in cis* aggiuntivi:
* **Elementi Prossimali al Promotore**: Sequenze (es. *CAAT box*, *GC box*) situate vicine (entro $\approx -100/-200$ $bp$) al promotore. Legano fattori di trascrizione specifici che aumentano l'efficienza di assemblaggio del PIC.
* **Elementi Distali: [[Enhancer]] e [[Silencer]]**:
    * **Enhancer (Intensificatori)**: Elementi *in cis* che possono trovarsi a migliaia di $bp$ di distanza (a monte, a valle, o in un introne). Legano proteine *Attivatori*.
    * **Silencer (Silenziatori)**: Simili agli Enhancer, ma legano proteine *Repressori*.

Questi elementi distali funzionano "ripiegando" il DNA (DNA looping) per portare i fattori specifici (Attivatori/Repressori) a contatto fisico con il complesso di inizio sul promotore, modulandone l'attività.



## Fattori di Trascrizione Specifici

Mentre i GTFs sono *generali* (richiesti da tutti i geni Pol II), i **Fattori di Trascrizione Specifici** sono proteine (Attivatori o Repressori) espresse solo in certi tipi cellulari o in risposta a certi stimoli. Essi determinano **quali** geni accendere o spegnere.

Questi fattori hanno tipicamente due domini:
1.  **Dominio di Legame al DNA (DBD)**: Riconosce una sequenza specifica (enhancer/silencer). Es. *Zinc finger*, *Leucine zipper*.
2.  **Dominio di Attivazione/Repressione (AD)**: Interagisce con altri componenti (es. i GTFs, co-attivatori come i complessi di rimodellamento della cromatina, o la stessa Pol II).

### Esempio: Recettori degli Ormoni Steroidei
Questo è un esempio classico di come un segnale esterno attiva un TF specifico.
* Gli **[[Ormoni Steroidei]]** (es. cortisolo, estrogeni) sono lipofili e possono attraversare la membrana cellulare.
* Nel citoplasma (o nel nucleo), l'ormone si lega al suo **Recettore** specifico (es. Recettore dei Glucocorticoidi, GR).
* *Senza* ormone, il recettore è inattivo (spesso legato a chaperonine come $Hsp90$ nel citoplasma).
* Il legame con l'ormone causa un cambiamento conformazionale:
    1.  Il recettore si stacca dalla $Hsp90$.
    2.  Spesso dimerizza.
    3.  Espone un segnale di localizzazione nucleare (NLS) ed entra nel nucleo.
* Nel nucleo, il complesso *Ormone-Recettore* agisce come un **Fattore di Trascrizione Specifico (Attivatore)**.
* Il suo DBD si lega a sequenze specifiche sul DNA (chiamate *Hormone Response Elements*, HREs, che sono Enhancer).
* Il suo AD recluta co-attivatori (es. **HAT**) che acetilano gli istoni, aprono la cromatina e attivano la trascrizione dei geni bersaglio.
  
## Elongazione (Allungamento)

Una volta che il PIC è assemblato, l'inizio effettivo richiede l'azione di un GTF (TFIIH) che ha attività:
1.  **Elicasica**: Svolge il DNA al promotore.
2.  **Chinasica**: **Fosforila** la coda C-terminale (CTD) della RNA Polimerasi II.

La fosforilazione della CTD è il segnale che "rilascia" la Polimerasi dal promotore (promoter escape) e la fa passare alla fase di **elongazione**.
Durante l'elongazione, la Pol II si muove lungo il filamento stampo ($3' \to 5'$) sintetizzando il **pre-mRNA** in direzione $5' \to 3'$. Man mano che avanza, recluta sulla sua coda (la CTD fosforilata) i fattori necessari per la maturazione dell'mRNA:
* Enzimi per il **Capping $5'$** (avviene quasi subito).
* Complessi dello **[[Splicing]]** (per rimuovere gli introni).
  
  

## Terminazione

La terminazione differisce tra le tre polimerasi.

* **Pol I**: Un fattore di terminazione specifico riconosce un segnale sul DNA.
* **Pol III**: Termina dopo aver trascritto una sequenza ricca di $U$ (simile ai procarioti).
* **Pol II**: È un processo complesso legato alla maturazione $3'$.
    1.  La Pol II trascrive oltre il punto finale del gene.
    2.  Trascrive un segnale (nel pre-mRNA) chiamato **Segnale di Poliadenilazione** (es. $AAUAAA$).
    3.  Questo segnale viene riconosciuto da enzimi (un'endonucleasi) che **tagliano** l'mRNA a valle di quel sito.
    4.  Sul $3'$ ora libero dell'mRNA viene aggiunta la **Coda di Poli-A** (Poliadenilazione).
    5.  La Polimerasi II, che sta ancora trascrivendo a valle del taglio, viene raggiunta e "smontata" (es. modello "Torpedo"), terminando la trascrizione.