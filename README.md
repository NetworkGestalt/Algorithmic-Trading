# University of Edinburgh - Undergraduate Research Assistantship Scheme (UGRA) with Dr. Tiancheng Sun: Simulating the Turtle Trading System

This past summer, I had the opportunity to assist __Dr. Tiancheng Sun__ with his research on technical trading strategies in structural economic models. I simulated one such strategy, the "Turtle Trading System", a legendary risk-adaptive, trend-following strategy from the 1980's, in Python to better understand the drivers of its performance. In the simulations, I unleashed the Turtle Trading System on prices modelled by Geometric Brownian Motion (GBM) and conditional heteroskedasticity (GARCH). I analyzed its behaviours from a deterministic and stochastic perspective, concluding with suggestions for improving its risk-reward profile. 

# Contents:
The two notebooks in this repository contain the Python code of the simulation and statistical analysis of the Trading Strategy:
- "__The Turtle Strategy (full)__" simulates and analyzes the original Turtle Trading System (https://www.tradingwithrayner.com/wp-content/uploads/2014/11/OriginalTurtleRules.pdf).
    1. Definition of Turtle Trading System rules (System 1 and System 2)
    2. Simulation of TTS with Geometric Brownian Motion (GBM).
    3. Monte Carlo analysis of System 1 and System 2 (GBM).
    4. Simulation of TTS with GBM and Conditional Volatility (GARCH).
    5. Monte Carlo of System 1 and System 2.
    6. Improving the Turtle Trading System's Return/Max Drawdown.

- "__The Turtle Strategy (simplified)__" simulates and analyzes a simplified version of the original Turtle Trading System that emphasizes its trend-following behaviours.
    1.  Definition of simplified Turtle Trading System rules.
    2.  Simulation of simplified TTS with GBM.
    3.  Monte Carlo and LAD Regression analysis of simplified TTS (GBM).
