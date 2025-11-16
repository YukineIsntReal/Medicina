I derivati degli acidi carbossilici sono composti in cui il gruppo $-OH$ del carbossile è stato sostituito da un altro gruppo ($-L$), con formula generale $R-CO-L$.

La reazione principale di tutti questi derivati è la **Sostituzione Nucleofila Acilica (NAS)**, dove un nucleofilo ($Nu:$) attacca il carbonile e sostituisce il gruppo uscente $L$.

## Gerarchia di Reattività
La reattività nella NAS dipende da quanto è buono il gruppo uscente $L$. Un buon gruppo uscente è una base debole (stabile).
La reattività decresce:

**Alogenuri Acilici > Anidridi > Tioesteri > Esteri > Ammidi**

Le ammidi sono le meno reattive (e quindi le più stabili), poiché $NH_2^-$ è una base fortissima e un pessimo gruppo uscente.

---

## Classi di Derivati (e Rilevanza Biologica)

### 1. Alogenuri Acilici ($R-CO-Cl$)
Estremamente reattivi, reagiscono violentemente con l'acqua. Usati in sintesi organica, non presenti in biologia.

### 2. Anidridi ($R-CO-O-CO-R'$)
Molto reattive. Il gruppo uscente è uno ione carbossilato ($RCOO^-$), stabile per risonanza.
* **Rilevanza Biologica:** I **legami fosfo-anidridici** nell'**ATP** (tra i gruppi fosfato) e gli **acilfosfati** (es. *1,3-Bisfosfoglicerato* nella glicolisi) sono anidridi miste (acido carbossilico-acido fosforico). La loro idrolisi libera moltissima energia.

### 3. Tioesteri ($R-CO-SR'$)
Reattivi, con un'energia di idrolisi simile a quella delle anidridi. Il gruppo uscente è un tiolato ($RS^-$), che è una base debole (buon gruppo uscente).
* **Rilevanza Biologica:** Fondamentali. L'**Acetil-Coenzima A (Acetil-CoA)** è un tioestere. È il "donatore universale" di gruppi acile (es. nel Ciclo di Krebs) proprio perché è sufficientemente reattivo da trasferire il suo gruppo acetile ($CH_3CO-$).

### 4. Esteri ($R-CO-OR'$)
Stabili in acqua a $pH$ neutro, ma idrolizzabili.
* **Rilevanza Biologica:** **Trigliceridi** (triesteri del glicerolo), sono la forma di immagazzinamento dei lipidi.

### 5. Ammidi ($R-CO-NR'_2$)
Estremamente stabili e poco reattivi. L'atomo di azoto dona il suo doppietto al carbonile, creando una forte **risonanza** che dà al legame $C-N$ un carattere di doppio legame parziale. Questo rende la molecola planare e molto resistente all'idrolisi.
* **Rilevanza Biologica:** Il **legame peptidico** che unisce gli amminoacidi nelle proteine è un legame ammidico. La sua stabilità è la chiave della stabilità strutturale delle proteine.

---

## Reazioni degli Esteri

### 1. Esterificazione di Fischer (Sintesi)
Reazione di equilibrio, catalizzata da acidi, tra un acido carbossilico e un alcol per formare un estere.
$$RCOOH + R'OH \rightleftharpoons RCOOR' + H_2O$$

### 2. Idrolisi Acida degli Esteri
È la reazione inversa della Fischer. Un estere reagisce con $H_2O$ in ambiente acido ($H^+$) per tornare all'acido carbossilico e all'alcol. Essendo un equilibrio, la reazione è reversibile.
$$RCOOR' + H_2O \xrightarrow{H^+} RCOOH + R'OH$$

### 3. Idrolisi Basica (Saponificazione)
L'idrolisi di un estere in ambiente basico (es. $NaOH$). Questa reazione è **irreversibile**.
$$RCOOR' + OH^- \rightarrow RCOO^- + R'OH$$
Il meccanismo prevede l'attacco di $OH^-$ (nucleofilo) e l'uscita di $R'O^-$ (alcossido). L'$R'O^-$ (base forte) deprotona immediatamente l'acido carbossilico ($RCOOH$) formatosi, trasformandolo nello **ione carbossilato ($RCOO^-$)**.
Il carbossilato è stabile, non reattivo e sposta l'equilibrio completamente verso i prodotti. È chiamata "saponificazione" perché è il processo usato per fare i saponi (idrolisi basica dei trigliceridi).

---

## Condensazione di Claisen
È l'equivalente della condensazione aldolica, ma per gli esteri. Richiede un estere con almeno due $H_\alpha$ e una base forte (es. $NaOR'$).

1.  Una base (alcossido $R'O^-$) rimuove un $H_\alpha$ da un estere, formando un **enolato di estere**.
2.  L'enolato (nucleofilo) attacca il carbonile di una seconda molecola di estere (NAS).
3.  L'intermedio tetraedrico collassa, espellendo il gruppo alcossido ($-OR'$).
4.  Il prodotto è un **$\beta$-chetoestere**.

*Importanza Biologica:* Il meccanismo della *Fatty Acid Synthase* (sintesi degli acidi grassi) è basato su una serie di condensazioni di Claisen, usando l'Acetil-CoA (un tioestere) come unità di partenza.

---

## Reazioni Speciali di Acidi Funzionalizzati

### 1. Formazione di Lattoni (Esterificazione Intramolecolare)
Un **lattone** è un estere ciclico. Si forma quando una molecola contiene *sia* un gruppo $-COOH$ *sia* un gruppo $-OH$ (un idrossiacido) e questi reagiscono tra loro.
La reazione è favorita (spesso spontanea) se porta alla formazione di anelli stabili a 5 termini ($\gamma$-lattoni) o 6 termini ($\delta$-lattoni).

$$\text{Acido } \gamma\text{-idrossibutirrico} \rightarrow \gamma\text{-Butirrolattone (GBL)} + H_2O$$

### 2. Decarbossilazione dei $\beta$-Chetoacidi
Gli acidi carbossilici che hanno un gruppo chetonico in posizione $\beta$ (sul $C-3$) sono instabili e subiscono **decarbossilazione** (perdita di $CO_2$) molto facilmente, spesso solo con un blando riscaldamento.

$$R-\overset{O}{\overset{||}{C}}-CH_2-COOH \xrightarrow{\Delta} R-\overset{O}{\overset{||}{C}}-CH_3 + CO_2$$

*Meccanismo:* Il $-COOH$ e il chetone $\beta$ formano un intermedio ciclico a 6 termini. Il $C=O$ accetta il protone $H^+$ e i legami si riorganizzano, rilasciando $CO_2$ e formando un enolo, che tautomerizza al chetone finale.
*Importanza Biologica:*
* **Metabolismo dei Corpi Chetonici:** L'acetoacetato (un $\beta$-chetoacido) decarbossila spontaneamente ad acetone (un chetone) e $CO_2$.
* **Ciclo di Krebs:** L'ossalacetato (che è un $\beta$-chetoacido) viene decarbossilato nella via di sintesi del PEP (nella gluconeogenesi).
* **Sintesi Acidi Grassi:** L'intermedio Malonil-ACP viene decarbossilato durante l'allungamento della catena.

*(Nota: Gli $\alpha$-chetoacidi, come il Piruvato, richiedono coenzimi specifici, come la TPP, per la decarbossilazione).*