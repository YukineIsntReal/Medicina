La materia risponde in modi molto diversi alla presenza di un campo elettrico $\vec{E}$. La distinzione principale si basa sulla mobilità delle cariche al loro interno.

## 1. Conduttori

I **conduttori** (es. metalli, soluzioni elettrolitiche) sono materiali che contengono un gran numero di *portatori di carica liberi* di muoversi (elettroni di conduzione nei metalli, ioni positivi e negativi nelle soluzioni).

### Equilibrio Elettrostatico
Quando un conduttore è posto in un campo elettrico esterno $\vec{E}_{est}$ (o quando gli viene fornita una carica netta), le cariche libere si muovono. Dopo un tempo brevissimo, il sistema raggiunge una nuova configurazione stabile chiamata **equilibrio elettrostatico**, che ha le seguenti proprietà:

1.  **Campo Elettrico Interno Nullo:** Il campo elettrico totale $\vec{E}_{int}$ all'interno del conduttore è **zero** ($\vec{E}_{int} = 0$).
2.  **Carica Netta solo in Superficie:** Qualsiasi carica netta in eccesso risiede *esclusivamente* sulla superficie esterna del conduttore. All'interno, la densità di carica è nulla.
3.  **Campo Esterno Perpendicolare:** Il campo elettrico $\vec{E}$ appena fuori dalla superficie del conduttore è sempre perpendicolare alla superficie stessa.
4.  **Conduttore Equipotenziale:** Tutti i punti di un conduttore in equilibrio (sia in superficie che al suo interno) si trovano allo **stesso potenziale elettrico $V$**. (Se non fosse così, esisterebbe un $\Delta V \neq 0$, che genererebbe un $\vec{E} \neq 0$ e muoverebbe le cariche, contraddicendo l'ipotesi di equilibrio).

### Induzione Elettrostatica
È il fenomeno di ridistribuzione delle cariche libere in un conduttore neutro a causa di un campo elettrico esterno.

Se un conduttore (es. una sfera metallica neutra) viene posto in un $\vec{E}_{est}$:
1.  Le cariche libere (es. elettroni) si muovono in direzione opposta a $\vec{E}_{est}$, accumulandosi su un lato della sfera.
2.  Questo lascia un eccesso di cariche positive fisse (nuclei atomici) sul lato opposto.
3.  Questa separazione di carica ($\sigma-$ e $\sigma+$) genera un proprio campo elettrico interno, $\vec{E}_{indotto}$, che si oppone a quello esterno.
4.  Il processo si ferma quando $\vec{E}_{indotto}$ è diventato esattamente uguale e opposto a $\vec{E}_{est}$, così che all'interno del conduttore:
    $\vec{E}_{tot} = \vec{E}_{est} + \vec{E}_{indotto} = 0$
Questo fenomeno è alla base della *schermatura elettrostatica* (Gabbia di Faraday).

---

## 2. Dielettrici (Isolanti)

I **dielettrici** (o isolanti, es. vetro, plastica, olio, acqua pura, *doppio strato lipidico*) sono materiali che **non** possiedono cariche libere di muoversi. Tutti gli elettroni sono strettamente legati ai loro atomi o molecole.

### Polarizzazione
Quando un dielettrico è immerso in un campo elettrico esterno $\vec{E}_{est}$, le cariche non possono muoversi attraverso il materiale, ma possono *ridistribuirsi localmente* a livello atomico/molecolare. Questo fenomeno è chiamato **polarizzazione**.

Il risultato netto è che, pur rimanendo neutro al suo interno, il dielettrico genera delle cariche superficiali (di polarizzazione) $\sigma_p$ sulla sua superficie. Queste cariche generano un campo indotto $\vec{E}_{pol}$ che, come nei conduttori, si oppone al campo esterno.

A differenza dei conduttori, però, $\vec{E}_{pol}$ è *sempre più debole* di $\vec{E}_{est}$.
Di conseguenza, il campo elettrico totale all'interno del dielettrico $\vec{E}_{int}$ **non è nullo**, ma è solo *attenuato*:
$\vec{E}_{int} = \vec{E}_{est} + \vec{E}_{pol} \neq 0$
($E_{int} < E_{est}$)

Il fattore di cui il campo viene ridotto è chiamato **costante dielettrica relativa** ($\kappa$ o $\epsilon_r$):
$E_{int} = \frac{E_{est}}{\kappa}$
(Per il vuoto $\kappa=1$; per i dielettrici $\kappa > 1$. L'acqua ha $\kappa \approx 80$).

### Meccanismi di Polarizzazione

Esistono due meccanismi principali:

#### A. Polarizzazione per Deformazione (Dielettrici A-polari)
In atomi o molecole a-polari (es. $N_2$, $O_2$, lipidi), il centro delle cariche positive (nuclei) e negative (nubi elettroniche) coincide.
Quando applicato un $\vec{E}_{est}$, il nucleo viene spinto leggermente in un verso e la nube elettronica nell'altro. L'atomo si "deforma", creando un piccolo **dipolo elettrico indotto**.

#### B. Polarizzazione per Orientamento (Dielettrici Polari)
In molecole polari (es. $H_2O$), le cariche sono già separate permanentemente, formando un **dipolo elettrico permanente** (vedi [[Potenziale Elettrico#5. Dipolo Elettrico|Dipolo Elettrico]]).
In assenza di campo, questi dipoli sono orientati casualmente (agitazione termica) e l'effetto netto è nullo.
Quando applicato un $\vec{E}_{est}$, questo esercita un [[Potenziale Elettrico#Dipolo in un Campo Elettrico Esterno E|momento torcente]] sui dipoli, che tendono ad *allinearsi* (parzialmente, contrastati dall'agitazione termica) con il campo.