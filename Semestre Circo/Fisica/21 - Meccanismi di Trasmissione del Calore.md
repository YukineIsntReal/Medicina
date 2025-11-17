Il calore ($Q$), come definito nella nota [[20 - Calore, Capacità Termica e Cambiamenti di Stato#Calore ($Q$)|precedente]], è energia in transito. Questo trasferimento di energia può avvenire attraverso tre meccanismi fondamentali, che possono coesistere, anche se spesso uno è predominante.

---

## 1. Conduzione Termica

La **conduzione** è il meccanismo di trasferimento del calore che avviene attraverso il contatto fisico diretto, senza un movimento macroscopico della materia. L'energia cinetica viene trasferita da una particella (atomo o molecola) a quella adiacente attraverso le collisioni.

* È il meccanismo dominante nei **solidi**.
* Esempio: Toccando un oggetto metallico (buon conduttore), si avverte una rapida sensazione di freddo perché il calore della mano viene condotto via velocemente.

### Flusso di Calore e Legge di Fourier

Il **flusso di calore** ($\Phi$) è la quantità di calore ($dQ$) che attraversa una superficie nell'unità di tempo ($dt$). Si misura in Watt ($W = J/s$).

La **Legge di Fourier** descrive la conduzione termica:

$\Phi = \frac{dQ}{dt} = -k \cdot A \cdot \frac{\Delta T}{\Delta x}$

Dove:
* $k$ = **Conducibilità termica** (o conduttività): Una costante che indica la capacità di un materiale di condurre calore ($W/(m·K)$). Metalli (argento, rame) hanno $k$ alta; isolanti (grasso, polistirolo, aria) hanno $k$ bassa.
* $A$ = Area della superficie attraverso cui passa il calore.
* $\frac{\Delta T}{\Delta x}$ = **Gradiente di temperatura**, ovvero la variazione di temperatura per unità di lunghezza. Il segno "$-$" indica che il calore fluisce sempre dalla temperatura più alta a quella più bassa (contro il gradiente).

---

## 2. Convenzione

La **convenzione** è un meccanismo di trasferimento del calore che avviene tramite il **movimento macroscopico di un fluido** (liquido o gas). Il fluido, riscaldandosi, si sposta, trasportando con sé l'energia termica.

* **Convenzione Naturale:** Il movimento è causato da differenze di densità dovute al riscaldamento. L'aria calda (meno densa) sale, l'aria fredda (più densa) scende, creando "moti convettivi".
* **Convenzione Forzata:** Il movimento del fluido è indotto da un agente esterno (es. una pompa, un ventilatore).

**Esempi:**
* *Naturale:* Il riscaldamento dell'acqua in una pentola; le correnti d'aria in una stanza.
* *Forzata:* Il sistema di raffreddamento di un computer (ventola); il **flusso sanguigno** nel corpo umano, che distribuisce il calore metabolico dagli organi interni verso la pelle.

---

## 3. Irraggiamento

L'**irraggiamento** è il trasferimento di calore tramite **onde elettromagnetiche** (radiazione infrarossa), che si propagano anche nel vuoto (non richiedono un mezzo materiale).

Ogni corpo con una temperatura superiore allo zero assoluto ($0 K$) emette energia sotto forma di radiazione termica.

### Emissione Termica e Corpo Nero

Un **corpo nero** è un oggetto ideale che assorbe il 100% della radiazione incidente e riemette radiazione termica con la massima efficienza possibile a una data temperatura.

### Legge di Wien (Legge dello Spostamento)

Questa legge correla la temperatura ($T$) di un corpo nero al picco di lunghezza d'onda ($\lambda_{max}$) della radiazione emessa. Più un corpo è caldo, più la radiazione emessa è "energetica" (lunghezza d'onda più corta).

$\lambda_{max} \cdot T = b$

* $b$ è la costante di Wien (circa $2.898 \times 10^{-3} m·K$).
* **Esempio:** Il sole (circa $5700 K$) emette nel visibile. Il corpo umano (circa $310 K$ o $37°C$) emette principalmente nell'infrarosso (circa $9-10 \mu m$).

### Potenza Irraggiata (Legge di Stefan-Boltzmann)

Descrive la potenza totale ($P$) irradiata da un oggetto per unità di superficie ($A$).

$P = \epsilon \cdot \sigma \cdot A \cdot T^4$

Dove:
* $\sigma$ = Costante di Stefan-Boltzmann ($5.67 \times 10^{-8} W/(m^2·K^4)$).
* $T$ = Temperatura assoluta (in Kelvin). La dipendenza da $T^4$ rende l'irraggiamento molto sensibile alle variazioni di temperatura.
* $\epsilon$ = **Emissività** (un numero da 0 a 1). È il rapporto tra la potenza emessa da un corpo reale e quella emessa da un corpo nero alla stessa temperatura. Un corpo nero ha $\epsilon = 1$.

---

## Esempi di Trasmissione del Calore (Sintesi)

| Meccanismo | Descrizione | Esempio Fisico | Esempio Biologico/Medico |
| :--- | :--- | :--- | :--- |
| **Conduzione** | Contatto diretto | Cucchiano di metallo che si scalda in una tazza calda. | Perdita di calore per contatto con una superficie fredda (es. panca di metallo); impacchi caldi/freddi sulla pelle. |
| **Convenzione** | Movimento di fluido | Radiatore (termosifone) che scalda l'aria della stanza. | Il **flusso sanguigno** (convenzione forzata) che porta calore alla pelle; perdita di calore al vento. |
| **Irraggiamento**| Onde elettromagnetiche | Sentire il calore del sole; il calore di un falò. | Il corpo umano che irradia calore verso l'ambiente (principale meccanismo di perdita a riposo); **termografia** medica; incubatrici neonatali. |