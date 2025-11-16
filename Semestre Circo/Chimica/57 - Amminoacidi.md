Gli **amminoacidi** (o aminoacidi) sono le molecole organiche che costituiscono i "mattoni" (monomeri) delle **proteine**. Esistono 20 amminoacidi standard codificati dal DNA.

## Struttura Generale

Ogni amminoacido (ad eccezione della prolina, che è tecnicamente un *imminoacido*) possiede una struttura comune:

1.  Un **Carbonio alfa** ($C\alpha$) centrale.
2.  Un **Gruppo Amminico** ($-NH_2$).
3.  Un **Gruppo Carbossilico** ($-COOH$).
4.  Un atomo di **Idrogeno** ($-H$).
5.  Una **Catena Laterale** (o **Gruppo R**), che differenzia i 20 amminoacidi.

A pH fisiologico (circa $7.4$), il gruppo amminico è protonato ($-NH_3^+$) e il gruppo carbossilico è deprotonato ($-COO^-$). In questa forma, l'amminoacido è uno **zwitterione** (o ione dipolare) con carica netta zero.

## Stereochimica e Proiezioni di Fischer

### Chiralità
Ad eccezione della **Glicina** (il cui gruppo R è un singolo atomo di $H$), il carbonio alfa ($C\alpha$) di tutti gli amminoacidi è legato a quattro gruppi differenti. Questo rende il $C\alpha$ un **centro chirale** (o stereocentro).

Una molecola con un centro chirale esiste in due forme speculari non sovrapponibili, chiamate **enantiomeri**. Questi sono designati come **L** (levo, sinistra) e **D** (destro, destra).

> [!important]
> Nelle proteine degli organismi viventi, quasi esclusivamente gli amminoacidi si trovano nella configurazione **L**. Gli amminoacidi D sono rari e si trovano solo in alcune pareti cellulari batteriche o in peptidi antibiotici.

### Proiezioni di Fischer
La convenzione di Fischer è un metodo standard per rappresentare in 2D la stereochimica 3D di una molecola chirale.

