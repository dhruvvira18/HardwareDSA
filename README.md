# HardwareDSA
Deterministic CPU Cache Profiler &amp; Hardware-Aware Data Structure Execution Engine

## Core Problem Statement
Traditional algorithm education and software profiling evaluate data structures purely through asymptotic Big-O notation (O(1) vs. O(N)), completely ignoring physical silicon realities like spatial locality, pointer-chasing overhead, CPU cache line eviction, and RAM fetch latency.

## Engineering Solution
A deterministic, zero-dependency, browser-based Virtual Memory & Cache Controller Simulator paired with a Time-Travel State Machine. It executes 6 core data structure families while simultaneously profiling how their memory layouts (Contiguous Blocks vs. Scattered Heap Nodes) impact CPU Cache Hits, Cache Misses, and Clock Cycle penalties in real time.
