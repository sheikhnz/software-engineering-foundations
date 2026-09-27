# Future-Proof Software Engineer Roadmap

> A long-term, systems-first roadmap for becoming a software engineer who understands how computers, operating systems, networks, databases, runtimes, distributed systems, and production infrastructure actually work.

This repository is my personal engineering curriculum.

The goal is **not** to chase frameworks or memorize tools. The goal is to build durable knowledge that will still matter years from now.

---

## Why this repository exists

Software changes quickly.

Frameworks appear and disappear. Libraries become obsolete. AI changes how code is written. Cloud platforms evolve. New abstractions are created every year.

But the foundations change much more slowly:

- CPU and memory
- operating systems
- networking
- algorithms and data structures
- databases
- concurrency
- distributed systems
- security
- system design
- software architecture
- debugging and performance

My goal is to understand these areas deeply enough that learning a new language, framework, database, cloud platform, or AI tool becomes much easier.

This repository tracks that journey.

---

# Long-Term Goal

Become a software engineer who can:

- understand what happens underneath frameworks
- reason from first principles
- debug difficult production problems
- design reliable backend systems
- understand performance bottlenecks
- work comfortably with Linux
- understand memory and CPU behavior
- understand databases beyond SQL syntax
- understand networking beyond HTTP
- reason about concurrency
- design distributed systems
- build secure systems
- use AI as leverage without depending on it
- learn new technologies quickly
- explain technical systems clearly
- make sound engineering tradeoffs

The target is not simply:

> "I know how to build an application."

The target is:

> "I understand why the system works, where it can fail, how to debug it, and how to improve it."

---

# Engineering Principles

Throughout this roadmap, I will follow these principles.

## 1. Fundamentals before abstractions

Do not only learn:

```text
Framework
Library
SDK
API
```

Also understand:

```text
Application
    ↓
Runtime
    ↓
Operating System
    ↓
Computer Architecture
    ↓
Hardware
```

---

## 2. Build while learning

Every major topic should include implementation.

The loop is:

```text
Learn
  ↓
Implement
  ↓
Break
  ↓
Debug
  ↓
Understand
  ↓
Explain
  ↓
Repeat
```

---

## 3. Prefer durable knowledge

Prioritize concepts that are likely to remain useful for decades.

Examples:

- memory
- processes
- threads
- TCP
- HTTP
- SQL
- transactions
- indexes
- synchronization
- distributed consistency
- cryptography fundamentals

Tools will change.

Concepts remain.

---

## 4. Understand failure

A system is not truly understood until I can answer:

- What can fail?
- How will I detect it?
- What happens after it fails?
- Can the operation safely retry?
- Can data become inconsistent?
- Can the system recover?
- What happens under load?

---

## 5. Use AI as leverage

AI should help me:

- explore unfamiliar code
- generate boilerplate
- create tests
- compare approaches
- review code
- debug hypotheses
- explain difficult concepts
- accelerate documentation

But I should still be able to:

- reason independently
- detect incorrect AI output
- understand generated code
- debug without blindly prompting
- make architectural decisions

---

# Roadmap Overview

```text
Computer Fundamentals
        ↓
C + Memory
        ↓
Data Structures & Algorithms
        ↓
Computer Architecture
        ↓
Operating Systems
        ↓
Linux
        ↓
Networking
        ↓
Databases
        ↓
Language & Runtime Internals
        ↓
Concurrency
        ↓
Distributed Systems
        ↓
Production Engineering
        ↓
Security
        ↓
System Design
        ↓
Deep Specialization
```

---

# Timeline

This is a multi-year roadmap.

The timeline is intentionally flexible. Understanding matters more than speed.

| Period | Main Focus |
|---|---|
| Months 0–3 | Computer fundamentals, binary, memory, C |
| Months 3–6 | Data structures, algorithms, architecture, Linux |
| Months 6–12 | Operating systems |
| Months 12–18 | Networking |
| Months 18–24 | Databases |
| Year 2–3 | Runtimes, concurrency, deeper Linux |
| Year 3–4 | Distributed systems, production engineering |
| Year 4–5 | Security, advanced system design |
| Year 5+ | Deep specialization and lifelong study |

---

# Phase 1 — Computer Fundamentals

**Timeline:** Months 0–3

## Topics

### Binary and data representation

