## Task 10 — Urn Models

Urn contains:

- 5 red  
- 4 blue  
- 3 green  

Total = 12 balls  

---

### 1. Three balls drawn, order ignored

We choose any 3 balls from 12:

C(12,3) = 220

---

### 2. Exactly two red balls

Choose 2 red:

C(5,2) = 10

Choose 1 from remaining 7 (blue + green):

C(7,1) = 7

Total:

C(5,2) × C(7,1) = 10 × 7 = 70

---

### 3. Order of colors recorded

Now order matters and balls are drawn without replacement.

Total outcomes:

12 × 11 × 10 = 1320

---

### 4. Exactly two red in sequence

Step 1: Choose positions of the 2 red balls:

C(3,2) = 3

Step 2: Choose and arrange 2 red balls:

P(5,2) = 5 × 4 = 20

Step 3: Choose 1 non-red ball:

7

Total:

3 × 20 × 7 = 420

---

## Final Answers

- Q1: 220  
- Q2: 70  
- Q3: 1320  
- Q4: 420
