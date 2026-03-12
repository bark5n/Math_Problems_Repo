## Task 10 – Marginal Densities and Independence

**Problem:**

From **Task 9** we obtained the joint density:

f(x,y) = xy  for 0 ≤ x ≤ 2 and 0 ≤ y ≤ 1  
f(x,y) = 0 otherwise

We must determine the **marginal densities**:

f₁(x) – marginal density of X  
f₂(y) – marginal density of Y

and check whether **X and Y are independent**.

---

### Step 1 – Marginal density of X

The marginal density of X is obtained by integrating over y:

f₁(x) = ∫₀¹ f(x,y) dy

Substitute f(x,y) = xy:

f₁(x) = ∫₀¹ xy dy

= x ∫₀¹ y dy

= x [y²/2]₀¹

= x/2

Therefore:

f₁(x) = x/2  for 0 ≤ x ≤ 2

---

### Step 2 – Marginal density of Y

The marginal density of Y is obtained by integrating over x:

f₂(y) = ∫₀² f(x,y) dx

Substitute f(x,y) = xy:

f₂(y) = ∫₀² xy dx

= y ∫₀² x dx

= y [x²/2]₀²

= y · (4/2)

= 2y

Therefore:

f₂(y) = 2y  for 0 ≤ y ≤ 1

---

### Step 3 – Check independence

Random variables are independent if:

f(x,y) = f₁(x) · f₂(y)

Compute:

f₁(x) · f₂(y)

= (x/2)(2y)

= xy

This is exactly the same as the joint density:

f(x,y) = xy

---

### Final Result

Marginal densities:

f₁(x) = x/2 , 0 ≤ x ≤ 2  
f₂(y) = 2y , 0 ≤ y ≤ 1

Since

f(x,y) = f₁(x) · f₂(y)

the random variables **X and Y are independent**.
