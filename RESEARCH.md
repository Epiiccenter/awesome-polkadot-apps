
## Parachain Paradigms

## On Native Parachain
- A blockchain can interact with Polkadot in two main ways: as a native parachain and through a bridge parachain. 
- To deploy as a native parachain a team could build using the Cumulus framework (based on Substrate),
- Another approach is to develop from scratch or use one of the upcoming Parachain Development Kits.
- Native parachains can make use of faster inter-chain messaging and Polkadot’s shared security. 

## On Bridge Parachain
- if a blockchain has a set of legacy design decisions that makes it difficult to move under Polkadot wholesale,
- it can retain its own consensus and finality mechanism and connect via a bridge hosted on a parachain to become a “bridge chain”.
- For bridge chains and the Polkadot network to communicate, the bridge chain must be finalized before messages can be passed securely. 
- It is likely that multiple blockchains would be able to share the same bridge parachain and thus the cost of its slot.

## Constraints on Parachain
-  There are key scalability constraints with Polkadot, specifically quadratic overhead for message queues, that lead to a natural upper bound. 

## Parachain Infrastructure
- Polkadot’s parachain slots will increase from around five to between 50 and 200 slots during the first year or two of operation.
