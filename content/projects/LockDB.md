---
date: "2024-11-30"
title: "LockDB"
github: ""
external: ""
tech:
  - Go
  - Goroutines
  - gRPC
  - SQLite
  - 2PL
  - 2PC
  - Sharding
company: "none"
showInProjects: true
---

Distributed key-value data store in Go sharded across server clusters and SQLite database, with two-phase commit (2PC) protocol for cross-shard transactions, ensuring atomicity and consistency across the nodes. Implemented two-phase locking (2PL) and Write-Ahead Logging (WAL) mechanisms to enable transaction rollbacks for persistent storage and crash recovery mechanisms.
