This is based on the guide at https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13

## To Launch the App

Run `npx hardhat node`
Then `npx hardhat run scripts/deploy.js --network localhost`
Paste the contract address in App.js
Run `npm start`

You'll need to add the top address in Hardhat into MetaMask in order to control the contract if there's an owner set