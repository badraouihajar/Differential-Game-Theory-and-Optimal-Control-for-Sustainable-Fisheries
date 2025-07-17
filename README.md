# 🎣 Differential Games and Optimal Control in Fisheries

This repository presents the work carried out during my final Master's internship at **UM6P (Mohammed VI Polytechnic University)** in 2024.

 **Internship Topic**:  
*Differential Game Theory and Applications: Sustainable Management of Fishery Resources*

 **Master’s Program**: Applied Mathematics – Mathematical Modelling  
 **University**: Mohammed V University of Rabat (UM5)  
 **Internship Host**: Mohammed VI Polytechnic University (UM6P)  
 **Supervisor**: Prof. Lahcen MANIAR, Prof. Nadia RAÏSSI, Prof. Mustapha SERHANI  
 **Author**: Hajar BADRAOUI  
 **Defense Date**: July 18, 2024  

---

##  Project Overview

The objective of the internship was to study **differential game theory** and apply it to ecological and economic modeling, particularly for the **sustainable exploitation of fishery resources**.

Key themes:

-  **Optimal control** for single-resource users
-  **Differential games** modeling competition between multiple fishermen
-  **Nash equilibrium** strategies under resource dynamics

---

##  Mathematical Models

### 1. Optimal Control Problem

$$
\max_E \int_0^\infty (pqx(t) - c)E(t) e^{-\delta t} dt
$$

Subject to:

$$
\dot{x}(t) = rx(t) \left(1 - \frac{x(t)}{K} \right) - qE(t)x(t)
$$

### 2. Differential Game Problem (multi-player)

Each fisherman maximizes their profit while impacting the shared resource:

$$
\max_{E_i} \int_0^\infty (p_i q_i x(t) - c_i)E_i(t) e^{-\delta_i t} dt
$$

The competition is captured via **interconnected control dynamics**.

---

## ⚙ Tools and Methods

- Pontryagin’s Maximum Principle for optimal control
- Derivation of **closed-form equilibrium strategies**
- Use of **Hamilton–Jacobi–Bellman inequalities**
- Numerical simulation of biomass and harvesting trajectories

---

##  Results

- Long-term behavior of fish biomass
- Comparison of exploitation strategies (solo vs competitive)
- Characterization of Nash equilibrium efforts
- Interpretation of sustainability and policy implications

---

##  Future Work

- Explore **cooperative game frameworks**
- Study **Stackelberg equilibria** between leaders and followers
- Apply models to multi-species or spatially distributed fisheries

---

##  References

- Haurie, A., Krawczyk, J.B., & Zaccour, G. (2012). *Games and Dynamic Games*  
- Conrad, J., & Clark, C. (1987). *Natural Resource Economics*  
- Raïssi, N., Sanogo, C., & Serhani, M. (2019). *Differential Game Model for Sustainability Multi-Fishery*

---

## 📎 License

This repository is shared for academic and educational purposes only.  
© 2024 Hajar BADRAOUI – Master student at UM5, internship hosted at UM6P
