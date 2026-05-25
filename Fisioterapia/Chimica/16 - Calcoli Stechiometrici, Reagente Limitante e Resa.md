Una volta bilanciata una reazione (vedi `[[Chimica Inorganica: Reazioni Chimiche e Bilanciamento]]`), i **coefficienti stechiometrici** ci forniscono il rapporto esatto (in moli) con cui le sostanze reagiscono e si formano. La stechiometria è la branca della chimica che sfrutta questi rapporti per calcolare le quantità delle sostanze coinvolte.

## 1. Relazioni Moli-Moli e Moli-Massa

Nei calcoli stechiometrici, l'unità di conversione universale è la **mole**. I coefficienti indicano il rapporto molare, NON il rapporto in grammi!

### Il "Metodo Universale" in 3 Step per i Test
Se il problema ti dà i grammi della Sostanza A e ti chiede i grammi della Sostanza B prodotta, segui SEMPRE questo percorso:
**Massa A $\xrightarrow{\text{Step 1}}$ Moli A $\xrightarrow{\text{Step 2}}$ Moli B $\xrightarrow{\text{Step 3}}$ Massa B**

**Esempio Pratico:**
Data la reazione: $2H_2 + O_2 \rightarrow 2H_2O$. Quanti grammi di acqua si ottengono facendo reagire $4 \text{ g}$ di $H_2$ con abbondante $O_2$?
* **Step 1 (Massa A $\rightarrow$ Moli A):** Trovo le moli di $H_2$. ($PM_{H_2} = 2 \text{ g/mol}$).
  $$n_{H_2} = \frac{4 \text{ g}}{2 \text{ g/mol}} = 2 \text{ mol}$$
* **Step 2 (Moli A $\rightarrow$ Moli B):** Guardo i coefficienti della reazione bilanciata. Il rapporto $H_2 : H_2O$ è $2:2$ (ovvero $1:1$). Quindi, da 2 moli di $H_2$ otterrò **$2 \text{ mol}$** di $H_2O$.
* **Step 3 (Moli B $\rightarrow$ Massa B):** Trasformo le moli di acqua in grammi. ($PM_{H_2O} = 18 \text{ g/mol}$).
  $$\text{Massa } H_2O = 2 \text{ mol} \times 18 \text{ g/mol} = \mathbf{36 \text{ g}}$$

---

## 2. Reagente Limitante e Reagente in Eccesso

Quando in un problema (o in un esperimento reale) le quantità iniziali dei reagenti non rispecchiano esattamente i rapporti stechiometrici, uno dei due si esaurirà prima dell'altro.
* **Reagente Limitante:** È il reagente che si consuma completamente per primo. Una volta finito lui, la reazione si ferma. **È lui che determina la quantità massima di prodotto che si può ottenere.**
* **Reagente in Eccesso:** È il reagente che avanza (rimane in parte non reagito) alla fine della reazione.

### Il trucco da Quiz per trovare il Reagente Limitante:
Non fidarti mai delle quantità in grammi per capire chi finirà prima (una sostanza pesante potrebbe sembrare in eccesso ma avere poche moli!). Applica questa regola:

1. Calcola le **moli iniziali** di tutti i reagenti.
2. Dividi le moli di ciascun reagente per il proprio **coefficiente stechiometrico** preso dall'equazione bilanciata.
3. **Il risultato più piccolo** identifica il reagente limitante.

*Esempio:*
Reazione: $N_2 + 3H_2 \rightarrow 2NH_3$
Mettiamo a reagire $2 \text{ mol}$ di $N_2$ e $3 \text{ mol}$ di $H_2$. Chi è il limitante?
* Per $N_2$: $\frac{2}{1} = 2$
* Per $H_2$: $\frac{3}{3} = \mathbf{1}$
Il numero più piccolo appartiene all'Idrogeno. **$H_2$ è il reagente limitante**, e tutta la stechiometria successiva andrà calcolata basandosi solo sui suoi dati!

---

## 3. Resa Teorica e Resa Percentuale

Nella realtà di laboratorio (e nei quiz più complessi), non tutto il reagente limitante si converte magicamente in prodotto puro.
* **Resa Teorica:** È la quantità massima di prodotto calcolabile sulla carta (sulla base del reagente limitante).
* **Resa Effettiva (o Reale):** È la quantità di prodotto fisicamente ottenuta e misurata alla fine dell'esperimento. È quasi sempre inferiore alla resa teorica.

La relazione tra le due si esprime tramite la **Resa Percentuale ($\% R$)**:
$$\% R = \left( \frac{\text{Resa Effettiva}}{\text{Resa Teorica}} \right) \times 100$$

*Esempio rapido da quiz:* Se mi aspetto (teoricamente) $100 \text{ g}$ di prodotto, ma la resa della reazione è dell'$80\%$, otterrò effettivamente solo $80 \text{ g}$.