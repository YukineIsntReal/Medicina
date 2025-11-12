# I Perossisomi

I **Perossisomi** sono piccoli organelli ($\approx$ 0.1-1 $\mu m$) ubiquitari, delimitati da una **singola membrana**. A differenza dei mitocondri, non possiedono un proprio genoma (mtDNA) né ribosomi; tutte le loro proteine (chiamate **Perossine**, *PEX*) sono codificate da geni nucleari, sintetizzate nel citosol e importate post-traduzionalmente.

Sono organelli metabolicamente molto versatili, il cui nome deriva dalla loro capacità di produrre e (soprattutto) neutralizzare il **perossido di idrogeno ($H_2O_2$)**.

---

## 1. Struttura e Funzioni

* **Struttura:** Un sacchetto membranoso singolo che racchiude una **matrice** granulare e densa, ricca di enzimi ossidativi. In alcune specie, possono contenere un nucleo paracristallino (cristalloide), che è un aggregato di enzimi (es. urato ossidasi).

* **Funzioni Principali:**

    1.  **Metabolismo Lipidico (Ossidazione):**
        * **$\beta$-Ossidazione degli Acidi Grassi a Catena Molto Lunga (VLCFA):** Questa è una funzione *esclusiva* dei perossisomi. I mitocondri gestiscono la $\beta$-ossidazione degli acidi grassi a catena corta, media e lunga, ma non i VLCFA ($>$C22). I perossisomi accorciano i VLCFA, rendendoli poi gestibili dai mitocondri.
        * A differenza della $\beta$-ossidazione mitocondriale, il primo step (ossidazione) nei perossisomi non cede elettroni alla catena respiratoria, ma li trasferisce direttamente all'ossigeno ($O_2$), producendo $H_2O_2$.
    2.  **Sintesi Lipidica:**
        * **Sintesi dei Plasmalogeni:** Sono una classe critica di etero-fosfolipidi in cui una catena acilica è legata all'glicerolo tramite un legame *etere* (non estere). Sono componenti fondamentali della **mielina** che riveste gli assoni nel sistema nervoso. Le prime fasi della loro sintesi avvengono solo nei perossisomi.
    3.  **Metabolismo dell'Acido Urico:** Contengono l'urato ossidasi (assente nell'uomo).
    4.  **Azione Detossificante.**

---

## 2. L'Azione Detossificante

I perossisomi sono cruciali nel neutralizzare sostanze tossiche, in particolare nel fegato e nei reni, usando un meccanismo a due fasi:

1.  **Produzione di $H_2O_2$ (Ossidasi):**
    Enzimi come le *ossidasi* (es. ossidasi degli acidi grassi, urato ossidasi) utilizzano $O_2$ molecolare per rimuovere atomi di idrogeno da substrati organici ($R$), producendo $H_2O_2$ (tossico):
    $RH_2 + O_2 \rightarrow R + H_2O_2$

2.  **Neutralizzazione di $H_2O_2$ (Catalasi):**
    La matrice perossisomiale è ricchissima di **Catalasi**, che utilizza l' $H_2O_2$ (appena prodotto *in situ*, senza che diffonda nel citosol) in due modi:
    * **Azione Perossidasica (Detox):** Usa $H_2O_2$ per ossidare altre molecole tossiche (fenoli, formaldeide, acido formico, etanolo). Questa è la via principale di smaltimento dell'alcol etilico nel fegato.
        $H_2O_2 + R'H_2 \rightarrow R' + 2H_2O$
    * **Azione Catalasica (Sicurezza):** Se l'$H_2O_2$ è in eccesso e non ci sono altri substrati da ossidare, la catalasi decompone $H_2O_2$ in acqua e ossigeno.
        $2H_2O_2 \rightarrow 2H_2O + O_2$

---

## 3. Trasporto e Biogenesi

### 3.1 Biogenesi e Perossine (PEX)
La formazione dei perossisomi è un processo dinamico:
1.  **Crescita e Divisione:** I perossisomi preesistenti possono crescere importando proteine e lipidi, e poi dividersi (fissione) in modo simile ai mitocondri (usando proteine come $Drp1$).
2.  **Biogenesi De Novo:** Esistono evidenze che vescicole "pre-perossisomiali" possano gemmare dal [[Reticolo Endoplasmatico]]. Queste vescicole acquisiscono poi le proteine di membrana e infine quelle della matrice.

L'intero macchinario di importazione e biogenesi è gestito dalle **Perossine**, proteine codificate dai geni *PEX*.

### 3.2 Segnali di Indirizzamento (PTS)
Le proteine destinate ai perossisomi (sintetizzate nel citosol) possiedono un segnale specifico:
* **PTS1 (Peroxisomal Targeting Signal 1):** Il più comune. È una sequenza di tre amminoacidi al **C-terminale**: **$-SKL-$** (Serina-Lisina-Leucina), o varianti simili.
* **PTS2 (Peroxisomal Targeting Signal 2):** Meno comune. È una sequenza (più lunga) localizzata all'**N-terminale**.

### 3.3 Meccanismo e Peculiarità del Trasporto
Il trasporto è mediato da recettori *solubili* nel citosol:
* **Pex5:** È il recettore citosolico che riconosce e lega le proteine cargo con segnale **PTS1**.
* **Pex7:** È il recettore citosolico che (spesso con un co-recettore) lega le proteine cargo con segnale **PTS2**.

Il meccanismo ha delle peculiarità uniche, diverse da RE e Mitocondri:
1.  **Importazione di Proteine Piegate (FOLDED):** Questa è la differenza chiave. I perossisomi possono importare proteine già nel loro stato **nativo e ripiegato**, e persino complessi oligomerici già assemblati (es. la Catalasi, che è un tetramero).
2.  **Meccanismo di Traslocazione:**
    * Pex5 (o Pex7) lega il cargo nel citosol.
    * Il complesso [Recettore-Cargo] si lega a un complesso di *docking* sulla membrana del perossisoma (formato da altre PEX, es. Pex13, Pex14).
    * L'intero complesso (cargo + recettore) viene traslocato attraverso un *traslocone* transitorio.
3.  **Riciclo del Recettore:** A differenza di altri sistemi, il recettore (es. Pex5) *entra* nel perossisoma (o si inserisce nella membrana) con il cargo. Per essere riciclato nel citosol, Pex5 viene **ubiquitinato**. L'energia ($ATP$) viene usata non per "tirare" la proteina (come $Hsp70$ nei mitocondri), ma per *estrarre* Pex5 ubiquitinato dalla membrana e riciclarlo (tramite ATPasi come PEX1 e PEX6).



---

## 4. Patologie (Sindrome di Zellweger)

Le malattie perossisomiali sono un gruppo di gravi disordini metabolici. La più grave è la **Sindrome di Zellweger** (o sindrome cerebro-epato-renale).

* **Tipo:** È una **Malattia da Biogenesi Perossisomiale (PBD)**.
* **Causa:** È una malattia genetica autosomica recessiva causata da mutazioni nei geni *PEX* (es. *PEX1*, *PEX5*, *PEX14*, ecc.).
* **Patofisiologia:** La mutazione in un gene *PEX* rende difettoso il macchinario di importazione. Le proteine della matrice (come la Catalasi o gli enzimi della $\beta$-ossidazione) non possono entrare nel perossisoma.
* **Risultato:** I perossisomi sono "vuoti" (definiti "fantasmi perossisomiali") o del tutto assenti.
* **Conseguenze Cliniche:**
    1.  **Accumulo di VLCFA:** I grassi a catena molto lunga non possono essere ossidati e si accumulano nel sangue e nei tessuti, specialmente nel Sistema Nervoso Centrale (SNC), causando grave danno neurologico (difetti di mielinizzazione).
    2.  **Deficit di Plasmalogeni:** La mancata sintesi di questi lipidi aggrava i difetti neurologici (la mielina è difettosa).
* **Clinica:** I neonati presentano grave ipotonia, dismorfismi facciali caratteristici, convulsioni intrattabili, disfunzione epatica e renale. La prognosi è infausta, con morte entro il primo anno di vita.