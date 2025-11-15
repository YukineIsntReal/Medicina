## Semielementi (Semicelle)

Abbiamo visto che una reazione Redox è composta da due semireazioni. Un **semielemento** (o semicella) è il sistema fisico dove avviene *una singola* semireazione (di ossidazione o di riduzione).

È costituito da:
1.  Un **elettrodo** (conduttore di I specie, es. una lamina di metallo $Zn$).
2.  Un **elettrolita** (conduttore di II specie, es. una soluzione di $ZnSO_4$, che contiene ioni $Zn^{2+}$).

Una cella elettrochimica completa (come una Pila) si ottiene collegando due semielementi diversi (es. $Zn/Zn^{2+}$ e $Cu/Cu^{2+}$) tramite:
* Un **conduttore metallico** esterno (filo) per il flusso di elettroni ($e^-$).
* Un **ponte salino** per il flusso di ioni ($K^+$, $Cl^-$), che chiude il circuito e mantiene l'elettroneutralità nelle due semicelle.

---

## Potenziali Redox Standard ($E^\circ$)

Non è possibile misurare il potenziale assoluto di un singolo semielemento. Possiamo solo misurare una **differenza di potenziale** ($\Delta V$ o $f.e.m.$, forza elettromotrice) tra due semielementi.

Per creare una scala di riferimento, si è scelto un semielemento di riferimento, l'**Elettrodo Standard a Idrogeno** (SHE - Standard Hydrogen Electrode), a cui è stato assegnato per convenzione un potenziale pari a zero.

**SHE:** $2H^+(aq) + 2e^- \rightleftharpoons H_2(g)$
*Condizioni Standard:* $[H^+] = 1 M$, $P_{H_2} = 1 \text{ atm}$, $T = 25^\circ C$.
**$E^\circ_{SHE} = 0.00 V$** (per definizione)

Il **Potenziale di Riduzione Standard ($E^\circ$)** di una qualsiasi coppia redox (es. $Zn^{2+}/Zn$) è la differenza di potenziale (in Volt) misurata in una cella galvanica formata da quel semielemento in condizioni standard (1M, 1 atm, 25°C) e lo SHE.

* Se $E^\circ > 0$ (es. $E^\circ_{Cu^{2+}/Cu} = +0.34 V$): La specie ($Cu^{2+}$) è un **agente ossidante** più forte di $H^+$. Si riduce più facilmente di $H^+$.
* Se $E^\circ < 0$ (es. $E^\circ_{Zn^{2+}/Zn} = -0.76 V$): La specie ($Zn^{2+}$) è un **agente ossidante** più debole di $H^+$. La sua forma ridotta ($Zn(s)$) è un **agente riducente** più forte di $H_2$.

Il potenziale standard di una cella completa ($\Delta E^\circ$ o $E^\circ_{cell}$) si calcola come:
$E^\circ_{cell} = E^\circ_{catodo} - E^\circ_{anodo}$
(Utilizzando *sempre* i potenziali di riduzione standard per entrambe le semicelle).

---

## Equazione di Nernst

Le condizioni standard ($1 M$) non si incontrano quasi mai in contesti reali, specialmente in biologia (dove le concentrazioni sono millimolari, $\mu M$, ecc.).

L'**Equazione di Nernst** corregge il potenziale elettrochimico ($E$) in base alle concentrazioni (e alla temperatura) effettive.

Per una generica semireazione di riduzione:
$aOx + ne^- \rightleftharpoons bRed$

$E = E^\circ - \frac{RT}{nF} \ln Q$

Dove:
* $E$ = Potenziale non-standard
* $E^\circ$ = Potenziale standard
* $R$ = Costante dei gas ($8.314 \text{ J} \cdot \text{mol}^{-1} \cdot \text{K}^{-1}$)
* $T$ = Temperatura in Kelvin (K)
* $n$ = Numero di elettroni ($e^-$) scambiati
* $F$ = Costante di Faraday ($\approx 96485 \text{ C/mol}$, la carica di una mole di elettroni)
* $Q$ = Quoziente di reazione, $\frac{[Red]^b}{[Ox]^a}$ (escludendo solidi e liquidi puri)

Sostituendo le costanti e convertendo a logaritmo in base 10 (a $T = 25^\circ C = 298.15 K$):
$\frac{RT}{F} \ln(Q) \approx 0.0592 \log(Q)$

Equazione di Nernst (a 25°C):
**$E = E^\circ - \frac{0.0592 \text{ V}}{n} \log Q$**

---

