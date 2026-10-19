
# Moto circolare

## Introduzione

Il **moto circolare** è il movimento di un corpo lungo una traiettoria circolare di raggio $R$.

A differenza del moto rettilineo, nel moto circolare la direzione della velocità cambia continuamente, anche quando il suo modulo rimane costante.

Si distinguono due casi principali:

- **Moto circolare uniforme (MCU):** il modulo della velocità è costante.
- **Moto circolare non uniforme:** il modulo della velocità varia nel tempo.

Nel moto circolare uniforme il corpo possiede comunque un'accelerazione, detta **accelerazione centripeta**, perché cambia continuamente la direzione della velocità.

---

## Grandezze fondamentali

### Raggio e posizione angolare

Il **raggio** $R$ è la distanza tra il centro della traiettoria e il corpo.

La **posizione angolare** $\theta$ indica la posizione del corpo lungo la circonferenza rispetto a una direzione di riferimento.

Gli angoli possono essere espressi in radianti:

$$
\boxed{360^\circ=2\pi\ \text{rad}}
$$

Una rotazione completa corrisponde quindi a $2\pi$ radianti.

La lunghezza di un arco di circonferenza è:

$$
\boxed{s=R\theta}
$$

dove:
- $s$ = lunghezza dell'arco (m).
- $R$ = raggio (m).
- $\theta$ = angolo percorso (rad).

La formula richiede che l'angolo sia espresso in radianti.

### Periodo

Il **periodo** $T$ è il tempo necessario per completare un giro.

Si misura in secondi (s).

$$
\boxed{T=\frac{\Delta t}{N}}
$$

dove:
- $\Delta t$ = tempo impiegato.
- $N$ = numero di giri completi.

### Frequenza

La **frequenza** $f$ rappresenta il numero di giri compiuti nell'unità di tempo.

Si misura in hertz (Hz), equivalenti a $s^{-1}$.

$$
\boxed{f=\frac{1}{T}}
$$

Di conseguenza:

$$
\boxed{T=\frac{1}{f}}
$$

**Esempio**

Un corpo compie 5 giri al secondo.

$$
f=5\ \text{Hz}
$$

$$
T=\frac15=\boxed{0{,}2\ \text{s}}
$$

### Velocità angolare

La **velocità angolare** $\omega$ descrive quanto rapidamente cambia la posizione angolare.

La velocità angolare media è:

$$
\omega_m=\frac{\Delta\theta}{\Delta t}
$$

Nel moto circolare uniforme, la velocità angolare è costante.

Poiché un giro completo corrisponde a $2\pi$ radianti:

$$
\boxed{\omega=\frac{2\pi}{T}}
$$

Utilizzando la frequenza:

$$
\boxed{\omega=2\pi f}
$$

L'unità di misura è rad/s.

### Velocità tangenziale

La **velocità tangenziale** è la velocità lineare posseduta da un corpo che percorre una circonferenza.

Il vettore velocità è sempre tangente alla traiettoria.

Nel moto circolare uniforme, il modulo della velocità tangenziale è:

$$
\boxed{v=\frac{2\pi R}{T}}
$$

Equivalente a:

$$
\boxed{v=\omega R}
$$

oppure:

$$
\boxed{v=2\pi Rf}
$$

dove:
- $v$ = velocità tangenziale (m/s).
- $R$ = raggio della traiettoria (m).
- $T$ = periodo (s).
- $\omega$ = velocità angolare (rad/s).
- $f$ = frequenza (Hz).

**Importante:** a parità di velocità angolare, un corpo più lontano dall'asse di rotazione possiede una velocità tangenziale maggiore.

---

## Moto circolare uniforme (MCU)

Il moto circolare uniforme è caratterizzato da:

- Traiettoria circolare.
- Modulo della velocità costante.
- Velocità angolare costante.
- Accelerazione centripeta non nulla.

La legge oraria angolare è:

$$
\boxed{\theta(t)=\theta_0+\omega t}
$$

dove:
- $\theta_0$ = posizione angolare iniziale.
- $\omega$ = velocità angolare costante.
- $t$ = tempo trascorso.