- [ ] bits and bytes
- [ ] binary numbers
- [ ] hexadecimal
- [ ] signed vs unsigned integers
- [ ] two's complement
- [ ] integer overflow
- [ ] floating-point numbers
- [ ] ASCII
- [ ] Unicode
- [ ] endianness

### Hardware fundamentals

- [ ] CPU
- [ ] CPU cores
- [ ] registers
- [ ] instruction cycle
- [ ] RAM
- [ ] SSD/HDD
- [ ] cache
- [ ] L1/L2/L3 cache
- [ ] memory hierarchy
- [ ] memory addresses
- [ ] buses
- [ ] interrupts

### Key questions

I should be able to answer:

- [ ] What is a byte?
- [ ] What is a memory address?
- [ ] Why is RAM faster than an SSD?
- [ ] Why does CPU cache exist?
- [ ] What is locality?
- [ ] What is an instruction?
- [ ] How does the CPU execute a program?

---

# Phase 2 — C and Memory

**Timeline:** Months 0–6

C is not necessarily my final production language.

I am learning C because it exposes concepts that higher-level languages hide.

## Topics

- [ ] variables
- [ ] primitive types
- [ ] arrays
- [ ] pointers
- [ ] pointer arithmetic
- [ ] structs
- [ ] stack
- [ ] heap
- [ ] `malloc`
- [ ] `calloc`
- [ ] `realloc`
- [ ] `free`
- [ ] memory leaks
- [ ] segmentation faults
- [ ] undefined behavior
- [ ] compilation
- [ ] object files
- [ ] static linking
- [ ] dynamic linking

## Projects

- [ ] dynamic array
- [ ] linked list
- [ ] string implementation
- [ ] hash map
- [ ] simple memory allocator
- [ ] CLI utilities

## Questions to answer

- [ ] What is a pointer?
- [ ] What does an address contain?
- [ ] What is the difference between stack and heap?
- [ ] What causes a segmentation fault?
- [ ] What happens when `malloc()` is called?
- [ ] What happens when a C program is compiled?

---

# Phase 3 — Data Structures and Algorithms

**Timeline:** Months 3–9

The goal is not only interview preparation.

The goal is understanding how software organizes data and the cost of different operations.

## Complexity

- [ ] Big-O
- [ ] time complexity
- [ ] space complexity
- [ ] amortized analysis
- [ ] tradeoffs

## Data structures

- [ ] arrays
- [ ] dynamic arrays
- [ ] linked lists
- [ ] stacks
- [ ] queues
- [ ] hash tables
- [ ] sets
- [ ] trees
- [ ] binary search trees
- [ ] heaps
- [ ] tries
- [ ] graphs

## Algorithms

- [ ] binary search
- [ ] sorting
- [ ] BFS
- [ ] DFS
- [ ] recursion
- [ ] divide and conquer
- [ ] greedy algorithms
- [ ] dynamic programming
- [ ] graph traversal
- [ ] shortest paths

## Projects

- [ ] implement each core data structure from scratch
- [ ] implement multiple sorting algorithms
- [ ] build a graph library
- [ ] benchmark different data structures

---

# Phase 4 — Computer Architecture

**Timeline:** Months 3–9

## Topics

- [ ] instruction set architecture
- [ ] machine instructions
- [ ] registers
- [ ] ALU
- [ ] CPU pipelines
- [ ] cache hierarchy
- [ ] cache lines
- [ ] temporal locality
- [ ] spatial locality
- [ ] cache misses
- [ ] branch prediction
- [ ] virtual vs physical addresses
- [ ] memory hierarchy

## Goal

Understand this flow:

```text
Program
  ↓
Machine Instructions
  ↓
CPU
  ↕
Registers
  ↕
Cache
  ↕
RAM
  ↕
Storage
```

---

# Phase 5 — Operating Systems

**Timeline:** Months 6–12

This is one of the most important phases.

## Processes

- [ ] program vs process
- [ ] process states
- [ ] process creation
- [ ] `fork`
- [ ] `exec`
- [ ] process IDs
- [ ] context switching
- [ ] scheduling

## Threads

- [ ] process vs thread
- [ ] thread stacks
- [ ] shared memory
- [ ] scheduling
- [ ] synchronization

## Virtual memory

