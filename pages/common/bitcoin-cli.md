# bitcoin-cli

> Client to interact with the Bitcoin Core daemon via RPC calls.
> Uses the configuration defined in `bitcoin.conf`.
> More information: <https://en.bitcoin.it/wiki/Running_Bitcoin#Command-line_arguments>.

- Send a transaction to a given address:

`bitcoin-cli sendtoaddress "{{address}}" {{amount}}`

- Generate one or more blocks:

`bitcoin-cli generate {{num_blocks}}`

- Print high-level information about the wallet:

`bitcoin-cli getwalletinfo`

- List all outputs from previous transactions available to fund outgoing transactions:

`bitcoin-cli listunspent`

- Export the wallet information to a text file:

`bitcoin-cli dumpwallet "{{path/to/file}}"`

- Get blockchain information:

`bitcoin-cli getblockchaininfo`

- Get network information:

`bitcoin-cli getnetworkinfo`

- Stop the Bitcoin Core daemon:

`bitcoin-cli stop`