### Perché esiste un'accelerazione?

La velocità è una grandezza vettoriale, quindi possiede:

1. Modulo.
2. Direzione.
3. Verso.

Nel moto circolare uniforme il modulo rimane costante, ma la direzione del vettore velocità cambia continuamente.

Poiché l'accelerazione descrive la variazione della velocità, il corpo è accelerato anche senza aumentare o diminuire la propria rapidità.

Questa accelerazione è sempre diretta verso il centro della circonferenza.

---

## Accelerazione centripeta

L'**accelerazione centripeta** è l'accelerazione necessaria per mantenere un corpo lungo una traiettoria circolare.

Il suo vettore è diretto radialmente verso il centro della circonferenza.

Il modulo è:

$$
\boxed{a_c=\frac{v^2}{R}}
$$

Utilizzando $v=\omega R$:

$$
\boxed{a_c=\omega^2R}
$$

Utilizzando il periodo:

$$
\boxed{a_c=\frac{4\pi^2R}{T^2}}
$$

Utilizzando la frequenza:

$$
\boxed{a_c=4\pi^2Rf^2}
$$

dove:
- $a_c$ = accelerazione centripeta (m/s²).
- $v$ = velocità tangenziale (m/s).
- $R$ = raggio (m).
- $\omega$ = velocità angolare (rad/s).
- $T$ = periodo (s).
- $f$ = frequenza (Hz).

### Come varia l'accelerazione centripeta?

Dalla relazione:

$$
a_c=\frac{v^2}{R}
$$

si deduce che:

- Se la velocità raddoppia, a parità di raggio, l'accelerazione quadruplica.
- Se il raggio raddoppia, a parità di velocità, l'accelerazione si dimezza.
- Se la velocità rimane costante ma il raggio diminuisce, l'accelerazione aumenta.

**Attenzione:** questi confronti assumono che le altre grandezze indicate rimangano costanti.

### Esempio

Un'automobile percorre una curva di raggio $50\ \text{m}$ alla velocità costante di $20\ \text{m/s}$.

$$
a_c=\frac{v^2}{R}
$$

$$
a_c=\frac{20^2}{50}
$$

$$
\boxed{a_c=8\ \text{m/s}^2}
$$

L'accelerazione è diretta verso il centro della curva.
![[Immagine ChatGPT 19 ott 2026, 16_28_03-1.png]]
---
![[Immagine ChatGPT 19 ott 2026, 16_28_05-2.png]]
## Forza centripeta

Secondo il [[3 - Principi della dinamica|secondo principio della dinamica]], una forza risultante produce un'accelerazione:

$$
\vec F_{\text{ris}}=m\vec a
$$

Nel moto circolare uniforme, la risultante delle forze è diretta verso il centro e prende il nome di **forza centripeta**.

Il suo modulo è:

$$
\boxed{F_c=ma_c}
$$

Sostituendo l'accelerazione centripeta:

$$
\boxed{F_c=\frac{mv^2}{R}}
$$

Oppure:

$$
\boxed{F_c=m\omega^2R}
$$

dove:
- $F_c$ = forza centripeta (N).
- $m$ = massa (kg).
- $v$ = velocità tangenziale (m/s).
- $R$ = raggio (m).

### Da dove proviene la forza centripeta?

La forza centripeta **non è una nuova forza fondamentale**.

È il nome dato alla risultante delle componenti delle forze dirette verso il centro della traiettoria.

A seconda del problema, può essere prodotta da:

- **Attrito:** automobile che percorre una curva piana.
- **Tensione:** oggetto legato a una corda e fatto ruotare.
- **Gravità:** satellite che orbita attorno alla Terra.
- **Forza elettrica o magnetica:** particella carica che percorre una traiettoria circolare in particolari condizioni.

La cosa importante è identificare quale forza fisica fornisce l'accelerazione centripeta.

### Esempio

Un corpo di massa $2\ \text{kg}$ percorre una circonferenza di raggio $4\ \text{m}$ con velocità $6\ \text{m/s}$.

$$
F_c=\frac{mv^2}{R}
$$

