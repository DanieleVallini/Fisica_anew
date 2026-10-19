
# Principi della dinamica

## Introduzione

La **dinamica** è la branca della meccanica che studia le cause del movimento dei corpi, cioè le **forze**.

Mentre la [[1 - Cinematica]] descrive come un corpo si muove, la dinamica spiega perché la sua velocità cambia oppure rimane costante.

La dinamica classica si basa sui **tre principi di Newton**:

1. Principio d'inerzia.
2. Principio fondamentale della dinamica.
3. Principio di azione e reazione.

Questi principi permettono di descrivere il movimento dei corpi quando sono soggetti a una o più forze.

---

## Il concetto di forza

Una **forza** è un'interazione capace di modificare lo stato di moto di un corpo oppure di deformarlo.

La forza è una grandezza vettoriale, caratterizzata da:

- **Modulo:** intensità della forza.
- **Direzione:** retta lungo la quale agisce.
- **Verso:** orientamento lungo la direzione.
- **Punto di applicazione:** punto in cui la forza agisce sul corpo.

Nel Sistema Internazionale la forza si misura in **newton (N)**.

$$
\boxed{1\ \text{N}=1\ \text{kg}\cdot\text{m/s}^2}
$$

Una forza di 1 N produce un'accelerazione di 1 m/s² su un corpo di massa 1 kg, se rappresenta la forza risultante agente sul corpo.

### Forze di contatto e forze a distanza

Le forze possono essere suddivise in due categorie.

**Forze di contatto**

Richiedono un'interazione diretta fra corpi.

Esempi:
- Reazione normale di una superficie.
- Attrito.
- Tensione di una corda.
- Forza elastica esercitata da una molla.

**Forze a distanza**

Possono agire anche senza contatto diretto.

Esempi:
- Forza gravitazionale.
- Forza elettrica.
- Forza magnetica.

---

## Risultante delle forze

Quando più forze agiscono su un corpo, il suo movimento dipende dalla loro **somma vettoriale**, chiamata forza risultante.

$$
\boxed{\vec F_{\text{ris}}=\sum_i\vec F_i}
$$

Due forze nella stessa direzione possono sommarsi oppure sottrarsi, a seconda del verso.

### Forze concordi

Due forze di 10 N e 5 N agiscono nella stessa direzione e nello stesso verso.

La risultante ha modulo:

$$
F_{\text{ris}}=10+5=\boxed{15\ \text{N}}
$$

### Forze opposte

Due forze di 10 N e 5 N agiscono lungo la stessa direzione, ma in versi opposti.

La risultante ha modulo:

$$
F_{\text{ris}}=10-5=\boxed{5\ \text{N}}
$$

ed è diretta nel verso della forza maggiore.

### Forze perpendicolari

Se due forze sono perpendicolari, il modulo della risultante si calcola mediante il teorema di Pitagora:

$$
\boxed{F_{\text{ris}}=\sqrt{F_x^2+F_y^2}}
$$

**Esempio**

Un corpo è sottoposto a una forza orizzontale di 3 N e a una forza verticale di 4 N.

$$
F_{\text{ris}}=\sqrt{3^2+4^2}
$$

$$
\boxed{F_{\text{ris}}=5\ \text{N}}
$$

### Scomposizione delle forze

Una forza inclinata di un angolo $\theta$ rispetto all'asse orizzontale può essere scomposta nelle componenti:

$$
\boxed{F_x=F\cos\theta}
$$

$$
\boxed{F_y=F\sin\theta}
$$

Queste formule assumono che l'angolo sia misurato rispetto all'asse orizzontale positivo; i segni dipendono dal verso delle componenti.

La scomposizione permette di studiare separatamente il moto lungo i diversi assi.

---

## Primo principio della dinamica — Principio d'inerzia

Il **primo principio di Newton** afferma che:

> Un corpo mantiene il proprio stato di quiete o di moto rettilineo uniforme finché la risultante delle forze esterne agenti su di esso è nulla.

Matematicamente:

$$
\boxed{\sum\vec F=\vec 0\Rightarrow\vec a=\vec 0}
$$

Se la risultante delle forze è nulla, la velocità del corpo rimane costante.

Questo significa che un corpo può:

- Rimanere fermo.
- Muoversi in linea retta con velocità costante.

**Non è necessaria una forza per mantenere un corpo in movimento rettilineo uniforme.**

