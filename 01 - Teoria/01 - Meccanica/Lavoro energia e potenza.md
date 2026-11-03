
# Lavoro, energia e potenza

## Introduzione

Il **lavoro**, l'**energia** e la **potenza** sono grandezze fondamentali della meccanica.

Permettono di descrivere come le forze trasferiscono energia ai corpi e come questa energia viene trasformata.

I concetti principali sono:

- **Lavoro:** misura l'energia trasferita da una forza durante uno spostamento.
- **Energia cinetica:** energia associata al movimento di un corpo.
- **Energia potenziale:** energia associata alla posizione o alla configurazione di un sistema.
- **Energia meccanica:** somma dell'energia cinetica e dell'energia potenziale.
- **Potenza:** misura la rapidità con cui viene compiuto un lavoro o trasferita energia.

Queste grandezze sono strettamente collegate ai [[Principi della dinamica|principi della dinamica]] e alla [[Cinematica]].

---

## Lavoro di una forza

Il **lavoro meccanico** misura l'energia trasferita da una forza a un corpo durante uno spostamento.

Per una forza costante, il lavoro è definito come:

$$
\boxed{L=Fs\cos\theta}
$$

dove:

- $L$ = lavoro (J).
- $F$ = modulo della forza (N).
- $s$ = modulo dello spostamento (m).
- $\theta$ = angolo tra la forza e lo spostamento.

L'unità di misura del lavoro nel Sistema Internazionale è il **joule (J)**.

$$
\boxed{1\ \text{J}=1\ \text{N}\cdot\text{m}}
$$

### Significato dell'angolo

Il lavoro dipende dalla componente della forza parallela allo spostamento.

Si distinguono tre casi fondamentali.

### Lavoro positivo

Se la forza ha una componente concorde con lo spostamento, il lavoro è positivo.

Nel caso di forza parallela e concorde:

$$
\theta=0^\circ
$$

Poiché:

$$
\cos0^\circ=1
$$

si ottiene:

$$
\boxed{L=Fs}
$$

**Esempio:** una forza che spinge un corpo nella direzione del suo movimento.

### Lavoro negativo

Se la forza ha una componente opposta allo spostamento, il lavoro è negativo.

Nel caso di forza parallela e opposta:

$$
\theta=180^\circ
$$

Poiché:

$$
\cos180^\circ=-1
$$

si ottiene:

$$
\boxed{L=-Fs}
$$

**Esempio:** la forza di attrito dinamico che si oppone allo scorrimento.

### Lavoro nullo

Se la forza è perpendicolare allo spostamento:

$$
\theta=90^\circ
$$

Poiché:

$$
\cos90^\circ=0
$$

il lavoro è nullo:

$$
\boxed{L=0}
$$

**Esempi:**
- La reazione normale di un piano durante lo scorrimento lungo la superficie.
- La forza centripeta durante un moto circolare.
- La forza magnetica su una particella carica in movimento.

### Riepilogo

| Angolo | Lavoro | Significato |
|---|---|---|
| $0^\circ$ | Positivo | Forza concorde allo spostamento |
| $90^\circ$ | Nullo | Forza perpendicolare |
| $180^\circ$ | Negativo | Forza opposta allo spostamento |

Per angoli intermedi bisogna utilizzare il valore del coseno.

---

## Lavoro totale

Quando su un corpo agiscono più forze, il lavoro totale è la somma dei lavori compiuti dalle singole forze.

$$
\boxed{L_{\text{tot}}=\sum_i L_i}
$$

Per esempio, un corpo che scivola lungo un piano inclinato può essere soggetto a:

- Forza peso.
- Reazione normale.
- Forza di attrito.

Il lavoro totale è:

$$
L_{\text{tot}}=L_P+L_N+L_f
$$

Poiché la reazione normale è perpendicolare allo spostamento lungo il piano:

$$
L_N=0
$$

quindi:

$$
\boxed{L_{\text{tot}}=L_P+L_f}
$$

### Esempio

Un corpo viene trascinato orizzontalmente per 5 m.

Agiscono:

- Una forza di 20 N concorde allo spostamento.
- Una forza di attrito di 5 N opposta allo spostamento.

Il lavoro della forza applicata è:

$$
L_F=20\cdot5=100\ \text{J}
$$

Il lavoro dell'attrito è:

$$
L_f=-5\cdot5=-25\ \text{J}
$$

Il lavoro totale vale:

$$
L_{\text{tot}}=100-25
$$

$$
\boxed{L_{\text{tot}}=75\ \text{J}}
$$

---

## Energia cinetica

L'**energia cinetica** è l'energia associata al movimento di un corpo.

