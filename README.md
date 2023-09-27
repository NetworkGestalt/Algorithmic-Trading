# Undergraduate Research with Dr. Tiancheng Sun: Simulating the Turtle Trading System

In the summer of 2023, I had the opportunity to assist [Dr. Tiancheng Sun](https://sites.google.com/view/tianchengsun) with his research on technical trading strategies in structural economic models. I simulated one such strategy, the "Turtle Trading System", a legendary risk-adaptive, trend-following strategy from the 1980's, in Python to better understand the drivers of its performance. In the simulations, I unleashed the Turtle Trading System on prices modelled by Geometric Brownian Motion (GBM) and conditional heteroskedasticity (GARCH). I analyzed its behaviours from deterministic and stochastic perspectives, concluding with suggestions for improving its risk-reward profile. 

# Contents:
- "__Turtle Trading System (full)__" simulates the [original](https://www.tradingwithrayner.com/wp-content/uploads/2014/11/OriginalTurtleRules.pdf) Turtle Trading System in a more complex price environment (GBM + GARCH).
    1. Definition of Turtle Trading System (TTS) rules: System 1 and System 2
    2. Simulation of TTS with prices modelled by Geometric Brownian Motion (GBM)
    3. Monte Carlo simulation and regression analysis of System 1 and System 2 with GBM prices
    4. Simulation of TTS with GBM prices and conditional heteroscedasticity (GARCH)
    5. Monte Carlo simulation of System 1 and System 2 with GBM + GARCH prices
    6. Improving the TTS risk-return profile: Return(%)/MaxDrawdown

- "__Turtle Trading System (simplified)__" simulates a simplified version of the original Turtle Trading System, focusing on its trend-following rules in a more simple price environment (GBM).
    1.  Definition of simplified Turtle Trading System (sTTS) rules
    2.  Simulation of sTTS with prices modelled by Geometric Brownian Motion (GBM)
    3.  Monte Carlo simulation and LAD regression analysis of sTTS with GBM prices
