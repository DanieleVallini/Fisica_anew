
# Impulso e quantità di moto

## Introduzione

La **quantità di moto** e l'**impulso** sono grandezze fondamentali della dinamica, particolarmente utili per descrivere il movimento dei corpi e le interazioni di breve durata, come gli urti.

I concetti principali sono:

- **Quantità di moto:** grandezza vettoriale che dipende dalla massa e dalla velocità di un corpo.
- **Impulso:** misura l'effetto di una forza durante un intervallo di tempo.
- **Teorema dell'impulso:** collega l'impulso alla variazione della quantità di moto.
- **Conservazione della quantità di moto:** permette di studiare sistemi nei quali l'impulso risultante delle forze esterne è nullo.

Questi concetti sono particolarmente importanti negli esercizi in cui una forza agisce per un tempo molto breve oppure due corpi entrano in collisione.

---

## Quantità di moto

La **quantità di moto** è una grandezza vettoriale definita come il prodotto tra la massa e la velocità di un corpo.

$$
\boxed{\vec p=m\vec v}
$$

dove:

- $\vec p$ = quantità di moto.
- $m$ = massa del corpo (kg).
- $\vec v$ = velocità del corpo (m/s).

Nel Sistema Internazionale la quantità di moto si misura in:

$$
\boxed{[\vec p]=\text{kg}\cdot\text{m/s}}
$$

### Significato fisico

La quantità di moto dipende da due grandezze:

1. La massa del corpo.
2. La sua velocità.

A parità di velocità, un corpo più massiccio possiede una quantità di moto maggiore.

A parità di massa, un corpo più veloce possiede una quantità di moto maggiore in modulo.

### Grandezza vettoriale

La quantità di moto possiede la stessa direzione e lo stesso verso della velocità.

Nel moto lungo un solo asse:

$$
\boxed{p=mv}
$$

La velocità e la quantità di moto possono essere positive o negative a seconda del sistema di riferimento.

**Attenzione:** il segno della quantità di moto indica il verso del movimento, non una quantità di moto fisicamente negativa in modulo.

### Esempio

Un corpo di massa:

$$
m=5\ \text{kg}
$$

si muove verso destra con velocità:

$$
v=4\ \text{m/s}
$$

Scegliendo verso destra come positivo:

$$
p=mv
$$

$$
p=5\cdot4
$$

$$
\boxed{p=20\ \text{kg}\cdot\text{m/s}}
$$

Se il corpo si muovesse verso sinistra con la stessa rapidità:

$$
v=-4\ \text{m/s}
$$

allora:

$$
\boxed{p=-20\ \text{kg}\cdot\text{m/s}}
$$

Il modulo sarebbe identico, ma il verso opposto.

---

## Variazione della quantità di moto

Quando cambia la velocità di un corpo, cambia anche la sua quantità di moto.

La variazione è definita da:

$$
\boxed{\Delta\vec p=\vec p_f-\vec p_i}
$$

Se la massa rimane costante:

$$
\boxed{\Delta\vec p=m(\vec v_f-\vec v_i)}
$$

Nel caso unidimensionale:

$$
\boxed{\Delta p=m(v_f-v_i)}
$$

dove:

- $v_i$ = velocità iniziale.
- $v_f$ = velocità finale.
- $m$ = massa del corpo.

### Corpo che accelera

Se un corpo aumenta la propria velocità mantenendo lo stesso verso, il modulo della quantità di moto aumenta.

### Corpo che rallenta

Se un corpo rallenta mantenendo lo stesso verso, il modulo della quantità di moto diminuisce.

### Corpo che cambia verso

Se un corpo inverte il proprio movimento, bisogna prestare particolare attenzione ai segni delle velocità.

**Esempio**

Un corpo di massa 2 kg si muove inizialmente verso destra a 5 m/s e successivamente verso sinistra a 3 m/s.

Scegliamo verso destra come positivo.

$$
v_i=+5\ \text{m/s}
$$

