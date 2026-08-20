Black-Scholes Option Pricing Model

A Python tool to calculate the fair price of Call and Put options using the Black-Scholes model.

Overview

The Black-Scholes model estimates the theoretical price of European-style options based on:

Underlying asset price (S)
Strike price (K)
Time to expiration (T)
Risk-free interest rate (r)
Volatility of the underlying asset (σ)

This notebook implements the closed-form Black-Scholes formula and computes Call and Put option prices, along with the key Greeks (Delta, Gamma, Vega, Theta, Rho) that measure the option's sensitivity to each input.

Tools Used
Python
NumPy, SciPy (for the cumulative normal distribution function)
Jupyter Notebook
How to Run

Open Black-Scholes-Option-Pricing-Model.ipynb in Jupyter and run all cells. Adjust the input parameters (S, K, T, r, σ) to price different options.

Why This Matters

Black-Scholes is the foundational model in options pricing theory and is still used as a benchmark across derivatives desks, despite its simplifying assumptions (constant volatility, no dividends, European exercise only).
