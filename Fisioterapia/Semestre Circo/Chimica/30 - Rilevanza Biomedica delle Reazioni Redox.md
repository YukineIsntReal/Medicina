Le reazioni di ossido-riduzione (Redox) sono alla base della vita cellulare. Governano il flusso di energia, la segnalazione e la difesa contro gli insulti ambientali. La loro importanza in ambito biomedico è onnipresente, dal metabolismo energetico alla patogenesi di innumerevoli malattie.

## 1. Metabolismo Energetico: La Bioenergetica

Il catabolismo (la scomposizione) di molecole ad alta energia come il glucosio è una **grande reazione di ossidazione controllata**.
*Reazione complessiva della respirazione cellulare:*
$C_6H_{12}O_6 + 6O_2 \rightarrow 6CO_2 + 6H_2O + \text{Energia (ATP)}$

* **Ossidazione:** Il Glucosio ($C_6H_{12}O_6$) viene ossidato a $CO_2$. Gli atomi di carbonio perdono elettroni (e idrogeni).
* **Riduzione:** L'Ossigeno ($O_2$) viene ridotto ad Acqua ($H_2O$). L'ossigeno (altamente elettronegativo, $E^\circ$ elevato) è l'**accettore finale di elettroni**.

Questo processo non avviene in un unico passaggio (che sarebbe esplosivo), ma è frazionato in tappe (Glicolisi, Ciclo di Krebs), dove gli elettroni vengono "parcheggiati" su coenzimi specializzati:

* **$NAD^+$ (Nicotinammide Adenina Dinucleotide):** È un agente ossidante chiave. Accetta $2e^-$ e $1H^+$ (un idruro, $H^-$) per diventare **$NADH$** (la sua forma ridotta).
    $NAD^+ + 2e^- + 2H^+ \rightarrow NADH + H^+$
* **$FAD$ (Flavina Adenina Dinucleotide):** Diventa **$FADH_2$** (forma ridotta).

Successivamente, nella **[[Fosforilazione Ossidativa]]** (che avviene nei mitocondri):
1.  $NADH$ e $FADH_2$ (agenti riducenti) cedono questi elettroni ad alta energia alla **[[Catena di Trasporto degli Elettroni]]**.
2.  La catena è una serie di complessi proteici (contenenti centri redox come citocromi e centri Fe-S) con **potenziali di riduzione ($E^\circ$) crescenti**.
3.  Gli elettroni "cadono" spontaneamente lungo questo gradiente di potenziale (un $\Delta E_{cell}$ positivo, che genera un $\Delta G$ negativo, come visto in [[Potenziali Elettrochimici e Spontaneità]]), liberando energia.
4.  Questa energia viene usata per pompare protoni ($H^+$) nello spazio intermembrana, creando un **gradiente elettrochimico** (un esempio biologico di [[Potenziali Elettrochimici e Spontaneità#Pile a Concentrazione|Pila a Concentrazione]]).
5.  Il rientro dei protoni attraverso l'enzima **ATP-sintasi** genera la stragrande maggioranza dell'ATP cellulare.

> **Rilevanza Clinica:** Veleni come il **Cianuro ($CN^-$)** o il **Monossido di Carbonio ($CO$)** sono letali perché bloccano la catena di trasporto (legano il Ferro nel Complesso IV), impedendo la riduzione dell'ossigeno e fermando la produzione di ATP.

## 2. Stress Ossidativo e Radicali Liberi

L'ossigeno è essenziale, ma anche tossico. Durante la fosforilazione ossidativa (e in altre reazioni), una piccola percentuale di elettroni "sfugge" alla catena e riduce parzialmente l'ossigeno, generando **Specie Reattive dell'Ossigeno (ROS)**.

* **Radicale Superossido ($O_2^{\cdot-}$):** $O_2 + 1e^- \rightarrow O_2^{\cdot-}$
* **Perossido di Idrogeno ($H_2O_2$):** $O_2^{\cdot-} + e^- + 2H^+ \rightarrow H_2O_2$ (Non è un radicale, ma è un forte ossidante)
* **Radicale Idrossile ($\cdot OH$):** $H_2O_2 + e^- \rightarrow \cdot OH + OH^-$ (Il più reattivo e dannoso)

Lo **Stress Ossidativo** è lo squilibrio tra la produzione di ROS e la capacità del corpo di neutralizzarli. I ROS (specialmente $\cdot OH$) attaccano e danneggiano le principali macromolecole:
* **Lipidi:** Perossidazione lipidica (danno alle membrane cellulari).
* **Proteine:** Ossidazione e denaturazione (perdita di funzione enzimatica/strutturale).
* **DNA:** Mutazioni (rotture del filamento, ossidazione delle basi).

Questo danno è implicato in:
* **Invecchiamento**
* **Malattie Neurodegenerative** (Alzheimer, Parkinson)
* **Cancro** (danno al DNA)
* **Infiammazione cronica**
* **Danno da ischemia-riperfusione** (es. infarto miocardico)

## 3. Sistemi di Difesa Antiossidante

Per contrastare i ROS, le cellule hanno evoluto sistemi di difesa complessi:

1.  **Antiossidanti Enzimatici:**
    * **Superossido Dismutasi (SOD):** $2O_2^{\cdot-} + 2H^+ \rightarrow H_2O_2 + O_2$
    * **Catalasi:** $2H_2O_2 \rightarrow 2H_2O + O_2$
    * **Glutatione Perossidasi (GPx):** Usa il **Glutatione ($GSH$)** per ridurre $H_2O_2$ ad acqua.

2.  **Antiossidanti Non-Enzimatici:**
    * **Glutatione ($GSH$):** È un tripeptide, il principale "tampone redox" della cellula. Si ossida a $GSSG$ per proteggere le altre molecole.
    * **Vitamine (esogene):** Vitamina E (liposolubile, protegge le membrane) e Vitamina C (idrosolubile).

## 4. Segnalazione Redox (Redox Signaling)

Recentemente si è compreso che i ROS, a basse e controllate concentrazioni, non sono solo dannosi ma agiscono come **molecole segnale** (simili a ormoni o neurotrasmettitori), modificando temporaneamente l'attività di proteine specifiche (spesso ossidando i gruppi tiolici $-SH$ delle cisteine).