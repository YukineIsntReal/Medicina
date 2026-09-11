Questa classe di recettori possiede un dominio intracellulare che ha un'**attività enzimatica intrinseca** o che è strettamente associato a un enzima che esso attiva.

La classe più vasta e importante è quella dei **Recettori Tirosin-Chinasici (RTKs)**.

---

## Recettori Tirosin-Chinasici (RTKs)

* **Struttura:** Sono tipicamente proteine transmembrana a singolo passo. Possiedono:
    1.  Un dominio extracellulare per il legame del ligando.
    2.  Un singolo elicoidale dominio transmembrana.
    3.  Un dominio citoplasmatico che contiene l'attività enzimatica **Tirosin-Chinasica** (cioè, fosforila residui specifici di Tirosina, $Tyr$ o $Y$).

* **Meccanismo di Attivazione (Generale):**
    1.  **Legame del Ligando:** Il ligando (spesso un fattore di crescita, che è un dimero) lega i domini extracellulari.
    2.  **Dimerizzazione:** Il legame induce i recettori (che erano monomeri inattivi) a formare un **dimero** (o oligomero).
    3.  **Trans-Autofosforilazione:** La dimerizzazione avvicina i domini chinasici intracellulari. Ogni dominio chinasico fosforila l'altro monomero su specifici residui di Tirosina ($Tyr$) presenti sulla "coda" citoplasmatica.
    4.  **Creazione di Siti di Attracco (Docking Sites):** Le tirosine appena fosforilate (ora $pY$) agiscono come siti di legame ad alta affinità per numerose proteine di segnalazione intracellulari.

---

## La Via Ras-MAP Chinasi (Via della Proliferazione)

Questa è la cascata di segnalazione "classica" attivata dagli RTK per indurre la **proliferazione cellulare**.

1.  **Reclutamento dell'Adattatore:**
    * Una proteina **adattatrice** (es. **Grb2**) riconosce e lega i siti $pY$ sul recettore attivato tramite il suo dominio **SH2** (Src Homology 2).
    * Grb2 porta con sé (tramite i suoi domini SH3) un'altra proteina: **Sos** (un **GEF** per Ras).

2.  **Attivazione di Ras:**
    * Il complesso RTK-Grb2-Sos porta Sos vicino alla membrana.
    * **Ras** è una **proteina G monomerica** (una piccola GTPasi) ancorata alla membrana, inattiva (legata a GDP).
    * Sos (il GEF) stimola Ras a rilasciare il GDP e a legare il **GTP**.
    * **Ras-GTP** è la forma **attiva**.

3.  **La Cascata delle MAP Chinasi (MAPK):**
    * Ras-GTP (attivo) recluta e attiva la prima chinasi della cascata, **Raf** (che è una **MAPKKK** - MAP Kinase Kinase Kinase).
    * Raf (attiva) fosforila e attiva **MEK** (una **MAPKK**).
    * MEK (attiva) fosforila e attiva **Erk** (una **MAPK** - Mitogen-Activated Protein Kinase).
    * La cascata (Raf $\rightarrow$ MEK $\rightarrow$ Erk) agisce come un amplificatore e un filtro.

4.  **Risposta Cellulare:**
    * **Erk** (attiva) entra nel nucleo.
    * Nel nucleo, Erk fosforila e attiva **fattori di trascrizione** (es. c-Myc, c-Fos, c-Jun).
    * Questi fattori attivano la trascrizione dei geni necessari per la divisione cellulare (es. le Cicline), promuovendo l'ingresso nel ciclo cellulare.

* **Spegnimento:** L'idrolisi del GTP a GDP da parte di Ras (accelerata da una proteina **GAP** specifica, come **NF1**) inattiva Ras e spegne la cascata.

---

## Oncogeni e Trasduzione del Segnale

Molti componenti delle vie di trasduzione del segnale (come Ras-MAPK) sono codificati da geni chiamati **proto-oncogeni**. Una mutazione che causa un **guadagno di funzione** (iperattivazione) in un proto-oncogene lo trasforma in un **oncogene**, contribuendo allo sviluppo del cancro.

