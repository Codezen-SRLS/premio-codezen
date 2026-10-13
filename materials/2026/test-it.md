# Premio Codezen – Test 2026 (Italiano)

Benvenuto al test per il Premio Codezen!

Questo questionario ha lo scopo di valutare le tue competenze in ambito tecnologico, logico e analitico. Leggi con attenzione le istruzioni prima di iniziare.

---

## Regolamento

- **Durata**: 50 minuti per completare l'intero test
- **Struttura**: 10 domande
- **Punteggio**:
  - Risposta corretta: **+1 punto**
  - Risposta errata: **-0.5 punti**
  - Risposta non data: **0 punti**
- Il test verrà annullato nel caso il software di proctoring riscontri operazioni anomale da parte del candidato (es. cambio schermata)
- In caso di parità, verrà assegnato il premio allo studente con ISEE minore

## Consigli utili

- Leggi attentamente ogni domanda prima di rispondere
- Gestisci bene il tempo: alcune sezioni potrebbero richiedere più attenzione
- Concentrati e rispondi solo quando sei sicuro della tua scelta

Consegnando il test si accetta il regolamento.

Buona fortuna!  
**Il Team Codezen**

---

## Domande

### 1 - Rete Corrotta

Sei nodi in un sistema distribuito — Aria, Bravo, Cypher, Delta, Echo, Foxtrot — sono ciascuno FIDATO (produce sempre affermazioni vere) o CORROTTO (produce sempre affermazioni false). Ognuno trasmette un messaggio:

- **Aria**: «Il numero di nodi CORROTTI è primo.»
- **Bravo**: «Aria è FIDATO.»
- **Cypher**: «Bravo e Delta sono entrambi CORROTTI.»
- **Delta**: «Cypher è FIDATO.»
- **Echo**: «Esattamente 2 nodi sono CORROTTI.»
- **Foxtrot**: «Aria ed Echo hanno tipi opposti.»

**Quali nodi sono CORROTTI?**

- A) Aria e Bravo
- B) Cypher e Delta
- C) Bravo, Cypher e Foxtrot
- D) Cypher, Delta ed Echo
- E) Aria, Delta ed Echo

---

### 2 - Il Caveau dei Segnali

Un'agenzia di intelligence conserva dati in tre rack server dall'aspetto identico:
- **Rack X**: due dischi cifrati
- **Rack Y**: un disco cifrato e un disco in chiaro
- **Rack Z**: due dischi in chiaro

Un tecnico sceglie un rack a caso ed estrae un disco a caso — risulta essere cifrato. Qual è la probabilità che anche l'altro disco nello stesso rack sia cifrato?

- A) 1/4
- B) 1/3
- C) 1/2
- D) 2/3
- E) 3/4

---

### 3 - Pattuglia al Buio

Una struttura dispone di tre droni di sorveglianza automatica in pattuglia continua:
- **Drone A**: completa un giro ogni 13 minuti
- **Drone B**: completa un giro ogni 17 minuti
- **Drone C**: completa un giro ogni 19 minuti

Tutti i droni partono simultaneamente al minuto 0. Ogni drone ha un blackout dei sensori di 1 minuto alla fine di ogni giro (l'ultimo minuto di ogni ciclo). Qual è il primo minuto dopo il minuto 0 in cui tutti e tre i droni si trovano simultaneamente nel loro periodo di blackout?

- A) 48
- B) 220
- C) 322
- D) 4198
- E) 4199

---

### 4 - Revisione Anonima

Otto ricercatori presentano ciascuno un articolo a una conferenza. A causa di un errore di sistema, gli otto articoli vengono ridistribuiti casualmente per la revisione tra pari — l'unico vincolo applicato è che nessun ricercatore riceva il proprio articolo. Quante assegnazioni valide esistono?

- A) 1854
- B) 14832
- C) 14833
- D) 20160
- E) 40320

---

### 5 - Blackout Urbano

Un drone di consegna naviga una griglia urbana 6×6 da (0,0) a (6,6), muovendosi solo verso Est o verso Nord di un passo alla volta. Due incroci sono chiusi per manutenzione e devono essere evitati: **(2,3)** e **(4,3)**. Quanti percorsi distinti di lunghezza minima esistono?

- A) 224
- B) 324
- C) 400
- D) 574
- E) 924

---

### 6 - Allarme in Sequenza

Un sistema di monitoraggio analizza un flusso continuo di eventi di rete. Ogni evento viene classificato indipendentemente come NORMALE (N) o SOSPETTO (S), ciascuno con probabilità 1/2. Il sistema lancia un allarme non appena individua per la prima volta la sottosequenza consecutiva **S N S N S**.

Qual è il numero atteso di eventi analizzati prima che scatti il primo allarme?

- A) 32
- B) 34
- C) 40
- D) 42
- E) 64

---

### 7 - Il Vault Cifrato

Un vault utilizza un codice di quattro cifre tutte diverse (da 0 a 9). Dopo ogni tentativo fallito il display mostra due numeri: quante cifre sono nella posizione corretta e quante cifre sono giuste ma in posizione sbagliata.

Sono stati registrati i seguenti cinque tentativi:

| # | Codice provato | Posizione corretta | Cifra corretta, posizione sbagliata |
|---|----------------|--------------------|-------------------------------------|
| 1 | 1735           | 1                  | 0                                   |
| 2 | 4192           | 1                  | 2                                   |
| 3 | 9274           | 0                  | 4                                   |
| 4 | 4751           | 2                  | 0                                   |
| 5 | 3726           | 2                  | 0                                   |

**Quale codice sblocca il vault?**

- A) 2479
- B) 4726
- C) 4729
- D) 4792
- E) 7429

---

### 8 - Campionato Cyber

Otto team si sfidano in un torneo a eliminazione diretta. I team sono classificati per forza da 1 a 8: il team 1 è il più forte, l'8 il più debole. Ogni volta che due team si incontrano, quello con il numero più basso vince con probabilità 3/4.

Il tabellone è fisso:
- **Quarti di finale**: (1 vs 8), (4 vs 5), (2 vs 7), (3 vs 6)
- **Semifinali**: vincitore di (1–8) vs vincitore di (4–5) — vincitore di (2–7) vs vincitore di (3–6)
- **Finale**: i vincitori delle due semifinali

Qual è la probabilità che la finale sia disputata tra il team 1 e il team 2?

- A) 3/4
- B) 9/64
- C) 27/64
- D) 9/16
- E) 81/256

---

### 9 - La Rete Firewall

Otto server sono disposti in una rete ad anello. Ogni server deve stabilire esattamente un tunnel cifrato verso un altro server nell'anello. I tunnel non possono incrociarsi: se disegnati come corde all'interno dell'anello, due corde qualsiasi non devono mai intersecarsi. Quante configurazioni valide di tunnel esistono?

- A) 5
- B) 14
- C) 28
- D) 42
- E) 105

---

### 10 - Backup della Griglia

Una griglia di server 3×8 deve essere completamente coperta da moduli di backup 1×2. Ogni modulo copre esattamente due server adiacenti (orizzontalmente o verticalmente), senza sovrapposizioni e senza spazi vuoti. In quanti modi distinti può essere coperta l'intera griglia?

- A) 41
- B) 128
- C) 153
- D) 256
- E) 571
