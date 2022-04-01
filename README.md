# ZK Uni
To start with, run `yarn install`.

Then, you  will need three terminals to run the code
- run  harhat on local: `yarn chain`
- deploy smart contract by: `yarn deploy`
- finally, to run the UI: `yarn start`

## Deploy on Harmony Testnet

Run the following command on the main direcory:
`yarn workspace @scaffold-eth/hardhat deploy --reset --network testnetHarmony`

## Smart contracts

verifier and contract are in in the [hardhat folder](packages/hardhat/contracts/).

## Circuits

cicom files are in this [path](packages/hardhat/circuits)
