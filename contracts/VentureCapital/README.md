# Venture Capital Sharing

Experimental Solidity Smart Contract to find the right balance between VCs and startup. Both sides have rules to respect into this contract and get rewarded only if tasks are completed 

# Team rules

Team get dynamic 1% of circulating supply or 1.25% if mktcap > 1000 ETH. So at any point the team can call this function which will withdraw up to 1% of the circulating supply.

For example if the circulating supply is 1000 tokens and the team has already taken 5 previously they are now due another 5. As the funds come in to the contract the circulating supply increases meaning the team has more funds to work with.

# VCs rules

There are two VC's with different terms:-

VC1 has 1m tokens owed linearly over 1 year with a 2x bonus if token price doubles
VC2 has 2m tokens owed linearly over 4 years with a 3x bonus if/when TVL goes over 100 ETH