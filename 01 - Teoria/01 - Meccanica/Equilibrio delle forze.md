
# Equilibrio delle forze

## Introduzione

Un corpo si trova in **equilibrio traslazionale** quando la risultante di tutte le forze esterne che agiscono su di esso è nulla.

Secondo il [[Principi della dinamica|secondo principio della dinamica]]:

$$
\sum \vec F=m\vec a
$$

Se la risultante delle forze è nulla:

$$
\boxed{\sum\vec F=\vec 0}
$$

allora:

$$
\boxed{\vec a=\vec 0}
$$

Il corpo non subisce accelerazione e mantiene costante la propria velocità.

L'equilibrio traslazionale comprende quindi due situazioni:

- **Equilibrio statico:** il corpo rimane fermo.
- **Equilibrio dinamico:** il corpo si muove con velocità vettoriale costante.

**Importante:** un corpo in equilibrio non è necessariamente fermo. Può anche muoversi di moto rettilineo uniforme.

---

## Condizioni di equilibrio

Poiché le forze sono grandezze vettoriali, l'equilibrio richiede che la somma delle loro componenti sia nulla lungo ogni asse.

Nel piano cartesiano:

$$
\boxed{\sum F_x=0}
$$

$$
\boxed{\sum F_y=0}
$$

Nello spazio tridimensionale si aggiunge:

$$
\boxed{\sum F_z=0}
$$

Queste equazioni permettono di determinare forze incognite, tensioni e reazioni vincolari.

### Equilibrio lungo un solo asse

Se un corpo è soggetto a due forze opposte lungo lo stesso asse:

$$
F_1-F_2=0
$$

quindi:

$$
\boxed{F_1=F_2}
$$

Le due forze devono avere uguale modulo e verso opposto.

### Equilibrio nel piano

Quando le forze agiscono in direzioni differenti, bisogna analizzare separatamente le componenti orizzontali e verticali.

Per esempio, se un corpo è fermo sotto l'azione di una forza orizzontale e di due forze inclinate, occorre:

1. Scomporre le forze inclinate.
2. Scrivere l'equazione di equilibrio orizzontale.
3. Scrivere l'equazione di equilibrio verticale.
4. Ricavare le grandezze incognite.

**Nota:** per un corpo rigido esteso in equilibrio statico occorre anche che sia nullo il momento risultante delle forze. Negli esercizi di equilibrio del punto materiale considerati qui, ci concentriamo sull'annullamento della risultante delle forze.

---

## Diagramma delle forze

Il **diagramma del corpo libero** è una rappresentazione delle forze esterne agenti su un corpo.

È uno strumento molto utile per evitare errori nella risoluzione degli esercizi.

### Come costruirlo

1. Isolare il corpo da studiare.
2. Rappresentarlo come un punto o un semplice blocco.
3. Disegnare tutte le forze esterne applicate.
4. Indicare direzione e verso di ogni forza.
5. Scegliere gli assi cartesiani.
6. Scomporre le eventuali forze inclinate.

Le forze più comuni sono:

| Forza | Simbolo | Direzione |
|---|---|---|
| Forza peso | $P$ | Verticale verso il basso |
| Reazione normale | $N$ | Perpendicolare alla superficie |
| Tensione | $T$ | Lungo il filo |
| Forza applicata | $F$ | Secondo la direzione indicata |
| Attrito | $f$ | Opposto allo scorrimento o alla sua tendenza |

**Attenzione:** bisogna rappresentare soltanto le forze che agiscono sul corpo scelto, non quelle che esso esercita su altri corpi.

---

## Equilibrio di un corpo su un piano orizzontale

Consideriamo un corpo di massa $m$ appoggiato su un piano orizzontale.

Se non agiscono altre forze verticali, sul corpo agiscono:

- La forza peso $P=mg$, diretta verso il basso.
- La reazione normale $N$, diretta verso l'alto.

Poiché il corpo non accelera verticalmente:

$$
\sum F_y=0
$$

$$
N-mg=0
$$

Pertanto:

$$
\boxed{N=mg}
$$

### Esempio

Un blocco di massa 5 kg è fermo su un pavimento orizzontale.

Calcolare la reazione normale.

$$
N=mg
$$

$$
N=5\cdot9{,}81
$$

$$
\boxed{N=49{,}05\ \text{N}}
$$

La reazione normale compensa esattamente il peso.

### Quando la reazione normale non coincide con il peso

La relazione $N=mg$ non è sempre valida.

Per esempio, se una forza esterna tira il corpo verso l'alto con una componente verticale $F_y$, senza provocare accelerazione verticale:

