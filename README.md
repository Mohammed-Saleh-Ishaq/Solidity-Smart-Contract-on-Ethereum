# Solidity-Smart-Contract-on-Ethereum

## setting up the environment

Folks we have a lot to set up before starting our project. But don’t worry, I’ve got you! Just follow the steps and you will be all ready!Let’s get to setting up the environment:
1. We will install and set up our Metamask account.
2. We will set up the Sepolia testnet environment.
3. We will fetch some fake money.
4. We will set up Hardhat project.
5. We will set up environment variables.

## Creating MetaMask wallet

Your metamask wallet is your key to the web3 world. It is your digital wallet to store, swap and buy cryptocurrencies, tokens, NFTs, and other amazing things in the web3 world.
MetaMask has a mobile application and a Chrome browser extension too. I personally use MetaMask on my Chrome browser extension because I do most of the work on my laptop. Anyways, 
let’s go!  
Here are the installation steps:
1. Go to MetaMask.ioClick
2. Download and Install the Chrome Extension.
3. Setup your secure password.
4. The next step is the most important one.Secure your 12-word phrase properly, never share it with anyone.
5. Write it somewhere because if you lose it, you will never have a way to recover your account. So be mindful of that.
6. Congrats! your account is created and you must have received a public address.
7. The public address will be in the pattern of:
   Example: 0x12r45...6HJ9

## Manually add Sepolia to your MetaMask
1. Use the provided information (Network name, RPC URL, Chain ID, Currency Symbol) to add the network manually.
![m-step-4 ffba6a8a](https://github.com/Mohammed-Saleh-Ishaq/Solidity-Smart-Contract-on-Ethereum/assets/117186633/2e2c454d-bda1-4a57-b257-504bafe92f65)

    Network name : Sepolia test network  
    RPC URL : https://rpc2.sepolia.org </br>
    chain ID : 11155111 </br>
    Currency : ETH </br>
2. Open MetaMask. </br>
3. Click the circle icon at the top right, then select "Settings." Navigate to "Networks" and click "Add Network."</br>
![m-step-5 e9128667](https://github.com/Mohammed-Saleh-Ishaq/Solidity-Smart-Contract-on-Ethereum/assets/117186633/3b2f9952-f799-4aa2-9fae-0f2707481718)
4. If your desired network isn't listed, scroll to the bottom and choose "Add a Network Manually."
![m-step-6 209228f9](https://github.com/Mohammed-Saleh-Ishaq/Solidity-Smart-Contract-on-Ethereum/assets/117186633/2225af14-21bc-4101-a329-8734b193ebe2)
5. Input the Network Name, RPC URL, Chain ID, and Currency Symbol. The Blockchain Explorer field can be left blank.
![m-step-7 b0a24dd6](https://github.com/Mohammed-Saleh-Ishaq/Solidity-Smart-Contract-on-Ethereum/assets/117186633/63d90a77-9337-4a3a-b183-c6162c7cf153)
6. Paste the values from the provided information and click "Save" to add the network.
7. You'll receive a success message prompting you to switch to the newly added network. Switch to it, and you'll see it displayed at the top middle of the app.

## Get some Sepolia ETH $$
You can follow the steps given below:

1. Head over to the site: https://sepoliafaucet.com/.
2. Create an account there.
3. Follow the steps if they ask you any questions.
   1. Select “Learning” as your project
   2. Select Ethereum as your blockchain you want to work with.
4. After the questions, faucet will re-appear.
5. Paste your account address and check captcha.
6. Click on “Send me ETH” button.

After waiting for some time, you will receive 0.5 Sepolia ETH.

## Set up HardHat project
First make a project directory where you will work and we will install all the dependencies and hardhat there.  
Now open your terminal and run the following commands one by one.   
Just copy and paste one by one.
``` bash
mkdir Hello-World
cd Hello-World
npm init --yes
npm install --save-dev hardhat
```
Now write the following command on the terminal.
``` bash
npx hardhat
```
You will see something like this.