$$
v_f=-3\ \text{m/s}
$$

La variazione della quantità di moto è:

$$
\Delta p=m(v_f-v_i)
$$

$$
\Delta p=2(-3-5)
$$

$$
\boxed{\Delta p=-16\ \text{kg}\cdot\text{m/s}}
$$

Il segno negativo indica che la variazione della quantità di moto è diretta verso sinistra.

---

## Impulso di una forza

L'**impulso** misura l'effetto di una forza esercitata su un corpo durante un intervallo di tempo.

Per una forza costante:

$$
\boxed{\vec J=\vec F\Delta t}
$$

dove:

- $\vec J$ = impulso.
- $\vec F$ = forza applicata.
- $\Delta t$ = intervallo di tempo durante il quale agisce la forza.

L'impulso è una grandezza vettoriale.

Nel Sistema Internazionale si misura in:

$$
\boxed{[J]=\text{N}\cdot\text{s}}
$$

Poiché:

$$
1\ \text{N}=1\ \text{kg}\cdot\text{m/s}^2
$$

si ottiene:

$$
\boxed{1\ \text{N}\cdot\text{s}=1\ \text{kg}\cdot\text{m/s}}
$$

Impulso e quantità di moto possiedono quindi le stesse dimensioni fisiche.

### Significato fisico

L'impulso dipende:

1. Dall'intensità della forza.
2. Dalla durata della sua applicazione.

Una forza molto intensa applicata per un tempo breve può produrre lo stesso impulso di una forza più debole applicata per un tempo maggiore.

### Esempio

Una forza costante di 100 N agisce su un corpo per 0,2 secondi.

Calcolare il modulo dell'impulso.

$$
J=F\Delta t
$$

$$
J=100\cdot0{,}2
$$

$$
\boxed{J=20\ \text{N}\cdot\text{s}}
$$

---

## Forza media e impulso

Durante un urto, la forza di contatto generalmente cambia nel tempo.

Per gli esercizi del professore non è necessario conoscere esattamente come varia.

Si utilizza la **forza media** nell'intervallo di contatto.

$$
\boxed{\vec J=\vec F_m\Delta t}
$$

dove $\vec F_m$ rappresenta la forza media vettoriale.

L'impulso può quindi essere calcolato utilizzando una forza media anche quando la forza effettiva non è costante.

### Ricavare la forza media

$$
\boxed{\vec F_m=\frac{\vec J}{\Delta t}}
$$

Una volta conosciuta la variazione della quantità di moto, questa relazione permette di calcolare la forza media esercitata durante un urto.

---

## Teorema dell'impulso

Il **teorema dell'impulso** stabilisce che l'impulso della forza risultante agente su un corpo è uguale alla variazione della sua quantità di moto.

$$
\boxed{\vec J_{\text{tot}}=\Delta\vec p}
$$

Per una forza risultante costante, oppure utilizzando la forza risultante media:

$$
\boxed{\vec F_m\Delta t=m(\vec v_f-\vec v_i)}
$$

Questa è la formula fondamentale dell'argomento.

### Ricavare la forza media

$$
\boxed{\vec F_m=\frac{m(\vec v_f-\vec v_i)}{\Delta t}}
$$

### Ricavare la velocità finale

Nel moto lungo un asse:

$$
F_m\Delta t=m(v_f-v_i)
$$

Quindi:

$$
\boxed{v_f=v_i+\frac{F_m\Delta t}{m}}
$$

### Ricavare il tempo

Se la forza media e la variazione della quantità di moto hanno lo stesso verso:

$$
\boxed{\Delta t=\frac{|\Delta p|}{F_m}}
$$

### Quando utilizzare il teorema

È particolarmente utile quando il problema fornisce:

- Massa del corpo.
- Velocità iniziale.
- Velocità finale.
- Durata dell'interazione.
- Forza media agente.

Di solito una di queste grandezze è incognita.

