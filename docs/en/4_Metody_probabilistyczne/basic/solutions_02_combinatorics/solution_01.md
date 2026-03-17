## Task 1 — Recognizing Counting Models

For each situation we identify the appropriate combinatorial model and explain why it applies.

---

### 1. Arranging 7 students in a line

All 7 students are used and their positions in the line matter.  
Different orders correspond to different outcomes.

Model: **Permutation**

Number of arrangements:

P₇ = 7!

---

### 2. Choosing 4 members of a committee from 12 people

We only choose a subset of people and the order of selection does not matter.  
For example, choosing {A,B,C,D} is the same as {B,A,C,D}.

Model: **Combination**

Number of committees:

C(12,4) = 12! / (4! · 8!)

---

### 3. Assigning gold, silver, and bronze medals among 15 athletes

Only three athletes are selected, but the order matters because the medals are different.  
Winning gold is not the same as winning silver.

Model: **k-permutation (ordered selection without repetition)**

Number of possibilities:

P(15,3) = 15! / 12!

---

### 4. Forming a 6-digit PIN code

Each of the six positions can contain any digit from 0–9 and digits may repeat.  
The choice in each position is independent.

Model: **Sequence with repetition**

Number of possible codes:

10⁶

---

### 5. Arranging the letters of the word BANANA

All letters are arranged, but some letters are identical.  
Since the letters A appear three times and N appear twice, many permutations would otherwise be counted multiple times.

Model: **Permutation with repeated elements**

Number of arrangements:

6! / (3! · 2!)

---

### 6. Seating 6 people around a round table

All people are seated, but rotations of the same seating are considered identical.  
In circular arrangements the first position can be fixed without loss of generality.

Model: **Circular permutation**

Number of arrangements:

(6 − 1)! = 5!
