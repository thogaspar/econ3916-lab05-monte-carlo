# econ3916-lab05-monte-carlo
ECON 3196 Lab 05 - Probability &amp; Simulation
# Monte Carlo Engine -- Probability & Simulation

## Objective

I used Monte Carlo simulation to study probability problems and to estimate financial risk for a $1M portfolio.

## Methodology

- Simulated 10,000 coin flips and plotted the running share of heads.
- Simulated 10,000 Monty Hall games and counted how often switching won.
- Simulated a disease screening test on 100,000 people, using a prevalence of 1%, a sensitivity of 95% and a specificity of 90%.
- Simulated outcomes for a $1M portfolio and computed Monte Carlo Value at Risk (VaR) and Expected Shortfall (ES) from them.
- Estimated pi by random sampling and checked that the Monte Carlo error shrinks like 1/sqrt(n).

## Key Findings

- **Coin flips:** The running share of heads settled as the number of flips grew.
- **Monty Hall:** Switching won 67% of the 10,000 games.
- **Disease screening:** Only 8.8% of positive tests were people who were actually sick. The disease is rare, so most positive results were false positives.
- **Portfolio risk:** The 95% VaR is $19,494 and the 95% ES is $24,230. ES is larger because it averages the losses beyond the VaR threshold.
- **Convergence:** The pi estimate confirmed that the error shrinks like 1/sqrt(n), so a more precise estimate needs many more samples.
