## Derivative Pricing

Here I have implementated the applications of Binomial and Black-Scholes models to price Derivative securities like Futures and European Call and Put options

### Derivative Pricing using the Binomial model

The binomial pricing model is primarily used to model the prices at different nodes, or points in time, usually during the current date (valuation date) and expiration date. With the model, there are two possible outcomes with each node or point of time —a up move or a down move that follow a binomial tree. Risk neutral probabilities for the up-move and the down-move are used to generate the risk-neutral price of options and futurs

### Methodology Used
- Define input variables of the models - Initial Stock Price, Strike Price (for Option pricing), Number of Binomial periods, Factor Change in Up-Move and Risk-Free Rate
- Used Numpy array to generate Stock Price Binomial Lattice
- p, q risk neutral probabilities are calculated
- Options and Futures prices is calculated using the binomial lattice and risk neutral probabilities
