# gas explained

gas is how ethereum measures computational work.

## simple view

- every operation in a contract has a gas cost
- you pay `gas_used * gas_price` in the network's native token
- higher gas price → miners/validators pick your tx faster

## why gas exists

- prevents spam (you can't run infinite loops for free)
- forces devs to think about efficiency
- creates a market for block space (limited resource)
