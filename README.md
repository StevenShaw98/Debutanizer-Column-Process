# Debutanizer-Column-Process

📖 Overview

This repository contains the benchmark dataset for the **Debutanizer Column** process — a widely used industrial dataset in the field of **soft sensor development**, **process monitoring**, and **data-driven modeling** for petroleum refining.

The dataset originates from a real debutanizer distillation column operating in a petroleum refinery (Fortuna et al., 2007) and has been extensively used in the literature to benchmark machine learning and statistical models.


🏭 Process Background

### What is a Debutanizer Column?

A debutanizer column is a distillation tower that is an integral part of any petroleum refinery. It belongs to the **NGL (Natural Gas Liquid) fractionation train**, which typically consists of up to five distillation towers in series:

```
Demethanizer → Deethanizer → Depropanizer → Debutanizer → Butane Splitter
```

In the debutanizer column, **C3 (propane)** and **C4 (butane)** are removed as overheads from the naphtha stream. The primary goal is to separate butane (C4H10) from heavier hydrocarbon fractions, contributing to the production of **Liquefied Petroleum Gas (LPG)**.

### Why Online Monitoring Matters

Online composition monitoring of the debutanizer column outlet streams is highly desirable in order to maximize LPG production and ensure product quality. Because direct analyzers are expensive and slow (subject to significant time delays), **data-driven soft sensors** are used to infer the butane concentration in the bottom product in real time using readily available process measurements.


### Variables

| Column | Variable | Role | Description |
|--------|----------|------|-------------|
| `u1` | Input 1 | Feature | Process variable 1 |
| `u2` | Input 2 | Feature | Process variable 2 |
| `u3` | Input 3 | Feature | Process variable 3 |
| `u4` | Input 4 | Feature | Process variable 4 |
| `u5` | Input 5 | Feature | Process variable 5 |
| `u6` | Input 6 | Feature | Process variable 6 |
| `u7` | Input 7 | Feature | Process variable 7 |
| `y`  | Output  | Target | Butane (C4) concentration in the bottom product |


## 📚 References
L. Fortuna, S. Graziani, and M. Xibilia, “Soft sensors for product quality monitoring in debutanizer distillation columns,” Control Engineering Practice, vol. 13, DOI 10.1016/j.conengprac.2004.04.013, no. 4, pp. 499–
508, 2005.