Una forza risultante è invece necessaria per modificare la velocità.

### Inerzia

L'**inerzia** è la tendenza di un corpo a opporsi ai cambiamenti del proprio stato di moto.

La massa rappresenta una misura dell'inerzia: maggiore è la massa, maggiore è la forza necessaria per ottenere la stessa accelerazione.

### Esempio: automobile che frena

Un'automobile procede in avanti e improvvisamente frena.

I passeggeri tendono a continuare il movimento in avanti perché, per inerzia, mantengono la velocità che possedevano prima della frenata.

La cintura di sicurezza esercita una forza che modifica il loro movimento e li rallenta.

### Esempio: automobile in curva

Durante una curva, i passeggeri sembrano essere spinti verso l'esterno.

Questo accade perché il loro corpo tende a mantenere la direzione della velocità precedente.

Per seguire la curva è necessaria una forza diretta verso il centro della traiettoria.

Questo fenomeno è approfondito in [[2 - Moto circolare]].

### Sistemi di riferimento inerziali

I principi di Newton valgono nella loro forma ordinaria nei **sistemi di riferimento inerziali**.

Un sistema di riferimento inerziale è un sistema nel quale un corpo non soggetto a una forza risultante mantiene una velocità costante.

Un sistema che accelera o ruota rispetto a un sistema inerziale è invece non inerziale.

Nei sistemi non inerziali possono comparire forze apparenti, come la forza centrifuga.

---

## Secondo principio della dinamica — Legge fondamentale

Il **secondo principio di Newton** stabilisce che l'accelerazione di un corpo è direttamente proporzionale alla forza risultante applicata e inversamente proporzionale alla sua massa.

Per un corpo di massa costante:

$$
\boxed{\sum\vec F=m\vec a}
$$

Questa è una delle formule più importanti dell'intero corso.

Dove:
- $\sum\vec F$ = forza risultante (N).
- $m$ = massa (kg).
- $\vec a$ = accelerazione (m/s²).

### Ricavare l'accelerazione

$$
\boxed{\vec a=\frac{\sum\vec F}{m}}
$$

### Ricavare la massa

Conoscendo i moduli della risultante e dell'accelerazione non nulla:

$$
\boxed{m=\frac{F_{\text{ris}}}{a}}
$$

### Significato fisico

Dalla relazione:

$$
a=\frac{F_{\text{ris}}}{m}
$$

si deduce che:

- A parità di massa, raddoppiando la forza risultante raddoppia l'accelerazione.
- A parità di forza risultante, raddoppiando la massa l'accelerazione si dimezza.
- Se la risultante è nulla, l'accelerazione è nulla.
- L'accelerazione ha la stessa direzione e lo stesso verso della forza risultante.

**Attenzione:** l'accelerazione ha la direzione della forza risultante, non necessariamente quella della velocità.

### Esempio

Un corpo di massa 5 kg è sottoposto a una forza risultante orizzontale di 20 N.

Calcolare l'accelerazione.

$$
a=\frac{F_{\text{ris}}}{m}
$$

$$
a=\frac{20}{5}
$$

$$
\boxed{a=4\ \text{m/s}^2}
$$

Se il corpo parte da fermo, dopo 3 secondi la velocità sarà:

$$
v=v_0+at
$$

$$
v=0+4\cdot3
$$

$$
\boxed{v=12\ \text{m/s}}
$$

Questo esempio combina il secondo principio della dinamica con una formula della [[1 - Cinematica]].

---

## Applicazione lungo gli assi cartesiani

Quando le forze agiscono in direzioni differenti, conviene applicare il secondo principio separatamente lungo ogni asse.

Nel piano:

$$
\boxed{\sum F_x=ma_x}
$$

$$
\boxed{\sum F_y=ma_y}
$$

Nel caso tridimensionale si aggiunge:

$$
\boxed{\sum F_z=ma_z}
$$

### Esempio

Un corpo di massa 2 kg è soggetto a due forze:

- $F_x=6\ \text{N}$ verso destra.
- $F_y=8\ \text{N}$ verso l'alto.

Le componenti dell'accelerazione sono:

$$
a_x=\frac{6}{2}=3\ \text{m/s}^2
$$

$$
a_y=\frac{8}{2}=4\ \text{m/s}^2
$$

Il modulo dell'accelerazione risultante vale:

