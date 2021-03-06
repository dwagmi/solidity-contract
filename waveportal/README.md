# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Run 
Ensure if in VS Code to open the app folder to avoid linting errors
```shell
npx hardhat run scripts/run.js
```

# Deploy Locally 
In one terminal: 
```shell
npx hardhat node
```
In another terminal (any script can be chosen, just need to specify the --network arg): 
```shell
npx hardhat run scripts/deploy.js --network localhost
```

# React front end
https://replit.com/@dwagmi/waveportal-baseline-student#.replit 

# Deploy to Rinkeby testnet 
- Get API URL from https://www.alchemy.com/
- Add network to hardhat.config.js
- Add API URL & Rinkeby private key to app/.env (`npm install dotenv`)
- Run: 
```shell
npx hardhat run scripts/deploy.js --network rinkeby
```