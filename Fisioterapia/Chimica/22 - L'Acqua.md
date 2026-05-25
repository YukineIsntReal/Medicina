L'acqua pura non è formata solo da molecole $H_2O$, ma contiene una piccolissima quantità di ioni derivanti da una reazione di auto-ionizzazione chiamata **autoprotolisi** (o auto-ionizzazione). Questa reazione spiega perché l'acqua, seppur debolmente, conduce l'elettricità.

---

## 1. La Reazione di Autoprotolisi
L'acqua è una sostanza **anfiprotica** (o anfotera), il che significa che può comportarsi sia da acido che da base secondo la [[Acidi e Basi: Le Tre Teorie Fondamentali#2. Teoria di Brønsted-Lowry (1923)|Teoria di Brønsted-Lowry]]. 

Nella reazione di autoprotolisi, una molecola di acqua cede un protone ($H^+$) a un'altra molecola di acqua:

$$H_2O + H_2O \rightleftharpoons H_3O^+ + OH^-$$

* Una molecola agisce da **acido** e si trasforma nella base coniugata $OH^-$ (ione idrossido).
* L'altra molecola agisce da **base** e si trasforma nell'acido coniugato $H_3O^+$ (ione idronio).

Per semplicità, la reazione viene spesso scritta in forma contratta:
$$H_2O \rightleftharpoons H^+ + OH^-$$

---

## 2. Il Prodotto Ionico dell'Acqua ($K_w$)
Essendo una reazione all'equilibrio, possiamo scrivere la costante di equilibrio ($K_c$):

$$K_c = \frac{[H_3O^+][OH^-]}{[H_2O]^2}$$

Poiché l'acqua pura è il solvente ed è presente in fortissimo eccesso, la sua concentrazione ($[H_2O] \approx 55,5 \text{ M}$) rimane praticamente costante. Possiamo quindi inglobare $[H_2O]^2$ nella costante, ottenendo una nuova costante chiamata **prodotto ionico dell'acqua** ($K_w$, dall'inglese *Water*):

$$K_w = [H_3O^+][OH^-]$$

### Valore di $K_w$ a $25^\circ\text{C}$
Alla temperatura standard di $25^\circ\text{C}$, il valore sperimentale di $K_w$ è:
$$K_w = 1,0 \times 10^{-14}$$

Poiché nell'acqua pura per ogni ione $H_3O^+$ si forma esattamente uno ione $OH^-$, le loro concentrazioni sono uguali (condizione di **neutralità**):
$$[H_3O^+] = [OH^-] = \sqrt{1,0 \times 10^{-14}} = 1,0 \times 10^{-7} \text{ M}$$

---

## 3. Effetto della Temperatura su $K_w$ (Focus Test)
> [!danger] ATTENZIONE: Il tranello preferito dei quiz!
> La reazione di autoprotolisi dell'acqua è un processo **endotermico** (assorbe calore). 
> Secondo il principio di Le Châtelier, se aumentiamo la temperatura, l'equilibrio si sposta verso destra.

* **Se la temperatura aumenta ($> 25^\circ\text{C}$):** la reazione si sposta a destra, quindi aumentano sia $[H_3O^+]$ che $[OH^-]$. Di conseguenza, **$K_w$ aumenta** (ad esempio a $60^\circ\text{C}$, $K_w \approx 10^{-13}$).
* **Se la temperatura diminuisce ($< 25^\circ\text{C}$):** la reazione si sposta a sinistra, quindi **$K_w$ diminuisce**.

*Nota bene:* Anche se a $60^\circ\text{C}$ il pH dell'acqua pura diventa minore di 7 (circa 6,5), l'acqua rimane **neutra** perché la concentrazione di $[H_3O^+]$ è ancora perfettamente identica a quella di $[OH^-]$.

---

## 4. Relazione tra $K_w$, pH e pOH
Applicando i logaritmi negativi alla formula del $K_w$, otteniamo una relazione matematica fondamentale per il [[Calcolo del pH]]:

$$-\log K_w = -\log([H_3O^+][OH^-])$$
$$pK_w = pH + pOH$$

A $25^\circ\text{C}$, poiché $K_w = 10^{-14}$, si ha che $pK_w = 14$. Quindi:
$$pH + pOH = 14$$

Grazie a questa equazione, se conosciamo il pH di una soluzione possiamo ricavare istantaneamente il pOH, e viceversa:
* **Soluzione Acida:** $[H_3O^+] > 10^{-7} \implies pH < 7$
* **Soluzione Neutra:** $[H_3O^+] = 10^{-7} \implies pH = 7$
* **Soluzione Basica:** $[H_3O^+] < 10^{-7} \implies pH > 7$

---
**Vedi anche:** [[Acidi e Basi: Le Tre Teorie Fondamentali]], [[Calcolo del pH]], [[Principio di Le Chatelier]]