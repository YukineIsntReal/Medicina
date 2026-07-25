Questa nota contiene le regole fondamentali per la risoluzione di equazioni e disequazioni di primo e secondo grado, e dei sistemi lineari. Si tratta di competenze di calcolo indispensabili per la risoluzione dei problemi di logica matematica, chimica e fisica.

## 1. Equazioni di 1° Grado ^equazioni-primo-grado

Un'equazione di primo grado (o lineare) si presenta nella forma normale:
$$ax + b = 0$$
con $a \neq 0$.

*   **Risoluzione:** L'obiettivo è isolare l'incognita $x$.
    $$ax = -b \implies x = -\frac{b}{a}$$
*   **Principi di equivalenza:**
    1.  Aggiungendo o sottraendo la stessa quantità a entrambi i membri, l'equazione non cambia.
    2.  Moltiplicando o dividendo entrambi i membri per una stessa quantità (diversa da zero), l'equazione non cambia.

## 2. Disequazioni di 1° Grado ^disequazioni-primo-grado

Una disequazione di primo grado ha una forma simile all'equazione, ma con un segno di disuguaglianza ($>, <, \geq, \leq$).
Es: $$ax + b > 0$$

*   **Risoluzione:** Si seguono gli stessi passaggi delle equazioni, prestando attenzione a una regola fondamentale:
    *   **Regola del segno:** Se si moltiplicano o dividono entrambi i membri per un numero **negativo**, si deve **invertire il verso della disuguaglianza**.
    *   Esempio: $-2x > 4 \implies 2x < -4 \implies x < -2$

## 3. Equazioni di 2° Grado ^equazioni-secondo-grado

Un'equazione di secondo grado è espressa nella forma completa:
$$ax^2 + bx + c = 0$$
con $a \neq 0$.

*   **Discriminante ($\Delta$):** È il valore che determina la natura delle soluzioni.
    $$\Delta = b^2 - 4ac$$
    *   Se $\Delta > 0$: Due soluzioni reali e distinte.
    *   Se $\Delta = 0$: Due soluzioni reali e coincidenti (una sola radice di molteplicità due).
    *   Se $\Delta < 0$: Nessuna soluzione reale (soluzioni complesse coniugate).
*   **Formula Risolutiva Generale:**
    $$x_{1,2} = \frac{-b \pm \sqrt{\Delta}}{2a}$$
*   **Casi Incompleti (metodi rapidi senza $\Delta$):**
    *   *Pura* ($b=0$): $ax^2 + c = 0 \implies x^2 = -\frac{c}{a}$. Ha soluzioni reali solo se $-\frac{c}{a} > 0$.
    *   *Spuria* ($c=0$): $ax^2 + bx = 0 \implies x(ax + b) = 0$. Le soluzioni sono $x=0$ e $x=-\frac{b}{a}$.

## 4. Disequazioni di 2° Grado ^disequazioni-secondo-grado

Si presentano nella forma $ax^2 + bx + c > 0$ (o $<, \geq, \leq$). Il metodo più efficace è quello grafico, associando il polinomio alla parabola $y = ax^2 + bx + c$.

1.  **Assicurarsi che $a > 0$**: Se l'equazione ha $a < 0$, si cambia segno a tutti i termini e si inverte il verso della disequazione.
2.  **Calcolare il $\Delta$ e trovare le radici dell'equazione associata ($x_1 < x_2$).**
3.  **Studio del segno (con $a > 0$):**
    *   Se $\Delta > 0$:
        *   La parabola interseca l'asse $x$ in $x_1$ e $x_2$.
        *   $ax^2 + bx + c > 0$ per **valori esterni**: $x < x_1 \lor x > x_2$.
        *   $ax^2 + bx + c < 0$ per **valori interni**: $x_1 < x < x_2$.
    *   Se $\Delta = 0$:
        *   La parabola tocca l'asse $x$ in $x_1$.
        *   $ax^2 + bx + c > 0$ per $\forall x \neq x_1$.
        *   $ax^2 + bx + c < 0$ per nessun valore reale.
    *   Se $\Delta < 0$:
        *   La parabola è tutta sopra l'asse $x$.
        *   $ax^2 + bx + c > 0$ per $\forall x \in \mathbb{R}$.
        *   $ax^2 + bx + c < 0$ per nessun valore.

## 5. Sistemi di Equazioni ^sistemi

Un sistema di equazioni è un insieme di più equazioni che devono essere soddisfatte contemporaneamente. Nel test sono comuni i **sistemi lineari** (due equazioni in due incognite).

$$
\begin{cases}
ax + by = c \\
a'x + b'y = c'
\end{cases}
$$

*   **Metodo di Sostituzione (più comune e versatile):**
    1. Si esplicita un'incognita da una delle due equazioni (es. $x = \frac{c - by}{a}$).
    2. Si sostituisce l'espressione trovata nell'altra equazione.
    3. Si risolve l'equazione ottenuta in una sola incognita.
    4. Si sostituisce il valore trovato nell'equazione di partenza per trovare l'altra incognita.
*   **Metodo di Riduzione (somma/sottrazione):** Consiste nel moltiplicare una o entrambe le equazioni per coefficienti tali da rendere uguali o opposti i coefficienti di una delle due incognite, per poi sommare o sottrarre le equazioni in colonna ed eliminare così un'incognita.