Per un corpo di massa $m$ che si muove con velocità di modulo $v$:

$$
\boxed{K=\frac12mv^2}
$$

dove:

- $K$ = energia cinetica (J).
- $m$ = massa (kg).
- $v$ = velocità (m/s).

### Proprietà dell'energia cinetica

L'energia cinetica:

- Dipende dalla massa del corpo.
- Dipende dal quadrato della velocità.
- È sempre positiva o nulla.
- È nulla quando il corpo è fermo nel sistema di riferimento scelto.

### Dipendenza dalla massa

A parità di velocità:

$$
K\propto m
$$

Se la massa raddoppia, l'energia cinetica raddoppia.

### Dipendenza dalla velocità

A parità di massa:

$$
K\propto v^2
$$

Se la velocità raddoppia:

$$
K'=4K
$$

Se la velocità triplica:

$$
K'=9K
$$

**Da ricordare:** l'energia cinetica cresce con il quadrato della velocità, non linearmente.

### Ricavare la velocità

Dalla formula:

$$
K=\frac12mv^2
$$

si ottiene:

$$
\boxed{v=\sqrt{\frac{2K}{m}}}
$$

### Ricavare la massa

$$
\boxed{m=\frac{2K}{v^2}}
$$

---

## Esercizio ufficiale — Esempio compito 2, domanda 10

### Testo

Una motocicletta di massa:

$$
m=200\ \text{kg}
$$

si muove alla velocità di:

$$
v=36\ \text{km/h}
$$

Calcolare la sua energia cinetica.

### Soluzione

**1. Convertire la velocità**

Le formule del Sistema Internazionale richiedono la velocità in m/s.

$$
v=\frac{36}{3{,}6}
$$

$$
v=10\ \text{m/s}
$$

**2. Applicare la formula dell'energia cinetica**

$$
K=\frac12mv^2
$$

Sostituendo:

$$
K=\frac12\cdot200\cdot10^2
$$

$$
K=100\cdot100
$$

$$
\boxed{K=10000\ \text{J}}
$$

In notazione scientifica:

$$
\boxed{K=1\cdot10^4\ \text{J}}
$$

### Principio da ricordare

Prima di utilizzare una formula che coinvolge la velocità, verificare sempre che sia espressa in m/s.

---

## Teorema dell'energia cinetica

Il **teorema dell'energia cinetica**, detto anche teorema del lavoro e dell'energia, stabilisce che:

> Il lavoro totale compiuto dalle forze agenti su un corpo è uguale alla variazione della sua energia cinetica.

Matematicamente:

$$
\boxed{L_{\text{tot}}=\Delta K}
$$

Dove:

$$
\Delta K=K_f-K_i
$$

Quindi:

$$
\boxed{L_{\text{tot}}=\frac12mv_f^2-\frac12mv_i^2}
$$

### Significato fisico

Se:

$$
L_{\text{tot}}>0
$$

l'energia cinetica aumenta.

Se:

$$
L_{\text{tot}}<0
$$

l'energia cinetica diminuisce.

Se:

$$
L_{\text{tot}}=0
$$

l'energia cinetica rimane costante.

**Attenzione:** energia cinetica costante significa che il modulo della velocità è costante, non necessariamente che la direzione della velocità rimanga invariata.

### Esempio

Un corpo di massa 2 kg parte da fermo.

Su di esso viene compiuto un lavoro totale di 100 J.

Calcolare la velocità finale.

Dal teorema:

$$
L_{\text{tot}}=K_f-K_i
$$

Poiché il corpo parte da fermo:

$$
K_i=0
$$

Quindi:

$$
100=\frac12\cdot2\cdot v_f^2
$$

$$
100=v_f^2
$$

$$
\boxed{v_f=10\ \text{m/s}}
$$

Questo metodo permette di trovare la velocità finale senza conoscere il tempo impiegato.

---

## Energia potenziale

L'**energia potenziale** è un'energia associata alla posizione o alla configurazione di un sistema soggetto a forze conservative.

Le forme principali studiate nel corso sono:

- Energia potenziale gravitazionale.
- Energia potenziale elastica.
- Energia potenziale elettrica.

L'energia potenziale non dipende dalla velocità del corpo, ma dalla sua posizione o configurazione e dalla scelta del livello di riferimento.

---

## Energia potenziale gravitazionale vicino alla Terra

Vicino alla superficie terrestre, dove l'accelerazione gravitazionale può essere considerata costante, l'energia potenziale gravitazionale è:

$$
\boxed{U_g=mgh}
$$

dove:

- $U_g$ = energia potenziale gravitazionale (J).
- $m$ = massa (kg).
- $g$ = accelerazione gravitazionale (m/s²).
- $h$ = altezza rispetto al livello di riferimento (m).

