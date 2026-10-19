
# Forza elastica

## Introduzione

La **forza elastica** è una forza che si manifesta quando un corpo elastico viene deformato rispetto alla sua configurazione di equilibrio.

Un corpo elastico tende a recuperare la propria forma originale quando viene rimossa la causa della deformazione.

L'esempio più semplice è una **molla ideale**, che può essere:

- **Allungata:** la sua lunghezza aumenta rispetto a quella naturale.
- **Compressa:** la sua lunghezza diminuisce rispetto a quella naturale.

In entrambi i casi la molla esercita una forza che tende a riportarla alla lunghezza naturale, detta **forza di richiamo**.

Il comportamento di una molla ideale è descritto dalla **legge di Hooke**.

---

## Deformazione di una molla

Consideriamo una molla di lunghezza naturale $l_0$.

Quando viene applicata una forza, la sua lunghezza diventa $l$.

La deformazione è:

$$
\boxed{x=l-l_0}
$$

dove:

- $x$ = deformazione (m).
- $l$ = lunghezza attuale (m).
- $l_0$ = lunghezza naturale (m).

### Allungamento

Se la molla viene allungata:

$$
l>l_0
$$

quindi:

$$
x>0
$$

### Compressione

Se la molla viene compressa:

$$
l<l_0
$$

quindi:

$$
x<0
$$

### Molla non deformata

Se la molla si trova alla lunghezza naturale:

$$
l=l_0
$$

allora:

$$
\boxed{x=0}
$$

La forza elastica di una molla ideale è nulla quando la deformazione è nulla.

---

## Legge di Hooke

La **legge di Hooke** stabilisce che la forza elastica esercitata da una molla ideale è proporzionale alla sua deformazione ed è diretta in verso opposto a essa.

$$
\boxed{F_e=-kx}
$$

dove:

- $F_e$ = componente della forza elastica (N).
- $k$ = costante elastica della molla (N/m).
- $x$ = deformazione rispetto alla lunghezza naturale (m).

Il segno negativo indica che la forza elastica è una **forza di richiamo**.

### Significato del segno negativo

Se la molla viene allungata verso destra:

$$
x>0
$$

la forza elastica è diretta verso sinistra:

$$
F_e<0
$$

Se invece la molla viene compressa verso sinistra:

$$
x<0
$$

la forza elastica è diretta verso destra:

$$
F_e>0
$$

In entrambi i casi la forza elastica tende a riportare la molla alla sua lunghezza naturale.

### Modulo della forza elastica

Quando un esercizio richiede solamente il modulo della forza, si utilizza:

$$
\boxed{|F_e|=k|x|}
$$

Se indichiamo con $\Delta l=|x|$ il valore positivo dell'allungamento o della compressione:

$$
\boxed{F=k\Delta l}
$$

Questa è la forma più frequentemente utilizzata negli esercizi numerici.

### Condizioni di validità

La legge di Hooke descrive il comportamento delle molle ideali e dei corpi elastici nel loro regime lineare.

Per deformazioni eccessive, un materiale reale potrebbe non seguire più una relazione proporzionale tra forza e deformazione.

Negli esercizi del corso si assume generalmente che la molla sia ideale, salvo indicazioni contrarie.

---

## Costante elastica

La **costante elastica** $k$ rappresenta la rigidità della molla.

Si misura in newton al metro:

$$
\boxed{[k]=\text{N/m}}
$$

Dalla legge di Hooke, considerando i moduli:

$$
\boxed{k=\frac{F}{\Delta l}}
$$

### Significato fisico

- Una molla con $k$ elevata è più rigida: richiede una forza maggiore per ottenere lo stesso allungamento.
- Una molla con $k$ ridotta è meno rigida: si deforma maggiormente sotto la stessa forza.

### Esempio

Consideriamo due molle:

$$
k_1=100\ \text{N/m}
$$

$$
k_2=500\ \text{N/m}
$$

Se entrambe vengono allungate di:

$$
\Delta l=0{,}10\ \text{m}
$$

La prima esercita una forza elastica di modulo:

$$
F_1=100\cdot0{,}10=10\ \text{N}
$$

La seconda:

$$
F_2=500\cdot0{,}10=50\ \text{N}
$$

La seconda molla è quindi cinque volte più rigida della prima.

---

## Calcolo dell'allungamento

Se si conoscono la forza elastica e la costante elastica, dalla legge di Hooke si ricava:

$$
F=k\Delta l
$$

Isolando la deformazione:

