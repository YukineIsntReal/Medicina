La **radioattività** (o decadimento radioattivo) è un processo fisico-nucleare spontaneo attraverso il quale alcuni nuclei atomici, definiti **instabili**, emettono particelle subatomiche o radiazioni elettromagnetiche (fotoni) ad alta energia per raggiungere uno stato di maggiore stabilità.

## Nucleo Instabile e Isotopi Radioattivi

### Nucleo Instabile
Un nucleo atomico è composto da protoni (carichi positivamente) e neutroni (neutri). La stabilità di un nucleo dipende da un delicato equilibrio tra:
1.  **Forza Nucleare Forte:** Attrae protoni e neutroni tra loro, tenendo unito il nucleo.
2.  **Repulsione Elettrostatica:** Respinge i protoni (tutti carichi positivamente) tra loro.

Un nucleo diventa **instabile** (e quindi radioattivo) quando questo equilibrio viene a mancare. Ciò accade tipicamente quando:
* Il nucleo è troppo grande (generalmente per $Z > 83$, dove $Z$ è il numero atomico).
* Il rapporto tra numero di neutroni ($N$) e numero di protoni ($Z$) è sbilanciato (troppi o troppo pochi neutroni per quel numero di protoni).

### Isotopi Radioattivi (Radioisotopi)
Gli **isotopi** sono atomi dello stesso elemento chimico (stesso numero di protoni $Z$) ma con un diverso numero di neutroni ($N$), e quindi un diverso numero di massa ($A = Z + N$).

Spesso, per un dato elemento, esistono isotopi stabili e isotopi instabili. Gli isotopi instabili sono chiamati **isotopi radioattivi** o **radioisotopi**.

*Esempio:* Il Carbonio ($Z=6$)
* **Carbonio-12 ($^{12}C$):** 6 protoni, 6 neutroni. È stabile.
* **Carbonio-13 ($^{13}C$):** 6 protoni, 7 neutroni. È stabile.
* **Carbonio-14 ($^{14}C$):** 6 protoni, 8 neutroni. È instabile (radioattivo).

Il $^{14}C$ è un radioisotopo che subisce un decadimento per raggiungere la stabilità.

---

## Tipi Principali di Decadimento Radioattivo

Quando un nucleo instabile (chiamato *nucleo padre*) decade, si trasforma in un *nucleo figlio* (spesso di un elemento chimico diverso) emettendo una radiazione.

Notazione:
* $X$: Nucleo padre
* $Y$: Nucleo figlio
* $Z$: Numero atomico (protoni)
* $A$: Numero di massa (protoni + neutroni)

### 1. Decadimento Alfa ($\alpha$)

Tipico dei nuclei pesanti ($Z > 83$).
Il nucleo padre emette una **particella alfa ($\alpha$)**, che è un nucleo di Elio ($^4He$), composto da 2 protoni e 2 neutroni.

* **Trasformazione Nucleare:**
    $$^{A}_{Z}X \longrightarrow {^{A-4}_{Z-2}Y} + {^4_2\alpha} \text{ (nucleo di } He\text{)}$$
* **Effetto sul nucleo:**
    * Il numero di massa $A$ diminuisce di $4$.
    * Il numero atomico $Z$ diminuisce di $2$ (l'elemento chimico cambia).

*Esempio:* Decadimento dell'Uranio-238
$$^{238}_{92}U \longrightarrow {^{234}_{90}Th} + {^4_2\alpha}$$

### 2. Decadimento Beta ($\beta$)

Tipico dei nuclei con un rapporto $N/Z$ sbilanciato. Esistono due tipi principali:

#### a) Decadimento Beta Meno ($\beta^-$)
Avviene quando il nucleo ha un **eccesso di neutroni**. Un neutrone ($n$) si trasforma in un protone ($p^+$), emettendo un **elettone ($\beta^-$ o $e^-$)** e un *antineutrino elettronico* ($\bar{\nu}_e$).

* **Trasformazione del Nucleone:**
    $$n \longrightarrow p^+ + e^- + \bar{\nu}_e$$
* **Trasformazione Nucleare:**
    $$^{A}_{Z}X \longrightarrow {^{A}_{Z+1}Y} + {e^-} + \bar{\nu}_e$$
* **Effetto sul nucleo:**
    * Il numero di massa $A$ rimane invariato.
    * Il numero atomico $Z$ aumenta di $1$ (l'elemento cambia).

*Esempio:* Decadimento del Carbonio-14
$$^{14}_{6}C \longrightarrow {^{14}_{7}N} + {e^-} + \bar{\nu}_e$$

#### b) Decadimento Beta Più ($\beta^+$) o Emissione di Positroni
Avviene quando il nucleo ha un **difetto di neutroni** (eccesso di protoni). Un protone si trasforma in un neutrone, emettendo un **positrone ($\beta^+$ o $e^+$)** (l'antiparticella dell'elettrone) e un *neutrino elettronico* ($\nu_e$).

* **Trasformazione del Nucleone:**
    $$p^+ \longrightarrow n + e^+ + \nu_e$$
* **Trasformazione Nucleare:**
    $$^{A}_{Z}X \longrightarrow {^{A}_{Z-1}Y} + {e^+} + \nu_e$$
* **Effetto sul nucleo:**
    * Il numero di massa $A$ rimane invariato.
    * Il numero atomico $Z$ diminuisce di $1$ (l'elemento cambia).

*Esempio:* Decadimento del Fluoro-18 (usato in PET)
$$^{18}_{9}F \longrightarrow {^{18}_{8}O} + {e^+} + \nu_e$$

### 3. Decadimento Gamma ($\gamma$)

Questo decadimento **non** cambia la composizione del nucleo (né $Z$ né $A$).
Spesso, dopo un decadimento $\alpha$ o $\beta$, il nucleo figlio ($Y$) viene lasciato in uno **stato eccitato** (con un eccesso di energia, indicato con $Y^*$).

Per tornare allo stato fondamentale (stabile), il nucleo $Y^*$ si "diseccita" emettendo l'energia in eccesso sotto forma di un **fotone ad altissima energia**, chiamato **raggio gamma ($\gamma$)**.

* **Trasformazione Nucleare:**
    $$^{A}_{Z}Y^* \longrightarrow {^{A}_{Z}Y} + \gamma$$
* **Effetto sul nucleo:**
    * $A$ e $Z$ rimangono invariati.
    * Il nucleo passa da uno stato energetico eccitato a uno stato a energia inferiore.

Il decadimento $\gamma$ è analogo all'emissione di un fotone da parte di un atomo eccitato (come visto nell'assorbimento selettivo), ma coinvolge livelli energetici nucleari, che sono molto più elevati.