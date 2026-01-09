# Black-Scholes-Option-Pricing-Model
📌 Project Overview

This project implements the Black–Scholes Option Pricing Model in Python to calculate the fair value of European call and put options.
It also includes a function to compute historical volatility using daily stock prices.

Approach: Implemented the Black–Scholes formula in Python using real market parameters.

Inputs Used: Stock price, strike price, time to maturity, risk-free rate, and volatility.

Results: Call option price = 5.63, Put option price = 9.47.

Conclusion: The model is effective for option valuation and financial decision-making.

The model is widely used in quantitative finance, derivatives pricing, and risk management.

🎯 Features

Calculates European Call Option Price

Calculates European Put Option Price

Computes annualized historical volatility

Uses log returns for volatility estimation

Based on real-world financial assumptions

Simple and modular Python functions

🛠 Tech Stack

Python

NumPy

Pandas

SciPy (Normal Distribution)

Mathematics & Statistics

📐 Financial Concepts Used

Black–Scholes Formula

Log Returns

Annualized Volatility

Risk-Free Interest Rate

Time to Maturity

Normal Distribution (CDF)

🧮 Black–Scholes Formula

Call Option:
C=SN(d1​)−Ke−rTN(d2​)

Put Option:
P=Ke−rTN(−d2​)−SN(−d1​)

Where:
d1​=ln(S/K)+(r+0.5σ^2)T/σT
​d2=d1​−σT

​​