$$
\boxed{\Delta l=\frac{F}{k}}
$$

Questa è la formula principale da ricordare per gli esercizi usciti negli esami.

**Attenzione:** quando viene fornita una forza esterna applicata alla molla, è possibile uguagliarne il modulo alla forza elastica soltanto nelle appropriate condizioni di equilibrio.

### Esempio

Una molla di costante elastica:

$$
k=200\ \text{N/m}
$$

viene allungata mediante una forza esterna di 40 N, fino a raggiungere l'equilibrio.

Calcolare l'allungamento.

$$
\Delta l=\frac{F}{k}
$$

$$
\Delta l=\frac{40}{200}
$$

$$
\boxed{\Delta l=0{,}20\ \text{m}}
$$

Convertendo in centimetri:

$$
\boxed{\Delta l=20\ \text{cm}}
$$

---

## Equilibrio di una massa appesa a una molla

Consideriamo una molla ideale appesa verticalmente al soffitto, alla quale viene collegato un corpo di massa $m$.

Sul corpo agiscono due forze principali:

1. **Forza peso:** diretta verso il basso.
2. **Forza elastica:** diretta verso l'alto quando la molla è allungata.

Se il corpo è fermo, si trova in equilibrio.

Dalle condizioni di [[Equilibrio delle forze]]:

$$
\sum F_y=0
$$

Considerando i moduli:

$$
F_e-mg=0
$$

Quindi:

$$
F_e=mg
$$

Utilizzando la legge di Hooke:

$$
k\Delta l=mg
$$

Da cui:

$$
\boxed{\Delta l=\frac{mg}{k}}
$$

### Esempio

Un corpo di massa:

$$
m=2\ \text{kg}
$$

viene appeso a una molla verticale con costante elastica:

$$
k=400\ \text{N/m}
$$

Calcolare l'allungamento della molla quando il corpo raggiunge l'equilibrio.

La forza peso è:

$$
P=mg
$$

$$
P=2\cdot9{,}81=19{,}62\ \text{N}
$$

La forza elastica deve compensare il peso.

$$
\Delta l=\frac{mg}{k}
$$

$$
\Delta l=\frac{19{,}62}{400}
$$

$$
\Delta l=0{,}04905\ \text{m}
$$

Convertendo:

$$
\boxed{\Delta l\approx4{,}91\ \text{cm}}
$$

### Osservazioni

- Aumentando la massa, aumenta l'allungamento di equilibrio.
- Aumentando la costante elastica, diminuisce l'allungamento.
- L'allungamento dipende dall'accelerazione gravitazionale.

**Importante:** se il corpo viene lasciato libero prima di aver raggiunto l'equilibrio, può oscillare. In quel caso la risultante delle forze non è necessariamente nulla.

---

## Energia potenziale elastica

Una molla deformata può immagazzinare energia sotto forma di **energia potenziale elastica**.

L'energia potenziale elastica di una molla ideale è:

$$
\boxed{U_e=\frac12kx^2}
$$

dove:

- $U_e$ = energia potenziale elastica (J).
- $k$ = costante elastica (N/m).
- $x$ = deformazione rispetto alla lunghezza naturale (m).

Il valore dell'energia è scelto uguale a zero quando la molla non è deformata.

### Significato fisico

Quando una molla viene allungata o compressa, la sua energia potenziale elastica aumenta.

Poiché la deformazione compare al quadrato:

$$
x^2\ge0
$$

l'energia potenziale elastica è sempre positiva o nulla, con questa scelta dello zero.

Inoltre, allungamento e compressione della stessa entità producono la stessa energia potenziale elastica.

### Esempio

Una molla ha costante elastica:

$$
k=200\ \text{N/m}
$$

e viene compressa di:

$$
\Delta l=10\ \text{cm}=0{,}10\ \text{m}
$$

Calcolare l'energia potenziale elastica.

$$
U_e=\frac12kx^2
$$

$$
U_e=\frac12\cdot200\cdot(0{,}10)^2
$$

$$
U_e=100\cdot0{,}01
$$

$$
\boxed{U_e=1\ \text{J}}
$$

### Variazione dell'energia potenziale elastica

Se la deformazione passa da $x_i$ a $x_f$:

$$
\boxed{\Delta U_e=\frac12k(x_f^2-x_i^2)}
$$

La variazione di energia dipende sia dalla deformazione iniziale sia da quella finale.

---

## Lavoro della forza elastica

La forza elastica è una **forza conservativa**.