* **Esempi:**
    * **RTK (Recettori):** Mutazioni nel recettore *EGF-R* (o *HER2*) possono causare la dimerizzazione e l'attivazione in assenza di ligando (segnale di "cresci!" costante).
    * **Ras:** Mutazioni puntiformi nel gene *RAS* (presenti in $\approx 30\%$ dei tumori umani) bloccano la sua capacità di idrolizzare il GTP (diventa insensibile alle GAP). **Ras rimane costitutivamente attivo** (sempre legato a GTP), tenendo la via MAPK perennemente accesa.
    * **Chinasi:** Mutazioni in *B-Raf* (una forma di Raf, comune nel melanoma) la rendono un'enzima sempre attivo, indipendentemente da Ras.

---

## La Segnalazione dei Fosfoinositidi (Via PI3K-Akt / Sopravvivenza)

Gli RTK non attivano solo la via Ras, ma anche una via parallela cruciale per la **sopravvivenza** e la **crescita** cellulare.

1.  **Attivazione di PI3K:**
    * L'RTK attivato (tramite i suoi $pY$) recluta e attiva la **PI 3-chinasi (PI3K)**.

2.  **Produzione del Secondo Messaggero Lipidico:**
    * PI3K è una chinasi che fosforila un lipide di membrana, il **PIP$_2$** (Fosfatidilinositolo 4,5-bisfosfato).
    * PI3K aggiunge un fosfato in posizione 3 $\rightarrow$ **PIP$_3$** (Fosfatidilinositolo 3,4,5-trisfosfato).
    * Il PIP$_3$ rimane in membrana e agisce da **sito di attracco** per altre proteine.

3.  **Attivazione di Akt (PKB):**
    * Il PIP$_3$ recluta due chinasi: **PDK1** e **Akt** (detta anche Protein Chinasi B o PKB).
    * Essere portate a contatto sulla membrana permette a PDK1 (e a un'altra chinasi, mTORC2) di fosforilare e attivare pienamente **Akt**.

4.  **Effetto Anti-Apoptotico (Sopravvivenza):**
    * **Akt** è il fulcro della sopravvivenza cellulare.
    * Uno dei suoi bersagli è la proteina pro-apoptotica **Bad**.
    * Akt fosforila Bad $\rightarrow$ Bad viene sequestrato da una proteina 14-3-3.
    * Bad non può più inibire **Bcl-2** (una proteina *anti*-apoptotica).
    * Risultato: La via dell'apoptosi (morte cellulare programmata) è **soppressa**.

* **Spegnimento:** La via è spenta dall'enzima **PTEN**, una fosfatasi che rimuove il fosfato in pos. 3 dal PIP$_3$, riconvertendolo in PIP$_2$. *PTEN* è un importantissimo **oncosoppressore** (la sua perdita di funzione porta all'attivazione costitutiva di Akt).

---

## Esempi Specifici di RTK

### 1. Recettore per l'EGF (Epidermal Growth Factor)
* È il prototipo di RTK.
* Il legame con EGF attiva potentemente la via **Ras-MAPK**, portando a una forte risposta **proliferativa**.

### 2. Recettore per l'Insulina
* È un RTK atipico: è un **tetramero** ($\alpha_2\beta_2$) pre-assemblato, anche senza ligando.
* Il legame con l'insulina causa un cambiamento conformazionale che attiva la trans-autofosforilazione.
* **Non** usa direttamente Grb2. La sua coda $pY$ recluta una grande proteina "impalcatura" (scaffold) chiamata **IRS-1** (Insulin Receptor Substrate 1).
* L'RTK fosforila IRS-1 su *molteplici* tirosine.
* **IRS-1 (ora attivo)** diventa la piattaforma centrale che recluta:
    1.  **Grb2 $\rightarrow$ Sos $\rightarrow$ Ras** (spiegando l'effetto *mitogeno* dell'insulina).
    2.  **PI 3-chinasi (PI3K)** (questa è la via *metabolica* principale!).
* L'attivazione di **PI3K $\rightarrow$ Akt** da parte dell'insulina:
    * Promuove la **traslocazione delle vescicole contenenti GLUT4** (il trasportatore del glucosio) sulla membrana plasmatica (in muscolo e adipe).
    * Causa un massiccio aumento dell'assorbimento (uptake) di glucosio dal sangue.
    * Attiva la Glicogeno Sintasi (stoccaggio del glucosio).