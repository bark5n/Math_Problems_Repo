# Task 7 – Probability of Receiving a Signal

**Problem:**

On a communication line, two types of signals are transmitted in the form of code combinations:

- 111 with a priori probability 0.65  
- 000 with a priori probability 0.35  

The signals are subject to random interference:

- Symbol 1 is received as 0 with probability 0.2  
- Symbol 0 is received as 1 with probability 0.2  

Symbols are distorted independently of each other.

Calculate the probability of receiving the signal:

1. 111  
2. 000  
3. 010  

---

## Solution

Given:
- P(111 sent) = 0.65  
- P(000 sent) = 0.35  
- P(correct transmission of a symbol) = 0.8  
- P(error in a symbol) = 0.2  

Since symbols are independent, we multiply probabilities for each bit.

---

### 1) Probability of receiving 111

If 111 was sent:
P(111 | 111 sent) = 0.8 × 0.8 × 0.8 = 0.8³ = 0.512  

If 000 was sent:
P(111 | 000 sent) = 0.2 × 0.2 × 0.2 = 0.2³ = 0.008  

Using total probability:

P(111 received) = 0.65 × 0.512 + 0.35 × 0.008  
P(111 received) = 0.3328 + 0.0028  
P(111 received) = 0.3356  

---

### 2) Probability of receiving 000

If 000 was sent:
P(000 | 000 sent) = 0.8³ = 0.512  

If 111 was sent:
P(000 | 111 sent) = 0.2³ = 0.008  

P(000 received) = 0.35 × 0.512 + 0.65 × 0.008  
P(000 received) = 0.1792 + 0.0052  
P(000 received) = 0.1844  

---

### 3) Probability of receiving 010

Case 1: 111 was sent  
To receive 010 from 111:
1→0 (0.2), 1→1 (0.8), 1→0 (0.2)

P(010 | 111 sent) = 0.2 × 0.8 × 0.2 = 0.032  

Case 2: 000 was sent  
To receive 010 from 000:
0→0 (0.8), 0→1 (0.2), 0→0 (0.8)

P(010 | 000 sent) = 0.8 × 0.2 × 0.8 = 0.128  

P(010 received) = 0.65 × 0.032 + 0.35 × 0.128  
P(010 received) = 0.0208 + 0.0448  
P(010 received) = 0.0656  

---

## Final Answers

- P(111) = **0.3356**  
- P(000) = **0.1844**  
- P(010) = **0.0656**
