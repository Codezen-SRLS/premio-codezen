# Premio Codezen – Test 2026

Welcome to the Premio Codezen test!

This questionnaire is designed to assess your skills in technology, logic, and analytical thinking. Read the instructions carefully before starting.

---

## Rules

- **Duration**: 50 minutes to complete the entire test
- **Structure**: 10 questions
- **Scoring**:
  - Correct answer: **+1 point**
  - Wrong answer: **-0.5 points**
  - Unanswered: **0 points**
- The test will be invalidated if the proctoring software detects anomalous behavior (e.g., switching screens)
- In case of a tie, the prize will be awarded to the student with the lower ISEE (income indicator)

## Tips

- Read each question carefully before answering
- Manage your time wisely: some sections may require more attention
- Focus and answer only when you are confident in your choice

By submitting the test, you accept the rules.

Good luck!  
**The Codezen Team**

---

## Questions

### 1 - Rogue Network

Six nodes in a distributed system — Aria, Bravo, Cypher, Delta, Echo, Foxtrot — are each either TRUSTED (always output true statements) or ROGUE (always output false statements). Each broadcasts one message:

- **Aria**: "The number of ROGUE nodes is prime."
- **Bravo**: "Aria is TRUSTED."
- **Cypher**: "Bravo and Delta are both ROGUE."
- **Delta**: "Cypher is TRUSTED."
- **Echo**: "Exactly 2 nodes are ROGUE."
- **Foxtrot**: "Aria and Echo have opposite types."

**Which nodes are ROGUE?**

- A) Aria and Bravo
- B) Cypher and Delta
- C) Bravo, Cypher and Foxtrot
- D) Cypher, Delta and Echo
- E) Aria, Delta and Echo

---

### 2 - Signal Vault

An intelligence agency stores data across three identical-looking server racks:
- **Rack X**: two encrypted drives
- **Rack Y**: one encrypted drive and one plaintext drive
- **Rack Z**: two plaintext drives

A technician picks a rack at random and retrieves one drive at random — it turns out to be encrypted. What is the probability that the other drive in the same rack is also encrypted?

- A) 1/4
- B) 1/3
- C) 1/2
- D) 2/3
- E) 3/4

---

### 3 - Patrol Blackout

A facility runs three automated patrol drones on continuous loops:
- **Drone A**: completes a loop every 13 minutes
- **Drone B**: completes a loop every 17 minutes
- **Drone C**: completes a loop every 19 minutes

All drones start simultaneously at minute 0. Each drone has a 1-minute sensor blackout at the very end of its loop (the last minute of each cycle). What is the earliest minute after minute 0 when all three drones are simultaneously in their blackout period?

- A) 48
- B) 220
- C) 322
- D) 4198
- E) 4199

---

### 4 - Blind Review

Eight researchers each submit a paper to a conference. Due to a system glitch, the eight papers are randomly redistributed for peer review — the only constraint enforced is that no researcher receives their own paper. How many valid assignments exist?

- A) 1854
- B) 14832
- C) 14833
- D) 20160
- E) 40320

---

### 5 - City Blackout

A delivery drone navigates a 6×6 city grid from (0,0) to (6,6), moving only East or North one step at a time. Two intersections are closed for maintenance and must be avoided: **(2,3)** and **(4,3)**. How many distinct shortest-path routes exist?

- A) 224
- B) 324
- C) 400
- D) 574
- E) 924

---

### 6 - Sequence Alarm

A network monitoring system analyzes a continuous stream of events. Each event is independently classified as NORMAL (N) or SUSPICIOUS (S), each with probability 1/2. The system triggers an alert as soon as it detects the consecutive subsequence **S N S N S** for the first time.

What is the expected number of events analyzed before the first alert is triggered?

- A) 32
- B) 34
- C) 40
- D) 42
- E) 64

---

### 7 - Vault Cipher

A vault uses a 4-digit code with all digits distinct (0–9). After each failed attempt the display shows two numbers: how many digits are in the correct position, and how many digits are correct but in the wrong position.

The following five attempts were recorded:

| # | Code tried | Correct position | Correct digit, wrong position |
|---|------------|-----------------|-------------------------------|
| 1 | 1735       | 1               | 0                             |
| 2 | 4192       | 1               | 2                             |
| 3 | 9274       | 0               | 4                             |
| 4 | 4751       | 2               | 0                             |
| 5 | 3726       | 2               | 0                             |

**What code unlocks the vault?**

- A) 2479
- B) 4726
- C) 4729
- D) 4792
- E) 7429

---

### 8 - Cyber Championship

Eight teams compete in a single-elimination tournament, seeded 1 to 8 (seed 1 is the strongest). In any match between seeds i and j with i < j, the stronger team wins with probability 3/4. The bracket is:

- **Quarter-finals**: (1 vs 8), (4 vs 5), (2 vs 7), (3 vs 6)
- **Semi-finals**: winner(1v8) vs winner(4v5) — winner(2v7) vs winner(3v6)
- **Final**: the two semi-final winners

What is the probability that the final is contested between seeds 1 and 2?

- A) 3/4
- B) 9/64
- C) 27/64
- D) 9/16
- E) 81/256

---

### 9 - Firewall Mesh

Eight servers are arranged in a ring network. Each server must establish exactly one encrypted tunnel to one other server in the ring. The tunnels cannot cross: if drawn as chords inside the ring, no two chords may intersect. How many valid tunnel configurations exist?

- A) 5
- B) 14
- C) 28
- D) 42
- E) 105

---

### 10 - Server Grid Backup

A 3×8 server grid must be fully covered by 1×2 backup modules. Each module covers exactly two adjacent servers (horizontally or vertically), with no overlaps and no gaps. In how many distinct ways can the entire grid be covered?

- A) 41
- B) 128
- C) 153
- D) 256
- E) 571
