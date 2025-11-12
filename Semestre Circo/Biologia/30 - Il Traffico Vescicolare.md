Il trasporto tra compartimenti topologicamente equivalenti (come [[Reticolo Endoplasmatico]], [[Apparato di Golgi]], endosomi, lisosomi e membrana plasmatica) avviene tramite **vescicole di trasporto**. Questo processo è un ciclo finemente regolato di:
1.  **Formazione (Gemmazione)**
2.  **Trasporto**
3.  **Attracco, Ormeggio e Fusione**

---

## 1. Formazione delle Vescicole e Proteine di Rivestimento

Le vescicole si formano per gemmazione (budding) da una membrana "donatrice". Questo processo richiede due azioni: **curvare la membrana** e **selezionare il cargo**. Entrambe sono mediate dalle **Proteine di Rivestimento (Coat Proteins)**.

* **Meccanismo Generale:**
    1.  **Reclutamento:** Una piccola **GTPasi** (Sar1 o Arf) viene attivata a $GTP$ (da una GEF specifica) e inserisce un'elica anfipatica nella membrana, iniziando la curvatura.
    2.  **Assemblaggio:** La GTPasi attiva recluta le subunità del *coat* (rivestimento).
    3.  **Selezione Cargo:** Le proteine del *coat* (o i loro adattatori) legano i "segnali di smistamento" presenti sul cargo (sia cargo di membrana che recettori per cargo solubile).
    4.  **Gemmazione:** L'assemblaggio polimerico del *coat* (che ha una sua geometria curva) forza la membrana a invaginarsi e a formare una gemma, che infine si stacca (a volte con l'aiuto di altre proteine come la *dinamina* nel caso della clatrina).
    5.  **Smantellamento (Uncoating):** Subito dopo la gemmazione, la GTPasi idrolizza il $GTP \rightarrow GDP$, cambia conformazione e causa il disassemblaggio del *coat*. La vescicola "nuda" è pronta per il trasporto.

* **I Tre Tipi di Rivestimento:**

    | Rivestimento | GTPasi | Rotta Principale | Esempio Cargo |
    | :--- | :--- | :--- | :--- |
    | **[[COPII]]** | **Sar1** | **Anterograda:** $RE \rightarrow Golgi$ (CGN) | Proteine cargo, enzimi del Golgi, v-SNAREs |
    | **[[COPI]]** | **Arf** | **Retrograda:** $Golgi \rightarrow RE$ (es. recupero KDEL) e Intra-Golgi | Recettore KDEL, v-SNAREs, enzimi residenti del RE |
    | **[[Clatrina]]** | **Arf** | $TGN \rightarrow Endosomi$ <br> $Membrana Plasm. \rightarrow Endosomi$ (Endocitosi) | Enzimi lisosomiali (M6P-R), Recettori di membrana |

* **Nota sulla Clatrina:** La clatrina (che forma una struttura a "triskelion") fornisce solo la forza meccanica per la curvatura. La selezione del cargo è demandata a **Proteine Adattatrici** (es. AP-1, AP-2) che legano i segnali specifici sul cargo *e* la clatrina, facendo da ponte.



---

## 2. Attracco, Ormeggio e Fusione (Specificità del Bersaglio)

Una volta "nuda", la vescicola deve trovare *esclusivamente* la sua membrana "accettrice" corretta. Questo processo avviene in tre fasi ed è garantito da due famiglie di proteine chiave: **Rab** e **SNARE**.



### 2.1 Ruolo delle Proteine Rab (GTPasi)
* **Funzione:** Sono i "codici postali" (address labels) che definiscono l'identità della vescicola e del bersaglio. Esistono $>60$ Rab diverse, ognuna localizzata in un compartimento specifico.
* **Meccanismo:**
    1.  Sulla vescicola è presente una **Rab-GTP** (forma attiva).
    2.  La Rab-GTP viene riconosciuta da un **Fattore di Ormeggio (Tethering factor)** sulla membrana bersaglio.
    3.  **Ormeggio (Tethering):** Questi fattori (spesso proteine lunghe e filamentose) agiscono come "lenze" che "pescano" la vescicola dal citosol (distanza $>$ 25 nm) e la avvicinano alla membrana.