### Significato fisico

A parità di massa:

- Se l'altezza aumenta, aumenta l'energia potenziale gravitazionale.
- Se l'altezza diminuisce, diminuisce l'energia potenziale gravitazionale.

La variazione di energia potenziale è:

$$
\boxed{\Delta U_g=mg(h_f-h_i)}
$$

L'energia potenziale può assumere valori positivi o negativi rispetto al livello di riferimento scelto.

### Esempio

Un corpo di massa 5 kg viene sollevato di 3 m.

Calcolare l'aumento dell'energia potenziale gravitazionale.

$$
\Delta U_g=mg\Delta h
$$

$$
\Delta U_g=5\cdot9{,}81\cdot3
$$

$$
\boxed{\Delta U_g=147{,}15\ \text{J}}
$$

---

## Lavoro della forza peso

La forza peso è una **forza conservativa**.

Il lavoro compiuto dalla gravità dipende soltanto dalla differenza tra posizione iniziale e finale, non dal percorso seguito.

Il lavoro della forza peso è:

$$
\boxed{L_P=-\Delta U_g}
$$

Quindi:

$$
\boxed{L_P=mg(h_i-h_f)}
$$

### Corpo che scende

Se un corpo scende:

$$
h_f<h_i
$$

L'energia potenziale diminuisce e il lavoro della forza peso è positivo.

### Corpo che sale

Se un corpo sale:

$$
h_f>h_i
$$

L'energia potenziale aumenta e il lavoro della forza peso è negativo.

### Esempio

Un corpo di massa 3 kg scende da un'altezza di 10 m a un'altezza di 4 m.

Calcolare il lavoro della forza peso.

$$
L_P=mg(h_i-h_f)
$$

$$
L_P=3\cdot9{,}81(10-4)
$$

$$
L_P=3\cdot9{,}81\cdot6
$$

$$
\boxed{L_P=176{,}58\ \text{J}}
$$

Il lavoro è positivo perché la forza peso favorisce lo spostamento verso il basso.

---

## Energia potenziale gravitazionale universale

Quando si studiano pianeti, satelliti e oggetti molto distanti dalla superficie terrestre, la formula $U_g=mgh$ può non essere appropriata.

In questi casi si utilizza l'espressione dell'energia potenziale gravitazionale associata alla legge di gravitazione universale:

$$
\boxed{U_g=-\frac{GMm}{r}}
$$

dove:

- $G$ = costante di gravitazione universale.
- $M$ = massa del corpo che genera il campo gravitazionale.
- $m$ = massa del corpo considerato.
- $r$ = distanza tra i centri dei due corpi.

La formula assume energia potenziale nulla a distanza infinita:

$$
U_g(\infty)=0
$$

### Significato del segno negativo

Poiché la forza gravitazionale è attrattiva, l'energia potenziale gravitazionale è negativa quando si sceglie come riferimento lo zero all'infinito.

Quando la distanza diminuisce:

$$
r\downarrow
$$

l'energia potenziale gravitazionale diventa più negativa.

Quando la distanza aumenta, l'energia potenziale si avvicina a zero.

### Perielio e afelio

In un'orbita ellittica:

- **Perielio:** punto di minima distanza dal Sole.
- **Afelio:** punto di massima distanza dal Sole.

Poiché:

$$
U_g=-\frac{GMm}{r}
$$

al perielio l'energia potenziale gravitazionale è minima.

All'afelio è massima, cioè meno negativa.

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 6

### Testo

Plutone si muove attorno al Sole lungo un'orbita ellittica.

Al perielio, cioè nel punto più vicino al Sole, quale valore assume la sua energia potenziale gravitazionale?

### Risposta corretta

**Il suo valore minimo.**

### Spiegazione

L'energia potenziale gravitazionale è:

$$
U_g=-\frac{GMm}{r}
$$

Al perielio la distanza $r$ è minima.

Di conseguenza, l'energia potenziale assume il valore più negativo.

$$
\boxed{U_g=\text{minima al perielio}}
$$

**Principio da ricordare:** per un'interazione gravitazionale attrattiva, con energia potenziale nulla all'infinito, avvicinare i due corpi diminuisce l'energia potenziale.

---

## Energia potenziale elastica

Una molla ideale deformata immagazzina energia potenziale elastica.

La sua espressione è:

$$
\boxed{U_e=\frac12kx^2}
$$

dove:

- $k$ = costante elastica della molla (N/m).
- $x$ = deformazione rispetto alla lunghezza naturale (m).

La variazione è:

$$
\boxed{\Delta U_e=\frac12k(x_f^2-x_i^2)}
$$

