# @solana/rpc-core

This package defines a specification of the [Solana JSON-RPC](https://docs.solana.com/api/http). The inputs and outputs of each RPC method are described in terms of Typescript interfaces. You generally will not need to depend on this package directly, but rather use it as part of the RPC creation functions of the Solana JavaScript SDK [`@solana/web3.js@experimental`](https://github.com/solana-labs/solana-web3.js/tree/master/packages/library).

## Contributing

As of this moment, this package does not represent a specification of the full set of Solana JSON-RPC methods. If you find that you have need of a method that has not yet been specified, we would be grateful if you submitted a specification for it.

Read the RPC method specification [contribution guide](https://github.com/solana-labs/solana-web3.js/issues/1278) to get started.