## Task 7 – Marginal Distribution and CDF of Y

**Problem:**

The two-dimensional random variable **(X, Y)** has the joint distribution:

| Y \ X | 1 | 2 | 3 |
|------|----|----|----|
| 2 | 0.1 | 0.2 | 0.3 |
| 4 | 0.1 | 0.1 | 0.2 |

We must determine the **cumulative distribution function (CDF)** of the **marginal distribution of Y**.

---

### Step 1 – Find the marginal distribution of Y

To obtain the marginal distribution of **Y**, sum the probabilities across each row.

For **Y = 2**:

P(Y=2) = 0.1 + 0.2 + 0.3  
P(Y=2) = **0.6**

For **Y = 4**:

P(Y=4) = 0.1 + 0.1 + 0.2  
P(Y=4) = **0.4**

Check:

0.6 + 0.4 = 1 ✔

Marginal distribution:

| Y | P(Y) |
|---|------|
| 2 | 0.6 |
| 4 | 0.4 |

---

### Step 2 – Determine the cumulative distribution function

The cumulative distribution function is:

F_Y(y) = P(Y ≤ y)

Therefore:

For **y < 2**

F_Y(y) = 0

For **2 ≤ y < 4**

F_Y(y) = P(Y=2)  
F_Y(y) = **0.6**

For **y ≥ 4**

F_Y(y) = P(Y=2) + P(Y=4)  
F_Y(y) = 0.6 + 0.4  
F_Y(y) = **1**

---

### Final Result

Marginal distribution of **Y**:

| Y | P(Y) |
|---|------|
| 2 | 0.6 |
| 4 | 0.4 |

Cumulative distribution function:

F_Y(y) = 0 , for y < 2  

F_Y(y) = 0.6 , for 2 ≤ y < 4  

F_Y(y) = 1 , for y ≥ 4