La forza elastica è conservativa.

Quindi:

$$
\boxed{L_e=-\Delta U_e}
$$

### Esempio

Una molla ideale di costante elastica:

$$
k=200\ \text{N/m}
$$

viene compressa di:

$$
x=0{,}10\ \text{m}
$$

Calcolare l'energia immagazzinata.

$$
U_e=\frac12kx^2
$$

$$
U_e=\frac12\cdot200\cdot0{,}10^2
$$

$$
\boxed{U_e=1\ \text{J}}
$$

Per ulteriori esempi si rimanda a [[Forza elastica]].

---

## Forze conservative e non conservative

Una **forza conservativa** è una forza il cui lavoro dipende soltanto dalle posizioni iniziale e finale, e non dal percorso seguito.

Per una forza conservativa:

$$
\boxed{L=-\Delta U}
$$

### Forze conservative

Esempi:

- Forza gravitazionale.
- Forza elastica ideale.
- Forza elettrostatica.

Per queste forze è possibile definire un'energia potenziale.

### Forze non conservative

Una forza non conservativa può compiere un lavoro che dipende dal percorso.

L'esempio più importante per il corso è l'**attrito dinamico**.

Nel modello di attrito radente:

$$
\boxed{L_f=-f_ds}
$$

Se:

$$
f_d=\mu_dN
$$

allora:

$$
\boxed{L_f=-\mu_dNs}
$$

Il lavoro dell'attrito dinamico è negativo perché la forza è opposta allo scorrimento relativo.

### Conseguenza fisica

L'attrito trasforma parte dell'energia meccanica in energia interna dei corpi e dell'ambiente.

L'energia complessiva non scompare, ma l'energia meccanica può diminuire.

---

## Energia meccanica

L'**energia meccanica** è la somma dell'energia cinetica e dell'energia potenziale.

$$
\boxed{E_m=K+U}
$$

Quando sono presenti sia energia potenziale gravitazionale sia elastica:

$$
\boxed{E_m=K+U_g+U_e}
$$

Vicino alla superficie terrestre:

$$
\boxed{E_m=\frac12mv^2+mgh+\frac12kx^2}
$$

Questa espressione è valida nel modello in cui le forme di energia meccanica considerate siano quelle indicate.

---

## Conservazione dell'energia meccanica

Se su un sistema agiscono soltanto forze conservative, oppure le forze non conservative compiono lavoro totale nullo, l'energia meccanica si conserva.

$$
\boxed{E_{m,i}=E_{m,f}}
$$

Nel caso di sola energia cinetica e potenziale gravitazionale:

$$
\boxed{K_i+U_{g,i}=K_f+U_{g,f}}
$$

Quindi:

$$
\boxed{\frac12mv_i^2+mgh_i=\frac12mv_f^2+mgh_f}
$$

### Significato fisico

Durante la caduta di un corpo:

- L'energia potenziale gravitazionale diminuisce.
- L'energia cinetica aumenta.

Durante la risalita:

- L'energia cinetica diminuisce.
- L'energia potenziale aumenta.

In assenza di dissipazione, la loro somma rimane costante.

---

## Esempio — Velocità di un corpo in caduta

Un corpo viene lasciato cadere da fermo da un'altezza di 5 m.

Trascurando l'attrito dell'aria, calcolare la velocità immediatamente prima di raggiungere il suolo.

### Energia iniziale

Il corpo è fermo:

$$
K_i=0
$$

Ponendo l'energia potenziale nulla al suolo:

$$
U_{g,i}=mgh
$$

### Energia finale

Al suolo:

$$
U_{g,f}=0
$$

L'energia è cinetica:

$$
K_f=\frac12mv^2
$$

### Conservazione dell'energia

$$
mgh=\frac12mv^2
$$

Semplificando la massa:

$$
gh=\frac12v^2
$$

Ricavando la velocità:

$$
\boxed{v=\sqrt{2gh}}
$$

Sostituendo:

$$
v=\sqrt{2\cdot9{,}81\cdot5}
$$

$$
\boxed{v\approx9{,}90\ \text{m/s}}
$$

**Osservazione:** nel modello senza attrito la velocità finale non dipende dalla massa del corpo.

---

## Energia meccanica in presenza di attrito

Quando agiscono forze non conservative che compiono lavoro, l'energia meccanica generalmente non si conserva.

La relazione diventa:

$$
\boxed{E_{m,f}-E_{m,i}=L_{\text{nc}}}
$$

dove:

$$
L_{\text{nc}}
$$

è il lavoro totale delle forze non conservative.

Se l'unica forza non conservativa è l'attrito dinamico:

