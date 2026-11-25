\# Supply Chain Network Optimization Using Linear Programming



\## Project Overview



This project develops a scenario-based supply chain network optimization model using Linear Programming (LP) and Python.



The objective is to minimize estimated transportation costs while satisfying regional demand and respecting capacity constraints across five candidate distribution hubs.



The analysis uses the public Olist Brazilian E-Commerce Dataset (2016–2018).



\## Technologies Used



\- Python

\- Pandas and NumPy

\- Matplotlib and Seaborn

\- PuLP

\- HiGHS Optimization Solver

\- JupyterLab



\## Key Project Results



| Metric | Result |

|---|---:|

| Total order items | 110,197 |

| Candidate hubs | 5 |

| Customer states | 27 |

| Decision variables | 135 |

| Optimized transportation cost | R$ 1,886,042.42 |

| Unconstrained transportation cost | R$ 1,831,893.92 |

| Capacity cost premium | 2.96% |

| Best expansion candidate | RJ |

| Cost reduction from 1,000 additional RJ capacity units | R$ 8,248.07 |



\## Methodology



1\. Data cleaning and exploratory analysis.

2\. Historical freight cost analysis.

3\. Selection of five candidate hub states.

4\. Construction of a transportation cost matrix.

5\. Formulation of a Linear Programming model.

6\. Optimization using PuLP and HiGHS.

7\. Capacity sensitivity and expansion analysis.



\## Important Assumptions and Limitations



\- Candidate hubs represent states with high seller presence, not verified Olist warehouses.

\- Hub capacities are hypothetical scenario assumptions.

\- Historical freight values are used as estimated transportation-cost proxies.

\- Missing cost values are imputed using available candidate-hub averages.

\- Results represent a modeled scenario, not Olist's actual internal logistics network or verified cost savings.



\## Dataset



Olist Brazilian E-Commerce Dataset:  

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce



Dataset license: CC BY-NC-SA 4.0.



\## Author



MSc Operational Research Portfolio Project

