# ETH Daddy 

This guide will walk you through the process of setting up a decentralized application (DApp) development environment on Windows using Hardhat and Visual Studio Code.

# Creating a DApp with Hardhat on Windows using Visual Studio Code

## Prerequisites

Before you begin, make sure you have the following installed on your Windows system:

- [Node.js](https://nodejs.org/) (version 12 or higher)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
### Highlights of the project
- I have used nodejs version of 14.16.10 changed using nvm
- used vs code to write my smart contract in solidity v 0.8.9
- have used frontend from some youtube channel
- project is based on buying domain using etherum via meta metamask transactions
-![Flow drawio](https://github.com/KshitizSadh/Dapp_project/assets/142923024/b9b27e9c-4462-4aa0-9fa9-2804454cbbbb)

## Step 1: Install Hardhat

Open a terminal (Command Prompt or PowerShell) and install Hardhat globally:

```bash
npm install -g hardhat
```
![image](https://github.com/KshitizSadh/Dapp_project/assets/142923024/1d5ff5b6-0b51-4447-b549-7a611a262850)

###Step 2: Create a New Hardhat Project
1. Create a new directory for your project:
```
mkdir my-dapp
cd my-dapp
```
2. Initialize a new Hardhat project:
```npx hardhat```
Follow the prompts to choose a project type. You can select "Create an empty hardhat.config.js" for a basic setup.

### Step 3: Set Up Visual Studio Code
Open Visual Studio Code and navigate to your project directory:
```code .```
Install the recommended extensions for Solidity development:
- Solidity by Juan Blanco
- EditorConfig for VS Code
 #### Step 4: Write Smart Contracts
Inside the contracts directory, create or modify Solidity smart contract files (.sol) according to your DApp requirements.
![image](https://github.com/KshitizSadh/Dapp_project/assets/142923024/11755c4f-2ae4-4cf1-be5f-247ad097c961)

Step 5: Compile Smart Contracts
Compile your smart contracts:
```
npx hardhat compile
```
![image](https://github.com/KshitizSadh/Dapp_project/assets/142923024/3c1cf154-65df-4eea-8593-3bbb4b8d6ea8)
The compiled artifacts will be generated in the artifacts directory.
### Step 6: Write Tests
Inside the test directory, create JavaScript or TypeScript test files to test your smart contracts.
### Step 7: Run Tests
Run your tests with Hardhat:
```
npx hardhat test
```
![Screenshot (49)](https://github.com/KshitizSadh/Dapp_project/assets/142923024/d378958f-7d59-4296-b4ce-609c4f9739bc)
 ### Step 8: Deploy Smart Contracts
Write deployment scripts inside the scripts directory or modify the hardhat.config.js file to specify deployment tasks.
Deploy your contracts:
```npx hardhat run scripts/deploy.js --network <network>```
![Screenshot (50)](https://github.com/KshitizSadh/Dapp_project/assets/142923024/6fa3fc77-7516-498c-ba08-0c5140646c67)

*Replace <network> with the desired network (e.g., localhost for local development or Ethereum testnets like Ropsten, Rinkeby, etc.).*
### Step 9: Interact with Smart Contracts
Use Hardhat console or write scripts to interact with your deployed smart contracts.

### Step 10: Build the Frontend (Optional)
If you're building a frontend for your DApp, use frameworks like React, Vue.js, etc.
![image](https://github.com/KshitizSadh/Dapp_project/assets/142923024/18544698-8195-4915-b939-711ce8192a46)
![Screenshot (51)](https://github.com/KshitizSadh/Dapp_project/assets/142923024/bdf3379f-e9de-48ff-afc2-cee1bbd7646f)

### Step 11: Run the DApp
Start your DApp server (if applicable) and navigate to the frontend URL in your browser to interact with your decentralized application.

![Screenshot (52)](https://github.com/KshitizSadh/Dapp_project/assets/142923024/699c71da-330f-4699-be66-552af063962d)

# Conclusion
Congratulations! You have successfully set up a development environment for building decentralized applications using Hardhat on Windows with Visual Studio Code.