$$
F_c=\frac{2\cdot6^2}{4}
$$

$$
\boxed{F_c=18\ \text{N}}
$$

---
![[Immagine ChatGPT 19 ott 2026, 16_28_07-4.png]]

![[Immagine ChatGPT 19 ott 2026, 16_28_06-3.png]]
## Lavoro della forza centripeta

La forza centripeta è sempre perpendicolare alla velocità istantanea del corpo.

Anche lo spostamento infinitesimo lungo la traiettoria è tangente alla circonferenza.

Il lavoro di una forza costante lungo uno spostamento rettilineo si calcola mediante:

$$
L=Fs\cos\alpha
$$

dove $\alpha$ è l'angolo tra forza e spostamento.

Nel caso della forza centripeta:

$$
\alpha=90^\circ
$$

Poiché:

$$
\cos90^\circ=0
$$

la forza centripeta compie lavoro nullo.

$$
\boxed{L_c=0}
$$

**Conseguenza:** la forza centripeta cambia la direzione della velocità, ma non il suo modulo e quindi non modifica l'energia cinetica.

Questa proprietà riguarda la componente centripeta della forza. In un moto circolare non uniforme, altre componenti della forza possono compiere lavoro.

---

## Forza centrifuga e inerzia

Quando un'automobile percorre una curva, i passeggeri hanno la sensazione di essere spinti verso l'esterno.

La causa è l'**inerzia**.

Secondo il primo principio della dinamica, un corpo tende a mantenere il proprio stato di moto rettilineo uniforme se non interviene una forza risultante.

Durante una curva:
- L'automobile cambia continuamente direzione.
- Il corpo del passeggero tende a mantenere la direzione del moto precedente.
- Il sedile o la portiera esercita la forza necessaria a far curvare anche il passeggero.

### Forza centrifuga

La **forza centrifuga** è una forza apparente che compare quando si descrive il moto da un sistema di riferimento rotante, quindi non inerziale.

Nel sistema di riferimento inerziale esterno, non è necessario introdurre una forza reale diretta verso l'esterno.

**Da ricordare per l'esame:**

- Forza centripeta: risultante radiale reale diretta verso il centro.
- Forza centrifuga: forza apparente diretta verso l'esterno nel sistema rotante.
- La sensazione di essere spinti verso l'esterno durante una curva è legata all'inerzia.

---

## Moto circolare non uniforme

Nel moto circolare non uniforme cambia anche il modulo della velocità.

L'accelerazione può essere scomposta in due componenti:

### Accelerazione centripeta

Modifica la direzione della velocità.

$$
\boxed{a_c=\frac{v^2}{R}}
$$

È diretta verso il centro della traiettoria.

### Accelerazione tangenziale

Modifica il modulo della velocità.

La sua componente scalare media è:

$$
\boxed{a_{t,m}=\frac{\Delta v}{\Delta t}}
$$

È tangente alla traiettoria e può essere concorde o discorde rispetto al verso del moto.

### Accelerazione totale

Le due componenti sono perpendicolari.

Il modulo dell'accelerazione totale è:

$$
\boxed{a=\sqrt{a_c^2+a_t^2}}
$$

Nel moto circolare uniforme:

$$
a_t=0
$$

quindi l'accelerazione totale coincide con quella centripeta.

---

## Satelliti e orbite circolari

Un satellite che percorre un'orbita circolare attorno alla Terra compie un moto circolare.

La forza gravitazionale fornisce la forza centripeta necessaria a mantenerlo in orbita.

$$
F_g=F_c
$$

Per un satellite di massa $m$ che orbita attorno alla Terra:

$$
\frac{GM_Tm}{R^2}=\frac{mv^2}{R}
$$

Da questa relazione si ricava:

$$
\boxed{v=\sqrt{\frac{GM_T}{R}}}
$$

dove:
- $G$ = costante gravitazionale.
- $M_T$ = massa terrestre.
- $R$ = distanza dal centro della Terra al satellite.

La velocità orbitale dipende quindi dalla distanza dal centro della Terra, non dalla massa del satellite.

