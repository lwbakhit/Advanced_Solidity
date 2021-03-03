# CrowdSale.sol Design



## PupperCoin Crowdsale

First we are going to work off the PupperCoin.sol 

![puppercoin](Screenshots/puppercoin_sol.PNG)

------

You will need to bootstrap the contract by inheriting the following OpenZeppelin contracts:

* `Crowdsale`

* `MintedCrowdsale`

* `CappedCrowdsale`

* `TimedCrowdsale`

* `RefundablePostDeliveryCrowdsale`

![code](Screenshots/crowdsale1.PNG)

-----

## Testing the Crowdsale

Test the crowdsale by sending Ether to the crowdsale from a different account. You can see below how the contract was deployed and the different addresses used are filled in to the deployment.

![deploy](Screenshots/deploy1.PNG)
![deploy](Screenshots/deploy2.PNG)

-----

## Transacting the Crowdsale

After deploying the contract, it was time to run a test and make sure the Transaction was successful. 

![transact](Screenshots/transact.PNG)
![success](Screenshots/success2.PNG)