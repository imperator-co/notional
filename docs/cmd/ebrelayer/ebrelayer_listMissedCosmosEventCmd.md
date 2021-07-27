## ebrelayer listMissedCosmosEventCmd

replay missed cosmos events

```
ebrelayer listMissedCosmosEventCmd [tendermintNode] [web3Provider] [bridgeRegistryContractAddress] [ebrelayerEthereumAddress] [days] [flags]
```

### Examples

```
listMissedCosmosEventCmd tcp://localhost:26657 ws://localhost:7545/ 0x30753E4A8aad7F8597332E813735Def5dD395028 0x627306090abaB3A6e1400e9345bC60c78a8BEf57 1
```

### Options

```
  -h, --help   help for listMissedCosmosEventCmd
```

### Options inherited from parent commands

```
      --chain-id string        Chain ID of tendermint node
      --gas string             gas limit to set per-transaction; set to "auto" to calculate required gas automatically (default 200000) (default "gas")
      --gas-adjustment float   gas adjustment (default 1)
      --gas-prices string      Gas prices to determine the transaction fee (e.g. 10uatom)
```

### SEE ALSO

* [ebrelayer](ebrelayer.md)	 - Streams live events from Ethereum and Cosmos and relays event information to the opposite chain

###### Auto generated by spf13/cobra on 2-Jul-2021