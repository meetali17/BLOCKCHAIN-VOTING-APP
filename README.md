# BLOCKCHAIN-VOTING-APP
BDLT LAB MINI PROJECT

1] First create a folder and run the command npm init -y to install the node modules and package.json
2] Run this command to install hardhat 
    npm install --save-dev hardhat
then this is will install it 
3] After that run this command to initialize hardhat 
    npx hardhat
Choose "Create a basic sample project"

4] It will install all the necessary folders 
5]Check for the scripts folder if not created , then create one and inside create a file named deploy.js which will be used to deploy your contract 
6]After this copy the code from my file and open a seperate terminal and run this command to start the hardhat server 
      npx hardhat node 
7]inside your project folder create a .env file where youll store the private key of your metamask account and then the contract address which youll get once you deploy the contract and then the react_app_key which will be used by your frontend to know the contract
8]To deploy the contract open a new terminal , and run this command :-
     npx hardhat run scripts/deploy.js --network localhost
first compile it by running :- npx hardhat compile 
9]