- [ ] virtual address
- [ ] physical address
- [ ] pages
- [ ] frames
- [ ] page offset
- [ ] virtual page number
- [ ] physical frame number
- [ ] page table
- [ ] multi-level page table
- [ ] TLB
- [ ] page fault
- [ ] demand paging
- [ ] swapping
- [ ] memory protection

### Core address translation model

```text
Virtual Address
    =
Virtual Page Number + Offset

VPN
 ↓
Page Table
 ↓
PFN

Physical Address
    =
Physical Frame Number + Same Offset
```

## System calls

- [ ] user mode
- [ ] kernel mode
- [ ] syscall boundary
- [ ] read
- [ ] write
- [ ] open
- [ ] close
- [ ] mmap

## File systems

- [ ] files
- [ ] directories
- [ ] file descriptors
- [ ] inodes
- [ ] permissions
- [ ] buffering
- [ ] filesystem cache

## Synchronization

- [ ] race conditions
- [ ] critical sections
- [ ] mutexes
- [ ] semaphores
- [ ] condition variables
- [ ] deadlocks
- [ ] starvation

## Projects

- [ ] tiny Unix shell
- [ ] process manager experiments
- [ ] pipes between processes
- [ ] multithreaded program
- [ ] basic allocator
- [ ] inspect syscalls using `strace`

---

# Phase 6 — Linux

**Timeline:** Start in Year 1 and continue forever

Linux should become a natural engineering environment.

## Core commands

- [ ] `ls`
- [ ] `cd`
- [ ] `find`
- [ ] `grep`
- [ ] `awk`
- [ ] `sed`
- [ ] `ps`
- [ ] `top`
- [ ] `htop`
- [ ] `free`
- [ ] `vmstat`
- [ ] `lsof`
- [ ] `ss`
- [ ] `curl`
- [ ] `dig`
- [ ] `tcpdump`
- [ ] `strace`
- [ ] `journalctl`

## Topics

- [ ] shell
- [ ] environment variables
- [ ] permissions
- [ ] processes
- [ ] signals
- [ ] pipes
- [ ] redirection
- [ ] `/proc`
- [ ] file descriptors
- [ ] systemd
- [ ] logs
- [ ] resource limits
- [ ] networking
- [ ] package management

---

# Phase 7 — Networking

**Timeline:** Months 12–18

## Layers

```text
Application
    ↓
HTTP / DNS / WebSocket
    ↓
TLS
    ↓
TCP / UDP
    ↓
IP
    ↓
Ethernet / Wi-Fi
```

## Topics

### IP

- [ ] IPv4
- [ ] IPv6 basics
- [ ] subnetting
- [ ] routing
- [ ] private/public addresses
- [ ] NAT
- [ ] gateways

### TCP

- [ ] ports
- [ ] sockets
- [ ] three-way handshake
- [ ] sequence numbers
- [ ] acknowledgements
- [ ] retransmission
- [ ] flow control
- [ ] congestion control
- [ ] connection termination

### UDP

- [ ] datagrams
- [ ] use cases
- [ ] reliability tradeoffs

### DNS

- [ ] recursive resolver
- [ ] authoritative DNS
- [ ] A/AAAA records
- [ ] CNAME
- [ ] TTL
- [ ] DNS caching

### HTTP

- [ ] request/response
- [ ] headers
- [ ] methods
- [ ] status codes
- [ ] cookies
- [ ] keep-alive
- [ ] HTTP/1.1
- [ ] HTTP/2
- [ ] HTTP/3 basics

### TLS

- [ ] certificates
- [ ] public/private keys
- [ ] handshake
- [ ] symmetric encryption
- [ ] certificate authorities

### Infrastructure

- [ ] proxy
- [ ] reverse proxy
- [ ] load balancer
- [ ] CDN
- [ ] firewall

## Projects

- [ ] raw TCP server
- [ ] HTTP server without framework
- [ ] TCP client
- [ ] simple proxy
- [ ] WebSocket server
- [ ] packet inspection with `tcpdump`

## Ultimate question

Be able to explain:

> What happens after I type `https://example.com` into the browser?

from DNS resolution all the way to rendering.

---

# Phase 8 — Databases

**Timeline:** Months 18–24

Focus heavily on PostgreSQL.

## Storage

- [ ] pages
- [ ] rows/tuples
- [ ] disk layout
- [ ] buffer cache
- [ ] WAL

## Indexes

