Questa nota raccoglie le formule e le definizioni fondamentali per la geometria piana, solida e analitica. Padroneggiare queste regole è essenziale per la risoluzione dei quesiti matematici e di logica spaziale dei test d'ingresso.

## 1. Geometria Analitica e Piano Cartesiano ^piano-cartesiano

Il piano cartesiano è definito da due assi ortogonali: l'asse delle ascisse ($x$) e l'asse delle ordinate ($y$). Ogni punto $P$ è identificato da una coppia di coordinate $(x_P, y_P)$.

*   **Distanza tra due punti $A(x_A, y_A)$ e $B(x_B, y_B)$:**
    $$d = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}$$
*   **Punto medio $M$ di un segmento $AB$:**
    $$x_M = \frac{x_A + x_B}{2}, \quad y_M = \frac{y_A + y_B}{2}$$

## 2. La Retta ^retta

Una funzione lineare rappresenta una retta nel piano cartesiano.

*   **Equazione implicita:** $ax + by + c = 0$
*   **Equazione esplicita:** $y = mx + q$
    *   $m$: **coefficiente angolare** (indica la pendenza). $m = -\frac{a}{b}$. Dati due punti, $m = \frac{y_B - y_A}{x_B - x_A}$.
    *   $q$: **intercetta** (punto di intersezione con l'asse $y$).
*   **Rette parallele:** Hanno lo stesso coefficiente angolare ($m_1 = m_2$).
*   **Rette perpendicolari:** Il prodotto dei coefficienti angolari è $-1$ ($m_1 \cdot m_2 = -1 \implies m_1 = -\frac{1}{m_2}$).

## 3. La Parabola ^parabola

Nei test, la parabola con asse verticale è la più ricorrente. È espressa da un'equazione di 2° grado (vedi `[[Algebra: Equazioni, Disequazioni e Sistemi#^equazioni-secondo-grado]]`).

*   **Equazione:** $y = ax^2 + bx + c$
*   **Concavità:**
    *   Se $a > 0$: concavità rivolta verso l'alto.
    *   Se $a < 0$: concavità rivolta verso il basso.
*   **Vertice $V$:** È il punto di massimo o minimo.
    $$V = \left(-\frac{b}{2a}, -\frac{\Delta}{4a}\right)$$
    dove $\Delta = b^2 - 4ac$.

## 4. Geometria Piana (Aree e Perimetri) ^geometria-piana

Formule rapide per le figure bidimensionali principali. Siano $2p$ il perimetro, $A$ l'area, $b$ la base, $h$ l'altezza.

*   **Triangolo:**
    *   $A = \frac{b \cdot h}{2}$
    *   *Teorema di Pitagora (solo rettangoli):* $i^2 = c_1^2 + c_2^2$ (l'ipotenusa al quadrato è pari alla somma dei quadrati dei cateti).
*   **Quadrato:**
    *   $2p = 4l$
    *   $A = l^2$
    *   *Diagonale:* $d = l\sqrt{2}$
*   **Rettangolo e Parallelogramma:**
    *   $A = b \cdot h$
*   **Rombo:**
    *   $A = \frac{D \cdot d}{2}$ (dove $D$ e $d$ sono le diagonali maggiore e minore).
*   **Trapezio:**
    *   $A = \frac{(B + b) \cdot h}{2}$
*   **Circonferenza e Cerchio (raggio $r$):**
    *   *Circonferenza (Perimetro):* $C = 2\pi r$
    *   *Area del cerchio:* $A = \pi r^2$

## 5. Geometria Solida (Volumi e Superfici) ^geometria-solida

Siano $V$ il volume, $S_b$ l'area di base, $S_l$ la superficie laterale, $S_t$ la superficie totale, $h$ l'altezza.

*   **Cubo (spigolo $l$):**
    *   $V = l^3$
    *   $S_t = 6l^2$
    *   *Diagonale:* $d = l\sqrt{3}$
*   **Parallelepipedo e Prisma:**
    *   $V = S_b \cdot h$
*   **Cilindro (raggio $r$):**
    *   $V = \pi r^2 h$
    *   $S_l = 2\pi r h$
*   **Piramide e Cono:**
    *   $V = \frac{S_b \cdot h}{3}$
    *   *Nel cono:* $S_b = \pi r^2$
*   **Sfera (raggio $r$):**
    *   $V = \frac{4}{3}\pi r^3$
    *   $S_t = 4\pi r^2$