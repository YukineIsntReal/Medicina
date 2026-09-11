Nei fluidi, le molecole all'interno della massa liquida sono soggette a forze di coesione (attrattive) uguali in tutte le direzioni. Le molecole sulla superficie, invece, non hanno molecole "sopra" di sé. Questo crea una forza netta di coesione diretta verso l'interno del liquido.

Questo squilibrio di forze genera la **tensione superficiale**.

---

## Tensione Superficiale ($\sigma$)

La tensione superficiale è la tendenza di un fluido a opporsi a un aumento della sua area superficiale. Può essere definita in due modi equivalenti:

1.  **Come Energia**: L'energia ($E$) necessaria per aumentare l'area superficiale ($A$) di una quantità unitaria.
    * $\sigma = \frac{E}{A}$ (Unità: $J/m^2$)
2.  **Come Forza**: La forza ($F$) per unità di lunghezza ($L$) che agisce tangenzialmente alla superficie, opponendosi alla sua espansione.
    * $\sigma = \frac{F}{L}$ (Unità: $N/m$)

### Effetti su Piccole Quantità di Liquido
La tensione superficiale è la forza che "tira" la superficie del liquido per farle assumere la **minima area possibile** a parità di volume.
* **Gocce Sferiche**: Per un dato volume, la forma geometrica con la minima superficie è la sfera. Ecco perché piccole gocce di liquido (o bolle) tendono ad essere sferiche.
* **Pressione Interna**: La tensione superficiale crea una pressione aggiuntiva all'interno di una goccia o bolla (vedi Legge di Laplace).

---

## Fenomeni di Capillarità
La capillarità è un fenomeno che descrive il comportamento dei liquidi all'interno di tubi molto stretti (capillari), ed è il risultato dell'interazione tra due forze:

* **Forze di Coesione**: Forze attrattive tra molecole dello stesso liquido (causano la tensione superficiale).
* **Forze di Adesione**: Forze attrattive tra le molecole del liquido e le molecole della parete del contenitore (es. vetro, tessuto biologico).

### Interfacce Piane e Curve (Menisco)
L'interfaccia tra un liquido e l'aria (o un altro fluido) in un contenitore è chiamata **menisco**.

1.  **Interfaccia Piana**: Si verifica in un contenitore largo, dove gli effetti di parete sono trascurabili, o se le forze di adesione e coesione si bilanciano perfettamente.
2.  **Menisco Concavo (curvo verso il basso)**:
    * Si forma quando: **Adesione > Coesione** (es. acqua e vetro).
    * Il liquido "cerca" di arrampicarsi sulla parete, bagnandola.
    * Questo causa la **risalita capillare**: il liquido sale nel tubo fino a che il peso della colonna liquida bilancia la forza di adesione.
3.  **Menisco Convesso (curvo verso l'alto)**:
    * Si forma quando: **Coesione > Adesione** (es. mercurio e vetro).
    * Il liquido è attratto più da sé stesso che dalla parete e si "ritira".
    * Questo causa la **depressione capillare**: il livello del liquido nel tubo è più basso di quello esterno.

---

## Pressione di Curvatura e Legge di Laplace

Una superficie curva, come un menisco o la superficie di una goccia, può esistere solo se c'è una differenza di pressione ($\Delta P$) tra i due lati dell'interfaccia. Questa è chiamata **pressione di curvatura**.

* La tensione superficiale ($\sigma$) "stringe" la superficie, creando una pressione maggiore sul lato **concavo** (interno) rispetto al lato convesso (esterno).

### Legge di Laplace (Descrizione Qualitativa)
La Legge di Laplace (spesso formulata come $T = P \cdot r$ per i vasi) descrive la relazione tra la pressione, la tensione della parete e la geometria (raggio).

Per una superficie sferica (come una bolla o un alveolo), la pressione di curvatura ($\Delta P$ - la pressione interna in eccesso) è:

* **Direttamente proporzionale** alla tensione superficiale ($\sigma$).
* **Inversamente proporzionale** al raggio di curvatura ($r$).

**Formula (Sfera)**: $\Delta P = P_{interna} - P_{esterna} = \frac{2\sigma}{r}$

**Formula (Cilindro/Tensione di Parete)**: Per strutture cilindriche come i vasi sanguigni, la legge descrive la Tensione di Parete ($T$, la forza che "tira" la parete) necessaria per sostenere la pressione transmurale ($\Delta P$):
$T \propto \Delta P \cdot r$

### Riferimenti a Contesti Biologici

#### 1. Polmoni (Alveoli Polmonari)
Gli alveoli sono piccole sacche sferiche ($r$ molto piccolo) rivestite da un sottile film liquido.
* **Problema**: Se questo liquido fosse acqua pura ($\sigma$ alta), la $\Delta P = \frac{2\sigma}{r}$ sarebbe altissima. Questa "pressione di collasso" renderebbe l'inspirazione (gonfiare gli alveoli) estremamente faticosa e favorirebbe l'atelettasia (collasso alveolare).
* **Soluzione Fisiologica**: I **pneumociti di tipo II** secernono il **surfattante polmonare**, un tensioattivo che si interpone tra le molecole d'acqua.
* **Funzione del Surfattante**: Abbassa drasticamente la tensione superficiale $\sigma$. Questo:
    1.  Riduce la $\Delta P$ e quindi il lavoro respiratorio.
    2.  Stabilizza gli alveoli: la sua efficacia è maggiore negli alveoli piccoli (più concentrato) che in quelli grandi, prevenendo il collasso dei piccoli nei grandi.

#### 2. Capillari Sanguigni
Perché un capillare, la cui parete è sottilissima, non scoppia sotto la pressione sanguigna?
* **Applicazione**: Usiamo la legge di Laplace per un cilindro ($T \propto \Delta P \cdot r$).
* I capillari hanno un **raggio ($r$) incredibilmente piccolo**.
* Anche se la $\Delta P$ (pressione sanguigna) è significativa, il raggio $r$ minuscolo fa sì che la **tensione di parete ($T$)** risultante sia bassissima. La parete sottile è quindi sufficiente a sostenerla.
* **Contrasto (Aneurisma)**: Un aneurisma è una dilatazione con $r$ molto grande. Per la stessa $\Delta P$, la tensione $T$ sulla parete (già indebolita) è **enorme**, portando a un alto rischio di rottura.