### Quando è nota l'accelerazione centripeta

Se il problema fornisce direttamente $a_c$ e $R$, non occorre utilizzare la legge di gravitazione universale.

Dalla formula:

$$
a_c=\frac{v^2}{R}
$$

si ricava:

$$
\boxed{v=\sqrt{a_cR}}
$$

Successivamente è possibile calcolare il periodo:

$$
\boxed{T=\frac{2\pi R}{v}}
$$

Queste due formule sono sufficienti per risolvere uno degli esercizi del compito del 29 gennaio 2024.

---

## Rotazione terrestre

La Terra ruota attorno al proprio asse con un periodo di circa 24 ore.

Un oggetto situato sull'equatore partecipa alla rotazione terrestre e percorre approssimativamente una circonferenza di raggio pari al raggio terrestre.

La sua accelerazione centripeta vale:

$$
\boxed{a_c=\frac{4\pi^2R_T}{T^2}}
$$

dove:
- $R_T$ = raggio terrestre.
- $T$ = periodo di rotazione.

Per calcolare l'accelerazione occorre utilizzare:
- Raggio in metri.
- Periodo in secondi.

**Nota:** questa accelerazione è dovuta alla rotazione terrestre e non coincide con l'accelerazione gravitazionale $g$.

Per un oggetto a una latitudine diversa dall'equatore, il raggio della traiettoria attorno all'asse terrestre è minore di $R_T$.

---

## Conservazione del momento angolare — Richiamo

Il **momento angolare** è una grandezza fisica associata al movimento rotatorio.

Per un corpo puntiforme che ruota a distanza $R$ da un asse:

$$
\boxed{L=mR^2\omega}
$$

Più in generale, per un corpo rigido che ruota attorno a un asse fisso:

$$
\boxed{L=I\omega}
$$

dove $I$ è il momento d'inerzia rispetto all'asse.

Se il momento delle forze esterne rispetto all'asse è nullo, il momento angolare si conserva.

$$
\boxed{I_i\omega_i=I_f\omega_f}
$$

Di conseguenza:

- Se il momento d'inerzia diminuisce, la velocità angolare aumenta.
- Se il momento d'inerzia aumenta, la velocità angolare diminuisce.

**Esempio:** una persona su una piattaforma rotante aumenta la velocità di rotazione quando si avvicina all'asse, supponendo trascurabili i momenti delle forze esterne.

Questo principio appartiene alla dinamica rotazionale, ma viene richiamato qui perché compare tra le domande teoriche degli esami.

---

## Formule principali

| Grandezza | Formula |
|---|---|
| Frequenza | $f=1/T$ |
| Periodo | $T=1/f$ |
| Velocità angolare | $\omega=2\pi/T$ |
| Velocità angolare dalla frequenza | $\omega=2\pi f$ |
| Velocità tangenziale | $v=\omega R$ |
| Velocità tangenziale dal periodo | $v=2\pi R/T$ |
| Accelerazione centripeta | $a_c=v^2/R$ |
| Accelerazione centripeta angolare | $a_c=\omega^2R$ |
| Accelerazione centripeta dal periodo | $a_c=4\pi^2R/T^2$ |
| Forza centripeta | $F_c=mv^2/R$ |
| Periodo dalla velocità | $T=2\pi R/v$ |
| Accelerazione totale | $a=\sqrt{a_c^2+a_t^2}$ |

---

## Come riconoscere gli esercizi

| Situazione | Formula principale |
|---|---|
| Corpo che percorre una curva | $a_c=v^2/R$ |
| È nota l'accelerazione e si cerca la velocità | $v=\sqrt{a_cR}$ |
| È nota la frequenza di rotazione | $\omega=2\pi f$ |
| È noto il periodo di rotazione | $v=2\pi R/T$ |
| Si chiede la forza per mantenere la traiettoria | $F_c=mv^2/R$ |
| Si chiede il periodo di un satellite | $T=2\pi R/v$ |
| Si chiede l'accelerazione dovuta alla rotazione terrestre | $a_c=4\pi^2R_T/T^2$ |
| Si chiede il lavoro della forza centripeta | $L_c=0$ |

