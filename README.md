# EthAvax_Function_frontend

This program utilizes both Javascript and Solidity to create a localhost website. The Javascript code serves as the frontend interface, while the Solidity code handles the backend interactions with Ethereum. The program aims to showcase how the JS frontend communicates with the Solidity backend to execute smart contract transactions seamlessly.

# Description

This program mimics an ATM, enabling users to withdraw and deposit funds based on their specified amounts. It employs JavaScript for the user-facing frontend, seamlessly interfacing with Solidity on the backend to execute the desired transactions. The program utilizes the Hardhat node to ensure that no actual cryptocurrency is involved, preventing any real-world financial losses during execution. This program serves as an illustrative example of how JavaScript effectively communicates with Solidity to perform smart contract transactions within a web-based setting.

# Getting Started

# Executing program
To run this program, you can clone this repository into your local machine, or you can use Gitpod (https://www.gitpod.io) to run the program online. Once you're done cloning, you can set up the localhost website by following these steps:
1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code or Gitpod
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. Typically at http://localhost:3000/

Make sure to check whether your port 8545 is made public, and make sure to also set up your MetaMask by adding your localhost network as a custom network within MetaMask.

# Authors

Marvin Simsiman

# License

This project is licensed under the MIT License - see the LICENSE.md file for details
