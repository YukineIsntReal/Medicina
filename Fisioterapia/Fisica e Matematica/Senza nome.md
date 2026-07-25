# Dinamica: Leggi di Newton, Lavoro, Energia, Potenza e Conservazione

La **Dinamica** studia il moto dei corpi in relazione alle cause che lo producono o lo modificano: le forze. Mentre la cinematica (vedi [[Cinematica: Moto Rettilineo, Accelerato e Circolare]]) descrive come si muove un corpo, la dinamica spiega perché lo fa.

## Principi della Dinamica (Leggi di Newton)

### 1. Primo Principio (Principio di Inerzia)
Un corpo mantiene il proprio stato di quiete o di moto rettilineo uniforme finché non interviene una forza esterna (o un sistema di forze con risultante non nulla) a modificarne lo stato. La tendenza della materia a opporsi alle variazioni di velocità è quantificata dalla sua massa inerziale.

### 2. Secondo Principio (Legge Fondamentale)
La risultante delle forze $\vec{F}$ applicate a un corpo è direttamente proporzionale all'accelerazione $\vec{a}$ che esso subisce. La costante di proporzionalità è la massa inerziale $m$ del corpo.
$$ \vec{F} = m \cdot \vec{a} $$
L'unità di misura è il Newton (N), definito come $1 \, \text{N} = 1 \, \text{kg} \cdot \text{m/s}^2$.

### 3. Terzo Principio (Principio di Azione e Reazione)
Se un corpo A esercita una forza sul corpo B (azione), il corpo B esercita sul corpo A una forza uguale e contraria (reazione). 
$$ \vec{F}_{A \to B} = - \vec{F}_{B \to A} $$
Nei quiz è vitale ricordare che le forze di azione e reazione NON si annullano a vicenda, poiché sono applicate su corpi diversi.

---

## Lavoro ($L$)
Il Lavoro in fisica è il trasferimento di energia meccanica. Se una forza costante $\vec{F}$ produce uno spostamento $\vec{s}$, il lavoro è definito come il prodotto scalare tra i due vettori:
$$ L = \vec{F} \cdot \vec{s} = F \cdot s \cdot \cos(\theta) $$
L'angolo $\theta$ è quello compreso tra il vettore forza e il vettore spostamento. L'unità di misura è il Joule (J).

Per visualizzare il concetto di lavoro meccanico in modo pratico, pensa alla forza applicata per sbloccare un pistone incastrato all'interno di un sistema complesso di ingranaggi: finché non avviene uno spostamento reale del componente lungo la sua sede, il lavoro fisico compiuto dalla forza motrice rimane nullo, indipendentemente dall'intensità dello sforzo applicato.

**Casi notevoli per i test:**
- Forza parallela allo spostamento ($\theta = 0^\circ$): Lavoro motore massimo ($L = F \cdot s$).
- Forza opposta allo spostamento ($\theta = 180^\circ$): Lavoro resistente, tipico della forza d'attrito ($L = -F \cdot s$).
- Forza perpendicolare allo spostamento ($\theta = 90^\circ$): Lavoro nullo ($L = 0$).

## Energia e Teoremi Fondamentali

### Energia Cinetica ($K$)
È l'energia che un corpo possiede per il solo fatto di essere in movimento a una certa velocità $v$.
$$ K = \frac{1}{2} m v^2 $$

### Teorema dell'Energia Cinetica (Forze Vive)
Il lavoro totale compiuto su un corpo dalla risultante delle forze è sempre uguale alla variazione della sua energia cinetica.
$$ L_{tot} = \Delta K = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2 $$

### Energia Potenziale ($U$)
L'energia potenziale è l'energia immagazzinata in un sistema a causa della posizione dei suoi elementi in un campo di forze conservative.
- **Gravitazionale:** In prossimità della superficie terrestre, a un'altezza $h$ rispetto a un livello di riferimento: $U_g = m g h$
- **Elastica:** Relativa a una molla di costante $k$ compressa o allungata di $x$: $U_e = \frac{1}{2} k x^2$

### Conservazione dell'Energia Meccanica
L'energia meccanica totale di un sistema è la somma della sua energia cinetica e potenziale ($E_m = K + U$). In un sistema in cui agiscono solo forze conservative (come forza peso o elastica), l'energia meccanica si conserva dal punto iniziale al punto finale:
$$ K_i + U_i = K_f + U_f $$

---

## Potenza ($P$)
La potenza definisce la rapidità con cui viene compiuto un lavoro o trasferita energia. È il rapporto tra il lavoro compiuto e l'intervallo di tempo impiegato:
$$ P = \frac{L}{\Delta t} $$
Nei quiz è spesso utile ricorrere alla formula che lega potenza, forza e velocità costante (quando forza e spostamento sono paralleli):
$$ P = F \cdot v $$
L'unità di misura è il Watt (W), pari a $1 \, \text{J/s}$.