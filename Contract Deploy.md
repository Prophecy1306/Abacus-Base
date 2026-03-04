<div align="left">

##  **Architecture Overview📜**

I’m deploying a series of lightweight Solidity contracts on the Base mainnet with one clear goal and keep it minimal, efficient and cost-aware.

</div>

<img width="1907" height="886" alt="Screenshot 2026-02-26 004637" src="https://github.com/user-attachments/assets/9404cf0a-87b0-404d-ba8a-92d8ae6e9939" />

<div align="center">

##  **Deployment Prerequisites⚙️**

</div>


1.) Base Guild Link :- https://guild.xyz/base/builders-founders

2.) Chainlist (Base Mainnet Chain) :- https://chainlist.org/?search=base

3.) Remix :- https://remix.ethereum.org/#lang=en&optimize&runs=200&evmVersion&version=soljson-v0.8.33+commit.64118f21.js

* >You will need to perform this process using a MetaMask wallet connected to the Base mainnet (EVM).

* >To execute this on the Base mainnet, you’ll need to hold at least $0.50 worth of ETH on the Base network to cover deployment and transaction fees.

<div align="center">

##  **Setup Instructions🪜**

</div>

* >Step 1 : Click on `Create new workspace`
* >Step 2 : Click on `Basic`
* >Step 3 : Then Click `Create a New workshop`
* >Step 4 : You have to `Create a new file` in the contract.
* >Step 5 : Then upload `Name` to GitHub.
* If your wallet is not connected, then `turn off` all EVM extension from your browser except `Metamask Extension` for a few seconds or refresh it and then connect the MetaMask wallet.

<div align="center">
  
 ## **Execution Steps📔**

</div>

■ Name : `BASE-1.sol`

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE1 {
    uint public x;

    function setX(uint _x) external {
        x = _x;
    }
}
```

■ Name : `BASE-2.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE2 {
    function value() external pure returns (uint) {
        return 42;
    }
}
```

■ Name : `BASE-3.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE3 {
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
```
■ Name : `BASE-4.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE4 {
    bool public state;

    function flip() external {
        state = !state;
    }
}
```

■ Name : `BASE-5.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE5 {
    uint public c;

    function inc() external {
        c++;
    }
}
```

■ Name : `ASE-6.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE6 {
    event Logged(address user, uint time);

    function log() external {
        emit Logged(msg.sender, block.timestamp);
    }
}
```

■ Name : `BASE-7.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE7 {
    string public data;

    function set(string calldata _d) external {
        data = _d;
    }
}
```
■ Name : `BASE-8.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE8 {
    function add(uint a, uint b) external pure returns (uint) {
        return a + b;
    }
}
```
■ Name : `BASE-9.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE9 {
    function isSenderEOA() external view returns (bool) {
        return msg.sender == tx.origin;
    }
}
```
■ Name : `BASE-10.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE10 {
    event Received(uint amount);

    receive() external payable {
        emit Received(msg.value);
    }
}
```
■ Name : `BASE-11.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE11 {
    uint public deployedAt;

    constructor() {
        deployedAt = block.number;
    }
}
```
■ Name : `BASE-12.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE12 {
    address public owner = msg.sender;

    function isOwner() external view returns (bool) {
        return msg.sender == owner;
    }
}
```
■ Name : `BASE-13.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE13 {
    bytes32 public hash;

    function setHash(bytes32 h) external {
        hash = h;
    }
}
```
■ Name : `BASE-14.sol`
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BASE14 {
    mapping(address => uint) public score;

    function setScore(uint s) external {
        score[msg.sender] = s;
    }
}
```

* At last, you need to go to the guild and claim these `three quests`.

<img width="1536" height="1024" alt="ChatGPT Image Feb 26, 2026, 10_39_12 PM" src="https://github.com/user-attachments/assets/81a62319-0613-48dc-8540-eb84578b7717" />

# Done✔️✔️

<pre>

Stay Connected

👉 Join for more updates and future releases: https://linktr.ee/EarlyCTs

If you run into any issues, You can also reach me directly via DM.

Thanks for checking out this.

</pre>

<div align="center">

#  *❤️‍🔥 Happy vibe coding 👨🏻‍💻*

</div>

