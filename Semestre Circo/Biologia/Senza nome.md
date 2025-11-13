# Morte Cellulare: Necrosi e Apoptosi

La morte di una cellula può avvenire secondo due modalità principali, con cause, morfologie e conseguenze biologiche radicalmente diverse: la necrosi e l'apoptosi.

## 1. Necrosi
* È una forma di morte **accidentale**, **passiva** e **patologica**.
* È causata da un danno acuto e grave (es. trauma fisico, ischemia, tossine, ipertermia).
* **Morfologia:** La cellula e i suoi organelli si gonfiano (rigonfiamento oncotico) a causa del fallimento delle pompe ioniche (dovuto a deplezione di ATP). La membrana plasmatica perde integrità e si rompe.
* **Conseguenze:** Il contenuto cellulare (enzimi lisosomiali, metaboliti) si riversa nell'ambiente extracellulare, scatenando una forte **risposta infiammatoria** (richiamo di leucociti) che può danneggiare il tessuto circostante.

## 2. Apoptosi
* È una forma di morte cellulare **programmata**, **attiva** (richiede ATP) e **fisiologica** (o indotta in modo controllato).
* È essenziale per l'omeostasi dei tessuti (eliminare cellule vecchie), lo sviluppo embrionale (es. eliminare le membrane interdigitali) e l'eliminazione di cellule danneggiate o infettate (es. danno al DNA, infezioni virali).
* **Morfologia:**
    * La cellula si **restringe** (picnosi).
    * Il citoscheletro collassa.
    * La cromatina si condensa (picnosi) e il nucleo si frammenta (carioressi).
    * La membrana plasmatica forma delle estroflessioni (blebbing).
    * La cellula si frammenta in **corpi apoptotici**: vescicole avvolte da membrana contenenti frammenti di citoplasma e nucleo.
* **Conseguenze:** I corpi apoptotici vengono riconosciuti e fagocitati (es. dai macrofagi) in modo "pulito", **senza innescare infiammazione**.

---

## Il Meccanismo Molecolare dell'Apoptosi: Le Caspasi

Il motore biochimico dell'apoptosi è una famiglia di proteasi chiamate **Caspasi** (Cysteine-dependent ASPartate-specific proteASES). Esse tagliano altre proteine solo dopo residui di Acido Aspartico.

Esistono due classi principali di caspasi, che agiscono in una cascata:

1.  **Caspasi Iniziatrici (es. Caspasi-8, -9, -10):**
    * Esistono come monomeri inattivi (procaspasi).
    * Vengono attivate in risposta a segnali specifici, portandole ad aggregarsi (dimerizzare) e auto-attivarsi.
    * Il loro compito è attivare le caspasi esecutrici.

2.  **Caspasi Esecutrici (o Effettrici) (es. Caspasi-3, -6, -7):**
    * Esistono come dimeri inattivi.
    * Vengono attivate per taglio proteolitico dalle caspasi iniziatrici.
    * Una volta attive, sono le responsabili della "demolizione" cellulare:
        * Tagliano le **lamine nucleari**, causando il collasso del nucleo.
        * Tagliano le proteine del citoscheletro (es. actina, gelsolina).
        * Attivano la $CAD$ (Caspase-Activated DNase) rimuovendo il suo inibitore ($iCAD$), portando alla frammentazione internucleosomale del DNA (il "DNA laddering").

L'attivazione delle caspasi iniziatrici avviene tramite due vie principali, che possono convergere.

---

### A) La Via Estrinseca (o dei Recettori di Morte)

Questa via è innescata da segnali **extracellulari**.

