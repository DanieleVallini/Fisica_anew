
# Gravitazione

## Introduzione

La **gravitazione** è l'interazione attrattiva che si manifesta tra corpi dotati di massa.

È responsabile di numerosi fenomeni fisici:

- La caduta dei corpi verso la superficie terrestre.
- Il peso degli oggetti.
- Il movimento della Luna attorno alla Terra.
- Il movimento dei pianeti attorno al Sole.
- Le orbite dei satelliti artificiali.

La gravitazione classica è descritta dalla **legge di gravitazione universale di Newton**.

Questa legge permette di calcolare la forza di attrazione tra due corpi e di descrivere il moto dei pianeti e dei satelliti.

---

## Legge di gravitazione universale

La **legge di gravitazione universale di Newton** stabilisce che due corpi dotati di massa si attraggono con una forza:

- Direttamente proporzionale al prodotto delle loro masse.
- Inversamente proporzionale al quadrato della distanza tra i loro centri, quando possono essere trattati come masse puntiformi o corpi sferici.

Il modulo della forza gravitazionale è:

$$
\boxed{F_g=G\frac{m_1m_2}{r^2}}
$$

dove:

- $F_g$ = modulo della forza gravitazionale (N).
- $G$ = costante di gravitazione universale.
- $m_1,m_2$ = masse dei due corpi (kg).
- $r$ = distanza tra i loro centri di massa (m), nei casi considerati.

La costante gravitazionale vale approssimativamente:

$$
\boxed{G=6{,}674\cdot10^{-11}\ \text{N}\cdot\text{m}^2/\text{kg}^2}
$$

### Caratteristiche della forza gravitazionale

La forza gravitazionale:

- È sempre attrattiva nella teoria newtoniana.
- Agisce lungo la retta che unisce i due corpi.
- Ha lo stesso modulo sui due corpi.
- Ha verso opposto sui due corpi.
- Diminuisce all'aumentare della distanza.

Le forze esercitate dai due corpi costituiscono una coppia di azione e reazione.

### Dipendenza dalle masse

Dalla relazione:

$$
F_g=G\frac{m_1m_2}{r^2}
$$

si deduce che:

- Se una massa raddoppia, la forza raddoppia.
- Se entrambe le masse raddoppiano, la forza quadruplica.
- Se una massa si dimezza, la forza si dimezza.

Queste considerazioni valgono mantenendo costante la distanza.

### Dipendenza dalla distanza

La forza è inversamente proporzionale al quadrato della distanza.

$$
\boxed{F_g\propto\frac{1}{r^2}}
$$

Di conseguenza:

| Variazione della distanza | Nuova forza |
|---|---|
| Distanza raddoppiata | $F_g/4$ |
| Distanza triplicata | $F_g/9$ |
| Distanza dimezzata | $4F_g$ |
| Distanza quadruplicata | $F_g/16$ |

**Attenzione:** nella formula si utilizza la distanza tra i centri dei corpi, non necessariamente la distanza tra le loro superfici.

---

## Campo gravitazionale

Un corpo dotato di massa genera un **campo gravitazionale** nello spazio circostante.

Il campo gravitazionale descrive la forza per unità di massa che agirebbe su un corpo di prova posto in una determinata posizione.

$$
\boxed{\vec g=\frac{\vec F_g}{m}}
$$

dove $m$ è la massa del corpo di prova.

Il campo gravitazionale è una grandezza vettoriale.

### Campo prodotto da una massa sferica

All'esterno di un corpo a distribuzione sfericamente simmetrica, il modulo del campo gravitazionale vale:

$$
\boxed{g(r)=G\frac{M}{r^2}}
$$

dove:

- $M$ = massa del corpo che genera il campo.
- $r$ = distanza dal suo centro.
- $G$ = costante gravitazionale.

Il campo è diretto verso il centro del corpo che lo genera.

### Significato fisico

Il campo gravitazionale diminuisce all'aumentare della distanza.

Se ci si allontana dal centro terrestre, l'accelerazione gravitazionale diminuisce.

---

## Accelerazione di gravità

Vicino alla superficie terrestre, il campo gravitazionale è approssimativamente uniforme su distanze piccole rispetto al raggio terrestre.

Il modulo dell'accelerazione gravitazionale vale:

$$
\boxed{g\approx9{,}81\ \text{m/s}^2}
$$

Il suo valore può essere ricavato dalla legge di gravitazione universale.

La forza gravitazionale esercitata dalla Terra su un corpo di massa $m$ è:

$$
F_g=G\frac{M_Tm}{R_T^2}
$$

Secondo il secondo principio della dinamica:

$$
F_g=mg
$$

Uguagliando:

$$
mg=G\frac{M_Tm}{R_T^2}
$$

Semplificando la massa del corpo:

$$
\boxed{g=\frac{GM_T}{R_T^2}}
$$

dove:

- $M_T$ = massa terrestre.
- $R_T$ = raggio terrestre.

### Conseguenza importante

L'accelerazione gravitazionale non dipende dalla massa del corpo che cade.

In assenza di resistenza dell'aria, due corpi lasciati cadere nello stesso luogo subiscono la stessa accelerazione gravitazionale.

### Distinzione tra G e g

| Simbolo | Significato | Unità |
|---|---|---|
| $G$ | Costante gravitazionale universale | N·m²/kg² |
| $g$ | Accelerazione gravitazionale locale | m/s² |

**Attenzione:** $G$ è una costante universale, mentre $g$ dipende dalla posizione e dalla distribuzione delle masse che generano il campo.

---

## Forza peso

La **forza peso** è la forza gravitazionale esercitata dalla Terra su un corpo.

Vicino alla superficie terrestre:

$$
\boxed{P=mg}
$$

dove:

- $P$ = forza peso (N).
- $m$ = massa (kg).
- $g$ = accelerazione gravitazionale (m/s²).

### Massa e peso

La massa e il peso sono grandezze differenti.

**Massa**
- Misura l'inerzia del corpo.
- Si misura in chilogrammi.
- Non dipende dal luogo in cui il corpo si trova.

**Peso**
- È una forza.
- Si misura in newton.
- Dipende dall'intensità del campo gravitazionale.

### Esempio

Un corpo ha massa:

$$
m=10\ \text{kg}
$$

Calcolare il suo peso sulla Terra.

$$
P=mg
$$

$$
P=10\cdot9{,}81
$$

$$
\boxed{P=98{,}1\ \text{N}}
$$

Lo stesso corpo sulla Luna avrebbe la stessa massa, ma un peso minore.

---

## Variazione della gravità con l'altitudine

L'accelerazione gravitazionale diminuisce all'aumentare della distanza dal centro della Terra.

Alla superficie terrestre:

$$
\boxed{g_0=\frac{GM_T}{R_T^2}}
$$

A un'altitudine $h$:

$$
r=R_T+h
$$

quindi:

$$
\boxed{g(h)=\frac{GM_T}{(R_T+h)^2}}
$$

Dividendo per l'accelerazione gravitazionale alla superficie:

$$
\boxed{g(h)=g_0\left(\frac{R_T}{R_T+h}\right)^2}
$$

### Significato fisico

- Se l'altitudine aumenta, l'accelerazione gravitazionale diminuisce.
- Se la distanza dal centro della Terra raddoppia, l'accelerazione si riduce a un quarto.
- Se la distanza triplica, l'accelerazione si riduce a un nono.

### Attenzione alla distanza

Se un problema afferma che un satellite si trova a un'altezza $h$ sopra la superficie terrestre, nella legge di gravitazione bisogna utilizzare:

$$
\boxed{r=R_T+h}
$$

Non bisogna sostituire direttamente $h$ al posto di $r$.

---

## Massa, volume e densità

La **densità** di un corpo è definita come il rapporto tra la sua massa e il suo volume.

$$
\boxed{\rho=\frac{M}{V}}
$$

Ricavando la massa:

$$
\boxed{M=\rho V}
$$

Per una sfera di raggio $R$, il volume è:

$$
\boxed{V=\frac43\pi R^3}
$$

Quindi la massa di una sfera omogenea è:

$$
\boxed{M=\rho\frac43\pi R^3}
$$

Questa relazione è fondamentale per un esercizio realmente uscito nell'esame.

---

## Accelerazione gravitazionale e densità terrestre

Consideriamo la Terra come una sfera di raggio $R_T$ e densità media $\rho_T$.

La massa terrestre è:

$$
M_T=\rho_T\frac43\pi R_T^3
$$

L'accelerazione gravitazionale alla superficie vale:

$$
g=\frac{GM_T}{R_T^2}
$$

Sostituendo l'espressione della massa:

$$
g=\frac{G\rho_T\frac43\pi R_T^3}{R_T^2}
$$

Semplificando:

$$
\boxed{g=\frac43\pi G\rho_TR_T}
$$

### Conseguenza importante

Se la densità media rimane costante:

$$
\boxed{g\propto R_T}
$$

Quindi:

- Se il raggio terrestre aumenta dell'1%, $g$ aumenta dell'1%.
- Se il raggio terrestre diminuisce dell'1%, $g$ diminuisce dell'1%.

