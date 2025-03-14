# ERC20-TST
Ethereum ERC-20 Test Standard Token (TST)

For testing of ERC-20 token apps. Create free TST by calling `showMeTheMoney(address _to, uint256 _value)`.

Available at:

- Mainnet: [0x3efd578b271d034a69499e4a2d933c631d44b9ad](https://etherscan.io/address/0x3efd578b271d034a69499e4a2d933c631d44b9ad)
- Ropsten testnet: [0x722dd3f80bac40c951b51bdd28dd19d435762180](https://ropsten.etherscan.io/address/0x722dd3f80bac40c951b51bdd28dd19d435762180)
- Kovan testnet: [0x0fff93a556a91a907165BfB6a6C6cAC695FC33F5](https://kovan.etherscan.io/address/0x0fff93a556a91a907165BfB6a6C6cAC695FC33F5)
- Goerli testnet: [0x45843aF56Aa1057eD1730cA5Ba3F709833900E77](https://goerli.etherscan.io/address/0x45843af56aa1057ed1730ca5ba3f709833900e77)
- Sepolia testnet: [0xe28a3A4BFbf285676405cF55354f8b504D844f3c](https://sepolia.etherscan.io/address/0xe28a3a4bfbf285676405cf55354f8b504d844f3c)

### Interface

```json
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"}],"name":"approve","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"_owner","type":"address"}],"name":"balanceOf","outputs":[{"name":"balance","type":"uint256"}],"payable":false,"type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"showMeTheMoney","outputs":[],"payable":false,"type":"function"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transfer","outputs":[{"name":"success","type":"bool"}],"payable":false,"type":"function"},{"constant":true,"inputs":[{"name":"_owner","type":"address"},{"name":"_spender","type":"address"}],"name":"allowance","outputs":[{"name":"remaining","type":"uint256"}],"payable":false,"type":"function"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_from","type":"address"},{"indexed":true,"name":"_to","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Transfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_owner","type":"address"},{"indexed":true,"name":"_spender","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Approval","type":"event"}]
```
