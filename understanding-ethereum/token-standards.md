# 📐 Token Standards

## ERC20

Ethereum offers the ability for developers to build on top of the Ethereum blockchain with the ERC-20 standard. ERC-20 introduces a standard for "Fungible Tokens", simply they have a property that makes each Token the same as another Token. So for a developer to release a token on the Ethereum blockchain, they would need to follow the ERC-20 standard. These tokens are written in scripts and smart contracts using the programming language; Solidity, to implement onto the Ethereum blockchain.

It is important to note the Ether itself does not suit the ERC-20 standard, that is why you will need to ["Wrap"](https://weth.io) the Ether instead. Once the Ether is wrapped it is now compliant with the ERC-20 standards and, can be freely swapped for other Tokens.

ERC20 was created by Ethereum devs for the Ethereum community in 2015 and was officially recognized by the year 2017. Developers can submit an Ethereum Improvement Proposal (EIP) which would describe new functions along with their specific protocols and standards. A Committee then reviews, approves, amends, and finalizes that EIP—at that point, it becomes an ERC. Although ERC-20 may be the most well-known know it is not the only ERC.

Here are the functions in which Tokens on ERC-20 must follow

* Total Supply
  * Information about the said Token total supply.
* Balance of
  * This provides the user's account balance.
* Transfers
  * The ability to transfer Tokens of a specific number to a defined address.
* Approve
  * The ability to withdraw Tokens of a specific number to a defined account
*   Allowance

    * returns a set number of tokens from a spender to the owner



in simple form the ERC-20 is a standard interface for fungible (interchangeable) tokens, like voting tokens, staking tokens, or virtual currencies

## ERC721 & NFTs

What is a Non-Fungible Token (NFT)? A Non-Fungible Token can be used to identify something or someone in a unique way. NFT's use the ERC-721 standard which provides functionalities like transferring tokens from one account to another, getting the current token balance of an account, getting the owner of a specific token, and also the total supply of the token available on the network. ERC-721 also is unique by approving that an amount of token from an account can be moved by a third-party account. an example is that an artist who sells an NFT can earn royalties for 3rd party sales on their art. This can be implemented using smart contracts.

ERC-721 allows for each token to be unique in its traits and stats which can lead to different values. An example is the NFT; HashMasks, where each HashMask is different from the other leading to rare and common NFTs.

## ERC1155&#x20;

