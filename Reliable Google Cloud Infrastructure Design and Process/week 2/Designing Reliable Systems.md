# Designing Reliable Systems

## 1. You're creating a service and you want to protect it from being overloaded by too many client retries in the event of a partial outage. Which design pattern would you implement

- [x] **Circuit breaker**
  > ✔️ Correct
  > This answer is correct, beacuse the circuit breaker will attempt to prevent an operation that is likely to fail and therefore will protect the resource that is in partial outage and hopefully prevent cascading failure.
- Overload feedback repudiation
- Lazy caching
- Truncated exponential backoff

## 2. You need a relational database for a system that requires extremely high availability (99.999%). The system must run uninterrupted even in the event of a regional outage. Which database would you choose?

- Cloud SQL
- BigQuery
- Firestore
- [x] **Spanner**
  > ✔️ Correct
  > This answer is correct, because Cloud Spanner meets all the requirements. It is a global relational database with high availability. Multi-regional instance have a monhtly uptime of >=99.999%.