### Differenza rispetto al secondo principio di Newton

Il secondo principio, per una massa costante, è:

$$
\sum\vec F=m\vec a
$$

Il teorema dell'impulso considera invece la variazione della quantità di moto durante un intervallo di tempo:

$$
\vec J_{\text{tot}}=\Delta\vec p
$$

Per una forza risultante media:

$$
\vec F_m\Delta t=m\Delta\vec v
$$

I due principi sono strettamente collegati, ma il teorema dell'impulso risulta particolarmente comodo quando si studiano urti e interazioni di breve durata.

---

## Forze impulsive

Una **forza impulsiva** è una forza molto intensa che agisce durante un intervallo di tempo relativamente breve.

Esempi:

- Una mazza che colpisce una palla da baseball.
- Un martello che colpisce un chiodo.
- Una racchetta che colpisce una pallina.
- Due veicoli che entrano in collisione.

Durante queste interazioni, la quantità di moto dei corpi può cambiare rapidamente.

### Forza e durata dell'urto

Dal teorema dell'impulso:

$$
F_m=\frac{|\Delta\vec p|}{\Delta t}
$$

A parità di variazione della quantità di moto:

- Se il tempo di contatto diminuisce, la forza media aumenta.
- Se il tempo di contatto aumenta, la forza media diminuisce.

### Applicazione: dispositivi di sicurezza

Airbag e dispositivi di protezione sono progettati anche per aumentare il tempo durante il quale avviene il cambiamento della quantità di moto.

In questo modo, a parità di variazione della quantità di moto, è possibile ridurre il modulo della forza media.

**Attenzione:** questo ragionamento riguarda la forza media. La forza massima istantanea dipende anche da come la forza varia durante l'interazione.

---

## Corpo che inverte il verso del movimento

Questo è uno dei casi più importanti per l'esame.

Consideriamo un corpo di massa $m$ che si muove inizialmente verso destra con velocità $v$.

Dopo un urto, torna indietro con la stessa rapidità.

Scegliendo verso destra come positivo:

$$
v_i=+v
$$

$$
v_f=-v
$$

La variazione della quantità di moto è:

$$
\Delta p=m(v_f-v_i)
$$

$$
\Delta p=m(-v-v)
$$

$$
\boxed{\Delta p=-2mv}
$$

Il modulo della variazione è:

$$
\boxed{|\Delta p|=2mv}
$$

Pertanto il modulo della forza media risultante è:

$$
\boxed{F_m=\frac{2mv}{\Delta t}}
$$

### Principio da ricordare

Quando un corpo inverte il verso della velocità mantenendone il modulo, la variazione della quantità di moto ha modulo doppio rispetto alla quantità di moto iniziale.

**Attenzione:** questa formula semplificata vale soltanto quando la velocità finale ha lo stesso modulo della velocità iniziale ed è esattamente opposta.

---

## Esercizio ufficiale — Esempio compito 2, domanda 6

### Testo

Una palla da baseball viaggia alla velocità di:

$$
v_i=150\ \text{km/h}
$$

Viene colpita da una mazza e torna indietro verso il lanciatore con la stessa rapidità.

La massa della palla è:

$$
m=200\ \text{g}
$$

La mazza rimane in contatto con la palla per:

$$
\Delta t=0{,}1\ \text{s}
$$

Calcolare il modulo della forza media agente sulla palla.

### Soluzione

**1. Convertire la massa**

$$
m=200\ \text{g}=0{,}200\ \text{kg}
$$

**2. Convertire la velocità**

$$
v=\frac{150}{3{,}6}
$$

$$
v\approx41{,}67\ \text{m/s}
$$

**3. Individuare le velocità con i rispettivi segni**

Scegliamo come positivo il verso iniziale del movimento.

$$
v_i=+41{,}67\ \text{m/s}
$$

La palla torna indietro:

$$
v_f=-41{,}67\ \text{m/s}
$$

**4. Calcolare la variazione della quantità di moto**