$$
\boxed{E_{m,f}-E_{m,i}=L_f}
$$

Poiché il lavoro dell'attrito è negativo:

$$
E_{m,f}<E_{m,i}
$$

### Esempio

Un corpo di massa 2 kg scivola lungo una superficie orizzontale scabra.

Parte con velocità:

$$
v_0=5\ \text{m/s}
$$

e si arresta dopo aver percorso 10 m.

Calcolare il modulo della forza media resistente, supposta costante e opposta al movimento.

### Energia cinetica iniziale

$$
K_i=\frac12mv_0^2
$$

$$
K_i=\frac12\cdot2\cdot25
$$

$$
K_i=25\ \text{J}
$$

### Energia cinetica finale

Poiché il corpo si ferma:

$$
K_f=0
$$

### Lavoro totale

$$
L_{\text{tot}}=K_f-K_i
$$

$$
L_{\text{tot}}=-25\ \text{J}
$$

La forza resistente è opposta allo spostamento:

$$
L_{\text{tot}}=-Fs
$$

Quindi:

$$
-25=-F\cdot10
$$

$$
\boxed{F=2{,}5\ \text{N}}
$$

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 10

### Testo

Un blocco di massa 1,50 kg risale un piano inclinato di $53^\circ$ con velocità iniziale di $2{,}0\ \text{m/s}$.

Calcolare la distanza percorsa prima di fermarsi:

1. Senza attrito.
2. Con coefficiente di attrito dinamico $\mu_d=0{,}40$.

L'esercizio può essere risolto mediante il teorema dell'energia cinetica.

### Prima parte — Senza attrito

Durante la risalita la forza peso compie lavoro negativo:

$$
L_P=-mgd\sin\theta
$$

Al punto di arresto:

$$
K_f=0
$$

Il lavoro totale è:

$$
L_{\text{tot}}=K_f-K_i
$$

Quindi:

$$
-mgd\sin\theta=-\frac12mv_0^2
$$

Semplificando la massa e ricavando $d$:

$$
\boxed{d=\frac{v_0^2}{2g\sin\theta}}
$$

Sostituendo:

$$
d=\frac{2^2}{2\cdot9{,}81\cdot\sin53^\circ}
$$

$$
\boxed{d\approx0{,}255\ \text{m}=25{,}5\ \text{cm}}
$$

### Seconda parte — Con attrito

Durante la risalita lavorano negativamente sia la forza peso sia l'attrito.

$$
L_{\text{tot}}=L_P+L_f
$$

$$
L_{\text{tot}}=-mgd\sin\theta-\mu_dmgd\cos\theta
$$

Il corpo si arresta, quindi:

$$
-mgd(\sin\theta+\mu_d\cos\theta)=-\frac12mv_0^2
$$

Ricaviamo:

$$
\boxed{d=\frac{v_0^2}{2g(\sin\theta+\mu_d\cos\theta)}}
$$

Sostituendo:

$$
d=\frac{4}{2\cdot9{,}81(\sin53^\circ+0{,}40\cos53^\circ)}
$$

$$
\boxed{d\approx0{,}196\ \text{m}=19{,}6\ \text{cm}}
$$

### Risultati ufficiali

| Condizione | Distanza |
|---|---:|
| Senza attrito | 25,5 cm |
| Con attrito | 19,6 cm |

### Principio da ricordare

La presenza di attrito aumenta l'energia meccanica dissipata durante la risalita.

Il corpo si arresta quindi in uno spazio minore.

Questo esercizio è approfondito anche in [[Piano inclinato e attrito]].

---

## Potenza

La **potenza** misura la rapidità con cui viene compiuto un lavoro o trasferita energia.

La potenza media è:

$$
\boxed{\mathcal P_m=\frac{L}{\Delta t}}
$$

dove:

- $\mathcal P_m$ = potenza media (W).
- $L$ = lavoro (J).
- $\Delta t$ = intervallo di tempo (s).

L'unità di misura è il **watt (W)**.

$$
\boxed{1\ \text{W}=1\ \text{J/s}}
$$

### Significato fisico

Due macchine possono compiere lo stesso lavoro ma impiegare tempi differenti.

La macchina che compie il lavoro in meno tempo sviluppa una potenza media maggiore.

### Esempio

Una macchina compie un lavoro di 3000 J in 5 secondi.

$$
\mathcal P_m=\frac{L}{\Delta t}
$$

$$
\mathcal P_m=\frac{3000}{5}
$$

$$
\boxed{\mathcal P_m=600\ \text{W}}
$$

### Ricavare il lavoro

$$
\boxed{L=\mathcal P_m\Delta t}
$$

### Ricavare il tempo

