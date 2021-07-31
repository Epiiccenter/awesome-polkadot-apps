
## Applications
- Stablecoin can use an oracle to bring in data of the exchange rate of assets, in order to peg their value to a real world currency
- Synthetic assets use oracles as price feeds to determine if the underlying cryptocurrency sufficiently collateralizes the debt position.
- Prediction markets use oracles to decide the outcome of real world events and determine the payout of the prediction shares.
- Decentralized insurance markets use oracles to bring in information about whether a claim is valid or not.

## Architecture
- Oracle solutions range from centralized and trusted to decentralized and game-theory based. 
- On the centralized end of the spectrum, an oracle could be a single account that has the authority to dictate the real-world data on-chain. 
- On the decentralized end, a complex game of "chicken" can be played among various staked actors 
- These actors have the risk getting slashed if they don't submit the same data as everyone else. Solutions such as ChainLink fit somewhere in the middle, where the amount of trust you put into the reporting oracles can be adjusted based on your preferences.
