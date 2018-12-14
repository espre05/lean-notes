
Distributed streaming platform

Streaming , MQ like system, but high throughput, reliability and scalability.

Use cases:

- Stream processing, website activity track, metrics, monitor, log aggregation, 
- CEP, CQRS, replay messages, error recovery
- Guaranteed distributed commit log for in-memory computing (microservices)

Why kafka fast?

- Zero copy: https://en.wikipedia.org/wiki/Zero-copy
- Allows batching data records into chunks -- allows efficient data compression and IO latency.



http://cloudurable.com/images/Kafka-Decoupling-Data-Streams.svg
