Mentre il [[Primo Principio della Termodinamica]] stabilisce un bilancio energetico (conservazione), non pone limiti sulla *direzione* dei processi. Il **Secondo Principio della Termodinamica** colma questa lacuna, definendo quali processi possono avvenire spontaneamente e introducendo il concetto fondamentale di **Entropia**.

---

## Enunciati Fondamentali e Irreversibilità

Tutti i processi naturali sono **irreversibili**, come definito in [[Primo Principio della Termodinamica#Trasformazioni Reversibili e Irreversibili|precedenza]]. Il Secondo Principio si basa su questa osservazione e può essere formulato in diversi modi equivalenti:

1.  **Enunciato di Clausius:**
    > "È impossibile realizzare una trasformazione il cui *unico* risultato sia il trasferimento di calore da un corpo più freddo a un corpo più caldo."
    * **Significato:** Il calore non fluisce *spontaneamente* dal freddo al caldo. Per farlo (come in un frigorifero), è necessario compiere un lavoro esterno.

2.  **Enunciato di Kelvin-Planck:**
    > "È impossibile realizzare una trasformazione ciclica il cui *unico* risultato sia la conversione completa di calore (assorbito da un'unica sorgente) in lavoro."
    * **Significato:** Non è possibile costruire un motore (macchina termica) con efficienza (rendimento) del 100%. Una parte del calore assorbito deve *necessariamente* essere ceduta a una sorgente più fredda.

---

## Cicli Termodinamici e Macchine Termiche

* **Ciclo Termodinamico:** Una serie di trasformazioni al termine delle quali il sistema torna al suo stato iniziale.
    * Poiché lo stato iniziale e finale coincidono, e l'Energia Interna ($U$) è una funzione di stato, la variazione totale di energia interna in un ciclo è sempre zero: **$\Delta U_{ciclo} = 0$**.
    * Applicando il Primo Principio ($\Delta U = Q - W$): $0 = Q_{tot} - W_{tot} \implies$ **$W_{tot} = Q_{tot}$**
    * Dove $Q_{tot} = Q_{assorbito} - Q_{ceduto}$

* **Macchina Termica:** Un dispositivo che opera secondo un ciclo termodinamico per convertire il calore in lavoro.
    * Assorbe calore ($Q_{ass}$) da una sorgente calda (a $T_{calda}$).
    * Produce lavoro ($W$).
    * Cede calore ($Q_{ced}$) a una sorgente fredda (a $T_{fredda}$).

* **Rendimento ($\eta$):** L'efficienza di una macchina termica. È definito come il rapporto tra il lavoro utile ottenuto e il calore assorbito dalla sorgente calda.
    $\eta = \frac{W}{Q_{ass}} = \frac{Q_{ass} - Q_{ced}}{Q_{ass}} = 1 - \frac{Q_{ced}}{Q_{ass}}$
    * Per l'enunciato di Kelvin, $Q_{ced}$ non può mai essere zero, quindi **$\eta < 1$** (sempre minore del 100%).

### Il Ciclo di Carnot

È un ciclo termodinamico **reversibile** ideale, composto da quattro trasformazioni:
1.  Espansione [[Primo Principio della Termodinamica#1. Trasformazione Isoterma ($T = costante$)|Isoterma]] (a $T_{calda}$, assorbe $Q_{ass}$)
2.  Espansione [[Primo Principio della Termodinamica#4. Trasformazione Adiabatica ($Q = 0$)|Adiabatica]] (si raffredda da $T_{calda}$ a $T_{fredda}$)
3.  Compressione Isoterma (a $T_{fredda}$, cede $Q_{ced}$)
4.  Compressione Adiabatica (si riscalda da $T_{fredda}$ a $T_{calda}$)

**Teorema di Carnot:** Nessuna macchina termica reale operante tra due sorgenti a temperature $T_{calda}$ e $T_{fredda}$ può avere un rendimento superiore a quello di una macchina di Carnot reversibile operante tra le stesse temperature.

Il **rendimento di Carnot** (il massimo teorico possibile) dipende *solo* dalle temperature assolute (in Kelvin) delle sorgenti:

$\eta_{Carnot} = 1 - \frac{T_{fredda}}{T_{calda}}$

---

## Entropia ($S$)

L'entropia è la **funzione di stato** che misura il grado di "disordine" o, più precisamente, il numero di microstati (configurazioni microscopiche) accessibili a un sistema macroscopico.

### Definizione Termodinamica (Clausius)

Per una trasformazione reversibile, la variazione infinitesima di entropia ($dS$) è definita come il rapporto tra il calore scambiato ($dQ_{rev}$) e la temperatura assoluta ($T$) a cui avviene lo scambio:

$dS = \frac{dQ_{rev}}{T}$

Per una trasformazione finita reversibile dallo stato A allo stato B:
$\Delta S = S_B - S_A = \int_{A}^{B} \frac{dQ_{rev}}{T}$

* Unità di misura: $J/K$.

### Implicazioni e Direzione dei Processi

L'entropia è la chiave per comprendere la direzione naturale dei processi. Il Secondo Principio può essere riformulato in termini di entropia:

**L'entropia totale dell'Universo (sistema + ambiente) non diminuisce mai per un processo spontaneo.**

1.  **Processi Reversibili (Ideali):** La variazione di entropia dell'Universo è nulla.
    $\Delta S_{Universo} = \Delta S_{sistema} + \Delta S_{ambiente} = 0$

2.  **Processi Irreversibili (Reali, Spontanei):** La variazione di entropia dell'Universo è sempre positiva (aumenta).
    **$\Delta S_{Universo} = \Delta S_{sistema} + \Delta S_{ambiente} > 0$**

Questo è il motivo per cui il calore fluisce spontaneamente dal caldo al freddo: questo processo massimizza l'aumento dell'entropia totale dell'Universo. Un sistema isolato (come l'Universo) evolve spontaneamente verso lo stato di massima entropia, che corrisponde all'equilibrio termodinamico.

### Interpretazione Statistica (Boltzmann)

A livello microscopico (meccanica statistica), l'entropia è legata al numero di modi ($\Omega$, omega) in cui le particelle di un sistema possono essere disposte per produrre un dato macrostato (P, V, T).

$S = k_B \cdot \ln(\Omega)$

* $k_B$ = Costante di Boltzmann (è $R/N_A$, la costante dei gas per singola molecola).
* $\ln(\Omega)$ = Logaritmo naturale del numero di microstati.

**Significato:** Un sistema evolve verso lo stato macroscopico più probabile, che è quello con il maggior numero di microstati (disposizione più "disordinata"), ovvero lo stato di **massima entropia**.