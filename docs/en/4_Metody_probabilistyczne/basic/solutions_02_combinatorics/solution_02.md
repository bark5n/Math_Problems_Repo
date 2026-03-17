## Task 2 — Permutations

These problems involve arranging all objects where order matters.

---

### 1. Arranging 8 different books on a shelf

All books are distinct and their order on the shelf matters.

Number of arrangements:

8!

---

### 2. Two particular people must sit next to each other

Treat the two people as a single block.

Then we arrange:

7 objects (the block + 6 other people)

Number of arrangements of the block and others:

7!

Inside the block the two people can switch places:

2!

Total arrangements:

7! × 2!

---

### 3. Two people must not sit next to each other

First compute all possible seatings:

8!

Then subtract the arrangements where the two people sit together:

7! × 2!

Valid arrangements:

8! − 7! × 2!

---

### 4. Ordering 10 questions when the first question is fixed

If the first question is fixed, we only arrange the remaining 9 questions.

Number of possible orders:

9!
