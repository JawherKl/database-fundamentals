# Database Replication

Replication is crucial for high availability, fault tolerance, and load balancing. This section covers key replication models:

- **Master-Slave Replication**: A model where the master handles writes and replicates data to one or more slaves, which manage reads.
- **Master-Master Replication**: In this setup, both databases can handle read and write operations, enabling higher availability but requiring conflict resolution.
- **Synchronous vs. Asynchronous Replication**: Discusses the trade-offs between synchronous replication, which ensures immediate consistency, and asynchronous replication, which offers higher performance with eventual consistency.

## Contents

1. `master-slave.md` - Introduction to master-slave replication, its use cases, and benefits.
2. `master-master.md` - Overview of master-master replication, with discussion on challenges like conflict resolution.
3. `synchronous-vs-asynchronous.md` - Comparison between synchronous and asynchronous replication methods, with scenarios where each is beneficial.

---

Understanding replication is essential for designing resilient and scalable databases that can handle high-demand applications.