$$
\Delta p=m(v_f-v_i)
$$

$$
\Delta p=0{,}200(-41{,}67-41{,}67)
$$

$$
\Delta p\approx-16{,}67\ \text{kg}\cdot\text{m/s}
$$

Il modulo è:

$$
\boxed{|\Delta p|\approx16{,}67\ \text{kg}\cdot\text{m/s}}
$$

**5. Applicare il teorema dell'impulso**

$$
F_m=\frac{|\Delta p|}{\Delta t}
$$

$$
F_m=\frac{16{,}67}{0{,}1}
$$

$$
\boxed{F_m\approx167\ \text{N}}
$$

### Risposta ufficiale

$$
\boxed{167\ \text{N}}
$$

### Principi da ricordare

- Convertire sempre km/h in m/s.
- Convertire i grammi in chilogrammi.
- Se il corpo inverte il verso, le velocità hanno segni opposti.
- La forza media dipende dalla variazione della quantità di moto, non semplicemente dalla quantità di moto iniziale.

Il risultato considera trascurabile l'impulso delle altre forze, come la gravità, durante il breve contatto.

---

## Esercizio ufficiale — Esame 29 gennaio 2024, domanda 6

### Testo

Una forza di modulo:

$$
F=1500\ \text{N}
$$

viene applicata per:

$$
\Delta t=20\ \text{ms}
$$

a una sfera di acciaio di massa:

$$
m=0{,}5\ \text{kg}
$$

che si muove inizialmente alla velocità di:

$$
v_i=15\ \text{m/s}
$$

La forza è applicata in verso opposto rispetto alla velocità iniziale.

Determinare:

1. Il modulo della velocità finale.
2. Il verso del movimento dopo l'interazione.

### Soluzione

**1. Convertire il tempo**

$$
20\ \text{ms}=20\cdot10^{-3}\ \text{s}
$$

$$
\boxed{\Delta t=0{,}020\ \text{s}}
$$

**2. Scegliere il verso positivo**

Consideriamo positivo il verso della velocità iniziale.

$$
v_i=+15\ \text{m/s}
$$

Poiché la forza agisce in verso opposto:

$$
F=-1500\ \text{N}
$$

**3. Calcolare l'impulso**

$$
J=F\Delta t
$$

$$
J=-1500\cdot0{,}020
$$

$$
\boxed{J=-30\ \text{N}\cdot\text{s}}
$$

**4. Applicare il teorema dell'impulso**

$$
F\Delta t=m(v_f-v_i)
$$

Ricaviamo la velocità finale:

$$
v_f=v_i+\frac{F\Delta t}{m}
$$

Sostituendo:

$$
v_f=15+\frac{-30}{0{,}5}
$$

$$
v_f=15-60
$$

$$
\boxed{v_f=-45\ \text{m/s}}
$$

### Risultato

**Modulo della velocità finale:**

$$
\boxed{|v_f|=45\ \text{m/s}}
$$

**Verso del movimento:**

Opposto rispetto alla velocità iniziale.

### Osservazione

L'impulso è sufficientemente grande non soltanto da arrestare momentaneamente la sfera, ma anche da farle invertire il verso del movimento.

**Attenzione:** non bisogna eliminare il segno negativo durante il calcolo, perché è necessario per determinare correttamente il verso finale.

*L'esame del 29 gennaio 2024 non contiene la soluzione ufficiale; questo risultato è stato calcolato a partire dai dati del testo.*

---

## Quantità di moto di un sistema

Quando un sistema contiene più corpi, la quantità di moto totale è la somma vettoriale delle quantità di moto dei singoli corpi.

$$
\boxed{\vec P_{\text{tot}}=\sum_i\vec p_i}
$$

Per due corpi:

$$
\boxed{\vec P_{\text{tot}}=m_1\vec v_1+m_2\vec v_2}
$$

Nel moto lungo un asse:

