# Fluent-Blended-App
build a blended HelloWorld application on Fluent. It combines a Rust smart contract to print “Hello” and a Solidity smart contract to print “World.”

![image](https://github.com/user-attachments/assets/292beeb4-cf1c-4c0b-a287-6c69f695990f)



# Fluent Devnet Setup

This repository contains a setup script for the Fluent Devnet.

## Prerequisites

Make sure you have the following installed:
- Git
- Screen

## Usage

1. Clone the repository:
   
   git clone https://github.com/USERNAME/fluent-devnet-setup.git
   cd fluent-devnet-setup
2. Make the setup script executable:

   chmod +x setup.sh
   
3. Run the setup script in a screen session:


   screen -S fluent -dm bash -c './setup.sh; exec bash'

The script will:

Update system packages
Install Node.js, pnpm, Rust, and Cargo
Set up a Rust project
Set up a Solidity project
Compile and deploy the contracts

Post-Setup
After the script completes, you can attach to the screen session to check the logs:

screen -r fluent
To detach from the screen session, press Ctrl + A, then D.





