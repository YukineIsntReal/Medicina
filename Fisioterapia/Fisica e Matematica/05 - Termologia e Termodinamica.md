La **Termodinamica** studia le leggi con cui i sistemi fisici scambiano energia con l'ambiente circostante sotto forma di calore e lavoro (un concetto che puoi rivedere in [[Dinamica: Leggi di Newton, Lavoro, Energia, Potenza e Conservazione]]).

## Temperatura e Calore

Spesso confusi nel linguaggio comune, in fisica e nei quiz rappresentano grandezze ben distinte:
- **Temperatura ($T$):** È un indice dell'energia cinetica media delle particelle di un corpo. Misura lo stato di agitazione termica del sistema. Nel Sistema Internazionale si misura in Kelvin (K). Come visto in [[Misure: Grandezze fisiche, Sistema Internazionale e Vettori]], è una grandezza fondamentale.
  - *Conversione rapida Celsius-Kelvin:* $T(K) = T(^\circ C) + 273.15$
- **Calore ($Q$):** È l'energia termica in transito da un corpo a temperatura maggiore verso uno a temperatura minore. L'unità di misura nel SI è il Joule (J), ma si usa ancora estesamente la caloria (cal) in ambito chimico e nutrizionale.
  - *Equivalente meccanico del calore:* $1 \, \text{cal} = 4.186 \, \text{J}$

### Principio Zero della Termodinamica
Se un corpo A è in equilibrio termico con un corpo B, e B è in equilibrio termico con un corpo C, allora A e C sono in equilibrio termico tra loro (hanno la stessa temperatura).

## Capacità Termica e Calore Specifico
- **Calore Specifico ($c$):** È la quantità di calore necessaria per innalzare di $1 \, \text{K}$ (o $1^\circ \text{C}$) la temperatura di $1 \, \text{kg}$ di una determinata sostanza. È una proprietà intensiva tipica del materiale.
- **Capacità Termica ($C$):** È propria di un intero corpo e dipende dalla sua massa: $C = m \cdot c$.
- **Legge Fondamentale della Termologia:**
  $$Q = c \cdot m \cdot \Delta T$$

## Passaggi di Stato e Calore Latente
Durante un passaggio di stato, la sostanza assorbe o cede calore **senza** variare la propria temperatura. Tutta l'energia fornita o sottratta viene spesa unicamente per rompere o formare i legami intermolecolari.
- **Calore Latente ($\lambda$):** La quantità di calore necessaria per far cambiare di stato $1 \, \text{kg}$ di sostanza a temperatura costante.
  $$Q = m \cdot \lambda$$
  
**Mappa dei Passaggi di Stato (da memorizzare per i test):**
- Solido $\rightarrow$ Liquido: Fusione (assorbe calore)
- Liquido $\rightarrow$ Gas: Evaporazione/Ebollizione (assorbe calore)
- Solido $\rightarrow$ Gas: Sublimazione (assorbe calore)
- Gas $\rightarrow$ Liquido: Condensazione (cede calore)
- Liquido $\rightarrow$ Solido: Solidificazione (cede calore)
- Gas $\rightarrow$ Solido: Brinamento (cede calore)

## Leggi dei Gas Ideali
Un gas ideale (o perfetto) obbedisce a leggi specifiche ed è un modello valido ad alte temperature e basse pressioni. Per analizzare questi stati si ricorre costantemente al concetto di pressione, già approfondito in [[Meccanica dei Fluidi: Pressione, Principi di Archimede, Stevino e Pascal]].

**Equazione di Stato dei Gas Perfetti:**
$$P \cdot V = n \cdot R \cdot T$$
Dove $P$ è la pressione, $V$ il volume, $n$ il numero di moli, $R$ la costante universale dei gas ($8.314 \, \text{J/(mol}\cdot\text{K)}$ oppure $0.082 \, \text{L}\cdot\text{atm/(mol}\cdot\text{K)}$ a seconda delle unità usate nei quiz), e $T$ la temperatura assoluta in Kelvin.

Da questa derivano tre leggi sperimentali per masse di gas costanti:
1. **Legge di Boyle (Trasformazione Isoterma, $T = \text{costante}$):**
   $$P_1 \cdot V_1 = P_2 \cdot V_2$$
2. **Prima Legge di Gay-Lussac o di Charles (Trasformazione Isobara, $P = \text{costante}$):**
   $$\frac{V_1}{T_1} = \frac{V_2}{T_2}$$
3. **Seconda Legge di Gay-Lussac (Trasformazione Isocora, $V = \text{costante}$):**
   $$\frac{P_1}{T_1} = \frac{P_2}{T_2}$$

## Principi della Termodinamica

### Primo Principio (Conservazione dell'Energia)
La variazione dell'energia interna ($\Delta U$) di un sistema chiuso è pari alla differenza tra il calore assorbito dal sistema ($Q$) e il lavoro compiuto dal sistema sull'ambiente ($L$).
$$\Delta U = Q - L$$
> **Attenzione ai Segni (Convenzione Egoistica):** 
> $Q > 0$ se assorbito dal sistema, $Q < 0$ se ceduto all'ambiente.
> $L > 0$ se compiuto dal sistema (espansione, energia che esce), $L < 0$ se subito dal sistema (compressione, energia che entra).

### Secondo Principio
Stabilisce la direzione irreversibile dei processi termodinamici spontanei.
- **Enunciato di Kelvin-Planck:** È impossibile realizzare una macchina termica il cui **unico** risultato sia quello di assorbire calore da un'unica sorgente e trasformarlo integralmente in lavoro. Ci sarà sempre calore disperso.
- **Enunciato di Clausius:** È impossibile realizzare una trasformazione il cui **unico** risultato sia il passaggio di calore da un corpo a temperatura minore a uno a temperatura maggiore (senza compiere lavoro sul sistema, come accade nei frigoriferi).
- **Entropia ($S$):** Grandezza che misura il grado di disordine di un sistema. In un sistema isolato, le trasformazioni spontanee avvengono sempre nel verso in cui l'entropia aumenta ($\Delta S \ge 0$).

---
**Suggerimenti per la tua Wiki (Interconnessioni):**
- Ti consiglio di integrare questa nota con `[[Applicazioni Mediche della Fisica]]`, dove potrai sfruttare la legge dei gas per spiegare, ad esempio, i meccanismi della ventilazione polmonare! Potrai usare il collegamento rapido digitando `[[Termologia e Termodinamica: Calore, Temperatura, Passaggi di Stato e Gas Ideali#^]]` per linkare l'equazione di Boyle direttamente alla fisiologia respiratoria.