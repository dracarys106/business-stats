# 📊 Business Statistics I Assignment

### Operational Analysis of Queue Waiting Time in Service Systems

---

## 👤 Author

**Puja Sharma**
Indian Institute of Management Bodh Gaya

---

## 📌 Table of Contents

* [1. Introduction](#1-introduction)
* [2. Data Source](#2-data-source)
* [3. Part A: Process Understanding](#3-part-a-process-understanding)
* [4. Part B: Descriptive Statistics](#4-part-b-descriptive-statistics)
* [5. Part C: Discrete Distribution](#5-part-c-discrete-distribution)
* [6. Part D: Continuous Distribution](#6-part-d-continuous-distribution)
* [7. Part E: Sampling Distribution](#7-part-e-sampling-distribution)
* [8. Part F: Operational Insights](#8-part-f-operational-insights)
* [9. Graphical Analysis](#9-graphical-analysis)
* [10. Conclusion](#10-conclusion)
* [11. References](#11-references)

---

## 1. Introduction

This study analyzes operational inefficiencies in queue-based service systems using statistical tools. The focus is on waiting time variability and service efficiency.

---

## 2. Data Source

Secondary data is used from:

* Kaggle: Queue Waiting Time Prediction Dataset
* Research study on queue systems

---

## 3. Part A: Process Understanding

### Process Flow

Arrival → Queue → Service → Exit

### Bottlenecks

* Queue congestion
* Limited service counters

### Variability

* Demand-driven (arrivals)
* Process-driven (service time)

---

## 4. Part B: Descriptive Statistics

| Metric  | Waiting Time |
| ------- | ------------ |
| Mean    | 6.8          |
| Median  | 6.2          |
| Std Dev | 2.5          |
| CV      | 0.37         |

**Interpretation:** Moderate variability, unstable during peak hours.

---

## 5. Part C: Discrete Distribution

* λ ≈ 5.6 customers

Arrivals follow **Poisson distribution**

**Implication:** Random demand → flexible staffing needed

---

## 6. Part D: Continuous Distribution

* Right-skewed waiting time
* Most values: 4–8 minutes
* Few extreme delays

---

## 7. Part E: Sampling Distribution

Sample Means:
6.2, 7.1, 6.5, 7.4, 6.8, 7.0, 6.3, 7.2, 6.9, 6.6

**Insight:** Reliable but small variation exists

---

## 8. Part F: Operational Insights

* Bottleneck: Service counter
* Variability: Demand-driven
* System: Overburdened during peak

### Recommendations

* Add counters
* Queue management system
* Demand forecasting

---

## 9. Graphical Analysis

### 📈 Waiting Time Distribution

![Histogram](graphs/histogram.png)

### 📊 Sampling Distribution

![Sampling](graphs/sampling.png)

---

## 10. Conclusion

Demand variability is the key driver of inefficiency. Proper staffing and system design can reduce waiting time.

---

## 11. References

* https://www.kaggle.com/datasets/sanjeebtiwary/queue-waiting-time-prediction
* https://www.researchgate.net/publication/339228555

---


