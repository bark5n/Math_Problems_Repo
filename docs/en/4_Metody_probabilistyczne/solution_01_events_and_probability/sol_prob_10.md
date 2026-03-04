# Probability of Receiving Specific Letter Sequences

**Problem:**

Only three types of sequences are transmitted:

AAAA with probability 0.4  
BBBB with probability 0.3  
CCCC with probability 0.3  

Letters are independently distorted during transmission.

Single-letter transition probabilities:

| Transmitted \ Received | A   | B   | C   |
|------------------------|-----|-----|-----|
| A                      | 0.8 | 0.1 | 0.1 |
| B                      | 0.1 | 0.8 | 0.1 |
| C                      | 0.1 | 0.1 | 0.8 |

Find the probability of receiving:

1) AAAA  
2) ACAA  

---

## Solution

Because letters are independent, we multiply symbol probabilities.
We use the law of total probability over all possible transmitted sequences.

---

## 1) Probability of receiving AAAA

### Case 1: AAAA was sent (prob = 0.4)

P(AAAA | AAAA sent) = 0.8⁴ = 0.4096  

Contribution:  
0.4 × 0.4096 = 0.16384  

### Case 2: BBBB was sent (prob = 0.3)

P(AAAA | BBBB sent) = 0.1⁴ = 0.0001  

Contribution:  
0.3 × 0.0001 = 0.00003  

### Case 3: CCCC was sent (prob = 0.3)

P(AAAA | CCCC sent) = 0.1⁴ = 0.0001  

Contribution:  
0.3 × 0.0001 = 0.00003  

### Total

P(AAAA received) =  
0.16384 + 0.00003 + 0.00003  

P(AAAA received) = **0.16390**

---

## 2) Probability of receiving ACAA

### Case 1: AAAA was sent

P(ACAA | AAAA sent) =  
0.8 × 0.1 × 0.8 × 0.8  

= 0.0512  

Contribution:  
0.4 × 0.0512 = 0.02048  

---

### Case 2: BBBB was sent

P(ACAA | BBBB sent) =  
0.1 × 0.1 × 0.1 × 0.1  

= 0.0001  

Contribution:  
0.3 × 0.0001 = 0.00003  

---

### Case 3: CCCC was sent

P(ACAA | CCCC sent) =  
0.1 × 0.8 × 0.1 × 0.1  

= 0.0008  

Contribution:  
0.3 × 0.0008 = 0.00024  

---

### Total

P(ACAA received) =  
0.02048 + 0.00003 + 0.00024  

P(ACAA received) = **0.02075**
