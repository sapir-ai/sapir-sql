# sapir-sql
SapirSQL is a novel NewSQL that ensures high consistency, high availability, and network partition tolerance, which is highlighted with linearizability (strong consistency), serializability, high concurrency supported by lock-free read-only transaction (MVCC on distributed environments based on NTP protocol), RDBMS driver supports , ...

## What's Sapir SQL?

SapirSQL stands on the architecture of the partitioned shared-nothing log replicated state machine.

## highlights

### consistency support: linearizability

* 2PL (two phase lock): ensures the linearizability of read-write transactions.
* MVCC (multi-version concurrency control): ensures the linearizability of read-only transactions.
* Consensus Algorithm: ensures the operational order among replicated partitions.

### transaction atomicity

* 2PC (two phase commit): ensures the atomicity of transacions across replicas

### transaction isolation: serializability

* 2PL (two phase lock): ensures the linearizability of read-write transactions.