$$
a=\sqrt{a_x^2+a_y^2}
$$

$$
a=\sqrt{3^2+4^2}
$$

$$
\boxed{a=5\ \text{m/s}^2}
$$

Questo procedimento è utile quando bisogna studiare contemporaneamente forze orizzontali e verticali.

---

## Terzo principio della dinamica — Azione e reazione

Il **terzo principio di Newton** afferma che:

> Quando un corpo A esercita una forza su un corpo B, il corpo B esercita contemporaneamente una forza su A di uguale modulo e direzione, ma verso opposto.

Matematicamente:

$$
\boxed{\vec F_{A\rightarrow B}=-\vec F_{B\rightarrow A}}
$$

Le due forze:

- Hanno lo stesso modulo.
- Hanno la stessa direzione.
- Hanno versi opposti.
- Agiscono su due corpi differenti.

### Esempio: camminare

Quando camminiamo, il piede esercita una forza sul terreno diretta all'indietro.

Il terreno esercita una forza di attrito sul piede diretta in avanti.

Questa forza contribuisce a farci avanzare.

### Esempio: razzo

Un razzo espelle gas ad alta velocità in una direzione.

Il razzo riceve una forza in verso opposto.

È il principio alla base della propulsione a reazione.

### Le forze di azione e reazione si annullano?

**No, non nella risultante delle forze su un singolo corpo.**

Le due forze agiscono su corpi differenti, quindi non possono essere sommate come se agissero sullo stesso oggetto.

Questo è un errore frequente nelle domande teoriche.

---

## Massa e forza peso

La **massa** e il **peso** sono grandezze fisiche differenti.

### Massa

La massa misura l'inerzia di un corpo.

- Simbolo: $m$.
- Unità di misura: kg.
- Non dipende dal luogo in cui si trova il corpo.

### Forza peso

La forza peso è la forza gravitazionale esercitata da un corpo celeste su un oggetto.

Vicino alla superficie terrestre:

$$
\boxed{P=mg}
$$

dove:
- $P$ = modulo della forza peso (N).
- $m$ = massa del corpo (kg).
- $g$ = accelerazione gravitazionale (m/s²).

Sulla Terra:

$$
\boxed{g\approx9{,}81\ \text{m/s}^2}
$$

La forza peso è diretta verso il centro della Terra.

### Esempio

Un corpo ha massa 10 kg.

$$
P=mg
$$

$$
P=10\cdot9{,}81
$$

$$
\boxed{P=98{,}1\ \text{N}}
$$

**Attenzione:** una massa di 10 kg non corrisponde a un peso di 10 N.

---

## Caduta libera e secondo principio

Un corpo in caduta libera, trascurando la resistenza dell'aria, è soggetto soltanto alla forza peso.

Applicando il secondo principio:

$$
F_{\text{ris}}=ma
$$

Poiché:

$$
F_{\text{ris}}=mg
$$

segue:

$$
ma=mg
$$

Per un corpo di massa non nulla:

$$
\boxed{a=g}
$$

L'accelerazione gravitazionale non dipende quindi dalla massa del corpo, nelle stesse condizioni e in assenza di resistenza dell'aria.

### Conseguenza

Due corpi di masse differenti, lasciati cadere dalla stessa altezza e nello stesso istante, raggiungono il suolo contemporaneamente se si trascura l'attrito dell'aria.

Le formule per calcolare tempi, velocità e spostamenti si trovano in [[Cinematica]].

---

## Reazione normale

La **reazione normale** è la forza esercitata da una superficie su un corpo a contatto con essa, diretta perpendicolarmente alla superficie.

Si indica generalmente con $N$.

### Corpo fermo su un piano orizzontale

Se un corpo è appoggiato su un piano orizzontale e le uniche forze verticali sono peso e reazione normale:

$$
N-P=0
$$

Pertanto:

$$
\boxed{N=mg}
$$

**Attenzione:** la reazione normale non è sempre uguale alla forza peso.

Il suo valore dipende dalle altre forze agenti e dall'accelerazione perpendicolare alla superficie.

Su un piano inclinato, ad esempio, in assenza di altre forze con componente perpendicolare al piano e di accelerazione normale:

$$
\boxed{N=mg\cos\theta}
$$

Questa situazione verrà approfondita in [[Piano inclinato e attrito]].

---

## Tensione di una corda

