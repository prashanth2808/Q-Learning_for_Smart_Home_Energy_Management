# Q-Learning for Smart Home Energy Management (HEMS)

**RL Assignment 1 | Dr. JBS (Dr. Simha) | REVA University**
**Student:** Prashanth S | **SRN:** R24MSA09 | **Program:** M.Sc in AI | **Batch:** FT 3

---

## Reference Paper

> Razghandi et al. (2021). Smart Home Energy Management: Sequence-to-Sequence Load Forecasting and Q-Learning.
> IEEE GLOBECOM 2021 | arXiv:2109.12440

---

## 5 Extensions

| # | Extension | Key Result |
|---|-----------|-----------|
| 1 | Reproduction (Q-Learning HEMS) | 18-23% cost savings vs baseline |
| 2 | Q-Learning vs SARSA | Q-Learning wins (lower cost, faster convergence) |
| 3 | Hyperparameter Analysis (a x g sweep) | Best: a=0.1, g=0.99 |
| 4 | Three Pricing Schemes | Time-of-Use gives highest savings (~23%) |
| 5 | Convergence Analysis (5 seeds) | Q-Learning more stable than SARSA |

---

## Repository Structure

```
HEMS_code_implementation.ipynb        # Main notebook with all code + results
R24MSA09_Prashanth_RL_assignment.docx # Research paper (Word)
R24MSA09_Prashanth_RL_assignment.pdf  # Research paper (PDF)
RL_assignment_ppt.pptx                # Presentation slides
results/
    01_reproduction.png               # Q-Learning reward curve
    02_ql_vs_sarsa.png                # Algorithm comparison
    03_hyperparameter_sweep.png       # Hyperparameter heatmap
    04_pricing_schemes.png            # Three pricing schemes
    05_convergence.png                # Convergence analysis
```

---

## How to Run

```bash
pip install numpy matplotlib seaborn tqdm
jupyter notebook HEMS_code_implementation.ipynb
```
