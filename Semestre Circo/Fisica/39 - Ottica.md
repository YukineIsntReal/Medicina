L'ottica è la branca della fisica che descrive il comportamento e le proprietà della luce (radiazione elettromagnetica, in particolare quella visibile) e la sua interazione con la materia. L'**ottica geometrica**, in particolare, descrive la propagazione della luce in termini di "raggi".

## Indice di Rifrazione ($n$)

L'**indice di rifrazione** ($n$) è una grandezza adimensionale che quantifica quanto un mezzo materiale "rallenta" la propagazione della luce rispetto al vuoto.

È definito come il rapporto tra la velocità della luce nel vuoto ($c$) e la velocità della luce $v$ nel mezzo:

$$n = \frac{c}{v}$$

* Nel vuoto, $n=1$.
* In qualsiasi altro mezzo trasparente (aria, acqua, vetro, tessuti biologici), $v < c$ e quindi $n > 1$.

---

## Leggi dell'Ottica Geometrica

Quando un raggio di luce incontra una superficie di separazione netta (interfaccia) tra due mezzi con indici di rifrazione diversi ($n_1$ e $n_2$), avvengono due fenomeni: riflessione e rifrazione.



### 1. Leggi della Riflessione
Il raggio di luce "rimbalza" sulla superficie.
1.  Il raggio incidente, il raggio riflesso e la retta **normale** (la perpendicolare alla superficie nel punto di incidenza) giacciono tutti sullo stesso piano.
2.  L'angolo di incidenza ($\theta_1$, tra raggio incidente e normale) è uguale all'angolo di riflessione ($\theta_r$):
    $$\theta_1 = \theta_r$$

### 2. Leggi della Rifrazione (Legge di Snell)
Il raggio di luce attraversa l'interfaccia, cambiando mezzo e (generalmente) direzione.
1.  Il raggio incidente, il raggio rifratto e la normale giacciono tutti sullo stesso piano.
2.  La relazione tra gli angoli di incidenza ($\theta_1$) e di rifrazione ($\theta_2$) e gli indici di rifrazione è data dalla **Legge di Snell**:
    $$n_1 \sin(\theta_1) = n_2 \sin(\theta_2)$$

---

## Fenomeno della Dispersione

Nella maggior parte dei materiali (come il vetro), l'indice di rifrazione $n$ non è costante, ma dipende leggermente dalla lunghezza d'onda ($\lambda$) e quindi dalla frequenza ($\nu$) della luce. Questo fenomeno è chiamato **dispersione**.

* Generalmente, l'indice di rifrazione è maggiore per la luce blu/violetta (frequenza più alta) rispetto alla luce rossa (frequenza più bassa).
* **Conseguenza:** Quando la luce bianca (policromatica, un insieme di tutte le lunghezze d'onda) attraversa un mezzo disperdente (es. un prisma), le diverse "colorazioni" vengono rifratte con angoli leggermente diversi. La luce bianca si scompone così nei suoi colori costituenti (come nell'arcobaleno).



---

## Lenti Sottili

Una lente sottile è un dispositivo ottico (tipicamente di vetro o plastica) con due superfici curve, il cui spessore centrale è trascurabile rispetto ai raggi di curvatura delle superfici e alle distanze dell'oggetto e dell'immagine.

La proprietà fondamentale di una lente è la sua **distanza focale ($f$)**.

### 1. Lenti Convergenti (Convesse)
* Sono più spesse al centro e più sottili ai bordi.
* Fanno convergere i raggi di luce paralleli in un punto detto **fuoco ($F$)**.
* Hanno una distanza focale **positiva** ($f > 0$).
* Sono usate per correggere l'ipermetropia (difficoltà a vedere da vicino).

### 2. Lenti Divergenti (Concave)
* Sono più sottili al centro e più spesse ai bordi.
* Fanno divergere i raggi di luce paralleli *come se* provenissero da un punto (il fuoco virtuale, $F$).
* Hanno una distanza focale **negativa** ($f < 0$).
* Sono usate per correggere la miopia (difficoltà a vedere da lontano).

### Formazione delle Immagini
La relazione tra la posizione dell'oggetto ($p$), la posizione dell'immagine ($q$) e la distanza focale ($f$) è data dall'**Equazione dei Punti Coniugati** (o Equazione delle Lenti Sottili):

$$\frac{1}{p} + \frac{1}{q} = \frac{1}{f}$$

L'**Ingrandimento lineare ($M$)** è il rapporto tra l'altezza dell'immagine e l'altezza dell'oggetto:

$$M = -\frac{q}{p}$$

#### Immagini Reali e Virtuali

* **Immagine Reale:**
    * Si forma nel punto in cui i raggi di luce *effettivamente* convergono.
    * Può essere proiettata su uno schermo (come l'immagine sul sensore di una fotocamera o sulla retina dell'occhio).
    * Si ottiene quando $q$ è positivo (l'immagine si forma "dopo" la lente rispetto all'oggetto).
    * Solitamente è capovolta ($M < 0$).

* **Immagine Virtuale:**
    * Si forma nel punto da cui i raggi di luce *sembrano* divergere.
    * Non può essere proiettata su uno schermo; può essere vista solo "attraverso" la lente (es. lente d'ingrandimento).
    * Si ottiene quando $q$ è negativo (l'immagine si forma "prima" della lente, dalla stessa parte dell'oggetto).
    * È sempre dritta ($M > 0$).

---

## Esempio: Il Microscopio Ottico Composto

Il microscopio ottico è uno strumento fondamentale in medicina, biologia e istologia, che sfrutta i principi delle lenti per ottenere un forte ingrandimento di campioni piccoli.
Utilizza (nella sua forma base) due sistemi di lenti convergenti:

1.  **Obiettivo:** Una lente (o sistema di lenti) convergente con una distanza focale $f_{ob}$ molto corta.
    * L'oggetto (il campione sul vetrino) viene posizionato appena oltre il fuoco dell'obiettivo.
    * L'obiettivo crea una **prima immagine reale, ingrandita e capovolta**.

2.  **Oculare:** Un'altra lente convergente (con $f_{oc}$ più lunga) che agisce come una *lente d'ingrandimento*.
    * La prima immagine (reale) prodotta dall'obiettivo funge da *oggetto* per l'oculare.
    * Questo "oggetto" viene posizionato *all'interno* della distanza focale dell'oculare.
    * L'oculare crea un'**immagine finale virtuale, ulteriormente ingrandita e capovolta** (rispetto all'oggetto originale), che è quella osservata dall'operatore.

L'ingrandimento totale ($M_{tot}$) è approssimativamente il prodotto dell'ingrandimento dell'obiettivo ($M_{ob}$) e dell'ingrandimento dell'oculare ($M_{oc}$).