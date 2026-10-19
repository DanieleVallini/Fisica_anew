
# Cinematica

## Introduzione

La **cinematica** è la branca della meccanica che descrive il movimento dei corpi senza studiare le cause che lo producono, cioè le forze.

Per descrivere un moto è necessario stabilire un **sistema di riferimento**, rispetto al quale misurare posizione, spostamento, velocità e accelerazione.

Un corpo è in movimento quando la sua posizione cambia nel tempo rispetto al sistema di riferimento scelto.

---

## Grandezze fondamentali

### Posizione e spostamento

La **posizione** indica dove si trova un corpo rispetto a un sistema di riferimento.

Nel moto unidimensionale viene rappresentata dalla coordinata $x(t)$.

Lo **spostamento** è la variazione della posizione tra due istanti:

$$
\Delta x = x_f-x_i
$$

Lo spostamento è una grandezza vettoriale: possiede modulo, direzione e verso.

**Attenzione:** spostamento e distanza percorsa non sono la stessa cosa.

- **Distanza percorsa:** lunghezza complessiva del percorso effettuato.
- **Spostamento:** differenza tra posizione finale e iniziale.

Ad esempio, se un corpo percorre 10 m verso destra e successivamente 10 m verso sinistra:

- Distanza percorsa: 20 m.
- Spostamento: 0 m.

### Velocità

La **velocità** descrive la rapidità e il verso con cui cambia la posizione di un corpo.

La velocità media è:

$$
\boxed{v_m=\frac{\Delta x}{\Delta t}}
$$

dove:
- $\Delta x$ = spostamento (m).
- $\Delta t$ = intervallo di tempo (s).
- $v_m$ = velocità media (m/s).

La **velocità istantanea** è la velocità posseduta dal corpo in un determinato istante.

La **velocità scalare media** è invece il rapporto tra distanza complessivamente percorsa e tempo impiegato.

$$
v_{\text{scalare media}}=\frac{\text{distanza percorsa}}{\Delta t}
$$

La distinzione è importante: un corpo può avere velocità media nulla pur avendo percorso una distanza diversa da zero.

### Accelerazione

L'**accelerazione** descrive come cambia la velocità nel tempo.

L'accelerazione media è:

$$
\boxed{a_m=\frac{\Delta v}{\Delta t}}
$$

dove:
- $\Delta v$ = variazione della velocità (m/s).
- $\Delta t$ = intervallo di tempo (s).
- $a_m$ = accelerazione media (m/s²).

Un'accelerazione diversa da zero indica che la velocità sta cambiando in modulo, direzione oppure verso.

Nel moto rettilineo:
- Se velocità e accelerazione hanno lo stesso segno, il corpo aumenta la propria rapidità.
- Se hanno segni opposti, il corpo rallenta.
- Se l'accelerazione è nulla, la velocità rimane costante.

**Importante:** un'accelerazione negativa non significa necessariamente che il corpo stia rallentando. Il suo significato dipende dal verso della velocità.

---

## Moto rettilineo uniforme (MRU)

Il **moto rettilineo uniforme** è caratterizzato da:

- Traiettoria rettilinea.
- Velocità costante.
- Accelerazione nulla.

La legge oraria è:

$$
\boxed{x(t)=x_0+vt}
$$

dove:
- $x_0$ = posizione iniziale.
- $v$ = velocità costante.
- $t$ = tempo trascorso dall'istante iniziale.

Se il corpo parte dall'origine ($x_0=0$):

$$
x=vt
$$

### Quando utilizzare questa formula

Quando il problema descrive un corpo che si muove in linea retta mantenendo una velocità costante.

Se la velocità cambia, non si può utilizzare direttamente questa legge con una singola velocità istantanea.

---

## Moto rettilineo uniformemente accelerato (MRUA)

Il **moto rettilineo uniformemente accelerato** è caratterizzato da un'accelerazione costante.

La velocità cambia della stessa quantità in intervalli di tempo uguali.

### Legge della velocità

$$
\boxed{v(t)=v_0+at}
$$

dove:
- $v_0$ = velocità iniziale.
- $a$ = accelerazione costante.
- $t$ = tempo trascorso.

### Legge oraria

$$
\boxed{x(t)=x_0+v_0t+\frac{1}{2}at^2}
$$

Permette di calcolare la posizione del corpo in funzione del tempo.

### Relazione senza il tempo

$$
\boxed{v^2=v_0^2+2a\Delta x}
$$

Questa relazione è particolarmente utile quando il problema non fornisce il tempo e non lo richiede.

