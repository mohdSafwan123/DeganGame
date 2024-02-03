DegenStore Smart Contract
Overview

DegenStore is a Solidity smart contract implementing an ERC-20 token with additional features for minting, transferring, burning, and redeeming tokens for in-game items.
Token Information

    Name: Degen
    Symbol: DGN

Key Functions
1. Minting

    Owner-exclusive function to mint new tokens.
    Function: mint(address to, uint256 amount)

2. Transferring Tokens

    Users can transfer tokens to another address.
    Function: TransferToken(address to, uint256 amount)

3. Burning Tokens

    Users can burn their tokens.
    Function: burn(uint256 amount)

4. Redeeming Tokens

    Users can redeem tokens for in-game items.
    Function: redeemToken(uint256 redeemFor)

5. Withdraw Store Funds

    Owner-exclusive function to withdraw store funds.
    Function: withdrawStoreFunds()

6. Check Balance

    Users can check their token balance.
    Function: checkBalance()

7. In-Game Store Prices

    Function: inGameStore(RedeemType redeemFor)

Note: Prices are in multiples of 1 ether.
How to Use

    Minting Tokens
        Only the owner can mint tokens for a specified address.

    Transferring Tokens
        Users can transfer tokens to other addresses.

    Burning Tokens
        Users can burn their own tokens.

    Redeeming Tokens
        Users can redeem tokens for in-game items.

    Withdraw Store Funds
        Owner can withdraw store funds.

    Check Balance
        Users can check their token balance.

    In-Game Store Prices
        Prices for in-game items are predefined.

License

This smart contract is licensed under MIT. See LICENSE for details.
