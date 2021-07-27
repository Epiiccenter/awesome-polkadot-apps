
## Context
- Each Substrate blockchain provides a runtime. The runtime is the state transition function of the blockchain.
- Polkadot expects each runtime exposes an interface for validating a Parachain's state transition 
- Polkadot also provides interfaces for the Parachain to send and receive messages of other Parachains.

## Concept
- Parachains support light-clients, full nodes, and authority nodes. 
- Authority nodes are called Collators in the Polkadot ecosystem. 
- Cumulus provides the consensus implementation for a Parachain and the block production logic.

## Operations
- To convert a Substrate runtime into a Parachain runtime, the following code needs to be added to the runtime:

## Implementations

### Cumulus
- Cumulus provides interfaces and extensions to convert a Substrate FRAME runtime into a Parachain runtime. 
- When compiling a runtime that uses Cumulus, a WASM binary is generated
- It contains the full code of the Parachain runtime plus the validate_block functionality. 
- This binary is required to register a Parachain on the relay chain.
