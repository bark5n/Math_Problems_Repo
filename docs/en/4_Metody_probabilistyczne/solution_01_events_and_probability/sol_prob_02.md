# Task 2

**Problem:**

Consider an electrical circuit in which element \(a_1\) is connected in series with a block consisting of two elements \(a_2\) and \(a_3\) connected in parallel. Let \(A_i\), \(i=1,2,3\), denote the event "element \(a_i\) is functional at time \(t\)".

Using operations on events \(A_i\) and the symbols for union (∪) and intersection (∩), describe the event \(A\): "in the time interval \(t\), the current flow through the circuit will not be interrupted".

---

## Solution

### Step 1: Series and parallel rules

- **Series connection:** Current flows if **all elements in series are functional**.  
  Functional event: \(A_x \cap A_y\)

- **Parallel connection:** Current flows if **at least one element is functional**.  
  Functional event: \(A_x \cup A_y\)

---

### Step 2: Apply rules to the circuit

1. **Parallel block** (elements \(a_2\) and \(a_3\)) → current flows if:  
\[
A_2 \cup A_3
\]

2. **Series with \(a_1\)** → current flows if:  
\[
A = A_1 \cap (A_2 \cup A_3)
\]

---

### ✅ Answer

\[
\boxed{A = A_1 \cap (A_2 \cup A_3)}
\]

*Explanation:*  
For the current to flow without interruption:  
- \(a_1\) must be functional **and**  
- **either \(a_2\) or \(a_3\) (or both) must be functional**.  
