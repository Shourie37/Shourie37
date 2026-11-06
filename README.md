# Hi, I'm Shourie 👋

Software engineer at **Amazon Web Services** (Seattle) with 8+ years of experience building distributed systems, REST APIs, data pipelines, and generative AI products.

At AWS I work on Amazon WorkSpaces, where I help customers run AI agents safely on their virtual desktops. Before that I built identity, payment, and data systems for Amazon One and Alexa for Business.

## What I've built at work

These are company projects, so their code is not public. I describe them here at a public level.

- **AI agents on virtual desktops:** launched a service that lets customers' AI agents operate virtual desktops, in 17 AWS regions, and extended it to Windows 11, Windows 10, and Linux.
- **Agent audit trail:** built a feature that records every action an AI agent takes as replayable video, encrypted with the customer's own key.
- **Experiment analysis:** extended an experiment analysis platform so AWS AppConfig customers get statistical results for every experiment run.
- **Data pipeline performance:** made an hourly data lake job 93% faster, with 99.9% less data scanned.
- **Payments:** let blocked customers update their payment card in the store lane, which reduced blocked customers from 11% to 4%.
- **Generative AI:** launched a RAG-based sales assistant used by 4 companies, and evaluated several LLMs for answer correctness and grounding.

## Open-source projects

| Project | What it shows |
|---|---|
| [mcp-agent-loop](https://github.com/Shourie37/mcp-agent-loop) | An agent harness: MCP-style tool server, an agent loop with limits and traces, workflow graphs, and an evaluation suite. |
| [rag-eval-harness](https://github.com/Shourie37/rag-eval-harness) | RAG with BM25 and hybrid retrieval, plus evaluation of retrieval, correctness, grounding, and refusals. |
| [payments-ledger-api](https://github.com/Shourie37/payments-ledger-api) | A double-entry ledger API with idempotency keys, optimistic concurrency, signed cursors, and an outbox for webhooks. |
| [raft-kv](https://github.com/Shourie37/raft-kv) | A Raft key-value store written from scratch, with chaos tests for partitions and leader failure. |
| [thundering-herd-sim](https://github.com/Shourie37/thundering-herd-sim) | A simulator that shows how reconnect storms overload a service, and how jitter, throttling, and autoscaling fix it. |
| [feature-flags-experiments](https://github.com/Shourie37/feature-flags-experiments) | Feature flags and A/B experiments with deterministic rollout, z-tests, t-tests, and sample ratio mismatch checks. |
| [incremental-etl](https://github.com/Shourie37/incremental-etl) | Incremental upserts with partition pruning and watermarks, benchmarked against full-table scans. |
| [distributed-rate-limiter](https://github.com/Shourie37/distributed-rate-limiter) | Five rate-limit algorithms, a shared-store distributed mode, and fail-open vs fail-closed policies. |
| [slo-anomaly-alerts](https://github.com/Shourie37/slo-anomaly-alerts) | Anomaly detection and SLO burn-rate alerts that catch what static thresholds miss, with precision and recall per detector. |
| [consistent-hash-cache](https://github.com/Shourie37/consistent-hash-cache) | A distributed cache with consistent hashing, replication, hinted handoff, and stampede protection. |
| [durable-workflow-engine](https://github.com/Shourie37/durable-workflow-engine) | A durable workflow engine: JSON state machines, retries, sagas, and crash-and-resume from event history. |
| [lsm-kv-store](https://github.com/Shourie37/lsm-kv-store) | An LSM-tree storage engine with a write-ahead log, Bloom filters, and two compaction strategies. |
| [event-sourced-orders](https://github.com/Shourie37/event-sourced-orders) | An event-sourced order system on a partitioned log, with consumer groups and exactly-once projections. |
| [realtime-chat-service](https://github.com/Shourie37/realtime-chat-service) | A real-time chat service with a WebSocket server built from scratch, offline delivery, and presence. |

## Skills

**Languages:** Java · Python · TypeScript · Go · SQL
**Cloud:** AWS (Lambda, DynamoDB, Step Functions, ECS, EMR, Kinesis, KMS, IAM, CloudWatch)
**AI:** AI agents · MCP · RAG · LLM evaluation · Amazon Bedrock
**Data:** Spark · Apache Iceberg · Kafka · PostgreSQL · Redshift

## Education

- M.S. Computer Science, Stony Brook University
- B.Tech. Computer Engineering, International Institute of Information Technology

🌐 [Portfolio](https://shourie37.github.io) · 📫 [LinkedIn](https://linkedin.com/in/shourie7) · shourie3009@gmail.com
