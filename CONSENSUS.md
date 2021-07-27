
## Context
- Each Substrate blockchain provides a runtime. The runtime is the state transition function of the blockchain.
- Polkadot expects each runtime exposes an interface for validating a Parachain's state transition 
- Polkadot also provides interfaces for the Parachain to send and receive messages of other Parachains.

## Operations
- To convert a Substrate runtime into a Parachain runtime, the following code needs to be added to the runtime:

## Implementations

### Cumulus
- Cumulus provides interfaces and extensions to convert a Substrate FRAME runtime into a Parachain runtime. 
