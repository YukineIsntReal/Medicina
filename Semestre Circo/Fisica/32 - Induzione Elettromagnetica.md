La **legge di Faraday-Neumann-Lenz** descrive come un campo magnetico variabile nel tempo possa generare una corrente elettrica in un circuito (fenomeno chiamato *induzione elettromagnetica*).

## 1. Flusso del Campo Magnetico ($\Phi_B$)

Per enunciare la legge, dobbiamo prima definire il **flusso del campo magnetico** ($\Phi_B$) attraverso una superficie $S$ (ad esempio, la superficie delimitata da una spira).

È l'analogo del [[Legge di Gauss#1. Flusso del Campo Elettrico|flusso del campo elettrico]]. Per una superficie piana $S$ immersa in un campo magnetico uniforme $\vec{B}$, il flusso è:
$\Phi_S(\vec{B}) = B \cdot S \cdot \cos(\theta) = \vec{B} \cdot \vec{S}$
Dove $\theta$ è l'angolo tra il vettore $\vec{B}$ e il vettore $\vec{S}$ (perpendicolare alla superficie).

L'unità di misura del flusso magnetico è il **Weber** ($Wb$), definito come $1 Wb = 1 T \cdot m^2$.

## 2. Legge di Faraday-Neumann

La legge afferma che:
**Se il flusso magnetico $\Phi_B$ che attraversa la superficie di un circuito (es. una spira) *varia* nel tempo, nel circuito si genera una *forza elettromotrice indotta* (f.e.m. indotta).**

La f.e.m. indotta (che agisce come una [[Corrente Elettrica e Leggi di Ohm#Generatore di Tensione|differenza di potenziale]], $\Delta V$) è pari al *tasso di variazione* (la derivata) del flusso magnetico, cambiato di segno:

$\text{f.e.m.} = - \frac{d\Phi_B}{dt}$

Se il circuito ha $N$ spire (come in un [[Legge di Biot-Savart#C. Solenoide Ideale|solenoide]]), la f.e.m. totale è $N$ volte maggiore:
$\text{f.e.m.} = - N \frac{d\Phi_B}{dt}$

### Come far variare il flusso $\Phi_B = B S \cos(\theta)$?
Il flusso può variare ($\frac{d\Phi_B}{dt} \neq 0$) in tre modi:
1.  **Variando $B$:** Il modulo del campo magnetico cambia nel tempo (es. accendendo/spegnendo un elettromagnete).
2.  **Variando $S$:** L'area della spira investita dal campo cambia (es. sfilando la spira dal campo).
3.  **Variando $\theta$:** L'orientamento della spira rispetto al campo cambia (es. ruotando la spira $\implies$ principio dell'alternatore).

## 3. Legge di Lenz (Il segno Meno)

Il segno negativo nella legge è fondamentale ed è descritto dalla **Legge di Lenz**:
**La corrente indotta ($I_{indotta}$) che scorre nel circuito (a causa della f.e.m. indotta) ha un verso tale da generare un *proprio* campo magnetico indotto ($\vec{B}_{indotto}$) che si *oppone* alla variazione del flusso magnetico ($\Delta \Phi_B$) che l'ha generata.**

In pratica, il sistema "cerca di contrastare" il cambiamento (principio di inerzia elettromagnetica):
* Se il flusso $\Phi_B$ **aumenta**, la corrente indotta crea un $\vec{B}_{indotto}$ opposto al $\vec{B}$ esterno (per frenare l'aumento).
* Se il flusso $\Phi_B$ **diminuisce**, la corrente indotta crea un $\vec{B}_{indotto}$ nello stesso verso del $\vec{B}$ esterno (per frenare la diminuzione).

## 4. Correnti Indotte (o Correnti Parassite)

La f.e.m. indotta non si genera solo nei fili, ma in *qualsiasi* blocco conduttore massiccio (es. un pezzo di metallo, o il tessuto biologico) che sia soggetto a un flusso magnetico variabile.
In questo caso, si generano correnti indotte che circolano in percorsi chiusi all'interno del conduttore, chiamate **correnti parassite** (o *correnti di Foucault*). Queste correnti, per [[Corrente Elettrica e Leggi di Ohm#3. Potenza Elettrica ed Effetto Joule|effetto Joule]], dissipano energia sotto forma di calore.