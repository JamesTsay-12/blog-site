---
layout: post
title: "Building a Flexible Retirement Simulator with Python"
date: 2025-06-25
categories: [finance]
tags: [retirement, simulation, python, monte-carlo]
---

Hi everyone! 👋

I created a retirement simulation using Python — with a big assist from ChatGPT. It's a more flexible version than most retirement calculators, designed to give **probabilities** for retiring safely rather than a single pass/fail number.  I was inspired by some conversations I had with others who gave many different scenarios about the future of the world economy given recent geopolitical developments.  This is why I created inputs for many different scenarios including deciding each assets' return rate and introducing shocks in specified years  - features missing in many of the existing tools.

It’s based on a **Monte Carlo simulation with a t-distribution**, which is often used in financial models to give more realistic results under volatile conditions.



---

### 🧮 Features

The simulation includes some powerful customization options:

- **Debt inputs** (house, credit card, student loan)
- **Age-based changes** in spending and income
- **Investment withdrawals** and **tax impacts**
- **Shocks** to simulate unexpected events at critical points
- **Custom portfolio estimates** and expected returns

Right now, the simulation outputs graphs of your:
- Median scenario
- Top 25% optimistic scenario
- Bottom 25% pessimistic scenario

---

### 🛠️ How to Run It

This was a fun little project to learn Python using generative AI. Currently, it’s available as a script, but I hope to build a browser-based version in the future.

#### 🔗 Resources

- 🐍 [Python file on GitHub](https://github.com/JamesTsay-12/Finance-public-/blob/main/retirementF.py)  
- 📄 [User Manual (PDF)](https://github.com/JamesTsay-12/Finance-public-/blob/main/User_Guide_Portfolio_Simulation060425-2.pdf)

---

### 🧭 Compare With Other Tools

Here are some solid alternatives for comparison:

- [**Fidelity Retirement Calculator**](https://digital.fidelity.com/stgw/digital/planning/retirement/retirement-income-calculator/)
- [**Model Investing Simulator**](https://modelinvesting.com/retirement-calculator/)
- [**Monte Carlo Simulation**](https://www.portfoliovisualizer.com/monte-carlo-simulation?s=y&allocation1=60&allocation2=40&inflationAdjusted=true&periodicAmount=45000&adjustmentType=2&frequency=4&initialAmount=1000000&simulationModel=1&years=30&asset2=TreasuryNotes&asset1=TotalStockMarket) — A web-based Monte Carlo simulation with fewer required inputs than my tool.


Let me know what you think or if you have suggestions for improvement!
