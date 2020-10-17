# RathCoin-Cryptocurrency
A simple cryptocurrency implemented and deployed over the Ethereum Blockchain using Solidity, the programming language of the Ethereum Virtual Machine. The code can be implemented to specify the Name of the Cryptocurrency, the max amount of Tokens, Decimals allowed and the symbol. This can then be used to send cryptocurrencies to anyone else on the Ethereum Blockchain using the public keys.

# Implementing the Code
* Open Remix online IDE. Upload the two files "RathCoin.sol" and "RathCoinInterface.sol"
* Select the right Compiler based on the Solidity version, for eg. for pragma ^0.4.18 you have to select "version:0.4.18+commit.9cf6e910.Emscripten.clang"
* The two files will be compiled on selection

![compile](/img/1.png)

* Now under "Run", in the Deploy textbox, specify the number of Tokens, Name of the Crypto, Decimals, Symbol. Select Injected web3, select your Metamask account. If you dint have one Download Metamask for Chrome, create an account (Go to end to learn how to deploy Metamask). Then hit Deploy

Confirmation through Metamask where a Few of Your Test Ethers would be spend

![confirm](/img/0M.png)

![Deploy](/img/7.png)


* When its Deployed, RathCoin will appear in the console. Copy and paste the Metamask ethereum public key in the "balanceOf" section to see the balance. It should show that you have 10000 Coins.

![Balance](/img/2.png)

* Now you can send your Crypto to other accounts. Select another VM Public key as a receiver test account. Paste it in the "transfer" section with quotes and the amount of coins you want to send with a comma. Eg, "0x66742e4Ed9EABDBdDd37D3E4c82157F13b61D24e",1000

Balance Before Sending

![BalanceBeforeSending](/img/3a.png)

Balance After Sending

![BalanceAfterSending](/img/3b.png)

![confirmation](/img/1M.png)

Debited from your account

![Debited](/img/2M.png)

Receiver After Coins have been Credited

![Credited](/img/4.png)

# RathCoin

![Interface](/img/5.png)

# Setting up Metamask

* Download the Metamask Chrome extension. Create an account. 
* When you land at the home page you will be having 0 ETH. Select "Rinkeby Test Net".

![mainpage](/img/Meta.png)

* To Acquire a few test Ethers, copy the PublicKey, which you can do you clicking on the name of the account. Then Create a twitter post by pasting that Public key. Now copy the post link and paste it here in this site and select how muhc Ethers you want.

![Funnel](/img/Meta2.png)

* Your Ethers would be transfered to your Rinkeby Test Account.

![Done](/img/Meta4.png)

* Now ehen you make any transactions or Operate your Crypto, You will get a popup. Just select Confirm

![popup](/img/Meta3.png)



Thank you

Yours Truely,

Anuraag Rath


