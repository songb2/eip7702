forge create src/Delegation.sol:Delegation --rpc-url http://127.0.0.1:8545 --private-key 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80 --broadcast


anvil --mnemonic "test test test test test test test test test test test junk" --fork-url https://reth-ethereum.ithaca.xyz/rpc


forge create src/Delegation.sol:Delegation --rpc-url http://34.58.178.77:8569 --private-key 0xc4ddeed5bd53f154151029b4a171f1dc68d9973dd831c0eecc77661656ae3b07 --gas-price 40000000000 --broadcast --timeout 600 -vvvv