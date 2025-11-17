La membrana cellulare, dal punto di vista elettrico, è il sistema fondamentale che permette la vita come la conosciamo. La sua funzione si basa sui principi di fisica che abbiamo trattato.

* **Il Condensatore:** Il doppio strato lipidico (un [[Conduttori e Dielettrici#2. Dielettrici (Isolanti)|dielettrico]]) separa due ambienti conduttivi (il citosol e il liquido extracellulare, [[Conduttori e Dielettrici#1. Conduttori|soluzioni elettrolitiche]]). Questo crea una [[Capacità e Condensatori|capacità di membrana]] ($C_m$).
* **Le Resistenze:** La membrana è costellata di canali ionici (proteine), che permettono il passaggio selettivo di ioni ($Na^+, K^+, Cl^-, Ca^{2+}$). Ogni famiglia di canali agisce come una [[Corrente e Leggi di Ohm#2. Leggi di Ohm e Resistenza|resistenza]] ($R_{ion}$) in parallelo alle altre.
* **Il Potenziale:** La cellula mantiene attivamente una [[Potenziale Elettrico#3. Differenza di Potenziale (ΔV)|differenza di potenziale]] ($\Delta V$) tra l'interno e l'esterno.

---

## 1. Il Potenziale di Membrana a Riposo ($V_m$)

Si definisce **Potenziale di Membrana a Riposo** ($V_m$) la differenza di potenziale elettrico stabile che la cellula mantiene tra l'ambiente intracellulare (citosol) e quello extracellulare.

Per convenzione, si pone il potenziale esterno a $0V$. Nelle cellule nervose, il potenziale a riposo è tipicamente **$V_m \approx -70 mV$** (l'interno è negativo rispetto all'esterno).

### Origine del Potenziale a Riposo

Il $V_m$ a riposo è generato da due fattori principali:

1.  **Gradiente di Concentrazione:** Pompe metaboliche attive (come la **Pompa $Na^+/K^+$ ATPasi**) utilizzano ATP per creare e mantenere squilibri di concentrazione ionica.
    * Alto $[K^+]$ **interno** / Basso $[K^+]$ **esterno**.
    * Alto $[Na^+]$ **esterno** / Basso $[Na^+]$ **interno**.
2.  **Permeabilità Selettiva a Riposo:** A riposo, la membrana è quasi impermeabile al $Na^+$, ma è *moderatamente permeabile* al $K^+$ (grazie a canali del $K^+$ detti "passivi" o *leak channels*).

### Il Potenziale di Equilibrio (Equazione di Nernst)

Cosa succede al $K^+$?
1.  Il $K^+$ è spinto *fuori* dalla cellula dal suo **gradiente di concentrazione**.
2.  Uscendo, il $K^+$ (una carica positiva) lascia indietro anioni (proteine, $Cl^-$) non diffusibili, rendendo l'interno della cellula sempre più negativo.
3.  Questa negatività interna genera una [[Fondamenti di Elettrostatica#2. Interazione tra Cariche: Legge di Coulomb|forza elettrica]] che *attrae* il $K^+$ (positivo) e si oppone alla sua ulteriore uscita.
4.  Si raggiunge un **equilibrio elettrochimico** quando la forza chimica (che spinge fuori) è perfettamente bilanciata dalla forza elettrica (che spinge dentro).

La differenza di potenziale $V_m$ a cui si raggiunge questo equilibrio per un singolo ione è data dall'**Equazione di Nernst**:
$E_{ion} = \frac{RT}{zF} \ln \frac{[ion]_{est}}{[ion]_{int}}$
Dove $R$ è la costante dei gas, $T$ la temperatura, $z$ la valenza dello ione e $F$ la costante di Faraday.

* $E_K \approx -90 mV$
* $E_{Na} \approx +60 mV$

Poiché a riposo la membrana è permeabile quasi solo al $K^+$, il $V_m$ a riposo ($-70mV$) è molto vicino a $E_K$ ($-90mV$). Non è identico perché una piccolissima permeabilità al $Na^+$ (che tende a entrare) "sposta" leggermente il potenziale verso $E_{Na}$.

(La formula completa che considera tutti gli ioni è l'Equazione di Goldman-Hodgkin-Katz).

---

## 2. Variazioni del Potenziale: Depolarizzazione e Ripolarizzazione

Le cellule eccitabili (neuroni, muscoli) possono variare drasticamente il loro $V_m$ in risposta a stimoli.

* **Depolarizzazione:** Il $V_m$ diventa **meno negativo** (più positivo). Es: da $-70mV \to -50mV$ o da $-70mV \to +20mV$. È un fenomeno *eccitatorio*.
* **Iperpolarizzazione:** Il $V_m$ diventa **più negativo**. Es: da $-70mV \to -80mV$. È un fenomeno *inibitorio*.
* **Ripolarizzazione:** Il $V_m$ *ritorna* verso il valore di riposo (dopo una depolarizzazione o iperpolarizzazione).

---

## 3. Il Potenziale d'Azione (PdA)

Il **Potenziale d'Azione** è una variazione del $V_m$ rapidissima (dura $\approx 1-2 ms$), stereotipata (sempre uguale) e "tutto-o-nulla", che si propaga lungo l'assone del neurone. È il segnale fondamentale del sistema nervoso.

Si innesca solo se una depolarizzazione iniziale raggiunge un **valore soglia** (es. $-55 mV$).

### Fasi del Potenziale d'Azione

Il PdA è causato dall'apertura e chiusura sequenziale di due tipi di canali: i **canali voltaggio-dipendenti** (VD) per il $Na^+$ e per il $K^+$.

#### Fase 1: Depolarizzazione Rapida (Fase Ascendente)
1.  Uno stimolo depolarizza la membrana fino alla **soglia** ($-55mV$).
2.  Alla soglia, i **canali $Na^+$ VD** si aprono massicciamente.
3.  La permeabilità al $Na^+$ ($P_{Na}$) diventa $\gg P_K$.
4.  Il $Na^+$ (positivo) si riversa *all'interno* della cellula, spinto sia dal gradiente chimico che da quello elettrico.
5.  Questo ingresso di cariche positive fa "schizzare" il $V_m$ verso $E_{Na}$, raggiungendo valori positivi (es. $+30mV$). (Il potenziale si *inverte*).

#### Fase 2: Ripolarizzazione (Fase Discendente)
Avviene per due motivi quasi contemporanei:
1.  **Inattivazione dei canali $Na^+$ VD:** Dopo $\approx 1ms$, i canali $Na^+$ si chiudono (si "inattivano") bloccando l'ingresso di $Na^+$.
2.  **Apertura dei canali $K^+$ VD:** Questi canali (più lenti ad aprirsi) si attivano in risposta alla depolarizzazione.
3.  La $P_K$ ora domina. Il $K^+$ (positivo) si riversa *all'esterno* della cellula, spinto dal suo gradiente.
4.  Questa uscita di cariche positive riporta il $V_m$ verso valori negativi (lo *ripolarizza*).

#### Fase 3: Iperpolarizzazione Postuma
I canali $K^+$ VD sono lenti anche a chiudersi. Rimangono aperti per un breve periodo anche dopo il ritorno a $-70mV$.
Questo fa sì che la $P_K$ sia temporaneamente *maggiore* di quella a riposo, e il $V_m$ si avvicina ancora di più a $E_K$ ($-90mV$), causando una breve **iperpolarizzazione** (es. $-80mV$). Questo crea il *periodo refrattario*, che impedisce al neurone di sparare un altro PdA immediatamente.