- [ ] B-tree
- [ ] hash index
- [ ] composite indexes
- [ ] covering indexes
- [ ] selectivity
- [ ] index scans
- [ ] sequential scans

## Query processing

- [ ] parser
- [ ] planner
- [ ] executor
- [ ] cost estimation
- [ ] join strategies
- [ ] query optimization

Use:

```sql
EXPLAIN
EXPLAIN ANALYZE
```

## Transactions

- [ ] ACID
- [ ] transactions
- [ ] isolation levels
- [ ] dirty reads
- [ ] non-repeatable reads
- [ ] phantom reads
- [ ] serialization

## Concurrency

- [ ] locks
- [ ] row locks
- [ ] table locks
- [ ] deadlocks
- [ ] MVCC

## PostgreSQL internals

- [ ] vacuum
- [ ] autovacuum
- [ ] WAL
- [ ] replication
- [ ] connection pooling
- [ ] checkpoints

## Scaling

- [ ] read replicas
- [ ] partitioning
- [ ] sharding concepts
- [ ] caching
- [ ] connection limits

## Projects

- [ ] key-value store
- [ ] append-only storage engine
- [ ] simple index
- [ ] B-tree implementation
- [ ] transaction experiments
- [ ] query performance experiments

---

# Phase 9 — Programming Language and Runtime Internals

**Timeline:** Year 2–3

## Topics

- [ ] lexing
- [ ] parsing
- [ ] AST
- [ ] interpreters
- [ ] compilers
- [ ] bytecode
- [ ] virtual machines
- [ ] machine code
- [ ] JIT compilation
- [ ] garbage collection
- [ ] stack frames
- [ ] calling conventions
- [ ] static linking
- [ ] dynamic linking

## JavaScript / Node.js internals

- [ ] V8
- [ ] event loop
- [ ] call stack
- [ ] heap
- [ ] promises
- [ ] microtasks
- [ ] macrotasks
- [ ] libuv
- [ ] worker threads
- [ ] garbage collector
- [ ] JIT

## Project

Build a tiny programming language:

```text
Source Code
    ↓
Lexer
    ↓
Parser
    ↓
AST
    ↓
Interpreter
```

Example input:

```text
1 + 2 * 3
```

---

# Phase 10 — Concurrency

**Timeline:** Year 2–3

## Topics

- [ ] concurrency vs parallelism
- [ ] threads
- [ ] processes
- [ ] event loops
- [ ] asynchronous I/O
- [ ] thread pools
- [ ] worker pools
- [ ] race conditions
- [ ] mutexes
- [ ] semaphores
- [ ] atomics
- [ ] condition variables
- [ ] deadlocks
- [ ] starvation
- [ ] lock-free concepts
- [ ] message passing

## Projects

- [ ] thread-safe queue
- [ ] worker pool
- [ ] concurrent web crawler
- [ ] multithreaded HTTP server
- [ ] thread-safe cache

---

# Phase 11 — Distributed Systems

**Timeline:** Year 3–4

## Fundamental problems

- [ ] partial failure
- [ ] unreliable networks
- [ ] latency
- [ ] message loss
- [ ] duplicate messages
- [ ] ordering
- [ ] clock differences

## Core concepts

- [ ] replication
- [ ] leader/follower
- [ ] partitioning
- [ ] sharding
- [ ] consistency
- [ ] availability
- [ ] network partitions
- [ ] eventual consistency
- [ ] consensus
- [ ] leader election
- [ ] distributed locks
- [ ] logical clocks
- [ ] idempotency
- [ ] retries
- [ ] backoff
- [ ] circuit breakers
- [ ] backpressure

## Messaging

- [ ] queues
- [ ] pub/sub
- [ ] streams
- [ ] delivery semantics
- [ ] at-most-once
- [ ] at-least-once
- [ ] exactly-once concepts
- [ ] dead-letter queues

## Systems to study

- [ ] Redis
- [ ] Kafka
- [ ] PostgreSQL replication
- [ ] distributed databases
- [ ] Kubernetes control plane concepts

## Questions to constantly ask

```text
What happens if this request times out?

Did the remote service fail,
or did the response simply get lost?

Should I retry?

What if the retry creates the same record twice?

How do I make the operation idempotent?
```

## Projects

- [ ] distributed key-value store
- [ ] replicated service
- [ ] job queue with retries
- [ ] idempotent API
- [ ] event-driven system

