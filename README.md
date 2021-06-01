A super simple smart contract backed app for setting a string, and getting the value of it. Practice making an Ethereum app from scratch, not using a scaffold or copying from a course.

This is based on the guide at https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13

## To Launch the App

Run `npx hardhat node`
Then `npx hardhat run scripts/deploy.js --network localhost`
Paste the contract address in App.js
Run `npm start`

You'll need to add the top address in Hardhat into MetaMask in order to control the contract if there's an owner set