La **cinetica chimica** è il ramo della chimica che studia la **velocità delle reazioni chimiche** e i **meccanismi** attraverso i quali esse avvengono.

Mentre la termodinamica ci dice *se* una reazione può avvenire (spontaneità, $\Delta G$), la cinetica ci dice *quanto velocemente* avviene.

## 1. Definizioni di Base

### Velocità di Reazione ($v$)
La velocità di reazione è definita come la variazione della concentrazione di un reagente o di un prodotto nell'unità di tempo.

* Per un **reagente** $R$ (la cui concentrazione diminuisce):
    $$v = -\frac{\Delta[R]}{\Delta t}$$
    (Il segno negativo indica che la concentrazione del reagente sta diminuendo).
* Per un **prodotto** $P$ (la cui concentrazione aumenta):
    $$v = +\frac{\Delta[P]}{\Delta t}$$

L'unità di misura è tipicamente Molarità al secondo ($M \cdot s^{-1}$ o $mol \cdot L^{-1} \cdot s^{-1}$).

---

## 2. Fattori che Influenzano la Velocità di Reazione

Diversi fattori possono alterare la velocità con cui avviene una reazione:

* **Natura dei Reagenti:** Lo stato fisico (gas, liquido, solido) e la natura dei legami chimici (jonici vs. covalenti) influenzano la facilità con cui i reagenti possono interagire.
* **Concentrazione dei Reagenti:** Generalmente, un aumento della concentrazione dei reagenti porta a una maggiore frequenza di collisioni e, quindi, a una maggiore velocità di reazione (vedi [[#4 Legge della Velocità Ordine e Molecolarità]]).
* **Temperatura:** Un aumento della temperatura aumenta l'energia cinetica media delle molecole. Ciò porta a collisioni più frequenti e, soprattutto, più energetiche, aumentando drasticamente la velocità di reazione (vedi [[#6 Effetto della Temperatura Legge di Arrhenius]]).
* **Stato Fisico e Area Superficiale:** Se i reagenti sono in fasi diverse (es. un solido in un liquido), la reazione può avvenire solo all'interfaccia. Aumentare l'area superficiale (es. polverizzando un solido) aumenta la velocità.
* **Presenza di un Catalizzatore:** Una sostanza che accelera la reazione senza essere consumata (vedi [[#8 I Catalizzatori]]).

---

## 3. Teoria delle Collisioni e Teoria dello Stato di Transizione

Queste teorie spiegano *come* avvengono le reazioni a livello molecolare.

### Teoria degli Urti Efficaci (Teoria delle Collisioni)
Affinché una reazione avvenga, le molecole dei reagenti devono collidere. Tuttavia, non tutte le collisioni portano alla formazione di prodotti. Una collisione è **efficace** solo se soddisfa due condizioni:

1.  **Energia Sufficiente:** Le molecole che collidono devono possedere un'energia cinetica totale uguale o superiore a un valore minimo, chiamato **Energia di Attivazione ($E_a$)**.
2.  **Orientazione Corretta:** Le molecole devono collidere con un'orientazione geometrica favorevole, che permetta la rottura dei vecchi legami e la formazione dei nuovi.

### L'Energia di Attivazione ($E_a$)
L'**energia di attivazione ($E_a$)** è la barriera energetica minima che deve essere superata affinché i reagenti si trasformino in prodotti. È la "spinta" iniziale necessaria per avviare la reazione.

### Teoria dello Stato di Transizione
Questa teoria affina la teoria delle collisioni. Postula che, durante una collisione efficace, i reagenti passino attraverso uno stato intermedio ad altissima energia, estremamente instabile e non isolabile, chiamato **Stato di Transizione** (o **Complesso Attivato**).

* Lo stato di transizione si trova al picco della barriera energetica (vedi profilo di reazione).
* L'$E_a$ è definita precisamente come la differenza di energia tra i reagenti e lo stato di transizione.

$Reagenti \rightarrow [\text{Stato di Transizione}]^\ddagger \rightarrow Prodotti$

---

## 4. Legge della Velocità, Ordine e Molecolarità

### Legge della Velocità (Rate Law)
La legge della velocità è un'equazione matematica che esprime la relazione tra la velocità di reazione ($v$) e la concentrazione dei reagenti. Per una reazione generica:
$aA + bB \rightarrow \text{Prodotti}$

La legge della velocità ha la forma:
$$v = k \cdot [A]^m \cdot [B]^n$$

* **$k$ (Costante di Velocità):** Una costante di proporzionalità specifica per una data reazione a una data temperatura.
* **$[A], [B]$:** Concentrazioni molari dei reagenti.
* **$m, n$ (Ordini di Reazione Parziali):** Esponenti che indicano come la velocità dipende dalla concentrazione di *ciascun* reagente. **Sono determinati solo sperimentalmente** e *non* sono necessariamente uguali ai coefficienti stoechiometrici ($a, b$).
* **Ordine di Reazione Totale:** È la somma degli ordini parziali ($m + n$).

### Ordine di Reazione
* **Ordine Zero ($m=0$):** $v = k$. La velocità è costante e indipendente dalla concentrazione del reagente $A$. (Comune nelle reazioni enzimatiche a saturazione o nell'assorbimento di farmaci a dose elevata).
* **Primo Ordine ($m=1$):** $v = k[A]$. La velocità è direttamente proporzionale alla concentrazione di $A$. (Fondamentale per il concetto di emivita, $t_{1/2}$, in farmacocinetica).
* **Secondo Ordine ($m=2$):** $v = k[A]^2$ (o $v = k[A][B]$). La velocità è proporzionale al quadrato della concentrazione di $A$ (o al prodotto delle concentrazioni di A e B).

### Molecolarità
La molecolarità si riferisce *esclusivamente* a una **reazione elementare** (vedi sotto) e definisce il numero di specie molecolari che collidono in quel singolo stadio.

* **Unimolecolare:** Una singola molecola si decompone ($A \rightarrow P$).
* **Bimolecolare:** Due molecole collidono ($A+B \rightarrow P$ o $2A \rightarrow P$).
* **Trimolecolare:** Tre molecole collidono (molto raro).

**Importante:** L'ordine di reazione si riferisce alla reazione *complessiva* (sperimentale), mentre la molecolarità si riferisce a un *singolo stadio* (teorico) del meccanismo.

---

## 5. Reazioni a Più Stadi (Meccanismi di Reazione)

La maggior parte delle reazioni chimiche non avviene in un unico passaggio, ma attraverso una sequenza di reazioni elementari. Questa sequenza è chiamata **meccanismo di reazione**.

* **Reazione Elementare:** Un singolo passaggio in un meccanismo di reazione.
* **Intermedio di Reazione:** Una specie che viene *prodotta* in uno stadio elementare e *consumata* in uno stadio successivo. Non compare nell'equazione bilanciata finale.
* **Stadio Rate-Determining (Rate-Determining Step, RDS):** È lo **stadio più lento** dell'intero meccanismo di reazione. Agisce come un "collo di bottiglia" e determina la velocità dell'intera reazione. L'RDS ha l'energia di attivazione ($E_a$) più alta di tutti gli stadi.

---

## 6. Effetto della Temperatura: Legge di Arrhenius

L'aumento della temperatura aumenta la costante di velocità $k$ (e quindi la velocità di reazione) in modo esponenziale. Questa relazione è descritta quantitativamente dall'**Equazione di Arrhenius**:

$$k = A \cdot e^{-E_a / (R \cdot T)}$$

Dove:
* **$k$**: Costante di velocità.
* **$A$**: Fattore pre-esponenziale (o fattore di frequenza). È correlato alla frequenza delle collisioni e al fattore di orientazione.
* **$E_a$**: Energia di attivazione (in $J/mol$).
* **$R$**: Costante universale dei gas ($8.314 \, J \cdot mol^{-1} \cdot K^{-1}$).
* **$T$**: Temperatura assoluta (in Kelvin).

In sintesi, l'equazione mostra che $k$ è molto sensibile a $T$ e $E_a$:
* Un'**alta $E_a$** (grande barriera) significa un $k$ piccolo e una reazione lenta.
* Un'**alta $T$** aumenta il termine esponenziale, aumentando $k$ e la velocità.

---

## 7. I Catalizzatori

Un **catalizzatore** è una sostanza che **aumenta la velocità di una reazione** fornendo un **percorso di reazione alternativo** (un meccanismo diverso) caratterizzato da una **energia di attivazione ($E_a$) più bassa**.

**Caratteristiche chiave:**
1.  **Abbassa $E_a$:** Questo è il suo meccanismo d'azione fondamentale.
2.  **Non viene consumato:** Partecipa alla reazione (spesso formando un intermedio) ma viene rigenerato alla fine.
3.  **Non altera la termodinamica:** Non cambia il $\Delta G$, $\Delta H$ o $\Delta S$ della reazione complessiva.
4.  **Non sposta l'equilibrio:** Accelera *sia* la reazione diretta *che* quella inversa, permettendo di raggiungere l'equilibrio più velocemente, ma non modifica la posizione dell'equilibrio (Costante di equilibrio $K_{eq}$).

### Tipi di Catalizzatori

* **Catalizzatori Omogenei:** Si trovano nella **stessa fase** dei reagenti (es. un acido ($H^+$) in soluzione acquosa che catalizza un'idrolisi).
* **Catalizzatori Eterogenei:** Si trovano in una **fase diversa** dai reagenti (es. un metallo solido come il Platino (Pt) che catalizza l'idrogenazione di un gas).

Gli **enzimi** sono i catalizzatori biologici del nostro corpo. Sono tipicamente proteine (catalizzatori omogenei, in quanto disciolti nel citosol o nei fluidi biologici) estremamente efficienti e specifici.