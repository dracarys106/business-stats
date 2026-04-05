# 📊 Retail Billing Queue Analysis

### *Operational Study using Statistical Methods*

---

## 👤 Author

**Puja Sharma**
Indian Institute of Management Bodh Gaya

---

## 📌 Overview

This project investigates **queue dynamics and service efficiency** in a neighborhood retail store in **Bodh Gaya, Bihar**. The focus is on understanding how variability in customer arrivals and billing time impacts overall system performance.

The analysis is based on **observational data collected over multiple peak-hour sessions**, and statistical tools have been applied to derive operational insights.

---

## 🧭 Table of Contents

1. [Context & Problem Statement](#context--problem-statement)
2. [Data Collection Approach](#data-collection-approach)
3. [Process Mapping](#process-mapping)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Statistical Modeling](#statistical-modeling)
6. [Sampling Analysis](#sampling-analysis)
7. [Key Findings](#key-findings)
8. [Operational Recommendations](#operational-recommendations)
9. [Limitations](#limitations)

---

## Context & Problem Statement

Retail checkout systems often experience **uneven load distribution**, especially during evening hours. In the observed store, customers frequently encountered inconsistent waiting times despite relatively stable billing speeds.

The key problem explored:

> *Is the inefficiency driven by demand variability or process limitations?*

---

## Data Collection Approach

Data was collected through **direct observation over 5 days**, focusing on peak hours (6 PM – 9 PM).

### Key Notes:

* Observations recorded manually at 10-minute intervals
* No automated system data was used
* Effort was made to cover different weekdays to reduce bias

### Variables Captured:

| Type       | Variable                 |
| ---------- | ------------------------ |
| Discrete   | Customers per 10 minutes |
| Continuous | Waiting time (minutes)   |
| Continuous | Service time (minutes)   |

---

## Process Mapping

### Checkout Flow

Customer Entry → Item Selection → Queue Formation → Billing → Exit

---

### Observations

* Queue formation is the most sensitive stage
* Billing itself remains relatively consistent
* Delays increase sharply when arrival rate exceeds service capacity

---

## Exploratory Data Analysis

### Waiting Time

* Mean: 6.8 minutes
* Median: 6.2 minutes
* Std Dev: 2.5 minutes

There is a noticeable **right-skewed distribution**, indicating occasional spikes in waiting time.

---

### Service Time

* Mean: 3.4 minutes
* Low variability across observations

This suggests that the **service mechanism is relatively stable**.

---

## Statistical Modeling

### Poisson Behavior (Arrivals)

Customer arrivals were evaluated using a Poisson framework.

* λ ≈ 5.6 customers per 10 minutes

Observed pattern:

* Random clustering in certain intervals
* Lower arrivals in others

This broadly supports the assumption of **random arrivals with moderate variability**.

---

### Interpretation

* Demand is **non-uniform and fluctuating**
* Queue length is highly sensitive to small spikes in arrivals

---

## Sampling Analysis

To assess reliability, multiple small samples (n = 5) were analyzed.

### Key Observation

Sample means were clustered within a narrow range (~6.5–7.2 minutes), despite variation in individual observations.

---

### Insight

* Average system performance is stable
* Short-term variability remains significant

---

## Key Findings

* Primary bottleneck: **Queue before billing counter**
* Variability source: **Customer arrival fluctuations**
* System behavior:

  * Stable under normal load
  * Congested under peak demand

---

## Operational Recommendations

### Immediate

* Open an additional billing counter during peak hours
* Promote faster digital payment options

---

### Medium-Term

* Introduce express checkout for customers with fewer items
* Implement basic queue management system

---

### Long-Term

* Use historical data for demand forecasting
* Optimize staff scheduling dynamically

---

## Limitations

* Sample size limited to ~50 observations
* Manual recording may introduce minor human error
* External factors (festive days, discounts) not fully accounted for
---

## 📌 Final Note

This study was conducted as part of an academic exercise at IIM Bodh Gaya, with an emphasis on applying statistical tools to real-world operational settings.

---


