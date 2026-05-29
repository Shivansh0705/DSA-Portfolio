# DSA-Portfolio
High-performance C++ algorithmic solutions built for quantitative finance and low-latency engineering prep.
# C++ Algorithmic Implementations

A curated set of algorithmic solutions and data structures written in C++, with an emphasis on performance constraints, in-place operations, and low-level memory management. 

## Implementation Notes

Rather than relying on high-level abstractions in the C++ Standard Template Library (e.g., `std::next_permutation`, `std::sort`), these solutions are largely implemented from first principles. 

By manually handling operations like array partitioning, pointer arithmetic, and cyclic graph traversal, this codebase serves as a practical study in targeting theoretical lower bounds for time and auxiliary space.

**Key constraints applied:**
* Preferring O(1) auxiliary space via in-place mutation and manual state tracking.
* Direct memory/pointer management (e.g., fast/slow pointer mechanics).
* Avoiding runtime overhead from unnecessary container allocations.

## Core Topics

* **Pointer Manipulation:** Cycle detection, $N$th-node lookaheads, and in-place structure reversals.
* **Search & Partitioning:** Modified binary search across rotated search spaces and 2D matrices.
* **State & Window Management:** $K$-sum problem variants and contiguous subarray optimizations.
* **Hashing & Frequency Maps:** Direct address tables and constant-time lookups.

---
*Maintained for quantitative systems and low-latency engineering preparation.*
