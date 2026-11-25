# Edward Shen

Senior Go backend / platform engineer. Distributed systems at Chinese SaaS scale — 30k tenants, 6M live QR codes, 200K delayed jobs per second.

**Stack:** Go · Kafka · Redis · MongoDB · TiDB CDC · Flink · Kubernetes

**Open source** — [hourglass](https://github.com/EdwardShen125/hourglass): delayed jobs & cron for Go. SQLite embedded, sharded MySQL/TiDB + etcd cluster, same engine — time-wheel precision, SQL truth, epoch-fenced failover. Clean-room rebuild of a 200K jobs/s production scheduler ([write-up](https://edwardshen125.github.io/posts/engineering-case-study/building-a-production-go-scheduler-for-200k-delayed-jobs-per-second/)). 

Merged upstream: Apache [arrow-go](https://github.com/apache/arrow-go) — [#1640](https://github.com/apache/arrow-go/pull/1640) Parquet row counting from repetition levels, [#1567](https://github.com/apache/arrow-go/pull/1567) / [#1478](https://github.com/apache/arrow-go/pull/1478) KMS-backed key material for modular encryption, [#1439](https://github.com/apache/arrow-go/pull/1439) pyarrow encryption interop tests; [pulsar-client-go #1569](https://github.com/apache/pulsar-client-go/pull/1569) encrypted batch deserialization; [iceberg-go #2688](https://github.com/apache/iceberg-go/pull/2688) zero-padded year partition values. In review: [gost #162](https://github.com/dubbogo/gost/pull/162) (dubbo-go global logger data race), [arrow-go #1671](https://github.com/apache/arrow-go/pull/1671) UTF-8 compute kernels.

**Recent writing** — full archive at [edwardshen125.github.io](https://edwardshen125.github.io/):

- [Cutting Firestore Reads 58% by Moving a Scan off the Request Path](https://edwardshen125.github.io/posts/engineering-case-study/cutting-firestore-reads-by-moving-a-scan-off-the-request-path/) — fewer executions, not a cheaper query
- [Migrating a Billion Elasticsearch Documents Without Stopping Writes](https://edwardshen125.github.io/posts/engineering-case-study/migrating-a-billion-elasticsearch-documents-without-stopping-writes/)
- [One Queue for Every State Change: Fixing Silent Over-Assignment in a Live QR Code System](https://edwardshen125.github.io/posts/engineering-case-study/one-queue-for-every-state-change-fixing-silent-over-assignment-in-a-live-qr-code-system/) — serializing WeCom QR-code membership updates through one Kafka topic, against the vendor's rate limits
- [Running a Million-DAU Casual Game on Go: Rooms as the Concurrency Boundary](https://edwardshen125.github.io/posts/engineering-case-study/running-a-million-dau-casual-game-on-go-rooms-as-the-concurrency-boundary/)
- [Debugging a Sporadic Go OOM in a Recursive JSON Encode Path](https://edwardshen125.github.io/posts/engineering-case-study/debugging-a-sporadic-go-oom-in-a-recursive-json-encode-path/)

Currently open to senior backend / platform roles, remote or relocation.

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,kafka,redis,mongodb,mysql,flink,kubernetes,docker" alt="Stack: Go, Kafka, Redis, MongoDB, MySQL, Flink, Kubernetes, Docker" />
  </a>
</p>