Questo risultato può sembrare controintuitivo.

Infatti la relazione usuale:

$$
g=\frac{GM_T}{R_T^2}
$$

potrebbe far pensare che una diminuzione del raggio faccia aumentare $g$.

Tuttavia, **se la densità rimane costante, cambia anche la massa totale della Terra**.

La massa è proporzionale al cubo del raggio:

$$
M_T\propto R_T^3
$$

Pertanto l'accelerazione alla superficie risulta proporzionale al raggio.

---

## Esercizio ufficiale — Esempio compito 1, domanda 9

### Testo

La Terra è approssimativamente una sfera.

Immaginiamo che il suo raggio diminuisca dell'1%:

$$
R_T'=0{,}99R_T
$$

Supponiamo che la sua densità media rimanga costante.

Calcolare la nuova accelerazione gravitazionale $g'$ alla superficie.

### Soluzione

**1. Scrivere la formula dell'accelerazione gravitazionale**

$$
g=\frac{GM_T}{R_T^2}
$$

**2. Esprimere la massa in funzione della densità**

Poiché la Terra viene approssimata a una sfera:

$$
M_T=\rho_T\frac43\pi R_T^3
$$

Sostituendo:

$$
g=\frac43\pi G\rho_TR_T
$$

**3. Considerare il nuovo raggio**

La densità rimane costante.

Quindi:

$$
g'=\frac43\pi G\rho_TR_T'
$$

Poiché:

$$
R_T'=0{,}99R_T
$$

si ottiene:

$$
g'=0{,}99\left(\frac43\pi G\rho_TR_T\right)
$$

Pertanto:

