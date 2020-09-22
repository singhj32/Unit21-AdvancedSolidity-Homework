


# Crowdsale using Solidity
<p align="center">
<img src="./images/CrowdSale.jpg?raw=true" alt="Smart contract"/>
</p>

We used solidity to create the smart contracts needed for the CrowdSale. The custom contract we created inherited the base classes needed for creating the CrowdSale solutions. These base classes are Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.Solidity code for our custom smart contracts can be found under folder "code".

1. [PupperCoin.sol](code/PupperCoin.sol) - This file has the code to create a standard ERC20Mintable Token.
2. [Crowdsale.sol](code/Crowdsale.sol) - This file has the code to create CoinSale Contract and the CrowdSale Deployer Contract.


<br>
<br>

First we created the solidity code in **Remix** editor. While developing and testing the contracts, we used the **Ganache** development chain, and pointed **MetaMask** to **localhost:8545**
<br>
<br>

### <ins>**Deploying and testing the contracts on the localhost:**</ins>

After deploying the contracts locally, we performed transactions to confirm that the contracts work as expected and sale of tokens runs successfully without errors. Below screen shot shows the token balance after a successful purchase transaction.  

<p align="center">
<img src="./images/BuyToken1.png?raw=true" alt="Smart contract"/>
</p>
<br>


### <ins>**Deploying and testing the contracts on the Kovan Test Network:**</ins> 
After testing the contracts locally and making sure they work as expected, we deployed the contracts to Kovan Test Network.  
<p align="center">
<img src="./images/Kovan.png?raw=true" alt="Smart contract"/>
</p>
<br>

 Depolying the contracts to Kovan:
<p align="center">
<img src="./images/TGC_Deployment.png?raw=true" alt="Smart contract"/>
</p>
<br>

 Carrying out the purchase transactions for tokens and checking the balance after successful transaction:
<p align="center">
<img src="./images/TGC_Balance.png?raw=true" alt="Smart contract"/>
</p>
<br>

 

 Transaction confirmation:
<p align="center">
<img src="./images/TGC_transaction_Confirmation.png?raw=true" alt="Smart contract"/>
</p>
<br>
 

 Token and Sale information after the above transactions:
<p align="center">
<img src="./images/TGC_Info.png?raw=true" alt="Smart contract"/>
</p>
<br>
<p align="center">
<img src="./images/TGC_Sale.png?raw=true" alt="Smart contract"/>
</p>
<br>