---

# Phase 12 — Production Engineering

**Timeline:** Year 3–4

## Infrastructure

- [ ] Docker
- [ ] containers
- [ ] images
- [ ] networking
- [ ] volumes
- [ ] reverse proxies
- [ ] Nginx
- [ ] cloud fundamentals
- [ ] Kubernetes basics

## CI/CD

- [ ] automated tests
- [ ] build pipelines
- [ ] deployments
- [ ] rollbacks
- [ ] blue/green deployment
- [ ] canary deployment

## Observability

Understand the three pillars:

```text
Logs
Metrics
Traces
```

Track:

- [ ] latency
- [ ] throughput
- [ ] error rates
- [ ] CPU
- [ ] memory
- [ ] disk I/O
- [ ] network I/O
- [ ] saturation

## Reliability

- [ ] health checks
- [ ] graceful shutdown
- [ ] retries
- [ ] circuit breakers
- [ ] rate limiting
- [ ] autoscaling
- [ ] disaster recovery
- [ ] backups
- [ ] SLI
- [ ] SLO
- [ ] SLA

---

# Phase 13 — Security

**Timeline:** Year 4+

## Application security

- [ ] authentication
- [ ] authorization
- [ ] sessions
- [ ] cookies
- [ ] JWT
- [ ] OAuth
- [ ] password hashing
- [ ] secret management
- [ ] rate limiting

## Web vulnerabilities

- [ ] SQL injection
- [ ] XSS
- [ ] CSRF
- [ ] SSRF
- [ ] command injection
- [ ] path traversal
- [ ] insecure deserialization

## Cryptography fundamentals

- [ ] hashing
- [ ] salts
- [ ] symmetric encryption
- [ ] asymmetric encryption
- [ ] digital signatures
- [ ] certificates
- [ ] TLS

## Security mindset

```text
Never trust user input.
Never trust the client.
Never assume the network is reliable.
Use the minimum privileges required.
```

---

# Phase 14 — System Design

**Timeline:** Year 4–5+

System design should come after understanding the components.

Do not memorize architecture diagrams.

## Design exercises

- [ ] URL shortener
- [ ] chat system
- [ ] notification system
- [ ] payment system
- [ ] search system
- [ ] analytics pipeline
- [ ] file storage system
- [ ] job processing system
- [ ] recommendation platform
- [ ] multi-tenant SaaS
- [ ] event-driven platform

## Questions

For every design:

- [ ] What are the requirements?
- [ ] What is the expected scale?
- [ ] Where does state live?
- [ ] What data is authoritative?
- [ ] What can fail?
- [ ] What needs strong consistency?
- [ ] What can be eventually consistent?
- [ ] How are retries handled?
- [ ] Is the operation idempotent?
- [ ] What are the bottlenecks?
- [ ] How is the system observed?
- [ ] How does it recover?
- [ ] What happens at 10x traffic?
- [ ] What happens at 100x traffic?

---

# Phase 15 — AI-Era Engineering

**Timeline:** Start now, continue forever

## Learn

- [ ] LLM fundamentals
- [ ] tokens
- [ ] embeddings
- [ ] vector search
- [ ] RAG
- [ ] tool calling
- [ ] agents
- [ ] evaluation
- [ ] hallucination
- [ ] context management
- [ ] model latency
- [ ] inference cost
- [ ] structured outputs

## Engineering focus

Do not only learn how to call an AI API.

Understand:

- [ ] reliability
- [ ] evaluation
- [ ] observability
- [ ] fallbacks
- [ ] deterministic boundaries
- [ ] data privacy
- [ ] prompt injection
- [ ] retrieval quality
- [ ] caching
- [ ] cost control

---

# Phase 16 — Mathematics

This runs in parallel with the rest of the roadmap.

## Core topics

- [ ] logic
- [ ] sets
- [ ] functions
- [ ] relations
- [ ] combinatorics
- [ ] discrete mathematics
- [ ] probability
- [ ] statistics
- [ ] graphs
- [ ] basic linear algebra

Advanced mathematics can be added depending on specialization.

---

# Project Ladder

These projects are ordered roughly from lower-level to higher-level.

