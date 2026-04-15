## 1. Visione d'insieme
La respirazione cellulare è il processo catabolico ed esoergonico attraverso il quale le cellule ricavano energia (sotto forma di ATP) degradando i nutrienti, principalmente il **glucosio**. In presenza di ossigeno (aerobiosi), l'equazione globale è:

$$C_6H_{12}O_6 + 6O_2 \rightarrow 6CO_2 + 6H_2O + Energia (\sim 32 \ ATP)$$

Il processo si divide in tre fasi principali: Glicolisi (nel citoplasma), Ciclo di Krebs (nella matrice mitocondriale) e Fosforilazione Ossidativa (sulle creste mitocondriali).

> [!NOTE] I Trasportatori di Elettroni
> Durante queste vie, l'energia non viene trasformata tutta subito in ATP, ma viene prima "caricata" su coenzimi trasportatori di elettroni, che passano dalla forma ossidata a quella ridotta:
> * $NAD^+ + 2e^- + 2H^+ \rightarrow NADH + H^+$
> * $FAD + 2e^- + 2H^+ \rightarrow FADH_2$

---

## 2. Fase 1: La Glicolisi
Avviene nel **citoplasma** ed è l'unica fase che **non richiede ossigeno** (può avvenire sia in aerobiosi che in anaerobiosi). Consiste in 10 reazioni catalizzate da enzimi specifici che scindono una molecola di glucosio (a 6 atomi di Carbonio) in due molecole di **piruvato** (a 3 atomi di Carbonio).

Si divide in due sotto-fasi:
1. **Fase di investimento:** La cellula "spende" 2 molecole di ATP per attivare il glucosio e renderlo instabile.
2. **Fase di rendimento:** Vengono prodotte 4 molecole di ATP e 2 molecole di NADH.

**Bilancio netto della Glicolisi per 1 molecola di glucosio:**
* $2 \ ATP$ (netti)
* $2 \ NADH$
* $2 \ Piruvato$

---

## 3. Fase Intermedia: La Decarbossilazione Ossidativa
Se c'è ossigeno, il piruvato entra nel **mitocondrio**. Prima di entrare nel Ciclo di Krebs, subisce una reazione preparatoria complessa:
* Perde un atomo di carbonio sotto forma di anidride carbonica ($CO_2$).
* Viene ossidato, producendo un $NADH$.
* Si lega al Coenzima A (CoA), formando l'**Acetil-CoA** (a 2 atomi di Carbonio).
* *Nota bene: Poiché il glucosio genera 2 piruvati, questo processo avviene due volte per ogni glucosio.*

---

## 4. Fase 2: Il Ciclo di Krebs (Ciclo dell'Acido Citrico)
Avviene nella **matrice mitocondriale**. È una via ciclica perché la molecola di partenza viene rigenerata alla fine di ogni giro.
1. L'Acetil-CoA (2C) si unisce all'**ossalacetato** (4C) per formare il **citrato** (6C).
2. Attraverso una serie di ossidazioni e decarbossilazioni, il citrato viene riconvertito in ossalacetato.

**Bilancio per un SINGOLO giro del ciclo (1 molecola di Acetil-CoA):**
* $3 \ NADH$
* $1 \ FADH_2$
* $1 \ ATP$ (o GTP)
* $2 \ CO_2$ (scarto)

> [!WARNING] Focus Test
> Molti quiz chiedono il bilancio per *molecola di glucosio*. In tal caso, devi **raddoppiare** i valori del Ciclo di Krebs, poiché un glucosio genera due Acetil-CoA! (Quindi 6 NADH, 2 FADH2, 2 ATP, 4 CO2).

---

## 5. Fase 3: Catena di Trasporto degli Elettroni e Fosforilazione Ossidativa
Avviene sulle **creste della membrana mitocondriale interna**. È qui che viene generata la stragrande maggioranza dell'ATP.

1. **Catena di trasporto:** Il $NADH$ e il $FADH_2$ cedono i loro elettroni a complessi proteici immersi nella membrana (es. citocromi).
2. **Accettore finale:** L'ossigeno ($O_2$) è l'accettore finale degli elettroni; catturandoli e legandosi a ioni $H^+$, forma **Acqua ($H_2O$)**. Se manca l'ossigeno, la catena si blocca!
3. **Gradiente protonico:** L'energia rilasciata dal passaggio degli elettroni viene usata dalle proteine della catena per pompare ioni $H^+$ dalla matrice verso lo spazio intermembrana, creando un forte gradiente elettrochimico.
4. **Chemiosmosi:** Gli ioni $H^+$ tendono a rientrare nella matrice passando attraverso un enzima canale chiamato **ATP Sintasi**. Questo passaggio fornisce l'energia meccanica/chimica per legare un fosfato all'ADP, creando massicce quantità di **ATP** (circa 26-28 ATP).

---

## 6. Il Metabolismo Anaerobico: Le Fermentazioni
Cosa succede se **non c'è ossigeno**? La catena di trasporto e il Ciclo di Krebs si fermano. La cellula può ricavare energia *solo* dalla Glicolisi (2 miseri ATP). 
Tuttavia, la glicolisi consuma costantemente $NAD^+$. Se tutto il $NAD^+$ diventa $NADH$, la glicolisi si arresta. **Scopo della fermentazione: riossidare il $NADH$ in $NAD^+$ per permettere alla glicolisi di continuare.**
Avvengono entrambe nel citoplasma:

### 6.1 Fermentazione Lattica
Tipica di alcuni batteri (es. lattobacilli) e delle **cellule muscolari umane** in condizioni di sforzo anaerobico.
* Il piruvato viene ridotto direttamente dal NADH per formare **acido lattico** (o lattato).
* Reazione: $Piruvato + NADH + H^+ \rightarrow Acido \ lattico + NAD^+$

### 6.2 Fermentazione Alcolica
Tipica dei lieviti (funghi unicellulari) e alcune piante. Usata per produrre vino, birra e pane.
* Il piruvato viene prima decarbossilato (perdendo $CO_2$) per formare acetaldeide, che poi viene ridotta dal NADH per formare **alcol etilico** (etanolo).
* Reazione: $Piruvato \rightarrow CO_2 + Acetaldeide \xrightarrow{NADH} Etanolo + NAD^+$