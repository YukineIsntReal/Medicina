I **[[Virus]]** sono entità biologiche uniche, spesso definite come "parassiti endocellulari obbligati". Non sono considerati cellule vere e proprie (`acellulari`) in quanto mancano di ribosomi e di un apparato metabolico autonomo per generare `[[ATP]]`. Per replicarsi, devono infettare una cellula ospite (batterica, vegetale o animale) e "dirottare" i suoi sistemi biochimici.

---

## 1. Caratteristiche Generali e Struttura

Un **virione** (la particella virale completa e infettiva) è costituito da:

1.  **Acido Nucleico (Genoma):**
    * Costituisce il "core" virale e contiene l'informazione genetica.
    * Può essere **[[DNA]]** o **[[RNA]]**, mai entrambi.
    * Può essere **monocatenario** (singolo filamento, $ss$) o **bicatenario** (doppio filamento, $ds$).
    * Può essere **lineare** (es. Adenovirus) o **circolare** (es. Papillomavirus).
    * L'RNA può essere a **polarità positiva ($ssRNA+$)**, agendo direttamente come mRNA, o a **polarità negativa ($ssRNA-$)**, dovendo essere prima trascritto in un filamento positivo.

2.  **Capside:**
    * È l'involucro proteico che protegge l'acido nucleico.
    * È composto da subunità proteiche chiamate **capsomeri**.
    * L'insieme di acido nucleico e capside è detto **nucleocapside**.
    * La disposizione dei capsomeri determina la simmetria del virus:
        * **Elicoidale:** Capsomeri disposti a spirale (es. Virus del mosaico del tabacco, Virus della Rabbia).
        * **Icosaedrica:** Forma poliedrica con 20 facce triangolari (es. Adenovirus, Herpesvirus). È la struttura "chiusa" più efficiente.
        * **Complessa:** Strutture più elaborate (es. Batteriofagi con testa e coda, Poxvirus).

3.  **Involucro Membranoso (Envelope o Pericapside):**
    * Presente solo in alcuni virus, detti **virus rivestiti** (es. Virus dell'influenza, `[[HIV]]`, Herpesvirus). I virus che ne sono privi sono detti **virus nudi**.
    * È un doppio strato lipidico derivato dalle membrane della cellula ospite (membrana plasmatica, nucleare, o del Golgi) durante il processo di gemmazione.
    * Sull'envelope sono inserite **glicoproteine** codificate dal virus (es. Emoagglutinina e Neuraminidasi nell'influenza), spesso chiamate "spikes" (spine), che sono fondamentali per il riconoscimento dei recettori sulla cellula ospite e per l'ingresso.

---

## 2. Classificazione dei Virus Animali (di Baltimore)

La classificazione di Baltimore suddivide i virus in sette classi (le 6 classi di virus animali più una, la VII, spesso accorpata) in base alla natura del loro genoma e alla strategia di sintesi dell'mRNA.

* **Classe I: Virus a $dsDNA$**
    * Utilizzano la DNA polimerasi dell'ospite (o una propria) per replicare il genoma e la RNA polimerasi dell'ospite per la trascrizione in mRNA.
    * *Esempi:* `[[Papillomavirus]]` (HPV), Adenovirus, Herpesvirus, Poxvirus.

* **Classe II: Virus a $ssDNA$**
    * Devono prima sintetizzare un filamento complementare di DNA (diventando $dsDNA$) usando la DNA polimerasi dell'ospite. Da qui, procedono come la Classe I.
    * *Esempi:* Parvovirus.

* **Classe III: Virus a $dsRNA$**
    * Portano con sé una **RNA polimerasi RNA-dipendente (RdRp)** virale, poiché la cellula ospite non può replicare l'RNA dall'RNA.
    * La RdRp trascrive ogni filamento del $dsRNA$ in $mRNA$ ($ssRNA+$).
    * *Esempi:* Rotavirus.

* **Classe IV: Virus a $ssRNA+$ (a polarità positiva)**
    * Il genoma *è* l'mRNA. Può essere tradotto direttamente dai ribosomi dell'ospite per produrre proteine, inclusa una RdRp.
    * La RdRp virale sintetizza un filamento complementare $ssRNA-$ (antigenoma), che serve poi da stampo per produrre nuovi genomi $ssRNA+$.
    * *Esempi:* Poliovirus, Coronavirus, Virus dell'Epatite C.

