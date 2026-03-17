## Task 5 — Combinations

In combination problems, we choose objects but the order does not matter.

---

### 1. Committee of 4 chosen from 12 students

Number of committees:

C(12,4)

---

### 2. Committees containing a particular student

Fix that student.

Now choose 3 more from the remaining 11:

C(11,3)

---

### 3. Committees containing at least one of two particular students

Case 1: committee contains student A  
C(11,3)

Case 2: committee contains student B  
C(11,3)

Case 3: both A and B counted twice → subtract

C(10,2)

Total:

C(11,3) + C(11,3) − C(10,2)

---

### 4. Exactly two women (7 men, 5 women)

Choose 2 women from 5:

C(5,2)

Choose 2 men from 7:

C(7,2)

Total committees:

C(5,2) × C(7,2)