### Come scegliere la formula

| Dati disponibili | Formula |
|---|---|
| Velocità iniziale, accelerazione e tempo | $v=v_0+at$ |
| Posizione iniziale, velocità iniziale, accelerazione e tempo | $x=x_0+v_0t+\frac12at^2$ |
| Velocità iniziale, accelerazione e spostamento | $v^2=v_0^2+2a\Delta x$ |

### Esempio

Un corpo parte da fermo e accelera costantemente a $2\ \text{m/s}^2$ per 5 secondi.

**Velocità finale:**

$$
v=0+2\cdot5=\boxed{10\ \text{m/s}}
$$

**Spazio percorso:**

$$
\Delta x=0+\frac12\cdot2\cdot5^2
$$

$$
\boxed{\Delta x=25\ \text{m}}
$$


![[Infografica di cinematica_ concetti e grafici.png]]
---
![[Infografica didattica sulla cinematica in italiano.png]]
## Caduta libera

La **caduta libera** è il moto di un corpo soggetto esclusivamente alla forza di gravità, trascurando la resistenza dell'aria.

Vicino alla superficie terrestre, l'accelerazione gravitazionale è approssimativamente costante:

$$
\boxed{g=9{,}81\ \text{m/s}^2}
$$

Si tratta quindi di un particolare moto uniformemente accelerato.

Scegliendo l'asse verticale positivo verso l'alto:

$$
\boxed{v_y=v_{0y}-gt}
$$

$$
\boxed{y=y_0+v_{0y}t-\frac12gt^2}
$$

### Corpo lasciato cadere da fermo

Se il corpo viene lasciato cadere, la sua velocità iniziale è nulla.

Indicando con $h$ la distanza percorsa verso il basso:

$$
\boxed{h=\frac12gt^2}
$$

$$
\boxed{v=gt}
$$

$$
\boxed{t=\sqrt{\frac{2h}{g}}}
$$

Queste formule valgono per un corpo lasciato cadere da fermo, con accelerazione gravitazionale costante e attrito dell'aria trascurabile.

---

## Lancio verticale

Nel lancio verticale verso l'alto, il corpo possiede una velocità iniziale positiva, mentre l'accelerazione gravitazionale è diretta verso il basso.

La velocità diminuisce progressivamente fino ad annullarsi nel punto più alto della traiettoria.

**Nel punto di altezza massima:**

$$
\boxed{v_y=0}
$$

### Tempo per raggiungere l'altezza massima

$$
\boxed{t_{\max}=\frac{v_0}{g}}
$$

### Altezza massima rispetto al punto di lancio

$$
\boxed{\Delta h_{\max}=\frac{v_0^2}{2g}}
$$

### Tempo totale di volo

Se il corpo ritorna alla stessa quota dalla quale è stato lanciato:

$$
\boxed{T=\frac{2v_0}{g}}
$$

Queste relazioni assumono che l'accelerazione gravitazionale sia costante e che la resistenza dell'aria sia trascurabile.

---

## Moto in due e tre dimensioni

Quando un corpo si muove nello spazio, posizione, velocità e accelerazione sono grandezze vettoriali.

La posizione può essere rappresentata mediante le coordinate:

$$
\vec r=(x,y,z)
$$

La velocità mediante:

$$
\vec v=(v_x,v_y,v_z)
$$

Il modulo della velocità è:

$$
\boxed{|\vec v|=\sqrt{v_x^2+v_y^2+v_z^2}}
$$

Nel moto piano, la componente $z$ è nulla e quindi:

$$
\boxed{|\vec v|=\sqrt{v_x^2+v_y^2}}
$$

### Scomposizione della velocità

Se un corpo possiede una velocità iniziale $v_0$ inclinata di un angolo $\theta$ rispetto all'orizzontale:

$$
\boxed{v_{0x}=v_0\cos\theta}
$$

$$
\boxed{v_{0y}=v_0\sin\theta}
$$

Questa scomposizione è fondamentale nei problemi di lancio obliquo.

### Indipendenza dei moti

Quando un corpo è soggetto a un'accelerazione costante, il suo movimento può essere studiato separatamente lungo i diversi assi.

Per esempio:
- Il movimento orizzontale dipende dall'accelerazione orizzontale.
- Il movimento verticale dipende dall'accelerazione verticale.

Nel moto parabolico senza attrito, le due componenti seguono leggi differenti ma condividono lo stesso tempo.

---

## Moto parabolico

