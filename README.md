# 祈雨 · Qiyu

I build **inspectable software systems** — from community-care workflows to fault-tolerant task execution, vector search, and distributed consensus.

软件工程学习者。关注**可靠性、可观测性与可验证的工程实现**：让系统不仅能运行，也能解释自身在故障下如何表现。

## Featured projects · 置顶项目

### [颐和健康 · Yihe Health](https://github.com/qiyuhuating/yihe-health)

A community-care prototype covering resident records, device signals, medication tasks, risk incidents, and staff workflows. The Python/SQLite backend separates read and write transactions, enforces role-based access, and includes privacy-contract and browser end-to-end checks.

**Python · SQLite · HTML/CSS/JavaScript** · [Browser demo](https://qiyuhuating.github.io/yihe-health/) · [Source & validation](https://github.com/qiyuhuating/yihe-health)

*The public demo uses browser-local simulated data; it is not a deployed medical backend.*

### [Faultline](https://github.com/qiyuhuating/faultline-lab)

A local task-execution lab built to make failure recovery observable. Crash a worker, inspect lease takeover and fencing-token rejection, and verify durable, idempotent results through repeatable experiments.

**Node.js · TypeScript · SQLite WAL · SSE** · [Recorded fault-trace demo](https://qiyuhuating.github.io/faultline-lab/) · [Design & tests](https://github.com/qiyuhuating/faultline-lab)

*The public page replays recorded traces; new fault experiments run locally.*

### [skipverse](https://github.com/qiyuhuating/skipverse)

A TypeScript vector-search engine with an **HNSW** index, write-ahead logging, snapshots, and vector quantization. Its interactive demo visualizes graph traversal using the same search core as the Node.js engine.

**TypeScript · HNSW · WAL · Zero runtime dependencies** · [Interactive search demo](https://qiyuhuating.github.io/skipverse/) · [Code & API](https://github.com/qiyuhuating/skipverse)

### [Quorum Lab](https://github.com/qiyuhuating/quorum-lab)

A deterministic, five-node **Raft** consensus lab. Inject partitions, delays, dropped messages and node crashes; inspect elections and log repair at the event level, then replay experiments with virtual time.

**TypeScript · React · Web Worker · Raft** · [Interactive consensus lab](https://qiyuhuating.github.io/quorum-lab/) · [Architecture & validation](https://github.com/qiyuhuating/quorum-lab)

## Other explorations · 其他探索

[**contrapunctus**](https://github.com/qiyuhuating/contrapunctus) — a Fugue Max Tree CRDT text engine for exploring concurrent edits, out-of-order delivery and replica convergence. [Try the collaboration lab](https://qiyuhuating.github.io/contrapunctus/).

I aim to keep project boundaries explicit and behavior reproducible. Each featured repository provides local setup instructions, tests, and implementation notes.

---

*我要我们在一起*
