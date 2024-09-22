# Monte Carlo Simulations
This is a numerical algorithm to solve mathematical problems by random sampling.

Introduction about Monte Carlo simulations describing the general mathematical idea with references can be found [here](https://github.com/GautamGopalKrishnan/montecarlo/wiki) in the wiki for this project in this github repository.

We use this algorithm in 2 different applications:

- Estimating mathematical constants ($\pi, e, \gamma, \sqrt2, \phi, \delta_s$)\
The simulations can be found in [MonteCarloSimulation_EstimatingConstants.ipynb](MonteCarloSimulation_EstimatingConstants.ipynb)

- Estimating stock market prices in the future\
The simulations can be found in [MonteCarloSimulation_Stocks.ipynb](MonteCarloSimulation_Stocks.ipynb)

## Installation
Install by cloning the repository with

    git clone https://github.com/GautamGopalKrishnan/montecarlo.git

## Estimating Constants
The following mathematical constants were estimated using Monte Carlo simulations.

- $\pi$
- $e$ (Euler's number)
- $\gamma$ (Euler's constant)
- $\sqrt2$
- $\phi$ (Golden Ratio)
- $\delta_s$ (Silver Ratio)

The wiki page for this project in this github repository has descriptions of the methods behind the Monte Carlo simulations to estimate each of these constants, and can be found here:

[https://github.com/GautamGopalKrishnan/montecarlo/wiki/Estimating-Mathematical-Constants](https://github.com/GautamGopalKrishnan/montecarlo/wiki/Estimating-Mathematical-Constants)

## Stock Indices
We estimate the prices in the future for the following stock indices using Monte Carlo simulations.

- NIFTY 50
- NIFTY 100
- NIFTY 200
- NIFTY 500
- NIFTY Next 50
- BSE 500

Historical Data for each of these indices from January, 1990 to August, 2004 is publicly available (courtesy of National Stock Exchange of India for indices owned by NSE). They are available on this github repository and have been used to estimate prices in the future.

Details about the Monte Carlo implementation are available on the wiki page for this project in this github repository and can be found here:

[https://github.com/GautamGopalKrishnan/montecarlo/wiki/Estimating-prices-of-Stock-Indices](https://github.com/GautamGopalKrishnan/montecarlo/wiki/Estimating-prices-of-Stock-Indices)
