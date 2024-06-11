The MyToken contract defines a simple ERC20-like token named "HARPIC" with the symbol "HPC". It includes public variables for the token name, abbreviation, and total supply, and uses a mapping to keep 
track of each address's token balance. The contract provides two primary functions: mint, which allows the creation of new tokens, increasing the total supply and the balance of the specified address,
and burn, which allows the destruction of tokens, decreasing both the total supply and the balance of the specified address, provided the address has enough tokens. The contract also includes checks to
prevent minting or burning tokens to/from the zero address and emits events for both minting and burning to facilitate tracking of these operations.