$$
N+F_y-mg=0
$$

quindi:

$$
\boxed{N=mg-F_y}
$$

Se invece una forza esterna spinge il corpo verso il basso, la reazione normale aumenta.

La reazione normale dipende quindi da tutte le forze perpendicolari alla superficie e dall'eventuale accelerazione in quella direzione.

---

## Equilibrio di un corpo sospeso

Consideriamo un corpo appeso a un filo verticale di massa trascurabile.

Le forze agenti sono:

- **Forza peso:** $P=mg$, verso il basso.
- **Tensione:** $T$, verso l'alto.

Se il corpo è fermo:

$$
\sum F_y=0
$$

$$
T-mg=0
$$

Da cui:

$$
\boxed{T=mg}
$$

### Esempio

Un corpo di massa 3 kg è sospeso a un filo verticale.

Calcolare la tensione.

$$
T=mg
$$

$$
T=3\cdot9{,}81
$$

$$
\boxed{T=29{,}43\ \text{N}}
$$

### Tensione e forza peso

La tensione non è necessariamente uguale al peso.

La relazione vale quando il corpo non possiede accelerazione verticale e le sole forze verticali sono tensione e peso.

Se il corpo accelera, bisogna applicare:

$$
\sum F_y=ma_y
$$

---

## Equilibrio con un filo inclinato

Questo è uno dei casi più importanti per il nostro esame.

Consideriamo un corpo di massa $m$ sospeso al soffitto mediante un filo, mantenuto fermo da una forza orizzontale $F$.

Il filo forma un angolo $\theta$ rispetto alla **verticale**.

Sul corpo agiscono tre forze:

1. **Peso:** $P=mg$, verso il basso.
2. **Tensione:** $T$, lungo il filo verso il punto di sospensione.
3. **Forza orizzontale:** $F$, nella direzione indicata.

Poiché il corpo è fermo:

$$
\sum F_x=0
$$

$$
\sum F_y=0
$$

### Scomposizione della tensione

Dato che l'angolo è misurato rispetto alla verticale:

**Componente orizzontale:**

$$
\boxed{T_x=T\sin\theta}
$$

**Componente verticale:**

$$
\boxed{T_y=T\cos\theta}
$$

Questa distinzione è fondamentale.

Se l'angolo fosse misurato rispetto all'orizzontale, seno e coseno si scambierebbero.

### Equilibrio orizzontale

Considerando i moduli delle forze opposte:

$$
F-T\sin\theta=0
$$

Quindi:

$$
\boxed{F=T\sin\theta}
$$

### Equilibrio verticale

La componente verticale della tensione deve compensare il peso:

$$
T\cos\theta-mg=0
$$

Pertanto:

$$
\boxed{T=\frac{mg}{\cos\theta}}
$$

### Ricavare la forza orizzontale

Sostituendo la tensione nell'equazione orizzontale:

$$
F=\frac{mg}{\cos\theta}\sin\theta
$$

Poiché:

$$
\tan\theta=\frac{\sin\theta}{\cos\theta}
$$

si ottiene:

$$
\boxed{F=mg\tan\theta}
$$

Questa è la formula principale per gli esercizi del professore sul corpo sospeso con una forza orizzontale.

### Formule da ricordare

| Grandezza | Formula |
|---|---|
| Peso | $P=mg$ |
| Tensione del filo | $T=mg/\cos\theta$ |
| Forza orizzontale | $F=mg\tan\theta$ |
| Componente orizzontale della tensione | $T_x=T\sin\theta$ |
| Componente verticale della tensione | $T_y=T\cos\theta$ |

Le formule valgono per un corpo fermo, un filo ideale e un angolo misurato rispetto alla verticale.

---

## Esercizio ufficiale — Corpo sospeso a 45°

**Presente in due prove:**
- Esempio compito 2 — Domanda 9.
- Esame 10 settembre 2026 — Domanda 2.

### Testo

Un corpo di massa:

$$
m=2\ \text{kg}
$$

è sospeso al soffitto tramite un filo di massa trascurabile.

Il corpo viene mantenuto in equilibrio mediante una forza orizzontale $F$.

Il filo forma un angolo:

$$
\theta=45^\circ
$$

rispetto alla verticale.

Calcolare il modulo della forza $F$.

### Soluzione

**1. Identificare le forze**

Sul corpo agiscono:

- Peso $P=mg$.
- Tensione $T$.
- Forza orizzontale $F$.

Il corpo è fermo, quindi la risultante è nulla.

**2. Equilibrio orizzontale**

