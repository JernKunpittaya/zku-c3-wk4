# ZKU C3 - Week 4

Part1

1. Full node is basically downloading the whole blockchain so fully sunc. Light node, instead, only download the block header from full node and validate if a certain transaction or account detail if valid by querying from full node and validate against Merkle root which it has.
2. Plumo uses BLS to compress block sequence (tx are aggregated into groups of 4 months), then verify it with SNARK (proving that the current group correctly follow the previous one.)
3. Harmony uses FBFT consensus algo while Celo uses IBFT. Harmony epoch is 4 hours, while Celo is 1 day.

Part3:

1. The config file allows us to customize webpack such as which to use a certain scss, which to use a certain plug in like babel loader.
