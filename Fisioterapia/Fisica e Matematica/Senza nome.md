La **Cinematica** è il ramo della meccanica che descrive il moto dei corpi indipendentemente dalle cause che lo producono. Per descrivere il moto, è fondamentale definire un sistema di riferimento.

Essendo velocità e accelerazione delle grandezze vettoriali, assicurati di aver consolidato i concetti espressi in [[Misure: Grandezze fisiche, Sistema Internazionale e Vettori#Vettori e Operazioni]].

## Concetti Fondamentali
- **Posizione ($s$ o $x$):** Il punto occupato da un corpo nello spazio in un determinato istante.
- **Spostamento ($\Delta s$):** La variazione di posizione. È un vettore calcolato come $\Delta s = s_f - s_i$ (posizione finale meno posizione iniziale).
- **Velocità media ($v_m$):** Il rapporto tra lo spostamento e l'intervallo di tempo impiegato a percorrerlo:
$$v_m = \frac{\Delta s}{\Delta t}$$
- **Accelerazione media ($a_m$):** Il rapporto tra la variazione di velocità e l'intervallo di tempo:
$$a_m = \frac{\Delta v}{\Delta t}$$

## Moto Rettilineo Uniforme (MRU)
Un corpo si muove di MRU quando la sua traiettoria è una linea retta e la sua velocità è costante ($v = \text{costante}$). Di conseguenza, l'accelerazione è nulla ($a = 0$).

**Legge oraria del MRU:**
$$s(t) = s_0 + v(t - t_0)$$
Dove:
- $s(t)$ è la posizione al tempo $t$
- $s_0$ è la posizione iniziale (al tempo $t_0$)
- $v$ è la velocità costante

## Moto Rettilineo Uniformemente Accelerato (MRUA)
Un corpo si muove di MRUA quando la sua traiettoria è una retta e la sua accelerazione è costante ($a = \text{costante}$).

**Legge della velocità:**
$$v(t) = v_0 + a(t - t_0)$$

**Legge oraria del MRUA:**
$$s(t) = s_0 + v_0(t - t_0) + \frac{1}{2}a(t - t_0)^2$$

**Equazione di Torricelli (senza il tempo):**
Questa formula è fondamentale per i quiz in cui il tempo non è un dato del problema:
$$v^2 - v_0^2 = 2a(s - s_0)$$

> **Nota per il Test - Caduta Libera:**
> La caduta dei gravi è un caso particolare di MRUA in cui l'accelerazione è l'accelerazione di gravità terrestre ($g \approx 9.81 \, \text{m/s}^2$). Se un corpo viene lasciato cadere da fermo ($v_0 = 0$), lo spazio percorso in caduta è $h = \frac{1}{2}gt^2$.

## Moto Circolare Uniforme (MCU)
Un corpo si muove di MCU quando la sua traiettoria è una circonferenza e il modulo della sua velocità (velocità tangenziale) è costante. 
*Attenzione:* Sebbene il *modulo* della velocità sia costante, la sua *direzione* cambia continuamente, il che implica la presenza di un'accelerazione (l'accelerazione centripeta).

**Grandezze tipiche del MCU:**
- **Periodo ($T$):** Il tempo necessario per compiere un giro completo (in secondi).
- **Frequenza ($f$):** Il numero di giri compiuti in un secondo. Si misura in Hertz ($\text{Hz}$) ed è l'inverso del periodo: $f = \frac{1}{T}$
- **Velocità angolare ($\omega$):** L'angolo spazzato dal raggio vettore nell'unità di tempo. Si misura in $\text{rad/s}$:
$$\omega = \frac{2\pi}{T} = 2\pi f$$
- **Velocità tangenziale ($v$):** Il rapporto tra la lunghezza della circonferenza e il periodo:
$$v = \frac{2\pi r}{T} = \omega r$$
- **Accelerazione centripeta ($a_c$):** È il vettore diretto sempre verso il centro della circonferenza, responsabile del cambiamento di direzione della velocità tangenziale:
$$a_c = \frac{v^2}{r} = \omega^2 r$$

---
**Collegamenti e Generalizzazioni suggerite per la tua Wiki:**
- Ti consiglio di espandere la nota `[[Trigonometria Base per la Fisica]]` includendo la conversione da gradi a radianti, vitale per gestire la velocità angolare $\omega$.
- Per facilitare il richiamo delle formule dirette e inverse nei quiz, potresti creare una nota `[[Formulario di Cinematica]]` e includere i collegamenti ai blocchi delle equazioni principali qui sopra. Ad esempio, per l'equazione di Torricelli potresti linkarla in futuro digitando `[[Cinematica: Moto Rettilineo, Accelerato e Circolare#^]]` e selezionando la riga corrispondente.