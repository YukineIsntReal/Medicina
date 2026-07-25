Questa nota racchiude gli strumenti essenziali per l'analisi dei dati, il calcolo delle probabilità e il calcolo combinatorio. Questi concetti sono frequentemente testati nei quesiti di logica, matematica e ragionamento critico.

## 1. Calcolo Combinatorio Base ^calcolo-combinatorio

Il calcolo combinatorio permette di determinare in quanti modi è possibile raggruppare, ordinare o scegliere gli elementi di un insieme. Un concetto preliminare fondamentale è il **fattoriale** di un numero intero positivo $n$, indicato con $n!$:
$$n! = n \cdot (n-1) \cdot (n-2) \dots 3 \cdot 2 \cdot 1$$
*(Nota: per convenzione, $0! = 1$ e $1! = 1$)*.

*   **Permutazioni Semplici:** Contano in quanti modi si possono ordinare $n$ elementi distinti (l'ordine conta, tutti gli elementi vengono presi).
    $$P_n = n!$$
*   **Permutazioni con Ripetizione:** Se tra gli $n$ elementi ce ne sono alcuni che si ripetono ($k$ volte, $h$ volte, ecc.).
    $$P_{n}^{k,h} = \frac{n!}{k! \cdot h!}$$
*   **Disposizioni Semplici:** Contano i gruppi di $k$ elementi scelti tra $n$ elementi disponibili, in cui **l'ordine conta**.
    $$D_{n,k} = \frac{n!}{(n-k)!}$$
*   **Combinazioni Semplici:** Contano i gruppi di $k$ elementi scelti tra $n$ elementi disponibili, in cui **l'ordine NON conta**.
    $$C_{n,k} = \binom{n}{k} = \frac{n!}{k!(n-k)!}$$

## 2. Medie Statistiche ^statistica

Gli indici di posizione centrale (o medie) sintetizzano un insieme di dati con un singolo valore rappresentativo.

*   **Media Aritmetica Semplice:** È il quoziente tra la somma di tutti i dati e il numero dei dati stessi. Dati $n$ valori ($x_1, x_2, \dots, x_n$):
    $$M = \frac{x_1 + x_2 + \dots + x_n}{n}$$
*   **Media Aritmetica Ponderata:** Si utilizza quando ogni dato $x_i$ ha un "peso" o una frequenza $p_i$.
    $$M_p = \frac{x_1p_1 + x_2p_2 + \dots + x_np_n}{p_1 + p_2 + \dots + p_n}$$
*   **Moda:** È il valore (o i valori) che si presenta con la massima frequenza in un insieme di dati. Un insieme può essere unimodale, bimodale o amodale.
*   **Mediana:** È il valore centrale di una serie di dati **ordinati in modo crescente (o decrescente)**.
    *   Se $n$ è **dispari**, la mediana è il valore esattamente al centro.
    *   Se $n$ è **pari**, la mediana è la media aritmetica dei due valori centrali.

## 3. Calcolo delle Probabilità ^probabilita

La probabilità misura la possibilità che un evento si verifichi.

*   **Probabilità Classica:** La probabilità $P$ di un evento $E$ è il rapporto tra il numero dei casi favorevoli ($f$) e il numero dei casi possibili ($n$), purché tutti i casi siano equiprobabili.
    $$P(E) = \frac{f}{n}$$
    *(La probabilità è sempre un numero compreso tra $0$ e $1$: $0 \leq P(E) \leq 1$)*.
*   **Evento Contrario:** La probabilità che un evento non si verifichi ($\overline{E}$).
    $$P(\overline{E}) = 1 - P(E)$$
*   **Probabilità dell'Unione Logica (Somma - evento "O"):**
    *   **Eventi Incompatibili** (non possono verificarsi contemporaneamente):
        $$P(A \cup B) = P(A) + P(B)$$
    *   **Eventi Compatibili** (possono verificarsi contemporaneamente):
        $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
*   **Probabilità dell'Intersezione Logica (Prodotto - evento "E"):**
    *   **Eventi Indipendenti** (il verificarsi di uno non influenza l'altro):
        $$P(A \cap B) = P(A) \cdot P(B)$$