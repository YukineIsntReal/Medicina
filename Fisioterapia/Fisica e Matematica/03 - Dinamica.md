La **Dinamica** studia il moto dei corpi in relazione alle cause che lo producono o lo modificano: le forze. Mentre la cinematica (vedi [[Cinematica: Moto Rettilineo, Accelerato e Circolare]]) descrive *come* si muove un corpo, la dinamica spiega *perché* lo fa.

## Le Tre Leggi della Dinamica (Principi di Newton)

### 1. Primo Principio (Principio di Inerzia)
Un corpo mantiene il proprio stato di quiete o di moto rettilineo uniforme finché non interviene una forza esterna (o un sistema di forze con risultante non nulla) a modificarne lo stato.
- **Inerzia:** È la tendenza della materia a opporsi alle variazioni di velocità. La massa inerziale misura quantitativamente questa tendenza.

### 2. Secondo Principio (Legge Fondamentale della Dinamica)
La risultante delle forze $\vec{F}$ applicate a un corpo è direttamente proporzionale all'accelerazione $\vec{a}$ che esso subisce, e la costante di proporzionalità è la massa inerziale $m$ del corpo.
$$ \vec{F} = m \cdot \vec{a} $$
- **Unità di misura:** Il Newton ($\text{N}$), definito come $1 \, \text{N} = 1 \, \text{kg} \cdot \text{m/s}^2$.

### 3. Terzo Principio (Principio di Azione e Reazione)
Se un corpo A esercita una forza sul corpo B (azione), il corpo B esercita sul corpo A una forza uguale e contraria (reazione).
$$ \vec{F}_{A \to B} = - \vec{F}_{B \to A} $$
*Attenzione per i quiz:* Le due forze di azione e reazione NON si annullano a vicenda perché sono applicate su corpi **diversi**.

---

## Lavoro ($L$)
Il Lavoro in fisica è il trasferimento di energia meccanica. Se una forza costante $\vec{F}$ produce uno spostamento $\vec{s}$, il lavoro è definito come il prodotto scalare tra i due vettori (concetto visto in [[Misure: Grandezze fisiche, Sistema Internazionale e Vettori]]):
$$ L = \vec{F} \cdot \vec{s} = F \cdot s \cdot \cos(\theta) $$
Dove $\theta$ è l'angolo compreso tra il vettore forza e il vettore spostamento.
- **Unità di misura:** Il Joule ($\text{J}$), definito come $1 \, \text{J} = 1 \, \text{N} \cdot 1 \, \text{m}$.
- **Casi particolari frequenti nei test:**
  - *Forza parallela allo spostamento* ($\theta = 0^\circ$): $L = F \cdot s$ (Lavoro motore, massimo).
  - *Forza opposta allo spostamento* ($\theta = 180^\circ$): $L = - F \cdot s$ (Lavoro resistente, es. forza d'attrito).
  - *Forza perpendicolare allo spostamento* ($\theta = 90^\circ$): $L = 0$ (Forza centripeta, forza peso se lo spostamento è orizzontale).

## Energia e Teoremi Fondamentali

### Energia Cinetica ($K$)
È l'energia che un corpo possiede per il solo fatto di essere in movimento.
$$ K = \frac{1}{2} m v^2 $$
- **Teorema dell'Energia Cinetica (o delle Forze Vive):** Il lavoro totale compiuto su un corpo (dalla risultante delle forze) è uguale alla variazione della sua energia cinetica.
$$ L_{tot} = \Delta K = K_f - K_i = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2 $$

### Energia Potenziale ($U$)
È l'energia immagazzinata in un sistema a causa della posizione dei suoi elementi in un campo di forze conservative (come la gravità o la forza elastica).
- **Energia Potenziale Gravitazionale:** Vicino alla superficie terrestre, a un'altezza $h$ rispetto a un livello di riferimento:
$$ U_g = m g h $$
- **Energia Potenziale Elastica:** Di una molla con costante elastica $k$ compressa o allungata di $x$:
$$ U_e = \frac{1}{2} k x^2 $$

### Conservazione dell'Energia Meccanica
L'energia meccanica totale di un sistema è la somma della sua energia cinetica e potenziale: $E_m = K + U$.
In un sistema in cui agiscono **solo forze conservative** (forze in cui il lavoro non dipende dalla traiettoria ma solo dalla posizione iniziale e finale, es. forza peso, forza elastica), l'energia meccanica si conserva:
$$ E_{m,i} = E_{m,f} \implies K_i + U_i = K_f + U_f $$
*Nota per i problemi:* Questa è spesso l'equazione risolutiva quando ti viene chiesta la velocità di un corpo che cade da una certa altezza (e si trascura l'attrito dell'aria).

---

## Potenza ($P$)
La potenza è la rapidità con cui viene compiuto un lavoro o trasferita energia. È il rapporto tra il lavoro compiuto e l'intervallo di tempo impiegato:
$$ P = \frac{L}{\Delta t} $$
Esiste anche una formula molto utile per i test che lega potenza, forza e velocità costante (se $\vec{F}$ e $\vec{v}$ sono paralleli):
$$ P = F \cdot v $$
- **Unità di misura:** Il Watt ($\text{W}$), definito come $1 \, \text{W} = 1 \, \text{J/s}$.