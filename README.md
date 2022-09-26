# Deploy contract with raw Javascript: Etherjs

Simple Storage Contract was created at address: 0x462224311f0772F470395B5BE66c16810eF7589a

Compile solidity contract by `solc`

Address of Metamask wallet (Goerli Test Network): 0xd795C5458572F5958DA0Ba915EA380b581C5f316

Private key of wallet was encrypted by encryptKey.js and wasn't storaged in `.env` file.

In deploy.js file, **Contract** was deployed by **ContractFactory**.
We have to pass `abi`, `binary` and `wallet` to **ContractFactory**
`wallet` was created by `private key` of wallet and connect to `provider` (have to pass RPC_URL to provider)
`RPC URL`: a connection to a blockchain node. This URL connect us to make API calls and interact with a blockchain node.
We use Goerli Test Network, RPC_URL: https://eth-goerli.g.alchemy.com/v2/iYZ_7Tdswbn8mp2lYCAf5Rsml5uppHt6

When you deploy contract, run a command: `PRIVATE_KEY_PASSWORD=*your password* node deploy.js`