$$
\boxed{g'=0{,}99g}
$$

### Risposta ufficiale

$$
\boxed{g'=0{,}99g}
$$

L'accelerazione gravitazionale diminuisce dell'1%.

### Valore numerico

Assumendo:

$$
g=9{,}81\ \text{m/s}^2
$$

si ottiene:

$$
g'=0{,}99\cdot9{,}81
$$

$$
\boxed{g'\approx9{,}71\ \text{m/s}^2}
$$

### Principio da ricordare

La soluzione dipende da quale grandezza il problema mantiene costante.

**Massa costante:**

$$
g\propto\frac{1}{R^2}
$$

**Densità costante:**

$$
g\propto R
$$

Non bisogna confondere i due casi.

---

## Energia potenziale gravitazionale

La forza gravitazionale è una **forza conservativa**.

Questo significa che il lavoro da essa compiuto dipende soltanto dalle posizioni iniziale e finale, non dal percorso seguito.

È quindi possibile definire un'energia potenziale gravitazionale.

Per due masse trattabili come puntiformi, scegliendo l'energia potenziale nulla a distanza infinita:

$$
\boxed{U_g=-\frac{GMm}{r}}
$$

dove:

- $U_g$ = energia potenziale gravitazionale (J).
- $G$ = costante gravitazionale.
- $M,m$ = masse dei corpi.
- $r$ = distanza tra i corpi.

### Perché l'energia potenziale è negativa?

La gravità è una forza attrattiva.

Per allontanare due corpi fino a distanza infinita è necessario fornire energia al sistema.

Scegliendo:

$$
U_g(\infty)=0
$$

l'energia potenziale a distanza finita è negativa.

### Dipendenza dalla distanza

$$
U_g=-\frac{GMm}{r}
$$

Se la distanza diminuisce, l'energia potenziale diventa più negativa.

Se la distanza aumenta, l'energia potenziale aumenta, avvicinandosi a zero.

**Importante:** un valore di energia potenziale più negativo corrisponde a un'energia potenziale minore.

---

## Energia potenziale gravitazionale vicino alla Terra

Vicino alla superficie terrestre, per variazioni di altezza piccole rispetto al raggio terrestre, si utilizza:

$$
\boxed{U_g=mgh}
$$

Questa espressione considera una scelta dello zero dell'energia potenziale a un'altezza di riferimento.

La variazione è:

$$
\boxed{\Delta U_g=mg(h_f-h_i)}
$$

### Quando utilizzare le due formule

| Situazione | Formula |
|---|---|
| Corpo sollevato vicino alla superficie terrestre | $U_g=mgh$ |
| Corpo che cade da un'altezza modesta | $\Delta U_g=mg\Delta h$ |
| Satellite lontano dalla superficie | $U_g=-GMm/r$ |
| Pianeta che orbita attorno al Sole | $U_g=-GMm/r$ |
| Confronto tra perielio e afelio | $U_g=-GMm/r$ |

**Attenzione:** la formula $mgh$ è un'approssimazione locale, mentre la formula gravitazionale universale considera la dipendenza dalla distanza.

---

## Lavoro della forza gravitazionale

La forza gravitazionale è conservativa.

Il suo lavoro è uguale all'opposto della variazione dell'energia potenziale gravitazionale.

$$
\boxed{L_g=-\Delta U_g}
$$

Pertanto:

$$
\boxed{L_g=U_{g,i}-U_{g,f}}
$$

### Corpo che si avvicina alla Terra

Durante la caduta:

- La distanza diminuisce.
- L'energia potenziale diminuisce.
- Il lavoro della gravità è positivo.

### Corpo che si allontana dalla Terra

Durante la risalita:

- La distanza aumenta.
- L'energia potenziale aumenta.
- Il lavoro della gravità è negativo.

### Esempio

Un corpo di massa 2 kg scende di 5 m vicino alla superficie terrestre.

Calcolare il lavoro della forza peso.

$$
L_g=mg(h_i-h_f)
$$

La diminuzione dell'altezza è 5 m:

$$
L_g=2\cdot9{,}81\cdot5
$$

$$
\boxed{L_g=98{,}1\ \text{J}}
$$

Il lavoro è positivo perché la gravità favorisce la discesa.

---

## Orbite dei pianeti

I pianeti si muovono attorno al Sole a causa dell'interazione gravitazionale.

In prima approssimazione, il movimento di un pianeta può essere descritto dalle **leggi di Keplero**.

Le orbite reali non sono generalmente circolari, ma ellittiche.

### Prima legge di Keplero

I pianeti descrivono orbite ellittiche, con il Sole situato in uno dei due fuochi.

### Seconda legge di Keplero

Il segmento che congiunge il Sole a un pianeta descrive aree uguali in intervalli di tempo uguali.

Una conseguenza è che:

- Il pianeta si muove più velocemente quando è vicino al Sole.
- Il pianeta si muove più lentamente quando è lontano dal Sole.

### Terza legge di Keplero

Il quadrato del periodo orbitale è proporzionale al cubo del semiasse maggiore dell'orbita, per corpi che orbitano attorno alla stessa massa dominante.

$$
\boxed{T^2\propto a^3}
$$

dove:

- $T$ = periodo orbitale.
- $a$ = semiasse maggiore dell'orbita.

Per due pianeti che orbitano attorno allo stesso corpo centrale:

$$
\boxed{\frac{T_1^2}{T_2^2}=\frac{a_1^3}{a_2^3}}
$$

### Significato fisico

I pianeti con orbite più grandi hanno generalmente periodi orbitali più lunghi.

Per l'esame è importante conoscere il significato delle tre leggi e saper applicare le formule più semplici.

---

## Perielio e afelio

In un'orbita ellittica si distinguono due punti importanti.

### Perielio

Il **perielio** è il punto dell'orbita in cui un pianeta si trova alla minima distanza dal Sole.

In questo punto:

- La distanza dal Sole è minima.
- La velocità orbitale è massima.
- L'energia potenziale gravitazionale è minima.

### Afelio

L'**afelio** è il punto dell'orbita in cui un pianeta si trova alla massima distanza dal Sole.

In questo punto:

- La distanza dal Sole è massima.
- La velocità orbitale è minima.
- L'energia potenziale gravitazionale è massima.

### Energia potenziale

La formula è:

$$
U_g=-\frac{GMm}{r}
$$

Al perielio, $r$ è minimo.

Quindi l'energia potenziale è più negativa.

All'afelio, $r$ è massimo.

Quindi l'energia potenziale è meno negativa.

**Attenzione:** le affermazioni sulla velocità riguardano il moto kepleriano attorno a un corpo centrale, trascurando perturbazioni rilevanti.

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 6

### Testo

Plutone si muove lungo un'orbita ellittica attorno al Sole.

Al perielio, cioè nel punto più vicino al Sole, quale valore assume la sua energia potenziale gravitazionale?

### Soluzione

L'energia potenziale gravitazionale è:

$$
U_g=-\frac{GMm}{r}
$$

Al perielio la distanza dal Sole è minima.

Di conseguenza il rapporto:

$$
\frac{GMm}{r}
$$

assume il valore massimo.

Poiché davanti compare un segno negativo, l'energia potenziale assume il valore più basso.

### Risposta ufficiale

$$
\boxed{\text{Energia potenziale minima}}
$$

### Principio da ricordare

Con energia potenziale gravitazionale nulla all'infinito:

- Distanza minore → energia potenziale minore.
- Distanza maggiore → energia potenziale maggiore.

Questo è uno dei quesiti teorici più semplici e importanti del materiale d'esame.

---

## Satelliti artificiali

Un satellite artificiale rimane in orbita attorno alla Terra grazie alla forza gravitazionale.

La gravità fornisce l'accelerazione centripeta necessaria a modificare continuamente la direzione della velocità.

Per un'orbita circolare:

$$
\boxed{F_g=F_c}
$$

La forza gravitazionale è:

$$
F_g=\frac{GM_Tm}{r^2}
$$

La forza centripeta richiesta è:

$$
F_c=\frac{mv^2}{r}
$$

Uguagliando:

$$
\frac{GM_Tm}{r^2}=\frac{mv^2}{r}
$$

Semplificando la massa del satellite:

$$
\boxed{v=\sqrt{\frac{GM_T}{r}}}
$$

dove:

- $v$ = velocità orbitale.
- $M_T$ = massa della Terra.
- $r$ = raggio dell'orbita misurato dal centro terrestre.

### Significato fisico

Nel modello di orbita circolare:

- La velocità orbitale non dipende dalla massa del satellite.
- Aumentando il raggio orbitale, la velocità diminuisce.
- Un satellite più vicino alla Terra deve muoversi più velocemente per mantenere un'orbita circolare.

---

## Accelerazione centripeta di un satellite

Per il moto circolare:

$$
\boxed{a_c=\frac{v^2}{r}}
$$

Quando l'accelerazione centripeta è nota, la velocità può essere calcolata direttamente:

$$
\boxed{v=\sqrt{a_cr}}
$$

Questa è la formula più conveniente quando l'esercizio fornisce il raggio dell'orbita e l'accelerazione centripeta.

### Periodo orbitale

Il periodo orbitale è il tempo necessario per completare un giro.

La distanza percorsa in un'orbita circolare è:

$$
2\pi r
$$

Quindi:

$$
\boxed{T=\frac{2\pi r}{v}}
$$

Sostituendo la velocità orbitale gravitazionale:

$$
\boxed{T=2\pi\sqrt{\frac{r^3}{GM_T}}}
$$

Per gli esercizi del professore è generalmente sufficiente utilizzare:

$$
v=\sqrt{a_cr}
$$

e successivamente:

$$
T=\frac{2\pi r}{v}
$$

---

## Esercizio ufficiale — Esame 29 gennaio 2024, domanda 13

### Testo

Un satellite artificiale in orbita circolare attorno alla Terra è soggetto a un'accelerazione centripeta di:

$$
a_c=9{,}8\ \text{m/s}^2
$$

Calcolare:

1. La velocità tangenziale.
2. Il periodo orbitale.

Approssimare il raggio dell'orbita a:

$$
r=6371\ \text{km}
$$

### Soluzione

**1. Convertire il raggio**

$$
r=6371\cdot1000
$$

$$
\boxed{r=6{,}371\cdot10^6\ \text{m}}
$$

**2. Calcolare la velocità tangenziale**

Dalla formula dell'accelerazione centripeta:

$$
a_c=\frac{v^2}{r}
$$

ricaviamo:

$$
v=\sqrt{a_cr}
$$

Sostituendo:

$$
v=\sqrt{9{,}8\cdot6{,}371\cdot10^6}
$$

$$
\boxed{v\approx7902\ \text{m/s}}
$$

Equivalentemente:

$$
\boxed{v\approx7{,}90\ \text{km/s}}
$$

**3. Calcolare il periodo orbitale**

$$
T=\frac{2\pi r}{v}
$$

Sostituendo:

$$
T=\frac{2\pi\cdot6{,}371\cdot10^6}{7902}
$$

$$
\boxed{T\approx5067\ \text{s}}
$$

**4. Convertire in minuti**

$$
T=\frac{5067}{60}
$$

$$
\boxed{T\approx84{,}4\ \text{min}}
$$

### Risultati

| Grandezza | Risultato |
|---|---|
| Velocità tangenziale | $7902\ \text{m/s}$ |
| Periodo orbitale | $5067\ \text{s}$ |
| Periodo in minuti | $84{,}4\ \text{min}$ |

### Principio da ricordare

Quando sono noti accelerazione centripeta e raggio:

$$
\boxed{v=\sqrt{a_cr}}
$$

Successivamente:

$$
\boxed{T=\frac{2\pi r}{v}}
$$

Si tratta di due applicazioni dirette delle formule del [[Moto circolare]].

*Nota: il compito del 2024 non riporta le soluzioni ufficiali. I risultati sono calcolati dai dati forniti. Il raggio approssimato a quello terrestre rappresenta un modello matematico ideale, non un'orbita praticabile sulla superficie.*

---

## Rotazione terrestre e accelerazione centripeta

La Terra ruota attorno al proprio asse.

Un oggetto situato sull'equatore partecipa a questa rotazione e percorre approssimativamente una circonferenza di raggio pari al raggio terrestre.

Pur essendo fermo rispetto al suolo, l'oggetto possiede un'accelerazione centripeta rispetto a un sistema di riferimento inerziale opportuno.

L'accelerazione vale:

$$
\boxed{a_c=\frac{4\pi^2R_T}{T^2}}
$$

dove:

- $R_T$ = raggio terrestre.
- $T$ = periodo di rotazione terrestre.

Questa accelerazione non coincide con l'accelerazione gravitazionale $g$.

### Differenza importante

L'accelerazione gravitazionale è prodotta dall'attrazione della Terra.

L'accelerazione centripeta dell'oggetto sull'equatore è quella necessaria per seguire la rotazione terrestre.

Le due accelerazioni hanno significati differenti.

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 1

### Testo

Calcolare il modulo dell'accelerazione centripeta, in m/s², dovuta alla rotazione della Terra per un oggetto situato sull'equatore.

Il raggio terrestre è:

$$
R_T=6370\ \text{km}
$$

### Soluzione

**1. Convertire il raggio**

$$
R_T=6370\cdot1000
$$

$$
\boxed{R_T=6{,}37\cdot10^6\ \text{m}}
$$

**2. Convertire il periodo**

Assumiamo una rotazione completa in 24 ore:

$$
T=24\cdot3600
$$

$$
\boxed{T=86400\ \text{s}}
$$

**3. Applicare la formula**

$$
a_c=\frac{4\pi^2R_T}{T^2}
$$

$$
a_c=\frac{4\pi^2\cdot6{,}37\cdot10^6}{86400^2}
$$

$$
\boxed{a_c\approx0{,}034\ \text{m/s}^2}
$$

### Risposta ufficiale

$$
\boxed{0{,}034\ \text{m/s}^2}
$$

### Osservazione

Il valore è molto inferiore all'accelerazione gravitazionale terrestre:

$$
g\approx9{,}81\ \text{m/s}^2
$$

**Principio da ricordare:** per calcolare l'accelerazione centripeta dovuta alla rotazione terrestre servono il raggio della traiettoria e il periodo di rotazione.

---

## Velocità di fuga — Richiamo

La **velocità di fuga** è la velocità minima che un corpo deve possedere per potersi allontanare indefinitamente da un corpo celeste, senza ulteriore propulsione e trascurando resistenze e perturbazioni.

Nel modello newtoniano, partendo a distanza $r$ dal centro di un corpo di massa $M$:

$$
\boxed{v_f=\sqrt{\frac{2GM}{r}}}
$$

### Significato fisico

- Aumentando la massa del corpo celeste, aumenta la velocità di fuga.
- Aumentando la distanza dal centro del corpo celeste, diminuisce la velocità di fuga.
- La velocità di fuga non dipende dalla massa dell'oggetto che si vuole far allontanare.

### Confronto con la velocità orbitale circolare

La velocità orbitale circolare è:

$$
v_o=\sqrt{\frac{GM}{r}}
$$

La velocità di fuga è:

$$
v_f=\sqrt{\frac{2GM}{r}}
$$

Pertanto:

$$
\boxed{v_f=\sqrt2\,v_o}
$$

Questa relazione vale confrontando le due velocità alla stessa distanza $r$.

**Priorità per l'esame:** argomento secondario rispetto agli esercizi sui satelliti, sulla gravità e sull'energia potenziale già presenti nelle prove.

---

## Come risolvere gli esercizi di gravitazione

### 1. Identificare il tipo di problema

Verificare se si parla di:

- Attrazione tra due masse.
- Accelerazione gravitazionale.
- Peso di un corpo.
- Variazione del raggio terrestre.
- Energia potenziale gravitazionale.
- Satellite in orbita.
- Perielio o afelio.

### 2. Individuare le grandezze note

Annotare masse, raggi, distanze, velocità, periodi ed eventuali densità.

### 3. Controllare le conversioni

Utilizzare:

- Masse in kg.
- Distanze in m.
- Tempi in s.
- Velocità in m/s.

### 4. Scegliere la formula più diretta

Per esempio:

**Accelerazione gravitazionale:**

$$
g=\frac{GM}{r^2}
$$

**Forza gravitazionale:**

$$
F_g=\frac{GMm}{r^2}
$$

**Energia potenziale:**

$$
U_g=-\frac{GMm}{r}
$$

**Velocità orbitale:**

$$
v=\sqrt{\frac{GM}{r}}
$$

**Periodo orbitale:**

$$
T=\frac{2\pi r}{v}
$$

### 5. Controllare le ipotesi

Verificare se il problema assume:

- Massa costante.
- Densità costante.
- Orbita circolare.
- Orbita ellittica.
- Accelerazione gravitazionale uniforme.
- Assenza di attrito o resistenza dell'aria.

Le ipotesi possono modificare sensibilmente la soluzione.

---

## Formule principali

### Gravitazione

| Grandezza | Formula |
|---|---|
| Forza gravitazionale | $F_g=Gm_1m_2/r^2$ |
| Costante gravitazionale | $G=6{,}674\cdot10^{-11}\ \text{N m}^2/\text{kg}^2$ |
| Campo gravitazionale | $g=GM/r^2$ |
| Peso | $P=mg$ |
| Gravità ad altezza $h$ | $g(h)=GM_T/(R_T+h)^2$ |
| Densità | $\rho=M/V$ |
| Volume della sfera | $V=\frac43\pi R^3$ |
| Massa sferica omogenea | $M=\frac43\pi\rho R^3$ |
| Gravità superficiale a densità costante | $g=\frac43\pi G\rho R$ |

### Energia gravitazionale

| Grandezza | Formula |
|---|---|
| Energia potenziale universale | $U_g=-GMm/r$ |
| Energia potenziale vicino alla Terra | $U_g=mgh$ |
| Variazione energia potenziale | $\Delta U_g=mg\Delta h$ |
| Lavoro gravitazionale | $L_g=-\Delta U_g$ |
| Velocità di fuga | $v_f=\sqrt{2GM/r}$ |

### Orbite circolari

| Grandezza | Formula |
|---|---|
| Accelerazione centripeta | $a_c=v^2/r$ |
| Forza centripeta | $F_c=mv^2/r$ |
| Velocità orbitale | $v=\sqrt{GM/r}$ |
| Velocità da accelerazione centripeta | $v=\sqrt{a_cr}$ |
| Periodo orbitale | $T=2\pi r/v$ |
| Periodo orbitale gravitazionale | $T=2\pi\sqrt{r^3/(GM)}$ |
| Terza legge di Keplero | $T^2\propto a^3$ |
| Accelerazione da rotazione terrestre | $a_c=4\pi^2R_T/T^2$ |

---

## Come riconoscere gli esercizi

| Situazione | Formula o principio |
|---|---|
| Due masse si attraggono | Legge di Newton |
| Si chiede la forza peso | $P=mg$ |
| Si chiede la gravità a una distanza $r$ | $g=GM/r^2$ |
| Il raggio terrestre cambia a massa costante | $g\propto1/R^2$ |
| Il raggio terrestre cambia a densità costante | $g\propto R$ |
| Si chiede l'energia potenziale di un pianeta | $U_g=-GMm/r$ |
| Si confrontano perielio e afelio | Energia potenziale e distanza |
| Si chiede la velocità di un satellite circolare | $v=\sqrt{GM/r}$ |
| Sono noti raggio orbitale e accelerazione centripeta | $v=\sqrt{a_cr}$ |
| Si chiede il periodo di un satellite circolare | $T=2\pi r/v$ |
| Si chiede l'accelerazione dovuta alla rotazione terrestre | $a_c=4\pi^2R_T/T^2$ |
| Si chiede la velocità di fuga | $v_f=\sqrt{2GM/r}$ |

---

## Domande teoriche da conoscere

**Che cosa afferma la legge di gravitazione universale?**

Due corpi dotati di massa si attraggono con una forza direttamente proporzionale al prodotto delle loro masse e inversamente proporzionale al quadrato della distanza.

**La forza gravitazionale è attrattiva o repulsiva?**

Nella teoria newtoniana è sempre attrattiva.

**Che cosa accade alla forza gravitazionale se la distanza raddoppia?**

Si riduce a un quarto.

**Che cosa accade alla forza gravitazionale se una massa raddoppia?**

La forza raddoppia, mantenendo costanti le altre grandezze.

**Qual è la differenza tra G e g?**

$G$ è la costante gravitazionale universale; $g$ è l'accelerazione gravitazionale locale.

**L'accelerazione gravitazionale dipende dalla massa del corpo che cade?**

No, nel modello di caduta libera in uno stesso campo gravitazionale, trascurando l'aria.

**Come cambia la gravità all'aumentare dell'altitudine?**

Diminuisce perché aumenta la distanza dal centro terrestre.

**Se il raggio della Terra diminuisce mantenendo costante la massa, cosa accade a g?**

Aumenta, perché $g\propto1/R^2$.

**Se il raggio della Terra diminuisce mantenendo costante la densità, cosa accade a g?**

Diminuisce proporzionalmente al raggio, perché cambia anche la massa terrestre.

**Che cosa rappresenta l'energia potenziale gravitazionale?**

È l'energia associata alla posizione relativa di due corpi che interagiscono gravitazionalmente.

**Perché l'energia potenziale gravitazionale universale è negativa?**

Perché viene scelta nulla all'infinito e la gravità è attrattiva.

**Dove è minima l'energia potenziale di un pianeta in un'orbita ellittica?**

Al perielio.

**Dove è massima l'energia potenziale di un pianeta in un'orbita ellittica?**

All'afelio.

**Perché un satellite rimane in orbita?**

Perché la forza gravitazionale fornisce l'accelerazione centripeta necessaria a mantenere la traiettoria orbitale.

**La velocità orbitale circolare dipende dalla massa del satellite?**

No, nel modello gravitazionale considerato.

**Che cosa accade alla velocità di un satellite circolare se aumenta il raggio orbitale?**

Diminuisce.

**Che cosa rappresenta il periodo orbitale?**

Il tempo necessario per completare un'orbita.

**Qual è la differenza tra accelerazione gravitazionale e accelerazione centripeta?**

La prima descrive il campo gravitazionale; la seconda descrive la variazione della direzione della velocità in un moto curvilineo.

**Che cosa afferma la seconda legge di Keplero?**

Il segmento che unisce il Sole a un pianeta descrive aree uguali in tempi uguali.

**Un pianeta si muove più velocemente al perielio o all'afelio?**

Al perielio.

---

## Errori frequenti

- Confondere la costante gravitazionale $G$ con l'accelerazione $g$.
- Dimenticare il quadrato della distanza nella legge di gravitazione.
- Utilizzare la distanza tra le superfici anziché quella tra i centri.
- Dimenticare di sommare il raggio terrestre all'altitudine di un satellite.
- Confondere massa e peso.
- Pensare che la gravità sia identica a qualsiasi altitudine.
- Utilizzare sempre $g=9{,}81\ \text{m/s}^2$ anche molto lontano dalla Terra.
- Confondere massa costante e densità costante.
- Dimenticare che la massa di una sfera a densità costante dipende dal cubo del raggio.
- Dimenticare il segno negativo dell'energia potenziale gravitazionale universale.
- Confondere energia potenziale minima con energia potenziale più vicina a zero.
- Pensare che la velocità di un pianeta sia costante lungo un'orbita ellittica.
- Applicare la formula della velocità orbitale circolare a un'orbita ellittica senza verificarne le condizioni.
- Dimenticare di convertire chilometri in metri.
- Dimenticare di convertire ore in secondi.
- Confondere raggio e diametro.
- Confondere velocità tangenziale e velocità angolare.
- Confondere accelerazione centripeta dovuta alla rotazione terrestre e accelerazione gravitazionale.

---

## Checklist di preparazione

- [ ] Conosco la legge di gravitazione universale.
- [ ] So calcolare la forza gravitazionale tra due corpi.
- [ ] So spiegare la dipendenza della forza dalla distanza.
- [ ] So distinguere la costante $G$ dall'accelerazione $g$.
- [ ] So calcolare l'accelerazione gravitazionale.
- [ ] So calcolare la forza peso.
- [ ] So calcolare la gravità a una determinata altitudine.
- [ ] So esprimere la massa terrestre in funzione di densità e volume.
- [ ] So distinguere i casi di massa costante e densità costante.
- [ ] So risolvere autonomamente l'esempio compito 1, domanda 9.
- [ ] Conosco l'energia potenziale gravitazionale.
- [ ] So spiegare il significato del segno negativo.
- [ ] So distinguere perielio e afelio.
- [ ] So rispondere autonomamente all'esame settembre 2026, domanda 6.
- [ ] Conosco il significato delle tre leggi di Keplero.
- [ ] So spiegare perché un satellite rimane in orbita.
- [ ] So calcolare la velocità tangenziale di un satellite circolare.
- [ ] So calcolare il periodo orbitale.
- [ ] So risolvere autonomamente l'esame gennaio 2024, domanda 13.
- [ ] So calcolare l'accelerazione centripeta dovuta alla rotazione terrestre.
- [ ] So risolvere autonomamente l'esame settembre 2026, domanda 1.
- [ ] So distinguere accelerazione gravitazionale e centripeta.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[Cinematica]]
- [[Moto circolare]]
- [[Principi della dinamica]]
- [[Lavoro energia e potenza]]
- [[Impulso e quantità di moto]]