Il lavoro compiuto dalla forza elastica è uguale all'opposto della variazione dell'energia potenziale elastica:

$$
\boxed{L_e=-\Delta U_e}
$$

Pertanto:

$$
\boxed{L_e=\frac12k(x_i^2-x_f^2)}
$$

### Molla che ritorna alla lunghezza naturale

Se la molla parte da una deformazione $x$ e torna alla lunghezza naturale:

$$
x_i=x
$$

$$
x_f=0
$$

Il lavoro della forza elastica è:

$$
L_e=\frac12k(x^2-0)
$$

Quindi:

$$
\boxed{L_e=\frac12kx^2}
$$

In questo caso il lavoro della forza elastica è positivo.

### Molla che viene deformata

Se una molla inizialmente non deformata viene allungata fino a $x$:

$$
x_i=0
$$

$$
x_f=x
$$

Il lavoro della forza elastica diventa:

$$
\boxed{L_e=-\frac12kx^2}
$$

È negativo perché la forza elastica si oppone alla deformazione.

### Lavoro della forza esterna

Se la molla viene deformata lentamente, partendo dalla lunghezza naturale e terminando in equilibrio, il lavoro della forza esterna è:

$$
\boxed{L_{\text{est}}=\frac12kx^2}
$$

L'energia fornita viene immagazzinata sotto forma di energia potenziale elastica.

**Attenzione:** il lavoro necessario per deformare una molla non è semplicemente $kx\cdot x$, perché la forza elastica varia con la deformazione.

---

## Conservazione dell'energia meccanica

Se un sistema massa-molla ideale non è soggetto a forze dissipative, l'energia meccanica totale si conserva.

L'energia meccanica è la somma dell'energia cinetica e dell'energia potenziale.

Nel caso di una molla orizzontale ideale, senza attrito:

$$
\boxed{E_m=K+U_e}
$$

Quindi:

$$
\boxed{E_m=\frac12mv^2+\frac12kx^2}
$$

Se non intervengono forze non conservative che compiono lavoro:

$$
\boxed{E_{m,i}=E_{m,f}}
$$

### Esempio

Una molla orizzontale con costante elastica:

$$
k=100\ \text{N/m}
$$

è compressa di:

$$
x=0{,}20\ \text{m}
$$

Un corpo di massa:

$$
m=1\ \text{kg}
$$

è inizialmente fermo contro la molla.

Trascurando l'attrito, calcolare la velocità del corpo quando la molla raggiunge la lunghezza naturale, assumendo che tutta l'energia elastica si trasformi in energia cinetica del corpo.

**Energia iniziale:**

$$
E_i=\frac12kx^2
$$

**Energia finale:**

$$
E_f=\frac12mv^2
$$

Per conservazione dell'energia:

$$
\frac12kx^2=\frac12mv^2
$$

Semplificando e ricavando la velocità:

$$
\boxed{v=x\sqrt{\frac{k}{m}}}
$$

Sostituendo:

$$
v=0{,}20\sqrt{\frac{100}{1}}
$$

$$
\boxed{v=2\ \text{m/s}}
$$

