
# Piano inclinato e attrito

## Introduzione

Un **piano inclinato** è una superficie che forma un angolo $\theta$ rispetto all'orizzontale.

Un corpo appoggiato sul piano è soggetto alla forza peso, che può essere scomposta in due componenti:

- Una componente **parallela al piano**, che tende a far scivolare il corpo verso il basso.
- Una componente **perpendicolare al piano**, che viene contrastata dalla reazione normale della superficie.

Se la superficie è scabra, può essere presente anche una **forza di attrito**, che si oppone allo scorrimento relativo tra il corpo e il piano, oppure alla sua tendenza.

Per risolvere gli esercizi si utilizzano principalmente:

- [[Principi della dinamica|Secondo principio di Newton]].
- [[Equilibrio delle forze|Condizioni di equilibrio]].
- [[Cinematica|Equazioni del moto uniformemente accelerato]].
- [[Lavoro energia e potenza|Teorema dell'energia cinetica]].

---

## Forze agenti su un piano inclinato

Consideriamo un blocco di massa $m$ appoggiato su un piano inclinato di un angolo $\theta$ rispetto all'orizzontale.

Le principali forze agenti sono:

1. **Forza peso** $P=mg$, verticale verso il basso.
2. **Reazione normale** $N$, perpendicolare alla superficie.
3. **Forza di attrito** $f$, se presente.

In eventuali esercizi possono essere applicate ulteriori forze esterne.

### Scelta degli assi

Per semplificare il problema conviene utilizzare:

- Asse $x$: parallelo al piano inclinato.
- Asse $y$: perpendicolare al piano inclinato.

Questa scelta permette di scomporre la forza peso lungo le due direzioni più utili.

---

## Scomposizione della forza peso

La forza peso è:

$$
\boxed{P=mg}
$$

Su un piano inclinato di angolo $\theta$, le sue componenti hanno modulo:

### Componente parallela al piano

$$
\boxed{P_{\parallel}=mg\sin\theta}
$$

Questa componente è diretta verso il basso lungo il piano.

È responsabile della tendenza del corpo a scivolare.

### Componente perpendicolare al piano

$$
\boxed{P_{\perp}=mg\cos\theta}
$$

Questa componente è diretta verso la superficie.

È contrastata dalla reazione normale.

### Reazione normale

Se il corpo rimane a contatto con il piano e non agiscono altre forze perpendicolari alla superficie:

$$
\sum F_y=0
$$

$$
N-mg\cos\theta=0
$$

Quindi:

$$
\boxed{N=mg\cos\theta}
$$

### Formule fondamentali

| Grandezza | Formula |
|---|---|
| Forza peso | $P=mg$ |
| Componente parallela | $P_{\parallel}=mg\sin\theta$ |
| Componente perpendicolare | $P_{\perp}=mg\cos\theta$ |
| Reazione normale | $N=mg\cos\theta$ |

**Attenzione:** queste formule considerano un piano inclinato di angolo $\theta$ rispetto all'orizzontale e nessun'altra forza che modifichi la reazione normale.

---

## Piano inclinato senza attrito

Consideriamo un blocco che può scivolare lungo un piano inclinato perfettamente liscio.

L'unica componente della forza peso che produce accelerazione lungo il piano è:

$$
F_{\parallel}=mg\sin\theta
$$

Applicando il secondo principio di Newton:

$$
F_{\parallel}=ma
$$

$$
mg\sin\theta=ma
$$

Semplificando la massa:

$$
\boxed{a=g\sin\theta}
$$

Questa è l'accelerazione del blocco diretta verso il basso lungo il piano.

### Osservazioni

- L'accelerazione non dipende dalla massa del corpo.
- Aumentando l'inclinazione del piano, aumenta l'accelerazione.
- Se $\theta=0^\circ$, l'accelerazione lungo il piano è nulla.
- Se $\theta=90^\circ$, si ottiene $a=g$, come nella caduta libera.

### Esempio

Un blocco scivola lungo un piano liscio inclinato di $30^\circ$.

Calcolare l'accelerazione.

$$
a=g\sin30^\circ
$$

$$
a=9{,}81\cdot0{,}5
$$

$$
\boxed{a=4{,}905\ \text{m/s}^2}
$$

L'accelerazione è diretta verso il basso lungo il piano.

---

## Forza di attrito

L'**attrito** è una forza che si oppone al moto relativo tra due superfici a contatto oppure alla tendenza allo scorrimento.

Si distinguono due principali tipologie:

- Attrito statico.
- Attrito dinamico.

### Attrito statico

L'**attrito statico** agisce quando non esiste scorrimento relativo tra le superfici.

La forza di attrito statico può assumere diversi valori, fino a un massimo:

$$
\boxed{f_{s,\max}=\mu_sN}
$$

In generale:

$$
\boxed{0\le f_s\le\mu_sN}
$$

dove:

- $f_s$ = modulo dell'attrito statico.
- $\mu_s$ = coefficiente di attrito statico.
- $N$ = reazione normale.

Il coefficiente di attrito statico è adimensionale.

**Importante:** l'attrito statico non è sempre uguale a $\mu_sN$. Questa relazione rappresenta soltanto il massimo valore possibile.

### Attrito dinamico

L'**attrito dinamico** agisce quando due superfici scorrono l'una rispetto all'altra.

Nel modello utilizzato negli esercizi:

$$
\boxed{f_d=\mu_dN}
$$

dove:

- $f_d$ = modulo della forza di attrito dinamico.
- $\mu_d$ = coefficiente di attrito dinamico.
- $N$ = reazione normale.

Sul piano inclinato:

$$
N=mg\cos\theta
$$

quindi:

$$
\boxed{f_d=\mu_dmg\cos\theta}
$$

### Direzione della forza di attrito

La forza di attrito dinamico è diretta in verso opposto alla velocità relativa tra le superfici.

Per esempio:

- Se il corpo scivola verso il basso, l'attrito è diretto verso l'alto.
- Se il corpo scivola verso l'alto, l'attrito è diretto verso il basso.

Questa distinzione è fondamentale per determinare correttamente l'accelerazione.

---

## Equilibrio su un piano inclinato con attrito statico

Consideriamo un blocco inizialmente fermo su un piano inclinato scabro.

La componente della forza peso che tende a farlo scivolare è:

$$
P_{\parallel}=mg\sin\theta
$$

L'attrito statico si oppone a questa tendenza.

Per mantenere il blocco in equilibrio:

$$
f_s=mg\sin\theta
$$

Tuttavia, l'attrito statico non può superare il proprio valore massimo:

$$
f_{s,\max}=\mu_smg\cos\theta
$$

La condizione affinché il blocco possa rimanere fermo è quindi:

$$
mg\sin\theta\le\mu_smg\cos\theta
$$

Semplificando:

$$
\boxed{\tan\theta\le\mu_s}
$$

### Significato fisico

- Se $\tan\theta<\mu_s$, l'attrito statico è sufficiente a mantenere il corpo fermo.
- Se $\tan\theta=\mu_s$, il corpo è al limite dello scivolamento.
- Se $\tan\theta>\mu_s$, l'attrito statico non è sufficiente a mantenere l'equilibrio.

### Angolo limite

L'angolo massimo per cui il corpo può rimanere fermo è:

$$
\boxed{\theta_{\max}=\arctan\mu_s}
$$

Questa relazione vale quando le uniche forze agenti sono il peso, la reazione normale e l'attrito statico.

### Esempio

Un blocco si trova su un piano inclinato di $20^\circ$.

Il coefficiente di attrito statico è:

$$
\mu_s=0{,}5
$$

Verificare se il corpo può rimanere fermo.

Calcoliamo:

$$
\tan20^\circ\approx0{,}364
$$

Confrontiamo:

$$
0{,}364<0{,}5
$$

Pertanto:

$$
\boxed{\text{Il corpo rimane fermo}}
$$

---

## Corpo che scivola verso il basso con attrito

Consideriamo un blocco che scivola verso il basso su un piano inclinato scabro.

Le forze parallele al piano sono:

- Componente del peso $mg\sin\theta$, verso il basso.
- Attrito dinamico $\mu_dmg\cos\theta$, verso l'alto.

Scegliamo come verso positivo quello diretto verso il basso lungo il piano.

Applicando il secondo principio:

$$
mg\sin\theta-\mu_dmg\cos\theta=ma
$$

Semplificando la massa:

$$
\boxed{a=g(\sin\theta-\mu_d\cos\theta)}
$$

### Significato fisico

L'attrito contrasta il movimento del corpo.

Di conseguenza, quando il corpo sta scivolando verso il basso, l'accelerazione è minore rispetto al caso senza attrito.

A seconda dei valori di $\theta$ e $\mu_d$, l'accelerazione può risultare:

- Positiva: il corpo aumenta la velocità verso il basso.
- Nulla: il corpo scende a velocità costante.
- Negativa: il corpo sta scendendo ma rallenta.

**Attenzione:** se l'accelerazione è negativa, il corpo può fermarsi; da quel momento occorre verificare le condizioni di attrito statico.

### Esempio

Un blocco scivola verso il basso lungo un piano inclinato di $30^\circ$.

Il coefficiente di attrito dinamico è:

$$
\mu_d=0{,}2
$$

Calcolare l'accelerazione.

$$
a=g(\sin30^\circ-\mu_d\cos30^\circ)
$$

$$
a=9{,}81(0{,}5-0{,}2\cdot0{,}866)
$$

$$
a=9{,}81(0{,}3268)
$$

$$
\boxed{a\approx3{,}21\ \text{m/s}^2}
$$

Il corpo accelera verso il basso lungo il piano.

---

## Corpo che risale un piano inclinato

Consideriamo un blocco lanciato verso l'alto lungo un piano inclinato.

Durante la risalita:

- La componente del peso è diretta verso il basso.
- L'attrito dinamico è diretto verso il basso, perché si oppone alla risalita.

Le due forze agiscono quindi nello stesso verso.

Scegliamo l'asse positivo verso l'alto lungo il piano.

### Senza attrito

La risultante delle forze lungo il piano è:

$$
-ma_g=-mg\sin\theta
$$

Indicando direttamente con $a$ l'accelerazione con segno:

$$
ma=-mg\sin\theta
$$

Quindi:

$$
\boxed{a=-g\sin\theta}
$$

Il segno negativo indica che l'accelerazione è opposta alla velocità iniziale diretta verso l'alto.

### Con attrito dinamico

Durante la risalita entrambe le forze sono dirette verso il basso.

$$
ma=-mg\sin\theta-\mu_dmg\cos\theta
$$

Semplificando:

$$
\boxed{a=-g(\sin\theta+\mu_d\cos\theta)}
$$

Il modulo della decelerazione è:

$$
\boxed{|a|=g(\sin\theta+\mu_d\cos\theta)}
$$

### Osservazione

Durante la risalita, gravità e attrito collaborano a rallentare il corpo.

Durante la discesa, invece, l'attrito contrasta la componente della forza peso parallela al piano.

Questa differenza determina il segno dei termini nelle formule.

---

## Distanza di arresto sul piano inclinato

Se un corpo viene lanciato verso l'alto lungo un piano inclinato, rallenta progressivamente fino a fermarsi.

Per calcolare la distanza percorsa si utilizza una formula del moto uniformemente accelerato:

$$
\boxed{v^2=v_0^2+2a\Delta x}
$$

Nel punto di arresto:

$$
v=0
$$

Pertanto:

$$
0=v_0^2+2a\Delta x
$$

Ricavando la distanza:

$$
\Delta x=-\frac{v_0^2}{2a}
$$

Poiché durante la risalita l'accelerazione è negativa, la distanza risulta positiva.

### Distanza di arresto senza attrito

L'accelerazione vale:

$$
a=-g\sin\theta
$$

Quindi:

$$
\boxed{d=\frac{v_0^2}{2g\sin\theta}}
$$

### Distanza di arresto con attrito

L'accelerazione vale:

$$
a=-g(\sin\theta+\mu_d\cos\theta)
$$

Pertanto:

$$
\boxed{d=\frac{v_0^2}{2g(\sin\theta+\mu_d\cos\theta)}}
$$

Queste formule valgono per un corpo che risale il piano, con forze costanti e condizioni tali da provocarne l'arresto.

### Interpretazione

- Aumentando la velocità iniziale, aumenta la distanza percorsa.
- Aumentando l'inclinazione, aumenta la decelerazione dovuta alla gravità.
- Aumentando l'attrito dinamico, diminuisce la distanza di arresto.
- A parità degli altri dati, la massa non influenza la distanza di arresto nel modello considerato.

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 10

### Testo

Un blocco di massa:

$$
m=1{,}50\ \text{kg}
$$

viene lanciato verso l'alto lungo un piano inclinato di:

$$
\theta=53^\circ
$$

con velocità iniziale:

$$
v_0=2{,}0\ \text{m/s}
$$

Calcolare la distanza percorsa prima di fermarsi:

1. In assenza di attrito.
2. Con coefficiente di attrito dinamico $\mu_d=0{,}40$.

### Prima parte — Senza attrito

Durante la risalita il blocco viene rallentato dalla componente parallela della forza peso.

L'accelerazione è:

$$
a=-g\sin\theta
$$

La distanza di arresto è:

$$
d=\frac{v_0^2}{2g\sin\theta}
$$

Sostituendo:

$$
d=\frac{2^2}{2\cdot9{,}81\cdot\sin53^\circ}
$$

$$
d=\frac{4}{2\cdot9{,}81\cdot0{,}7986}
$$

$$
d\approx0{,}255\ \text{m}
$$

Convertendo in centimetri:

$$
\boxed{d\approx25{,}5\ \text{cm}}
$$

### Seconda parte — Con attrito

Durante la risalita agiscono verso il basso sia la componente del peso sia l'attrito dinamico.

Il modulo della decelerazione è:

$$
|a|=g(\sin\theta+\mu_d\cos\theta)
$$

Quindi la distanza di arresto è:

$$
d=\frac{v_0^2}{2g(\sin\theta+\mu_d\cos\theta)}
$$

Sostituendo:

$$
d=\frac{2^2}{2\cdot9{,}81(\sin53^\circ+0{,}40\cos53^\circ)}
$$

Utilizzando:

$$
\sin53^\circ\approx0{,}7986
$$

$$
\cos53^\circ\approx0{,}6018
$$

Otteniamo:

$$
d=\frac{4}{19{,}62(0{,}7986+0{,}2407)}
$$

$$
d\approx0{,}196\ \text{m}
$$

Convertendo in centimetri:

$$
\boxed{d\approx19{,}6\ \text{cm}}
$$

### Risultati

| Condizione | Distanza |
|---|---:|
| Senza attrito | 25,5 cm |
| Con attrito | 19,6 cm |

Le risposte coincidono con quelle riportate nella revisione Moodle.

**Principio da ricordare:** quando il blocco risale il piano, l'attrito dinamico è diretto nello stesso verso della componente parallela del peso. Di conseguenza, il blocco si arresta in una distanza minore.

---

## Lavoro delle forze sul piano inclinato

Il **lavoro** di una forza costante è:

$$
\boxed{L=Fs\cos\alpha}
$$

dove:
- $F$ = modulo della forza.
- $s$ = modulo dello spostamento.
- $\alpha$ = angolo tra forza e spostamento.

Il lavoro si misura in joule (J).

Sul piano inclinato possiamo distinguere il lavoro delle diverse forze.

### Lavoro della forza peso

La componente della forza peso parallela al piano ha modulo:

$$
P_{\parallel}=mg\sin\theta
$$

Se il corpo scende lungo il piano per una distanza $s$, il lavoro della forza peso è positivo:

$$
\boxed{L_P=mg\,s\sin\theta}
$$

Se invece il corpo risale il piano, il lavoro della forza peso è negativo:

$$
\boxed{L_P=-mg\,s\sin\theta}
$$

Questo perché la forza peso si oppone allo spostamento durante la risalita.

### Lavoro della reazione normale

La reazione normale è sempre perpendicolare allo spostamento lungo il piano.

Quindi:

$$
\alpha=90^\circ
$$

Poiché:

$$
\cos90^\circ=0
$$

il lavoro della reazione normale è nullo:

$$
\boxed{L_N=0}
$$

Anche la componente della forza peso perpendicolare al piano compie lavoro nullo durante uno spostamento lungo la superficie.

### Lavoro dell'attrito dinamico

L'attrito dinamico è opposto allo scorrimento.

Pertanto il suo lavoro è negativo:

$$
L_f=-f_ds
$$

Sostituendo:

$$
\boxed{L_f=-\mu_dmg\cos\theta\cdot s}
$$

L'attrito sottrae energia meccanica al corpo, trasformandola prevalentemente in energia interna delle superfici.

---

## Teorema dell'energia cinetica

Il **teorema dell'energia cinetica** stabilisce che il lavoro totale delle forze agenti su un corpo è uguale alla variazione della sua energia cinetica.

$$
\boxed{L_{\text{tot}}=\Delta K}
$$

L'energia cinetica è:

$$
\boxed{K=\frac12mv^2}
$$

Quindi:

$$
\boxed{L_{\text{tot}}=\frac12mv_f^2-\frac12mv_i^2}
$$

Questa relazione permette di risolvere i problemi sui piani inclinati anche senza calcolare esplicitamente il tempo.

### Corpo che risale un piano con attrito

Durante la risalita:

$$
L_P=-mgd\sin\theta
$$

$$
L_f=-\mu_dmg\cos\theta\cdot d
$$

Il lavoro totale è:

$$
L_{\text{tot}}=-mgd(\sin\theta+\mu_d\cos\theta)
$$

Nel punto di arresto:

$$
v_f=0
$$

Quindi:

$$
-mgd(\sin\theta+\mu_d\cos\theta)=-\frac12mv_0^2
$$

Semplificando la massa e ricavando $d$:

$$
\boxed{d=\frac{v_0^2}{2g(\sin\theta+\mu_d\cos\theta)}}
$$

Si ottiene lo stesso risultato del metodo basato sull'accelerazione.

**Per l'esame:** entrambi i metodi sono validi. Conviene scegliere quello che richiede meno passaggi.

Per approfondire: [[Lavoro energia e potenza]].

---

## Moto a velocità costante su un piano inclinato

Un corpo può scendere lungo un piano inclinato mantenendo una velocità costante.

In questo caso:

$$
a=0
$$

Per il secondo principio:

$$
\sum F_{\parallel}=0
$$

Se il corpo scende con attrito dinamico:

$$
mg\sin\theta-f_d=0
$$

Quindi:

$$
\boxed{f_d=mg\sin\theta}
$$

Se l'unica forza resistente lungo il piano è l'attrito dinamico:

$$
\mu_dmg\cos\theta=mg\sin\theta
$$

Da cui:

$$
\boxed{\mu_d=\tan\theta}
$$

### Significato fisico

La componente parallela della forza peso viene compensata completamente dall'attrito.

La velocità rimane quindi costante.

**Attenzione:** risultante nulla non significa che non agiscano forze sul corpo. Significa che le forze si compensano.

---

## Esercizio ufficiale — Esempio compito 1, domanda 12

### Testo

Un blocco di ghiaccio di massa:

$$
m=10\ \text{kg}
$$

scende a velocità costante lungo un piano inclinato scabro.

Il piano ha:

$$
s=2\ \text{m}
$$

$$
\theta=30^\circ
$$

Sapendo che il calore latente di fusione del ghiaccio è:

$$
\lambda=3{,}35\cdot10^5\ \text{J/kg}
$$

calcolare quanta massa di ghiaccio si scioglie a causa dell'attrito.

### Soluzione

**1. Individuare la condizione di moto**

Il blocco scende a velocità costante.

Quindi:

$$
a=0
$$

La risultante delle forze parallele al piano è nulla.

$$
mg\sin\theta-f_d=0
$$

Pertanto:

$$
f_d=mg\sin\theta
$$

**2. Calcolare il lavoro dissipato dall'attrito**

Il modulo del lavoro compiuto dall'attrito è:

$$
|L_f|=f_ds
$$

Sostituendo:

$$
|L_f|=mg\sin\theta\cdot s
$$

$$
|L_f|=10\cdot9{,}81\cdot\sin30^\circ\cdot2
$$

$$
|L_f|=10\cdot9{,}81\cdot0{,}5\cdot2
$$

$$
\boxed{|L_f|=98{,}1\ \text{J}}
$$

**3. Calcolare la massa di ghiaccio fusa**

Assumendo, come nel modello dell'esercizio, che tutta l'energia dissipata dall'attrito contribuisca a fondere il ghiaccio:

$$
Q=m_f\lambda
$$

La massa fusa è:

$$
m_f=\frac{Q}{\lambda}
$$

$$
m_f=\frac{98{,}1}{3{,}35\cdot10^5}
$$

$$
m_f\approx2{,}93\cdot10^{-4}\ \text{kg}
$$

Convertendo in grammi:

$$
\boxed{m_f\approx0{,}293\ \text{g}}
$$

### Risposta corretta

$$
\boxed{m_f\approx0{,}29\ \text{g}}
$$

### Principi da ricordare

Questo esercizio combina tre concetti:

1. Velocità costante significa accelerazione nulla.
2. Il lavoro dell'attrito rappresenta energia meccanica dissipata.
3. Il calore necessario per fondere una massa $m_f$ è $Q=m_f\lambda$.

La parte relativa al calore latente sarà approfondita in [[Calore latente]].

---

## Esercizio teorico — Esame 29 gennaio 2024, domanda 11

### Testo

Un blocco scivola verso il basso su un piano inclinato scabro.

Quale forza compie lavoro nullo?

Opzioni:

1. La forza peso.
2. La forza di attrito.
3. La componente normale al piano della forza peso.
4. Nessuna delle forze agenti compie lavoro nullo.

### Risposta corretta

**La componente normale al piano della forza peso.**

### Spiegazione

Il lavoro di una forza dipende dalla sua componente parallela allo spostamento.

$$
L=Fs\cos\alpha
$$

La componente della forza peso perpendicolare al piano forma un angolo di 90° con lo spostamento.

Pertanto:

$$
\boxed{L=0}
$$

Anche la reazione normale esercitata dal piano compie lavoro nullo, perché è perpendicolare allo spostamento.

La forza peso complessiva, invece, compie lavoro positivo durante la discesa; l'attrito dinamico compie lavoro negativo.

---

## Formule principali

| Situazione | Formula |
|---|---|
| Componente parallela del peso | $P_{\parallel}=mg\sin\theta$ |
| Componente normale del peso | $P_{\perp}=mg\cos\theta$ |
| Reazione normale | $N=mg\cos\theta$ |
| Attrito statico massimo | $f_{s,\max}=\mu_sN$ |
| Attrito dinamico | $f_d=\mu_dN$ |
| Equilibrio statico sul piano | $\tan\theta\le\mu_s$ |
| Accelerazione senza attrito | $a=g\sin\theta$ verso il basso |
| Accelerazione durante la discesa con attrito | $a=g(\sin\theta-\mu_d\cos\theta)$ |
| Accelerazione durante la risalita con attrito | $a=-g(\sin\theta+\mu_d\cos\theta)$ |
| Distanza di arresto senza attrito | $d=v_0^2/(2g\sin\theta)$ |
| Distanza di arresto con attrito | $d=v_0^2/[2g(\sin\theta+\mu_d\cos\theta)]$ |
| Lavoro del peso durante la discesa | $L_P=mg\,s\sin\theta$ |
| Lavoro della normale | $L_N=0$ |
| Lavoro dell'attrito dinamico | $L_f=-\mu_dmg\cos\theta\cdot s$ |
| Teorema dell'energia cinetica | $L_{\text{tot}}=\Delta K$ |

Le formule con accelerazione positiva verso il basso assumono tale direzione come verso positivo; durante la risalita viene invece utilizzato l'asse positivo verso l'alto.

---

## Come riconoscere gli esercizi

| Situazione | Procedimento |
|---|---|
| Blocco che scende su piano liscio | $a=g\sin\theta$ |
| Blocco che scende con attrito | Sottrarre l'attrito dalla componente del peso |
| Blocco che risale con attrito | Peso e attrito rallentano entrambi il corpo |
| Blocco inizialmente fermo | Verificare l'attrito statico |
| Si chiede la distanza prima dell'arresto | Usare $v^2=v_0^2+2a\Delta x$ |
| Corpo che scivola a velocità costante | Imporre $\sum F_{\parallel}=0$ |
| Si chiede il lavoro dell'attrito | $L_f=-f_ds$ |
| Si chiede quale forza compie lavoro nullo | Cercare la forza perpendicolare allo spostamento |
| Si chiede la variazione di energia cinetica | Utilizzare $L_{\text{tot}}=\Delta K$ |

---

## Domande teoriche da conoscere

**Quale componente della forza peso fa scivolare il corpo lungo il piano?**

La componente parallela:

$$
P_{\parallel}=mg\sin\theta
$$

**Quale componente della forza peso viene compensata dalla reazione normale?**

La componente perpendicolare:

$$
P_{\perp}=mg\cos\theta
$$

**La reazione normale è sempre uguale alla forza peso?**

No. Sul piano inclinato, nel caso semplice senza altre forze normali:

$$
N=mg\cos\theta
$$

**L'accelerazione di un corpo su un piano liscio dipende dalla sua massa?**

No. Nel modello senza attrito:

$$
a=g\sin\theta
$$

**In quale direzione agisce l'attrito dinamico?**

In verso opposto alla velocità relativa di scorrimento tra le superfici.

**In quale direzione agisce l'attrito se il corpo risale il piano?**

Verso il basso lungo il piano.

**In quale direzione agisce l'attrito se il corpo scende lungo il piano?**

Verso l'alto lungo il piano.

**Qual è la differenza tra attrito statico e dinamico?**

L'attrito statico impedisce o contrasta l'inizio dello scorrimento; quello dinamico agisce quando le superfici scorrono relativamente.

**L'attrito statico è sempre uguale a $\mu_sN$?**

No. $\mu_sN$ rappresenta il massimo valore possibile dell'attrito statico.

**Quando un blocco può rimanere fermo su un piano inclinato?**

Quando l'attrito statico disponibile è sufficiente a compensare la componente parallela del peso.

Nel caso semplice:

$$
\tan\theta\le\mu_s
$$

**Perché un corpo che risale un piano inclinato rallenta?**

Perché la componente parallela della forza peso è opposta alla velocità e, se è presente attrito dinamico, anche quest'ultimo si oppone alla risalita.

**Se un corpo scende a velocità costante, qual è la forza risultante?**

È nulla.

**La reazione normale compie lavoro durante lo scorrimento lungo il piano?**

No. È perpendicolare allo spostamento.

**L'attrito dinamico compie lavoro positivo o negativo?**

Negativo, perché si oppone allo scorrimento.

**Perché la distanza di arresto diminuisce quando aumenta l'attrito?**

Perché aumenta il modulo della decelerazione e quindi il corpo perde la propria velocità in uno spazio minore.

---

## Errori frequenti

- Confondere la componente parallela del peso con quella perpendicolare.
- Utilizzare $mg\cos\theta$ al posto di $mg\sin\theta$ per la componente parallela.
- Dimenticare che l'angolo del piano è misurato rispetto all'orizzontale.
- Considerare la reazione normale sempre uguale a $mg$.
- Dimenticare di cambiare il verso dell'attrito quando cambia il verso dello scorrimento.
- Sommare o sottrarre le forze senza aver scelto il verso positivo.
- Utilizzare il coefficiente di attrito statico nei problemi di scorrimento dinamico.
- Considerare l'attrito statico sempre uguale al suo valore massimo.
- Applicare la formula della discesa a un corpo che sta risalendo.
- Dimenticare che al punto di arresto la velocità è nulla.
- Confondere distanza percorsa e altezza verticale.
- Considerare nullo il lavoro della forza peso lungo il piano.
- Dimenticare che la reazione normale compie lavoro nullo.
- Pensare che velocità costante significhi assenza di forze.
- Confondere lavoro dell'attrito, che è negativo, ed energia dissipata, che viene considerata positiva.

---

## Checklist di preparazione

- [ ] So individuare le forze agenti su un piano inclinato.
- [ ] So scomporre la forza peso.
- [ ] So calcolare la reazione normale.
- [ ] So distinguere attrito statico e dinamico.
- [ ] So calcolare l'attrito dinamico.
- [ ] So verificare se un corpo rimane fermo su un piano scabro.
- [ ] So calcolare l'accelerazione su un piano senza attrito.
- [ ] So calcolare l'accelerazione durante la discesa con attrito.
- [ ] So calcolare la decelerazione durante la risalita.
- [ ] So calcolare la distanza di arresto.
- [ ] So utilizzare il teorema dell'energia cinetica.
- [ ] So individuare le forze che compiono lavoro nullo.
- [ ] So calcolare il lavoro della forza peso.
- [ ] So calcolare il lavoro dell'attrito dinamico.
- [ ] So interpretare il moto a velocità costante su un piano inclinato.
- [ ] So risolvere autonomamente l'esame del 10 settembre 2026, domanda 10.
- [ ] So risolvere autonomamente l'esempio compito 1, domanda 12.
- [ ] So rispondere alla domanda teorica dell'esame del 29 gennaio 2024, domanda 11.

---

## Collegamenti

- [[Cinematica]]
- [[Principi della dinamica]]
- [[Equilibrio delle forze]]
- [[Forza elastica]]
- [[Lavoro energia e potenza]]
- [[Calore latente]]
