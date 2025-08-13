# miniredis (C++)

A learning-oriented, minimal Redis‑like server written in C++ with a tiny client and a simple in‑memory store.

> **Goal**: explore event‑driven networking, a basic request/response protocol, and a hash‑table–backed storage engine.

---

## Status

* [x] Single‑threaded TCP server that accepts multiple clients (non‑blocking sockets + event loop)
* [x] Pipelined requests to increase the amount of work per IO
* [x] String KV store implemented by chaining hashtable with progressive rehashing
* [x] Basic Redis commands: `get`, `set`, `del`
* [ ] A simple JSON-like data serialization
* [ ] Sorted set interfaces
* [ ] Cache expiration with TTL
* [ ] Multithreading with a concurrent queue

> Check the repository history/PRs for the most up‑to‑date status of implemented features.
