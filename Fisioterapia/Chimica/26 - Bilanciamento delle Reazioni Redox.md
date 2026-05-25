Il bilanciamento di una reazione di ossidoriduzione differisce dal bilanciamento chimico ordinario perché, oltre alla **conservazione della massa** (il numero di atomi di ciascun elemento deve essere uguale tra reagenti e prodotti), deve essere rigorosamente rispettata la **conservazione della carica**: il numero di elettroni ceduti dalla specie che si ossida deve essere esattamente uguale al numero di elettroni acquistati dalla specie che si riduce.

Nei test d'ingresso si possono utilizzare due metodi principali a seconda del tipo di reazione e della preferenza personale.

---

## Metodo 1: Variazione del Numero di Ossidazione ($n.o.$)

Questo metodo è generalmente il più rapido ed efficace per i quiz a scelta multipla, specialmente quando la reazione è scritta in forma molecolare completa.

### Algoritmo Passo-Passo

1. **Determinare i $n.o.$**: Calcola il numero di ossidazione di tutti gli elementi e individua l'atomo che si ossida e quello che si riduce.
2. **Calcolare la variazione ($\Delta n.o.$)**: 
   * Determina quanti elettroni perde il singolo atomo che si ossida.
   * Determina quanti elettroni acquista il singolo atomo che si riduce.
   * *Attenzione:* Moltiplica questa variazione per il numero di atomi presenti nella formula chimica del reagente (es. se hai $\text{Cr}_2\text{O}_7^{2-}$, la variazione del cromo va moltiplicata per 2).
3. **Incrociare i coefficienti (Bilancio degli elettroni)**: Trova il minimo comune multiplo ($\text{m.c.m.}$) tra gli elettroni persi e quelli acquistati. Moltiplica i reagenti per i coefficienti necessari affinché il guadagno e la perdita di elettroni si equivalgano.
4. **Bilanciare gli atomi rimanenti**: Bilancia prima i metalli e i non-metalli rimasti esclusi dal calcolo redox, poi l'idrogeno ($\text{H}$) e infine l'ossigeno ($\text{O}$) come verifica finale.

### Esempio Pratico
Bilanciamo la reazione:
$$\text{Cu} + \text{HNO}_3 \rightarrow \text{Cu(NO}_3)_2 + \text{NO}_2 + \text{H}_2\text{O}$$

