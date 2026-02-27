Node.js Internals — Roadmap + Free Resources
Phase 1 — Runtime Fundamentals
1. What Node.js Actually Is

Learn:

V8 engine

Single-threaded model

Event-driven architecture

Non-blocking I/O

Resources:

Node.js Official Docs
https://nodejs.org/en/docs

Node.js Architecture (Official)
https://nodejs.org/en/learn/getting-started/introduction-to-nodejs

2. Event Loop (Critical)

Learn:

Call stack

Callback queue

Microtask queue

Macrotask queue

setTimeout, setImmediate, process.nextTick

Promises in event loop

Resources:

Node.js Event Loop Guide (Official)
https://nodejs.org/en/learn/asynchronous-work/event-loop-timers-and-nexttick

Philip Roberts Event Loop Talk
https://www.youtube.com/watch?v=8aGhZQkoFbQ

Phase 2 — Asynchronous Internals
3. Async Patterns

Learn:

Callbacks

Promises

async/await

Error propagation

Unhandled promise rejections

Resources:

Node Async Guide
https://nodejs.org/en/learn/asynchronous-work/asynchronous-flow-control

MDN Promises
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

4. libuv & Non-blocking I/O

Learn:

What libuv does

Thread pool

I/O offloading

Blocking vs non-blocking operations

Resources:

libuv Docs
https://libuv.org/

Node Under the Hood (YouTube search)
https://www.youtube.com/results?search_query=node+js+under+the+hood

Phase 3 — Memory & Performance
5. Memory Model

Learn:

Stack vs Heap

Garbage collection

Memory leaks

V8 GC basics

Resources:

Node Memory Management
https://nodejs.org/en/learn/diagnostics/memory

V8 Blog
https://v8.dev/blog

6. Streams (Very Important)

Learn:

Readable streams

Writable streams

Duplex streams

Backpressure

Pipe mechanism

Resources:

Node Streams Guide
https://nodejs.org/api/stream.html

Node Streams Explained
https://nodejs.org/en/learn/modules/how-to-use-streams

Phase 4 — Core Modules
7. File System (fs)

Learn:

fs (sync vs async)

File streams

Buffer handling

Resources:

Node fs Docs
https://nodejs.org/api/fs.html

8. Buffer & Binary Data

Learn:

Buffer basics

Encoding (utf-8, base64)

Binary handling (important for ML file uploads)

Resource:

Node Buffer Docs
https://nodejs.org/api/buffer.html

9. Process & OS

Learn:

process object

Environment variables

Signals (SIGTERM, SIGINT)

Graceful shutdown

Resources:

Node Process Docs
https://nodejs.org/api/process.html

Node OS Docs
https://nodejs.org/api/os.html

Phase 5 — Concurrency & Scaling
10. Worker Threads

Learn:

CPU-bound tasks

worker_threads module

When to use workers

Resources:

Worker Threads Docs
https://nodejs.org/api/worker_threads.html

11. Cluster Module

Learn:

Multi-core utilization

Cluster setup

Load balancing basics

Resource:

Cluster Docs
https://nodejs.org/api/cluster.html

Phase 6 — Debugging & Performance
12. Debugging

Learn:

Node Inspector

--inspect flag

Chrome DevTools integration

Resources:

Node Debugging Guide
https://nodejs.org/en/learn/diagnostics/debugging

13. Performance Monitoring

Learn:

process.memoryUsage()

process.cpuUsage()

Profiling

Event loop lag

Resources:

Node Diagnostics Guide
https://nodejs.org/en/learn/diagnostics

Phase 7 — Production-Level Knowledge
14. Environment & Configuration

Learn:

dotenv

NODE_ENV

Production vs development configs

Resource:

dotenv
https://github.com/motdotla/dotenv

15. Process Management

Learn:

PM2

Restart strategies

Monitoring

Resource:

PM2 Docs
https://pm2.keymetrics.io/

Execution Order

Understand event loop deeply

Master async/await + error flow

Learn libuv + non-blocking I/O

Learn streams + buffers

Learn memory + GC basics

Learn worker threads

Learn clustering

Learn debugging + profiling

Learn graceful shutdown

Learn production process management