$$
\boxed{\Delta t=\frac{L}{\mathcal P_m}}
$$

Queste relazioni valgono utilizzando la potenza media sull'intervallo considerato.

---

## Potenza e velocità

La potenza istantanea sviluppata da una forza è:

$$
\boxed{\mathcal P=\vec F\cdot\vec v}
$$

In termini di moduli:

$$
\boxed{\mathcal P=Fv\cos\theta}
$$

dove $\theta$ è l'angolo tra forza e velocità.

Se forza e velocità hanno la stessa direzione e lo stesso verso:

$$
\boxed{\mathcal P=Fv}
$$

### Esempio

Un corpo viene trascinato con velocità costante di 3 m/s mediante una forza di 100 N parallela al movimento.

La potenza sviluppata dalla forza è:

$$
\mathcal P=Fv
$$

$$
\mathcal P=100\cdot3
$$

$$
\boxed{\mathcal P=300\ \text{W}}
$$

### Potenza nulla

Se una forza è sempre perpendicolare alla velocità:

$$
\theta=90^\circ
$$

allora:

$$
\boxed{\mathcal P=0}
$$

Questo è il caso della forza centripeta e della forza magnetica su una particella carica.

---

## Esercizio ufficiale — Esempio compito 1, domanda 13

### Testo

La forza centripeta può compiere lavoro su un corpo?

### Risposta corretta

**No, mai, quando si considera la componente centripeta della forza.**

### Spiegazione

La forza centripeta è perpendicolare alla velocità istantanea.

La potenza è:

$$
\mathcal P=\vec F\cdot\vec v
$$

Poiché forza e velocità sono perpendicolari:

$$
\mathcal P=0
$$

Il lavoro totale della forza centripeta lungo il movimento è quindi nullo:

$$
\boxed{L_c=0}
$$

La forza centripeta modifica la direzione della velocità, ma non il suo modulo.

Per approfondire: [[Moto circolare]].

---

## Energia e potenza elettrica — Richiamo

Nei circuiti elettrici, la potenza dissipata da una resistenza può essere calcolata mediante:

$$
\boxed{\mathcal P=VI}
$$

Utilizzando la legge di Ohm:

$$
V=RI
$$

si ricavano:

$$
\boxed{\mathcal P=RI^2}
$$

e:

$$
\boxed{\mathcal P=\frac{V^2}{R}}
$$

dove:

- $V$ = tensione (V).
- $I$ = corrente (A).
- $R$ = resistenza ($\Omega$).

Queste formule sono particolarmente importanti per gli esercizi sui circuiti.

L'argomento sarà approfondito in [[Corrente e legge di Ohm]] e [[Circuiti elettrici]].

---

## Energia potenziale elettrica e lavoro — Richiamo

La forza elettrostatica è conservativa.

L'energia potenziale di una carica $q$ posta in un punto a potenziale elettrico $V$ è:

$$
\boxed{U_e=qV}
$$

Il lavoro compiuto dalla forza elettrica quando una carica si sposta da A a B è:

$$
\boxed{L_e=q(V_A-V_B)}
$$

### Esercizio ufficiale — Esempio compito 1, domanda 2

Una carica elettrica positiva:

$$
q=+8\ \text{C}
$$

si sposta da un punto A a potenziale:

$$
V_A=6\ \text{V}
$$

a un punto B a potenziale:

$$
V_B=2\ \text{V}
$$

Calcolare il lavoro compiuto dalla forza elettrica.

$$
L_e=q(V_A-V_B)
$$

$$
L_e=8(6-2)
$$

$$
\boxed{L_e=32\ \text{J}}
$$

Il lavoro è positivo perché una carica positiva si sposta verso un potenziale minore sotto l'azione della forza elettrica.

**Principio da ricordare:** il lavoro della forza elettrostatica dipende dalla differenza di potenziale tra i punti iniziale e finale.

Per approfondire: [[Potenziale elettrico]].

---

## Rendimento — Richiamo

Il **rendimento** misura il rapporto tra l'energia utile ottenuta e l'energia fornita a un sistema.

$$
\boxed{\eta=\frac{E_{\text{utile}}}{E_{\text{fornita}}}}
$$

Quando si confrontano potenze nelle stesse condizioni:

$$
\boxed{\eta=\frac{\mathcal P_{\text{utile}}}{\mathcal P_{\text{assorbita}}}}
$$

Il rendimento è adimensionale.

Per esprimerlo in percentuale:

$$
\boxed{\eta_{\%}=\eta\cdot100}
$$

Per esempio, un rendimento:

$$
\eta=0{,}75
$$

corrisponde al:

$$
\boxed{75\%}
$$