La **tensione** è la forza trasmessa da una corda o da un filo quando viene tirato.

Si indica generalmente con $T$.

In un modello ideale di corda:

- La massa della corda è trascurabile.
- La corda è inestensibile.
- La tensione agisce lungo la corda.
- In un tratto ideale privo di altre forze distribuite, la tensione ha modulo costante.

### Corpo sospeso in equilibrio

Un corpo di massa $m$ è appeso verticalmente a una corda ed è fermo.

Le forze agenti sono:

- Forza peso $P=mg$, verso il basso.
- Tensione $T$, verso l'alto.

La risultante è nulla:

$$
T-mg=0
$$

Quindi:

$$
\boxed{T=mg}
$$

Se il corpo accelera verticalmente, è necessario utilizzare il secondo principio con i segni appropriati.

### Corpo sospeso e forza orizzontale

Se un corpo è appeso a una corda inclinata e viene mantenuto fermo da una forza orizzontale, bisogna scomporre la tensione.

Questo è esattamente il caso dell'esercizio presente sia nel secondo compito di esempio sia nell'esame del settembre 2026.

Il procedimento completo sarà sviluppato in [[Equilibrio delle forze]].

---

## Forza elastica — Richiamo

Una molla ideale esercita una forza che tende a riportarla alla lunghezza di riposo.

La **legge di Hooke** è:

$$
\boxed{F_x=-kx}
$$

dove:
- $F_x$ = componente della forza elastica (N).
- $k$ = costante elastica della molla (N/m).
- $x$ = deformazione rispetto alla lunghezza di riposo (m).

Il segno negativo indica che la forza elastica è opposta alla deformazione.

In modulo:

$$
\boxed{F=k|x|}
$$

Per calcolare l'allungamento a partire dal modulo della forza elastica:

$$
\boxed{|x|=\frac{F}{k}}
$$

Questo argomento è particolarmente importante perché un esercizio identico sull'allungamento di una molla compare in due prove d'esame.

Sarà approfondito in [[Forza elastica]].

---

## Forze di attrito — Richiamo

L'**attrito** è una forza di contatto che si oppone allo scorrimento relativo tra superfici o alla sua tendenza.

Si distinguono:

### Attrito statico

Agisce quando le superfici non scorrono l'una rispetto all'altra.

Il suo modulo soddisfa:

$$
\boxed{0\le f_s\le\mu_sN}
$$

Il massimo attrito statico possibile è:

$$
\boxed{f_{s,\max}=\mu_sN}
$$

### Attrito dinamico

Agisce quando due superfici scorrono l'una rispetto all'altra.

Nel modello elementare di attrito radente:

$$
\boxed{f_d=\mu_dN}
$$

dove:
- $\mu_s$ = coefficiente di attrito statico.
- $\mu_d$ = coefficiente di attrito dinamico.
- $N$ = reazione normale.

**Attenzione:** l'attrito statico non è necessariamente uguale a $\mu_sN$. Quello è soltanto il suo valore massimo.

Per gli esercizi completi si rimanda a [[Piano inclinato e attrito]].

---

## Forze dipendenti dalla velocità

Alcune forze dipendono dalla velocità del corpo rispetto al mezzo in cui si muove.

Un esempio è la **resistenza dell'aria**.

In alcuni modelli semplificati, per velocità e condizioni opportune, la forza resistente può essere approssimata da:

$$
\boxed{\vec F_r=-b\vec v}
$$

In altri casi, il suo modulo può essere proporzionale al quadrato della velocità:

$$
F_r\propto v^2
$$

La forza resistente è diretta in verso opposto alla velocità relativa rispetto al fluido.

### Velocità limite

Un corpo che cade in un fluido può raggiungere una velocità alla quale la risultante delle forze diventa nulla.

In questa situazione:

$$
\sum\vec F=0
$$

e quindi:

$$
a=0
$$

Il corpo prosegue con una velocità costante, detta **velocità limite**.

Per l'esame è sufficiente comprendere il fenomeno e saper riconoscere la condizione di risultante nulla.

---

## Come risolvere un problema di dinamica

Per affrontare gli esercizi del professore, conviene utilizzare sempre lo stesso procedimento.

### Identificare il corpo

Stabilire quale corpo si sta studiando.

### Individuare tutte le forze

Elencare le forze agenti, indicando direzione e verso.

