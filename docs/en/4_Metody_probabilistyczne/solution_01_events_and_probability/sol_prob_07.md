### Task 7 Answer

**Problem:**

- Two types of signals are transmitted: \(111\) and \(000\)  
- A priori probabilities: \(P(111) = 0.65, \ P(000) = 0.35\)  
- Random interference:  
  - Symbol 1 can be received as 0 with probability 0.2  
  - Symbol 0 can be received as 1 with probability 0.2  
- Symbols are independently affected.

Calculate the probability of receiving the signals: \(111, 000, 010\).

---

**Solution:**

Let’s denote the received signal as \(R\).

1. **Probability of receiving \(111\)**  

- If transmitted \(111\): each 1 is correctly received with probability \(0.8\)  
\[
P(R=111 | 111 \text{ sent}) = 0.8^3 = 0.512
\]  

- If transmitted \(000\): each 0 is received as 1 with probability 0.2  
\[
P(R=111 | 000 \text{ sent}) = 0.2^3 = 0.008
\]  

Use **total probability formula**:  
\[
P(R=111) = P(R=111|111)P(111) + P(R=111|000)P(000)
\]  
\[
P(R=111) = 0.512 \cdot 0.65 + 0.008 \cdot 0.35 = 0.3328 + 0.0028 \approx 0.3356
\]

---

2. **Probability of receiving \(000\)**  

- If transmitted \(000\): each 0 correctly received with probability \(0.8\)  
\[
P(R=000 | 000) = 0.8^3 = 0.512
\]  

- If transmitted \(111\): each 1 received as 0 with probability 0.2  
\[
P(R=000 | 111) = 0.2^3 = 0.008
\]  

Total probability:  
\[
P(R=000) = 0.512 \cdot 0.35 + 0.008 \cdot 0.65 = 0.1792 + 0.0052 \approx 0.1844
\]

---

3. **Probability of receiving \(010\)**  

- If transmitted \(111\): probability to get 010  
\[
P(R=010|111) = 0.2 \cdot 0.8 \cdot 0.2 = 0.032
\]  
- If transmitted \(000\): probability to get 010  
\[
P(R=010|000) = 0.8 \cdot 0.2 \cdot 0.8 = 0.128
\]  

Total probability:  
\[
P(R=010) = 0.032 \cdot 0.65 + 0.128 \cdot 0.35 = 0.0208 + 0.0448 \approx 0.0656
\]

---

**Answer:**

\[
P(R=111) \approx 0.336, \quad P(R=000) \approx 0.184, \quad P(R=010) \approx 0.066
\]
