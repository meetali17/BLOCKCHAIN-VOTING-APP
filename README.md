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

9]after ur contract is deployed start with the frontend 

10]craate a new react app and install all the modules 

11]Once done copy the code from app.css and paste it do the same for app.js as well

12] Now create two folders under the src folder 
 .Components
  - connected.js
  - finished.jsx
  - login.jsx
.Constant
  -constant.js
copy the code for them once everything is done

-compile and ensure that ur contract is deployed properly and hardhat server is running in other window 


Metamask Account:-
when the hardhat server is running it gives private key for creating a acc on metamask copy the private key and on the top right corner set a new network (the default is ethereum mainnet )
-Select localhost as its name
-the rpc url :- https://localhost:8545 and the chain code as 31337 and currency as ETH rest be default 
in the metamask 

now there will be a default acc as account no 1 click on it there will be a option to add a new wallet or import click on it and select private key option and then paste the private key which u got through the hardhat server and then the account is created 

now in the react terminal of ur project folder run npm start to run the project 

