### Task 4 Answer

**Problem:**

A fragment of an electrical network consists of two elements connected in **parallel**: \(a_1\) and \(a_2\).  
Let \(A_i\), \(i=1,2\), denote the event that element \(a_i\) remains functional for at least time \(t\).  

Given:  
\[
P(A_1) = P(A_2) = p, \quad P(A_1 \cap A_2) = p^2
\]

Find the probability of continuous current flow through this system for at least time \(t\).

---

**Solution:**

1. For a **parallel system**, current flows if **at least one element is functional**:  
   \[
   A = A_1 \cup A_2
   \]

2. Use the formula for the union of two events:  
   \[
   P(A_1 \cup A_2) = P(A_1) + P(A_2) - P(A_1 \cap A_2)
   \]

3. Plug in the given probabilities:  
   \[
   P(A_1 \cup A_2) = p + p - p^2 = 2p - p^2
   \]

---

**Answer:**  
\[
\boxed{2p - p^2}
\]

**Explanation:**  
In a parallel connection, the current flows uninterrupted if **at least one element works**, giving the probability \(2p - p^2\).