### 2.2 Ruolo delle Proteine SNARE (Fusione)
* **Funzione:** Sono le "cerniere lampo" (zippers) che mediano la fusione fisica delle due membrane.
* **Tipi:**
    * **v-SNARE** (vesicle-SNARE): Si trova sulla membrana della *vescicola* (es. VAMP/Sinaptobrevina).
    * **t-SNARE** (target-SNARE): Si trova sulla membrana *bersaglio* (es. Sintaxina e SNAP-25).
* **Meccanismo:**
    1.  **Attracco (Docking):** Dopo l'ormeggio (Tethering), la v-SNARE sulla vescicola si appaia strettamente con le t-SNARE sul bersaglio (distanza $< 10$ nm).
    2.  **Fusione (Zippering):** I domini elicoidali delle v-SNARE e t-SNARE si avvolgono strettamente gli uni sugli altri, formando un **complesso *trans*-SNARE** (un fascio di 4 eliche) estremamente stabile.
    3.  Questo processo "strizza" letteralmente le due membrane, espellendo le molecole d'acqua interposte (superando la barriera di idratazione) e forzando la fusione dei due doppi strati lipidici, creando un poro di fusione che si allarga e rilascia il contenuto della vescicola.

### 2.3 Ruolo di NSF e SNAPs (Riciclo)
* **Problema:** Dopo la fusione, le v-SNARE e t-SNARE sono "incastrate" in un complesso *cis*-SNARE (ora entrambe sulla membrana bersaglio) e devono essere separate per essere riutilizzate.
* **Soluzione:**
    1.  **SNAPs** (Soluble NSF Attachment Proteins) riconoscono e legano il complesso *cis*-SNARE.
    2.  **NSF** (N-ethylmaleimide-sensitive fusion protein) si lega alle SNAPs.
    3.  NSF è una **$ATP$asi** (un motore molecolare). Utilizza l'energia dell'idrolisi dell'**$ATP$** per "svolgere" attivamente (disassemblare) il complesso SNARE.
    4.  La v-SNARE viene riciclata (spesso tramite vescicole COPI) al compartimento donatore, e le t-SNARE sono pronte per un nuovo ciclo di fusione.

---

## 3. Il Ruolo dei Fosfoinositidi (PIPs)

I Fosfoinositidi (PIPs) sono fosfolipidi (derivati del Fosfatidilinositolo) che agiscono come **indicatori di identità della membrana**.

* **Come funzionano:** L'anello inositolo (la testa polare) può essere fosforilato in diverse posizioni (3, 4, 5) da specifiche *chinasi* e *fosfatasi* che sono localizzate in compartimenti specifici.
* **Identità:** Questo crea "codici" unici.
    * Es. La Membrana Plasmatica è ricca di **PI(4,5)P$_2$**.
    * Es. L'Apparato di Golgi è ricco di **PI(4)P**.
    * Es. Gli Endosomi precoci sono ricchi di **PI(3)P**.
* **Ruolo nel Traffico:**
    Molte delle proteine coinvolte nel traffico (come le **Proteine Adattatrici** della clatrina, i **Fattori di Ormeggio** e i regolatori delle **Rab**) possiedono domini specifici (es. domini PH, FYVE) che legano *solo* un tipo specifico di PIP.
* **Doppia Specificità:** Questo fornisce un doppio controllo di sicurezza. Una vescicola non solo deve avere la Rab giusta (codice postale), ma può attraccare solo a una membrana che ha il marcatore PIP corretto (l'indirizzo di quartiere), assicurando che i macchinari di rivestimento e fusione si assemblino solo nel posto giusto al momento giusto.