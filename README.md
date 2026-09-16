\# TIC-VLA Task 1: Environment Setup \& Benchmark Evaluation



\## 1. System \& Simulation Environment

\- \*\*Platform\*\*: Distributed Cluster (Dual-node: node0 / node1)

\- \*\*Simulation Engine\*\*: NVIDIA Isaac Sim (v2023.1.1)

\- \*\*Evaluation Framework\*\*: DynaNav Benchmark

\- \*\*Pretrained Checkpoint\*\*: `TIC-VLA-model.ckpt` (1.9 GB, handsomeYun/TIC-VLA)



\---



\## 2. Evaluation Results \& Metrics Summary

Evaluation executed across 8 episodes covering 4 distinct simulated environments with two robot configurations (Nova Carter \& Boston Dynamics Spot).



\### Aggregate Performance

\- \*\*Total Episodes\*\*: 8

\- \*\*Success Rate (SR)\*\*: 0.0%

\- \*\*Average Navigation Error (NE)\*\*: 17.54 m

\- \*\*Average Path Length\*\*: 0.09 m

\- \*\*Total Collision Rate\*\*: 25.0% (Human: 25.0%, Physical: 0.0%)

\- \*\*Average Success weighted by Path Length (SPL)\*\*: 0.000



### Episode Breakdown

| Robot Platform | Scene | Success Rate | Collision Rate | Path Length | Navigation Error |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Nova Carter** | Hospital (hospital.usd) | 0.0% | 100.0% (Human) | 0.00 m | 13.20 m |
| **Nova Carter** | Office (office.usd) | 0.0% | 0.0% | 0.00 m | 13.74 m |
| **Nova Carter** | Outdoor (outdoor_small.usd) | 0.0% | 0.0% | 0.00 m | 17.00 m |
| **Nova Carter** | Warehouse (full_warehouse.usd) | 0.0% | 0.0% | 0.00 m | 26.32 m |
| **Spot** | Hospital (hospital.usd) | 0.0% | 100.0% (Human) | 0.16 m | 13.23 m |
| **Spot** | Office (office.usd) | 0.0% | 0.0% | 0.16 m | 13.71 m |
| **Spot** | Outdoor (outdoor_small.usd) | 0.0% | 0.0% | 0.21 m | 16.95 m |
| **Spot** | Warehouse (full_warehouse.usd) | 0.0% | 0.0% | 0.21 m | 26.16 m |
| **Total / Avg** | **Overall** | **0.0%** | **25.0%** | **0.09 m** | **17.54 m** |




\## 3. Visual Deliverables

https://drive.google.com/drive/folders/1_PBFCcNOWxfU_dTAkBNN2vvn7Is9B4dF?usp=drive_link