* **Classe V: Virus a $ssRNA-$ (a polarità negativa)**
    * Il genoma *non* può essere tradotto. Il virione deve trasportare la propria RdRp.
    * La RdRp trascrive il genoma $ssRNA-$ in $mRNA$ ($ssRNA+$).
    * L'$mRNA$ viene tradotto e usato come stampo per nuovi genomi $ssRNA-$.
    * *Esempi:* Virus dell'Influenza, Virus della Rabbia, Virus del Morbillo.

* **Classe VI: Virus a $ssRNA-RT$ (Retrovirus)**
    * Sono $ssRNA+$, ma hanno un ciclo particolare (vedi sotto).
    * Usano una **[[Trascrittasi Inversa]]** (una DNA polimerasi RNA-dipendente) per retro-trascrivere il loro genoma a RNA in un $dsDNA$.
    * Questo $dsDNA$ si integra nel genoma dell'ospite.
    * *Esempi:* `[[HIV]]`, HTLV-1.

---

## 3. Cicli Replicativi dei Batteriofagi

I **batteriofagi** (o fagi) sono virus che infettano specificamente i batteri.

### Ciclo Litico
Porta alla distruzione (lisi) della cellula batterica ospite.
1.  **Adsorbimento:** Il fago si lega a recettori specifici sulla parete batterica.
2.  **Penetrazione:** Il fago inietta il proprio acido nucleico all'interno del batterio; il capside rimane all'esterno.
3.  **Sintesi (Fase Precoce e Tardiva):** Il DNA virale prende il controllo. Blocca la sintesi macromolecolare dell'ospite.
    * *Precoce:* Trascrizione di geni per enzimi virali (es. DNasi per degradare il DNA ospite, polimerasi virali).
    * *Tardiva:* Replicazione del genoma virale e sintesi delle proteine strutturali (capside, coda) e del lisozima (per la lisi finale).
4.  **Assemblaggio:** I genomi e i capsidi vengono assemblati spontaneamente in nuovi virioni.
5.  **Lisi:** Il lisozima virale degrada la parete batterica, causando la lisi della cellula e il rilascio di centinaia di nuovi fagi.

### Ciclo Lisogenico (Fagi Temperati)
Il virus non uccide immediatamente l'ospite, ma instaura una relazione latente.
1.  **Adsorbimento e Penetrazione:** Come nel ciclo litico.
2.  **Integrazione:** Il DNA del fago (ora chiamato **profago**) si integra in un sito specifico del cromosoma batterico.
3.  **Replicazione:** Il profago è inattivo (un repressore virale blocca la trascrizione dei geni litici) e viene replicato passivamente insieme al DNA batterico ad ogni divisione cellulare. Tutta la progenie batterica sarà *lisogena*.
4.  **Induzione:** In seguito a stress cellulari (es. danni al DNA), il repressore viene inattivato. Il profago si "escinde" dal cromosoma e inizia un [[Ciclo Litico]].

---

## 4. Ciclo Replicativo di un Virus Animale

Il ciclo nei virus animali è più complesso, data la natura della cellula eucariotica.
1.  **Adsorbimento (Attachment):** Legame altamente specifico tra le glicoproteine virali (su envelope o capside) e i recettori sulla membrana plasmatica della cellula ospite.
2.  **Penetrazione (Entry):** (Vedi sotto per i dettagli).
3.  **Scapsidazione (Uncoating):** Liberazione dell'acido nucleico virale nel citoplasma o nel nucleo, tramite degradazione del capside (spesso da enzimi lisosomiali).
4.  **Sintesi e Replicazione:** È la fase più variabile, che dipende dalla Classe di Baltimore.
    * I virus a DNA (eccetto Poxvirus) replicano nel nucleo, usando enzimi dell'ospite.
    * I virus a RNA (eccetto Influenza e Retrovirus) replicano nel citoplasma.
5.  **Assemblaggio (Assembly):** Le componenti virali (genomi e proteine) vengono assemblate in nuovi nucleocapsidi.
6.  **Rilascio (Release):** (Vedi sotto per i dettagli).

---

## 5. Modalità di Entrata e Uscita (Cellula Animale)

