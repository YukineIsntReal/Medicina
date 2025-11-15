# Soluzioni Tampone ed Equilibrio Acido-Base

Una **soluzione tampone** è una soluzione acquosa che si oppone a variazioni significative di $pH$ in seguito all'aggiunta di moderate quantità di acidi forti o basi forti.

Questa capacità è fondamentale per i sistemi biologici, dove la maggior parte dei processi enzimatici e fisiologici può avvenire solo in un intervallo di $pH$ estremamente ristretto.

## Composizione dei Tamponi

Un sistema tampone è tipicamente composto da:
1.  Un **acido debole** e la sua **base coniugata** (spesso sotto forma di sale).
    * *Esempio:* Tampone acetato $\implies$ Acido acetico ($CH_3COOH$) + Acetato di sodio ($CH_3COONa$).
    * Componente acida: $CH_3COOH$
    * Componente basica: $CH_3COO^-$
2.  Una **base debole** e il suo **acido coniugato** (spesso sotto forma di sale).
    * *Esempio:* Tampone ammoniacale $\implies$ Ammoniaca ($NH_3$) + Cloruro d'ammonio ($NH_4Cl$).
    * Componente basica: $NH_3$
    * Componente acida: $NH_4^+$

### Meccanismo d'Azione

Prendiamo l'esempio del tampone acetato ($HA / A^-$).
* **Aggiunta di Acido Forte ($H_3O^+$):** La componente basica del tampone ($A^-$) neutralizza l'acido aggiunto, trasformandolo nell'acido debole del tampone.
    $A^- + H_3O^+ \rightarrow HA + H_2O$
    (es. $CH_3COO^- + H_3O^+ \rightarrow CH_3COOH + H_2O$)
* **Aggiunta di Base Forte ($OH^-$):** La componente acida del tampone ($HA$) neutralizza la base aggiunta, trasformandosi nella base coniugata del tampone.
    $HA + OH^- \rightarrow A^- + H_2O$
    (es. $CH_3COOH + OH^- \rightarrow CH_3COO^- + H_2O$)

In entrambi i casi, l'acido/base forte aggiunto viene "assorbito" e convertito in un componente debole del sistema, minimizzando così la variazione del $pH$.

---

## Equazione di Henderson-Hasselbalch

Questa equazione è lo strumento fondamentale per calcolare il $pH$ di una soluzione tampone e per progettarne una.

Si parte dalla costante di dissociazione dell'acido debole $HA$:
$HA + H_2O \rightleftharpoons H_3O^+ + A^-$
$K_a = \frac{[H_3O^+][A^-]}{[HA]}$

Risolvendo per $[H_3O^+]$:
$[H_3O^+] = K_a \cdot \frac{[HA]}{[A^-]}$

Applicando l'operatore $p$ ($-\log_{10}$):
$-\log[H_3O^+] = -\log K_a - \log\left(\frac{[HA]}{[A^-]}\right)$

Cambiando il segno dell'ultimo logaritmo e invertendo la frazione:
**$pH = pK_a + \log\left(\frac{[A^-]}{[HA]}\right)$**

Dove:
* $pH$ è il potenziale idrogenionico della soluzione tampone.
* $pK_a$ è il $pK_a$ dell'acido debole del sistema tampone.
* $[A^-]$ è la concentrazione della base coniugata (spesso chiamata "sale").
* $[HA]$ è la concentrazione dell'acido debole (spesso chiamato "acido").

---

## Efficienza di un Sistema Tampone

L'efficienza di un tampone si misura in due modi:

1.  **Potere Tampone (o Capacità Tampone):**
    È la quantità di acido o base forte che un tampone può neutralizzare prima che il suo $pH$ cambi in modo significativo.
    * Il potere tampone è **massimo** quando le concentrazioni dei due componenti sono uguali: **$[A^-] = [HA]$**.
    * In questa condizione, dall'equazione di Henderson-Hasselbalch:
        $pH = pK_a + \log\left(\frac{[A^-]}{[HA]}\right) \implies pH = pK_a + \log(1) \implies$ **$pH = pK_a$**
    * Il potere tampone aumenta all'aumentare della concentrazione assoluta dei componenti (un tampone 1M è più efficiente di un tampone 0.1M).

2.  **Intervallo di Tamponamento:**
    È l'intervallo di $pH$ in cui un tampone è efficace. Convenzionalmente, si definisce come:
    **$pH = pK_a \pm 1$**
    Questo corrisponde a un rapporto $[A^-]/[HA]$ compreso tra $10:1$ e $1:10$.

---

## Equilibrio Acido-Base nei Fluidi Biologici

