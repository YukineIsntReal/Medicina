Alcuni nuclei atomici possiedono una proprietà quantistica intrinseca chiamata **spin nucleare**. Si può immaginare lo spin (anche se è una semplificazione) come il nucleo che "ruota" sul proprio asse.

Dato che il nucleo è carico positivamente (a causa dei protoni), questa rotazione genera un piccolo campo magnetico, detto **momento di dipolo magnetico**. In pratica, il nucleo si comporta come una minuscola calamita.

Questa proprietà è presente nei nuclei con:
* Numero di massa ($A$) dispari.
* Numero atomico ($Z$) e numero di neutroni ($N$) entrambi dispari.

(I nuclei con $A$ e $Z$ entrambi pari hanno spin nullo e sono "invisibili" alla risonanza magnetica).

### Il Protone come Base della RMN

Il nucleo più importante per la diagnostica medica è quello dell'atomo di Idrogeno ($\text{ }^{1}H$), che è costituito da un singolo **protone ($p^+$)**. Il protone ha uno spin non nullo e un forte momento magnetico.

Data l'enorme abbondanza di atomi di idrogeno nel corpo umano (principalmente nell'acqua, $H_2O$, e nei lipidi), il segnale che possiamo ottenere da essi è molto forte.

### Principi della Risonanza Magnetica Nucleare (RMN)

La Risonanza Magnetica Nucleare (RMN), in ambito clinico più nota come **Imaging a Risonanza Magnetica** (MRI, *Magnetic Resonance Imaging*), sfrutta questo fenomeno:

1.  **Allineamento:** In assenza di un campo magnetico esterno, gli spin dei protoni nel corpo sono orientati casualmente. Quando il paziente viene inserito in un magnete molto potente (il "tunnel" della RMN), i protoni allineano i loro spin con il campo magnetico esterno ($B_0$), un po' come aghi di una bussola. Si allineano in due stati: parallelo (bassa energia) e antiparallelo (alta energia), con una leggerissima prevalenza per lo stato a bassa energia.
2.  **Precessione:** I protoni non si allineano staticamente, ma "precedono" (ruotano come trottole) attorno alle linee del campo $B_0$ a una frequenza specifica, detta **frequenza di Larmor**, che è proporzionale alla forza del campo $B_0$.
3.  **Risonanza:** Vengono inviati degli impulsi di **radiofrequenza** ($RF$) sintonizzati esattamente sulla frequenza di Larmor. I protoni nello stato a bassa energia assorbono questa energia (fenomeno della *risonanza*) e "saltano" allo stato ad alta energia (antiparallelo).
4.  **Rilassamento e Segnale:** Quando l'impulso RF cessa, i protoni "eccitati" tornano al loro stato di equilibrio (bassa energia). Rilasciando l'energia assorbita, emettono un segnale radio.
5.  **Imaging:** Questo segnale viene captato da antenne. I diversi tessuti del corpo (es. grasso, muscolo, acqua, tessuto cerebrale) hanno tempi di "rilassamento" diversi (noti come $T_1$ e $T_2$). Analizzando queste differenze temporali e spaziali (tramite campi magnetici gradienti), un computer può ricostruire un'immagine tridimensionale dettagliata dei tessuti molli del corpo.