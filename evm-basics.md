# evm basics

the ethereum virtual machine (evm) is the runtime that executes smart contracts.

## key ideas

- every smart contract is just bytecode that the evm understands
- each node replays and verifies transactions using the same rules
- storage is like a huge key-value store, paid for with gas

## why it matters

once you understand that "code runs on a shared computer" (the evm), it gets easier to reason about gas costs, security and why upgrades are hard.
