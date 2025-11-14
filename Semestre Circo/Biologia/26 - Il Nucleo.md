Il **nucleo** è l'organello distintivo della cellula eucariotica. Contiene la quasi totalità del materiale genetico (DNA) organizzato in **cromatina**. È la sede di processi vitali come la **replicazione** del DNA e la **trascrizione** (sintesi di RNA). Il nucleo è un compartimento altamente dinamico, separato dal citosol ma in costante e selettiva comunicazione con esso.

---

## 1. Struttura del Nucleo

### 1.1 L'Involucro Nucleare
Non è una singola membrana, ma un **doppio bilayer fosfolipidico** (due membrane concentriche):
1.  **Membrana Esterna:** È in continuità fisica e funzionale con il [[!|Reticolo Endoplasmatico]] (RE). La sua superficie citosolica è spesso costellata di [[Ribosomi]].
2.  **Membrana Interna:** Possiede proteine di legame uniche (es. LBR, Emerina) che ancorano la **lamina nucleare** e la cromatina periferica (eterocromatina).
3.  **Spazio Perinucleare:** Lo spazio tra le due membrane, in continuità con il lume del RE.

### 1.2 La Lamina Nucleare
È un fitto reticolo ($\approx$ 10-20 nm) di **filamenti intermedi** (proteine chiamate **Lamine A, B, C**) che riveste la faccia interna della membrana nucleare interna.
* **Funzioni:** Fornisce supporto strutturale all'involucro, funge da sito di ancoraggio per la cromatina e partecipa all'organizzazione del nucleo.

### 1.3 Il Nucleolo
È la struttura più prominente all'interno del nucleo. Non è delimitato da membrana.
* **Funzione:** È la "fabbrica" dei ribosomi. È la sede della:
    1.  Trascrizione degli **RNA ribosomiali (rRNA)** (ad eccezione del 5S rRNA).
    2.  Processamento (maturazione) degli rRNA.
    3.  Assemblaggio degli rRNA con le proteine ribosomiali (importate dal citosol) per formare le **subunità ribosomiali** (maggiore 60S e minore 40S).

### 1.4 Il Complesso del Poro Nucleare (NPC)
L'involucro nucleare è perforato da migliaia di **Pori Nucleari**. Non sono semplici buchi, ma strutture proteiche enormi e complesse ($>$120 MDa).
* **Struttura:** Ogni NPC è formato da $\approx$ 30-50 proteine diverse, chiamate **Nucleoporine (NUPs)**. Ha una simmetria ottagonale con strutture ad anello (sul lato citosolico e nucleare) e un "canestro" (basket) sul lato nucleare.
* **Selettività:**
    * **Diffusione Passiva:** Piccole molecole ($<$ 50-60 kDa) possono diffondere liberamente.
    * **Trasporto Attivo:** Macromolecole (proteine, RNA, subunità ribosomiali) richiedono un trasporto regolato.
* **Barriera Selettiva:** Il canale centrale del poro è riempito di Nucleoporine contenenti **domini FG (Fenilalanina-Glicina)**. Queste sequenze disordinate e idrofobe formano una sorta di "gel" o "setaccio" che impedisce il passaggio non regolato di macromolecole.
---

## 2. Il Trasporto Nucleare

Questo trasporto attivo (che richiede energia) è mediato da una famiglia di recettori di trasporto solubili chiamati **Carioferine** (Importine e Esportine), che legano specifici segnali sulle proteine "cargo" e interagiscono con i domini FG delle NUPs per attraversare il poro.

### 2.1 Segnali di Indirizzamento
* **NLS (Segnale di Localizzazione Nucleare):** Una sequenza (spesso ricca di amminoacidi basici carichi positivamente, es. $...-Pro-Lis-Lis-Lis-Arg-Lis-Val-...$) che "etichetta" una proteina per l'importazione nel nucleo. **Non viene clivata** dopo l'importazione.
* **NES (Segnale di Esportazione Nucleare):** Una sequenza (spesso ricca di amminoacidi idrofobi, come la $Leucina$) che etichetta una proteina per l'esportazione nel citosol.

### 2.2 Il Motore del Trasporto: Il Ciclo di Ran
L'energia e la **direzionalità** del trasporto non derivano direttamente dall'idrolisi di $ATP$, ma da un gradiente di concentrazione della piccola GTPasi **Ran**.

* **Ran:** Una proteina che agisce come un interruttore molecolare, esistendo in due stati:
    * **Ran-GTP** (forma attiva)
    * **Ran-GDP** (forma inattiva)
* **Gradiente:** Questo gradiente è mantenuto da due regolatori posizionati asimmetricamente:
    * **Ran-GEF (Guanine nucleotide Exchange Factor):** Si trova **solo nel nucleo** (legato alla cromatina). Ricarica Ran-GDP $\rightarrow$ Ran-GTP. $\rightarrow$ **Alta [Ran-GTP] nel Nucleo**.
    * **Ran-GAP (GTPase Activating Protein):** Si trova **solo nel citosol** (legata ai filamenti citosolici del poro). Attiva l'idrolisi: Ran-GTP $\rightarrow$ Ran-GDP. $\rightarrow$ **Alta [Ran-GDP] nel Citosol**.