$$
F-T\sin45^\circ=0
$$

Quindi:

$$
F=T\sin45^\circ
$$

**3. Equilibrio verticale**

$$
T\cos45^\circ-mg=0
$$

Da cui:

$$
T=\frac{mg}{\cos45^\circ}
$$

**4. Sostituire**

$$
F=mg\tan45^\circ
$$

Poiché:

$$
\tan45^\circ=1
$$

si ottiene:

$$
F=2\cdot9{,}81\cdot1
$$

$$
\boxed{F=19{,}62\ \text{N}}
$$

### Risposta corretta

$$
\boxed{19{,}62\ \text{N}}
$$

### Osservazione importante

Quando il filo forma un angolo di 45° rispetto alla verticale:

$$
\sin45^\circ=\cos45^\circ
$$

Le componenti orizzontale e verticale della tensione hanno lo stesso modulo.

Di conseguenza:

$$
\boxed{F=mg}
$$

Questo vale specificamente per l'angolo di 45°.

### Come potrebbe cambiare l'esercizio

Il professore potrebbe chiedere:

- La tensione del filo invece della forza orizzontale.
- La forza necessaria per mantenere un angolo diverso.
- L'angolo prodotto da una forza nota.
- La massa del corpo conoscendo forza e angolo.

Le formule utili sono:

$$
\boxed{T=\frac{mg}{\cos\theta}}
$$

$$
\boxed{F=mg\tan\theta}
$$

$$
\boxed{m=\frac{F}{g\tan\theta}}
$$

Se si cerca l'angolo:

$$
\boxed{\theta=\arctan\left(\frac{F}{mg}\right)}
$$

---

## Equilibrio con due fili

Un corpo può essere mantenuto in equilibrio anche mediante due fili inclinati.

Consideriamo un corpo di massa $m$ sostenuto da due fili simmetrici.

Ciascun filo forma un angolo $\theta$ rispetto all'orizzontale.

Le tensioni sono uguali:

$$
T_1=T_2=T
$$

### Equilibrio orizzontale

Le componenti orizzontali delle due tensioni si annullano:

$$
T\cos\theta-T\cos\theta=0
$$

### Equilibrio verticale

Le componenti verticali devono compensare la forza peso:

$$
2T\sin\theta-mg=0
$$

Quindi:

$$
\boxed{T=\frac{mg}{2\sin\theta}}
$$

### Esempio

Un corpo di massa 4 kg è sostenuto da due fili simmetrici, ciascuno inclinato di 30° rispetto all'orizzontale.

Calcolare la tensione di ciascun filo.

$$
T=\frac{mg}{2\sin30^\circ}
$$

$$
T=\frac{4\cdot9{,}81}{2\cdot0{,}5}
$$

$$
\boxed{T=39{,}24\ \text{N}}
$$

**Attenzione:** la formula cambia se l'angolo viene misurato rispetto alla verticale oppure se i due fili non sono simmetrici.

In generale, è sempre preferibile partire dalle equazioni di equilibrio lungo gli assi anziché memorizzare formule particolari.

---

## Equilibrio e attrito statico

L'**attrito statico** può mantenere fermo un corpo anche quando viene applicata una forza orizzontale.

Consideriamo un blocco appoggiato su un piano orizzontale, sottoposto a una forza orizzontale $F$.

Se il blocco rimane fermo:

$$
\sum F_x=0
$$

Quindi, in modulo:

$$
\boxed{f_s=F}
$$

L'attrito statico assume il valore necessario a compensare la forza applicata, purché non superi il proprio valore massimo:

$$
\boxed{f_s\le\mu_sN}
$$

Il massimo valore possibile è:

$$
\boxed{f_{s,\max}=\mu_sN}
$$

dove:
- $\mu_s$ = coefficiente di attrito statico.
- $N$ = reazione normale.

### Condizione per mantenere l'equilibrio

Su un piano orizzontale, in assenza di altre forze verticali:

$$
N=mg
$$

Se l'unica forza orizzontale applicata ha modulo $F$, il blocco può rimanere fermo se:

$$
\boxed{F\le\mu_smg}
$$

### Esempio

Un blocco di massa 5 kg è appoggiato su un piano orizzontale.

Il coefficiente di attrito statico è:

$$
\mu_s=0{,}4
$$

Si applica una forza orizzontale di 15 N.

Stabilire se il corpo rimane fermo.

**1. Calcolare la reazione normale**

$$
N=mg
$$

$$
N=5\cdot9{,}81=49{,}05\ \text{N}
$$

