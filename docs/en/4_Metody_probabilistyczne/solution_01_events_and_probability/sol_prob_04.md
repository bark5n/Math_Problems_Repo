# Task 4 – Parallel System Reliability

**Problem:**

A fragment of an electrical network consists of two elements connected in parallel: a₁ and a₂.

Let Aᵢ (i = 1, 2) denote the event that element aᵢ remains functional for at least time t.

Given:

P(A₁) = P(A₂) = p  
P(A₁ ∩ A₂) = p²  

Find the probability of continuous current flow through the system for at least time t.

---

## Solution

In a parallel system, current flows if **at least one element** remains functional.

Therefore, the required probability is:

P(A₁ ∪ A₂)

Using the formula for the union of two events:

P(A₁ ∪ A₂) = P(A₁) + P(A₂) − P(A₁ ∩ A₂)

Substitute the given values:

P(A₁ ∪ A₂) = p + p − p²  
P(A₁ ∪ A₂) = 2p − p²  

---

## Final Answer

P(system works for at least time t) = **2p − p²**
