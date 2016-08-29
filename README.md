# Link

The purpose of the Link blockchain is to permanently store semantic linked data.

Funding preallocation: 56,000,000 Link (equivalent to approximately 5 years worth of mining)

Currency code: LINK

## Ethereum configuration

Network ID: 13919287

Port: 30313

RPC Port: 8645

## Parity instructions

    parity --chain link.json --db-path ~/.link-parity --port 30313 --jsonrpc-port 8645

## Geth instructions

    geth --datadir ~/.link-geth init genesis.json
    cp static-nodes.json ~/.link-geth
    geth --datadir ~/.link-geth --networkid 13919287 --port 30313 --rpcport 8645 --fast
    # In a separate terminal launch the console.
    geth attach ~/.link-geth/geth.ipc
