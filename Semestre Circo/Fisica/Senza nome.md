# Idrodinamica (Fluidi in Movimento)

L'**idrodinamica** (o fluidodinamica) descrive il comportamento dei fluidi quando sono in movimento.

---

## Concetti di Flusso e Portata

### Flusso
Il flusso è il movimento ordinato (o non) delle particelle di un fluido. Per descriverlo si utilizzano le **linee di flusso**: traiettorie immaginarie che indicano la direzione della velocità delle particelle in ogni punto.

### Portata ($Q$)
La portata misura la "quantità" di fluido che attraversa una determinata sezione trasversale ($A$) nell'unità di tempo.

1.  **Portata Volumetrica ($Q_V$)**: Misura il volume di fluido che passa al secondo. È la più comune in fisiologia (es. gittata cardiaca in $L/min$).
    * $Q_V = \frac{\Delta V}{\Delta t} = A \cdot v$
    * Dove $A$ è l'area della sezione e $v$ è la velocità media del fluido perpendicolare all'area.
    * Unità SI: $m^3/s$.

2.  **Portata Massica ($Q_m$)**: Misura la massa di fluido che passa al secondo.
    * $Q_m = \frac{\Delta m}{\Delta t} = \rho \cdot A \cdot v = \rho \cdot Q_V$
    * Unità SI: $kg/s$.

---

## Regimi di Moto

Il modo in cui un fluido scorre è definito "regime di moto".

### Moto Stazionario
Un moto si dice stazionario (o permanente) quando le proprietà del fluido (come velocità $v$, pressione $P$, densità $\rho$) in **qualsiasi punto** dello spazio non cambiano nel tempo.
* Le linee di flusso rimangono fisse.
* Esempio: un fiume che scorre lentamente con livello costante.

### Moto Laminare
È un regime di moto **ordinato**, caratteristico dei flussi a basse velocità e/o alta viscosità.
* Le particelle di fluido si muovono in strati paralleli (le "lamine") che scorrono l'uno sull'altro senza mescolarsi.
* Il profilo di velocità non è uniforme: la velocità è massima al centro del condotto e nulla a contatto con le pareti (a causa della viscosità).
* È il regime di flusso desiderato nella maggior parte del sistema circolatorio.

### Moto Turbolento
È un regime di moto **caotico e disordinato**, caratteristico di alte velocità e/o bassa viscosità.
* Le linee di flusso si intrecciano e si formano vortici (eddi).
* C'è un'intensa miscelazione trasversale del fluido.
* Richiede una maggiore energia per essere mantenuto (maggiore perdita di carico).
* In fisiologia, può verificarsi a valle di una stenosi o nelle grandi arterie (come l'aorta) durante la sistole. I "soffi" cardiaci sono spesso il suono di un flusso turbolento.

---

## Equazione di Continuità (Fluidi Ideali)

Questa equazione è una formulazione della **conservazione della massa**.

Per un **fluido ideale** (incomprimibile, quindi $\rho = costante$) che scorre in un condotto senza perdite o sorgenti, la portata volumetrica ($Q_V$) deve essere costante in ogni sezione del condotto.

* **Formula**: $Q_V = A \cdot v = costante$
* **Applicazione**: Dati due punti (1 e 2) lungo un condotto:
    $A_1 v_1 = A_2 v_2$
* **Conseguenza**: La velocità del fluido è inversamente proporzionale all'area della sezione trasversale.
    * Dove il condotto si restringe ($A_2 < A_1$), la velocità aumenta ($v_2 > v_1$).
    * Dove il condotto si allarga ($A_2 > A_1$), la velocità diminuisce ($v_2 < v_1$).
* **Esempio Fisiologico**: Nel sistema circolatorio, l'area trasversale totale dei capillari è molto maggiore di quella dell'aorta. Per l'equazione di continuità, la velocità del sangue nei capillari è molto bassa, favorendo gli scambi di nutrienti e gas.

---

## Teorema di Bernoulli
Questo teorema è una formulazione della **conservazione dell'energia meccanica** per un fluido ideale (incomprimibile e non viscoso) in moto stazionario.

Afferma che lungo una linea di flusso, la somma di tre termini energetici (per unità di volume) rimane costante:

* **Formula**: $P + \frac{1}{2}\rho v^2 + \rho g h = costante$
* **Termini**:
    * $P$: **Pressione statica**. È l'energia di pressione per unità di volume.
    * $\frac{1}{2}\rho v^2$: **Pressione dinamica**. È l'energia cinetica per unità di volume.
    * $\rho g h$: **Pressione idrostatica** (o potenziale). È l'energia potenziale gravitazionale per unità di volume.

**Interpretazione**: Se il fluido accelera (es. in una strozzatura), $v$ aumenta e $\frac{1}{2}\rho v^2$ aumenta. Se $h$ non cambia, per mantenere la somma costante, la pressione statica $P$ deve diminuire (effetto Venturi).

### Teorema di Torricelli
È un'applicazione specifica del teorema di Bernoulli. Calcola la velocità di efflusso ($v_2$) di un fluido da un piccolo foro in un grande recipiente aperto, posto a una profondità $h$ rispetto alla superficie libera.

$P_1 + \frac{1}{2}\rho v_1^2 + \rho g h_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho g h_2$

* $P_1 = P_2 = P_{atm}$ (entrambi aperti all'atmosfera).
* $v_1 \approx 0$ (il livello del "grande recipiente" scende molto lentamente).
* $h_1 - h_2 = h$ (dislivello).

Semplificando:
$\rho g h = \frac{1}{2}\rho v_2^2 \implies v_2 = \sqrt{2 g h}$
La velocità di efflusso è la stessa di un corpo in caduta libera da un'altezza $h$.

---

## Applicazioni Fisiologiche (Stenosi e Aneurisma)

Questi concetti spiegano le pericolose conseguenze delle alterazioni dei vasi sanguigni. Consideriamo un vaso orizzontale ($h = costante$).

### 1. Stenosi
Una stenosi è un **restringimento** del vaso ($A \downarrow$).
1.  **Equazione di Continuità**: $A \downarrow \implies v \uparrow$. Il sangue deve accelerare bruscamente per passare attraverso la sezione ristretta.
2.  **Teorema di Bernoulli**: $v \uparrow \implies P \downarrow$. L'aumento di energia cinetica ($\frac{1}{2}\rho v^2$) avviene a scapito dell'energia di pressione ($P$).
3.  **Conseguenza**: La pressione laterale esercitata dal sangue sulla parete del vaso nel punto di stenosi **diminuisce**. Se la pressione esterna è maggiore, il vaso può collassare (effetto Venturi). Inoltre, l'alta velocità può danneggiare l'endotelio e generare flusso turbolento (soffio vascolare).

### 2. Aneurisma
Un aneurisma è una **dilatazione** anomala del vaso ($A \uparrow$).
1.  **Equazione di Continuità**: $A \uparrow \implies v \downarrow$. Il sangue rallenta nella sacca aneurismatica. (Questo rallentamento favorisce anche la formazione di trombi).
2.  **Teorema di Bernoulli**: $v \downarrow \implies P \uparrow$. La diminuzione di energia cinetica si traduce in un **aumento** della pressione statica laterale sulla parete.
3.  **Conseguenza**: L'aumento di pressione $P$ agisce su una parete vasale già indebolita e dilatata, aumentando ulteriormente lo stress sulla parete (per la Legge di Laplace) e incrementando esponenzialmente il rischio di rottura.