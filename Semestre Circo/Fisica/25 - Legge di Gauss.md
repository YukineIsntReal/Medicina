La Legge di Gauss è una delle quattro equazioni di Maxwell e fornisce una relazione fondamentale tra il flusso del campo elettrico attraverso una superficie chiusa e la carica elettrica totale contenuta all'interno di tale superficie.

## 1. Flusso del Campo Elettrico

Il **flusso del campo elettrico** ($\Phi(\vec{E})$) è una misura di quante "linee di forza" del campo elettrico attraversano una determinata superficie.

Per una superficie piana $S$ immersa in un campo elettrico uniforme $\vec{E}$, il flusso è:
$\Phi_S(\vec{E}) = E \cdot S \cdot \cos(\theta) = \vec{E} \cdot \vec{S}$
Dove $\theta$ è l'angolo tra il vettore $\vec{E}$ e il vettore $\vec{S}$ (un vettore perpendicolare alla superficie, con modulo pari all'area $S$).

Per una superficie generica (curva) e un campo non uniforme, il flusso totale si calcola sommando (integrando) i contributi infinitesimi $d\Phi$ su tutta la superficie $S$:
$\Phi_S(\vec{E}) = \int_S \vec{E} \cdot d\vec{S}$

## 2. Enunciato della Legge di Gauss

La Legge di Gauss afferma che:
**Il flusso totale del campo elettrico $\vec{E}$ attraverso una qualsiasi superficie chiusa (detta *superficie gaussiana*) è uguale al rapporto tra la carica elettrica totale netta ($Q_{int}$) contenuta all'interno della superficie e la costante dielettrica del vuoto ($\epsilon_0$).**

In forma integrale:
$\Phi_{\text{chiusa}}(\vec{E}) = \oint_S \vec{E} \cdot d\vec{S} = \frac{Q_{int}}{\epsilon_0}$

Dove $\epsilon_0 \approx 8.854 \times 10^{-12} \frac{C^2}{N \cdot m^2}$.

### Punti Chiave
* **Superficie Gaussiana:** È una superficie immaginaria, chiusa, che scegliamo noi in modo strategico per semplificare il calcolo.
* **$Q_{int}$:** È solo la carica *interna* alla superficie. Le cariche esterne non contribuiscono al flusso totale (tante linee entrano quante escono).
* **Simmetria:** La legge è sempre vera, ma è *utile* per calcolare $\vec{E}$ solo quando la simmetria del problema ci permette di portare $E$ (il modulo del campo) fuori dall'integrale.

---

## 3. Applicazioni (Distribuzioni Simmetriche)

Per usare la Legge di Gauss, la strategia è:
1.  Scegliere una superficie gaussiana $S$ che abbia la stessa simmetria della distribuzione di carica.
2.  Scegliere $S$ in modo che $\vec{E}$ sia (a) parallelo a $d\vec{S}$ (così $\vec{E} \cdot d\vec{S} = E dS$) e (b) costante in modulo su tutta la superficie.
3.  Calcolare l'integrale $\oint E dS = E \oint dS = E \cdot S_{\text{gaussiana}}$.
4.  Determinare la $Q_{int}$ racchiusa da $S$.
5.  Uguagliare: $E \cdot S_{\text{gaussiana}} = \frac{Q_{int}}{\epsilon_0}$ e ricavare $E$.

### A. Sfera Conduttrice Carica (in equilibrio elettrostatico)

Consideriamo una sfera conduttrice di raggio $R$ con una carica totale $Q$. In equilibrio elettrostatico:
1.  La carica $Q$ si distribuisce *unicamente* sulla superficie esterna della sfera.
2.  Il campo elettrico $\vec{E}$ all'interno del conduttore è nullo.

#### Campo all'interno ($r < R$)
* **Superficie Gaussiana:** Sfera concentrica di raggio $r < R$.
* **Carica interna:** $Q_{int} = 0$ (perché tutta la carica è sulla superficie esterna).
* **Legge di Gauss:** $\Phi(\vec{E}) = E \cdot (4 \pi r^2) = \frac{Q_{int}}{\epsilon_0} = 0$
* **Risultato:** $E = 0$ (per $r < R$)

#### Campo all'esterno ($r > R$)
* **Superficie Gaussiana:** Sfera concentrica di raggio $r > R$.
* **Carica interna:** $Q_{int} = Q$ (tutta la carica della sfera).
* **Legge di Gauss:** $\Phi(\vec{E}) = E \cdot (4 \pi r^2) = \frac{Q}{\epsilon_0}$
* **Risultato:** $E = \frac{1}{4 \pi \epsilon_0} \frac{Q}{r^2}$ (per $r > R$)

**Nota:** All'esterno, la sfera si comporta *esattamente* come se tutta la sua carica $Q$ fosse concentrata in un punto nel suo centro.

### B. Piano Infinito Uniformemente Carico

Consideriamo un piano infinito con densità di carica superficiale $\sigma$ (carica per unità di area, $\sigma = \frac{Q}{A}$, misurata in $C/m^2$).
* **Simmetria:** Per simmetria, il campo $\vec{E}$ deve essere perpendicolare al piano (puntando verso l'esterno se $\sigma > 0$).
* **Superficie Gaussiana:** Un cilindro (o un parallelepipedo) con le basi $A$ parallele al piano, posizionato in modo che il piano lo tagli a metà.
* **Flusso:**
    * Il flusso attraverso la superficie laterale del cilindro è nullo (perché $\vec{E}$ è parallelo alla superficie laterale, cioè $\vec{E} \perp d\vec{S}$).
    * Il flusso attraverso le due basi (sopra e sotto) è $E \cdot A$ per ciascuna base.
    * $\Phi_{tot} = (E \cdot A) + (E \cdot A) = 2 E A$.
* **Carica interna:** La carica racchiusa è quella contenuta nell'area $A$ del piano: $Q_{int} = \sigma A$.
* **Legge di Gauss:** $2 E A = \frac{\sigma A}{\epsilon_0}$
* **Risultato:** $E = \frac{\sigma}{2 \epsilon_0}$

**Nota:** Il campo generato da un piano infinito è **uniforme**: non dipende dalla distanza $r$ dal piano.

### C. Filo Infinito Uniformemente Carico

Consideriamo un filo rettilineo infinito con densità di carica lineare $\lambda$ (carica per unità di lunghezza, $\lambda = \frac{Q}{L}$, misurata in $C/m$).
* **Simmetria:** Per simmetria, il campo $\vec{E}$ deve essere radiale e perpendicolare al filo.
* **Superficie Gaussiana:** Un cilindro coassiale al filo, di raggio $r$ e lunghezza $h$.
* **Flusso:**
    * Il flusso attraverso le due basi del cilindro è nullo (perché $\vec{E}$ è parallelo alle basi, $\vec{E} \perp d\vec{S}$).
    * Il flusso attraverso la superficie laterale (area $S = 2 \pi r h$) è $\Phi_{tot} = E \cdot (2 \pi r h)$.
* **Carica interna:** La carica racchiusa è quella contenuta nel tratto di filo di lunghezza $h$: $Q_{int} = \lambda h$.
* **Legge di Gauss:** $E \cdot (2 \pi r h) = \frac{\lambda h}{\epsilon_0}$
* **Risultato:** $E = \frac{\lambda}{2 \pi \epsilon_0 r} = \frac{1}{2 \pi \epsilon_0} \frac{\lambda}{r}$

**Nota:** Il campo diminuisce con la distanza $r$ (non con $r^2$ come per la carica puntiforme).