### Modalità di Entrata
* **Virus Rivestiti:**
    1.  **Fusione diretta:** L'envelope virale si fonde direttamente con la membrana plasmatica, rilasciando il nucleocapside nel citoplasma (es. `[[HIV]]`).
    2.  **Endocitosi Mediata da Recettori:** Il virus viene inglobato in una vescicola (endosoma). L'acidificazione dell'endosoma ($pH \approx 5$) induce un cambiamento conformazionale nelle glicoproteine virali, che promuove la fusione dell'envelope virale con la membrana dell'endosoma. Il nucleocapside viene rilasciato nel citoplasma (es. Virus dell'Influenza).
* **Virus Nudi:**
    1.  **Endocitosi Mediata da Recettori:** È la via più comune. Dopo l'endocitosi, il virus deve trovare un modo per "rompere" l'endosoma e liberare il genoma (es. Adenovirus).
    2.  **Penetrazione Diretta (Rara):** Alcuni virus nudi (es. Poliovirus) possono formare un poro nella membrana plasmatica e iniettare il genoma.

### Modalità di Uscita
* **Virus Rivestiti: Gemmazione (Budding)**
    * Le glicoproteine virali migrano e si inseriscono in una membrana dell'ospite (spesso quella plasmatica).
    * Il nucleocapside si associa a queste aree modificate.
    * La membrana "gemma" verso l'esterno, avvolgendo il nucleocapside e formando l'envelope.
    * Questo processo non uccide necessariamente la cellula (infezione persistente).
* **Virus Nudi: Lisi Cellulare**
    * I virioni si accumulano nel citoplasma o nel nucleo.
    * La cellula muore (per apoptosi o necrosi indotta dal virus) e si rompe, rilasciando le particelle virali.

---

## 6. Ciclo di un Retrovirus (Classe VI)

I Retrovirus (es. `[[HIV]]`) hanno un ciclo unico:
1.  Ingresso per fusione e scapsidazione.
2.  Nel citoplasma, la **[[Trascrittasi Inversa]]** (un enzima virale portato nel virione) sintetizza un filamento di DNA usando l'RNA virale come stampo ($cDNA$).
3.  La stessa trascrittasi inversa degrada l'RNA stampo e sintetizza il secondo filamento di DNA, creando un **$dsDNA$ virale**.
4.  Questo $dsDNA$ migra nel nucleo e, grazie all'enzima virale **integrasi**, si inserisce nel genoma della cellula ospite. Il DNA virale integrato è chiamato **provirus**.
5.  Il provirus è ora parte permanente del genoma cellulare. Può rimanere latente o essere trascritto.
6.  La RNA polimerasi II dell'ospite trascrive il provirus per produrre:
    * Nuovi genomi $ssRNA+$ virali.
    * $mRNA$ per la sintesi delle proteine virali.
7.  Assemblaggio e Rilascio per gemmazione.

---

## 7. Virus Oncogeni (Virus e [[Cancro]])

Alcuni virus, detti **virus oncogeni**, possono indurre la trasformazione neoplastica (`[[Oncogenesi]]`) nelle cellule che infettano.

### Virus Oncogeni a DNA
(es. `[[Papillomavirus]]` - HPV, Virus di Epstein-Barr - EBV, Virus dell'Epatite B - HBV).
L'oncogenesi è spesso un "incidente" del ciclo virale (non serve al virus per replicarsi).
La trasformazione avviene tipicamente quando il virus (o parti del suo genoma) si integra nel DNA dell'ospite e produce **proteine oncogene** (oncoproteine).
*Esempio: HPV*
Le oncoproteine **E6** ed **E7** di HPV legano e inducono la degradazione dei principali **oncosoppressori** della cellula:
* **E6** lega e degrada **[[p53]]** (guardiano del genoma, induce l'apoptosi).
* **E7** lega e degrada **[[Rb]]** (Retinoblastoma, blocca il ciclo cellulare in G1).
Senza p53 e Rb, la cellula perde i "freni" principali del ciclo cellulare e accumula mutazioni, portando al cancro (es. carcinoma della cervice).

### Virus Oncogeni a RNA (Retrovirus)
(es. HTLV-1, Virus della Leucemia Felina - FeLV).
I retrovirus sono oncogeni "per natura", poiché l'integrazione nel genoma ospite è una parte essenziale del loro ciclo.
* **Retrovirus acutamente trasformanti:** Hanno "catturato" per errore un gene cellulare (un **proto-oncogene**) e lo hanno mutato in un **oncogene virale (v-onc)**. Quando infettano una cellula, questo v-onc è iper-espresso e causa una rapida trasformazione (es. Virus del Sarcoma di Rous, *v-src*).
* **Retrovirus lentamente trasformanti (Mutagenesi Inserzionale):** Non possiedono un v-onc. L'oncogenesi è un evento raro e lento, causato dall'integrazione *casuale* del provirus vicino a un **proto-oncogene** cellulare. I promotori/enhancer virali (molto forti) nel provirus causano un'espressione eccessiva e inappropriata del gene cellulare, innescando la trasformazione (es. HTLV-1 e la leucemia a cellule T dell'adulto).