* Si disegna una croce con il $C\alpha$ all'intersezione.
* I legami **verticali** rappresentano i gruppi che si proiettano *dietro* il piano del foglio. Per convenzione, il gruppo a più alta ossidazione ($COOH$) sta in alto e la catena laterale ($R$) in basso.
* I legami **orizzontali** rappresentano i gruppi che si proiettano *davanti* al piano (verso l'osservatore).

La distinzione L/D si basa sulla posizione del **gruppo amminico** ($-NH_2$):

* **L-Amminoacido:** Il gruppo $-NH_2$ si trova a **sinistra** (Left) nella proiezione di Fischer.
* **D-Amminoacido:** Il gruppo $-NH_2$ si trova a **destra** (Right) nella proiezione di Fischer.

**Esempio: L-Alanina vs D-Alanina**

$$
\begin{array}{c}
\text{L-Alanina} \\
\Large
\begin{array}{c@{\,}c@{\,}c}
& \text{COOH} & \\
& | & \\
\text{H}_2\text{N} & - & \text{C} & - & \text{H} \\
& | & \\
& \text{CH}_3 & \\
\end{array}
\end{array}
\qquad \qquad
\begin{array}{c}
\text{D-Alanina} \\
\Large
\begin{array}{c@{\,}c@{\,}c}
& \text{COOH} & \\
& | & \\
\text{H} & - & \text{C} & - & \text{NH}_2 \\
& | & \\
& \text{CH}_3 & \\
\end{array}
\end{array}
$$

*Nota: La Treonina (Thr) e la Isoleucina (Ile) hanno un *secondo* centro chirale sulla loro catena laterale, ma la designazione L/D si riferisce sempre alla configurazione del $C\alpha$.*

## Proprietà Acido-Base e Punto Isoelettrico

Gli amminoacidi sono **molecole anfotere** (o anfoliti), in quanto possono agire sia da acidi (donatori di protoni) che da basi (accettori di protoni).

Questo è dovuto alla presenza di almeno due gruppi ionizzabili:
1.  Il gruppo $\alpha$-carbossilico ($-COOH$)
2.  Il gruppo $\alpha$-amminico ($-NH_3^+$)

### Valori di $pKa$
Ogni gruppo ionizzabile è caratterizzato da un **$pKa$**, che rappresenta il $pH$ al quale il gruppo è per il 50% in forma protonata (acida) e per il 50% in forma deprotonata (base coniugata).

* **Gruppo $\alpha$-carbossilico ($pKa_1$):** È un acido relativamente forte. $pKa_1 \approx 2.0 - 2.4$
    * A $pH < pKa_1$ (es. $pH=1$): Prevale la forma protonata $-COOH$ (carica 0).
    * A $pH > pKa_1$ (es. $pH=7$): Prevale la forma deprotonata $-COO^-$ (carica -1).
* **Gruppo $\alpha$-amminico ($pKa_2$):** È un acido debole (la sua forma protonata). $pKa_2 \approx 9.0 - 9.6$
    * A $pH < pKa_2$ (es. $pH=7$): Prevale la forma protonata $-NH_3^+$ (carica +1).
    * A $pH > pKa_2$ (es. $pH=11$): Prevale la forma deprotonata $-NH_2$ (carica 0).
* **Catena Laterale ($pKa_R$):** Gli amminoacidi acidi (Asp, Glu) e basici (Lys, Arg, His), più Cys e Tyr, hanno un terzo $pKa$ per il loro gruppo R.

### Punto Isoelettrico ($pI$)

> [!important] Definizione
> Il **Punto Isoelettrico ($pI$)** è il valore di $pH$ specifico al quale la carica elettrica netta dell'amminoacido è esattamente **zero**.

In questo punto, la molecola esiste quasi esclusivamente come **zwitterione** (carica $+1$ e $-1$, netto 0) e presenta la sua **minima solubilità** in acqua.

#### Calcolo del $pI$

Il calcolo del $pI$ dipende dal numero di gruppi ionizzabili.

**1. Amminoacidi Neutri (Gruppo R non ionizzabile)**
(Glicina, Alanina, Valina, Leucina, Isoleucina, Metionina, Prolina, Fenilalanina, Triptofano, Serina, Treonina, Asparagina, Glutammina)

Hanno solo due $pKa$ ($pKa_1$ e $pKa_2$). Il $pI$ è la media aritmetica di questi due valori.
$$
pI = \frac{pKa_1 + pKa_2}{2}
$$
*Esempio (Alanina):* $pKa_1 \approx 2.3$, $pKa_2 \approx 9.7$. $pI = (2.3 + 9.7) / 2 = 6.0$.
A $pH = 6.0$, la carica netta dell'Alanina è 0.

**2. Amminoacidi Acidi (Gruppo R acido)**
(Acido Aspartico, Acido Glutammico)

Hanno tre $pKa$: $pKa_1$ ($\alpha$-carbossile), $pKa_R$ ($R$-carbossile) e $pKa_2$ ($\alpha$-ammino).
Lo zwitterione (carica 0) è "intrappolato" tra i due $pKa$ più acidi. Il $pI$ si calcola come media dei due gruppi acidi.
$$
pI = \frac{pKa_1 + pKa_R}{2}
$$
*Esempio (Ac. Aspartico):* $pKa_1 \approx 2.0$, $pKa_R \approx 3.9$, $pKa_2 \approx 9.9$.
$pI = (2.0 + 3.9) / 2 = 2.95$. A $pH$ fisiologico ($\sim 7.4$), l'Aspartato ha carica netta -1.

**3. Amminoacidi Basici (Gruppo R basico)**
(Lisina, Arginina, Istidina)

Hanno tre $pKa$: $pKa_1$ ($\alpha$-carbossile), $pKa_2$ ($\alpha$-ammino) e $pKa_R$ ($R$-gruppo basico).
Lo zwitterione (carica 0) è "intrappolato" tra i due $pKa$ più basici. Il $pI$ si calcola come media dei due gruppi basici.
$$
pI = \frac{pKa_R + pKa_2}{2}
$$
*Esempio (Lisina):* $pKa_1 \approx 2.2$, $pKa_2 \approx 9.0$, $pKa_R \approx 10.5$.
$pI = (9.0 + 10.5) / 2 = 9.75$. A $pH$ fisiologico ($\sim 7.4$), la Lisina ha carica netta +1.
*(Nota: L'Istidina è un caso particolare con $pKa_R \approx 6.0$. Il suo $pI = (6.0 + 9.2) / 2 = 7.6$, molto vicino al $pH$ fisiologico, permettendole di agire come tampone).*

## Nomenclatura e Abbreviazioni

Ogni amminoacido ha un nome completo, un'abbreviazione a 3 lettere e un simbolo a 1 lettera.

| Nome Completo | 3 Lettere | 1 Lettera |
| :--- | :---: | :---: |
| Alanina | Ala | A |
| Arginina | Arg | R |
| Asparagina | Asn | N |
| Acido Aspartico | Asp | D |
| Cisteina | Cys | C |
| Glutammina | Gln | Q |
| Acido Glutammico | Glu | E |
| Glicina | Gly | G |
| Istidina | His | H |
| Isoleucina | Ile | I |
| Leucina | Leu | L |
| Lisina | Lys | K |
| Metionina | Met | M |
| Fenilalanina | Phe | F |
| Prolina | Pro | P |
| Serina | Ser | S |
| Treonina | Thr | T |
| Triptofano | Trp | W |
| Tirosina | Tyr | Y |
| Valina | Val | V |

## Classificazione in base al Gruppo R

La proprietà chimica del gruppo R determina la struttura tridimensionale e la funzione della proteina.

### 1. Amminoacidi Apolari (Idrofobici)

Generalmente si trovano all'interno (core) delle proteine, lontano dall'acqua.

* **Gruppi R Alifatici:**
    * **Glicina** (Gly, G): Il gruppo R è solo un $H$. È l'unico amminoacido non chirale; molto flessibile.
    * **Alanina** (Ala, A): Gruppo R = $-CH_3$ (metile).
    * **Valina** (Val, V): Gruppo R ramificato.
    * **Leucina** (Leu, L): Gruppo R ramificato.
    * **Isoleucina** (Ile, I): Gruppo R ramificato (isomero della Leucina).
    * **Metionina** (Met, M): Contiene zolfo ($S$) in un gruppo tioetere, ma è comunque apolare.
    * **Prolina** (Pro, P): L'unico imminoacido. Il gruppo R si lega sia al $C\alpha$ che all' $N$ amminico, creando una struttura ciclica rigida. Spesso "interrompe" le eliche alfa.

* **Gruppi R Aromatici:**
    * **Fenilalanina** (Phe, F): Fortemente idrofobica (anello benzenico).
    * **Triptofano** (Trp, W): Gruppo R più grande (anello indolico).

### 2. Amminoacidi Polari (Idrofili)

Si trovano sulla superficie delle proteine, interagendo con l'acqua.

* **Polari Neutri (Non carichi a pH 7):**
    * **Serina** (Ser, S): Gruppo R con $-OH$ (alcol primario).
    * **Treonina** (Thr, T): Gruppo R con $-OH$ (alcol secondario).
    * **Cisteina** (Cys, C): Contiene zolfo ($S$) in un gruppo tiolico ($-SH$). Due cisteine possono formare un **ponte disolfuro** ($-S-S-$), fondamentale per la struttura terziaria.
    * **Tirosina** (Tyr, Y): È aromatica (come Phe) ma ha un $-OH$, che la rende polare.
    * **Asparagina** (Asn, N): Gruppo R ammidico (derivato dall'Aspartato).
    * **Glutammina** (Gln, Q): Gruppo R ammidico (derivato dal Glutammato).

* **Polari Carichi (Acidi e Basici a pH 7):**
    * **Acidi (Carica Negativa - COO$^-$-):**
        * **Acido Aspartico** (Asp, D): (Forma ionica: Aspartato)
        * **Acido Glutammico** (Glu, E): (Forma ionica: Glutammato)
    * **Basici (Carica Positiva - NH$_3$ $^+$ o simile):**
        * **Lisina** (Lys, K): Gruppo amminico primario sulla catena laterale.
        * **Arginina** (Arg, R): Gruppo guanidinico, fortemente basico.
        * **Istidina** (His, H): Gruppo imidazoico. La sua basicità è debole e il suo $pKa$ è vicino al $pH$ fisiologico ($pKa \approx 6.0-6.5$), il che la rende cruciale nei siti attivi degli enzimi (es. emoglobina) poiché può agire sia da donatore che da accettore di protoni.

## Amminoacidi Essenziali e Non Essenziali

Questa classificazione non riguarda la struttura, ma la nutrizione umana.

* **Amminoacidi Essenziali (EAA):**
    * L'organismo umano non è in grado di sintetizzarli *de novo* (o non in quantità sufficiente).
    * Devono essere obbligatoriamente introdotti con la dieta.
    * Sono 9: **Fenilalanina**, **Valina**, **Treonina**, **Triptofano**, **Isoleucina**, **Metionina**, **Istidina**, **Leucina**, **Lisina**.
    * (Mnemotecnica: "PVT TIM HALL", anche se Arginina (A) è considerata *semi-essenziale* o *condizionatamente essenziale*).

* **Amminoacidi Non Essenziali (NEAA):**
    * L'organismo può sintetizzarli, solitamente a partire da intermedi metabolici (es. dal ciclo di Krebs).
    * Sono 11: Alanina, Arginina (semi-essenziale), Asparagina, Aspartato, Cisteina, Glutammato, Glutammina, Glicina, Prolina, Serina, Tirosina.
    * *Nota: La Tirosina è sintetizzata dalla Fenilalanina (essenziale). Se la dieta è carente di Phe, anche Tyr diventa essenziale.*