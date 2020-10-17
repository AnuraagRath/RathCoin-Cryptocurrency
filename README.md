# RathCoin-Cryptocurrency
A simple cryptocurrency implemented and deployed over the Ethereum Blockchain using Solidity, the programming language of the Ethereum Virtual Machine. The code can be implemented to specify the Name of the Cryptocurrency, the max amount of Tokens, Decimals allowed and the symbol. This can then be used to send cryptocurrencies to anyone else on the Ethereum Blockchain using the public keys.

# Implementing the Code
* Open Remix online IDE. Upload the two files "RathCoin.sol" and "RathCoinInterface.sol"
* Select the right Compiler based on the Solidity version, for eg. for pragma ^0.4.18 you have to select "version:0.4.18+commit.9cf6e910.Emscripten.clang"
* The two files will be compiled on selection

![compile](/img/1.png)

* Now under "Run", in the Deploy textbox, specify the number of Tokens, Name of the Crypto, Decimals, Symbol. Select JavaScript VM, if u dont have a Metamask account with Test Ethers. Select any free account. Then hit Deploy

![Deploy](/img/6.png)

* When its Deployed, RathCoin will appear in the console. Copy and paste the VM ethereum public key in the "balanceOf" section to see the balance. It should show that you have 10000 Coins.

![Balance](/img/2.png)

* Now you can send your Crypto to other accounts. Select another VM Public key as a receiver test account. Paste it in the "transfer" section with quotes and the amount of coins you want to send with a comma. Eg, "0x66742e4Ed9EABDBdDd37D3E4c82157F13b61D24e",1000

Balance Before Sending

![BalanceBeforeSending](/img/3a.png)

Balance After Sending

![BalanceAfterSending](/img/3b.png)

Receiver After Coins have been Credited

![Credited](/img/4.png)

# RathCoin

![Interface](/img/5.png)


Thank you

Yours Truely,

Anuraag Rath