$$
\boxed{P_{\text{tot}}=m_1v_1+m_2v_2}
$$

È necessario utilizzare i segni corretti delle velocità.

### Esempio

Due corpi si muovono lungo la stessa direzione.

Il primo ha:

$$
m_1=2\ \text{kg}
$$

$$
v_1=+5\ \text{m/s}
$$

Il secondo ha:

$$
m_2=3\ \text{kg}
$$

$$
v_2=-2\ \text{m/s}
$$

La quantità di moto totale è:

$$
P_{\text{tot}}=m_1v_1+m_2v_2
$$

$$
P_{\text{tot}}=2\cdot5+3\cdot(-2)
$$

$$
P_{\text{tot}}=10-6
$$

$$
\boxed{P_{\text{tot}}=4\ \text{kg}\cdot\text{m/s}}
$$

La quantità di moto totale è diretta nel verso positivo.

---

## Forze interne ed esterne

In un sistema composto da più corpi, le forze possono essere distinte in:

### Forze interne

Sono le forze che i corpi del sistema esercitano gli uni sugli altri.

Per il terzo principio di Newton, le forze interne si presentano in coppie uguali e opposte.

Considerando il sistema completo, il loro contributo alla forza risultante totale si annulla.

### Forze esterne

Sono le forze esercitate sul sistema da corpi esterni a esso.

Esempi:

- Forza di attrito del terreno su un sistema di oggetti.
- Forza esercitata da una persona esterna al sistema.
- Forza gravitazionale di un corpo non compreso nel sistema considerato.

### Quantità di moto e forze esterne

La variazione della quantità di moto totale di un sistema è uguale all'impulso risultante delle forze esterne.

$$
\boxed{\vec J_{\text{est}}=\Delta\vec P_{\text{tot}}}
$$

Questa relazione è fondamentale per comprendere la conservazione della quantità di moto.

---

## Conservazione della quantità di moto

Il **principio di conservazione della quantità di moto** afferma che la quantità di moto totale di un sistema rimane costante quando l'impulso risultante delle forze esterne è nullo.

$$
\boxed{\vec P_i=\vec P_f}
$$

Per due corpi:

$$
\boxed{m_1\vec v_{1i}+m_2\vec v_{2i}=m_1\vec v_{1f}+m_2\vec v_{2f}}
$$

Questa relazione permette di calcolare le velocità dopo un'interazione.

### Sistemi isolati

Un sistema viene considerato **isolato**, dal punto di vista della quantità di moto, quando la risultante delle forze esterne è nulla.

$$
\sum\vec F_{\text{est}}=\vec0
$$

In tal caso la quantità di moto totale si conserva.

Negli urti di breve durata, è spesso sufficiente che l'impulso delle forze esterne sia trascurabile durante la collisione.

### Significato fisico

Durante un'interazione, la quantità di moto di un singolo corpo può cambiare.

Tuttavia, se la quantità di moto totale si conserva, la variazione di quantità di moto di un corpo viene compensata da quella degli altri corpi del sistema.

### Esempio

Due pattinatori inizialmente fermi si spingono reciprocamente su una superficie priva di attrito.

La quantità di moto iniziale totale è nulla:

$$
P_i=0
$$

Dopo la spinta i due pattinatori si muovono in versi opposti.

La quantità di moto totale rimane nulla:

$$
m_1v_1+m_2v_2=0
$$

Quindi:

$$
\boxed{v_2=-\frac{m_1}{m_2}v_1}
$$

Il pattinatore con massa maggiore avrà una velocità di modulo minore.

---

## Urti e quantità di moto — Richiamo

Gli **urti** sono interazioni tra corpi durante le quali possono agire forze molto intense per intervalli di tempo brevi.

Quando l'impulso risultante delle forze esterne è trascurabile, la quantità di moto totale si conserva.

$$
\boxed{\vec P_i=\vec P_f}
$$

Questa proprietà vale sia per gli urti elastici sia per quelli anelastici.

