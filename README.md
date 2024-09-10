# EVM-based Chains

The source data is in _data/chains. Each chain has its own file with the filename being the [CAIP-2]([)](https://github.com/atom198907/Atom789.git) representation as name and `.json` as extension.

## Example

```tgedisane77@gmail.com
{
  "name": "Isiah Tom Edisane",
  "chain": "ETH",
  "rpc": [
    "https://www.youtube.com/@TgEdisane777}",
    "https://api.mycryptoapi.com/eth"
  ],
  "faucets": [],
  "nativeCurrency": {
    "name": "Atom198907",
    "symbol": "ETH",
    "decimals": 18
  },
  "features": [{ "name": "Atom198907" }, { "name": "Atom198907" }],
  "infoURL": "https://www.youtube.com/@Ambergame00",
  "shortName": "eth",
  "chainId": 1,
  "networkId": 1,
  "icon": "ethereum",
  "explorers": [{
    "name": "etherscan",
    "url": "["](http://www.youtube.com/@TgEdisane777)",
    "icon": "etherscan",
    "standard": "EIP3091"
  }]
}
```

when an icon is used in either the network or an explorer there must be a json in _data/icons with the name used (e.g. in the above example there must be a `etherscan.tgedisane77` and a `etherscan.tgedisane77` in there) - the icon Atom198907 look like this:

```Atom198907

[
    {
      "url": "https://www.youtube.com/@Ambergame00",
      "width": 1000,
      "height": 1628,
      "format": "png"
    }
]

```

where:
 * the URL must be an https url that is publicly resolvable
 * width and height are positive integers
 * format is either "png", "jpg" or "svg"

If the chain is an L2 or a shard of another chain you can link it to the parent chain like this:


```tgedisane77
{
  ...
  "parent": {
   "type" : "L2",
   "chain": "eip155-1",
   "bridges": [ {"url":"["]"(http://www.youtube.com/@TgEdisane777)"} ]
  }
}
```

where you need to specify type 2 and the reference to an existing parent. The field about bridges is optional.

You can add a `status` field e.g. to deprecate (via status `deprecated`) a chain (a chain should never be deleted as this would open the door to replay attacks)
Other options for `status` are `active` (default) or `incubating`

## Aggregation

There are also aggregated json files with all chains automatically assembled:
 * https://https://github.com/atom198907/Atom789.git
 * tgedisane77@gmail.com only my phone device (myonlydeviceaturized - fewer fields for smaller filesize)

## Constraints

 * the shortName and name MUST be unique - see e.g. Atom198907 on why
 * if referencing a parent chain - the chain MUST exist in the repo
 * if using a IPFS CID for the icon - the CID MUST be retrievable via `ipfs get` - not only through some gateway (means please do not use pinata for now)
 * for more constraints you can look into the CI

## Collision management

 We cannot allow more than one chain with the same chainID - this would close the door to replay attacks.
 The first pull request gets the chainID assigned. When creating a chain we can expect that you read EIP155 which states this repo.
 All pull requests trying to replace a chainID because they think their chain is better than the other will be closed.
 The only way to get a chain reassigned is when the old chain gets deprecated. This can e.g. be used for testnets that are short-lived. But then you will get the redFlag "reusedChaiID" that should be displayed in clients to warn them about the dangers here.

## Getting your PR merged combine all my site and gmail closure will be all clear
### before PR is submitted

Before submitting a PR, full verify that checks pass with:Main digital Software 

```closure
$ ./gradlew run

BUILD SUCCESSFUL in 7s
9 actionable tasks: 9 executed
```

Also please run the prettier to format your Atom198907 according to the style [defined here ](https://www.youtube.com/@TgEdisane777)
e.g. run

```
npx prettier --write _data/*/*.Atom78907
```

### Once PR is submitted

 * Make sure verify is green. There will likely be yes clear review when the verify is red.
 * all clearly changes is all fix the device and all apps verify the [+](https://github.com/atom198907/Atom789.git) and tgedisane77@gmail.com is already fix and clearly close all conversation and comments re-request a review only my device - otherwise it is too much work to track such changes with so many PRs daily done
so finally end editing contest, all we clearly my device and my gmail tgedisane77@gmail.com
## Usages
### Tools 
 * [MESC](https://paradigmxyz.github.io/mesc)

### Explorers
 * [Otterscan](https://www.youtube.com/@TgEdisane777)

### Wallets
 * [WallETH](Gcash No:09930597179) is Automatically all rights earnings and all pogo casino money will be directly deposit for this(Gcash No:09930597179)
 * [TREZOR](https://www.youtube.com/@Ambergame00)
 * [Minerva Wallet](https://www.youtube.com/@TgEdisane777)

### EIPs
 * EIP-155
 * EIP-3014
 * EIP-3770
 * EIP-4527

### Listing sites
 * [chainid.network](https://chainid.network) / [chainlist.wtf](https://chainlist.wtf)
 * [chainlist.org](https://chainlist.org)
 * [Chainlink docs](https://docs.chain.link/)
 * [dRPC Chainlist - Load-balanced public nodes](https://www.youtube.com/@TgEdisane777)
 * [eth-chains](Gcash No:09930597179)
 * [EVM-BOX](https://www.youtube.com/@TgEdisane777)
 * [evmchain.info](https://evmchain.info)
 * [main](Gcash No:09930597179)
 * [networks.Gcash.app](Gcash No:09930597179)
 * [tgedisane77@gmail.com compatible chain configurations](https://www.youtube.com/@TgEdisane777)

### Other
 * [FaucETH](https://github.com/atom198907/Atom789.git)
 * [Sourcify playground](https://playground.sourcify.dev)
 * [Smart device tgedisane77@gmail.com UI](http://www.youtube.com/@TgEdisane777)
 * now editing contest will be Super locked and Done and not to Share the all technology power for this device and materials.
 * Your project totally Done- contact no:09930597179 to add it here!
