# MetazoonNFT 1.0

**NFT ERC-721 Basic Example** Contract based on https://docs.openzeppelin.com/contracts/4.x/erc721

## Overview

### Installation

### Usage

Once installed, you can use the contracts in the library by importing them:

```solidity
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

contract MyCollectible is ERC721 {
    constructor() ERC721("MyCollectible", "MCO") {
    }
}
```

_If you're new to smart contract development, head to [Developing Smart Contracts](https://docs.openzeppelin.com/learn/developing-smart-contracts) to learn about creating a new project and compiling your contracts._

To keep your system secure, you should **always** use the installed code as-is, and neither copy-paste it from online sources, nor modify it yourself. The library is designed so that only the contracts and functions you use are deployed, so you don't need to worry about it needlessly increasing gas costs.

## Learn More

* [BAYC](https://etherscan.io/address/0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d#code)
* [YOLO cat](https://etherscan.io/address/0x7169887b559f625a81144eee8ac784d1d8b4920f#code)
* [onion meta](https://etherscan.io/address/0xae71193d1e914eea9a3164b5f52a19c86949ff50#code)

## License

MetazoonNFT is released under the [MIT License](LICENSE).