### Urto elastico

In un urto perfettamente elastico si conservano:

- Quantità di moto totale.
- Energia cinetica totale.

### Urto anelastico

In un urto anelastico si conserva la quantità di moto totale, ma non necessariamente l'energia cinetica.

### Urto completamente anelastico

In un urto completamente anelastico i due corpi rimangono uniti dopo la collisione e possiedono la stessa velocità finale.

La conservazione della quantità di moto lungo un asse diventa:

$$
\boxed{m_1v_{1i}+m_2v_{2i}=(m_1+m_2)v_f}
$$

Questa è la formula utilizzata nell'esempio compito 1, domanda 8.

Il procedimento completo sarà approfondito in [[Urti]].

---

## Esercizio ufficiale — Esempio compito 1, domanda 8

### Testo

Un proiettile di massa:

$$
m_p=10\ \text{g}
$$

viene sparato contro un blocco di legno inizialmente fermo di massa:

$$
M=5\ \text{kg}
$$

Il proiettile rimane conficcato nel blocco.

Dopo l'urto, il sistema proiettile-blocco si muove con velocità:

$$
v_f=0{,}6\ \text{m/s}
$$

Calcolare la velocità iniziale del proiettile.

### Soluzione

**1. Convertire la massa**

$$
m_p=10\ \text{g}=0{,}010\ \text{kg}
$$

**2. Riconoscere il tipo di urto**

Il proiettile rimane nel blocco.

Si tratta quindi di un **urto completamente anelastico**.

**3. Applicare la conservazione della quantità di moto**

$$
m_pv_p+Mv_B=(m_p+M)v_f
$$

Il blocco è inizialmente fermo:

$$
v_B=0
$$

Quindi:

$$
m_pv_p=(m_p+M)v_f
$$

Ricaviamo la velocità iniziale del proiettile:

$$
\boxed{v_p=\frac{(m_p+M)v_f}{m_p}}
$$

**4. Sostituire i dati**

$$
v_p=\frac{(0{,}010+5)\cdot0{,}6}{0{,}010}
$$

$$
v_p=\frac{5{,}01\cdot0{,}6}{0{,}010}
$$

$$
\boxed{v_p=300{,}6\ \text{m/s}}
$$

### Risposta ufficiale

$$
\boxed{300{,}6\ \text{m/s}}
$$

### Principio da ricordare

Durante un urto completamente anelastico i corpi rimangono uniti dopo la collisione.

Se l'impulso delle forze esterne è trascurabile, la quantità di moto totale si conserva, anche se l'energia cinetica diminuisce.

---

## Centro di massa — Richiamo

Il **centro di massa** è un punto che rappresenta la posizione media delle masse di un sistema, pesata in base alle rispettive masse.

Per due corpi lungo un asse:

$$
\boxed{x_{CM}=\frac{m_1x_1+m_2x_2}{m_1+m_2}}
$$

dove:

- $m_1,m_2$ = masse dei corpi.
- $x_1,x_2$ = loro posizioni.
- $x_{CM}$ = posizione del centro di massa.

### Significato fisico

Il centro di massa si trova più vicino al corpo con massa maggiore.

Se due masse sono uguali, il centro di massa si trova nel punto medio tra di esse.

### Esempio

Due corpi sono posti lungo un asse:

$$
m_1=2\ \text{kg},\qquad x_1=0\ \text{m}
$$

$$
m_2=3\ \text{kg},\qquad x_2=10\ \text{m}
$$

Il centro di massa è:

$$
x_{CM}=\frac{2\cdot0+3\cdot10}{2+3}
$$

$$
\boxed{x_{CM}=6\ \text{m}}
$$

Il centro di massa è più vicino al corpo di massa 3 kg.

### Velocità del centro di massa

Per un sistema di due corpi:

$$
\boxed{\vec v_{CM}=\frac{m_1\vec v_1+m_2\vec v_2}{m_1+m_2}}
$$

