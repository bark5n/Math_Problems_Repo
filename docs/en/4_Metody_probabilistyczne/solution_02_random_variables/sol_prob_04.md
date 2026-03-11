## Task 4 – Exponential Distribution

**Problem:**

The time **X** of failure-free operation of a device is a continuous random variable with density:

f(x) = (1/λ) · exp(-x/λ) for x > 0  
f(x) = 0 for other x

This is the **exponential distribution**.  
The parameter is:

λ = 10

We need to:

1. Calculate the probability that the device operates without failure from **5 to 10 hours**.
2. Determine the **cumulative distribution function (CDF)**.

---

### Step 1 – Cumulative Distribution Function

For the exponential distribution the CDF is:

F(x) = P(X ≤ x)

F(x) = 1 − exp(-x/λ)  for x > 0

With λ = 10:

F(x) = 1 − exp(-x/10)

---

### Step 2 – Probability for the interval 5 ≤ X ≤ 10

For a continuous variable:

P(5 ≤ X ≤ 10) = F(10) − F(5)

Substitute the CDF:

F(10) = 1 − exp(-10/10)  
F(10) = 1 − exp(-1)

F(5) = 1 − exp(-5/10)  
F(5) = 1 − exp(-0.5)

Now compute:

P(5 ≤ X ≤ 10) = (1 − exp(-1)) − (1 − exp(-0.5))

P(5 ≤ X ≤ 10) = exp(-0.5) − exp(-1)

---

### Step 3 – Numerical value

exp(-0.5) ≈ 0.6065  
exp(-1) ≈ 0.3679

P(5 ≤ X ≤ 10) ≈ 0.6065 − 0.3679

P(5 ≤ X ≤ 10) ≈ **0.2386**

---

### Final Results

Cumulative distribution function:

F(x) = 1 − exp(-x/10)

Probability of operating without failure between 5 and 10 hours:

P(5 ≤ X ≤ 10) ≈ **0.2386**