1.  **Recettori di Morte:** Sulla superficie cellulare sono presenti recettori della famiglia $TNFR$ (Tumor Necrosis Factor Receptor), come **$Fas$ (CD95)** o $TNFR1$.
2.  **Ligandi:** Questi recettori vengono attivati dal legame con i loro ligandi specifici (es. **$FasL$** o $TNF-\alpha$), spesso esposti su altre cellule (es. linfociti T citotossici).
3.  **Segnalazione:** Il legame del ligando induce la trimerizzazione dei recettori.
4.  **Formazione del DISC:** Questo recluta proteine adattatrici (es. $FADD$) che, a loro volta, reclutano la **Procaspasi-8**. L'intero complesso è chiamato **DISC** (Death-Inducing Signaling Complex).
5.  **Attivazione:** L'alta concentrazione locale nel DISC induce la dimerizzazione e l'auto-attivazione della **Caspasi-8** (iniziatrice).
6.  **Esecuzione:** La Caspasi-8 attiva direttamente le **Caspasi Esecutrici** (es. Caspasi-3), scatenando l'apoptosi.

*Questa via può anche "incrociarsi" (crosstalk) con la via intrinseca: la Caspasi-8 può tagliare la proteina $BID$, trasformandola in $tBID$, che attiva la via mitocondriale.*

---

### B) La Via Intrinseca (o Mitocondriale)

Questa via è innescata da segnali di **stress intracellulare** (es. danno al DNA, ipossia, stress del RE, perdita di fattori di crescita).

Il fulcro di questa via è il **mitocondrio** e la sua permeabilizzazione, regolata dalla **famiglia di proteine BCL2**.

**La Famiglia BCL2:**
Si dividono in tre gruppi in base alla loro funzione:

1.  **Proteine Anti-Apoptotiche (es. $BCL2$, $BCL-XL$, $Mcl-1$):**
    * Sono "i guardiani". Risiedono sulla membrana mitocondriale esterna.
    * Inibiscono l'apoptosi legando e sequestrando le proteine pro-apoptotiche (BAX, BAK o le BH3-only).
2.  **Proteine Pro-Apoptotiche Effettrici (es. $BAX$, $BAK$):**
    * Sono "gli esecutori". $BAK$ è già sulla membrana mitocondriale, $BAX$ è nel citosol e vi trasloca dopo l'attivazione.
    * Se non inibite da $BCL2$, possono oligomerizzare e formare un poro nella membrana.
3.  **Proteine Pro-Apoptotiche "BH3-only" (es. $BID$, $BIM$, $PUMA$, $NOXA$):**
    * Sono "i sensori" dello stress.
    * Es: un [[Regolazione dell'Entrata in Fase S|danno al DNA]] attiva **$p53$**, che induce la trascrizione di **$PUMA$** e **$NOXA$**.
    * La loro funzione è **attivare** $BAX/BAK$ (direttamente) o **inibire** le anti-apoptotiche $BCL2/BCL-XL$ (indirettamente), "liberando" $BAX/BAK$.

**La Catena di Eventi Intrinseca:**

1.  Un segnale di stress attiva le proteine **BH3-only** (es. $PUMA$).
2.  $PUMA$ si lega e inibisce $BCL2$ (l'anti-apoptotico).
3.  $BAX$ e $BAK$ (i pro-apoptotici effettori), non più inibiti da $BCL2$, sono liberi di oligomerizzare.
4.  **MOMP (Mitochondrial Outer Membrane Permeabilization):** $BAX/BAK$ formano un canale (poro) nella membrana mitocondriale esterna.
5.  **Rilascio del Citocromo C:** Dal poro fuoriescono proteine dall'intermembrana, in particolare il **Citocromo C**.
6.  **Formazione dell'Apoptosoma:** Nel citosol, il Citocromo C si lega alla proteina adattatrice **$APAF-1$**. Questo legame (stimolato da ATP) induce $APAF-1$ ad assemblarsi in un eptamero, una struttura a ruota chiamata **Apoptosoma**.
7.  **Attivazione:** L'apoptosoma recluta la **Procaspasi-9** (iniziatrice).
8.  **Esecuzione:** La Caspasi-9 attivata taglia e attiva le **Caspasi Esecutrici** (es. Caspasi-3), innescando la demolizione cellulare.