La quantità di moto totale può quindi essere espressa come:

$$
\boxed{\vec P_{\text{tot}}=M\vec v_{CM}}
$$

dove $M$ è la massa totale del sistema.

Se la quantità di moto totale si conserva, anche la velocità del centro di massa rimane costante, purché la massa totale sia costante.

---

## Quantità di moto ed energia cinetica

Quantità di moto ed energia cinetica sono entrambe grandezze associate al movimento, ma hanno proprietà differenti.

### Quantità di moto

$$
\boxed{\vec p=m\vec v}
$$

- È vettoriale.
- Dipende linearmente dalla velocità.
- Possiede direzione e verso.

### Energia cinetica

$$
\boxed{K=\frac12mv^2}
$$

- È scalare.
- Dipende dal quadrato della velocità.
- È sempre positiva o nulla.

### Differenza fondamentale

Un corpo può invertire il verso del proprio movimento mantenendo la stessa energia cinetica.

In questo caso:

- L'energia cinetica non cambia.
- La quantità di moto cambia.

**Esempio:** una palla da baseball che torna indietro con la stessa rapidità dopo essere stata colpita.

Prima e dopo il colpo:

$$
K_i=K_f
$$

Ma:

$$
\vec p_i\ne\vec p_f
$$

Questa distinzione è importante per capire perché la mazza esercita un impulso anche se il modulo della velocità della palla rimane invariato.

---

## Formule principali

| Grandezza | Formula |
|---|---|
| Quantità di moto | $\vec p=m\vec v$ |
| Variazione della quantità di moto | $\Delta\vec p=m(\vec v_f-\vec v_i)$ |
| Impulso di una forza costante | $\vec J=\vec F\Delta t$ |
| Teorema dell'impulso | $\vec J_{\text{tot}}=\Delta\vec p$ |
| Forza risultante media | $\vec F_m=\Delta\vec p/\Delta t$ |
| Velocità finale lungo un asse | $v_f=v_i+F_m\Delta t/m$ |
| Inversione del moto con uguale rapidità | $|\Delta p|=2mv$ |
| Quantità di moto totale | $\vec P_{\text{tot}}=\sum_i m_i\vec v_i$ |
| Conservazione della quantità di moto | $\vec P_i=\vec P_f$ |
| Urto completamente anelastico | $m_1v_{1i}+m_2v_{2i}=(m_1+m_2)v_f$ |
| Centro di massa | $x_{CM}=(m_1x_1+m_2x_2)/(m_1+m_2)$ |

---

## Come riconoscere gli esercizi

| Situazione | Procedimento |
|---|---|
| Si chiede la quantità di moto | $p=mv$ |
| Una forza agisce per un certo tempo | $J=F\Delta t$ |
| Si chiede la forza media di un urto | $F_m=|\Delta p|/\Delta t$ |
| Un corpo inverte il verso con uguale rapidità | $|\Delta p|=2mv$ |
| Si conoscono forza e durata e si cerca la velocità finale | $F_m\Delta t=m(v_f-v_i)$ |
| Due corpi si urtano | Conservazione della quantità di moto |
| Due corpi rimangono uniti dopo l'urto | Urto completamente anelastico |
| Si chiede la posizione del centro di massa | Media delle posizioni pesata sulle masse |

---

## Domande teoriche da conoscere

**Che cos'è la quantità di moto?**

È una grandezza vettoriale uguale al prodotto tra massa e velocità.

**Qual è l'unità di misura della quantità di moto?**

Chilogrammi per metri al secondo (kg·m/s).

**La quantità di moto è una grandezza scalare o vettoriale?**

Vettoriale, perché ha direzione e verso.

**Che cos'è l'impulso?**

È una grandezza vettoriale che descrive l'effetto di una forza durante un intervallo di tempo.

**Qual è l'unità di misura dell'impulso?**

Newton per secondo di durata, cioè newton moltiplicato per secondo (N·s).

