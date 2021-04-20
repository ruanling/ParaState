# ParaState
Tutorial: How To Develop, Deploy &amp; Test An Smart Contract To The ParaState Testnet

Introduction
This article explains step-by-step instructions on using the BUIDL online IDE, created by Second State, to develop and test a Smart Contract to the ParaState testnet:

We have started a blockchain testnet with the ParaState Frontier software, and the web3 RPC endpoint is
https://rpc.parastate.io:8545/
We’ll do this in 5 steps:
1. Setup
2. Creating Our Project
3. Writing The Smart Contract
4. Compile and Migrate
5. Testing

1. Setting Up
Use account on metamask wallet
Add the Parastate Custom RPC network according to the parameters below:
• Network Name: ParaState
• New RPC URL: https://rpc.parastate.io:8545
• Chain ID: 123
• Currency Symbol (Optional): STATE

Add the Parastate Custom RPC network
Go to http://faucet.parastate.io/, enter the address of the wallet you just created in Step 2, click Submit to receive STATE Testnet. Everyone will receive the testnet STATE token in the wallet.

2. Creating Our Project
Load BUIDL for ParaState in your browser: http://buidl.secondstate.io/parastate
Import the MetaMask account address into the BUIDL Account

3. Writing The Smart Contract
The full working project code is available on Github. https://github.com/ruanling/ParaState/

4. Compile and Migrate
After deploying is complete, you will receive the token address

5. Testing
At this point, you have created your own token
Now we will test sending the token to a different wallet address

Done
Well done, you developed, tested and deployed your very own Smart Contract to the ParaState testnet. I hope this will inspire you to experiment more with Blockchain in general.
Happy coding.
