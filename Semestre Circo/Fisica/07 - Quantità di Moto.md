Il concetto di **quantità di moto** (o *momento lineare*) è fondamentale in fisica per descrivere lo "stato di moto" di un corpo in modo più completo rispetto alla sola velocità, includendo la sua inerzia (massa).

---

## 1. Definizione di Quantità di Moto

La **quantità di moto** $\vec{p}$ di un punto materiale è una grandezza vettoriale definita come il prodotto della sua massa $m$ per la sua velocità vettoriale $\vec{v}$:
$$\vec{p} = m\vec{v}$$
* Ha la stessa direzione e verso della velocità $\vec{v}$.
* L'unità di misura nel SI è $\text{kg} \cdot \text{m/s}$.

### Riformulazione della Seconda Legge di Newton
La [[Dinamica del Punto Materiale#B. Secondo Principio (Legge Fondamentale)|Seconda Legge di Newton]] ($\vec{F} = m\vec{a}$) può essere espressa in una forma più generale. Assumendo la massa $m$ costante:
$$\vec{F} = m\vec{a} = m \frac{d\vec{v}}{dt} = \frac{d(m\vec{v})}{dt}$$
Si ottiene:
$$\vec{F}_{\text{ris}} = \frac{d\vec{p}}{dt}$$
> "La risultante delle forze agenti su un corpo è uguale alla rapidità di variazione (derivata) della sua quantità di moto nel tempo."
Questa forma è più generale perché resta valida anche per sistemi a massa variabile.

## 2. Impulso ($\vec{I}$)

L'**impulso** $\vec{I}$ è una grandezza vettoriale che misura l'effetto di una [[Dinamica del Punto Materiale|forza]] $\vec{F}$ applicata per un certo intervallo di tempo $\Delta t$.

* **Per una forza costante $\vec{F}$:**
    $$\vec{I} = \vec{F} \cdot \Delta t$$
* **Per una forza variabile $\vec{F}(t)$:**
    L'impulso è definito dall'integrale della forza sull'intervallo di tempo $t_i \to t_f$:
    $$\vec{I} = \int_{t_i}^{t_f} \vec{F}(t) dt$$

L'unità di misura nel SI è $\text{N} \cdot \text{s}$, che è dimensionalmente equivalente a $\text{kg} \cdot \text{m/s}$.

## 3. Teorema dell'Impulso

Questo teorema collega direttamente l'impulso alla variazione della quantità di moto.
Partendo dalla seconda legge $\vec{F} = \frac{d\vec{p}}{dt}$ e integrando nel tempo:
$$d\vec{p} = \vec{F} dt$$
$$\int_{\vec{p}_i}^{\vec{p}_f} d\vec{p} = \int_{t_i}^{t_f} \vec{F}(t) dt$$
Si ottiene il **Teorema dell'Impulso-Quantità di Moto**:
$$\Delta\vec{p} = \vec{p}_f - \vec{p}_i = \vec{I}_{\text{tot}}$$
> "La variazione della quantità di moto di un corpo è uguale all'**impulso della forza risultante** (totale) agente sul corpo."
Questo teorema è utilissimo per analizzare forze intense e di breve durata (es. un calcio a un pallone), dove è difficile misurare $\vec{F}$ ma è facile misurare $\Delta\vec{p}$.

---

## 4. Conservazione della Quantità di Moto

Consideriamo un sistema (es. due particelle che interagiscono).
* **Forze Interne:** Forze scambiate tra le particelle del sistema (es. $\vec{F}_{12}$ e $\vec{F}_{21}$). Per il [[Dinamica del Punto Materiale#C. Terzo Principio (Principio di Azione e Reazione)|Terzo Principio]], la loro somma è sempre zero.
* **Forze Esterne:** Forze esercitate da corpi esterni al sistema (es. la gravità).

La variazione della quantità di moto *totale* del sistema $\vec{p}_{\text{tot}} = \vec{p}_1 + \vec{p}_2$ è:
$$\frac{d\vec{p}_{\text{tot}}}{dt} = \sum \vec{F}_{\text{est}}$$
L'impulso totale delle forze *esterne* è $\vec{I}_{\text{est}} = \Delta\vec{p}_{\text{tot}}$.

Un **sistema isolato** è un sistema su cui la risultante delle forze esterne è nulla ($\sum \vec{F}_{\text{est}} = 0$).
In un sistema isolato:
$$\frac{d\vec{p}_{\text{tot}}}{dt} = 0 \implies \vec{p}_{\text{tot}} = \text{costante}$$

**Principio di Conservazione della Quantità di Moto:**
> "Se la risultante delle forze esterne agenti su un sistema è nulla, la quantità di moto totale del sistema si conserva."
$$\vec{p}_{\text{tot, iniziale}} = \vec{p}_{\text{tot, finale}}$$

Negli urti, le forze interne sono così intense ($\vec{I}_{\text{int}} \gg \vec{I}_{\text{est}}$) che le forze esterne (come la gravità) possono essere trascurate *durante la breve durata dell'urto*, e il sistema si considera isolato.

---

## 5. Applicazioni: Urti in una Dimensione

Un **urto** è un'interazione intensa e di breve durata tra due o più corpi. Durante un urto, il sistema si considera isolato, quindi la **quantità di moto totale si conserva sempre**.

$$m_1\vec{v}_{1i} + m_2\vec{v}_{2i} = m_1\vec{v}_{1f} + m_2\vec{v}_{2f}$$

La distinzione tra i tipi di urto si basa sulla conservazione (o meno) dell'[[Lavoro ed Energia#3. Energia Cinetica ($K$)|Energia Cinetica]].

### A. Urto Elastico
Un urto è **elastico** se si conserva anche l'**energia cinetica** totale del sistema.
$$\begin{cases}
m_1v_{1i} + m_2v_{2i} = m_1v_{1f} + m_2v_{2f} & \text{(Conservazione di } \vec{p} \text{)} \\
\frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 = \frac{1}{2}m_1v_{1f}^2 + \frac{1}{2}m_2v_{2f}^2 & \text{(Conservazione di } K \text{)}
\end{cases}$$
Questo sistema di due equazioni in due incognite ($v_{1f}, v_{2f}$) permette di risolvere completamente il moto.

### B. Urto Anelastico
Un urto è **anelastico** se l'energia cinetica totale **non** si conserva. Parte dell'energia cinetica iniziale viene dissipata (convertita in calore, suono, o usata per deformare permanentemente i corpi).
$$K_f < K_i$$
L'unica legge di conservazione applicabile è quella della quantità di moto:
$$m_1v_{1i} + m_2v_{2i} = m_1v_{1f} + m_2v_{2f}$$
(Non essendoci una seconda equazione, l'urto è indeterminato a meno di non avere informazioni aggiuntive).

### C. Urto Completamente Anelastico
È il caso estremo di urto anelastico, in cui i due corpi restano uniti dopo l'urto, muovendosi con la stessa velocità finale $v_f$ ($v_{1f} = v_{2f} = v_f$).
* È l'urto con la **massima dissipazione** di energia cinetica.
* L'equazione di conservazione della quantità di moto diventa:
    $$m_1v_{1i} + m_2v_{2i} = (m_1 + m_2)v_f$$
    da cui si può facilmente ricavare la velocità finale $v_f$.