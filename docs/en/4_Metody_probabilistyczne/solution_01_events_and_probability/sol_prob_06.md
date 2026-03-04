# Task 6 – Total Probability and Bayes' Theorem

**Problem:**

Identical products manufactured by 2 automated machines are placed on a conveyor belt.  
The quantitative production ratio of the first machine to the second is 3:2.

- The first machine produces 65% first-grade products.
- The second machine produces 85% first-grade products.

1. One product is randomly selected. Find the probability that it is first-grade (use the total probability formula).
2. The selected product turned out to be first-grade. Find the probability that it was produced by the first machine (use Bayes' theorem).

---

## Solution

Let:

P(M1) = 3 / (3 + 2) = 3/5 = 0.6  
P(M2) = 2 / (3 + 2) = 2/5 = 0.4  

P(F | M1) = 0.65  
P(F | M2) = 0.85  

---

### 1) Probability that a randomly selected product is first-grade

Using the total probability formula:

P(F) = P(M1)·P(F | M1) + P(M2)·P(F | M2)

P(F) = 0.6 × 0.65 + 0.4 × 0.85  
P(F) = 0.39 + 0.34  
P(F) = 0.73  

So,

P(first-grade) = **0.73**

---

### 2) Probability that the product was produced by Machine 1 (Bayes' theorem)

Using Bayes' theorem:

P(M1 | F) = [P(M1)·P(F | M1)] / P(F)

P(M1 | F) = (0.6 × 0.65) / 0.73  
P(M1 | F) = 0.39 / 0.73  
P(M1 | F) ≈ 0.5342  

So,

P(M1 | first-grade) ≈ **0.534**