Il mantenimento del $pH$ fisiologico (omeostasi acido-base) è cruciale per la vita. Il $pH$ del **sangue arterioso** è mantenuto in un intervallo ristrettissimo: **$pH = 7.35 - 7.45$**.
Variazioni al di fuori di questo intervallo (acidosi $pH < 7.35$, alcalosi $pH > 7.45$) compromettono gravemente le funzioni cellulari, in particolare l'attività enzimatica e la struttura delle proteine.

I principali sistemi tampone dell'organismo sono:

### 1. Tampone Acido Carbonico / Bicarbonato ($H_2CO_3 / HCO_3^-$)

È il **sistema tampone extracellulare più importante** (presente nel sangue e nel fluido interstiziale).
$pK_a \approx 6.1$

$CO_2 + H_2O \stackrel{\text{Anidrasi Carbonica}}{\rightleftharpoons} H_2CO_3 \rightleftharpoons H^+ + HCO_3^-$

Sebbene il suo $pK_a$ (6.1) sia lontano dal $pH$ ottimale (7.4), questo sistema è estremamente efficace perché è un **sistema aperto**, finemente regolato da due organi:
* **Polmoni:** Regolano la componente acida ($H_2CO_3$) controllando l'eliminazione di $CO_2$ (ventilazione). Un aumento della $pCO_2$ (ipoventilazione) causa acidosi; una diminuzione (iperventilazione) causa alcalosi.
* **Reni:** Regolano la componente basica ($HCO_3^-$) controllando il riassorbimento di bicarbonato e l'escrezione di $H^+$.

Applicando l'equazione di Henderson-Hasselbalch al sangue ($pH = 7.4$ e $pK_a = 6.1$):
$7.4 = 6.1 + \log\left(\frac{[HCO_3^-]}{[H_2CO_3]}\right)$
$1.3 = \log\left(\frac{[HCO_3^-]}{[H_2CO_3]}\right) \implies \frac{[HCO_3^-]}{[H_2CO_3]} = 10^{1.3} \approx \frac{20}{1}$

Nel sangue, il rapporto tra base (bicarbonato) e acido (acido carbonico/CO2 disciolta) è circa **20:1**, fornendo un'enorme riserva per neutralizzare gli acidi prodotti dal metabolismo.

### 2. Tampone Diidrogeno Fosfato / Idrogenofosfato ($H_2PO_4^- / HPO_4^{2-}$)

$H_2PO_4^- \rightleftharpoons H^+ + HPO_4^{2-}$
$pK_a \approx 7.21$

Questo $pK_a$ è molto vicino al $pH$ fisiologico, rendendolo un tampone teoricamente molto efficiente.
Tuttavia, la sua concentrazione nel sangue è bassa, per cui ha un ruolo secondario nel plasma.
È fondamentale:
* **All'interno delle cellule (tampone intracellulare)**, dove la sua concentrazione è maggiore.
* **Nelle urine (tubuli renali)**, dove gioca un ruolo chiave nell'escrezione di ioni $H^+$ (acidificazione delle urine).

### 3. Proteine come Sistemi Tampone

Le proteine sono **anfoliti** (o zwitterioni), poiché possiedono gruppi funzionali acidi (es. carbossilici, $-COOH$) e basici (es. amminici, $-NH_2$) nelle loro catene laterali (residui amminoacidici).
Possono agire da tampone sia $intra$ che $extra$-cellulare (es. albumina nel plasma).

$Proteina-COOH \rightleftharpoons Proteina-COO^- + H^+$
$Proteina-NH_3^+ \rightleftharpoons Proteina-NH_2 + H^+$

Il gruppo funzionale più importante per il tamponamento a $pH$ fisiologico è l'**anello imidazolico dell'istidina** ($pK_a \approx 6.0 - 7.0$).

Un esempio prominente è l'**Emoglobina** (Hb) nei globuli rossi, che è responsabile di gran parte del potere tampone del sangue (oltre al sistema bicarbonato). L'emoglobina tampona gli $H^+$ prodotti dal metabolismo della $CO_2$ nei tessuti (vedi [[Effetto Bohr]]).

## Riepilogo Tamponi del Sangue

L'efficace stabilità del $pH$ ematico ($7.4 \pm 0.05$) è data dall'azione sinergica di:
1.  **Sistema Bicarbonato (Extracellulare):** Rapido, regolato dai polmoni.
2.  **Emoglobina (Intracellulare - Eritrociti):** Lega $H^+$ e $CO_2$.
3.  **Proteine Plasmatiche (es. Albumina):** Ruolo minore.
4.  **Sistema Fosfato:** Ruolo minore nel sangue, importante nei reni.

L'importanza biomedica è assoluta: il fallimento di questi sistemi o della loro regolazione (polmonare o renale) porta a squilibri acido-base potenzialmente letali (es. [[Acidosi Metabolica]], [[Alcalosi Respiratoria]]).