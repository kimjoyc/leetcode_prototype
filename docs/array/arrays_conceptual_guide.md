# 📘 Arrays for Coding Interviews: A Concept-First Tutorial

Welcome to your structured guide to mastering arrays — not by brute-forcing patterns, but by deeply understanding what makes each concept work. Arrays are foundational. Getting them right means everything else in data structures and algorithms becomes easier to reason about.

---

## 🧠 Why Arrays Matter

Arrays are not just containers — they are predictable, efficient surfaces to simulate state, sequence, and logic.

### Key Properties:

- Fixed index access (`O(1)`) 
- Contiguous memory layout
- Ideal for simulating sequential systems (e.g. time, order, range)

---

## STAGE 1: Iteration & State

### 🔹 Linear Traversal

Start with building confidence in looping through arrays, tracking ongoing state like maximums, counts, or current streaks.

**Core Skills**

- Single-pass `for` loop
- State variables (`max_so_far`, `current_sum`, etc.)

**Problems**

- [Maximum Subarray (Kadane’s)](https://leetcode.com/problems/maximum-subarray/)
- Best Time to Buy and Sell Stock

---

## STAGE 2: Lookup & Frequency

### 🔹 Hashing and Counting

Arrays often work in tandem with dictionaries to enable fast lookups and tracking.

**Core Skills**

- Frequency maps
- Value-to-index storage
- Avoiding nested loops

**Problems**

- Two Sum
- Contains Duplicate

---

## STAGE 3: Index Control

### 🔹 Two Pointers

Useful when iterating with dual control — either on the same array or across two.

**Use Cases**

- Sorted arrays
- Removing duplicates
- Merging arrays

**Problems**

- Remove Duplicates from Sorted Array
- Merge Sorted Arrays

---

### 🔹 Reverse Traversal

Sometimes it’s more intuitive or efficient to process the array from the end.

**Use Cases**

- Next-greater / visibility-based logic
- Building output arrays backwards

**Problems**

- Daily Temperatures
- Next Greater Element

---

## STAGE 4: Range Operations

### 🔹 Prefix Sums

Used when repeated range calculations are involved (e.g., subarray sums).

**Core Skills**

- Precompute cumulative sums
- Use subtraction for range queries

**Problems**

- Product of Array Except Self
- Subarray Sum Equals K

---

### 🔹 Sliding Window

Controls a dynamic range within the array, useful for constraint-based problems over contiguous subarrays.

**Core Skills**

- Grow/shrink window
- Track running values (e.g., sums or counts)
- Maintain validity with two indices

**Problems**

- Minimum Size Subarray Sum
- Longest Substring Without Repeating Characters

**Example**

```
[2, 3, 1, 4, 5]
 ^     ^
 l     r
```

## STAGE 5: Array Transformation

### 🔹 Sorting + Post-processing
Used to simplify constraints or enable greedy logic.

**Core Skills**

- Pre-sort to reduce logic complexity
- Combine with two pointers

**Problems**

- 3Sum  
- Container With Most Water

---

### 🔹 In-place Rearrangement
Some problems require space-optimized manipulation of the input array.

**Core Skills**

- Use values as indices
- Swap, negate, or mark visited positions

**Problems**

- First Missing Positive  
- Find All Duplicates in an Array

---

## STAGE 6: Simulation via Arrays

Arrays can simulate more complex logic:

- Use values to encode presence/state  
- Track timelines or board states  
- Simulate stack/queue behavior  

**Problems**

- Game of Life  
- Interval Overlaps  
- Custom state machines

---

## Common Pitfalls to Check

- Index out of bounds  
- Modifying array during iteration  
- Off-by-one errors  
- Forgetting to reset state between tests

---

## Concept Progression Summary

| Stage | Concept                  | Sample Problems                              |
|-------|--------------------------|----------------------------------------------|
| 1     | Linear Traversal         | Kadane’s, Stock Profit                        |
| 2     | Hashing / Frequency      | Two Sum, Contains Duplicate                   |
| 3     | Two Pointers             | Merge Arrays, Remove Duplicates               |
| 4     | Reverse Traversal        | Daily Temperatures                            |
| 5     | Prefix Sum               | Product Except Self, Subarray Sum Equals K    |
| 6     | Sliding Window           | Longest Substring, Min Subarray Sum           |
| 7     | Sorting + Post-processing| 3Sum, Container With Most Water               |
| 8     | In-place Rearrangement   | First Missing Positive                        |
| 9     | Array as Simulation      | Game of Life, Stack/State tracking            |

---

## Final Thoughts

Mastering arrays isn’t about solving 100 problems.  
It’s about knowing what problems need which tools, and what those tools do.  
Build your intuition from the ground up — and arrays will become one of your strongest assets.
