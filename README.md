# Reinforcement Learning for American Option Pricing & Hedging
**Author:** 陈少旭 (Shaoxu Chen)  
**MSc (Financial Mathematics)** — University of Manchester.  
Project code & notebooks: (附上你的 GitHub 链接)

## Project summary
This project implements and compares four approaches for pricing & hedging American put options in a discrete Black-Scholes setting:
- Binomial tree (CRR)
- Least-Squares Monte Carlo (LSM)
- QLBS (Q-learning for Black-Scholes)
- Fitted Q-Iteration (FQI)

Key contributions:
- Unified Python framework reproducing classical and RL-based algorithms under identical market assumptions. :contentReference[oaicite:27]{index=27}  
- Robustness checks (regression diagnostics, hedging error statistics) and runtime benchmarking. :contentReference[oaicite:28]{index=28}

## How to run (quick)
1. Clone repo and create virtual env:
```bash
git clone <your-repo>
cd repo
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
