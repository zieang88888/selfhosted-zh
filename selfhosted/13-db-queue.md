# 13 · 数据库与消息队列

> 自托管服务的"发动机舱"：关系型/文档/时序/搜索数据库与消息中间件。

## 关系型 / 通用数据库

- [PostgreSQL](https://www.postgresql.org) — 最先进的开源对象关系数据库｜PostgreSQL License
- [MySQL](https://www.mysql.com) — 最流行的开源关系型数据库｜GPL
- [MariaDB](https://mariadb.org) — MySQL 的社区分叉，真正开源｜GPL
- [SQLite](https://www.sqlite.org) — 嵌入式零配置数据库｜公有领域
- [MongoDB](https://www.mongodb.com) — 流行的文档型数据库｜Server Side Public License
- [CouchDB](https://couchdb.apache.org) — 多主同步的文档数据库｜Apache-2.0
- [SurrealDB](https://surrealdb.com) — 云原生多模型数据库｜BSL / 商业
- [DuckDB](https://duckdb.org) — 进程内分析型 OLAP 数据库｜MIT
- [CockroachDB](https://www.cockroachlabs.com) — 兼容 PostgreSQL 的分布式 SQL 数据库｜BSL / 商业
- [YugabyteDB](https://www.yugabyte.com) — 分布式云原生 SQL 数据库｜Apache-2.0
- [TiDB](https://www.pingcap.com) — 兼容 MySQL 的分布式 HTAP 数据库｜Apache-2.0
- [Dolt](https://www.dolthub.com) — 带 Git 版本控制的 SQL 数据库｜Apache-2.0
- [Citus](https://www.citusdata.com) — PostgreSQL 分布式扩展｜AGPL-3.0
- [FerretDB](https://www.ferretdb.io) — 把 MongoDB 协议跑在 PostgreSQL 上｜Apache-2.0
- [immudb](https://immudb.io) — 高性能不可变（immutable）数据库｜Apache-2.0

## 时序 / 分析 / 搜索

- [ClickHouse](https://clickhouse.com) — 极速开源列式分析数据库｜Apache-2.0
- [TimescaleDB](https://www.timescale.com) — 基于 PostgreSQL 的时序数据库｜Timescale License
- [QuestDB](https://questdb.io) — 高性能时序 SQL 数据库｜Apache-2.0
- [ScyllaDB](https://www.scylladb.com) — 兼容 Cassandra/CQL 的高性能分布式数据库｜AGPL-3.0
- [Cassandra](https://cassandra.apache.org) — 高可用分布式宽列存储数据库｜Apache-2.0
- [OpenSearch](https://opensearch.org) — Elasticsearch 的开源分叉搜索与分析引擎｜Apache-2.0
- [Meilisearch](https://www.meilisearch.com) — 极速、易用的开源搜索引擎｜MIT
- [Typesense](https://typesense.org) — 轻量即时搜索，Algolia 自托管替代｜GPL-3.0
- [Manticore Search](https://manticoresearch.com) — 开源高性能搜索引擎｜GPL-3.0

## 缓存 / 键值 / 图

- [Redis](https://redis.io) — 最流行的内存键值缓存/消息代理｜RSAL/SSPL
- [KeyDB](https://github.com/Snapchat/KeyDB) — 多线程兼容 Redis 的高性能分叉｜BSD
- [etcd](https://etcd.io) — 一致的分布式键值存储｜Apache-2.0
- [Neo4j](https://neo4j.com) — 最流行的图数据库（社区版 GPL）｜GPL-3.0
- [ArangoDB](https://www.arangodb.com) — 原生多模型（文档/图/键值）数据库｜Apache-2.0
- [Dgraph](https://dgraph.io) — 分布式高吞吐图数据库｜Apache-2.0

## 消息队列 / 消息代理

- [RabbitMQ](https://www.rabbitmq.com) — 经典开源消息代理｜MPL-2.0
- [Apache Kafka](https://kafka.apache.org) — 分布式流处理与消息队列｜Apache-2.0
- [Redpanda](https://redpanda.com) — 兼容 Kafka、无 JVM 的流数据平台｜Apache-2.0
- [NATS](https://nats.io) — 轻量高性能云原生消息系统｜Apache-2.0
- [ActiveMQ](https://activemq.apache.org) — 成熟的开源消息与集成模式代理｜Apache-2.0
- [ZeroMQ](https://zeromq.org) — 嵌入式高性能消息库｜MPL-2.0
- [EMQX](https://www.emqx.com) — 大规模可扩展开源 MQTT 消息代理｜Apache-2.0
- [Mosquitto](https://mosquitto.org) — 轻量开源 MQTT 消息代理｜EPL/EDL
- [VerneMQ](https://vernemq.com) — 企业级可扩展 MQTT 消息代理｜Apache-2.0
