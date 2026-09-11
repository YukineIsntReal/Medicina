I **Recettori Accoppiati a Proteine G** (GPCRs) costituiscono la più grande superfamiglia di recettori di superficie.

* **Struttura:** Sono caratterizzati da una singola catena polipeptidica che attraversa la membrana plasmatica **sette volte** (recettori a 7 domini transmembrana o 7-TM).
* **Funzionamento:** Non hanno attività enzimatica intrinseca. Agiscono legando un ligando extracellulare e, in risposta, attivano una proteina intracellulare associata chiamata **Proteina G** (una proteina che lega nucleotidi guanilici).

---

## Proteine G Eterotrimeriche

Le proteine G che si accoppiano direttamente ai GPCR sono **eterotrimeriche**, composte cioè da tre subunità diverse: $\alpha$, $\beta$ e $\gamma$.

* **Stato Inattivo (a riposo):**
    * Il GPCR non è legato al ligando.
    * La proteina G è un trimero ($\alpha\beta\gamma$).
    * La subunità $\alpha$ lega una molecola di **GDP** (Guanosina Difosfato).

* **Ciclo di Attivazione:**
    1.  **Legame del Ligando:** Il ligando (es. ormone, neurotrasmettitore) si lega al dominio extracellulare del GPCR.
    2.  **Cambiamento Conformazionale:** Il GPCR cambia forma e "apre" un sito di legame per la proteina G sul suo lato citoplasmatico.
    3.  **Azione da GEF:** Il GPCR attivato agisce come un **GEF** (vedi sotto) sulla subunità $\alpha$: induce il rilascio del GDP.
    4.  **Scambio Nucleotidico:** Il sito di legame sulla G$\alpha$ viene immediatamente occupato dal **GTP** (Guanosina Trifosfato), che è molto più abbondante del GDP nel citosol.
    5.  **Dissociazione:** Il legame del GTP alla G$\alpha$ causa un altro cambiamento conformazionale:
        * La G$\alpha$-GTP si dissocia sia dal recettore sia dal dimero $\beta\gamma$.
    6.  **Trasmissione del Segnale:** Entrambe le componenti, **G$\alpha$-GTP** e il **dimero $\beta\gamma$**, sono ora attive e possono legarsi a proteine bersaglio a valle (gli **effettori**), trasmettendo il segnale.

* **Spegnimento (Inattivazione):**
    1.  La subunità G$\alpha$ possiede un'**attività GTPasica intrinseca** (è un enzima lento).
    2.  Dopo un certo tempo, G$\alpha$ idrolizza il GTP $\rightarrow$ GDP + $\text{P}_i$.
    3.  La G$\alpha$-GDP (ora inattiva) perde affinità per l'effettore e si riassocia al dimero $\beta\gamma$, riformando il trimero inattivo, pronto per un nuovo ciclo.

---

## Proteine G Monomeriche (Piccole GTPasi)

Esiste un'altra grande famiglia di proteine G, quelle **monomeriche** (o piccole GTPasi, es. famiglia **Ras**, Rho, Rab).

* **Funzionamento:** Sono strutturalmente omologhe alla subunità G$\alpha$, ma funzionano come proteine singole.
* **Ruolo:** Agiscono anch'esse come interruttori molecolari:
    * **Attive** quando legano **GTP**.
    * **Inattive** quando legano **GDP**.
* **Regolazione:** A differenza delle G$\alpha$, la loro attività GTPasica intrinseca è estremamente lenta e il loro scambio GDP/GTP è quasi nullo. Dipendono quindi interamente da due classi di proteine regolatorie.

---

## Proteine Regolatorie: GEF e GAP

Queste proteine sono i veri "regolatori" degli interruttori GTPasici.

1.  **GEF (Guanine nucleotide Exchange Factor):**
    * **Funzione:** Facilitano lo **scambio** GDP $\rightarrow$ GTP.
    * **Azione:** Si legano alla proteina G inattiva (legata a GDP) e ne inducono il rilascio. Il sito viene subito occupato da un GTP.
    * **Effetto:** **Attivano** la proteina G.
    * *Nota:* Il GPCR attivato è il GEF specifico per la sua proteina G trimerica associata.

2.  **GAP (GTPase-Activating Protein):**
    * **Funzione:** Attivano l'attività GTPasica.
    * **Azione:** Si legano alla proteina G attiva (legata a GTP) e aumentano drasticamente la velocità di idrolisi del GTP a GDP.
    * **Effetto:** **Inattivano** la proteina G (accelerano lo spegnimento).
    * *Nota:* Le proteine **RGS** (Regulator of G protein Signaling) agiscono come GAP per le subunità G$\alpha$ trimeriche.

---

## Secondi Messaggeri e Amplificazione

Il segnale deve essere propagato e amplificato all'interno della cellula.

