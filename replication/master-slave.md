# Master-Slave Replication

In **Master-Slave Replication**, the master server handles all write operations and replicates the data to one or more slave servers for read operations.

## Benefits

- **Load Distribution**: Reduces load on the master by offloading reads.
- **Data Redundancy**: Copies of data are maintained across servers.

## Drawbacks

- **Consistency**: Potential delays in data replication.
- **Single Point of Failure**: If the master fails, writes are affected.

---

Master-Slave replication is effective for read-heavy applications but requires careful management to handle consistency issues.
