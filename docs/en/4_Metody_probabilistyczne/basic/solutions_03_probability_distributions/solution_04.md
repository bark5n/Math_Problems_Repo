## Task 4 — Poisson Model (Arrival of Events)

### Problem

A web service receives on average 3 error reports per hour.  
We assume that the number of reports in a given time interval follows a Poisson distribution.

---

## 1. Description of the Random Experiment

The random experiment consists of observing the system over a fixed time interval (one hour) and counting the number of error reports that occur during that time.

Each outcome of the experiment is the total number of error reports observed in that hour.

---

## 2. Sample Space

The sample space is the set of all possible numbers of error reports:

Ω = {0, 1, 2, 3, 4, ...}

This set is infinite because there is no upper limit on how many reports may occur in a given time interval.

---

## 3. Probability Distribution

The number of events follows a Poisson distribution with parameter λ.

The probability of observing exactly k events is given by:

P(X = k) = (e^(-λ) * λ^k) / k!

where:
- k = number of events (k = 0,1,2,...)
- λ = average number of events in the interval
- e ≈ 2.71828

---

## 4. Interpretation of λ (Lambda)

The parameter λ represents the expected (average) number of events in a given time interval.

In this problem:

λ = 3

This means that, on average, the system receives 3 error reports per hour.

---

## 5. Why the Poisson Model is Used

The Poisson model is appropriate in this situation because:

- Events (error reports) occur randomly over time  
- Events occur independently of each other  
- The average rate (λ) is constant  

These conditions define a Poisson process.

---

## 6. Interpretation of the Model

The Poisson distribution allows us to answer questions such as:

- What is the probability of receiving exactly k reports in one hour?
- What is the probability of receiving no reports?
- What is the probability of receiving many reports?

Although the number of events varies randomly, it is centered around the average value λ.

---

## 7. Example

For example, the probability of receiving exactly 2 error reports in one hour is:

P(X = 2) = (e^(-3) * 3^2) / 2!

This formula can be used to compute probabilities for any number of events.

---

## 8. Key Idea

The Poisson model describes the number of events occurring in a fixed time interval when those events are random, independent, and occur at a constant average rate.

It is widely used in real-life applications such as:

- network traffic
- system failures
- customer arrivals
- error reporting systems