**2. Calcolare l'attrito statico massimo**

$$
f_{s,\max}=\mu_sN
$$

$$
f_{s,\max}=0{,}4\cdot49{,}05
$$

$$
\boxed{f_{s,\max}=19{,}62\ \text{N}}
$$

**3. Confrontare le forze**

La forza applicata è:

$$
F=15\ \text{N}
$$

Poiché:

$$
15<19{,}62
$$

il corpo rimane fermo.

L'attrito statico effettivo sarà:

$$
\boxed{f_s=15\ \text{N}}
$$

e non 19,62 N.

**Principio da ricordare:** l'attrito statico si adatta alla forza applicata fino a un valore massimo.

Gli esercizi con piani inclinati e attrito sono approfonditi in [[Piano inclinato e attrito]].

---

## Equilibrio e moto rettilineo uniforme

Un corpo può essere in equilibrio traslazionale anche quando si muove.

Se la sua velocità vettoriale è costante:

$$
\vec a=\vec 0
$$

Dal secondo principio:

$$
\sum\vec F=m\vec a
$$

si ottiene:

$$
\boxed{\sum\vec F=\vec 0}
$$

### Esempio

Un blocco scivola lungo una superficie orizzontale a velocità costante.

Una forza orizzontale di 20 N lo trascina verso destra, mentre l'attrito agisce verso sinistra.

Poiché l'accelerazione è nulla:

$$
F-f_d=0
$$

Quindi:

$$
\boxed{f_d=20\ \text{N}}
$$

**Importante:** velocità costante non significa assenza di forze, ma risultante delle forze nulla.

Questo concetto compare anche negli esercizi in cui un corpo scende lungo un piano inclinato a velocità costante.

---

## Equilibrio e terzo principio della dinamica

Una distinzione importante riguarda le forze che si equilibrano e le coppie di azione e reazione.

### Forze in equilibrio

Agiscono sullo **stesso corpo** e hanno risultante nulla.

Esempio: su un libro fermo sopra un tavolo agiscono:
- Forza peso verso il basso.
- Reazione normale verso l'alto.

Queste due forze si compensano.

### Azione e reazione

Agiscono invece su **due corpi differenti**.

Esempio:
- Il libro esercita una forza verso il basso sul tavolo.
- Il tavolo esercita una forza verso l'alto sul libro.

Queste costituiscono una coppia di azione e reazione.

**Attenzione:** la forza peso sul libro e la reazione normale del tavolo sul libro non costituiscono una coppia di azione e reazione.

---

## Come risolvere gli esercizi di equilibrio

Per gli esercizi del professore è sufficiente seguire una procedura sistematica.

### 1. Identificare il corpo

Stabilire quale oggetto si sta studiando.

### 2. Elencare le forze agenti

Individuare peso, tensioni, reazioni normali, attrito e forze applicate.

### 3. Scegliere gli assi

Di solito:
- Asse $x$ orizzontale.
- Asse $y$ verticale.

In presenza di piani inclinati possono essere più convenienti assi paralleli e perpendicolari al piano.

### 4. Scomporre le forze inclinate

Se l'angolo è misurato rispetto all'orizzontale:

$$
F_x=F\cos\theta
$$

$$
F_y=F\sin\theta
$$

Se l'angolo è misurato rispetto alla verticale, i ruoli di seno e coseno si scambiano per i moduli delle componenti.

### 5. Imporre l'equilibrio

$$
\boxed{\sum F_x=0}
$$

$$
\boxed{\sum F_y=0}
$$

### 6. Ricavare l'incognita

Risolvere le equazioni e sostituire i dati numerici.

### 7. Verificare il risultato

Controllare:
- Le unità di misura.
- Il verso delle forze.
- Gli angoli utilizzati.
- La coerenza fisica del risultato.

---

## Formule principali

| Situazione | Formula |
|---|---|
| Equilibrio traslazionale | $\sum\vec F=\vec0$ |
| Equilibrio orizzontale | $\sum F_x=0$ |
| Equilibrio verticale | $\sum F_y=0$ |
| Forza peso | $P=mg$ |
| Corpo su piano orizzontale | $N=mg$ |
| Corpo appeso a un filo verticale | $T=mg$ |
| Filo inclinato, forza orizzontale | $F=mg\tan\theta$ |
| Filo inclinato, tensione | $T=mg/\cos\theta$ |
| Due fili simmetrici | $T=mg/(2\sin\theta)$ |
| Attrito statico massimo | $f_{s,\max}=\mu_sN$ |

