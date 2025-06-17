#📈Comparative Analysis of European Option Pricing using Binomial Trees and Black Scholes Model

Welcome to our Finclub Summer 2025 project! This repository presents a comparative study of two foundational models used in European option pricing: the Binomial Tree model and the Black-Scholes closed-form formula.

📌 Problem Statement
This project aims to:

Implement pricing algorithms for European call and put options using:

✅ Binomial Tree method (with adjustable steps)

✅ Black-Scholes formula (including Option Greeks)

Compare mathematical assumptions (discrete vs. continuous time, volatility, etc.)

Study convergence of Binomial prices to Black-Scholes values

Analyze sensitivity to:

Volatility (σ)

Time to maturity (T)

Risk-free interest rate (r)

Strike price (K)

Validate with real market data (e.g., SPY, AAPL) and assess model performance

🧠 Key Learnings
Binomial model offers flexibility but increases in complexity with time steps.

Black-Scholes is efficient and elegant, but depends on strict assumptions (constant volatility, log-normal returns).

Real-world data introduces imperfections that influence model accuracy.

🛠 Tech Stack
Python 🐍

NumPy, Pandas

Matplotlib for plotting

yFinance for data extraction

📊 Features Implemented
✅ Binomial Tree option pricer with custom steps

✅ Black-Scholes pricer with Greeks (Delta, Gamma, Theta, Vega, Rho)

✅ Price convergence visualizations

✅ Sensitivity analysis for key parameters

✅ Market comparison with real option data

✅ Performance report covering:

Pricing accuracy

Computational speed

Error convergence over steps

📁 Project Structure
├── European_Option_Pricing_Comparison.ipynb  # Main project notebook
├── README.md                                # This file
📌 Limitations
Black-Scholes assumes constant volatility & risk-free rates.

Binomial model becomes slow for large time steps.

Market options pricing may involve American-style assumptions, causing slight mismatches.

📚 References
Options, Futures and Other Derivatives – John C. Hull (Chapters 10–13, 15)

yFinance documentation

Quantitative finance blogs and Python tutorials

📬 Contact
For any queries, suggestions, or contributions, feel free to reach out!
