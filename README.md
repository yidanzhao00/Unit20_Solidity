# Unit20_Solidity

## Overview
- In this assignment, I used Remix as the IDE to create three different ethereum powered smart contracts. 
- The reason for developing these smart contracts was to improve transaction efficiency and transparency; in the case of this assginment, they were intended to automate company finances to make transactions to employees more easier. 
____

## Contracts
- Level one contract was created to accept Ether and divide it evenly among three level employees. The contract was deployed on the local Ganache blockchain by connecting to Injected Web3 on Remix, and conducted through MetaMask under localhost:8545. After the contract successfully deployed, it can be used to send various values to employees by using the deposit function

- Level two contract was created to distribute different percentages of Ether to employee at different levels. The amount of profits that are going to be sent to the employee is based on the points multiplied by their given percentage, such as 60 representing 60%. The contract is also deployed on the local blockchain. 


- Level three was modeled traditional company stock plan. It manages 1000 shares with four equal distribution shares to employees. Instead of sending various amount of Ether to employee directly, this contract was intended to be storing deferred equity that represents the number of distributed shares the employee owns and enforcing the vetting periods automatically.
_____

## Deploy the contracts to a live Testnet
- The contract was later deployed to the Kovan network on MetaMask. The tesenet address is: 0x43570Da2bC07C5d7a9060b22B34cc2cee1Dc3CbB. Anyoner who's interested in testing the contract can send the test Ether to this address. 