---

## Esercizi usciti negli esami

### Esempio compito 2 — Domanda 11

**Testo**

Un camioncino percorre una curva di raggio $150\ \text{m}$ alla velocità massima di $32\ \text{m/s}$.

Con quale velocità massima deve percorrere una curva di raggio $75\ \text{m}$ per mantenere la stessa accelerazione centripeta?

**Soluzione**

L'accelerazione centripeta iniziale è:

$$
a_c=\frac{v^2}{R}
$$

$$
a_c=\frac{32^2}{150}
$$

$$
a_c\approx6{,}83\ \text{m/s}^2
$$

Nella seconda curva l'accelerazione deve rimanere uguale.

$$
v'=\sqrt{a_cR'}
$$

$$
v'=\sqrt{6{,}83\cdot75}
$$

$$
\boxed{v'\approx22{,}6\ \text{m/s}}
$$

**Principio da ricordare:** per mantenere la stessa accelerazione centripeta in una curva più stretta, bisogna diminuire la velocità.

### Esame 10 settembre 2026 — Domanda 1

**Testo**

Calcolare il modulo dell'accelerazione centripeta dovuta alla rotazione della Terra per un oggetto situato sull'equatore.

Dati:

$$
R_T=6370\ \text{km}
$$

**Soluzione**

Si utilizza:

$$
a_c=\frac{4\pi^2R_T}{T^2}
$$

Convertiamo il raggio:

$$
R_T=6{,}37\cdot10^6\ \text{m}
$$

Assumiamo un periodo di rotazione di 24 ore:

$$
T=24\cdot3600=86400\ \text{s}
$$

Sostituendo:

$$
a_c=\frac{4\pi^2\cdot6{,}37\cdot10^6}{86400^2}
$$

$$
\boxed{a_c\approx0{,}034\ \text{m/s}^2}
$$

**Principio da ricordare:** anche un oggetto fermo rispetto alla superficie terrestre possiede un'accelerazione centripeta dovuta alla rotazione del pianeta.

### Esame 29 gennaio 2024 — Domanda 13

**Testo**

Un satellite artificiale in orbita attorno alla Terra è soggetto a un'accelerazione centripeta di $9{,}8\ \text{m/s}^2$.

Calcolare:

1. La velocità tangenziale.
2. Il periodo dell'orbita.

Approssimare il raggio dell'orbita a $6371\ \text{km}$.

**Soluzione**

Dati:

$$
a_c=9{,}8\ \text{m/s}^2
$$

$$
R=6{,}371\cdot10^6\ \text{m}
$$

**1. Velocità tangenziale**

$$
v=\sqrt{a_cR}
$$

$$
v=\sqrt{9{,}8\cdot6{,}371\cdot10^6}
$$

$$
\boxed{v\approx7902\ \text{m/s}}
$$

**2. Periodo orbitale**

$$
T=\frac{2\pi R}{v}
$$

$$
T=\frac{2\pi\cdot6{,}371\cdot10^6}{7902}
$$

$$
\boxed{T\approx5067\ \text{s}}
$$

Convertendo in minuti:

$$
\boxed{T\approx84{,}4\ \text{min}}
$$

**Principio da ricordare:** conoscendo accelerazione centripeta e raggio, si ricava la velocità e successivamente il periodo.

*Il compito del 2024 non contiene le soluzioni ufficiali: i risultati sopra sono stati calcolati a partire dai dati del testo.*

### Esempio compito 1 — Domanda 13

**Testo**

La forza centripeta può compiere lavoro su un corpo?

**Risposta corretta:** no, mai.

**Spiegazione**

La forza centripeta è sempre perpendicolare alla velocità istantanea.

Non possiede quindi una componente nella direzione dello spostamento istantaneo.

$$
\boxed{L_c=0}
$$

### Esempio compito 1 — Domanda 4

**Testo**

Durante una curva i passeggeri di un'auto vengono apparentemente spinti verso l'esterno. Perché?

**Risposta corretta:** a causa dell'inerzia, che tende a far mantenere loro la velocità precedente alla curva.

**Spiegazione**

Il corpo tende a proseguire nella direzione iniziale, mentre l'automobile cambia direzione.

Per far curvare il passeggero è necessaria una forza diretta verso il centro della curva.

### Esame 10 settembre 2026 — Domanda 13

**Testo**

Una persona si trova sul bordo di una piattaforma rotante. Cosa accade se si avvicina al centro?

**Risposta corretta:** la piattaforma ruota più velocemente.

**Spiegazione**

Avvicinandosi all'asse si riduce il momento d'inerzia del sistema.

Se il momento angolare si conserva, la velocità angolare deve aumentare.

---

## Domande teoriche da conoscere

**Un corpo in moto circolare uniforme possiede accelerazione?**

Sì. Anche se il modulo della velocità è costante, la sua direzione cambia continuamente.

**In quale direzione agisce l'accelerazione centripeta?**

Verso il centro della circonferenza.

**In quale direzione è orientata la velocità tangenziale?**

Lungo la tangente alla traiettoria, nel verso del movimento.

**Qual è la differenza tra periodo e frequenza?**

Il periodo è il tempo necessario per un giro, mentre la frequenza è il numero di giri nell'unità di tempo.

**La forza centripeta è una forza fondamentale?**

No. È la risultante delle componenti radiali delle forze che mantengono il corpo sulla traiettoria circolare.

**La forza centripeta può compiere lavoro?**

No, perché è perpendicolare allo spostamento istantaneo.

**Perché un'automobile deve rallentare nelle curve più strette?**

A parità di velocità, diminuendo il raggio aumenta l'accelerazione centripeta richiesta, e quindi aumenta anche la forza centripeta necessaria.

**Perché un satellite rimane in orbita?**

Perché la forza gravitazionale fornisce l'accelerazione centripeta necessaria a modificare continuamente la direzione della sua velocità.

**Cosa accade alla velocità angolare di una persona che si avvicina all'asse di una piattaforma rotante?**

Aumenta, se il momento angolare del sistema si conserva.

---

## Errori frequenti

- Confondere velocità tangenziale e velocità angolare.
- Pensare che l'accelerazione sia nulla quando il modulo della velocità è costante.
- Confondere la direzione della velocità con quella dell'accelerazione.
- Considerare la forza centrifuga una forza reale nel sistema di riferimento inerziale.
- Dimenticare che la forza centripeta è diretta verso il centro.
- Utilizzare il diametro al posto del raggio.
- Non convertire i chilometri in metri.
- Non convertire le ore in secondi.
- Confondere frequenza e periodo.
- Dimenticare il quadrato della velocità nella formula dell'accelerazione centripeta.
- Utilizzare direttamente $g=9{,}81\ \text{m/s}^2$ per un satellite senza verificare le condizioni del problema.
- Pensare che la forza centripeta aumenti l'energia cinetica.

---

## Checklist di preparazione

- [ ] Conosco la differenza tra periodo e frequenza.
- [ ] So calcolare la velocità angolare.
- [ ] So calcolare la velocità tangenziale.
- [ ] So spiegare perché il moto circolare uniforme è accelerato.
- [ ] So calcolare l'accelerazione centripeta.
- [ ] So individuare la direzione della forza centripeta.
- [ ] So calcolare la forza centripeta.
- [ ] So spiegare perché la forza centripeta non compie lavoro.
- [ ] So distinguere forza centripeta e forza centrifuga.
- [ ] So calcolare il periodo di un'orbita circolare.
- [ ] So risolvere gli esercizi sulle curve.
- [ ] So calcolare l'accelerazione dovuta alla rotazione terrestre.
- [ ] So spiegare qualitativamente la conservazione del momento angolare.
- [ ] So risolvere autonomamente le domande d'esame collegate.

---

## Collegamenti

- [[1 - Cinematica]]
- [[3 - Principi della dinamica]]
- [[Equilibrio delle forze]]
- [[Lavoro energia e potenza]]
- [[Gravitazione]]
- [[Impulso e quantità di moto]]
