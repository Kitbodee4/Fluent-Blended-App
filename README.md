# Guide to Build HelloWorld (Blended App) on Fluent Devnet

<img src="https://images.mirror-media.xyz/publication-images/_89lCC1I0m5JlMwv14wo3.png?height=360&width=720" width="700"/>

## About Fluent
The first blended execution network. Fluent blends Wasm, EVM, and SVM apps into a unified execution environment.
* [Twitter](https://x.com/fluentxyz)
* [Website](https://fluent.xyz/)
* [Discord](https://discord.gg/fluentlabs)
* [Docs](https://docs.fluentlabs.xyz/learn/introduction/what-is-fluent)
* [Github](https://github.com/fluentlabs-xyz)
* [Devnet Explorer](https://blockscout.dev.thefluent.xyz/)

For more information about Fluent, you can find my article "Fluent: Simplifying Blockchain Technology with Blended Execution" from [this link](https://mirror.xyz/kocality.eth/orzqskeUXS_lefo0oo99nB9r21wdKzJGp7gfquYdLlc).

## About Guide
This guide provides step-by-step instructions to create a Blended (HelloWorld) application on Fluent Devnet. The application consists of a Rust smart contract that prints "Hello" and a Solidity smart contract that prints "World." This setup demonstrates:

- **Composability:** Integrating different programming languages (Solidity and Rust) into a single application.
- **Interoperability:** Ensuring smooth operation between different virtual machine targets (EVM and Wasm).

By following this guide, you will learn how to:

- Combine different programming languages into one project.
- Ensure seamless operation across various virtual machine targets.
- Manage everything within a unified execution environment.

## Setup Instructions

### Step 1: Clone the Repository
Clone this repository to your local machine:

git clone https://github.com/Kitbodee4/Fluent-Blended-App.git
cd Fluent-Blended-App

Step 2: Set Up Environment Variables
Edit the setup.sh file to add your private key:

nano setup.sh
Replace your-private-key-here with your actual private key in the following line:
DEPLOYER_PRIVATE_KEY=  PRIVATE_KEY

Step 3: Run the Setup Script
Run the setup script to install dependencies, set up the project, and deploy the contracts:

chmod +x setup.sh
./setup.sh

Additional Information
For more details on configuring and customizing your project, refer to the Fluent Devnet documentation.