Esempi:
- Peso.
- Tensione.
- Reazione normale.
- Attrito.
- Forza applicata.

### Scegliere gli assi

Scegliere assi cartesiani convenienti.

Per i piani inclinati, spesso è utile scegliere:
- Un asse parallelo al piano.
- Un asse perpendicolare al piano.

### Applicare il secondo principio

$$
\sum F_x=ma_x
$$

$$
\sum F_y=ma_y
$$

### Ricavare l'incognita

Isolare la grandezza richiesta e sostituire i valori numerici.

### Controllare il risultato

Verificare che:
- Le unità di misura siano coerenti.
- I segni siano corretti.
- Il risultato abbia significato fisico.

---

## Esercizi usciti negli esami

### Esame 29 gennaio 2024 — Domanda 7

**Testo**

Vicino alla superficie terrestre è presente un campo elettrico uniforme di intensità:

$$
E=100\ \text{N/C}
$$

diretto verticalmente verso il basso.

Quale carica elettrica deve essere posta su una monetina di massa 3 g affinché acceleri verso l'alto con accelerazione:

$$
a=0{,}19\ \text{m/s}^2
$$

Determinare modulo e segno della carica.

**Soluzione**

Sulla monetina agiscono due forze:

1. La forza peso, diretta verso il basso.
2. La forza elettrica, che deve essere diretta verso l'alto.

Poiché il campo elettrico è diretto verso il basso, la carica deve essere **negativa**.

Scegliamo l'asse verticale positivo verso l'alto.

Il secondo principio diventa:

$$
F_e-mg=ma
$$

La forza elettrica in modulo è:

$$
F_e=|q|E
$$

Quindi:

$$
|q|E-mg=ma
$$

Isolando la carica:

$$
|q|=\frac{m(g+a)}{E}
$$

Convertiamo la massa:

$$
m=3\ \text{g}=0{,}003\ \text{kg}
$$

Sostituendo:

$$
|q|=\frac{0{,}003(9{,}81+0{,}19)}{100}
$$

$$
|q|=\frac{0{,}03}{100}
$$

$$
|q|=3\cdot10^{-4}\ \text{C}
$$

Essendo negativa:

$$
\boxed{q=-3\cdot10^{-4}\ \text{C}}
$$

Equivalentemente:

$$
\boxed{q=-300\ \mu\text{C}}
$$

**Principio da ricordare:** per trovare la carica è necessario applicare il secondo principio lungo l'asse verticale e identificare correttamente il verso della forza elettrica.

*Il compito del 2024 non contiene le soluzioni ufficiali; il risultato è stato calcolato a partire dai dati dell'esercizio.*

### Esame 10 settembre 2026 — Domanda 5

**Testo**

Una carica elettrica inizialmente in quiete viene sottoposta esclusivamente alla forza elettrostatica prodotta da un campo elettrico uniforme.

Quale tipo di moto assume?

**Risposta corretta:** moto rettilineo uniformemente accelerato.

**Spiegazione**

In un campo elettrico uniforme, la forza esercitata su una carica costante è:

$$
\vec F=q\vec E
$$

Poiché il campo è uniforme, la forza è costante.

Per il secondo principio:

$$
m\vec a=q\vec E
$$

Quindi:

$$
\boxed{\vec a=\frac{q\vec E}{m}}
$$

L'accelerazione è costante.

Poiché la carica parte da ferma e la forza mantiene una direzione fissa, il movimento è rettilineo uniformemente accelerato.

### Esempio compito 1 — Domanda 4

**Testo**

Durante una curva i passeggeri di un'automobile vengono apparentemente spinti verso l'esterno. Perché?

**Risposta corretta:** a causa dell'inerzia, che tende a far mantenere loro la velocità precedente alla curva.

**Spiegazione**

Per il primo principio di Newton, un corpo tende a mantenere la propria velocità in assenza di una forza risultante.

Quando l'automobile curva, il passeggero tende a proseguire nella direzione precedente.

Il sedile o la portiera esercita una forza diretta verso il centro della curva per modificarne la velocità.

### Esempio compito 2 — Domanda 9

**Testo**

Un corpo di massa 2 kg è sospeso al soffitto mediante un filo di massa trascurabile e mantenuto fermo da una forza orizzontale.

L'angolo del filo rispetto alla verticale è di 45°.