Il **moto parabolico** descrive il movimento di un corpo lanciato con una velocità iniziale inclinata rispetto all'orizzontale e soggetto soltanto alla gravità.

È la combinazione di due moti indipendenti:

1. **Moto orizzontale:** rettilineo uniforme.
2. **Moto verticale:** uniformemente accelerato.

### Componente orizzontale

In assenza di attrito dell'aria, l'accelerazione orizzontale è nulla.

$$
\boxed{v_x=v_0\cos\theta}
$$

La posizione orizzontale è:

$$
\boxed{x=x_0+v_0\cos\theta\cdot t}
$$

La velocità orizzontale rimane costante durante tutto il volo.

### Componente verticale

La velocità verticale varia per effetto della gravità:

$$
\boxed{v_y=v_0\sin\theta-gt}
$$

La posizione verticale è:

$$
\boxed{y=y_0+v_0\sin\theta\cdot t-\frac12gt^2}
$$

### Punto più alto della traiettoria

Al culmine della traiettoria:

$$
\boxed{v_y=0}
$$

Tuttavia la velocità totale non è necessariamente nulla: rimane la componente orizzontale.

$$
\boxed{v=v_x=v_0\cos\theta}
$$

### Tempo per raggiungere il culmine

$$
\boxed{t_{\max}=\frac{v_0\sin\theta}{g}}
$$

### Altezza massima

Rispetto alla quota del punto di lancio:

$$
\boxed{\Delta h_{\max}=\frac{v_0^2\sin^2\theta}{2g}}
$$

### Tempo totale di volo

Se il corpo atterra alla stessa altezza dalla quale è stato lanciato:

$$
\boxed{T=\frac{2v_0\sin\theta}{g}}
$$

### Gittata

La **gittata** è la distanza orizzontale percorsa tra lancio e atterraggio.

Se il lancio e l'atterraggio avvengono alla stessa quota:

$$
\boxed{G=\frac{v_0^2\sin(2\theta)}{g}}
$$

In assenza di attrito dell'aria, a parità di velocità iniziale, la gittata massima si ottiene con un angolo di $45^\circ$.

**Attenzione:** le formule semplificate per tempo totale e gittata non valgono direttamente quando il corpo atterra a una quota diversa da quella iniziale. In quel caso bisogna utilizzare le equazioni oraria orizzontale e verticale.

---

## Composizione dei moti e velocità relativa

Il moto osservato dipende dal sistema di riferimento.

Se due corpi A e B si muovono lungo lo stesso asse, la velocità di A rispetto a B è:

$$
\boxed{v_{A/B}=v_A-v_B}
$$

Nel caso generale, la relazione è vettoriale:

$$
\boxed{\vec v_{A/B}=\vec v_A-\vec v_B}
$$

Ad esempio, due auto che viaggiano nella stessa direzione rispettivamente a 80 km/h e 60 km/h hanno una velocità relativa di 20 km/h.

Se viaggiano in versi opposti, scegliendo correttamente i segni delle velocità, il modulo della velocità relativa è 140 km/h.

---

## Grafici del moto

I grafici possono aiutare a interpretare il tipo di movimento.

| Grafico | Significato |
|---|---|
| Posizione-tempo | La pendenza rappresenta la velocità |
| Velocità-tempo | La pendenza rappresenta l'accelerazione |
| Accelerazione-tempo | Mostra come cambia l'accelerazione nel tempo |

Nel moto rettilineo uniforme:
- Il grafico posizione-tempo è una retta.
- Il grafico velocità-tempo è una linea orizzontale.

Nel moto uniformemente accelerato:
- Il grafico posizione-tempo è una parabola.
- Il grafico velocità-tempo è una retta.
- Il grafico accelerazione-tempo è una linea orizzontale.

---

## Conversioni delle unità di misura

Le formule vanno applicate utilizzando unità di misura coerenti, preferibilmente quelle del Sistema Internazionale.

| Grandezza | Conversione |
|---|---|
| Chilometri in metri | $1\ \text{km}=1000\ \text{m}$ |
| Centimetri in metri | $1\ \text{cm}=0{,}01\ \text{m}$ |
| Millisecondi in secondi | $1\ \text{ms}=10^{-3}\ \text{s}$ |
| km/h in m/s | Dividere per 3,6 |
| m/s in km/h | Moltiplicare per 3,6 |

Esempi:

$$
72\ \text{km/h}=\frac{72}{3{,}6}=20\ \text{m/s}
$$

$$
15\ \text{m/s}=15\cdot3{,}6=54\ \text{km/h}
$$

