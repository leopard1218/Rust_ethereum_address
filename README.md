# Integration of Making ethereum sacret_key and address and making transaction

The wallet can generate a secret key, public key and public address. Furthermore it shows the balance for the wallet's address. An example of sending Eth from the wallet to a different address is also shown.

In order to run the project a `.env` file is required containing an endpoint for connecting to an Ethereum network using WebSockets. For example:

```
INFURA_RINKEBY_WS=wss://rinkeby.infura.io/ws/v3/08xxxxxxxxx
```

The `INFURA_RINKEBY` value is an endpoint address from [infura.io](https://infura.io), however it can be any valid address to an Ethereum network WebSocket endpoint.

Infura.io is an easy way to gain access to an Ethereum node endpoint.

And we use anchor framework to build and deploy contract.

solana config set --url localhost
solana config set --url devnet
solana address

anchor build
solana address -k target/deploy/generator-keypair.json
You get address from keypair.json. It's program_Id.
anchor deploy