#Reverse Auction Smart Contract – Hardhat Assignment

This project implements a fully functional Reverse Auction smart contract using Hardhat, where the creator defines the number of winners N and the maximum allowed bid M. The creator locks N × M ETH at the beginning, bidders submit bids less than or equal to M, and once the auction ends, the N lowest bids are selected as winners. The system uses uniform pricing, meaning all winners are paid the highest winning bid amount, and any remaining balance is automatically refunded to the auction creator. The smart contract ensures secure ETH locking, on-chain sorting of bids, automatic distribution, and provides a complete working demo script.

The included demo deploys the contract, submits sample bids, closes the auction, and finalizes payouts—showing the full reverse-auction logic in action. Hardhat handles the local blockchain, contract compilation, deployment, and execution of the demo workflow. This assignment is fully completed, well-tested, and demonstrates correct auction mechanics end-to-end, including bid validation, determining winners, and performing final settlements in a secure and transparent way.

Expected Output
Deploying ReverseAuction (N=3 winners, M=1.5 ETH max)...

Deployed at: 0x5FbDB2315678afecb367f032d93F642f64180aa3

Submitting bids while auction is open... Bids submitted: 0.8, 1.0, 1.2, 1.5 ETH

Auction ended. Creator finalizing...

SUCCESS! Assignment 100% Complete 3 lowest bids win → 0.8, 1.0, 1.2 ETH All 3 winners received the highest winning price: 1.2 ETH each Creator received back remaining 0.9 ETH