Nel caso di una macchina termica, il rendimento è il rapporto tra il lavoro utile prodotto e il calore assorbito dalla sorgente calda.

Questo argomento sarà approfondito in [[7. Macchine termiche e Carnot]].

---

## Conversioni importanti

| Grandezza | Conversione |
|---|---|
| Chilojoule | $1\ \text{kJ}=1000\ \text{J}$ |
| Kilowatt | $1\ \text{kW}=1000\ \text{W}$ |
| Watt | $1\ \text{W}=1\ \text{J/s}$ |
| Chilowattora | $1\ \text{kWh}=3{,}6\cdot10^6\ \text{J}$ |
| Caloria | $1\ \text{cal}\approx4{,}186\ \text{J}$ |
| Chilometri orari | $1\ \text{km/h}=1/3{,}6\ \text{m/s}$ |

**Attenzione:** il kilowattora (kWh) misura un'energia, non una potenza.

---

## Formule principali

### Lavoro

| Grandezza | Formula |
|---|---|
| Lavoro di una forza costante | $L=Fs\cos\theta$ |
| Lavoro totale | $L_{\text{tot}}=\sum_iL_i$ |
| Lavoro della forza peso | $L_P=mg(h_i-h_f)$ |
| Lavoro dell'attrito dinamico | $L_f=-f_ds$ |
| Lavoro della forza elastica | $L_e=-\Delta U_e$ |

### Energia

| Grandezza | Formula |
|---|---|
| Energia cinetica | $K=\frac12mv^2$ |
| Energia potenziale gravitazionale | $U_g=mgh$ |
| Energia potenziale gravitazionale universale | $U_g=-GMm/r$ |
| Energia potenziale elastica | $U_e=\frac12kx^2$ |
| Energia meccanica | $E_m=K+U$ |
| Conservazione dell'energia meccanica | $E_{m,i}=E_{m,f}$ |
| Teorema dell'energia cinetica | $L_{\text{tot}}=\Delta K$ |
| Lavoro non conservativo | $L_{\text{nc}}=\Delta E_m$ |

### Potenza

| Grandezza | Formula |
|---|---|
| Potenza media | $\mathcal P_m=L/\Delta t$ |
| Lavoro dalla potenza media | $L=\mathcal P_m\Delta t$ |
| Potenza istantanea di una forza | $\mathcal P=Fv\cos\theta$ |
| Potenza elettrica | $\mathcal P=VI$ |
| Potenza su una resistenza | $\mathcal P=RI^2$ |
| Potenza su una resistenza | $\mathcal P=V^2/R$ |

---

## Come riconoscere gli esercizi

| Situazione | Formula principale |
|---|---|
| Si chiede il lavoro di una forza | $L=Fs\cos\theta$ |
| Si chiede l'energia di un corpo in movimento | $K=\frac12mv^2$ |
| Si chiede la variazione di velocità dovuta a un lavoro | $L_{\text{tot}}=\Delta K$ |
| Un corpo viene sollevato | $\Delta U_g=mg\Delta h$ |
| Un corpo cade senza attrito | Conservazione dell'energia |
| Un corpo risale un piano inclinato | Lavoro della forza peso |
| Un corpo risale con attrito | $L_{\text{tot}}=L_P+L_f$ |
| Una molla viene compressa o allungata | $U_e=\frac12kx^2$ |
| Si chiede la potenza sviluppata | $\mathcal P_m=L/\Delta t$ |
| Sono note forza e velocità concordi | $\mathcal P=Fv$ |
| Si chiede il lavoro della forza centripeta | $L_c=0$ |
| Si chiede l'energia gravitazionale di un pianeta | $U_g=-GMm/r$ |
| Si chiede il rendimento | $\eta=E_{\text{utile}}/E_{\text{fornita}}$ |

---

## Domande teoriche da conoscere

**Che cos'è il lavoro di una forza?**

È una grandezza che misura l'energia trasferita da una forza durante uno spostamento.

**Quando il lavoro è positivo?**

Quando la forza possiede una componente concorde con lo spostamento.

**Quando il lavoro è negativo?**

Quando la forza possiede una componente opposta allo spostamento.

**Quando il lavoro è nullo?**

Quando la forza è perpendicolare allo spostamento oppure quando non avviene alcuno spostamento.

**Che cos'è l'energia cinetica?**

È l'energia associata al movimento di un corpo.

**Se la velocità raddoppia, cosa accade all'energia cinetica?**

Quadruplica.

**Che cosa afferma il teorema dell'energia cinetica?**

Il lavoro totale delle forze agenti su un corpo è uguale alla variazione della sua energia cinetica.

**Che cos'è l'energia potenziale gravitazionale?**

