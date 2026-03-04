# Task 8 – Probability of Coded Pulses

**Problem:**

Coded information consists of seven pulses of types A, B, C in quantities:  
- 4 pulses of A  
- 2 pulses of B  
- 1 pulse of C  

Assuming a random arrangement of pulses, find the probability that:  

1. The first received pulse will be A  
2. The first received pulse will be A or C  
3. The first two pulses will be A and C in that order  

---

## Solution

Total number of pulses = 4 + 2 + 1 = 7

1. **Probability that the first pulse is A:**  

\[
P(\text{first A}) = \frac{\text{number of A pulses}}{\text{total pulses}} = \frac{4}{7}
\]

2. **Probability that the first pulse is A or C:**  

\[
P(\text{first A or C}) = \frac{\text{number of A + C pulses}}{\text{total pulses}} = \frac{4 + 1}{7} = \frac{5}{7}
\]

3. **Probability that the first two pulses are A then C (in that order):**  

- Probability first pulse is A = 4/7  
- After removing 1 A, total pulses left = 6, number of C pulses = 1  
- Probability second pulse is C = 1/6  

\[
P(\text{first A, second C}) = \frac{4}{7} \cdot \frac{1}{6} = \frac{4}{42} = \frac{2}{21}
\]

---

**Answer:**  

1. **4/7**  
2. **5/7**  
3. **2/21**