---

## Esercizi usciti negli esami

### Esempio compito 1 — Domanda 5

**Testo**

Un sasso è lanciato con un angolo di $60^\circ$ rispetto all'orizzontale e una velocità iniziale di $6\ \text{m/s}$.

Calcolare il modulo della velocità al culmine della traiettoria.

**Soluzione**

Nel punto più alto della traiettoria, la componente verticale della velocità è nulla:

$$
v_y=0
$$

La componente orizzontale rimane costante:

$$
v_x=v_0\cos\theta
$$

Sostituendo:

$$
v_x=6\cos60^\circ
$$

$$
\boxed{v_x=3\ \text{m/s}}
$$

**Principio da ricordare:** al culmine di un moto parabolico, la velocità verticale è nulla, ma il corpo continua a muoversi orizzontalmente.

### Esame 29 gennaio 2024 — Domanda 3

**Testo**

Se la velocità media di un oggetto in un certo intervallo di tempo è zero, cosa si può dire dello spostamento dell'oggetto in quell'intervallo di tempo?

**Risposta corretta:** lo spostamento complessivo è nullo.

**Spiegazione**

La velocità media è definita da:

$$
v_m=\frac{\Delta x}{\Delta t}
$$

Se $v_m=0$ e l'intervallo di tempo è diverso da zero:

$$
\boxed{\Delta x=0}
$$

Il corpo potrebbe comunque essersi mosso ed essere ritornato nella posizione iniziale.

---

## Domande teoriche da conoscere

**Qual è la differenza tra distanza e spostamento?**

La distanza è la lunghezza totale del percorso, mentre lo spostamento è il vettore che collega la posizione iniziale a quella finale.

**Un corpo può avere velocità nulla e accelerazione diversa da zero?**

Sì. Un esempio è il punto più alto di un lancio verticale: la velocità istantanea è nulla, ma l'accelerazione gravitazionale continua ad agire.

**Un corpo può avere accelerazione nulla e velocità diversa da zero?**

Sì. Accade nel moto rettilineo uniforme.

**Nel moto parabolico, quale componente della velocità rimane costante?**

La componente orizzontale, purché la resistenza dell'aria sia trascurabile.

**Nel moto parabolico, la velocità al culmine è sempre nulla?**

No. Si annulla soltanto la componente verticale.

**L'accelerazione di gravità dipende dalla massa del corpo?**

Nel modello di caduta libera, trascurando la resistenza dell'aria, tutti i corpi in uno stesso luogo subiscono la medesima accelerazione gravitazionale.

**Che differenza esiste tra MRU e MRUA?**

Nel MRU la velocità è costante e l'accelerazione nulla. Nel MRUA l'accelerazione è costante e la velocità varia nel tempo.

---

## Errori frequenti

- Confondere distanza percorsa e spostamento.
- Confondere velocità media e velocità scalare media.
- Utilizzare km/h senza convertirli in m/s.
- Dimenticare il segno dell'accelerazione gravitazionale.
- Applicare le formule del moto uniforme a un corpo accelerato.
- Pensare che un'accelerazione negativa implichi sempre un rallentamento.
- Confondere seno e coseno nella scomposizione della velocità.
- Considerare nulla tutta la velocità al culmine di un moto parabolico.
- Applicare la formula della gittata a lanci con quote iniziale e finale diverse.

---

## Checklist di preparazione

- [ ] Conosco la differenza tra posizione, spostamento e distanza.
- [ ] So distinguere velocità media e velocità istantanea.
- [ ] So calcolare un'accelerazione media.
- [ ] So riconoscere MRU e MRUA.
- [ ] So scegliere la formula corretta del MRUA.
- [ ] So risolvere problemi elementari di caduta libera.
- [ ] So calcolare tempo e altezza massima di un lancio verticale.
- [ ] So scomporre un vettore velocità nelle sue componenti.
- [ ] So risolvere problemi elementari di moto parabolico.
- [ ] So riconoscere quando una formula richiede particolari condizioni.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.
- [ ] So risolvere autonomamente gli esercizi d'esame collegati.

---

## Collegamenti

- [[2 - Moto circolare]]
- [[3 - Principi della dinamica]]
- [[Equilibrio delle forze]]
- [[Lavoro energia e potenza]]
- [[Gravitazione]]

**Argomenti trattati separatamente:**
- Il moto circolare uniforme e l'accelerazione centripeta saranno approfonditi in [[2 - Moto circolare]].
- Il moto armonico sarà trattato in [[Moto armonico]].
