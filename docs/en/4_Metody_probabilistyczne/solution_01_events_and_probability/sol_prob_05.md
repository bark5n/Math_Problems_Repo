### Task 5 Answer

**Problem:**

We consider the volume of water (in \(dm^3\)) that a concrete culvert can conduct per second.  

Given:  
\[
P(A) = 0.6, \quad P(B) = 0.7, \quad P(A \cup B) = 0.8
\]

Where:  

- \(A =\) volume in \([125, 250]\)  
- \(B =\) volume in \((200, 300]\)

Find:

1. \(P(A')\) (complement of \(A\))  
2. \(P(A \cap B)\) (intersection of the intervals)  
3. \(P(A' \cap B')\) (volume not in either interval)  

---

**Solution:**

1. **Complement of \(A\):**  
\[
P(A') = 1 - P(A) = 1 - 0.6 = 0.4
\]

2. **Intersection of \(A\) and \(B\):**  

Use the formula:  
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]  

Solve for \(P(A \cap B)\):  
\[
P(A \cap B) = P(A) + P(B) - P(A \cup B) = 0.6 + 0.7 - 0.8 = 0.5
\]

3. **Intersection of complements (\(A' \cap B'\))**  

Complement rule:  
\[
A' \cap B' = (A \cup B)'
\]  
\[
P(A' \cap B') = 1 - P(A \cup B) = 1 - 0.8 = 0.2
\]

---

**Answer:**

- \(P(A') = 0.4\)  
- \(P(A \cap B) = 0.5\)  
- \(P(A' \cap B') = 0.2\)
