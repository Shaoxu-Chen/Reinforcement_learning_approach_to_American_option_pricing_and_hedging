# Reinforcement Learning for American Option Pricing & Hedging
**Author:** 陈少旭 (Shaoxu Chen)  
**MSc (Financial Mathematics)** — University of Manchester.  
Project code & notebooks: https://github.com/Shaoxu-Chen/Reinforcement_learning_approach_to_American_option_pricing_and_hedging/edit/main

## Project summary
This project implements and compares four approaches for pricing & hedging American put options in a discrete Black-Scholes setting:
- Binomial tree (CRR)
- Least-Squares Monte Carlo (LSM)
- QLBS (Q-learning for Black-Scholes)
- Fitted Q-Iteration (FQI)

Key contributions:
- Unified Python framework reproducing classical and RL-based algorithms under identical market assumptions. 
- Robustness checks (regression diagnostics, hedging error statistics) and runtime benchmarking. 

## How to run (quick)
1. Clone repo and create virtual env:
```bash
git clone <your-repo>
cd repo
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
