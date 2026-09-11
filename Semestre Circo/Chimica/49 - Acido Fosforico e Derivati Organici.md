L'acido fosforico ($H_3PO_4$) è un acido triprotico (ha tre protoni acidi). È un acido forte sul primo $pKa$, ma a $pH$ fisiologico ($\approx 7.4$) esiste come una miscela di ioni fosfato, prevalentemente **$HPO_4^{2-}$** (ione idrogeno fosfato) e **$H_2PO_4^-$** (ione diidrogeno fosfato).
Per semplicità, in biochimica, l'intero gruppo fosfato (in qualsiasi stato di protonazione) è spesso indicato come **$P_i$** (fosfato inorganico).

Come l'acido carbossilico, l'acido fosforico può formare derivati, principalmente esteri e anidridi.

## 1. Esteri Fosforici (Fosfoesteri)

Un **estere fosforico** si forma dalla reazione tra un gruppo alcolico ($-OH$ di un composto organico, come uno zucchero o una proteina) e un gruppo acido dell'acido fosforico.

$$R-OH + HO-PO_3^{2-} \rightarrow R-O-PO_3^{2-} + H_2O$$

* **Legame:** È un legame **estereo** (o **fosfoestereo**).
* **Stabilità:** È un legame molto **stabile** a $pH$ neutro. Richiede enzimi (le *fosfatasi*) per essere idrolizzato.
* **Importanza Biologica:**
    * **Intermedi Metabolici:** Quasi tutti gli zuccheri nel metabolismo (es. **Glucosio-6-fosfato**, Fruttosio-6-fosfato) sono fosforilati. Il gruppo fosfato ($PO_3^{2-}$) è carico negativamente e serve a "intrappolare" lo zucchero all'interno della cellula, poiché la membrana cellulare è impermeabile alle molecole cariche.
    * **Struttura del DNA/RNA:** Lo scheletro (la "colonna vertebrale") del DNA e dell'RNA è formato da legami **fosfodiesterei**, in cui un singolo gruppo fosfato fa da ponte tra il $C-5'$ di un nucleotide e il $C-3'$ del nucleotide successivo.
    * **Proteine:** La fosforilazione di residui $-OH$ (di Serina, Treonina, Tirosina) è il principale meccanismo di regolazione "on/off" dell'attività enzimatica.

## 2. Anidridi Fosforiche (Fosfoanidridi)

Si formano per condensazione (eliminazione di $H_2O$) tra due gruppi fosfato, o tra un gruppo fosfato e un altro gruppo acido.

### Anidridi tra Fosfati
Si formano quando due o più unità di fosfato si legano tra loro.
* **Composti:** **$ADP$** (Adenosina *Di*fosfato) e **$ATP$** (Adenosina *Tri*fosfato).
* **Legame:** **Legame fosfoanidridico**.
* **Energia:** Questi sono **legami ad alta energia**.
    * *Motivo:* Contengono un'elevata densità di carica negativa (es. 3-4 cariche negative sull'ATP) confinata in uno spazio ristretto, creando una forte repulsione elettrostatica. L'idrolisi (rottura con $H_2O$) rilascia questa repulsione, libera $P_i$ (che si stabilizza per risonanza) e produce una grande quantità di energia libera ($\Delta G^\circ ' \approx -30.5 \text{ kJ/mol}$).

$$ATP + H_2O \rightarrow ADP + P_i + \text{Energia}$$

L'ATP è la "moneta energetica" universale della cellula: l'energia prodotta dal catabolismo viene usata per creare legami fosfoanidridici (ATP), e l'idrolisi di questi legami fornisce l'energia per quasi tutte le reazioni anaboliche (sintesi, movimento, trasporto).

---

## 3. Acilfosfati (Anidridi Miste)

Questa è la classe di composti più importante che collega il metabolismo dell'acido carbossilico a quello dell'acido fosforico.

Un **acilfosfato** è un'**anidride mista**, formata dalla condensazione tra un **acido carbossilico ($RCOOH$)** e l'**acido fosforico ($H_3PO_4$)**.

$$\underbrace{R-\overset{O}{\overset{||}{C}}-OH}_{\text{Acido Carbossilico}} + \underbrace{HO-PO_3^{2-}}_{\text{Fosfato}} \rightarrow \underbrace{R-\overset{O}{\overset{||}{C}}-O-PO_3^{2-}}_{\text{Acilfosfato}} + H_2O$$

### Importanza Biochimica: Composti "Altamente Energetici"

Gli acilfosfati sono composti ad **altissima energia di idrolisi**, persino più energetici dell'ATP ($\Delta G^\circ ' \approx -49 \text{ kJ/mol}$).

* **Perché sono così energetici?**
    1.  **Alta Energia del Reagente:** Come le anidridi fosforiche, soffrono di repulsione elettrostatica.
    2.  **Bassa Energia dei Prodotti:** L'idrolisi libera *due* specie che sono entrambe estremamente stabili:
        * Lo **ione carbossilato ($RCOO^-$)**, stabilizzato per risonanza.
        * Il **fosfato inorganico ($P_i$)**, anch'esso stabilizzato per risonanza.

Questa grande differenza di stabilità tra reagenti e prodotti rende il $\Delta G$ di idrolisi estremamente negativo (molto favorevole).

### Ruolo nel Metabolismo: La Fosforilazione a Livello del Substrato

Gli acilfosfati sono così energetici che il loro potenziale di trasferimento del gruppo fosfato è *superiore* a quello dell'ATP. Questo significa che possono essere usati per **sintetizzare ATP da ADP**.
Questo processo è chiamato **Fosforilazione a Livello del Substrato**.

L'esempio chiave è nella **Glicolisi**:
1.  **Reazione 6 (Glicolisi):** L'aldeide (Gliceraldeide-3-fosfato) viene ossidata *contemporaneamente* alla fosforilazione (usando $P_i$), formando l'acilfosfato **1,3-Bisfosfoglicerato (1,3-BPG)**.
2.  **Reazione 7 (Glicolisi):** L'1,3-BPG ha un'energia così alta che, nell'enzima *Fosfoglicerato Chinasi*, dona il suo gruppo fosfato (quello "acile") direttamente all'ADP per produrre la *prima* molecola di **ATP** della glicolisi.

$$\underbrace{1,3\text{-BPG}}_{\text{Acilfosfato}} + ADP \rightarrow \underbrace{3\text{-Fosfoglicerato}}_{\text{Carbossilato}} + \textbf{ATP}$$

In sintesi, la cellula usa un'ossidazione (di un'aldeide) per creare un acilfosfato (un derivato ad altissima energia), che poi "incassa" per creare ATP.