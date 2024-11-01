# 🏗 Scaffold-AVS



🔧 We are building Scaffold-AVS in Hardhat. 
A tool to get started with core eigen layer contracts deploy them locally on hardhat and run your operators using docker.Using Scaffold ETH you also get chance to tickerr your contracts and try it out using frontend. In the coming versions we are also looking forward to actively deploy the contracts on holesky and register our operator to EIGEN AVS.

- ✅ **Contract Hot Reload**: The frontend auto-adapts to your smart contract as you edit it.
- 🪝 **Scaffold hooks**: Collection of React hooks wrapper around [wagmi](https://wagmi.sh/) to simplify interactions with smart contracts with typescript autocompletion.
- 🧱 **Components**: Collection of common web3 components to quickly build your frontend.
- 🔐 **Integration with Wallet Providers**: Connect to different wallet providers and interact with the AVS smart contracts.


## Functions

This dApp uses the Hello World AVS smart contracts, which includes the most basic functionalties that your AVS will probably also have. Use the Hello World AVS, or deploy your own contracts, and interact with them on your frontend dashboard. Here's an overview of all functions to interact with the AVS via the dashboard. If you want to add more, you can modify the frontend or interact with the AVS contracts via the `Debug` tab.

#### Register as operator with Eigenlayer and AVS
The first component checks if the connected wallet is registered with Eigenlayer and the AVS. Use the button to register or deregister.

#### Create task
This component is used to send a new task to the AVS. Connect your wallet to send a single task, or input your private keys and have the dApp send a task every 5 seconds.

#### Monitor tasks
The events component displays all tasks. Use the `Watch Tasks` toggle to get live updates for new tasks. By clicking the `Respond` button, the task information is copied to the Respond component fields.

#### Respond to tasks
This component is used to respond to task. Manually input the task information and response, or click the `Respond` button in the Tasks monitor to autofill for a specific task. This is only available for registered operators.

## Requirements

Before you begin, you need to install the following tools:

- [Node (>= v18.17)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)
- [Foundry](https://getfoundry.sh/)
- [Docker](https://www.docker.com/get-started/)