* **Passo 1 & 2**: Il Rame ($\text{Cu}$) passa da $0$ a $+2$ ($\Delta = +2$, perde $2e^-$). Il Azoto ($\text{N}$) in $\text{HNO}_3$ ha $n.o. = +5$, mentre in $\text{NO}_2$ ha $n.o. = +4$ ($\Delta = -1$, acquista $1e^-$). 
  *(Nota: l'azoto presente in $\text{Cu(NO}_3)_2$ non ha cambiato $n.o.$, è rimasto $+5$).*
* **Passo 3**: Il $\text{m.c.m.}$ tra $2$ e $1$ è $2$. 
  * Moltiplichiamo il componente del rame per $1$.
  * Moltiplichiamo il componente dell'azoto ridotto ($\text{NO}_2$) per $2$.
  $$\text{Cu} + \text{HNO}_3 \rightarrow \text{Cu(NO}_3)_2 + 2\text{NO}_2 + \text{H}_2\text{O}$$
* **Passo 4**: Conta gli atomi di Azoto a destra: ce ne sono $2$ in $\text{Cu(NO}_3)_2$ e $2$ in $2\text{NO}_2$, per un totale di $4$. Mettiamo quindi coefficiente $4$ davanti a $\text{HNO}_3$:
  $$\text{Cu} + 4\text{HNO}_3 \rightarrow \text{Cu(NO}_3)_2 + 2\text{NO}_2 + \text{H}_2\text{O}$$
  Infine, bilanciamo gli idrogeni: a sinistra abbiamo $4\text{H}$, quindi a destra occorrono $2\text{H}_2\text{O}$:
  $$\text{Cu} + 4\text{HNO}_3 \rightarrow \text{Cu(NO}_3)_2 + 2\text{NO}_2 + 2\text{H}_2\text{O}$$
  *(Verifica ossigeni: $4 \cdot 3 = 12$ a sinistra; $6 + 4 + 2 = 12$ a destra. La reazione è bilanciata).*

---

## Metodo 2: Metodo delle Semireazioni (Ionico-Elettronico)

Questo metodo è ideale ed estremamente logico quando la reazione ti viene fornita in **forma ionica netta**. Si basa sulla separazione netta del processo in due semireazioni separate (ossidazione e riduzione).



### Algoritmo Passo-Passo

1. **Identificare e separare**: Trova le specie che cambiano $n.o.$ e scrivi le due semireazioni separate in forma ionica.
2. **Bilanciare la massa (esclusi $\text{H}$ e $\text{O}$)**: Inserisci i coefficienti per avere lo stesso numero di atomi d'elemento a destra e a sinistra in ciascuna semireazione.
3. **Bilanciare Ossigeno e Idrogeno**:
   * **In ambiente acido**: Aggiungi molecole di $\text{H}_2\text{O}$ per bilanciare gli atomi di $\text{O}$, e ioni $\text{H}^+$ per bilanciare gli atomi di $\text{H}$.
   * **In ambiente basico**: Aggiungi molecole di $\text{H}_2\text{O}$ dalla parte in cui c'è carenza di ossigeno e il doppio di ioni $\text{OH}^-$ dalla parte opposta (oppure bilancia inizialmente come se fossi in ambiente acido e poi neutralizza gli $\text{H}^+$ aggiungendo ad ambo i lati lo stesso numero di $\text{OH}^-$).
4. **Bilanciare la carica**: Aggiungi elettroni ($e^-$) a sinistra nella riduzione e a destra nell'ossidazione per rendere uguali le cariche nette dei due lati.
5. **Eguagliare gli elettroni e sommare**: Moltiplica le due semireazioni per opportuni coefficienti affinché gli elettroni scambiati siano uguali, quindi sommale eliminando gli elettroni e semplificando le molecole d'acqua o gli ioni identici presenti da entrambi i lati.

### Esempio Pratico (Ambiente Acido)
Bilanciamo la reazione ionica:
$$\text{Fe}^{2+} + \text{MnO}_4^- \rightarrow \text{Fe}^{3+} + \text{Mn}^{2+}$$

* **Passo 1 (Separazione)**:
  * Semireazione di Ossidazione: $\text{Fe}^{2+} \rightarrow \text{Fe}^{3+}$
  * Semireazione di Riduzione: $\text{MnO}_4^- \rightarrow \text{Mn}^{2+}$ *(il manganese scende da $+7$ a $+2$)*
* **Passo 2 & 3 (Massa, ambiente acido)**:
  * L'ossidazione del ferro è già bilanciata in massa.
  * Per la riduzione del manganese, ci sono $4$ ossigeni a sinistra, aggiungiamo $4\text{H}_2\text{O}$ a destra:
    $$\text{MnO}_4^- \rightarrow \text{Mn}^{2+} + 4\text{H}_2\text{O}$$
    Ora aggiungiamo $8\text{H}^+$ a sinistra per bilanciare l'idrogeno:
    $$\text{MnO}_4^- + 8\text{H}^+ \rightarrow \text{Mn}^{2+} + 4\text{H}_2\text{O}$$
* **Passo 4 (Carica)**:
  * Ossidazione: $\text{Fe}^{2+} \rightarrow \text{Fe}^{3+} + 1e^-$  *(la carica netta è $+2$ da entrambi i lati)*
  * Riduzione: a sinistra la carica totale è $(-1) + (+8) = +7$. A destra è $+2$. Per portarla a $+2$ anche a sinistra aggiungiamo $5e^-$:
    $$\text{MnO}_4^- + 8\text{H}^+ + 5e^- \rightarrow \text{Mn}^{2+} + 4\text{H}_2\text{O}$$
* **Passo 5 (Eguagliare e sommare)**:
  Il ferro scambia $1e^-$, il manganese $5e^-$. Moltiplichiamo l'ossidazione per $5$:
  $$5 \cdot (\text{Fe}^{2+} \rightarrow \text{Fe}^{3+} + 1e^-)$$
  Sommiamo le due semireazioni:
  $$5\text{Fe}^{2+} + \text{MnO}_4^- + 8\text{H}^+ + 5e^- \rightarrow 5\text{Fe}^{3+} + 5e^- + \text{Mn}^{2+} + 4\text{H}_2\text{O}$$
  Semplificando i $5e^-$ da entrambi i lati otteniamo la reazione finale bilanciata:
  $$5\text{Fe}^{2+} + \text{MnO}_4^- + 8\text{H}^+ \rightarrow 5\text{Fe}^{3+} + \text{Mn}^{2+} + 4\text{H}_2\text{O}$$

---
## 💡 Strategia Rapida da Test (Trucco dell'Escluso)
Se durante il test ti trovi davanti a una redox complessa e hai poco tempo, **non bilanciare tutto il processo**. Guarda le opzioni di risposta: spesso basta calcolare solo il coefficiente del riducente e dell'ossidante tramite l'incrocio del $\Delta n.o.$ (Punti 2 e 3 del primo metodo) per trovare l'unica alternativa corretta tra quelle proposte!

---
Collegamenti correlati: 
* Concetti base e definizioni: [[Reazioni di ossidoriduzione (Redox)]]
* Struttura atomica e tavola periodica: [[Tavola Periodica]]