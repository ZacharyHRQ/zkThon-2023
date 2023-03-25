# solution 2

# Contract Address
https://explorer.public.zkevm-test.net/address/0x0AA481875bea357CB288d4caFc2ead0Ec220f33D/contracts

# Transaction Address
https://explorer.public.zkevm-test.net/tx/0x015db66016be3b862b6d4c53ff251afe0f7d8de0ff04c2b3aaa4df66b2e9081b

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.9;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor() ERC20("ZKMoon", "ZKMoons") {
        _mint(msg.sender, 100000000000 * 10 ** decimals());
    }
}
```
