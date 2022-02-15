# NFT martketplace Project

This project demonstrates a basic Hardhat use case. It comes with a NFTcontract, a test for that contract, a script that deploys that contract.



# Local setup
To run this project locally, follow these steps.

Clone the project locally, change into the directory, and install the dependencie.
Start the local Hardhat node
``` npx hardhat node```

Deploy the contracts to the local network in a separate terminal window
``` npx hardhat run scripts/deploy.js --network localhost```
Start the app
``` npm run dev```

# Configuration
To deploy to Polygon test or main networks, update the configurations located in hardhat.config.js
If using Infura, update .infuraid with your Infura project ID.

