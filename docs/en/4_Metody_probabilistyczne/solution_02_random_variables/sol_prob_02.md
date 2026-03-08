## Task 2 – Probability Distribution of Grades

**Problem:**

The ratio of grades is given as:

very good : good : satisfactory : failing  
1 : 3 : 4 : 2

Let **X** denote the grade of a randomly selected student.

We want to determine:

- the **probability mass function (PMF)**,
- the **cumulative distribution function (CDF)**,
- the probability **P(X < 3.5)**.

---

### Step 1 – Convert the ratio into probabilities

Total parts of the ratio:

1 + 3 + 4 + 2 = 10

Each probability is the ratio part divided by 10.

Grades correspond to values:

2 → failing  
3 → satisfactory  
4 → good  
5 → very good

---

### Step 2 – Probability Mass Function (PMF)

P(X = x) = (ratio part) / 10

| x | 2 | 3 | 4 | 5 |
|---|---|---|---|---|
| P(X = x) | 2/10 | 4/10 | 3/10 | 1/10 |

---

### Step 3 – PMF Graph

The PMF graph is a **discrete bar graph** with bars at:

(2, 0.2)  
(3, 0.4)  
(4, 0.3)  
(5, 0.1)

---

### Step 4 – Cumulative Distribution Function (CDF)

The CDF is defined as:

F(x) = P(X ≤ x)

Compute cumulative probabilities:

F(2) = 2/10 = 0.2

F(3) = P(X ≤ 3)  
= 2/10 + 4/10  
= 6/10 = 0.6

F(4) = P(X ≤ 4)  
= 6/10 + 3/10  
= 9/10 = 0.9

F(5) = P(X ≤ 5)  
= 1

---

### Step 5 – CDF Graph

The CDF graph is a **step function**:

(2, 0.2)  
(3, 0.6)  
(4, 0.9)  
(5, 1)

---

### Step 6 – Calculate the probability P(X < 3.5)

Values less than 3.5 are:

2 and 3

P(X < 3.5) = P(X = 2) + P(X = 3)

= 2/10 + 4/10

= 6/10

= **0.6**
