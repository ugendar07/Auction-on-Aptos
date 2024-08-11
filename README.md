# Auction on Aptos

## Overview

This project implements a first-price auction smart contract on the Aptos blockchain. In a first-price auction, participants bid on an item, and the highest bid wins, paying the price they bid. The smart contract facilitates the auction process, ensuring transparency, fairness, and security.


## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Python3](https://www..org/)
- [Move](https://aptos.dev/en/build/smart-contracts/book)
    
    ```curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3``` 

 

### Installation

1. Clone the repository:

   git clone [Auction-on-Aptos](https://github.com/ugendar07/Auction-on-Aptos.git)
   
   ```
   aptos move init --name Auction-on-aptos
   cd Auction-on-aptos
   aptos init --network devnet
    
   ```
2. Compile the code:
    ```
    aptos move compile
    aptos move test
    ```
3. Publish the Code on Devnet:
   
     ```
     aptos move publish
     ```

## Acknowledgments
- The Aptos Blockchain community for providing a robust platform for Smart Contract.

## Contact
For questions or inquiries, please contact [ugendar](mailto:ugendar07@gmail.com) .
