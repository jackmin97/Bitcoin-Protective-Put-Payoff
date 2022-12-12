# Bitcoin-Protective-Put-Payoff
In this notebook, we will build a payoff graph for protective put by using the payoff graph of long Bitcoin spot and long 17500 strike put on Bitcoin. A protective put strategy is built by going long on a underlying asset and simultaneously buying a put option. The aim of this strategy is to protect from adverse underlying asset movement.

### 1. Import libraries
First, we will import the necessary libraries

### 2. Put payoff
We define a function that calculates the payoff from buying a put option. The function takes St which is a range of possible values of Bitcoin price at expiration, the strike price of the put option and premium of the put option as input. It returns the put option payoff.

### 3. Define parameters
We define various parameters required to calculate the put payoff. One of the parameters is the range of Bitcoin price at expiry. To calculate the Bitcoin price range at the put's expiration, we define a range for the Bitcoin price at expiry from -10% to +10% from the spot price. That is from 90% or 0.90 to 110% or 1.10 from the spot price. These range values are for illustration purposes and can be changed.

### 4. Long 17500 strike put payoff
We plot the payoff of the long 17500 strike put option.

### 5. Long Bitcoin spot payoff
We plot the payoff of the long Bitcoin spot.

### 6. Protective put payoff
The max profit is unlimited and the max loss is limited to USD 500.