**Che cosa afferma il teorema dell'impulso?**

L'impulso della forza risultante è uguale alla variazione della quantità di moto.

**Perché aumentando il tempo di un urto può diminuire la forza media?**

Perché, a parità di variazione della quantità di moto, la forza media è inversamente proporzionale alla durata dell'interazione.

**Cosa accade alla quantità di moto se un corpo inverte il verso mantenendo la stessa rapidità?**

La quantità di moto cambia verso e la sua variazione ha modulo pari a $2mv$.

**Quando si conserva la quantità di moto totale di un sistema?**

Quando l'impulso risultante delle forze esterne è nullo.

**Le forze interne possono modificare la quantità di moto totale di un sistema?**

No, se si considera il sistema completo e le forze interne soddisfano il principio di azione e reazione.

**La quantità di moto si conserva durante un urto anelastico?**

Sì, se l'impulso delle forze esterne è nullo o trascurabile.

**L'energia cinetica si conserva durante tutti gli urti?**

No. Si conserva negli urti perfettamente elastici, ma non generalmente negli urti anelastici.

**Un corpo può cambiare quantità di moto senza cambiare energia cinetica?**

Sì. Per esempio quando inverte il verso della velocità mantenendone il modulo.

**Che cos'è il centro di massa?**

È il punto che rappresenta la posizione media delle masse di un sistema, pesata secondo i valori delle masse.

---

## Errori frequenti

- Confondere quantità di moto ed energia cinetica.
- Dimenticare che la quantità di moto è vettoriale.
- Ignorare il segno delle velocità nei moti lungo un asse.
- Sommare i moduli delle velocità senza considerare i versi.
- Dimenticare di convertire grammi in chilogrammi.
- Dimenticare di convertire km/h in m/s.
- Dimenticare di convertire millisecondi in secondi.
- Calcolare la forza media usando soltanto la quantità di moto iniziale.
- Dimenticare che durante un'inversione del moto con uguale rapidità la variazione ha modulo $2mv$.
- Confondere la forza media con la forza massima durante l'urto.
- Applicare la conservazione della quantità di moto senza verificare l'impulso delle forze esterne.
- Pensare che la quantità di moto di ogni singolo corpo debba conservarsi durante una collisione.
- Pensare che la conservazione della quantità di moto implichi sempre la conservazione dell'energia cinetica.
- Dimenticare che in un urto completamente anelastico i corpi hanno la stessa velocità finale.
- Confondere il centro di massa con il punto medio geometrico quando le masse sono differenti.

---

## Checklist di preparazione

- [ ] So definire la quantità di moto.
- [ ] So calcolare la quantità di moto di un corpo.
- [ ] So distinguere modulo e verso della quantità di moto.
- [ ] So calcolare la variazione della quantità di moto.
- [ ] So definire l'impulso di una forza.
- [ ] So calcolare l'impulso di una forza costante.
- [ ] Conosco il teorema dell'impulso.
- [ ] So ricavare la forza media da massa, velocità e tempo.
- [ ] So ricavare la velocità finale conoscendo forza e durata.
- [ ] So risolvere problemi in cui un corpo inverte il verso.
- [ ] So distinguere forze interne ed esterne.
- [ ] Conosco il principio di conservazione della quantità di moto.
- [ ] So applicare la conservazione a due corpi.
- [ ] So riconoscere un urto completamente anelastico.
- [ ] So distinguere quantità di moto ed energia cinetica.
- [ ] So calcolare il centro di massa di due corpi.
- [ ] So risolvere autonomamente l'esempio compito 2, domanda 6.
- [ ] So risolvere autonomamente l'esame del 29 gennaio 2024, domanda 6.
- [ ] So risolvere autonomamente l'esempio compito 1, domanda 8.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[Cinematica]]
- [[Principi della dinamica]]
- [[Lavoro energia e potenza]]
- [[Urti]]
- [[Moto circolare]]
- [[Gravitazione]]