**Attenzione:** le formule per tensioni, reazione normale e attrito dipendono dalle condizioni del problema. Le equazioni generali di equilibrio sono sempre il punto di partenza più sicuro.

---

## Come riconoscere gli esercizi

| Situazione | Procedimento |
|---|---|
| Corpo fermo appoggiato su un piano | Equilibrio verticale |
| Corpo appeso a un filo verticale | Uguagliare tensione e peso |
| Corpo appeso a un filo inclinato | Scomporre la tensione |
| Corpo mantenuto fermo da una forza orizzontale | Equilibrio lungo $x$ e $y$ |
| Due fili che sostengono un oggetto | Scomporre entrambe le tensioni |
| Blocco fermo nonostante una spinta | Verificare l'attrito statico |
| Corpo che procede a velocità costante | Imporre risultante nulla |

---

## Domande teoriche da conoscere

**Quando un corpo si trova in equilibrio traslazionale?**

Quando la somma vettoriale delle forze esterne che agiscono su di esso è nulla.

**Un corpo in equilibrio deve essere necessariamente fermo?**

No. Può muoversi con velocità vettoriale costante.

**Un corpo fermo è necessariamente privo di forze?**

No. Possono agire più forze che si compensano.

**Che differenza c'è tra equilibrio statico e dinamico?**

Nell'equilibrio statico il corpo è fermo. Nell'equilibrio dinamico traslazionale si muove con velocità vettoriale costante.

**Come si studia l'equilibrio di un corpo soggetto a forze inclinate?**

Scomponendo le forze lungo gli assi e imponendo che la somma delle componenti sia nulla.

**Qual è la tensione di un filo verticale che sostiene un corpo fermo?**

Se le uniche forze sono peso e tensione, $T=mg$.

**La reazione normale è sempre uguale al peso?**

No. Dipende dall'orientamento della superficie, dalle altre forze e dall'eventuale accelerazione normale.

**Come varia la tensione di un filo se viene inclinato mantenendo fermo il corpo mediante una forza orizzontale?**

Aumenta con l'angolo rispetto alla verticale, secondo $T=mg/\cos\theta$.

**L'attrito statico è sempre uguale a $\mu_sN$?**

No. Il prodotto $\mu_sN$ rappresenta il massimo attrito statico disponibile.

**Se un corpo si muove a velocità costante, qual è la forza risultante?**

È nulla.

**Le forze che si equilibrano sono necessariamente una coppia di azione e reazione?**

No. Le forze che si equilibrano agiscono sullo stesso corpo, mentre le coppie di azione e reazione agiscono su corpi differenti.

---

## Errori frequenti

- Pensare che equilibrio significhi necessariamente assenza di movimento.
- Pensare che un corpo fermo non sia soggetto a forze.
- Considerare una singola forza invece della risultante.
- Dimenticare di scomporre le tensioni inclinate.
- Confondere seno e coseno nella scomposizione.
- Non controllare rispetto a quale asse viene misurato l'angolo.
- Assumere che la tensione sia sempre uguale al peso.
- Assumere che la reazione normale sia sempre uguale al peso.
- Considerare l'attrito statico sempre uguale al suo valore massimo.
- Confondere le forze in equilibrio con le coppie di azione e reazione.
- Applicare direttamente formule particolari senza verificare le condizioni.
- Dimenticare di convertire la massa da grammi a chilogrammi.

---

## Checklist di preparazione

- [ ] So definire l'equilibrio traslazionale.
- [ ] So distinguere equilibrio statico e dinamico.
- [ ] So costruire un diagramma del corpo libero.
- [ ] So individuare tutte le forze agenti su un corpo.
- [ ] So scomporre una forza inclinata.
- [ ] So applicare le equazioni di equilibrio lungo gli assi.
- [ ] So calcolare la reazione normale su un piano orizzontale.
- [ ] So calcolare la tensione di un filo verticale.
- [ ] So risolvere problemi con un filo inclinato.
- [ ] So ricavare $F=mg\tan\theta$ dalle condizioni di equilibrio.
- [ ] So risolvere autonomamente l'esercizio del corpo di 2 kg a 45°.
- [ ] So risolvere problemi semplici con due fili.
- [ ] So verificare l'equilibrio in presenza di attrito statico.
- [ ] So spiegare l'equilibrio di un corpo che si muove a velocità costante.
- [ ] So distinguere equilibrio delle forze e azione-reazione.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[Cinematica]]
- [[Moto circolare]]
- [[Principi della dinamica]]
- [[Piano inclinato e attrito]]
- [[Forza elastica]]
- [[Lavoro energia e potenza]]
