# Consensus

Consensus is the distributed systems problem of getting a set of unreliable processes to agree on a value or sequence of values. Consensus algorithms power state-machine replication for databases, key-value stores, configuration systems, and blockchains. The topic spans crash-fault tolerant algorithms (Paxos, Raft, Multi-Paxos, Zab, Viewstamped Replication) and Byzantine fault tolerant algorithms (PBFT, Tendermint, HotStuff, Casper).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/consensus/refs/heads/main/apis.yml)

## Tags

- Algorithms, BFT, Blockchain, Consensus, Crash Fault Tolerance, Distributed Systems, Replication, State Machine

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Paxos
The classical crash-fault-tolerant consensus algorithm by Leslie Lamport. Powers Google Chubby, Spanner, Megastore.

**Human URL:** [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

### Raft
Consensus algorithm designed for understandability. Implemented in etcd, Consul, CockroachDB, TiKV, MongoDB.

**Human URL:** [https://raft.github.io/](https://raft.github.io/)

### Practical Byzantine Fault Tolerance (PBFT)
By Castro and Liskov (1999). BFT consensus tolerating up to f failures with 3f+1 replicas.

**Human URL:** [PBFT paper](http://pmg.csail.mit.edu/papers/osdi99.pdf)

### Tendermint / CometBFT
BFT consensus engine that powers Cosmos SDK chains. ABCI decouples consensus from application logic.

**Human URL:** [https://docs.cometbft.com/](https://docs.cometbft.com/)

### HotStuff
Leader-based BFT consensus with linear view change. Foundation for Diem/Libra, Aptos, and Sui consensus.

**Human URL:** [HotStuff paper](https://arxiv.org/abs/1803.05069)

## Common Properties

- [Wikipedia: Consensus](https://en.wikipedia.org/wiki/Consensus_(computer_science))
- [Wikipedia: Paxos](https://en.wikipedia.org/wiki/Paxos_(computer_science))
- [Wikipedia: Raft](https://en.wikipedia.org/wiki/Raft_(algorithm))
- [Wikipedia: Byzantine fault](https://en.wikipedia.org/wiki/Byzantine_fault)
- [FLP Impossibility paper](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)
- [Raft resources](https://raft.github.io/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
