Le misure e la gestione delle grandezze fisiche rappresentano le fondamenta per affrontare i quesiti scientifici del test d'ingresso. Una solida comprensione di questi concetti accelera anche la risoluzione dei problemi di chimica.

## Grandezze Fisiche
Una **grandezza fisica** è una qualunque proprietà di un fenomeno naturale che può essere misurata in modo oggettivo. Si dividono principalmente in due grandi categorie:
- **Grandezze Scalari:** sono completamente definite da un numero (il valore della misura) e dalla sua unità di misura (es. tempo, massa, temperatura, densità, lavoro).
- **Grandezze Vettoriali:** per essere definite necessitano di un modulo (o intensità), una direzione (la retta su cui giacciono), un verso (orientamento sulla retta) e un punto di applicazione (es. forza, velocità, accelerazione, campo elettrico).

Inoltre, ricorda la differenza tra:
- **Grandezze Intensive:** non dipendono dalla quantità di materia del campione (es. temperatura, pressione, densità).
- **Grandezze Estensive:** dipendono dalla quantità di materia (es. massa, volume, energia).

## Il Sistema Internazionale (SI)
Il Sistema Internazionale definisce sette grandezze **fondamentali**, fisicamente indipendenti, da cui si ricavano, tramite formule matematiche, tutte le grandezze **derivate** (come velocità, forza, pressione).

| Grandezza Fondamentale | Unità di Misura | Simbolo |
| :--- | :--- | :--- |
| Lunghezza | metro | m |
| Massa | chilogrammo | kg |
| Tempo | secondo | s |
| Intensità di corrente elettrica | ampere | A |
| Temperatura termodinamica | kelvin | K |
| Quantità di sostanza | mole | mol |
| Intensità luminosa | candela | cd |

*Attenzione per i test:* I prefissi del SI sono oggetto frequente di domanda. Assicurati di padroneggiare conversioni con prefissi come micro ($\mu$, $10^{-6}$), nano (n, $10^{-9}$) e pico (p, $10^{-12}$).

## Vettori e Operazioni
Un vettore $\vec{v}$ è uno strumento matematico fondamentale in fisica. Il suo modulo è indicato con $|\vec{v}|$ o semplicemente con $v$.

### Somma di Vettori
- **Metodo Punta-Coda:** Si fa coincidere la coda del secondo vettore con la punta del primo; il vettore somma unisce la coda del primo alla punta del secondo.
- **Regola del Parallelogramma:** Se due vettori $\vec{a}$ e $\vec{b}$ hanno la stessa origine, la somma $\vec{c} = \vec{a} + \vec{b}$ è la diagonale del parallelogramma costruito su di essi. 
Il modulo della somma (se l'angolo compreso è $\theta$) si calcola con il teorema del coseno generalizzato:
$$|\vec{a} + \vec{b}| = \sqrt{a^2 + b^2 + 2ab \cos(\theta)}$$

### Prodotto tra Vettori
- **Prodotto Scalare:** Restituisce un numero (uno scalare). 
$$\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$$
*Tip:* Se due vettori sono perpendicolari ($\theta = 90^\circ$), il loro prodotto scalare è nullo. Questo concetto è basilare per calcolare il Lavoro di una forza perpendicolare allo spostamento.

- **Prodotto Vettoriale:** Restituisce un nuovo vettore $\vec{c} = \vec{a} \times \vec{b}$ perpendicolare al piano individuato da $\vec{a}$ e $\vec{b}$.
Il modulo del prodotto vettoriale è:
$$|\vec{c}| = |\vec{a}| |\vec{b}| \sin(\theta)$$

## Errori di Misura
Poiché nessuna misurazione è perfetta, nei test d'ingresso potresti imbatterti nell'analisi degli errori:
- **Errore Assoluto ($e_a$):** Rappresenta la semidispersione massima in una serie di misure. 
$$e_a = \frac{x_{max} - x_{min}}{2}$$
- **Errore Relativo ($e_r$):** È il rapporto tra l'errore assoluto e il valore medio della misura ($x_m$). È una grandezza adimensionale (non ha unità di misura).
$$e_r = \frac{e_a}{x_m}$$
- **Errore Percentuale ($e_\%$):** È semplicemente l'errore relativo espresso in percentuale.
$$e_\% = e_r \cdot 100$$

---
**Collegamenti suggeriti per la tua Wiki:**
- Ti consiglio di creare una nota separata per le conversioni e i prefissi chiamandola ad esempio `[[Prefissi SI e Conversioni]]` e un'altra di matematica su `[[Trigonometria Base per la Fisica]]` (in cui inserire i valori noti di seno e coseno per angoli come 30°, 45° e 60°).
- Se in futuro vorrai richiamare la formula del prodotto scalare direttamente nella nota dedicata al "Lavoro", potrai usare un link a blocco diretto a quella specifica formula digitando `[[Misure: Grandezze fisiche, Sistema Internazionale e Vettori#^]]` e selezionando il blocco corrispondente!