- [ ] CLI utility
- [ ] dynamic array
- [ ] linked list
- [ ] hash map
- [ ] Unix-like shell
- [ ] simple memory allocator
- [ ] TCP server
- [ ] HTTP server from scratch
- [ ] proxy server
- [ ] WebSocket server
- [ ] simple key-value database
- [ ] B-tree/index
- [ ] job queue
- [ ] thread pool
- [ ] thread-safe cache
- [ ] tiny programming language
- [ ] multithreaded server
- [ ] distributed key-value store
- [ ] event-driven backend
- [ ] production SaaS
- [ ] observable distributed platform

---

# Recommended Books

These are not meant to be read all at once.

## Computer systems

**Computer Systems: A Programmer's Perspective**

Topics:

- machine representation
- assembly
- memory
- linking
- virtual memory
- concurrency
- systems programming

---

## Operating systems

**Operating Systems: Three Easy Pieces**

Main sections:

- virtualization
- concurrency
- persistence

---

## Networking

**Computer Networking: A Top-Down Approach**

---

## Databases and distributed systems

**Designing Data-Intensive Applications**

Read once when starting distributed systems.

Read it again after building real systems.

The second reading will be much more valuable.

---

## Algorithms

**The Algorithm Design Manual**

A good combination of theory and practical reasoning.

---

# Study Strategy

A suggested weekly distribution:

```text
40% deep study
40% implementation/projects
20% review, notes, debugging and experimentation
```

As production experience increases:

```text
60% building real systems
25% fundamentals/deep study
15% new technologies
```

---

# Daily Study Template

Example:

```text
30 min — reading
60 min — implementation
30 min — experiment/debug
15 min — write notes
15 min — explain the concept from memory
```

Even 60–90 focused minutes per day compounds dramatically over several years.

---

# How I Know I Understand Something

Reading is not enough.

For each topic, I should be able to:

### Level 1 — Define it

Explain what it is.

### Level 2 — Explain why it exists

What problem does it solve?

### Level 3 — Explain how it works

Describe the mechanism.

### Level 4 — Implement a simplified version

Build it.

### Level 5 — Debug it

Understand failure cases.

### Level 6 — Explain tradeoffs

When should it or should it not be used?

### Level 7 — Teach it

Explain it simply without hiding behind terminology.

---

# Engineering Notebook

For each concept, create notes using this structure:

```markdown
# Concept

## What is it?

## Why does it exist?

## How does it work?

## Simple example

## Real-world example

## What happens internally?

## Common mistakes

## Performance implications

## Security implications

## Experiments

## Questions I still have
```

---

# Suggested Repository Structure

```text
future-proof-engineer/
│
├── README.md
│
├── progress.md
│
├── roadmap/
│   ├── 01-computer-fundamentals.md
│   ├── 02-c-and-memory.md
│   ├── 03-data-structures.md
│   ├── 04-computer-architecture.md
│   ├── 05-operating-systems.md
│   ├── 06-linux.md
│   ├── 07-networking.md
│   ├── 08-databases.md
│   ├── 09-language-runtimes.md
│   ├── 10-concurrency.md
│   ├── 11-distributed-systems.md
│   ├── 12-production-engineering.md
│   ├── 13-security.md
│   ├── 14-system-design.md
│   ├── 15-ai-engineering.md
│   └── 16-mathematics.md
│
├── notes/
│   ├── memory/
│   ├── operating-systems/
│   ├── networking/
│   ├── databases/
│   ├── concurrency/
│   └── distributed-systems/
│
├── labs/
│   ├── c/
│   ├── linux/
│   ├── networking/
│   ├── databases/
│   └── concurrency/
│
├── projects/
│   ├── shell/
│   ├── allocator/
│   ├── tcp-server/
│   ├── http-server/
│   ├── key-value-store/
│   ├── tiny-language/
│   └── distributed-kv/
│
└── resources/
    ├── books.md
    ├── courses.md
    └── papers.md
```

---

# Progress Tracking

Use this scale:

```text
⬜ Not started
🟨 Learning
🟦 Practicing
🟩 Comfortable
🟪 Deep understanding
```

Example:

| Area | Status |
|---|---|
| Computer Fundamentals | ⬜ |
| C & Memory | ⬜ |
| Data Structures | ⬜ |
| Computer Architecture | ⬜ |
| Operating Systems | ⬜ |
| Linux | ⬜ |
| Networking | ⬜ |
| Databases | ⬜ |
| Runtime Internals | ⬜ |
| Concurrency | ⬜ |
| Distributed Systems | ⬜ |
| Production Engineering | ⬜ |
| Security | ⬜ |
| System Design | ⬜ |
| AI Engineering | ⬜ |

