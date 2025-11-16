## Acidità degli Idrogeni in Alfa ($\alpha$)

Si definisce **Carbonio Alfa** ($C_\alpha$) il carbonio adiacente al gruppo carbonilico ($C=O$). Gli idrogeni legati ad esso sono detti **Idrogeni Alfa** ($H_\alpha$).

La proprietà fondamentale di questi idrogeni è la loro **acidità**.

Sebbene i legami $C-H$ siano generalmente non acidi (pKa di un alcano $\approx 50$), gli idrogeni in $\alpha$ a un carbonile hanno un $pKa \approx 19-20$. Sono quindi *milioni di volte più acidi* degli idrogeni di un alcano.

Questa acidità è dovuta a due fattori:
1.  **Effetto Induttivo:** Il gruppo $C=O$ è fortemente elettron-attrattore e polarizza il legame $C_\alpha-H$, indebolendolo.
2.  **Stabilizzazione della Base Coniugata:** Questo è il fattore dominante. Quando una base rimuove un $H_\alpha$, si forma un carbanione. Questo carbanione, chiamato **Ione Enolato**, non è un carbanione "normale": è stabilizzato per **risonanza**.

La carica negativa non risiede solo sul $C_\alpha$, ma è delocalizzata sull'atomo di ossigeno, che è molto più elettronegativo e sopporta meglio la carica.

$$\underbrace{R-\overset{O}{\overset{||}{C}}-\underset{\alpha}{C}H_2-R'}_{\text{Forma Chetonica}} + B: \rightleftharpoons \underbrace{[ R-\overset{O}{\overset{||}{C}}-{}^{\ominus}CH-R' \longleftrightarrow R-\overset{O^-}{\overset{|}{C}}=CH-R' ]}_{\text{Ione Enolato (stabilizzato per risonanza)}} + BH$$

Lo ione enolato è un intermedio chiave in moltissime reazioni biochimiche.

---

## Tautomeria Cheto-Enolica

L'acidità dell'$H_\alpha$ porta direttamente al fenomeno della **tautomeria**.

I **Tautomeri** sono isomeri costituzionali in rapido equilibrio tra loro, che differiscono per la posizione di un protone e di un doppio legame.

Per aldeidi e chetoni, i due tautomeri sono:
1.  **Forma Chetonica:** La forma standard con il doppio legame $C=O$.
2.  **Forma Enolica:** (da *-ene* + *-olo*) Una forma con un doppio legame $C=C$ e un gruppo ossidrile ($-OH$) legato a uno dei carboni del doppio legame.

$$\underbrace{R-\overset{O}{\overset{||}{C}}-CH_2-R'}_{\text{Forma Chetonica}} \rightleftharpoons \underbrace{R-\overset{OH}{\overset{|}{C}}=CH-R'}_{\text{Forma Enolica}}$$

L'interconversione (detta **tautomerizzazione**) è catalizzata sia da acidi che da basi e procede attraverso l'intermedio enolato (in catalisi basica) o il suo equivalente protonato (in catalisi acida).

### Posizione dell'Equilibrio
Per la maggior parte delle aldeidi e chetoni semplici (es. acetone), l'equilibrio è quasi totalmente ($>99.9\%$) spostato verso la **forma chetonica**.
*Motivo:* Il doppio legame $C=O$ è termodinamicamente molto più stabile del doppio legame $C=C$.

L'equilibrio si sposta verso l'enolo solo in casi particolari (es. composti $\beta$-dicarbonilici), dove l'enolo è stabilizzato dalla coniugazione o da legami idrogeno intramolecolari.

---

## Importanza Biologica della Tautomeria

Anche se la forma enolica è termodinamicamente sfavorita, la sua *formazione* è cruciale. Molti enzimi operano catalizzando la tautomeria, utilizzando un intermedio enolico (o enolato) per eseguire reazioni che sarebbero impossibili sulla forma chetonica.

### 1. Metabolismo dei Carboidrati (Glicolisi)
Le **isomerasi** nella glicolisi dipendono da questo meccanismo.
* **Fosfoglucosio Isomerasi:** Catalizza la conversione **Glucosio-6-fosfato $\rightleftharpoons$ Fruttosio-6-fosfato**.
    * Il G6P (un'aldeide/aldoso) viene convertito in un intermedio **enediolo** (un enolo con due $-OH$) nel sito attivo.
    * L'enediolo collassa poi a F6P (un chetone/chetoso).
* **Trioso Fosfato Isomerasi (TIM):** Catalizza la conversione **Diidrossiacetone Fosfato (DHAP) $\rightleftharpoons$ Gliceraldeide-3-fosfato (G3P)**.
    * Anche questa reazione fondamentale, che permette a tutto il glucosio di procedere nella glicolisi, passa attraverso un intermedio **enediolo**.

### 2. Metabolismo degli Amminoacidi
Le reazioni di **transaminazione** (trasferimento di un gruppo amminico), catalizzate da enzimi che usano il coenzima Piridossal Fosfato ($PLP$), coinvolgono una serie di tautomerie (tra forme imminiche ed enoliche) per spostare il gruppo $NH_2$.

### 3. Mutagenesi Spontanea (DNA)
Questo è uno degli esempi più critici. Le basi azotate (Guanina, Timina, Adenina, Citosina) esistono in un equilibrio tautomerico (cheto $\rightleftharpoons$ enol, o ammino $\rightleftharpoons$ immino).
* **Forma Standard (Cheto):** La Timina e la Guanina sono stabili in forma chetonica.
* **Forma Rara (Enolo):** Occasionalmente, tautomerizzano nella loro forma enolica.

Questo ha conseguenze drammatiche sulla replicazione del DNA:
* **Timina (Cheto)** si appaia correttamente con **Adenina**.
* **Timina (Enolo)** si appaia erroneamente (mispairing) con **Guanina**.

Questo "salto" tautomerico è una delle cause principali delle **mutazioni puntiformi** spontanee nel genoma.