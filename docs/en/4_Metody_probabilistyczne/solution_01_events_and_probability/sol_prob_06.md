### Task 6 Answer

**Problem:**

Identical products are manufactured by 2 automated machines and placed on a conveyor belt.  

- Production ratio (first machine : second machine) = \(3 : 2\)  
- First machine produces on average 65% first-grade products  
- Second machine produces on average 85% first-grade products  

Questions:

1. Probability that a randomly selected product is first-grade (use total probability formula)  
2. If a randomly selected product is first-grade, probability it was produced by the first machine (use Bayes' theorem)

---

**Solution:**

Let:

\[
M_1 = \text{product from first machine}, \quad M_2 = \text{product from second machine}
\]  
\[
F = \text{first-grade product}
\]

Given probabilities:

\[
P(M_1) = \frac{3}{5}, \quad P(M_2) = \frac{2}{5}
\]  
\[
P(F|M_1) = 0.65, \quad P(F|M_2) = 0.85
\]

---

### 1. Probability that a randomly selected product is first-grade

Use **total probability formula**:

\[
P(F) = P(F|M_1)P(M_1) + P(F|M_2)P(M_2)
\]

Plug in the values:

\[
P(F) = 0.65 \cdot \frac{3}{5} + 0.85 \cdot \frac{2}{5} = 0.39 + 0.34 = 0.73
\]

\[
\boxed{P(F) = 0.73}
\]

---

### 2. Probability that a first-grade product came from the first machine

Use **Bayes’ theorem**:

\[
P(M_1|F) = \frac{P(F|M_1) P(M_1)}{P(F)}
\]

Plug in the numbers:

\[
P(M_1|F) = \frac{0.65 \cdot \frac{3}{5}}{0.73} = \frac{0.39}{0.73} \approx 0.534
\]

\[
\boxed{P(M_1|F) \approx 0.534}
\]

---

**Answer:**

- Probability that a randomly selected product is first-grade: \(P(F) = 0.73\)  
- Probability that a first-grade product was produced by the first machine: \(P(M_1|F) \approx 0.534\)