È l'energia associata alla posizione relativa di corpi che interagiscono gravitazionalmente.

**Quando aumenta l'energia potenziale gravitazionale vicino alla Terra?**

Quando aumenta l'altezza rispetto al livello di riferimento.

**Qual è la differenza tra forza conservativa e non conservativa?**

Il lavoro di una forza conservativa dipende soltanto dalle posizioni iniziale e finale, mentre quello di una forza non conservativa può dipendere dal percorso.

**Quali sono esempi di forze conservative?**

Forza gravitazionale, forza elastica ideale e forza elettrostatica.

**L'attrito dinamico è una forza conservativa?**

No. Dissipa energia meccanica, trasformandola prevalentemente in energia interna.

**Quando si conserva l'energia meccanica?**

Quando il lavoro totale delle forze non conservative è nullo.

**La forza centripeta compie lavoro?**

No. È perpendicolare alla velocità istantanea.

**Una forza magnetica può modificare l'energia cinetica di una carica?**

La sola forza magnetica non compie lavoro e quindi non modifica l'energia cinetica della particella.

**Che cos'è la potenza?**

È la rapidità con cui viene compiuto un lavoro o trasferita energia.

**Qual è la differenza tra lavoro e potenza?**

Il lavoro misura l'energia trasferita, mentre la potenza misura l'energia trasferita nell'unità di tempo.

**In quale punto dell'orbita di Plutone l'energia potenziale gravitazionale è minima?**

Al perielio, perché la distanza dal Sole è minima.

---

## Errori frequenti

- Confondere lavoro ed energia con la potenza.
- Dimenticare il coseno dell'angolo nel calcolo del lavoro.
- Confondere lavoro positivo e negativo.
- Pensare che ogni forza agente su un corpo compia lavoro.
- Dimenticare che una forza perpendicolare allo spostamento compie lavoro nullo.
- Utilizzare km/h senza convertirli in m/s.
- Dimenticare il quadrato della velocità nell'energia cinetica.
- Confondere energia cinetica e potenziale.
- Utilizzare sempre $mgh$ anche nei problemi gravitazionali su scale astronomiche.
- Dimenticare il segno negativo dell'energia potenziale gravitazionale universale.
- Considerare conservata l'energia meccanica anche quando l'attrito compie lavoro.
- Confondere l'energia dissipata positiva con il lavoro negativo dell'attrito.
- Dimenticare l'energia potenziale elastica nei sistemi con molle.
- Confondere watt e joule.
- Pensare che il kilowattora sia un'unità di potenza.
- Dimenticare di convertire le calorie in joule negli esercizi che mescolano unità termiche e meccaniche.
- Confondere potenziale elettrico ed energia potenziale elettrica.
- Pensare che rendimento e potenza siano la stessa grandezza.

---

## Checklist di preparazione

- [ ] So definire il lavoro di una forza.
- [ ] So calcolare il lavoro di una forza costante.
- [ ] So distinguere lavoro positivo, negativo e nullo.
- [ ] So calcolare il lavoro totale di più forze.
- [ ] So calcolare l'energia cinetica.
- [ ] So ricavare la velocità dall'energia cinetica.
- [ ] So applicare il teorema dell'energia cinetica.
- [ ] So calcolare l'energia potenziale gravitazionale.
- [ ] So calcolare il lavoro della forza peso.
- [ ] So distinguere forze conservative e non conservative.
- [ ] So calcolare l'energia potenziale elastica.
- [ ] So applicare la conservazione dell'energia meccanica.
- [ ] So risolvere problemi con attrito utilizzando il lavoro.
- [ ] So calcolare la potenza media.
- [ ] So calcolare la potenza a partire da forza e velocità.
- [ ] So spiegare perché la forza centripeta non compie lavoro.
- [ ] So riconoscere il valore minimo dell'energia potenziale gravitazionale in un'orbita ellittica.
- [ ] So risolvere autonomamente l'esempio compito 2, domanda 10.
- [ ] So risolvere autonomamente l'esempio compito 1, domanda 13.
- [ ] So risolvere autonomamente l'esame 10 settembre 2026, domanda 6.
- [ ] So risolvere autonomamente l'esame 10 settembre 2026, domanda 10.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[Cinematica]]
- [[Moto circolare]]
- [[Principi della dinamica]]
- [[Equilibrio delle forze]]
- [[Piano inclinato e attrito]]
- [[Forza elastica]]
- [[Impulso e quantità di moto]]
- [[Gravitazione]]
- [[Potenziale elettrico]]
- [[Corrente e legge di Ohm]]
- [[Circuiti elettrici]]
- [[7. Macchine termiche e Carnot]]
