# easy-smart-wallet
A smart wallet based on a Solidity smart contract is a decentralized application that allows users to deposit funds, make withdrawals, and perform transfers between addresses.

The functions and events of this smart contract are similar to the previous example:

Deposit: Allows users to deposit Ether (ETH) into their wallet balance.
Withdraw: Enables users to request withdrawals of a specific amount of ETH from their wallet balance.
Transfer: Allows users to perform transfers of ETH between addresses. The recipient's address and the transfer amount are specified.
Get Balance: Enables users to retrieve the current balance of their wallet.
Get Contract Balance: Allows the contract owner to obtain the total balance of the contract.
The contract also includes the onlyOwner modifier, which restricts access to certain functions to the contract owner.

It is recommended to conduct thorough testing and implement the necessary security checks to ensure the safe and secure usage of this smart contract.
