# Black-Scholes-Option-Pricing-Model
📌 Project Overview

This project implements the Black–Scholes Option Pricing Model in Python to calculate the fair value of European call and put options.
It also includes a function to compute historical volatility using daily stock prices.

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
𝐶
=
𝑆
𝑁
(
𝑑
1
)
−
𝐾
𝑒
−
𝑟
𝑇
𝑁
(
𝑑
2
)
C=SN(d
1
	​

)−Ke
−rT
N(d
2
	​

)
Put Option:
𝑃
=
𝐾
𝑒
−
𝑟
𝑇
𝑁
(
−
𝑑
2
)
−
𝑆
𝑁
(
−
𝑑
1
)
P=Ke
−rT
N(−d
2
	​

)−SN(−d
1
	​

)

Where:

𝑑
1
=
ln
⁡
(
𝑆
/
𝐾
)
+
(
𝑟
+
0.5
𝜎
2
)
𝑇
𝜎
𝑇
,
𝑑
2
=
𝑑
1
−
𝜎
𝑇
d
1
	​

=
σ
T
	​

ln(S/K)+(r+0.5σ
2
)T
	​

,d
2
	​

=d
1
	​

−σ
T
	​