* **Effettori Primari:** Sono gli enzimi (o canali) attivati direttamente da G$\alpha$-GTP o da G$\beta\gamma$. Esempi: **Adenilato Ciclasi**, **Fosfolipasi C (PLC)**.
* **Secondi Messaggeri:** Sono piccole molecole intracellulari, non proteiche, la cui concentrazione varia rapidamente in risposta all'attivazione dell'effettore.
    * **cAMP** (Adenosina Monofosfato Ciclico): Prodotto dall'Adenilato Ciclasi. Attiva la **Protein Chinasi A (PKA)**.
    * **IP$_3$** (Inositolo 1,4,5-Trifosfato) e **DAG** (Diacilglicerolo): Prodotti dalla PLC (che scinde il PIP$_2$).
        * **IP$_3$** (idrosolubile) diffonde nel citosol e apre i canali del $\text{Ca}^{2+}$ sul Reticolo Endoplasmatico.
        * **DAG** (liposolubile) rimane in membrana e, insieme al $\text{Ca}^{2+}$, attiva la **Protein Chinasi C (PKC)**.
    * **$\text{Ca}^{2+}$:** La sua concentrazione citosolica è un potentissimo secondo messaggero.

**Amplificazione del Segnale:** Il sistema GPCR è una cascata di amplificazione:
1.  1 Recettore attivato $\rightarrow$ attiva *molte* Proteine G.
2.  1 Proteina G attiva $\rightarrow$ attiva 1 Enzima Effettore.
3.  1 Enzima Effettore (es. Adenilato Ciclasi) $\rightarrow$ produce *migliaia* di molecole di Secondo Messaggero (es. cAMP).
4.  Migliaia di cAMP $\rightarrow$ attivano *migliaia* di PKA.
5.  Migliaia di PKA $\rightarrow$ fosforilano *milioni* di proteine bersaglio.

---

## Desensitizzazione Recettoriale

Per evitare una stimolazione eccessiva, le cellule devono poter "spegnere" o smorzare la risposta anche se il ligando è ancora presente.

* **Meccanismo Generale:**
    1.  **Fosforilazione:** Un GPCR che rimane attivo per troppo tempo viene riconosciuto da una chinasi specifica, la **GRK** (G protein-coupled Receptor Kinase).
    2.  La GRK fosforila i residui di Serina/Treonina sul dominio citoplasmatico del recettore.
    3.  **Legame dell'Arrestina:** Il recettore fosforilato diventa un sito di legame ad alta affinità per una proteina chiamata **Arrestina**.
    4.  **Desensitizzazione:** L'Arrestina legata impedisce fisicamente (ingombro sterico) al recettore di interagire e attivare altre proteine G.
    5.  **Internalizzazione:** L'Arrestina agisce anche come adattatore per reclutare le proteine dell'endocitosi (es. Clatrina), portando all'internalizzazione del recettore in una vescicola. Da qui, il recettore può essere o degradato (down-regulation) o defosforilato e riciclato in membrana.

### Esempio: la Visione (Fototrasduzione nei Bastoncelli)

La visione è un esempio perfetto e altamente specializzato di segnalazione GPCR e desensitizzazione.

* **Al Buio (Stato di Riposo):**
    * Nei bastoncelli, la concentrazione di **cGMP** è alta.
    * Il cGMP tiene aperti i canali $\text{Na}^+/\text{Ca}^{2+}$ cGMP-dipendenti.
    * L'ingresso di cariche positive mantiene la cellula **depolarizzata** ($\approx -30 \text{ mV}$).
    * La depolarizzazione causa un rilascio costante del neurotrasmettitore **Glutamato** (è il "segnale di buio").

* **Alla Luce (Attivazione):**
    1.  **Recettore:** Il GPCR è la **Rodopsina** (Opsina + 11-cis-Retinale).
    2.  **Ligando:** Un **fotone** (luce).
    3.  **Attivazione:** Il fotone colpisce l'11-cis-Retinale, che isomerizza in **tutto-trans-Retinale**. Questo cambia la conformazione dell'Opsina, attivandola (ora chiamata Metarodopsina II).
    4.  **Proteina G:** La Rodopsina attivata agisce da GEF per la **Trasducina** (una G$\alpha_t$).
    5.  **Effettore:** La G$\alpha_t$-GTP si dissocia e attiva la **Fosfodiesterasi (PDE) del cGMP**.
    6.  **Amplificazione:** La PDE idrolizza migliaia di molecole di **cGMP** $\rightarrow$ $\text{GMP}$.
    7.  **Risposta:** La concentrazione di cGMP crolla.
    8.  I canali cGMP-dipendenti si **chiudono**.
    9.  L'ingresso di cariche positive cessa, la cellula si **iperpolarizza** ($\approx -70 \text{ mV}$).
    10. Il rilascio di Glutamato **si interrompe**. Questo è il segnale nervoso che "c'è luce".

* **Desensitizzazione (Spegnimento Rapido):**
    1.  La Rodopsina attivata viene immediatamente fosforilata dalla **Rodopsina Chinasi** (una GRK).
    2.  L'**Arrestina** si lega alla Rodopsina fosforilata, bloccando l'attivazione di altra Trasducina (spegnimento del recettore).
    3.  L'attività GTPasica della Trasducina (aiutata da un GAP/RGS) spegne la PDE.
    4.  La Guanilato Ciclasi (sempre attiva, ma stimolata dal calo di $\text{Ca}^{2+}$) risintetizza cGMP, riaprendo i canali e riportando la cellula allo stato di buio.