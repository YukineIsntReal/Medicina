## Caratteristiche Fondamentali

La materia si presenta principalmente in tre stati di aggregazione: **solido**, **liquido** e **gassoso**. La distinzione fondamentale tra questi stati risiede nella forza dei legami intermolecolari e nella libertà di movimento delle particelle.

### Solidi
Nei solidi, le particelle (atomi o molecole) sono strettamente impacchettate in posizioni fisse, spesso formando una struttura cristallina regolare.
* Hanno **forma e volume propri**.
* Le particelle vibrano attorno a posizioni di equilibrio.
* **Resistono agli sforzi di taglio**: se applichiamo una forza parallela a una superficie, il solido si deforma ma non "scorre" (entro i limiti di elasticità).

### Fluidi (Liquidi e Gas)
I fluidi comprendono sia i liquidi che i gas. La loro caratteristica distintiva è l'**incapacità di resistere a sforzi di taglio statici**.

* **Liquidi**:
    * Hanno un **volume definito** (sono quasi incomprimibili), ma **non hanno una forma propria** (assumono la forma del contenitore).
    * Le particelle sono vicine, ma libere di muoversi l'una rispetto all'altra.
* **Gas**:
    * Non hanno **né forma né volume propri** (tendono a occupare tutto il volume disponibile).
    * Le particelle sono molto distanti tra loro e si muovono caoticamente. Sono facilmente comprimibili.

In sintesi, un fluido è una sostanza che "scorre" (fluisce) se sottoposta a uno sforzo di taglio, per quanto piccolo.

---

## Grandezze Fondamentali dei Fluidi

Per descrivere il comportamento dei fluidi, due grandezze intensive sono essenziali: la densità e la pressione.

### Densità ($\rho$)
La densità è una misura di quanta massa è contenuta in un dato volume.

* **Definizione**: Rapporto tra la massa ($m$) di una sostanza e il volume ($V$) che occupa.
* **Formula**: $\rho = \frac{m}{V}$
* **Unità di Misura (SI)**: Chilogrammo per metro cubo ($kg/m^3$).
* **Note**: Per i liquidi, la densità è considerata quasi costante (fluido incomprimibile). Per i gas, la densità dipende fortemente da pressione e temperatura.

### Pressione ($P$)
La pressione è una misura della forza esercitata perpendicolarmente su una superficie, per unità di area.

* **Definizione**: Rapporto tra il modulo della forza perpendicolare ($F_{\perp}$) agente su una superficie e l'area ($A$) della superficie stessa.
* **Formula**: $P = \frac{F_{\perp}}{A}$
* **Unità di Misura (SI)**: Pascal ($Pa$), che equivale a un Newton su metro quadro ($1 \, Pa = 1 \, N/m^2$).
* **Natura**: La pressione è una **grandezza scalare**. In un fluido, agisce in egual misura in tutte le direzioni su un punto (Principio di Pascal).

---

## Ruolo nella Statica e Dinamica dei Fluidi

Densità e pressione sono cruciali per descrivere sia i fluidi in quiete (statica) sia i fluidi in movimento (dinamica).

### 1. Statica dei Fluidi (Idrostatica)
Studia i fluidi in equilibrio (fermi).

* **Legge di Stevino**: Descrive come la pressione varia con la profondità in un fluido omogeneo. La pressione a una profondità $h$ è data dalla pressione alla superficie $P_0$ più il contributo del peso della colonna di fluido soprastante.
    * $P(h) = P_0 + \rho g h$
    * Dove $g$ è l'accelerazione di gravità. La pressione idrostatica ($\rho g h$) dipende direttamente dalla **densità** del fluido.
* **Principio di Archimede**: Un corpo immerso in un fluido riceve una spinta verso l'alto (spinta idrostatica $F_A$) pari al peso del fluido spostato.
    * $F_A = \rho_{fluido} \cdot g \cdot V_{immerso}$
    * Il galleggiamento dipende dal confronto tra la densità del corpo e la **densità** del fluido.

### 2. Dinamica dei Fluidi (Idrodinamica)
Studia i fluidi in movimento.

* **Equazione di Continuità** (per fluidi incomprimibili): Riflette la conservazione della massa. La portata ($Q = A \cdot v$) è costante.
    * $A_1 v_1 = A_2 v_2$
    * Dove $A$ è l'area della sezione e $v$ la velocità del fluido.
* **Equazione di Bernoulli**: Descrive la conservazione dell'energia per un fluido ideale (incomprimibile, non viscoso) in moto stazionario.
    * $P + \frac{1}{2}\rho v^2 + \rho g h = costante$
    * Il termine $P$ rappresenta l'energia di pressione.
    * Il termine $\frac{1}{2}\rho v^2$ è l'energia cinetica per unità di volume (dipendente dalla **densità**).
    * Il termine $\rho g h$ è l'energia potenziale gravitazionale per unità di volume (dipendente dalla **densità**).
    * L'equazione mostra la relazione inversa tra pressione e velocità: dove il fluido scorre più veloce, la **pressione** dinamica è maggiore, ma quella statica è minore.