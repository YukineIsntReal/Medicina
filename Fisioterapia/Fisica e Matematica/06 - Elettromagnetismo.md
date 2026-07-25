L'**elettromagnetismo** è una branca fondamentale della fisica. Nei test d'ingresso per le professioni sanitarie, l'elettrostatica e l'elettrodinamica sono di importanza critica, in quanto i principi elettrici governano l'intera neurofisiologia cellulare (es. pompe ioniche, potenziale di membrana, conduzione saltatoria) e la diagnostica medica.

## Elettrostatica e Legge di Coulomb

Le cariche elettriche ($q$) si misurano in Coulomb (C). In natura esistono cariche positive (es. protoni) e negative (es. elettroni): cariche dello stesso segno si respingono, cariche di segno opposto si attraggono.

### Legge di Coulomb
La forza di interazione elettrostatica $\vec{F}$ tra due cariche puntiformi $q_1$ e $q_2$ poste a una distanza $r$ è direttamente proporzionale al prodotto delle cariche e inversamente proporzionale al quadrato della loro distanza:
$$ F = k_0 \frac{|q_1 \cdot q_2|}{r^2} $$
- **Costante dielettrica nel vuoto ($k_0$):** $k_0 = \frac{1}{4\pi\varepsilon_0} \approx 9 \cdot 10^9 \, \text{N}\cdot\text{m}^2/\text{C}^2$.
- **Costante dielettrica relativa ($\varepsilon_r$):** Se le cariche si trovano in un mezzo materiale (come l'acqua all'interno del corpo umano), la forza elettrostatica diminuisce di un fattore $\varepsilon_r$.
- *Nota per i quiz:* La struttura matematica è identica alla Legge di Gravitazione Universale di Newton, ma ricorda che la forza gravitazionale è solo attrattiva, mentre quella elettrica può essere sia attrattiva che repulsiva.

## Elettrodinamica e Circuiti Elettrici

### Grandezze Fondamentali
- **Intensità di Corrente ($I$):** È la quantità di carica $\Delta q$ che attraversa la sezione trasversale di un conduttore in un determinato intervallo di tempo $\Delta t$. 
  $$ I = \frac{\Delta q}{\Delta t} $$
  Si misura in Ampere (A), che è una grandezza fondamentale del SI (vedi [[01 - Grandezze fisiche, Sistema Internazionale e Vettori]]).
- **Differenza di Potenziale o Tensione ($\Delta V$):** Corrisponde al lavoro necessario per spostare una carica unitaria tra due punti di un campo elettrico. Si misura in Volt (V).
- **Resistenza Elettrica ($R$):** È la grandezza che misura l'ostacolo opposto da un materiale al passaggio della corrente elettrica. Si misura in Ohm ($\Omega$).

### Le Leggi di Ohm

**1. Prima Legge di Ohm**
In un conduttore ohmico (come un filo metallico) a temperatura costante, l'intensità di corrente $I$ è direttamente proporzionale alla differenza di potenziale $\Delta V$ applicata ai suoi capi, e inversamente proporzionale alla resistenza $R$:
$$ \Delta V = R \cdot I $$

**2. Seconda Legge di Ohm**
La resistenza $R$ di un conduttore filoiforme è direttamente proporzionale alla sua lunghezza $l$, inversamente proporzionale alla sua area di sezione trasversale $A$ e dipende dal tipo di materiale tramite una costante chiamata resistività ($\rho$):
$$ R = \rho \frac{l}{A} $$
> **Attenzione nei Test:** Se in un quesito ti dicono che il raggio (o il diametro) di un filo conduttore raddoppia, l'area della sezione trasversale $A = \pi \cdot r^2$ diventa 4 volte più grande. Di conseguenza, la resistenza diventerà la quarta parte!

### Potenza Elettrica (Effetto Joule)
La potenza termica dissipata da un resistore attraversato da corrente (che causa il riscaldamento del filo) si calcola combinando la potenza con la Prima Legge di Ohm:
$$ P = \Delta V \cdot I = R \cdot I^2 = \frac{\Delta V^2}{R} $$
*(Per ripassare il concetto generale di Potenza, puoi richiamare la nota [[03 - Dinamica]]).*

## Collegamenti in Serie e in Parallelo

La corretta individuazione dei collegamenti è vitale per semplificare e risolvere le reti elettriche nei test a crocette.

### Resistenze in Serie
Due o più resistori sono in serie quando sono disposti uno di seguito all'altro, senza biforcazioni, e sono attraversati dalla **stessa intensità di corrente** $I$.
- **Resistenza Equivalente ($R_{eq}$):** È la semplice somma algebrica delle singole resistenze.
  $$ R_{eq} = R_1 + R_2 + \dots + R_n $$
- La differenza di potenziale totale del generatore si ripartisce sui vari resistori: $\Delta V_{tot} = \Delta V_1 + \Delta V_2 + \dots$

### Resistenze in Parallelo
Due o più resistori sono in parallelo quando i loro capi sono collegati agli stessi due nodi. Di conseguenza, sono sottoposti alla **stessa differenza di potenziale** $\Delta V$.
- **Resistenza Equivalente ($R_{eq}$):** Il reciproco della resistenza equivalente è uguale alla somma dei reciproci delle singole resistenze.
  $$ \frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n} $$
- **Formula Rapida (Vitale per i quiz) per soli 2 resistori:** 
  $$ R_{eq} = \frac{R_1 \cdot R_2}{R_1 + R_2} $$
- La corrente totale erogata dal generatore si divide tra i vari rami del parallelo: $I_{tot} = I_1 + I_2 + \dots$

---
**Suggerimenti per i Collegamenti (Wiki):**
- Ti consiglio vivamente di creare una nuova nota chiamata `[[Circuiti RC e Condensatori]]` per completare il quadro dell'elettromagnetismo di base. Potrai sfruttare questa nota per un parallelismo: i condensatori in serie e in parallelo si comportano esattamente all'opposto delle resistenze!