### 2.3 Meccanismo di Importazione
1.  **Citosol:** Un'**Importina** (recettore di importazione) lega il NLS della proteina cargo.
2.  Il complesso [Importina-Cargo] attraversa il poro interagendo con le NUPs-FG.
3.  **Nucleo:** Ran-GTP (qui abbondante) si lega all'Importina.
4.  Questo legame cambia la conformazione dell'Importina, che **rilascia il cargo** nel nucleo.
5.  Il complesso [Importina-Ran-GTP] torna nel citosol.
6.  **Citosol:** Ran-GAP attiva l'idrolisi. Ran-GTP $\rightarrow$ Ran-GDP. Ran-GDP si stacca dall'Importina.
7.  L'Importina è libera per un nuovo ciclo.

### 2.4 Meccanismo di Esportazione
1.  **Nucleo:** Un'**Esportina** (recettore di esportazione) lega *contemporaneamente* il NES del cargo e **Ran-GTP** (che qui è abbondante). La formazione di questo complesso *ternario* è cooperativa.
2.  Il complesso [Esportina-Cargo-Ran-GTP] attraversa il poro.
3.  **Citosol:** Ran-GAP attiva l'idrolisi. Ran-GTP $\rightarrow$ Ran-GDP.
4.  L'intero complesso si disassembla. Il **cargo viene rilasciato** nel citosol.
5.  L'Esportina (e Ran-GDP) tornano nel nucleo separatamente.



---

## 3. Regolazione dell'Importazione Nucleare

Il trasporto non è solo "on/off", ma finemente regolato. Un metodo comune è *mascherare* o *smascherare* il segnale NLS in risposta a stimoli.

* **Esempio 1: Recettore dei Glucocortoidi (Ormoni Steroidei)**
    * **Senza ormone (Citosol):** Il recettore è inattivo, legato a un complesso inibitore (es. $Hsp90$) che **maschera l'NLS**.
    * **Con ormone:** L'ormone (es. cortisolo) diffonde nella cellula, lega il recettore. Questo causa il distacco dell'inibitore.
    * **NLS Smascherato:** L'Importina ora può legare l'NLS e trasportare il recettore attivo nel nucleo, dove agirà da fattore di trascrizione.

* **Esempio 2: NF-$\kappa$B (Fattore Trascrizionale)**
    * **Stato inattivo (Citosol):** $NF-\kappa B$ è legato al suo inibitore, **$I\kappa B$**. $I\kappa B$ **maschera l'NLS** di $NF-\kappa B$.
    * **Segnale (es. infiammatorio):** Una via di segnalazione attiva una chinasi ($IKK$) che *fosforila* $I\kappa B$.
    * $I\kappa B$ fosforilato viene riconosciuto e **degradato** dal proteasoma.
    * **NLS Smascherato:** $NF-\kappa B$ è libero, lega l'Importina e viene traslocato nel nucleo per attivare i geni della risposta infiammatoria.

* **Esempio 3: SREBP (Controllo Colesterolo)**
    * **Stato inattivo (Membrana ER):** SREBP è una proteina transmembrana ancorata al RE (il suo NLS è nel citosol, ma "bloccato").
    * **Basso Colesterolo:** Un complesso (SREBP-SCAP) migra via vescicole $COPII$ verso l'**Apparato di Golgi**.
    * **Nel Golgi:** Due proteasi (S1P, S2P) tagliano SREBP.
    * **Rilascio:** Il frammento citosolico (contenente l'NLS) viene **rilasciato** dalla membrana.
    * **Importazione:** Il frammento ora solubile lega l'Importina e va nel nucleo per attivare i geni della sintesi di colesterolo.

---

## 4. Trasporto degli RNA (Esportazione)

Gli RNA sono sintetizzati nel nucleo ma (la maggior parte) funzionano nel citosol. Vengono esportati come complessi **Ribonucleoproteici (RNP)**.

* **Subunità Ribosomiali (assemblate nel Nucleolo):**
    * Vengono esportate usando il sistema **Ran-GTP** e specifiche Esportine (es. $Crm1$).

* **tRNA e snRNA (small nuclear):**
    * Usano Esportine specifiche (es. Esportina-t per i $tRNA$) e dipendono da **Ran-GTP**.

* **mRNA (RNA messaggero):**
    * Il loro trasporto è **indipendente da Ran**.
    * È un processo complesso legato alla maturazione (splicing, capping, poliadenilazione).
    * Solo gli mRNA *maturi* vengono esportati. Proteine specifiche (es. complesso **TREX**) legano l'mRNA processato.
    * Un complesso esportatore (es. **NXF1/NXT1**) lega l'mRNA-RNP e interagisce direttamente con le NUPs-FG del poro.
    * **Direzionalità:** Sul lato citosolico, un'elicasi $ATP$-dipendente (es. **Dbp5**) rimuove le proteine esportatrici dall'mRNA, impedendo il re-ingresso e garantendo l'unidirezionalità.