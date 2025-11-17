Mentre i fluidi ideali sono un'astrazione (incomprimibili e non viscosi), i **fluidi reali** (come il sangue) presentano una resistenza interna al flusso. Questa resistenza è chiamata **viscosità**.

* **Viscosità ($\eta$)**: È una misura dell'attrito interno di un fluido. Rappresenta la resistenza che gli strati (lamine) di fluido oppongono allo scorrimento l'uno sull'altro.
    * Un fluido con alta viscosità (es. miele) scorre con difficoltà.
    * Un fluido con bassa viscosità (es. acqua) scorre facilmente.
* **Forza Viscosa ($F_v$)**: La forza necessaria per far scorrere uno strato di fluido ($A$) a una certa velocità ($v$) rispetto a un altro, a distanza ($y$), è data dalla **legge di Newton per la viscosità**:
    * $F_v = \eta \cdot A \cdot \frac{dv}{dy}$
    * Unità di misura (SI): Pascal-secondo ($Pa \cdot s$). In medicina si usa spesso il $Poise$ ($P$) o il $centiPoise$ ($cP$). $1 \, cP = 10^{-3} Pa \cdot s$. (L'acqua a 20°C ha $\eta \approx 1 \, cP$, il sangue circa $3-4 \, cP$).

---

## Moto Laminare e Gradiente di Velocità

Come già introdotto, nel moto laminare (tipico dei fluidi viscosi a basse velocità), il fluido scorre in strati paralleli.

* **Adesione alle pareti**: A causa delle forze di adesione tra il fluido e le pareti del condotto (es. endotelio vascolare), lo strato di fluido a diretto contatto con la parete è **fermo** ($v = 0$).
* **Gradiente di Velocità ($\frac{dv}{dy}$)**: La velocità aumenta man mano che ci si sposta dalla parete verso il centro del condotto. Il **gradiente di velocità** è il tasso di variazione della velocità tra strati adiacenti. È massimo vicino alle pareti (dove la velocità cambia rapidamente da 0) e nullo al centro (dove la velocità è massima e costante).

### Profilo Parabolico della Velocità
In un condotto cilindrico rigido (come un'arteria, in prima approssimazione), il moto laminare di un fluido viscoso assume un caratteristico **profilo di velocità parabolico**.

La velocità ($v$) non è uniforme, ma dipende dalla distanza radiale ($r$) dal centro del condotto:

* $v(r) = v_{max} \left( 1 - \frac{r^2}{R^2} \right)$
* **Dove**:
    * $v(r)$ è la velocità alla distanza $r$ dal centro.
    * $R$ è il raggio totale del condotto.
    * $v_{max}$ è la velocità massima al centro del condotto ($r=0$).
    * $v_{parete}$ è la velocità alla parete ($r=R$), che è $v(R) = 0$.

**Nota**: La velocità media ($v_{media}$) in un profilo parabolico è esattamente la metà della velocità massima: $v_{media} = \frac{v_{max}}{2}$.

---

## Legge di Poiseuille
Questa è una delle leggi più importanti in emodinamica (lo studio del flusso sanguigno). La legge di Hagen-Poiseuille descrive la portata ($Q$) di un fluido viscoso in moto laminare attraverso un condotto cilindrico rigido.

La legge stabilisce che la portata volumetrica ($Q_V$) è:
1.  Direttamente proporzionale alla differenza di pressione ai capi del condotto ($\Delta P = P_1 - P_2$).
2.  Direttamente proporzionale alla **quarta potenza** del raggio ($R^4$).
3.  Inversamente proporzionale alla viscosità ($\eta$) del fluido.
4.  Inversamente proporzionale alla lunghezza ($L$) del condotto.

* **Formula**: $Q_V = \frac{\Delta P \cdot \pi \cdot R^4}{8 \cdot \eta \cdot L}$

**Implicazioni Fisiologiche**: L'aspetto cruciale è la dipendenza da $R^4$. Ciò significa che un piccolo cambiamento nel raggio di un vaso sanguigno (vasocostrizione o vasodilatazione) ha un effetto enorme sulla quantità di sangue che può fluire attraverso di esso.
* Se il raggio si dimezza ($R/2$), la portata si riduce di $16$ volte ($2^4$).
* Se il raggio raddoppia ($2R$), la portata aumenta di $16$ volte.

---

## Resistenze Idrauliche (o Vascolari)

Possiamo definire una "resistenza" al flusso idraulico ($R_{id}$) in modo analogo alla legge di Ohm per l'elettricità ($V = I \cdot R$).

* **Definizione**: $R_{id} = \frac{\Delta P}{Q_V}$
    * $\Delta P$ (differenza di pressione) è l'analogo della differenza di potenziale (Tensione, $V$).
    * $Q_V$ (portata) è l'analogo della corrente ($I$).

Combinando questa definizione con la Legge di Poiseuille, otteniamo la resistenza per un singolo condotto:

* **Formula**: $R_{id} = \frac{8 \cdot \eta \cdot L}{\pi \cdot R^4}$

Questa formula quantifica la resistenza che un'arteria o un capillare oppone al flusso sanguigno.

### Resistenze in Serie e in Parallelo
Il sistema circolatorio è un complesso circuito di resistenze.

#### 1. Resistenze in Serie
Si hanno quando il fluido deve attraversare diversi segmenti di condotto uno dopo l'altro (es. aorta $\to$ arteria femorale $\to$ arteria poplitea).
* La portata $Q$ è la stessa attraverso ogni resistenza.
* La differenza di pressione totale $\Delta P_{tot}$ è la somma delle cadute di pressione parziali.
* La resistenza totale equivalente ($R_{eq}$) è la somma delle singole resistenze.
    * $R_{eq (serie)} = R_1 + R_2 + R_3 + ...$

#### 2. Resistenze in Parallelo
Si hanno quando un condotto si ramifica in più condotti paralleli (es. l'aorta che si ramifica nelle arterie principali, o le arteriole che si ramificano nei capillari).
* La differenza di pressione $\Delta P$ è la stessa ai capi di tutti i condotti.
* La portata totale $Q_{tot}$ è la somma delle portate nei singoli rami.
* L'inverso della resistenza totale equivalente è la somma degli inversi delle singole resistenze.
    * $\frac{1}{R_{eq (parallelo)}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + ...$

**Implicazione Fisiologica**: L'organizzazione in parallelo dei capillari è fondamentale. Sebbene un singolo capillare abbia una resistenza molto alta (raggio $R$ piccolissimo), ci sono miliardi di capillari in parallelo. La resistenza totale ($R_{eq}$) del letto capillare è quindi molto più bassa della resistenza delle arteriole che li precedono.