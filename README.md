# Kotlin Interview Preparation Guide

A comprehensive collection of Kotlin solutions for common coding interview patterns and LeetCode problems.

## 🎯 Key Interview Patterns

### Arrays and Strings
- Two Pointers Pattern
- Sliding Window Pattern
- Binary Search Pattern
- Prefix Sum Pattern

### Trees
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Binary Search Tree operations
- Tree construction

### Hash Tables
- Frequency counting
- Two Sum pattern
- Anagram detection
- Caching

### Graphs
- DFS traversal
- BFS traversal
- Topological Sort
- Union Find

### Stacks & Queues
- Parentheses matching
- Monotonic stack
- Expression evaluation
- BFS implementation

### Heaps
- Top K Elements
- Merge K Sorted Lists
- Two Heaps Pattern
- Sliding Window Median

## 📚 Kotlin Tips for LeetCode

### 1. Array Operations
```kotlin
// Initialize arrays
val arr = IntArray(5) // [0, 0, 0, 0, 0]
val arr = IntArray(5) { it * 2 } // [0, 2, 4, 6, 8]

// List to Array conversion
val list = listOf(1, 2, 3)
val arr = list.toIntArray()
```

### 2. Collections
```kotlin
// HashMap operations
val map = HashMap<Int, Int>()
map[1] = map.getOrDefault(1, 0) + 1

// Priority Queue (Min Heap)
val minHeap = PriorityQueue<Int>()
```

### 3. Common Time Complexities
- Hash Table Operations: O(1) average
- Binary Search: O(log n)
- DFS/BFS: O(V + E)
- Heap Operations: O(log n)

## 📝 Contributing
Feel free to contribute by:
1. Forking the repository
2. Creating a new branch
3. Making your changes
4. Submitting a pull request