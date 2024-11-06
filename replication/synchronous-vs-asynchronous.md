# Synchronous vs. Asynchronous Replication

**Synchronous Replication** requires immediate data consistency, while **Asynchronous Replication** allows delayed consistency.

## Synchronous Replication

- **Advantages**: Strong data consistency.
- **Drawbacks**: Higher latency due to waiting for confirmation.

## Asynchronous Replication

- **Advantages**: Better performance with less delay.
- **Drawbacks**: Potential data lag between servers.

## Use Cases

- **Synchronous**: Banking systems where data consistency is critical.
- **Asynchronous**: Applications prioritizing speed over immediate consistency.

---

Choosing between synchronous and asynchronous replication depends on the application’s consistency and performance needs.