Questo tipo di esercizio collega la forza elastica alla [[Lavoro energia e potenza|conservazione dell'energia meccanica]].

---

## Forza elastica e moto armonico

Un corpo collegato a una molla può oscillare attorno a una posizione di equilibrio.

In assenza di attrito e di altre forze che alterino il modello, il sistema può compiere un **moto armonico semplice**.

La forza elastica è:

$$
F_e=-kx
$$

Applicando il secondo principio di Newton:

$$
ma=-kx
$$

Quindi:

$$
\boxed{a=-\frac{k}{m}x}
$$

L'accelerazione è proporzionale allo spostamento dalla posizione di equilibrio, ma ha verso opposto.

### Frequenza angolare

Nel sistema massa-molla ideale:

$$
\boxed{\omega=\sqrt{\frac{k}{m}}}
$$

### Periodo di oscillazione

Il periodo rappresenta il tempo necessario per compiere un'oscillazione completa.

$$
\boxed{T=2\pi\sqrt{\frac{m}{k}}}
$$

### Frequenza di oscillazione

$$
\boxed{f=\frac{1}{2\pi}\sqrt{\frac{k}{m}}}
$$

### Osservazioni

- Aumentando la massa, aumenta il periodo.
- Aumentando la costante elastica, diminuisce il periodo.
- Nel modello ideale il periodo non dipende dall'ampiezza dell'oscillazione.

Il moto oscillatorio sarà approfondito in [[Moto armonico]].

Per gli esercizi sulla legge di Hooke visti nelle prove, non è necessario utilizzare queste formule.

---

## Esercizio ufficiale — Esame 29 gennaio 2024, domanda 8

### Testo

Calcolare l'allungamento di una molla di costante elastica:

$$
k=500\ \text{N/m}
$$

sottoposta a una forza di:

$$
F=125\ \text{N}
$$

### Soluzione

Utilizziamo la legge di Hooke, considerando i moduli delle forze in equilibrio:

$$
F=k\Delta l
$$

Ricaviamo l'allungamento:

$$
\Delta l=\frac{F}{k}
$$

Sostituendo i dati:

$$
\Delta l=\frac{125}{500}
$$

$$
\Delta l=0{,}25\ \text{m}
$$

Convertendo in centimetri:

$$
\boxed{\Delta l=25\ \text{cm}}
$$

### Principio da ricordare

L'allungamento di una molla ideale, in condizioni di equilibrio, è direttamente proporzionale alla forza applicata e inversamente proporzionale alla costante elastica.

---

## Esercizio ufficiale — Esame 10 settembre 2026, domanda 3

### Testo

Una molla di costante elastica:

$$
k=500\ \text{N/m}
$$

viene sottoposta a una forza di:

$$
F=125\ \text{N}
$$

Calcolare l'allungamento della molla.

### Soluzione

$$
\Delta l=\frac{F}{k}
$$

$$
\Delta l=\frac{125}{500}
$$

$$
\boxed{\Delta l=0{,}25\ \text{m}=25\ \text{cm}}
$$

### Osservazione

Questo esercizio è praticamente identico alla domanda 8 del compito del 29 gennaio 2024.

È quindi uno degli esempi più evidenti di ripetizione degli stessi schemi di esercizio nelle prove del professore.

---

## Altri esempi di applicazione

### Esempio 1 — Calcolare la forza elastica

Una molla di costante:

$$
k=300\ \text{N/m}
$$

viene compressa di 8 cm.

Calcolare il modulo della forza elastica.

Convertiamo:

$$
\Delta l=0{,}08\ \text{m}
$$

Applicando Hooke:

$$
F=k\Delta l
$$

$$
F=300\cdot0{,}08
$$

$$
\boxed{F=24\ \text{N}}
$$

La forza elastica è diretta in verso opposto alla compressione.

### Esempio 2 — Calcolare la costante elastica

Una molla si allunga di 15 cm quando viene sottoposta a una forza di 30 N in condizioni di equilibrio.

Calcolare la costante elastica.

$$
k=\frac{F}{\Delta l}
$$

$$
k=\frac{30}{0{,}15}
$$

$$
\boxed{k=200\ \text{N/m}}
$$

### Esempio 3 — Calcolare l'energia elastica

Una molla di costante:

$$
k=500\ \text{N/m}
$$

viene allungata di:

$$
x=0{,}10\ \text{m}
$$

Calcolare l'energia potenziale elastica.

$$
U_e=\frac12kx^2
$$

$$
U_e=\frac12\cdot500\cdot0{,}10^2
$$

$$
\boxed{U_e=2{,}5\ \text{J}}
$$

---

## Formule principali

| Grandezza | Formula |
|---|---|
| Deformazione | $x=l-l_0$ |
| Legge di Hooke | $F_e=-kx$ |
| Modulo della forza elastica | $F=k\Delta l$ |
| Allungamento | $\Delta l=F/k$ |
| Costante elastica | $k=F/\Delta l$ |
| Forza peso | $P=mg$ |
| Allungamento verticale in equilibrio | $\Delta l=mg/k$ |
| Energia potenziale elastica | $U_e=\frac12kx^2$ |
| Lavoro della forza elastica | $L_e=\frac12k(x_i^2-x_f^2)$ |
| Energia meccanica massa-molla | $E_m=\frac12mv^2+\frac12kx^2$ |
| Frequenza angolare | $\omega=\sqrt{k/m}$ |
| Periodo delle oscillazioni | $T=2\pi\sqrt{m/k}$ |

---

## Come riconoscere gli esercizi

| Situazione | Formula principale |
|---|---|
| È nota la forza e si cerca l'allungamento | $\Delta l=F/k$ |
| È nota la deformazione e si cerca la forza | $F=k\Delta l$ |
| Si cerca la rigidità della molla | $k=F/\Delta l$ |
| Massa appesa a una molla in equilibrio | $k\Delta l=mg$ |
| Si cerca l'energia immagazzinata | $U_e=\frac12kx^2$ |
| Si cerca il lavoro della forza elastica | $L_e=-\Delta U_e$ |
| Una molla spinge un corpo senza attrito | Conservazione dell'energia |
| Si cerca il periodo di oscillazione | $T=2\pi\sqrt{m/k}$ |

---

## Domande teoriche da conoscere

**Che cos'è la forza elastica?**

È una forza che si oppone alla deformazione di un corpo elastico e tende a riportarlo alla sua configurazione di equilibrio.

**Che cosa afferma la legge di Hooke?**

La forza elastica esercitata da una molla ideale è proporzionale alla deformazione e diretta in verso opposto a essa.

**Qual è la formula della legge di Hooke?**

$$
F_e=-kx
$$

**Che cosa rappresenta la costante elastica?**

Misura la rigidità della molla.

**Qual è l'unità di misura della costante elastica?**

Newton al metro (N/m).

**Una molla più rigida si allunga di più o di meno sotto la stessa forza?**

Si allunga di meno, perché possiede una costante elastica maggiore.

**Perché nella legge di Hooke compare un segno negativo?**

Perché la forza elastica è diretta in verso opposto alla deformazione.

**La forza elastica è una forza conservativa?**

Sì, nel modello di molla ideale.

**L'energia potenziale elastica dipende dal segno della deformazione?**

No. Dipende dal quadrato della deformazione.

**Quando l'energia potenziale elastica è nulla?**

Quando la molla si trova alla lunghezza naturale, scegliendo tale configurazione come riferimento di energia nulla.

**Che cosa accade all'energia potenziale se la deformazione raddoppia?**

Quadruplica, perché è proporzionale al quadrato della deformazione.

**Qual è la condizione di equilibrio per una massa appesa a una molla verticale?**

La forza elastica compensa la forza peso:

$$
k\Delta l=mg
$$

**Da quali grandezze dipende il periodo di un sistema massa-molla ideale?**

Dalla massa del corpo e dalla costante elastica della molla.

**Che cosa succede al periodo se la massa aumenta?**

Il periodo aumenta.

**Che cosa succede al periodo se la molla diventa più rigida?**

Il periodo diminuisce.

---

## Errori frequenti

- Dimenticare il segno negativo nella legge di Hooke.
- Confondere la forza elastica con la forza esterna applicata.
- Uguagliare sempre forza esterna e forza elastica anche quando il sistema accelera.
- Confondere allungamento e lunghezza totale della molla.
- Utilizzare centimetri al posto di metri.
- Pensare che una molla più rigida si allunghi maggiormente.
- Dimenticare che la forza elastica è opposta alla deformazione.
- Confondere la forza elastica con l'energia potenziale elastica.
- Dimenticare il quadrato nella formula dell'energia elastica.
- Pensare che la compressione produca energia potenziale negativa.
- Applicare $F\Delta l$ come lavoro della forza elastica durante una deformazione variabile.
- Dimenticare la forza peso negli esercizi con molle verticali.
- Confondere la posizione di equilibrio con la lunghezza naturale della molla.
- Utilizzare il periodo del moto armonico quando basta la legge di Hooke.

---

## Checklist di preparazione

- [ ] So definire la forza elastica.
- [ ] Conosco la legge di Hooke.
- [ ] So spiegare il significato del segno negativo.
- [ ] So distinguere allungamento e compressione.
- [ ] So calcolare la deformazione di una molla.
- [ ] So calcolare la forza elastica.
- [ ] So ricavare la costante elastica.
- [ ] So risolvere un problema con una massa appesa a una molla verticale.
- [ ] So calcolare l'energia potenziale elastica.
- [ ] So determinare il lavoro della forza elastica.
- [ ] So utilizzare la conservazione dell'energia in un sistema massa-molla.
- [ ] Conosco la relazione tra forza elastica e moto armonico.
- [ ] So calcolare il periodo di un sistema massa-molla ideale.
- [ ] So risolvere autonomamente la domanda 8 dell'esame del 29 gennaio 2024.
- [ ] So risolvere autonomamente la domanda 3 dell'esame del 10 settembre 2026.
- [ ] So rispondere alle domande teoriche senza consultare gli appunti.

---

## Collegamenti

- [[Cinematica]]
- [[Principi della dinamica]]
- [[Equilibrio delle forze]]
- [[Lavoro energia e potenza]]
- [[Moto armonico]]