## Spontaneità e Lavoro: Gibbs e $\Delta E$

In termodinamica, la **variazione di Energia Libera di Gibbs ($\Delta G$)** rappresenta il lavoro chimico *massimo* (non-PV) ottenibile da una reazione a T e P costanti.

In elettrochimica, il lavoro (elettrico) è dato da:
$Lavoro = Carica \times \text{Differenza di Potenziale}$
Per una mole di reazione, la carica totale trasferita è $(n \cdot F)$ e la d.d.p. è $E_{cell}$.

La relazione fondamentale che lega termodinamica ed elettrochimica è:

**$\Delta G = -nFE_{cell}$**

(Il segno negativo indica che un processo spontaneo, $\Delta G < 0$, *produce* un potenziale positivo, $E_{cell} > 0$, che può compiere lavoro).

* **$\Delta G < 0 \implies E_{cell} > 0$**: Reazione **spontanea** (Pila Galvanica).
* **$\Delta G > 0 \implies E_{cell} < 0$**: Reazione **non spontanea** (richiede lavoro esterno, Cella Elettrolitica).
* **$\Delta G = 0 \implies E_{cell} = 0$**: Reazione all'**equilibrio**.

In condizioni standard:
**$\Delta G^\circ = -nFE^\circ_{cell}$**

---

## Potenziale e Costante di Equilibrio ($K_{eq}$)

Esiste anche una relazione tra $\Delta G^\circ$ e la costante di equilibrio $K_{eq}$:
$\Delta G^\circ = -RT \ln K_{eq}$

Combinando le due equazioni per $\Delta G^\circ$:
$-nFE^\circ_{cell} = -RT \ln K_{eq}$

Risolvendo per $E^\circ_{cell}$:
$E^\circ_{cell} = \frac{RT}{nF} \ln K_{eq}$

A $25^\circ C$ e in $\log_{10}$:
**$E^\circ_{cell} = \frac{0.0592 \text{ V}}{n} \log K_{eq}$**

Questa equazione ci dice che misurando la differenza di potenziale standard ($E^\circ_{cell}$) possiamo calcolare la costante di equilibrio ($K_{eq}$) della reazione redox, e viceversa.

---

## Pile a Concentrazione

Sono un'applicazione diretta dell'Equazione di Nernst. Una pila a concentrazione è formata da **due semielementi identici** (stesse specie chimiche), che differiscono solo per la **concentrazione** della specie in soluzione.

*Esempio:* $Cu(s) | Cu^{2+}(aq, 0.01 M) \quad || \quad Cu^{2+}(aq, 1.0 M) | Cu(s)$

1.  **Catodo:** Semicella più concentrata (la riduzione consuma $Cu^{2+}$)
    $Cu^{2+}(1.0 M) + 2e^- \rightarrow Cu(s)$
2.  **Anodo:** Semicella più diluita (l'ossidazione produce $Cu^{2+}$)
    $Cu(s) \rightarrow Cu^{2+}(0.01 M) + 2e^-$

* Il potenziale standard $E^\circ_{cell}$ è zero (perché $E^\circ_{cat} = E^\circ_{an}$).
* Il potenziale *reale* $E_{cell}$ è generato *solo* dalla differenza di concentrazione, secondo Nernst:

$E_{cell} = E^\circ_{cell} - \frac{0.0592}{n} \log Q \quad$ (dove $Q = \frac{[Cu^{2+}]_{anodo}}{[Cu^{2+}]_{catodo}}$)
$E_{cell} = 0 - \frac{0.0592}{2} \log\left(\frac{0.01}{1.0}\right)$
$E_{cell} = - \frac{0.0592}{2} \log(10^{-2}) = - \frac{0.0592}{2} (-2) = +0.0592 V$

Il processo è spontaneo ($E_{cell} > 0$) e la cella funziona finché le concentrazioni non si eguagliano (raggiungendo l'equilibrio, $Q=1$, $\log Q = 0$, $E_{cell} = 0$).

### Rilevanza Biomedica

Il principio delle pile a concentrazione è **alla base della neurofisiologia**. Le membrane cellulari separano ioni (come $Na^+$, $K^+$, $Cl^-$) a diverse concentrazioni tra l'interno (citoplasma) e l'esterno (fluido interstiziale). Questo gradiente di concentrazione genera una differenza di potenziale elettrico, il **potenziale di membrana a riposo**. L'equazione di Nernst (e la sua estensione, l'equazione di Goldman-Hodgkin-Katz) calcola questo potenziale, che è essenziale per la trasmissione dell'impulso nervoso.