Calcolare il modulo della forza orizzontale.

**Risposta ufficiale:**

$$
\boxed{F=19{,}62\ \text{N}}
$$

**Principio applicato:** il secondo principio con accelerazione nulla, scomponendo le forze lungo gli assi.

L'esercizio viene approfondito in [[Equilibrio delle forze]].

---

## Domande teoriche da conoscere

**Che cosa studia la dinamica?**

La dinamica studia le forze e le cause dei cambiamenti dello stato di moto dei corpi.

**Che cosa afferma il primo principio di Newton?**

Un corpo mantiene la propria velocità costante quando la risultante delle forze esterne è nulla, in un sistema di riferimento inerziale.

**Un corpo può muoversi senza che agiscano forze su di esso?**

Sì. In assenza di forza risultante può muoversi di moto rettilineo uniforme.

**Che cosa afferma il secondo principio di Newton?**

La forza risultante agente su un corpo di massa costante è uguale al prodotto della massa per l'accelerazione.

**Se la forza risultante raddoppia, cosa accade all'accelerazione?**

Raddoppia, se la massa rimane costante.

**Se la massa raddoppia e la forza risultante rimane costante, cosa accade all'accelerazione?**

Si dimezza.

**Che cosa afferma il terzo principio di Newton?**

A ogni forza esercitata da un corpo su un altro corrisponde una forza uguale e contraria esercitata dal secondo corpo sul primo.

**Le forze di azione e reazione si annullano tra loro?**

Non nella risultante su un singolo corpo, perché agiscono su corpi differenti.

**Qual è la differenza tra massa e peso?**

La massa misura l'inerzia e si misura in kg. Il peso è una forza gravitazionale e si misura in N.

**Perché due corpi di massa differente cadono con la stessa accelerazione nel vuoto?**

Perché, applicando il secondo principio alla forza peso, la massa si semplifica e rimane $a=g$.

**Un corpo fermo è necessariamente privo di forze?**

No. Possono agire più forze che si compensano, producendo una risultante nulla.

**La forza risultante è sempre diretta come la velocità?**

No. È diretta come l'accelerazione.

---

## Errori frequenti

- Confondere una singola forza con la forza risultante.
- Pensare che sia necessaria una forza per mantenere un moto rettilineo uniforme.
- Confondere massa e forza peso.
- Utilizzare la massa in grammi nelle formule del Sistema Internazionale.
- Confondere direzione della velocità e direzione dell'accelerazione.
- Sommare forze vettoriali senza considerare i versi.
- Dimenticare di scomporre le forze inclinate.
- Pensare che le forze di azione e reazione agiscano sullo stesso corpo.
- Assumere che la reazione normale sia sempre uguale a $mg$.
- Utilizzare $F=ma$ riferendosi a una sola forza quando ne agiscono diverse.
- Confondere l'attrito statico effettivo con il suo valore massimo.
- Dimenticare il segno della carica elettrica negli esercizi con campi elettrici.

---

## Checklist di preparazione

- [ ] So distinguere cinematica e dinamica.
- [ ] Conosco il significato fisico di una forza.
- [ ] So calcolare la risultante di forze concordi e opposte.
- [ ] So calcolare la risultante di due forze perpendicolari.
- [ ] So scomporre una forza lungo gli assi cartesiani.
- [ ] Conosco e so spiegare il primo principio di Newton.
- [ ] So spiegare il concetto di inerzia.
- [ ] Conosco e so applicare il secondo principio di Newton.
- [ ] So utilizzare le equazioni lungo gli assi.
- [ ] Conosco e so spiegare il terzo principio di Newton.
- [ ] So distinguere massa e peso.
- [ ] So calcolare la forza peso.
- [ ] So individuare reazione normale e tensione.
- [ ] Conosco il significato della forza elastica.
- [ ] So distinguere attrito statico e dinamico.
- [ ] So spiegare perché un campo elettrico uniforme può produrre un'accelerazione costante.
- [ ] So risolvere i problemi numerici collegati ai principi della dinamica.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[1 - Cinematica]]
- [[2 - Moto circolare]]
- [[Equilibrio delle forze]]
- [[Piano inclinato e attrito]]
- [[Forza elastica]]
- [[Lavoro energia e potenza]]
- [[Impulso e quantità di moto]]
- [[Gravitazione]]
- [[Campo elettrico]]
