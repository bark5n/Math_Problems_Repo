## Task 6 — Combinations in Card Problems

A standard deck contains 52 cards.

---

### 1. Exactly 2 hearts in a 5-card hand

Choose 2 hearts from 13:

C(13,2)

Choose 3 non-hearts from 39:

C(39,3)

Total hands:

C(13,2) × C(39,3)

---

### 2. At least one heart

Total hands:

C(52,5)

Hands with no hearts:

C(39,5)

Hands with at least one heart:

C(52,5) − C(39,5)

---

### 3. No face cards (J, Q, K)

Face cards = 12

Non-face cards = 40

Choose all 5 from non-face cards:

C(40,5)
