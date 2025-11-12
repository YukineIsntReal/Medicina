Nei [[Procarioti]], la [[Trascrizione]] è un processo rapidissimo e spesso **accoppiato** alla [[Traduzione]]. La regolazione genica è cruciale per permettere al batterio (es. *E. coli*) di adattarsi velocemente ai cambiamenti ambientali, attivando i geni solo quando i loro prodotti sono necessari.

L'**[[Operone]]** è l'unità trascrizionale fondamentale nei procarioti. L'**Operone Lattosio** (**[[Operone Lac]]**) è l'esempio canonico di un operone *inducibile*, ovvero un gruppo di geni che vengono "accesi" solo in presenza di uno specifico substrato (l'induttore).

L'obiettivo dell'Operone Lac è semplice: permettere a *E. coli* di utilizzare il lattosio (uno zucchero) come fonte di energia, **solo** se il lattosio è disponibile e **solo** se una fonte di energia migliore (il glucosio) è assente.

## Componenti dell'Operone Lac

L'operone è composto da:
1.  **Geni Strutturali**: I geni che codificano per le proteine metaboliche.
    * `lacZ`: Codifica per la **$\beta$-galattosidasi**, l'enzima che scinde il lattosio in glucosio e galattosio.
    * `lacY`: Codifica per la **Permeasi**, una proteina di membrana che trasporta attivamente il lattosio all'interno della cellula.
    * `lacA`: Codifica per la **Transacetilasi** (ruolo secondario nel metabolismo del lattosio).
2.  **Elementi Regolativi *in cis***:
    * **Promotore ($P$)**: Il sito di legame per la [[RNA Polimerasi]].
    * **Operatore ($O$)**: Una sequenza di DNA (posta tra il promotore e i geni strutturali) che agisce da "interruttore". È il sito di legame per la proteina Repressore.
3.  **Gene Regolatore** (Esterno all'operone):
    * `lacI`: Un gene (con un proprio promotore) che codifica per la proteina **Repressore Lac**. Questo gene è espresso *costitutivamente* (sempre attivo) a bassi livelli.

## Regolazione 1: Controllo Negativo (Induzione)

Questo meccanismo risponde alla domanda: "C'è lattosio?"

### Stato 1: Assenza di Lattosio (Operone Spento - OFF)
1.  Il gene `lacI` produce il **Repressore Lac** (una proteina attiva).
2.  Il repressore si lega saldamente all'**Operatore ($O$)**.
3.  Il legame del repressore sull'operatore impedisce fisicamente alla [[RNA Polimerasi]] di legarsi al promotore $P$ o di avanzare lungo i geni strutturali.
4.  **Risultato**: La trascrizione è bloccata. La cellula non spreca energia per produrre enzimi per il lattosio se non c'è lattosio.


### Stato 2: Presenza di Lattosio (Operone Acceso - ON)
1.  Quando il lattosio entra nella cellula, una piccola quantità viene convertita in **Allolattosio** (un isomero del lattosio).
2.  L'Allolattosio agisce da **Induttore**: si lega al Repressore Lac.
3.  Questo legame causa un cambiamento conformazionale nel repressore, che **perde la sua affinità** per l'Operatore ($O$) e si stacca dal DNA.
4.  L'Operatore è ora libero. La RNA Polimerasi può legarsi al Promotore $P$ e trascrivere i geni strutturali ($lacZ, lacY, lacA$) in un unico **mRNA policistronico**.
5.  **Risultato**: Gli enzimi per metabolizzare il lattosio vengono prodotti.


## Regolazione 2: Controllo Positivo (Repressione da Catabolita)

Questo meccanismo risponde alla domanda: "C'è una fonte di energia migliore (glucosio)?"

I batteri preferiscono il glucosio. Se sono presenti sia glucosio che lattosio, l'Operone Lac rimane quasi spento.

Questo controllo dipende da due elementi:
1.  **$cAMP$ (AMP ciclico)**: Un segnale di "fame cellulare". I suoi livelli sono *inversamente proporzionali* a quelli del glucosio (Basso Glucosio $\to$ Alto $cAMP$; Alto Glucosio $\to$ Basso $cAMP$).
2.  **CAP (Catabolite Activator Protein)**: Una proteina *Attivatrice*. È attiva solo quando è legata al $cAMP$.

### Stato A: Presenza di Glucosio (Bassa Trascrizione)
1.  I livelli di $cAMP$ sono bassi.
2.  La proteina CAP è *inattiva* e non si lega al $cAMP$.
3.  Anche se il lattosio è presente (e il repressore è staccato), la RNA Polimerasi ha una bassa affinità per il promotore $lac$ da sola.
4.  **Risultato**: La trascrizione avviene, ma a livelli molto bassi (trascrizione basale).

### Stato B: Assenza di Glucosio (e Presenza di Lattosio) (Alta Trascrizione)
1.  I livelli di $cAMP$ sono alti.
2.  Il $cAMP$ si lega alla proteina CAP, attivandola.
3.  Il complesso **$cAMP-CAP$** si lega a un sito specifico sul DNA (vicino al promotore $P$).
4.  Questo legame *facilita* (recluta) la RNA Polimerasi, aumentando enormemente la sua affinità per il promotore.
5.  **Risultato**: Si ottiene un alto livello di trascrizione (espressione massima).


---
### Riepilogo Logico

| Glucosio | Lattosio | $cAMP$ | Repressore | CAP | Livello Trascrizione |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **+** | **-** | Basso | **Legato** (a $O$) | Inattivo | **SPENTO** (No) |
| **+** | **+** | Basso | **Staccato** (da $O$) | Inattivo | **BASSO** (Basale) |
| **-** | **-** | Alto | **Legato** (a $O$) | Attivo | **SPENTO** (No) |
| **-** | **+** | Alto | **Staccato** (da $O$) | **Attivo** (Legato) | **ALTO** (Massimo) |