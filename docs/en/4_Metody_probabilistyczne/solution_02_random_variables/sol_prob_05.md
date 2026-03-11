## Task 5 – Determining Constants in a Cumulative Distribution Function

**Problem:**

Select constants **A** and **B** such that the function

F(x) = A + B arctan(x) ,  for  −∞ < x < ∞

is the **cumulative distribution function (CDF)** of a continuous random variable **X**.

Then determine the **probability density function (PDF)** of this variable.

---

### Step 1 – Use properties of a CDF

For any cumulative distribution function:

F(-∞) = 0  
F(∞) = 1

We use the limits of the arctangent function:

arctan(-∞) = -π/2  
arctan(∞) = π/2

---

### Step 2 – Apply the limits

For x → -∞:

F(-∞) = A + B(-π/2) = 0

A - Bπ/2 = 0

A = Bπ/2

---

For x → ∞:

F(∞) = A + B(π/2) = 1

Substitute A = Bπ/2:

Bπ/2 + Bπ/2 = 1

Bπ = 1

B = 1/π

---

### Step 3 – Find A

A = Bπ/2

A = (1/π)(π/2)

A = 1/2

---

### Step 4 – Final CDF

F(x) = 1/2 + (1/π) arctan(x)

---

### Step 5 – Find the probability density function

The density function is the derivative of the CDF:

f(x) = dF(x)/dx

The derivative of arctan(x) is:

d/dx (arctan(x)) = 1/(1 + x²)

Therefore:

f(x) = (1/π) · 1/(1 + x²)

---

### Final Results

Constants:

A = 1/2  
B = 1/π

Cumulative distribution function:

F(x) = 1/2 + (1/π) arctan(x)

Probability density function:

f(x) = 1 / (π(1 + x²))
