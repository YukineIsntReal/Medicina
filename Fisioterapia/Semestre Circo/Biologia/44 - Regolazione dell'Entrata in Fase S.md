La transizione dalla fase $G_1$ alla fase $S$ è il punto decisionale fondamentale del ciclo cellulare. È qui che la cellula, in base a segnali esterni e condizioni interne, "decide" se impegnarsi irreversibilmente a duplicare il proprio DNA e dividersi. Questo punto è noto come **Punto di Restrizione (R)**.

## 1. Il Ruolo dei Fattori di Crescita (Mitogeni)

Nella maggior parte delle cellule, l'avanzamento in $G_1$ non è automatico. Richiede segnali extracellulari positivi, chiamati **fattori di crescita** (o **mitogeni**), che si legano a recettori specifici sulla superficie cellulare.

* Questo legame innesca cascate di trasduzione del segnale (es. la via $Ras/MAPK$).
* L'esito finale di queste cascate è la **sintesi della Ciclina D**, il primo ingranaggio del motore $G_1$.
* Finché i mitogeni sono presenti, la cellula accumula Ciclina D. Se i mitogeni vengono rimossi prima del Punto di Restrizione, la Ciclina D viene rapidamente degradata e la cellula torna in $G_0$ (quiescenza).

## 2. Il Complesso Ciclina D-Cdk4/6 e la Fosforilazione di Rb

La Ciclina D, una volta sintetizzata, si lega ai suoi partner catalitici, le chinasi **$Cdk4$** e **$Cdk6$**.

* Il complesso attivo **Ciclina D-Cdk4/6** inizia a fosforilare (in modo incompleto, o "ipofosforilare") la proteina chiave di questo checkpoint: **$pRb$ (proteina del Retinoblastoma)**.

**$pRb$ (Retinoblastoma): Il Guardiano del Checkpoint $G_1$**

* $Rb$ è un **gene oncosoppressore**. La sua proteina ($pRb$) agisce come un freno.
* In $G_0$ e $G_1$ precoce, $pRb$ è **attiva** (ipofosforilata) e lega i fattori di trascrizione della famiglia **$E2F$**.
* Quando $pRb$ lega $E2F$, non solo blocca la sua capacità di attivare i geni, ma recluta anche enzimi (come le istone deacetilasi, $HDAC$) che compattano la cromatina, reprimendo attivamente la trascrizione.

## 3. Attivazione di E2F e Transizione $G_1$/S

L'azione della Ciclina D-Cdk4/6 prepara il terreno, ma il "colpo di grazia" a $pRb$ è dato da un altro complesso:

1.  La fosforilazione parziale da parte di Ciclina D-Cdk4/6 "allenta" la presa di $pRb$ su $E2F$.
2.  $E2F$ (ora parzialmente libero) inizia a promuovere la trascrizione del proprio gene e, soprattutto, della **Ciclina E**.
3.  La Ciclina E si lega a **$Cdk2$**.
4.  Il complesso **Ciclina E-Cdk2** (ora attivo) **iperfosforila** $pRb$.
5.  $pRb$ iperfosforilata cambia conformazione e si stacca completamente da $E2F$.

A questo punto, la cellula ha superato il Punto di Restrizione (R).

**$E2F$ Libero: Il Motore della Fase S**
$E2F$ è ora libero di agire come un potente attivatore trascrizionale per tutti i geni necessari alla duplicazione del DNA, tra cui:
* Enzimi per la sintesi dei nucleotidi (es. timidina chinasi, diidrofolato reduttasi).
* Proteine del complesso di replicazione (es. DNA polimerasi, $PCNA$).
* Le cicline $A$ e $B$ (necessarie per le fasi successive del ciclo).

**Rb nel Retinoblastoma**
Il retinoblastoma è un tumore oculare pediatrico causato dalla perdita (mutazione inattivante) di entrambe le copie del gene $Rb1$.
* Senza $pRb$ funzionale, non c'è nessun "guardiano".
* $E2F$ è costitutivamente libero e attivo, anche in assenza di fattori di crescita.
* La cellula supera continuamente il Punto di Restrizione e prolifera in modo incontrollato.
* Questo segue l'ipotesi "a due colpi" (two-hit hypothesis) di Knudson per i geni oncosoppressori: è necessaria l'inattivazione di entrambi gli alleli.

---

## 4. Inibitori del Complesso Ciclina-CDK (CKI)

Il ciclo è tenuto a freno non solo dall'assenza di cicline, ma anche da proteine inibitrici specifiche (CKI). Si dividono in due famiglie:

1.  **Famiglia $INK4$ (Inhibitors of CDK4):**
    * Comprende $p16^{INK4a}$, $p15$, $p18$, $p19$.
    * Agiscono *solo* su **$Cdk4$** e **$Cdk6$**.
    * Si legano a $Cdk4/6$ impedendo fisicamente il legame della Ciclina D.
    * $p16$ è un oncosoppressore cruciale; la sua perdita è comune in molti tumori (es. melanoma) e permette l'attivazione incontrollata di $Cdk4/6$.

2.  **Famiglia $Cip/Kip$ (CDK inhibitory protein / Kinase inhibitory protein):**
    * Comprende **$p21^{Cip1}$**, **$p27^{Kip1}$**, $p57$.
    * Sono inibitori ad ampio spettro: legano e inattivano i complessi $Ciclina E-Cdk2$, $Ciclina A-Cdk2$ e $Ciclina D-Cdk4/6$.
    * $p27$ è importante per mantenere la quiescenza ($G_0$).
    * $p21$ è l'effettore principale del checkpoint del danno al DNA (vedi sotto).

---

## 5. Danno al DNA e Attivazione di p53

Il checkpoint più importante in $G_1$ è quello che monitora l'integrità del genoma.

* **$p53$:** È il "Guardiano del Genoma", un altro **gene oncosoppressore** fondamentale.
* In condizioni normali, $p53$ è tenuta a livelli bassissimi perché viene costantemente legata da **$MDM2$** (una E3 ubiquitina ligasi) che la marca per la degradazione.

**In caso di Danno al DNA (es. rotture del doppio filamento):**

1.  Il danno viene rilevato da proteine "sensore" (es. $ATM$, $ATR$).
2.  Questi sensori attivano chinasi (es. $Chk1$, $Chk2$) che fosforilano $p53$.
3.  La fosforilazione impedisce a $MDM2$ di legare $p53$.
4.  $p53$ si **stabilizza**, si accumula nel nucleo e agisce come fattore di trascrizione.

**L'azione di $p53$ (Il Bivio: Riparo o Morte):**

$p53$ attiva la trascrizione di geni che decidono il destino della cellula:

1.  **Arresto del Ciclo Cellulare (per dare tempo al riparo):**
    * $p53$ induce potentemente l'espressione di **$p21$** (l'inibitore CKI).
    * $p21$ si lega e inibisce i complessi $Ciclina E-Cdk2$ e $Ciclina D-Cdk4/6$.
    * Questo blocca la fosforilazione di $pRb$, $E2F$ rimane legato e il ciclo si arresta in $G_1$ (o in $G_2$, inibendo $Cdk1$).

2.  **Apoptosi (se il danno è troppo grave):**
    * Se l'arresto non è sufficiente, $p53$ attiva un programma di morte cellulare programmata ([[Apoptosi]]).
    * Lo fa inducendo l'espressione di geni pro-apoptotici (es. $BAX$, $PUMA$, $Noxa$).

*Mutazioni a carico di $p53$ (presenti in >50% dei tumori umani) sono devastanti: la cellula non solo non riesce a fermare il ciclo per riparare il DNA, ma è anche resistente all'apoptosi. Questo porta ad **instabilità genomica** (accumulo di mutazioni).*

---

## 6. Definizioni Oncologiche di Base

I geni che regolano il ciclo cellulare sono spesso al centro della trasformazione tumorale.

* **Proto-oncogeni:**
    * Sono geni *normali* che, quando espressi correttamente, promuovono la crescita e la divisione cellulare (es. $Ciclina D$, $Cdk4$, $E2F$, $Ras$, recettori per i fattori di crescita).
    * Sono "l'acceleratore" della cellula.

* **Oncogeni:**
    * Sono la versione *mutata* (attivata) di un proto-oncogene.
    * Una mutazione in *un solo* allele (mutazione dominante) è sufficiente a renderli iperattivi.
    * L'oncogene agisce come un "acceleratore bloccato".
    * Es: $Ras$ mutato (sempre attivo), $Ciclina D$ sovraespressa.

* **Geni Oncosoppressori (o Antioncogeni):**
    * Sono geni *normali* che inibiscono la proliferazione cellulare o promuovono l'apoptosi (es. **$Rb$**, **$p53$**, **$p16$**, **$p21$**).
    * Sono "i freni" della cellula.
    * Per perdere la loro funzione, *entrambi* gli alleli devono essere inattivati (mutazione recessiva), secondo l'ipotesi dei "due colpi".