---

# Milestones

## Milestone 1 — Understand the machine

I can explain:

- [ ] CPU
- [ ] RAM
- [ ] cache
- [ ] registers
- [ ] memory addresses
- [ ] stack/heap
- [ ] how programs execute

---

## Milestone 2 — Understand the OS

I can explain:

- [ ] processes
- [ ] threads
- [ ] syscalls
- [ ] virtual memory
- [ ] paging
- [ ] TLB
- [ ] page faults
- [ ] scheduling
- [ ] filesystems

---

## Milestone 3 — Understand the network

I can explain:

```text
Browser
  ↓
DNS
  ↓
TCP
  ↓
TLS
  ↓
HTTP
  ↓
Server
```

---

## Milestone 4 — Understand databases

I can reason about:

- [ ] indexes
- [ ] query plans
- [ ] MVCC
- [ ] locks
- [ ] transactions
- [ ] WAL
- [ ] replication

---

## Milestone 5 — Understand concurrency

I can identify and solve:

- [ ] race conditions
- [ ] deadlocks
- [ ] synchronization problems
- [ ] async I/O problems

---

## Milestone 6 — Understand distributed systems

I can reason about:

- [ ] retries
- [ ] idempotency
- [ ] consistency
- [ ] replication
- [ ] failure
- [ ] queues
- [ ] partitioning

---

## Milestone 7 — Operate production systems

I can:

- [ ] monitor systems
- [ ] investigate incidents
- [ ] trace requests
- [ ] debug performance
- [ ] deploy safely
- [ ] rollback safely
- [ ] design for failure

---

# Things I Will Avoid

## Tutorial dependency

Do not spend years building only tutorial projects.

---

## Framework addiction

Do not confuse knowing a framework with knowing software engineering.

---

## Blind AI coding

Never merge code I cannot explain.

---

## Memorizing system-design answers

Understand the underlying tradeoffs instead.

---

## Premature specialization

Build broad foundations before going extremely deep.

---

## Passive learning

Reading without implementation creates an illusion of understanding.

---

# What "Future-Proof" Means

Future-proof does **not** mean predicting the technologies that will dominate in 10 years.

It means developing the ability to adapt when technology changes.

A future-proof engineer has strong knowledge of:

```text
Computation
Memory
Operating Systems
Networks
Databases
Concurrency
Distributed Systems
Security
Architecture
Problem Solving
```

Then new technology becomes another abstraction to learn instead of an entirely new world.

---

# Long-Term Specialization

After building broad foundations, become T-shaped.

Broad knowledge:

```text
OS
Networking
Databases
Security
Cloud
Distributed Systems
AI
Programming Languages
```

Then choose one or two areas for deep specialization.

Possible paths:

### Backend / Distributed Systems

```text
Backend
+
Databases
+
Distributed Systems
+
Infrastructure
```

### Database Engineering

```text
Storage Engines
+
Query Processing
+
Distributed Databases
```

### Systems Engineering

```text
Operating Systems
+
Networking
+
C/C++
+
Performance
```

### AI Systems Engineering

```text
Backend
+
Distributed Systems
+
Data Infrastructure
+
ML/LLM Systems
```

### Security Engineering

```text
Operating Systems
+
Networking
+
Cryptography
+
Application Security
```

---

# Lifelong Learning Loop

There is no final graduation.

The long-term loop is:

```text
Build
 ↓
Encounter a problem
 ↓
Study the underlying concept
 ↓
Experiment
 ↓
Fix the problem
 ↓
Document what I learned
 ↓
Build something harder
 ↓
Repeat
```

The goal is continuous compounding.

---

# Final Principle

The objective of this repository is not to know everything.

That is impossible.

The objective is to build enough fundamental understanding that when I encounter something I do not know, I can:

1. identify the underlying problem
2. find the right abstraction
3. learn it quickly
4. test my understanding
5. implement a solution
6. debug it when it fails
7. explain the tradeoffs clearly

That is the engineer I want to become.

---

## Status

**Journey:** In progress.

```text
Learn deeply.
Build constantly.
Break things.
Debug carefully.
Understand why.
Repeat for life.
```
