# ZK Uni
To start with, run `yarn install`.

Then, you  will need three terminals to run the code
- run  harhat on local: `yarn chain`
- deploy smart contract by: `yarn deploy`
- finally, to run the UI: `yarn start`

## Deploy on Harmony Testnet
Delete the build and node_module in a case the react is still reading from the cache.
Then run `yarn build` and finally run  `yarn surge`.

Run the following command on the main direcory:
`yarn workspace @scaffold-eth/hardhat deploy --reset --network testnetHarmony`

## Smart contracts

verifier and contract are in in the [hardhat folder](packages/hardhat/contracts/).

## Circuits

cicom files are in this [path](packages/hardhat/circuits)
