Il **pH** è una misura della scala di acidità o basicità di una soluzione acquosa, espressa in termini di concentrazione di ioni idronio ($H_3O^+$ o, più semplicemente, $H^+$). Il concetto fu introdotto dal biochimico danese Søren Sørensen nel 1909.

---

## 1. Definizione Matematica e Scala del pH
Il prefisso "$p$" indica l'operatore matematico di **logaritmo negativo in base 10** ($-\log_{10}$).

* **Definizione di pH:**
  $$pH = -\log_{10}[H^+]$$
* **Definizione di pOH:**
  $$pOH = -\log_{10}[OH^-]$$

### La Relazione Fondamentale
Come visto nella nota riguardante [[L'Acqua: Autoprotolisi e Prodotto Ionico (Kw)]], a $25^\circ\text{C}$ il prodotto ionico dell'acqua è $K_w = 10^{-14}$, il che ci fornisce una formula utilissima per i calcoli veloci:
$$pH + pOH = 14$$

### La Scala del pH (a $25^\circ\text{C}$)
La scala varia generalmente da 0 a 14:
* **Soluzioni Acide:** $pH < 7$ (più il pH è basso, più la soluzione è acida).
* **Soluzioni Neutre:** $pH = 7$.
* **Soluzioni Basiche (o Alkaline):** $pH > 7$ (più il pH è alto, più la soluzione è basica).

> [!tip] Trucco Matematico per il Test (Senza Calcolatrice)
> Se la concentrazione è espressa come potenza di 10 esatta (es. $[H^+] = 10^{-x}$), allora il **$pH = x$**.
> * Esempio: Se $[H^+] = 10^{-3} \text{ M} \implies pH = 3$.
> * Se $[H^+] = 1 \times 10^{-5} \text{ M} \implies pH = 5$.

---

## 2. Calcolo del pH per Acidi e Basi Forti
Gli acidi e le basi forti si dissociano (o ionizzano) **completamente** in acqua. La reazione è irreversibile ($\rightarrow$).

### Acidi Forti
Essendosi dissociato tutto l'acido, la concentrazione di $H^+$ all'equilibrio è pari alla concentrazione iniziale dell'acido ($C_a$), moltiplicata per il numero di idrogeni rilasciati (valenza acida).

$$[H^+] = C_a \times \text{valenza}$$
$$pH = -\log(C_a \times \text{valenza})$$

*Gli acidi forti più comuni nei test:* $HCl$, $HBr$, $HI$, $HNO_3$, $H_2SO_4$ (prima dissociazione), $HClO_4$.
* **Esempio:** Calcolare il pH di una soluzione di $HCl$ $0,01 \text{ M}$.
  Poiché $HCl$ è un acido forte monoprotico (valenza = 1):
  $$[H^+] = 0,01 \text{ M} = 10^{-2} \text{ M} \implies pH = 2$$

### Basi Forti
Le basi forti si dissociano completamente liberando $OH^-$. Pertanto, calcoliamo prima il $pOH$ e poi ricaviamo il $pH$ per sottrazione.

$$[OH^-] = C_b \times \text{valenza}$$
$$pOH = -\log(C_b \times \text{valenza}) \implies pH = 14 - pOH$$

*Le basi forti più comuni nei test:* Idrossidi dei metalli alcalini e alcalino-terrosi (es. $NaOH$, $KOH$, $Ca(OH)_2$).
* **Esempio (Attenzione alla Valenza!):** Calcolare il pH di una soluzione di $Ca(OH)_2$ $0,005 \text{ M}$.
  L'idrossido di calcio rilascia 2 ioni $OH^-$ per ogni molecola (valenza = 2):
  $$[OH^-] = 0,005 \times 2 = 0,01 \text{ M} = 10^{-2} \text{ M}$$
  $$pOH = 2 \implies pH = 14 - 2 = 12$$

---

## 3. Acidi e Basi Deboli: $K_a$ e $K_b$
Gli acidi e le basi deboli si dissociano solo **parzialmente** in acqua, stabilendo un equilibrio chimico dinamico ($\rightleftharpoons$).

### Costante di Dissociazione Acida ($K_a$)
Consideriamo un acido debole generico $HA$:
$$HA + H_2O \rightleftharpoons A^- + H_3O^+$$

La costante di equilibrio associata è la $K_a$:
$$K_a = \frac{[A^-][H_3O^+]}{[HA]}$$

* **Significato logico:** Più il valore di $K_a$ è grande, più l'equilibrio è spostato a destra, il che significa che l'acido è "più forte" (anche se rimane debole rispetto agli acidi forti).

### Costante di Dissociazione Basica ($K_b$)
Consideriamo una base debole generica $B$ (come l'ammoniaca $NH_3$):
$$B + H_2O \rightleftharpoons BH^+ + OH^-$$

La costante di equilibrio associata è la $K_b$:
$$K_b = \frac{[BH^+][OH^-]}{[B]}$$

### Formula Approssimata per il Calcolo del pH (Focus Test)
Nei test d'ingresso non ti verrà mai chiesto di risolvere un'equazione di secondo grado completa. Si usa sempre la formula di approssimazione (valida se l'acido/base è sufficientemente debole e la concentrazione non è infinitamente diluita):

* **Per un acido debole:**
  $$[H^+] = \sqrt{K_a \cdot C_a}$$
* **Per una base debole:**
  $$[OH^-] = \sqrt{K_b \cdot C_b}$$

> [!danger] Errore Comune da Evitare
> Ricorda che se calcoli $[OH^-]$ per una base debole, la radice ti darà la concentrazione degli ossidrili. Dovrai fare il $-\log$ per trovare il $pOH$ e infine fare $14 - pOH$ per trovare il vero valore di pH!

---
**Vedi anche:** [[Acidi e Basi: Le Tre Teorie Fondamentali]], [[L'Acqua: Autoprotolisi e Prodotto Ionico (Kw)]], [[Idrolisi Salina]], [[Soluzioni Tampone]]