# DSA Interview Questions & Answers — Python

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

---

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level — Complexity & Fundamentals

| No. | Questions |
| --- | --------- |
| 1 | [What is a Data Structure? Why is it important?](#1-what-is-a-data-structure-why-is-it-important) |
| 2 | [What is an Algorithm? What are its properties?](#2-what-is-an-algorithm-what-are-its-properties) |
| 3 | [What is Big O notation? Why is it used?](#3-what-is-big-o-notation-why-is-it-used) |
| 4 | [What is the difference between time complexity and space complexity?](#4-what-is-the-difference-between-time-complexity-and-space-complexity) |
| 5 | [What are the common Big O complexities from best to worst?](#5-what-are-the-common-big-o-complexities-from-best-to-worst) |
| 6 | [What is the difference between linear and non-linear data structures?](#6-what-is-the-difference-between-linear-and-non-linear-data-structures) |
| 7 | [What is recursion? What are its advantages and disadvantages?](#7-what-is-recursion-what-are-its-advantages-and-disadvantages) |
| 8 | [What is the difference between iteration and recursion?](#8-what-is-the-difference-between-iteration-and-recursion) |
| 9 | [What is memoization? How is it different from tabulation?](#9-what-is-memoization-how-is-it-different-from-tabulation) |
| 10 | [What are in-place algorithms? Give an example.](#10-what-are-in-place-algorithms-give-an-example) |

#### 🟢 Basic Level — Arrays

| No. | Questions |
| --- | --------- |
| 11 | [What is an array? What are its time complexities?](#11-what-is-an-array-what-are-its-time-complexities) |
| 12 | [Find the maximum and minimum element in an array](#12-find-the-maximum-and-minimum-element-in-an-array) |
| 13 | [Reverse an array in-place](#13-reverse-an-array-in-place) |
| 14 | [Find the missing number in an array of 1 to N](#14-find-the-missing-number-in-an-array-of-1-to-n) |
| 15 | [Two Sum — find two numbers that add up to a target](#15-two-sum--find-two-numbers-that-add-up-to-a-target) |
| 16 | [Move all zeros to the end of an array](#16-move-all-zeros-to-the-end-of-an-array) |
| 17 | [Find duplicates in an array](#17-find-duplicates-in-an-array) |
| 18 | [Rotate an array by K positions](#18-rotate-an-array-by-k-positions) |
| 19 | [Find the second largest element in an array](#19-find-the-second-largest-element-in-an-array) |
| 20 | [Merge two sorted arrays](#20-merge-two-sorted-arrays) |

#### 🟢 Basic Level — Strings

| No. | Questions |
| --- | --------- |
| 21 | [Reverse a string](#21-reverse-a-string) |
| 22 | [Check if a string is a palindrome](#22-check-if-a-string-is-a-palindrome) |
| 23 | [Check if two strings are anagrams](#23-check-if-two-strings-are-anagrams) |
| 24 | [Find the first non-repeating character in a string](#24-find-the-first-non-repeating-character-in-a-string) |
| 25 | [Count the frequency of each character in a string](#25-count-the-frequency-of-each-character-in-a-string) |
| 26 | [Check if a string contains only digits](#26-check-if-a-string-contains-only-digits) |
| 27 | [Remove duplicate characters from a string](#27-remove-duplicate-characters-from-a-string) |
| 28 | [Find all permutations of a string](#28-find-all-permutations-of-a-string) |

#### 🟢 Basic Level — Linked Lists

| No. | Questions |
| --- | --------- |
| 29 | [What is a Linked List? Types and time complexities?](#29-what-is-a-linked-list-types-and-time-complexities) |
| 30 | [Implement a singly linked list in Python](#30-implement-a-singly-linked-list-in-python) |
| 31 | [Reverse a linked list](#31-reverse-a-linked-list) |
| 32 | [Detect a cycle in a linked list (Floyd's algorithm)](#32-detect-a-cycle-in-a-linked-list-floyds-algorithm) |
| 33 | [Find the middle element of a linked list](#33-find-the-middle-element-of-a-linked-list) |
| 34 | [Merge two sorted linked lists](#34-merge-two-sorted-linked-lists) |
| 35 | [Remove the Nth node from the end of a linked list](#35-remove-the-nth-node-from-the-end-of-a-linked-list) |

#### 🟢 Basic Level — Stack & Queue

| No. | Questions |
| --- | --------- |
| 36 | [What is a Stack? Implement using Python list](#36-what-is-a-stack-implement-using-python-list) |
| 37 | [What is a Queue? Implement using collections.deque](#37-what-is-a-queue-implement-using-collectionsdeque) |
| 38 | [Check for balanced parentheses using a stack](#38-check-for-balanced-parentheses-using-a-stack) |
| 39 | [Implement a stack that supports getMin() in O(1)](#39-implement-a-stack-that-supports-getmin-in-o1) |
| 40 | [Implement a queue using two stacks](#40-implement-a-queue-using-two-stacks) |
| 41 | [Next greater element using stack](#41-next-greater-element-using-stack) |
| 42 | [What is a Deque? When is it used?](#42-what-is-a-deque-when-is-it-used) |

#### 🟡 Medium Level — Searching & Sorting

| No. | Questions |
| --- | --------- |
| 43 | [What is Linear Search? When to use it?](#43-what-is-linear-search-when-to-use-it) |
| 44 | [What is Binary Search? Implement it.](#44-what-is-binary-search-implement-it) |
| 45 | [Search in a rotated sorted array](#45-search-in-a-rotated-sorted-array) |
| 46 | [Find first and last position of element in sorted array](#46-find-first-and-last-position-of-element-in-sorted-array) |
| 47 | [What is Bubble Sort? Time and space complexity?](#47-what-is-bubble-sort-time-and-space-complexity) |
| 48 | [What is Selection Sort? Implement it.](#48-what-is-selection-sort-implement-it) |
| 49 | [What is Insertion Sort? When is it efficient?](#49-what-is-insertion-sort-when-is-it-efficient) |
| 50 | [What is Merge Sort? Implement it.](#50-what-is-merge-sort-implement-it) |
| 51 | [What is Quick Sort? Implement it.](#51-what-is-quick-sort-implement-it) |
| 52 | [What is Heap Sort? How does it work?](#52-what-is-heap-sort-how-does-it-work) |
| 53 | [What is Counting Sort? When is it useful?](#53-what-is-counting-sort-when-is-it-useful) |
| 54 | [Sorting algorithm comparison table](#54-sorting-algorithm-comparison-table) |

#### 🟡 Medium Level — Hashing

| No. | Questions |
| --- | --------- |
| 55 | [What is Hashing? What is a Hash Table?](#55-what-is-hashing-what-is-a-hash-table) |
| 56 | [What are collision resolution techniques?](#56-what-are-collision-resolution-techniques) |
| 57 | [Find the most frequent element in an array](#57-find-the-most-frequent-element-in-an-array) |
| 58 | [Find all pairs with a given sum using hashing](#58-find-all-pairs-with-a-given-sum-using-hashing) |
| 59 | [Longest consecutive sequence in an array](#59-longest-consecutive-sequence-in-an-array) |
| 60 | [Subarray with zero sum](#60-subarray-with-zero-sum) |
| 61 | [Group anagrams together](#61-group-anagrams-together) |

#### 🟡 Medium Level — Trees

| No. | Questions |
| --- | --------- |
| 62 | [What is a Binary Tree? Important terminology?](#62-what-is-a-binary-tree-important-terminology) |
| 63 | [Implement a Binary Tree and its traversals (Inorder, Preorder, Postorder)](#63-implement-a-binary-tree-and-its-traversals-inorder-preorder-postorder) |
| 64 | [Level order traversal (BFS) of a binary tree](#64-level-order-traversal-bfs-of-a-binary-tree) |
| 65 | [Find the height of a binary tree](#65-find-the-height-of-a-binary-tree) |
| 66 | [Check if a binary tree is balanced](#66-check-if-a-binary-tree-is-balanced) |
| 67 | [Find the diameter of a binary tree](#67-find-the-diameter-of-a-binary-tree) |
| 68 | [Lowest Common Ancestor (LCA) of two nodes](#68-lowest-common-ancestor-lca-of-two-nodes) |
| 69 | [What is a Binary Search Tree (BST)? Insert and search.](#69-what-is-a-binary-search-tree-bst-insert-and-search) |
| 70 | [Validate if a binary tree is a BST](#70-validate-if-a-binary-tree-is-a-bst) |
| 71 | [Delete a node from a BST](#71-delete-a-node-from-a-bst) |
| 72 | [Inorder successor in a BST](#72-inorder-successor-in-a-bst) |
| 73 | [Convert sorted array to balanced BST](#73-convert-sorted-array-to-balanced-bst) |
| 74 | [Zigzag level order traversal](#74-zigzag-level-order-traversal) |
| 75 | [Find all paths from root to leaf](#75-find-all-paths-from-root-to-leaf) |

#### 🟡 Medium Level — Heap & Priority Queue

| No. | Questions |
| --- | --------- |
| 76 | [What is a Heap? Min-Heap vs Max-Heap?](#76-what-is-a-heap-min-heap-vs-max-heap) |
| 77 | [Find K largest elements using a heap](#77-find-k-largest-elements-using-a-heap) |
| 78 | [Find the Kth smallest element in an array](#78-find-the-kth-smallest-element-in-an-array) |
| 79 | [Merge K sorted arrays using a heap](#79-merge-k-sorted-arrays-using-a-heap) |
| 80 | [Top K frequent elements](#80-top-k-frequent-elements) |

#### 🟡 Medium Level — Sliding Window & Two Pointers

| No. | Questions |
| --- | --------- |
| 81 | [What is the Sliding Window technique?](#81-what-is-the-sliding-window-technique) |
| 82 | [Longest substring without repeating characters](#82-longest-substring-without-repeating-characters) |
| 83 | [Maximum sum subarray of size K](#83-maximum-sum-subarray-of-size-k) |
| 84 | [Minimum window substring](#84-minimum-window-substring) |
| 85 | [What is the Two Pointers technique?](#85-what-is-the-two-pointers-technique) |
| 86 | [Container with most water](#86-container-with-most-water) |
| 87 | [3Sum — find all triplets that sum to zero](#87-3sum--find-all-triplets-that-sum-to-zero) |
| 88 | [Trapping rain water](#88-trapping-rain-water) |

#### 🟡 Medium Level — Graphs

| No. | Questions |
| --- | --------- |
| 89 | [What is a Graph? Types and representations?](#89-what-is-a-graph-types-and-representations) |
| 90 | [Implement BFS (Breadth First Search)](#90-implement-bfs-breadth-first-search) |
| 91 | [Implement DFS (Depth First Search)](#91-implement-dfs-depth-first-search) |
| 92 | [Detect a cycle in an undirected graph](#92-detect-a-cycle-in-an-undirected-graph) |
| 93 | [Detect a cycle in a directed graph](#93-detect-a-cycle-in-a-directed-graph) |
| 94 | [Topological Sort (Kahn's algorithm)](#94-topological-sort-kahns-algorithm) |
| 95 | [Number of islands (connected components)](#95-number-of-islands-connected-components) |
| 96 | [Shortest path in an unweighted graph (BFS)](#96-shortest-path-in-an-unweighted-graph-bfs) |
| 97 | [Dijkstra's shortest path algorithm](#97-dijkstras-shortest-path-algorithm) |
| 98 | [Bellman-Ford algorithm](#98-bellman-ford-algorithm) |
| 99 | [Floyd-Warshall algorithm (All pairs shortest path)](#99-floyd-warshall-algorithm-all-pairs-shortest-path) |
| 100 | [Minimum Spanning Tree — Prim's algorithm](#100-minimum-spanning-tree--prims-algorithm) |
| 101 | [Minimum Spanning Tree — Kruskal's algorithm + Union Find](#101-minimum-spanning-tree--kruskals-algorithm--union-find) |

#### 🔴 Advanced Level — Dynamic Programming

| No. | Questions |
| --- | --------- |
| 102 | [What is Dynamic Programming? When to use it?](#102-what-is-dynamic-programming-when-to-use-it) |
| 103 | [Fibonacci using DP (memoization + tabulation)](#103-fibonacci-using-dp-memoization--tabulation) |
| 104 | [0/1 Knapsack problem](#104-01-knapsack-problem) |
| 105 | [Longest Common Subsequence (LCS)](#105-longest-common-subsequence-lcs) |
| 106 | [Longest Increasing Subsequence (LIS)](#106-longest-increasing-subsequence-lis) |
| 107 | [Coin Change — minimum coins](#107-coin-change--minimum-coins) |
| 108 | [Coin Change — number of ways](#108-coin-change--number-of-ways) |
| 109 | [Maximum subarray sum (Kadane's algorithm)](#109-maximum-subarray-sum-kadanes-algorithm) |
| 110 | [Edit Distance (Levenshtein distance)](#110-edit-distance-levenshtein-distance) |
| 111 | [Climbing stairs problem](#111-climbing-stairs-problem) |
| 112 | [House Robber problem](#112-house-robber-problem) |
| 113 | [Matrix chain multiplication](#113-matrix-chain-multiplication) |
| 114 | [Subset sum problem](#114-subset-sum-problem) |
| 115 | [Partition equal subset sum](#115-partition-equal-subset-sum) |

#### 🔴 Advanced Level — Backtracking

| No. | Questions |
| --- | --------- |
| 116 | [What is Backtracking? How does it differ from recursion?](#116-what-is-backtracking-how-does-it-differ-from-recursion) |
| 117 | [Generate all subsets of a set (Power Set)](#117-generate-all-subsets-of-a-set-power-set) |
| 118 | [Generate all permutations of an array](#118-generate-all-permutations-of-an-array) |
| 119 | [N-Queens problem](#119-n-queens-problem) |
| 120 | [Sudoku solver](#120-sudoku-solver) |
| 121 | [Word search in a 2D grid](#121-word-search-in-a-2d-grid) |
| 122 | [Combination sum — find all combinations that sum to target](#122-combination-sum--find-all-combinations-that-sum-to-target) |

#### 🔴 Advanced Level — Advanced Data Structures

| No. | Questions |
| --- | --------- |
| 123 | [What is a Trie? Implement insert and search.](#123-what-is-a-trie-implement-insert-and-search) |
| 124 | [Implement LRU Cache](#124-implement-lru-cache) |
| 125 | [What is a Segment Tree? Build and query.](#125-what-is-a-segment-tree-build-and-query) |
| 126 | [What is a Fenwick Tree (Binary Indexed Tree)?](#126-what-is-a-fenwick-tree-binary-indexed-tree) |
| 127 | [What is Disjoint Set (Union-Find)?](#127-what-is-disjoint-set-union-find) |
| 128 | [What is a Skip List?](#128-what-is-a-skip-list) |

#### 🔴 Advanced Level — Greedy Algorithms

| No. | Questions |
| --- | --------- |
| 129 | [What is a Greedy Algorithm? When does it work?](#129-what-is-a-greedy-algorithm-when-does-it-work) |
| 130 | [Activity selection problem](#130-activity-selection-problem) |
| 131 | [Fractional Knapsack problem](#131-fractional-knapsack-problem) |
| 132 | [Huffman encoding](#132-huffman-encoding) |
| 133 | [Jump Game — can you reach the end?](#133-jump-game--can-you-reach-the-end) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 134 | [What is the difference between Stack and Queue?](#134-what-is-the-difference-between-stack-and-queue) |
| 135 | [When would you use a HashMap over an array?](#135-when-would-you-use-a-hashmap-over-an-array) |
| 136 | [What is the difference between DFS and BFS? When to use which?](#136-what-is-the-difference-between-dfs-and-bfs-when-to-use-which) |
| 137 | [What is the difference between Greedy and Dynamic Programming?](#137-what-is-the-difference-between-greedy-and-dynamic-programming) |
| 138 | [How do you find if a number is a power of 2?](#138-how-do-you-find-if-a-number-is-a-power-of-2) |
| 139 | [Find the single non-duplicate in an array (XOR trick)](#139-find-the-single-non-duplicate-in-an-array-xor-trick) |
| 140 | [Find median of two sorted arrays](#140-find-median-of-two-sorted-arrays) |
| 141 | [Merge overlapping intervals](#141-merge-overlapping-intervals) |
| 142 | [Product of array except self (no division)](#142-product-of-array-except-self-no-division) |
| 143 | [Spiral order traversal of a matrix](#143-spiral-order-traversal-of-a-matrix) |
| 144 | [Rotate a matrix 90 degrees clockwise](#144-rotate-a-matrix-90-degrees-clockwise) |
| 145 | [Search in a 2D sorted matrix](#145-search-in-a-2d-sorted-matrix) |
| 146 | [Word ladder (shortest transformation)](#146-word-ladder-shortest-transformation) |
| 147 | [Clone a graph](#147-clone-a-graph) |
| 148 | [Serialize and deserialize a binary tree](#148-serialize-and-deserialize-a-binary-tree) |
| 149 | [Design a stack using a linked list](#149-design-a-stack-using-a-linked-list) |
| 150 | [What are the top patterns to master for DSA interviews?](#150-what-are-the-top-patterns-to-master-for-dsa-interviews) |

</details>

---

<br>

## 🟢 Basic Level — Complexity & Fundamentals

<br>

### 1. What is a Data Structure? Why is it important?

**Answer:**

A data structure is a way of **organizing, storing, and managing data** in a computer so it can be accessed and modified efficiently.

**Why it matters:**
- Choosing the right data structure directly impacts the performance of your program
- Different structures excel at different operations — arrays for fast access, linked lists for fast insertion, hash maps for fast lookup
- All software systems — databases, operating systems, compilers — are built on data structures

| Category | Examples |
| -------- | -------- |
| Linear | Array, Linked List, Stack, Queue |
| Non-linear | Tree, Graph |
| Hash-based | Hash Map, Hash Set |
| Heap-based | Min-Heap, Max-Heap |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. What is an Algorithm? What are its properties?

**Answer:**

An algorithm is a **step-by-step finite set of instructions** to solve a specific problem.

**5 essential properties:**
- **Input** — zero or more inputs
- **Output** — at least one output
- **Definiteness** — each step is clear and unambiguous
- **Finiteness** — terminates after a finite number of steps
- **Effectiveness** — each step is basic and executable

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. What is Big O notation? Why is it used?

**Answer:**

Big O notation describes the **worst-case upper bound** on the time or space an algorithm uses as input size `n` grows. It lets you compare algorithms independently of hardware.

```python
# O(1) — constant — doesn't depend on input size
def get_first(arr):
    return arr[0]

# O(n) — linear — one pass through the array
def find_max(arr):
    max_val = arr[0]
    for num in arr:          # n iterations
        if num > max_val:
            max_val = num
    return max_val

# O(n²) — quadratic — nested loop
def has_duplicate(arr):
    for i in range(len(arr)):
        for j in range(i + 1, len(arr)):   # n*(n-1)/2 comparisons
            if arr[i] == arr[j]:
                return True
    return False

# O(log n) — logarithmic — halves input each step (binary search)
def binary_search(arr, target):
    lo, hi = 0, len(arr) - 1
    while lo <= hi:
        mid = (lo + hi) // 2
        if arr[mid] == target: return mid
        elif arr[mid] < target: lo = mid + 1
        else: hi = mid - 1
    return -1
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What is the difference between time complexity and space complexity?

| Feature | Time Complexity | Space Complexity |
| ------- | --------------- | ---------------- |
| Measures | How long the algorithm runs | How much memory it uses |
| Includes | Basic operations, comparisons, iterations | Variables, call stack, data structures |
| Goal | Minimize CPU time | Minimize RAM usage |

```python
# Example: Reverse array
# In-place: O(n) time, O(1) space — modifies original
def reverse_inplace(arr):
    left, right = 0, len(arr) - 1
    while left < right:
        arr[left], arr[right] = arr[right], arr[left]
        left += 1
        right -= 1

# With extra array: O(n) time, O(n) space — uses extra memory
def reverse_new(arr):
    return arr[::-1]  # creates a new list
```

> **Trade-off:** You often trade space for time (memoization) or time for space (in-place algorithms). Always clarify which constraint matters more in your interview.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What are the common Big O complexities from best to worst?

| Complexity | Name | Example |
| ---------- | ---- | ------- |
| O(1) | Constant | Array index access, hash map lookup |
| O(log n) | Logarithmic | Binary search, balanced BST ops |
| O(n) | Linear | Linear search, single loop |
| O(n log n) | Linearithmic | Merge sort, heap sort |
| O(n²) | Quadratic | Bubble sort, nested loops |
| O(n³) | Cubic | Floyd-Warshall, matrix multiplication |
| O(2ⁿ) | Exponential | Recursive Fibonacci, power set |
| O(n!) | Factorial | Generating all permutations |

```
Best → Worst:
O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ) < O(n!)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What is the difference between linear and non-linear data structures?

| Feature | Linear | Non-Linear |
| ------- | ------ | ---------- |
| Arrangement | Sequential — one after another | Hierarchical or networked |
| Traversal | Single run covers all elements | May need multiple runs |
| Memory | Usually contiguous or linked | Scattered |
| Examples | Array, Stack, Queue, Linked List | Tree, Graph |
| Relationships | One-to-one | One-to-many or many-to-many |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What is recursion? What are its advantages and disadvantages?

**Answer:**

Recursion is when a **function calls itself** to solve a smaller version of the same problem, until it reaches a base case.

```python
# Every recursive function needs:
# 1. Base case — stops the recursion
# 2. Recursive case — calls itself with smaller input

def factorial(n):
    if n == 0 or n == 1:   # base case
        return 1
    return n * factorial(n - 1)  # recursive case

# factorial(4) → 4 * factorial(3)
#              → 4 * 3 * factorial(2)
#              → 4 * 3 * 2 * factorial(1)
#              → 4 * 3 * 2 * 1 = 24

def fibonacci(n):
    if n <= 1: return n     # base case
    return fibonacci(n-1) + fibonacci(n-2)  # O(2^n) — inefficient without memoization
```

| Advantages | Disadvantages |
| ---------- | ------------- |
| Cleaner, readable code | Function call overhead |
| Natural for tree/graph problems | Stack overflow for deep recursion |
| Divide and conquer made easy | Often slower than iteration |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What is the difference between iteration and recursion?

```python
# Iterative Fibonacci — O(n) time, O(1) space
def fib_iterative(n):
    if n <= 1: return n
    a, b = 0, 1
    for _ in range(2, n + 1):
        a, b = b, a + b
    return b

# Recursive Fibonacci — O(2^n) time, O(n) space (call stack)
def fib_recursive(n):
    if n <= 1: return n
    return fib_recursive(n-1) + fib_recursive(n-2)

# Recursive with memoization — O(n) time, O(n) space
from functools import lru_cache

@lru_cache(maxsize=None)
def fib_memo(n):
    if n <= 1: return n
    return fib_memo(n-1) + fib_memo(n-2)
```

> **Rule:** Prefer iteration for simple loops. Use recursion when the problem has a natural recursive structure (trees, graphs, divide and conquer).

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. What is memoization? How is it different from tabulation?

Both are DP optimization techniques:

| Feature | Memoization (Top-Down) | Tabulation (Bottom-Up) |
| ------- | ---------------------- | ---------------------- |
| Approach | Recursive + cache | Iterative + table |
| Order | Solves only needed subproblems | Solves all subproblems |
| Stack overflow risk | Yes (deep recursion) | No |
| Code simplicity | Simpler to write | More explicit |

```python
# Memoization — top-down, recursive, only computes what's needed
def knapsack_memo(weights, values, capacity, n, memo={}):
    if n == 0 or capacity == 0: return 0
    if (n, capacity) in memo: return memo[(n, capacity)]

    if weights[n-1] > capacity:
        result = knapsack_memo(weights, values, capacity, n-1, memo)
    else:
        include = values[n-1] + knapsack_memo(weights, values, capacity - weights[n-1], n-1, memo)
        exclude = knapsack_memo(weights, values, capacity, n-1, memo)
        result = max(include, exclude)

    memo[(n, capacity)] = result
    return result

# Tabulation — bottom-up, iterative, fills entire table
def knapsack_tab(weights, values, capacity):
    n = len(weights)
    dp = [[0] * (capacity + 1) for _ in range(n + 1)]
    for i in range(1, n + 1):
        for w in range(capacity + 1):
            if weights[i-1] <= w:
                dp[i][w] = max(dp[i-1][w], values[i-1] + dp[i-1][w - weights[i-1]])
            else:
                dp[i][w] = dp[i-1][w]
    return dp[n][capacity]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What are in-place algorithms? Give an example.

**Answer:**

An in-place algorithm transforms data **using only O(1) extra space** — it modifies the input directly without allocating a new data structure proportional to input size.

```python
# In-place partition (used in Quick Sort)
def partition(arr, low, high):
    pivot = arr[high]
    i = low - 1
    for j in range(low, high):
        if arr[j] <= pivot:
            i += 1
            arr[i], arr[j] = arr[j], arr[i]   # swap in-place
    arr[i+1], arr[high] = arr[high], arr[i+1]
    return i + 1

# In-place vs not:
nums = [3, 1, 2]
# In-place: O(1) extra space
nums.sort()                     # sorts the list itself

# Not in-place: O(n) extra space
sorted_nums = sorted(nums)      # creates a new list
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Arrays

<br>

### 11. What is an array? What are its time complexities?

**Answer:**

An array stores elements of the **same type in contiguous memory locations**, accessed via an index in O(1).

| Operation | Time Complexity | Notes |
| --------- | --------------- | ----- |
| Access by index | O(1) | Direct memory address computation |
| Search (unsorted) | O(n) | Must check every element |
| Search (sorted) | O(log n) | Binary search |
| Insert at end | O(1) amortized | Python list dynamic resizing |
| Insert at position | O(n) | Must shift elements right |
| Delete at position | O(n) | Must shift elements left |

```python
# Python list is a dynamic array
arr = [10, 20, 30, 40, 50]

print(arr[2])       # O(1) — access
arr.append(60)      # O(1) amortized — insert at end
arr.insert(2, 25)   # O(n) — insert at position
arr.pop()           # O(1) — remove last
arr.pop(0)          # O(n) — remove first (shifts all elements)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. Find the maximum and minimum element in an array

```python
# Approach 1: Python built-in — O(n)
def find_max_min(arr):
    return max(arr), min(arr)

# Approach 2: Single pass — O(n) time, O(1) space
def find_max_min_manual(arr):
    max_val = min_val = arr[0]
    for num in arr[1:]:
        if num > max_val: max_val = num
        if num < min_val: min_val = num
    return max_val, min_val

# Test
arr = [3, 1, 7, 2, 9, 4]
print(find_max_min(arr))        # (9, 1)
print(find_max_min_manual(arr)) # (9, 1)
```

**Time:** O(n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. Reverse an array in-place

```python
# Two pointer approach — O(n) time, O(1) space
def reverse_array(arr):
    left, right = 0, len(arr) - 1
    while left < right:
        arr[left], arr[right] = arr[right], arr[left]
        left += 1
        right -= 1
    return arr

# Python one-liner (creates new list — not in-place)
def reverse_pythonic(arr):
    return arr[::-1]

# Test
print(reverse_array([1, 2, 3, 4, 5]))  # [5, 4, 3, 2, 1]
```

**Time:** O(n) | **Space:** O(1) for in-place

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. Find the missing number in an array of 1 to N

```python
# Approach 1: Sum formula — O(n) time, O(1) space
def find_missing(arr):
    n = len(arr) + 1          # array should have n elements
    expected_sum = n * (n + 1) // 2
    return expected_sum - sum(arr)

# Approach 2: XOR — O(n) time, O(1) space (handles overflow better)
def find_missing_xor(arr):
    n = len(arr) + 1
    xor_all = 0
    for i in range(1, n + 1): xor_all ^= i     # XOR of 1 to n
    for num in arr: xor_all ^= num               # XOR with array elements
    return xor_all  # missing number remains

# Test
arr = [1, 2, 4, 5, 6]   # missing 3
print(find_missing(arr))      # 3
print(find_missing_xor(arr))  # 3
```

**Time:** O(n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. Two Sum — find two numbers that add up to a target

```python
# Approach 1: Hash Map — O(n) time, O(n) space
def two_sum(nums, target):
    seen = {}  # value → index
    for i, num in enumerate(nums):
        complement = target - num
        if complement in seen:
            return [seen[complement], i]
        seen[num] = i
    return []

# Approach 2: Two Pointers (only if sorted) — O(n) time, O(1) space
def two_sum_sorted(nums, target):
    left, right = 0, len(nums) - 1
    while left < right:
        current_sum = nums[left] + nums[right]
        if current_sum == target: return [left, right]
        elif current_sum < target: left += 1
        else: right -= 1
    return []

# Test
print(two_sum([2, 7, 11, 15], 9))   # [0, 1]
print(two_sum([3, 2, 4], 6))        # [1, 2]
```

**Time:** O(n) | **Space:** O(n) — this is one of the most asked questions in all interviews

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 16. Move all zeros to the end of an array

```python
# Two pointer — maintain order of non-zero elements — O(n) time, O(1) space
def move_zeros(nums):
    insert_pos = 0
    for num in nums:
        if num != 0:
            nums[insert_pos] = num
            insert_pos += 1
    # fill remaining positions with zeros
    while insert_pos < len(nums):
        nums[insert_pos] = 0
        insert_pos += 1
    return nums

# Test
print(move_zeros([0, 1, 0, 3, 12]))  # [1, 3, 12, 0, 0]
print(move_zeros([0, 0, 1]))          # [1, 0, 0]
```

**Time:** O(n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. Find duplicates in an array

```python
# Approach 1: Hash Set — O(n) time, O(n) space
def find_duplicates_set(arr):
    seen = set()
    duplicates = []
    for num in arr:
        if num in seen:
            duplicates.append(num)
        else:
            seen.add(num)
    return duplicates

# Approach 2: For arrays with values in range [1, n] — O(n) time, O(1) space
def find_duplicates_inplace(nums):
    duplicates = []
    for num in nums:
        idx = abs(num) - 1
        if nums[idx] < 0:
            duplicates.append(abs(num))
        else:
            nums[idx] = -nums[idx]  # mark as visited
    return duplicates

# Test
print(find_duplicates_set([4, 3, 2, 7, 8, 2, 3, 1]))   # [2, 3]
print(find_duplicates_inplace([4, 3, 2, 7, 8, 2, 3, 1]))# [2, 3]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. Rotate an array by K positions

```python
# Reverse algorithm — O(n) time, O(1) space
def rotate(nums, k):
    n = len(nums)
    k = k % n  # handle k > n

    def reverse(left, right):
        while left < right:
            nums[left], nums[right] = nums[right], nums[left]
            left += 1; right -= 1

    reverse(0, n - 1)    # step 1: reverse entire array
    reverse(0, k - 1)    # step 2: reverse first k elements
    reverse(k, n - 1)    # step 3: reverse remaining elements
    return nums

# Test
print(rotate([1, 2, 3, 4, 5, 6, 7], 3))  # [5, 6, 7, 1, 2, 3, 4]
```

**Time:** O(n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. Find the second largest element in an array

```python
# Single pass — O(n) time, O(1) space
def second_largest(arr):
    first = second = float('-inf')
    for num in arr:
        if num > first:
            second = first
            first = num
        elif num > second and num != first:
            second = num
    return second if second != float('-inf') else None

# Test
print(second_largest([12, 35, 1, 10, 34, 1]))  # 34
print(second_largest([10, 10, 10]))              # None (all equal)
```

**Time:** O(n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. Merge two sorted arrays

```python
# Merge into new array — O(m+n) time, O(m+n) space
def merge_sorted(arr1, arr2):
    result = []
    i = j = 0
    while i < len(arr1) and j < len(arr2):
        if arr1[i] <= arr2[j]:
            result.append(arr1[i]); i += 1
        else:
            result.append(arr2[j]); j += 1
    result.extend(arr1[i:])
    result.extend(arr2[j:])
    return result

# Test
print(merge_sorted([1, 3, 5, 7], [2, 4, 6, 8]))  # [1, 2, 3, 4, 5, 6, 7, 8]
```

**Time:** O(m+n) | **Space:** O(m+n) — this logic is the core of Merge Sort

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Strings

<br>

### 21. Reverse a string

```python
# Python — multiple approaches
s = "hello"

# Approach 1: Slicing — O(n)
reversed_s = s[::-1]           # "olleh"

# Approach 2: Built-in — O(n)
reversed_s = ''.join(reversed(s))

# Approach 3: Manual — O(n) time, O(1) space (in-place using list)
def reverse_string(s):
    chars = list(s)
    left, right = 0, len(chars) - 1
    while left < right:
        chars[left], chars[right] = chars[right], chars[left]
        left += 1; right -= 1
    return ''.join(chars)

print(reverse_string("hello"))  # "olleh"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. Check if a string is a palindrome

```python
# Approach 1: Two pointers — O(n) time, O(1) space
def is_palindrome(s):
    left, right = 0, len(s) - 1
    while left < right:
        if s[left] != s[right]: return False
        left += 1; right -= 1
    return True

# Approach 2: Pythonic — O(n)
def is_palindrome_v2(s):
    return s == s[::-1]

# Real interview version: ignore non-alphanumeric and case
def is_palindrome_clean(s):
    s = ''.join(c.lower() for c in s if c.isalnum())
    return s == s[::-1]

# Test
print(is_palindrome("racecar"))         # True
print(is_palindrome_clean("A man a plan a canal Panama"))  # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 23. Check if two strings are anagrams

```python
# Approach 1: Sort both — O(n log n) time
def is_anagram_sort(s, t):
    return sorted(s) == sorted(t)

# Approach 2: Counter — O(n) time, O(1) space (26 letters max)
from collections import Counter

def is_anagram(s, t):
    if len(s) != len(t): return False
    return Counter(s) == Counter(t)

# Approach 3: Manual frequency count — O(n)
def is_anagram_manual(s, t):
    if len(s) != len(t): return False
    count = {}
    for c in s: count[c] = count.get(c, 0) + 1
    for c in t:
        if c not in count: return False
        count[c] -= 1
        if count[c] < 0: return False
    return True

# Test
print(is_anagram("anagram", "nagaram"))  # True
print(is_anagram("rat", "car"))          # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. Find the first non-repeating character in a string

```python
from collections import OrderedDict, Counter

# Approach 1: Counter — O(n) two passes
def first_unique_char(s):
    count = Counter(s)
    for i, c in enumerate(s):
        if count[c] == 1:
            return i  # return index
    return -1

# Approach 2: OrderedDict — O(n) single conceptual pass
def first_unique_char_v2(s):
    freq = OrderedDict()
    for c in s:
        freq[c] = freq.get(c, 0) + 1
    for c, cnt in freq.items():
        if cnt == 1: return c
    return None

# Test
print(first_unique_char("leetcode"))    # 0 (l)
print(first_unique_char("aabb"))        # -1 (none)
print(first_unique_char_v2("loveleet")) # 'v'
```

**Time:** O(n) | **Space:** O(1) — at most 26 distinct characters

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. Count the frequency of each character in a string

```python
from collections import Counter

def char_frequency(s):
    return dict(Counter(s))

# Manual approach
def char_frequency_manual(s):
    freq = {}
    for c in s:
        freq[c] = freq.get(c, 0) + 1
    return freq

# Most common N characters
def top_n_chars(s, n):
    return Counter(s).most_common(n)

# Test
print(char_frequency("banana"))           # {'b':1,'a':3,'n':2}
print(top_n_chars("programming", 3))      # [('g',2),('r',2),('p',1)]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 26. Check if a string contains only digits

```python
# Multiple approaches
s1 = "12345"
s2 = "123a5"

print(s1.isdigit())          # True  — built-in
print(s2.isdigit())          # False

print(s1.isnumeric())        # True  — also handles unicode numbers
print(all(c.isdigit() for c in s1))  # True — explicit check

# Handles negative numbers and floats:
def is_valid_number(s):
    try:
        float(s)
        return True
    except ValueError:
        return False

print(is_valid_number("-3.14"))  # True
print(is_valid_number("abc"))    # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. Remove duplicate characters from a string

```python
# Approach 1: Preserve order using dict — O(n)
def remove_duplicates(s):
    seen = dict.fromkeys(s)  # preserves insertion order in Python 3.7+
    return ''.join(seen)

# Approach 2: Using set (order NOT preserved)
def remove_duplicates_set(s):
    return ''.join(set(s))

# Approach 3: Manual — O(n) time, O(n) space
def remove_duplicates_manual(s):
    seen = set()
    result = []
    for c in s:
        if c not in seen:
            seen.add(c)
            result.append(c)
    return ''.join(result)

# Test
print(remove_duplicates("programming"))   # "progamin"
print(remove_duplicates_manual("banana")) # "ban"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. Find all permutations of a string

```python
# Backtracking — O(n! * n) time
def permutations(s):
    result = []
    def backtrack(current, remaining):
        if not remaining:
            result.append(current)
            return
        for i in range(len(remaining)):
            backtrack(current + remaining[i], remaining[:i] + remaining[i+1:])
    backtrack("", s)
    return result

# Using Python's itertools
from itertools import permutations as iperms
def all_permutations(s):
    return [''.join(p) for p in iperms(s)]

# Test
print(permutations("abc"))  # ['abc','acb','bac','bca','cab','cba']
print(len(permutations("abcd")))  # 24 = 4!
```

**Time:** O(n! × n) | **Space:** O(n) call stack depth

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Linked Lists

<br>

### 29. What is a Linked List? Types and time complexities?

**Answer:**

A linked list is a linear data structure where each element (**node**) contains a value and a **pointer to the next node**. Unlike arrays, nodes are NOT stored in contiguous memory.

| Type | Description |
| ---- | ----------- |
| Singly Linked List | Each node points to the next node only |
| Doubly Linked List | Each node points to both next and previous nodes |
| Circular Linked List | Last node points back to the first node |

| Operation | Array | Linked List |
| --------- | ----- | ----------- |
| Access by index | O(1) | O(n) |
| Search | O(n) | O(n) |
| Insert at head | O(n) | O(1) |
| Insert at tail | O(1) amortized | O(n) or O(1) with tail ptr |
| Delete at head | O(n) | O(1) |
| Memory | Contiguous, fixed type | Non-contiguous, pointer overhead |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. Implement a singly linked list in Python

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class LinkedList:
    def __init__(self):
        self.head = None

    def append(self, data):         # O(n)
        new_node = Node(data)
        if not self.head:
            self.head = new_node; return
        curr = self.head
        while curr.next: curr = curr.next
        curr.next = new_node

    def prepend(self, data):        # O(1)
        new_node = Node(data)
        new_node.next = self.head
        self.head = new_node

    def delete(self, data):         # O(n)
        if not self.head: return
        if self.head.data == data:
            self.head = self.head.next; return
        curr = self.head
        while curr.next:
            if curr.next.data == data:
                curr.next = curr.next.next; return
            curr = curr.next

    def display(self):
        elements = []
        curr = self.head
        while curr:
            elements.append(curr.data)
            curr = curr.next
        print(" → ".join(map(str, elements)))

# Test
ll = LinkedList()
ll.append(1); ll.append(2); ll.append(3)
ll.prepend(0)
ll.display()   # 0 → 1 → 2 → 3
ll.delete(2)
ll.display()   # 0 → 1 → 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 31. Reverse a linked list

```python
class Node:
    def __init__(self, val): self.val = val; self.next = None

# Iterative — O(n) time, O(1) space
def reverse_list(head):
    prev = None
    curr = head
    while curr:
        next_node = curr.next   # save next
        curr.next = prev        # reverse pointer
        prev = curr             # move prev forward
        curr = next_node        # move curr forward
    return prev  # new head

# Recursive — O(n) time, O(n) space (call stack)
def reverse_list_recursive(head):
    if not head or not head.next:
        return head
    new_head = reverse_list_recursive(head.next)
    head.next.next = head   # reverse the link
    head.next = None        # clear old link
    return new_head
```

**Time:** O(n) | **Space:** O(1) iterative — one of the most asked linked list questions

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. Detect a cycle in a linked list (Floyd's algorithm)

```python
# Floyd's Cycle Detection (Tortoise and Hare) — O(n) time, O(1) space
def has_cycle(head):
    slow = fast = head
    while fast and fast.next:
        slow = slow.next          # moves 1 step
        fast = fast.next.next     # moves 2 steps
        if slow == fast:
            return True           # cycle detected — they meet
    return False

# Find the START of the cycle
def detect_cycle_start(head):
    slow = fast = head
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next
        if slow == fast:
            # move one pointer to head, keep other at meeting point
            slow = head
            while slow != fast:
                slow = slow.next
                fast = fast.next
            return slow  # start of cycle
    return None
```

**Time:** O(n) | **Space:** O(1) — Floyd's algorithm is a must-know

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 33. Find the middle element of a linked list

```python
# Slow and fast pointer (Tortoise and Hare) — O(n) time, O(1) space
def find_middle(head):
    slow = fast = head
    while fast and fast.next:
        slow = slow.next        # 1 step
        fast = fast.next.next   # 2 steps
    return slow  # when fast reaches end, slow is at middle

# For even length: returns second middle (e.g., [1,2,3,4] → node 3)
# To get first middle: check fast.next instead of fast

# Test: 1 → 2 → 3 → 4 → 5
# slow: 1→2→3 | fast: 1→3→5 → middle = 3 ✓
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. Merge two sorted linked lists

```python
def merge_sorted_lists(l1, l2):
    # Dummy node trick avoids edge cases
    dummy = Node(0)
    curr = dummy

    while l1 and l2:
        if l1.val <= l2.val:
            curr.next = l1; l1 = l1.next
        else:
            curr.next = l2; l2 = l2.next
        curr = curr.next

    curr.next = l1 or l2   # attach remaining list
    return dummy.next

# Recursive approach — cleaner but O(n) stack space
def merge_recursive(l1, l2):
    if not l1: return l2
    if not l2: return l1
    if l1.val <= l2.val:
        l1.next = merge_recursive(l1.next, l2)
        return l1
    else:
        l2.next = merge_recursive(l1, l2.next)
        return l2
```

**Time:** O(m+n) | **Space:** O(1) iterative

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. Remove the Nth node from the end of a linked list

```python
def remove_nth_from_end(head, n):
    dummy = Node(0)
    dummy.next = head
    fast = slow = dummy

    # Move fast n+1 steps ahead
    for _ in range(n + 1):
        fast = fast.next

    # Move both until fast reaches end
    while fast:
        fast = fast.next
        slow = slow.next

    # slow is now just before the node to delete
    slow.next = slow.next.next
    return dummy.next

# Example: 1→2→3→4→5, n=2 → removes 4 → 1→2→3→5
```

**Time:** O(n) | **Space:** O(1) — one pass with two pointers

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟢 Basic Level — Stack & Queue

<br>

### 36. What is a Stack? Implement using Python list

**Answer:**

A Stack is a **LIFO (Last In First Out)** linear data structure. The last element added is the first to be removed.

```python
# Python list as stack — O(1) for push/pop
class Stack:
    def __init__(self):
        self._stack = []

    def push(self, item):           # O(1)
        self._stack.append(item)

    def pop(self):                  # O(1)
        if self.is_empty():
            raise IndexError("Stack is empty")
        return self._stack.pop()

    def peek(self):                 # O(1) — view top without removing
        if self.is_empty(): raise IndexError("Stack is empty")
        return self._stack[-1]

    def is_empty(self):             # O(1)
        return len(self._stack) == 0

    def size(self):
        return len(self._stack)

# Test
s = Stack()
s.push(10); s.push(20); s.push(30)
print(s.peek())    # 30
print(s.pop())     # 30
print(s.size())    # 2

# Real-world uses: undo/redo, function call stack, expression parsing, DFS
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. What is a Queue? Implement using collections.deque

**Answer:**

A Queue is a **FIFO (First In First Out)** data structure. The first element added is the first to be removed.

```python
from collections import deque

class Queue:
    def __init__(self):
        self._queue = deque()

    def enqueue(self, item):        # O(1) — add to rear
        self._queue.append(item)

    def dequeue(self):              # O(1) — remove from front
        if self.is_empty():
            raise IndexError("Queue is empty")
        return self._queue.popleft()

    def front(self):                # O(1) — peek front
        return self._queue[0]

    def is_empty(self):
        return len(self._queue) == 0

    def size(self):
        return len(self._queue)

# Test
q = Queue()
q.enqueue("A"); q.enqueue("B"); q.enqueue("C")
print(q.dequeue())  # "A" — FIFO
print(q.front())    # "B"

# Real-world uses: task scheduling, BFS, printer queue, CPU scheduling
```

> **Why deque not list?** `list.pop(0)` is O(n) because it shifts all elements. `deque.popleft()` is O(1).

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 38. Check for balanced parentheses using a stack

```python
def is_balanced(s):
    stack = []
    pairs = {')': '(', '}': '{', ']': '['}

    for char in s:
        if char in '({[':
            stack.append(char)          # push opening bracket
        elif char in ')}]':
            if not stack or stack[-1] != pairs[char]:
                return False            # mismatch or empty stack
            stack.pop()                 # matching pair found

    return len(stack) == 0             # stack must be empty at end

# Test
print(is_balanced("({[]})"))    # True
print(is_balanced("([)]"))      # False
print(is_balanced("{[}"))       # False
print(is_balanced(""))          # True
```

**Time:** O(n) | **Space:** O(n) — asked in almost every MNC interview

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. Implement a stack that supports getMin() in O(1)

```python
class MinStack:
    def __init__(self):
        self.stack = []       # main stack
        self.min_stack = []   # tracks minimums

    def push(self, val):
        self.stack.append(val)
        # push to min_stack if it's the new minimum (or stack is empty)
        if not self.min_stack or val <= self.min_stack[-1]:
            self.min_stack.append(val)

    def pop(self):
        val = self.stack.pop()
        if val == self.min_stack[-1]:
            self.min_stack.pop()    # also remove from min tracking
        return val

    def top(self):
        return self.stack[-1]

    def get_min(self):              # O(1) — key insight
        return self.min_stack[-1]

# Test
ms = MinStack()
ms.push(5); ms.push(3); ms.push(7); ms.push(2); ms.push(4)
print(ms.get_min())   # 2
ms.pop()              # remove 4
ms.pop()              # remove 2
print(ms.get_min())   # 3 — correctly updated
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 40. Implement a queue using two stacks

```python
class QueueUsingStacks:
    def __init__(self):
        self.inbox = []    # for enqueue
        self.outbox = []   # for dequeue

    def enqueue(self, val):    # O(1)
        self.inbox.append(val)

    def dequeue(self):         # Amortized O(1)
        if not self.outbox:
            # transfer all from inbox to outbox (reverses order → FIFO)
            while self.inbox:
                self.outbox.append(self.inbox.pop())
        if not self.outbox:
            raise IndexError("Queue is empty")
        return self.outbox.pop()

    def peek(self):
        if not self.outbox:
            while self.inbox:
                self.outbox.append(self.inbox.pop())
        return self.outbox[-1]

# Test
q = QueueUsingStacks()
q.enqueue(1); q.enqueue(2); q.enqueue(3)
print(q.dequeue())  # 1 — FIFO preserved
print(q.dequeue())  # 2
q.enqueue(4)
print(q.dequeue())  # 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 41. Next greater element using stack

```python
# For each element, find the next element that is greater — O(n) time, O(n) space
def next_greater_element(arr):
    n = len(arr)
    result = [-1] * n   # default: -1 (no greater element)
    stack = []          # stores indices

    for i in range(n):
        # pop all elements smaller than arr[i]
        while stack and arr[stack[-1]] < arr[i]:
            idx = stack.pop()
            result[idx] = arr[i]  # arr[i] is the next greater for arr[idx]
        stack.append(i)

    return result

# Test
print(next_greater_element([4, 5, 2, 10, 8]))  # [5, 10, 10, -1, -1]
print(next_greater_element([1, 3, 2, 4]))       # [3, 4, 4, -1]
```

**Time:** O(n) — each element pushed and popped at most once | **Space:** O(n)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What is a Deque? When is it used?

**Answer:**

A Deque (Double-Ended Queue) allows **insertion and deletion from both ends in O(1)**.

```python
from collections import deque

dq = deque([1, 2, 3])
dq.appendleft(0)    # O(1) — add to front: [0,1,2,3]
dq.append(4)        # O(1) — add to back:  [0,1,2,3,4]
dq.popleft()        # O(1) — remove front: returns 0
dq.pop()            # O(1) — remove back:  returns 4
dq.rotate(2)        # rotate right by 2

# Sliding window maximum using deque
def max_sliding_window(nums, k):
    dq = deque()   # stores indices, front = max of window
    result = []
    for i, num in enumerate(nums):
        while dq and nums[dq[-1]] < num:
            dq.pop()                         # remove smaller elements
        dq.append(i)
        if dq[0] < i - k + 1:
            dq.popleft()                     # remove out-of-window index
        if i >= k - 1:
            result.append(nums[dq[0]])       # front is always max
    return result

print(max_sliding_window([1,3,-1,-3,5,3,6,7], 3))  # [3,3,5,5,6,7]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Searching & Sorting

<br>

### 43. What is Linear Search? When to use it?

```python
# O(n) time, O(1) space — works on any list, sorted or not
def linear_search(arr, target):
    for i, val in enumerate(arr):
        if val == target:
            return i    # return index
    return -1           # not found

# Test
print(linear_search([3, 7, 1, 9, 4], 9))  # 3
print(linear_search([3, 7, 1, 9, 4], 5))  # -1

# Use linear search when:
# - Array is unsorted
# - Array is very small (n < 20)
# - You only need to search once (not worth sorting first)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What is Binary Search? Implement it.

```python
# Iterative Binary Search — O(log n) time, O(1) space
def binary_search(arr, target):
    lo, hi = 0, len(arr) - 1
    while lo <= hi:
        mid = lo + (hi - lo) // 2   # avoids integer overflow
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            lo = mid + 1
        else:
            hi = mid - 1
    return -1

# Recursive Binary Search — O(log n) time, O(log n) space (stack)
def binary_search_recursive(arr, target, lo=0, hi=None):
    if hi is None: hi = len(arr) - 1
    if lo > hi: return -1
    mid = (lo + hi) // 2
    if arr[mid] == target: return mid
    elif arr[mid] < target: return binary_search_recursive(arr, target, mid+1, hi)
    else: return binary_search_recursive(arr, target, lo, mid-1)

# Test
arr = [1, 3, 5, 7, 9, 11, 13]
print(binary_search(arr, 7))   # 3
print(binary_search(arr, 6))   # -1
```

**Prerequisite:** Array must be **sorted**. | **Time:** O(log n) | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 45. Search in a rotated sorted array

```python
# Modified binary search — O(log n) time, O(1) space
def search_rotated(nums, target):
    lo, hi = 0, len(nums) - 1
    while lo <= hi:
        mid = (lo + hi) // 2
        if nums[mid] == target: return mid

        # Determine which half is sorted
        if nums[lo] <= nums[mid]:           # left half is sorted
            if nums[lo] <= target < nums[mid]:
                hi = mid - 1               # target in left half
            else:
                lo = mid + 1
        else:                               # right half is sorted
            if nums[mid] < target <= nums[hi]:
                lo = mid + 1               # target in right half
            else:
                hi = mid - 1
    return -1

# Test
print(search_rotated([4,5,6,7,0,1,2], 0))   # 4
print(search_rotated([4,5,6,7,0,1,2], 3))   # -1
print(search_rotated([1], 0))               # -1
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. Find first and last position of element in sorted array

```python
# Two binary searches — O(log n) time, O(1) space
def search_range(nums, target):
    def find_bound(is_first):
        lo, hi, bound = 0, len(nums) - 1, -1
        while lo <= hi:
            mid = (lo + hi) // 2
            if nums[mid] == target:
                bound = mid
                if is_first: hi = mid - 1   # keep searching left
                else:        lo = mid + 1   # keep searching right
            elif nums[mid] < target: lo = mid + 1
            else:                    hi = mid - 1
        return bound

    return [find_bound(True), find_bound(False)]

# Test
print(search_range([5,7,7,8,8,10], 8))  # [3, 4]
print(search_range([5,7,7,8,8,10], 6))  # [-1, -1]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is Bubble Sort? Time and space complexity?

```python
# Optimized Bubble Sort — stops early if no swaps in a pass
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        swapped = False
        for j in range(0, n - i - 1):   # last i elements are sorted
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
                swapped = True
        if not swapped:
            break    # already sorted — exit early
    return arr

# Test
print(bubble_sort([64, 34, 25, 12, 22, 11, 90]))  # [11,12,22,25,34,64,90]
```

| Case | Time | Space |
| ---- | ---- | ----- |
| Best (sorted) | O(n) | O(1) |
| Average | O(n²) | O(1) |
| Worst | O(n²) | O(1) |

**Stable:** Yes | **In-place:** Yes

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. What is Selection Sort? Implement it.

```python
# Selection Sort — find minimum, place at front — O(n²) always
def selection_sort(arr):
    n = len(arr)
    for i in range(n):
        min_idx = i
        for j in range(i + 1, n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]  # swap minimum to position i
    return arr

# Test
print(selection_sort([64, 25, 12, 22, 11]))  # [11,12,22,25,64]
```

| Case | Time | Space |
| ---- | ---- | ----- |
| All cases | O(n²) | O(1) |

**Stable:** No | **In-place:** Yes | **Makes minimum swaps:** Yes (good when write is expensive)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. What is Insertion Sort? When is it efficient?

```python
# Insertion Sort — like sorting playing cards — O(n²) worst, O(n) best
def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and arr[j] > key:
            arr[j + 1] = arr[j]   # shift right
            j -= 1
        arr[j + 1] = key          # insert key at correct position
    return arr

# Test
print(insertion_sort([12, 11, 13, 5, 6]))  # [5,6,11,12,13]
```

| Case | Time | Space |
| ---- | ---- | ----- |
| Best (sorted) | O(n) | O(1) |
| Average | O(n²) | O(1) |
| Worst | O(n²) | O(1) |

**Best when:** Nearly sorted arrays, small input (n < 20), online sorting (elements arrive one by one) | **Stable:** Yes

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. What is Merge Sort? Implement it.

```python
# Divide and Conquer — O(n log n) always
def merge_sort(arr):
    if len(arr) <= 1:
        return arr

    mid = len(arr) // 2
    left = merge_sort(arr[:mid])    # sort left half
    right = merge_sort(arr[mid:])   # sort right half
    return merge(left, right)

def merge(left, right):
    result = []
    i = j = 0
    while i < len(left) and j < len(right):
        if left[i] <= right[j]:
            result.append(left[i]); i += 1
        else:
            result.append(right[j]); j += 1
    result.extend(left[i:])
    result.extend(right[j:])
    return result

# Test
print(merge_sort([38, 27, 43, 3, 9, 82, 10]))  # [3,9,10,27,38,43,82]
```

| Case | Time | Space |
| ---- | ---- | ----- |
| All cases | O(n log n) | O(n) |

**Stable:** Yes | **Best for:** Linked lists, external sorting, guaranteed O(n log n)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 51. What is Quick Sort? Implement it.

```python
# Divide and Conquer — O(n log n) average, O(n²) worst
def quick_sort(arr, low=0, high=None):
    if high is None: high = len(arr) - 1
    if low < high:
        pivot_idx = partition(arr, low, high)
        quick_sort(arr, low, pivot_idx - 1)
        quick_sort(arr, pivot_idx + 1, high)
    return arr

def partition(arr, low, high):
    pivot = arr[high]   # last element as pivot
    i = low - 1
    for j in range(low, high):
        if arr[j] <= pivot:
            i += 1
            arr[i], arr[j] = arr[j], arr[i]
    arr[i+1], arr[high] = arr[high], arr[i+1]
    return i + 1

# Test
print(quick_sort([10, 7, 8, 9, 1, 5]))  # [1,5,7,8,9,10]
```

| Case | Time | Space |
| ---- | ---- | ----- |
| Best/Average | O(n log n) | O(log n) |
| Worst (sorted) | O(n²) | O(n) |

**Stable:** No | **In-place:** Yes | **Fastest in practice** for random data

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. What is Heap Sort? How does it work?

```python
import heapq

# Heap Sort using Python's heapq — O(n log n) time, O(n) space
def heap_sort(arr):
    # Min-heap: negate values for max-heap behavior
    heap = arr[:]
    heapq.heapify(heap)            # O(n) — build heap
    return [heapq.heappop(heap) for _ in range(len(heap))]  # O(n log n)

# In-place Heap Sort — O(n log n) time, O(1) space
def heap_sort_inplace(arr):
    n = len(arr)

    # Build max-heap
    for i in range(n // 2 - 1, -1, -1):
        heapify(arr, n, i)

    # Extract elements from heap one by one
    for i in range(n - 1, 0, -1):
        arr[0], arr[i] = arr[i], arr[0]    # move max to end
        heapify(arr, i, 0)
    return arr

def heapify(arr, n, i):
    largest = i
    left, right = 2 * i + 1, 2 * i + 2
    if left < n and arr[left] > arr[largest]:  largest = left
    if right < n and arr[right] > arr[largest]: largest = right
    if largest != i:
        arr[i], arr[largest] = arr[largest], arr[i]
        heapify(arr, n, largest)

print(heap_sort([12, 11, 13, 5, 6, 7]))  # [5,6,7,11,12,13]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 53. What is Counting Sort? When is it useful?

```python
# Counting Sort — O(n + k) time, O(k) space where k = range of values
def counting_sort(arr):
    if not arr: return arr
    max_val = max(arr)
    min_val = min(arr)
    k = max_val - min_val + 1

    count = [0] * k
    for num in arr:
        count[num - min_val] += 1  # frequency count

    result = []
    for i, freq in enumerate(count):
        result.extend([i + min_val] * freq)
    return result

# Test
print(counting_sort([4, 2, 2, 8, 3, 3, 1]))  # [1,2,2,3,3,4,8]
```

**Use when:** Values are small integers in a known range (e.g., grades 0-100, ages 0-120). Not suitable for large ranges or floating points.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 54. Sorting algorithm comparison table

| Algorithm | Best | Average | Worst | Space | Stable | In-place |
| --------- | ---- | ------- | ----- | ----- | ------ | -------- |
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | ✅ | ✅ |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | ❌ | ✅ |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | ✅ | ✅ |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | ✅ | ❌ |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | ❌ | ✅ |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) | ❌ | ✅ |
| Counting Sort | O(n+k) | O(n+k) | O(n+k) | O(k) | ✅ | ❌ |
| Python `sort()` | O(n) | O(n log n) | O(n log n) | O(n) | ✅ | ❌ |

> Python's built-in `sorted()` and `.sort()` use **Timsort** — a hybrid of Merge Sort and Insertion Sort.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Hashing

<br>

### 55. What is Hashing? What is a Hash Table?

**Answer:**

Hashing converts a key into a fixed-size index using a **hash function**, allowing O(1) average-case lookups in a hash table.

```python
# Python dict is a hash table
table = {}
table["name"] = "Sisi"     # O(1) insert
val = table["name"]        # O(1) lookup
"name" in table            # O(1) search
del table["name"]          # O(1) delete

# Python's hash() function
print(hash("hello"))       # deterministic integer
print(hash(42))            # 42

# Hash Set for O(1) membership testing
seen = set()
seen.add(5)                # O(1)
print(5 in seen)           # O(1) — True
```

| Operation | Hash Table Average | Hash Table Worst (all collisions) |
| --------- | ------------------ | --------------------------------- |
| Insert | O(1) | O(n) |
| Search | O(1) | O(n) |
| Delete | O(1) | O(n) |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 56. What are collision resolution techniques?

**Answer:**

A collision occurs when two keys produce the same hash index.

**1. Chaining (Open Hashing)** — each bucket holds a linked list of colliding elements

**2. Open Addressing** — find another slot in the table:
- **Linear Probing:** try next slot: `(hash(key) + i) % size`
- **Quadratic Probing:** try `(hash(key) + i²) % size`
- **Double Hashing:** use a second hash function

```python
# Python uses open addressing (compact hash table variant)
# Each dict bucket: (hash, key, value) or empty/dummy sentinel

# Chaining simulation
class HashTable:
    def __init__(self, size=10):
        self.size = size
        self.buckets = [[] for _ in range(size)]   # each bucket = list (chain)

    def _hash(self, key):
        return hash(key) % self.size

    def set(self, key, value):
        idx = self._hash(key)
        for i, (k, v) in enumerate(self.buckets[idx]):
            if k == key:
                self.buckets[idx][i] = (key, value)  # update existing
                return
        self.buckets[idx].append((key, value))

    def get(self, key):
        idx = self._hash(key)
        for k, v in self.buckets[idx]:
            if k == key: return v
        return None

ht = HashTable()
ht.set("name", "Sisi")
print(ht.get("name"))    # Sisi
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. Find the most frequent element in an array

```python
from collections import Counter

# Approach 1: Counter — O(n) time
def most_frequent(arr):
    count = Counter(arr)
    return count.most_common(1)[0][0]  # most common element

# Approach 2: Manual — O(n)
def most_frequent_manual(arr):
    freq = {}
    for num in arr:
        freq[num] = freq.get(num, 0) + 1
    return max(freq, key=freq.get)

# Approach 3: Moore's Voting Algorithm — O(n) time, O(1) space
# Works only when majority element (>n/2) is guaranteed to exist
def majority_element(nums):
    candidate, count = None, 0
    for num in nums:
        if count == 0: candidate = num
        count += 1 if num == candidate else -1
    return candidate

# Test
print(most_frequent([1, 3, 1, 3, 2, 1]))   # 1
print(majority_element([3, 2, 3]))           # 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 58. Find all pairs with a given sum using hashing

```python
# Find all unique pairs that sum to target — O(n) time, O(n) space
def find_pairs(arr, target):
    seen = set()
    pairs = set()
    for num in arr:
        complement = target - num
        if complement in seen:
            pairs.add((min(num, complement), max(num, complement)))
        seen.add(num)
    return list(pairs)

# Count pairs — O(n)
def count_pairs(arr, target):
    freq = {}
    for num in arr:
        freq[num] = freq.get(num, 0) + 1
    count = 0
    seen = set()
    for num in arr:
        complement = target - num
        if complement in freq and num not in seen:
            if num == complement and freq[num] > 1: count += 1
            elif num != complement: count += 1
            seen.add(num)
    return count

# Test
print(find_pairs([1, 5, 3, 7, 9, 2, 6, 4], 8))  # [(1,7),(2,6),(3,5)]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. Longest consecutive sequence in an array

```python
# Hash Set approach — O(n) time, O(n) space
def longest_consecutive(nums):
    num_set = set(nums)
    max_length = 0

    for num in num_set:
        # Only start counting from the beginning of a sequence
        if num - 1 not in num_set:
            current = num
            length = 1
            while current + 1 in num_set:
                current += 1
                length += 1
            max_length = max(max_length, length)

    return max_length

# Test
print(longest_consecutive([100, 4, 200, 1, 3, 2]))  # 4 (1,2,3,4)
print(longest_consecutive([0, 3, 7, 2, 5, 8, 4, 6, 0, 1]))  # 9
```

**Time:** O(n) — each number processed at most twice | **Space:** O(n)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. Subarray with zero sum

```python
# Prefix sum + hash set — O(n) time, O(n) space
def has_zero_sum_subarray(arr):
    prefix_sums = {0}   # empty prefix has sum 0
    current_sum = 0
    for num in arr:
        current_sum += num
        if current_sum in prefix_sums:
            return True     # subarray from some point to here sums to 0
        prefix_sums.add(current_sum)
    return False

# Find the actual subarray
def find_zero_sum_subarray(arr):
    prefix_sum = 0
    seen = {0: -1}   # sum → index
    for i, num in enumerate(arr):
        prefix_sum += num
        if prefix_sum in seen:
            return arr[seen[prefix_sum]+1 : i+1]  # subarray found
        seen[prefix_sum] = i
    return []

# Test
print(has_zero_sum_subarray([3, 4, -7, 3, 1, 3, 1, -4, -2, -2]))  # True
print(find_zero_sum_subarray([3, 4, -7, 3, 1]))  # [3, 4, -7]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 61. Group anagrams together

```python
from collections import defaultdict

# Sort each string as key — O(n * k log k) where k = avg string length
def group_anagrams(strs):
    groups = defaultdict(list)
    for s in strs:
        key = tuple(sorted(s))   # sorted string as key
        groups[key].append(s)
    return list(groups.values())

# Frequency count as key — O(n * k)
def group_anagrams_v2(strs):
    groups = defaultdict(list)
    for s in strs:
        count = [0] * 26
        for c in s:
            count[ord(c) - ord('a')] += 1
        groups[tuple(count)].append(s)
    return list(groups.values())

# Test
result = group_anagrams(["eat","tea","tan","ate","nat","bat"])
print(result)  # [['eat','tea','ate'], ['tan','nat'], ['bat']]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Trees

<br>

### 62. What is a Binary Tree? Important terminology?

**Answer:**

A Binary Tree is a hierarchical data structure where each node has **at most two children** (left and right).

| Term | Definition |
| ---- | ---------- |
| Root | Topmost node (no parent) |
| Leaf | Node with no children |
| Height | Longest path from root to a leaf |
| Depth | Distance from root to a node |
| Level | Depth + 1 |
| Full BT | Every node has 0 or 2 children |
| Complete BT | All levels filled except last (left-filled) |
| Perfect BT | All levels completely filled |
| Balanced BT | Height difference between subtrees ≤ 1 |

```python
class TreeNode:
    def __init__(self, val=0, left=None, right=None):
        self.val = val
        self.left = left
        self.right = right

# Build a tree:
#       1
#      / \
#     2   3
#    / \
#   4   5
root = TreeNode(1)
root.left = TreeNode(2)
root.right = TreeNode(3)
root.left.left = TreeNode(4)
root.left.right = TreeNode(5)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 63. Implement a Binary Tree and its traversals (Inorder, Preorder, Postorder)

```python
class TreeNode:
    def __init__(self, val=0, left=None, right=None):
        self.val = val; self.left = left; self.right = right

# Inorder: Left → Root → Right (gives sorted output for BST)
def inorder(root):
    if not root: return []
    return inorder(root.left) + [root.val] + inorder(root.right)

# Preorder: Root → Left → Right (useful for copying tree)
def preorder(root):
    if not root: return []
    return [root.val] + preorder(root.left) + preorder(root.right)

# Postorder: Left → Right → Root (useful for deleting tree)
def postorder(root):
    if not root: return []
    return postorder(root.left) + postorder(root.right) + [root.val]

# Iterative inorder using stack — O(n) time, O(h) space
def inorder_iterative(root):
    result, stack = [], []
    curr = root
    while curr or stack:
        while curr:
            stack.append(curr)
            curr = curr.left
        curr = stack.pop()
        result.append(curr.val)
        curr = curr.right
    return result

# Tree:   1
#        / \
#       2   3
#      / \
#     4   5
root = TreeNode(1, TreeNode(2, TreeNode(4), TreeNode(5)), TreeNode(3))
print(inorder(root))    # [4, 2, 5, 1, 3]
print(preorder(root))   # [1, 2, 4, 5, 3]
print(postorder(root))  # [4, 5, 2, 3, 1]
```

**Time:** O(n) | **Space:** O(h) where h = height of tree (O(n) worst, O(log n) balanced)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. Level order traversal (BFS) of a binary tree

```python
from collections import deque

def level_order(root):
    if not root: return []
    result = []
    queue = deque([root])

    while queue:
        level_size = len(queue)
        level = []
        for _ in range(level_size):
            node = queue.popleft()
            level.append(node.val)
            if node.left:  queue.append(node.left)
            if node.right: queue.append(node.right)
        result.append(level)

    return result

# Tree: [[1], [2,3], [4,5]]
root = TreeNode(1, TreeNode(2, TreeNode(4), TreeNode(5)), TreeNode(3))
print(level_order(root))  # [[1], [2, 3], [4, 5]]
```

**Time:** O(n) | **Space:** O(w) where w = maximum width of tree

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 65. Find the height of a binary tree

```python
# Recursive DFS — O(n) time, O(h) space
def max_depth(root):
    if not root: return 0
    left_h = max_depth(root.left)
    right_h = max_depth(root.right)
    return 1 + max(left_h, right_h)

# Iterative BFS — O(n) time, O(w) space
def max_depth_bfs(root):
    if not root: return 0
    queue = deque([root])
    depth = 0
    while queue:
        depth += 1
        for _ in range(len(queue)):
            node = queue.popleft()
            if node.left:  queue.append(node.left)
            if node.right: queue.append(node.right)
    return depth

root = TreeNode(3, TreeNode(9), TreeNode(20, TreeNode(15), TreeNode(7)))
print(max_depth(root))  # 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 66. Check if a binary tree is balanced

```python
# O(n) time — bottom-up, check height and balance simultaneously
def is_balanced(root):
    def check(node):
        if not node: return 0   # height of empty = 0
        left_h = check(node.left)
        if left_h == -1: return -1  # left subtree not balanced
        right_h = check(node.right)
        if right_h == -1: return -1  # right subtree not balanced
        if abs(left_h - right_h) > 1: return -1  # this node not balanced
        return 1 + max(left_h, right_h)

    return check(root) != -1

# Test
balanced = TreeNode(1, TreeNode(2, TreeNode(3), None), TreeNode(4))
unbalanced = TreeNode(1, TreeNode(2, TreeNode(3, TreeNode(4), None), None), None)
print(is_balanced(balanced))    # True
print(is_balanced(unbalanced))  # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. Find the diameter of a binary tree

**Diameter** = longest path between any two nodes (may not pass through root).

```python
def diameter_of_binary_tree(root):
    max_diameter = [0]  # use list to modify in nested function

    def height(node):
        if not node: return 0
        left_h = height(node.left)
        right_h = height(node.right)
        # diameter through this node = left_height + right_height
        max_diameter[0] = max(max_diameter[0], left_h + right_h)
        return 1 + max(left_h, right_h)

    height(root)
    return max_diameter[0]

root = TreeNode(1, TreeNode(2, TreeNode(4), TreeNode(5)), TreeNode(3))
print(diameter_of_binary_tree(root))  # 3 (path: 4→2→1→3 or 5→2→1→3)
```

**Time:** O(n) | **Space:** O(h)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. Lowest Common Ancestor (LCA) of two nodes

```python
# LCA in Binary Tree — O(n) time
def lca(root, p, q):
    if not root: return None
    if root == p or root == q: return root  # found one of the nodes

    left  = lca(root.left, p, q)
    right = lca(root.right, p, q)

    if left and right: return root   # p and q are in different subtrees → root is LCA
    return left or right              # both in same subtree

# LCA in BST — O(h) time using BST property
def lca_bst(root, p, q):
    while root:
        if p.val < root.val and q.val < root.val:
            root = root.left      # both in left subtree
        elif p.val > root.val and q.val > root.val:
            root = root.right     # both in right subtree
        else:
            return root           # split point → LCA found
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. What is a Binary Search Tree (BST)? Insert and search.

**Answer:**

A BST is a binary tree where for every node: **left subtree values < node < right subtree values**.

```python
class BST:
    def __init__(self):
        self.root = None

    def insert(self, val):         # O(h) time
        def _insert(node, val):
            if not node: return TreeNode(val)
            if val < node.val: node.left = _insert(node.left, val)
            elif val > node.val: node.right = _insert(node.right, val)
            return node
        self.root = _insert(self.root, val)

    def search(self, val):         # O(h) time
        def _search(node, val):
            if not node: return False
            if val == node.val: return True
            if val < node.val: return _search(node.left, val)
            return _search(node.right, val)
        return _search(self.root, val)

# Iterative search — O(h) time, O(1) space
def search_bst(root, val):
    while root:
        if val == root.val: return root
        elif val < root.val: root = root.left
        else: root = root.right
    return None

bst = BST()
for val in [5, 3, 7, 1, 4, 6, 8]:
    bst.insert(val)
print(bst.search(4))  # True
print(bst.search(9))  # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 70. Validate if a binary tree is a BST

```python
# Pass min/max bounds down — O(n) time, O(h) space
def is_valid_bst(root, min_val=float('-inf'), max_val=float('inf')):
    if not root: return True
    if root.val <= min_val or root.val >= max_val: return False
    return (is_valid_bst(root.left, min_val, root.val) and
            is_valid_bst(root.right, root.val, max_val))

# Inorder should give sorted sequence
def is_valid_bst_inorder(root):
    prev = [float('-inf')]
    def inorder(node):
        if not node: return True
        if not inorder(node.left): return False
        if node.val <= prev[0]: return False
        prev[0] = node.val
        return inorder(node.right)
    return inorder(root)

valid = TreeNode(2, TreeNode(1), TreeNode(3))
invalid = TreeNode(5, TreeNode(1), TreeNode(4, TreeNode(3), TreeNode(6)))
print(is_valid_bst(valid))    # True
print(is_valid_bst(invalid))  # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. Delete a node from a BST

```python
def delete_node(root, key):
    if not root: return None
    if key < root.val:
        root.left = delete_node(root.left, key)
    elif key > root.val:
        root.right = delete_node(root.right, key)
    else:
        # Case 1: Leaf node or one child
        if not root.left: return root.right
        if not root.right: return root.left
        # Case 2: Two children — replace with inorder successor (min of right subtree)
        successor = root.right
        while successor.left: successor = successor.left
        root.val = successor.val                  # copy successor value
        root.right = delete_node(root.right, successor.val)  # delete successor
    return root
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. Inorder successor in a BST

```python
# Inorder successor = next larger element in inorder traversal
def inorder_successor(root, p):
    successor = None
    while root:
        if p.val < root.val:
            successor = root     # potential successor (it's larger than p)
            root = root.left
        else:
            root = root.right
    return successor
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 73. Convert sorted array to balanced BST

```python
# Recursively pick middle element as root — O(n) time
def sorted_array_to_bst(nums):
    if not nums: return None
    mid = len(nums) // 2
    node = TreeNode(nums[mid])
    node.left  = sorted_array_to_bst(nums[:mid])
    node.right = sorted_array_to_bst(nums[mid+1:])
    return node

arr = [-10, -3, 0, 5, 9]
root = sorted_array_to_bst(arr)
print(inorder(root))  # [-10, -3, 0, 5, 9] — sorted ✓
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. Zigzag level order traversal

```python
from collections import deque

def zigzag_level_order(root):
    if not root: return []
    result = []
    queue = deque([root])
    left_to_right = True

    while queue:
        level = []
        for _ in range(len(queue)):
            node = queue.popleft()
            level.append(node.val)
            if node.left:  queue.append(node.left)
            if node.right: queue.append(node.right)
        result.append(level if left_to_right else level[::-1])
        left_to_right = not left_to_right

    return result

root = TreeNode(3, TreeNode(9), TreeNode(20, TreeNode(15), TreeNode(7)))
print(zigzag_level_order(root))  # [[3], [20, 9], [15, 7]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. Find all paths from root to leaf

```python
def root_to_leaf_paths(root):
    result = []
    def dfs(node, path):
        if not node: return
        path.append(node.val)
        if not node.left and not node.right:   # leaf node
            result.append(list(path))
        dfs(node.left, path)
        dfs(node.right, path)
        path.pop()   # backtrack

    dfs(root, [])
    return result

root = TreeNode(1, TreeNode(2, TreeNode(4), TreeNode(5)), TreeNode(3))
print(root_to_leaf_paths(root))  # [[1,2,4], [1,2,5], [1,3]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Heap & Priority Queue

<br>

### 76. What is a Heap? Min-Heap vs Max-Heap?

**Answer:**

A Heap is a **complete binary tree** satisfying the heap property. Python's `heapq` implements a **min-heap** by default.

| Feature | Min-Heap | Max-Heap |
| ------- | -------- | -------- |
| Root | Smallest element | Largest element |
| Property | Parent ≤ Children | Parent ≥ Children |
| Use case | Get minimum fast | Get maximum fast |

```python
import heapq

# Min-Heap
min_heap = []
heapq.heappush(min_heap, 5)
heapq.heappush(min_heap, 1)
heapq.heappush(min_heap, 3)
print(heapq.heappop(min_heap))   # 1 — always pops minimum

# Max-Heap: negate values
max_heap = []
for val in [5, 1, 3]:
    heapq.heappush(max_heap, -val)
print(-heapq.heappop(max_heap))  # 5 — largest

# Build heap from list — O(n)
arr = [3, 1, 4, 1, 5, 9, 2, 6]
heapq.heapify(arr)  # in-place min-heap

# Heap operations: push O(log n), pop O(log n), peek O(1)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. Find K largest elements using a heap

```python
import heapq

# Using min-heap of size K — O(n log k) time
def k_largest(nums, k):
    # Maintain a min-heap of size k
    heap = nums[:k]
    heapq.heapify(heap)
    for num in nums[k:]:
        if num > heap[0]:
            heapq.heapreplace(heap, num)  # remove min, add num
    return sorted(heap, reverse=True)

# Python built-in — O(n log k)
def k_largest_builtin(nums, k):
    return heapq.nlargest(k, nums)

# Test
print(k_largest([3,2,1,5,6,4], 2))         # [6, 5]
print(k_largest_builtin([3,2,1,5,6,4], 2)) # [6, 5]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 78. Find the Kth smallest element in an array

```python
import heapq
import random

# Approach 1: Min-Heap — O(n + k log n)
def kth_smallest_heap(nums, k):
    heapq.heapify(nums)
    for _ in range(k - 1):
        heapq.heappop(nums)
    return heapq.heappop(nums)

# Approach 2: Max-Heap of size K — O(n log k)
def kth_smallest(nums, k):
    heap = []
    for num in nums:
        heapq.heappush(heap, -num)
        if len(heap) > k:
            heapq.heappop(heap)
    return -heap[0]

# Approach 3: QuickSelect — O(n) average, O(n²) worst
def kth_smallest_quickselect(nums, k):
    pivot = random.choice(nums)
    less    = [x for x in nums if x < pivot]
    equal   = [x for x in nums if x == pivot]
    greater = [x for x in nums if x > pivot]
    if k <= len(less): return kth_smallest_quickselect(less, k)
    elif k <= len(less) + len(equal): return pivot
    else: return kth_smallest_quickselect(greater, k - len(less) - len(equal))

print(kth_smallest([3,2,1,5,6,4], 2))           # 2
print(kth_smallest_quickselect([7,10,4,3,20,15], 3))  # 7
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. Merge K sorted arrays using a heap

```python
import heapq

# Min-heap stores (value, array_index, element_index) — O(n log k)
def merge_k_sorted(arrays):
    result = []
    heap = []

    # Initialize heap with first element from each array
    for i, arr in enumerate(arrays):
        if arr:
            heapq.heappush(heap, (arr[0], i, 0))

    while heap:
        val, arr_idx, elem_idx = heapq.heappop(heap)
        result.append(val)
        # Push next element from the same array
        if elem_idx + 1 < len(arrays[arr_idx]):
            next_val = arrays[arr_idx][elem_idx + 1]
            heapq.heappush(heap, (next_val, arr_idx, elem_idx + 1))

    return result

arrays = [[1, 4, 7], [2, 5, 8], [3, 6, 9]]
print(merge_k_sorted(arrays))  # [1,2,3,4,5,6,7,8,9]
```

**Time:** O(n log k) where n = total elements, k = number of arrays

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. Top K frequent elements

```python
import heapq
from collections import Counter

# Min-heap of size K — O(n log k)
def top_k_frequent(nums, k):
    count = Counter(nums)
    return heapq.nlargest(k, count.keys(), key=count.get)

# Bucket Sort approach — O(n) time
def top_k_frequent_bucket(nums, k):
    count = Counter(nums)
    buckets = [[] for _ in range(len(nums) + 1)]
    for num, freq in count.items():
        buckets[freq].append(num)
    result = []
    for i in range(len(buckets) - 1, -1, -1):
        result.extend(buckets[i])
        if len(result) >= k: break
    return result[:k]

print(top_k_frequent([1,1,1,2,2,3], 2))          # [1, 2]
print(top_k_frequent_bucket([1,1,1,2,2,3], 2))   # [1, 2]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Sliding Window & Two Pointers

<br>

### 81. What is the Sliding Window technique?

**Answer:**

The sliding window technique maintains a **window (subarray/substring) that slides over the input**, avoiding re-computation of overlapping parts.

```
Fixed window of size K:
arr = [1, 3, -1, -3, 5, 3, 6, 7], K=3
      [1  3  -1]
         [3  -1  -3]
               [-1  -3  5]  ← window slides right by 1
```

**Two types:**
- **Fixed size:** window size is constant (e.g., max sum of subarray of size K)
- **Variable size:** window expands/shrinks based on condition (e.g., longest substring)

**Time:** Usually O(n) — each element enters and leaves the window once

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 82. Longest substring without repeating characters

```python
# Sliding window + hash map — O(n) time, O(min(n,m)) space
def length_of_longest_substring(s):
    char_index = {}   # char → most recent index
    max_len = 0
    left = 0

    for right, char in enumerate(s):
        if char in char_index and char_index[char] >= left:
            left = char_index[char] + 1   # shrink window: move left past duplicate
        char_index[char] = right
        max_len = max(max_len, right - left + 1)

    return max_len

# Test
print(length_of_longest_substring("abcabcbb"))  # 3 ("abc")
print(length_of_longest_substring("pwwkew"))    # 3 ("wke")
print(length_of_longest_substring("bbbbb"))     # 1 ("b")
```

**Time:** O(n) | **Space:** O(min(n, charset_size))

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 83. Maximum sum subarray of size K

```python
# Fixed sliding window — O(n) time, O(1) space
def max_sum_subarray(arr, k):
    if len(arr) < k: return -1

    window_sum = sum(arr[:k])
    max_sum = window_sum

    for i in range(k, len(arr)):
        window_sum += arr[i] - arr[i - k]   # slide: add new, remove old
        max_sum = max(max_sum, window_sum)

    return max_sum

# Test
print(max_sum_subarray([2, 1, 5, 1, 3, 2], 3))  # 9 (5+1+3)
print(max_sum_subarray([2, 3, 4, 1, 5], 2))     # 7 (3+4)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. Minimum window substring

```python
from collections import Counter

# Variable sliding window — O(n) time
def min_window(s, t):
    if not t or not s: return ""
    need = Counter(t)
    missing = len(t)   # total characters still needed
    start = 0
    best = ""
    left = 0

    for right, c in enumerate(s):
        if need[c] > 0: missing -= 1
        need[c] -= 1
        if missing == 0:   # found valid window
            # shrink from left
            while need[s[left]] < 0:
                need[s[left]] += 1
                left += 1
            window = s[left:right+1]
            if not best or len(window) < len(best):
                best = window
            need[s[left]] += 1
            missing += 1
            left += 1

    return best

print(min_window("ADOBECODEBANC", "ABC"))  # "BANC"
print(min_window("a", "a"))               # "a"
```

**Time:** O(n) | **Space:** O(|charset|) — classic hard sliding window problem

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. What is the Two Pointers technique?

**Answer:**

Two pointers use **two indices that move through the array** (often from both ends or at different speeds) to solve problems in O(n) that would otherwise need O(n²).

```python
# Classic: check if sorted array has pair summing to target
def has_pair_with_sum(arr, target):   # arr must be sorted
    left, right = 0, len(arr) - 1
    while left < right:
        s = arr[left] + arr[right]
        if s == target: return True
        elif s < target: left += 1    # need bigger sum
        else: right -= 1              # need smaller sum
    return False

# Remove duplicates from sorted array in-place
def remove_duplicates(nums):
    if not nums: return 0
    slow = 0
    for fast in range(1, len(nums)):
        if nums[fast] != nums[slow]:
            slow += 1
            nums[slow] = nums[fast]
    return slow + 1

print(has_pair_with_sum([1,2,4,6,8,14], 14))  # True (6+8)
print(remove_duplicates([1,1,2,2,3]))          # 3 → [1,2,3,...]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 86. Container with most water

```python
# Two pointers from both ends — O(n) time, O(1) space
def max_area(height):
    left, right = 0, len(height) - 1
    max_water = 0
    while left < right:
        water = min(height[left], height[right]) * (right - left)
        max_water = max(max_water, water)
        # Move the pointer with smaller height (can only improve with taller wall)
        if height[left] < height[right]: left += 1
        else: right -= 1
    return max_water

print(max_area([1,8,6,2,5,4,8,3,7]))  # 49
print(max_area([1,1]))                 # 1
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 87. 3Sum — find all triplets that sum to zero

```python
# Sort + Two Pointers — O(n²) time, O(1) extra space
def three_sum(nums):
    nums.sort()
    result = []
    n = len(nums)

    for i in range(n - 2):
        if i > 0 and nums[i] == nums[i-1]: continue   # skip duplicate i
        left, right = i + 1, n - 1
        while left < right:
            total = nums[i] + nums[left] + nums[right]
            if total == 0:
                result.append([nums[i], nums[left], nums[right]])
                while left < right and nums[left] == nums[left+1]: left += 1   # skip dups
                while left < right and nums[right] == nums[right-1]: right -= 1
                left += 1; right -= 1
            elif total < 0: left += 1
            else: right -= 1

    return result

print(three_sum([-1,0,1,2,-1,-4]))  # [[-1,-1,2],[-1,0,1]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 88. Trapping rain water

```python
# Two pointers — O(n) time, O(1) space
def trap(height):
    left, right = 0, len(height) - 1
    left_max = right_max = 0
    water = 0

    while left < right:
        if height[left] < height[right]:
            if height[left] >= left_max: left_max = height[left]
            else: water += left_max - height[left]
            left += 1
        else:
            if height[right] >= right_max: right_max = height[right]
            else: water += right_max - height[right]
            right -= 1

    return water

# Dynamic programming approach — O(n) time, O(n) space
def trap_dp(height):
    n = len(height)
    left_max = [0] * n
    right_max = [0] * n
    left_max[0] = height[0]
    right_max[-1] = height[-1]
    for i in range(1, n): left_max[i] = max(left_max[i-1], height[i])
    for i in range(n-2, -1, -1): right_max[i] = max(right_max[i+1], height[i])
    return sum(min(left_max[i], right_max[i]) - height[i] for i in range(n))

print(trap([0,1,0,2,1,0,1,3,2,1,2,1]))  # 6
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Graphs

<br>

### 89. What is a Graph? Types and representations?

**Answer:**

A graph G = (V, E) consists of **vertices (nodes) V** and **edges E** connecting them.

| Type | Description |
| ---- | ----------- |
| Undirected | Edges have no direction |
| Directed (Digraph) | Edges have direction (A→B ≠ B→A) |
| Weighted | Edges have weights/costs |
| Cyclic | Contains at least one cycle |
| Acyclic | No cycles (DAG = Directed Acyclic Graph) |

```python
# Adjacency List (most common — space efficient for sparse graphs)
graph = {
    0: [1, 2],
    1: [0, 3],
    2: [0, 4],
    3: [1],
    4: [2]
}

# Adjacency Matrix (good for dense graphs, O(1) edge lookup)
n = 5
matrix = [[0] * n for _ in range(n)]
matrix[0][1] = 1; matrix[1][0] = 1  # undirected edge 0-1
matrix[0][2] = 1; matrix[2][0] = 1  # undirected edge 0-2

# Edge List
edges = [(0,1), (0,2), (1,3), (2,4)]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. Implement BFS (Breadth First Search)

```python
from collections import deque

def bfs(graph, start):
    visited = set([start])
    queue = deque([start])
    order = []

    while queue:
        node = queue.popleft()
        order.append(node)
        for neighbor in graph[node]:
            if neighbor not in visited:
                visited.add(neighbor)
                queue.append(neighbor)

    return order

graph = {0: [1,2], 1: [0,3,4], 2: [0], 3: [1], 4: [1]}
print(bfs(graph, 0))  # [0, 1, 2, 3, 4]

# BFS shortest path
def bfs_shortest_path(graph, start, end):
    queue = deque([(start, [start])])
    visited = {start}
    while queue:
        node, path = queue.popleft()
        if node == end: return path
        for neighbor in graph[node]:
            if neighbor not in visited:
                visited.add(neighbor)
                queue.append((neighbor, path + [neighbor]))
    return None
```

**Time:** O(V + E) | **Space:** O(V)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 91. Implement DFS (Depth First Search)

```python
# Recursive DFS
def dfs_recursive(graph, node, visited=None):
    if visited is None: visited = set()
    visited.add(node)
    order = [node]
    for neighbor in graph[node]:
        if neighbor not in visited:
            order.extend(dfs_recursive(graph, neighbor, visited))
    return order

# Iterative DFS using stack
def dfs_iterative(graph, start):
    visited = set()
    stack = [start]
    order = []
    while stack:
        node = stack.pop()
        if node not in visited:
            visited.add(node)
            order.append(node)
            # Add neighbors (reversed so left neighbors processed first)
            for neighbor in reversed(graph[node]):
                if neighbor not in visited:
                    stack.append(neighbor)
    return order

graph = {0: [1,2], 1: [0,3,4], 2: [0], 3: [1], 4: [1]}
print(dfs_recursive(graph, 0))   # [0, 1, 3, 4, 2]
print(dfs_iterative(graph, 0))   # [0, 1, 3, 4, 2]
```

**Time:** O(V + E) | **Space:** O(V)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. Detect a cycle in an undirected graph

```python
# BFS/DFS with parent tracking — O(V + E)
def has_cycle_undirected(graph):
    visited = set()

    def dfs(node, parent):
        visited.add(node)
        for neighbor in graph[node]:
            if neighbor not in visited:
                if dfs(neighbor, node): return True
            elif neighbor != parent:    # visited and not parent → cycle!
                return True
        return False

    for node in graph:
        if node not in visited:
            if dfs(node, -1): return True
    return False

# Union-Find approach
def has_cycle_union_find(n, edges):
    parent = list(range(n))
    def find(x):
        while parent[x] != x:
            parent[x] = parent[parent[x]]  # path compression
            x = parent[x]
        return x
    def union(x, y):
        px, py = find(x), find(y)
        if px == py: return False   # same component → cycle!
        parent[px] = py
        return True
    for u, v in edges:
        if not union(u, v): return True
    return False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. Detect a cycle in a directed graph

```python
# DFS with rec_stack (currently in recursion stack) — O(V + E)
def has_cycle_directed(graph):
    visited = set()
    rec_stack = set()

    def dfs(node):
        visited.add(node)
        rec_stack.add(node)
        for neighbor in graph.get(node, []):
            if neighbor not in visited:
                if dfs(neighbor): return True
            elif neighbor in rec_stack:  # back edge → cycle!
                return True
        rec_stack.remove(node)
        return False

    for node in graph:
        if node not in visited:
            if dfs(node): return True
    return False

# Test
cyclic = {0: [1], 1: [2], 2: [0]}    # 0→1→2→0
acyclic = {0: [1], 1: [2], 2: []}    # 0→1→2
print(has_cycle_directed(cyclic))   # True
print(has_cycle_directed(acyclic))  # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. Topological Sort (Kahn's algorithm)

```python
from collections import deque

# Kahn's BFS-based topological sort — O(V + E)
def topological_sort(n, edges):
    graph = {i: [] for i in range(n)}
    in_degree = [0] * n

    for u, v in edges:
        graph[u].append(v)
        in_degree[v] += 1

    # Start with nodes having no incoming edges
    queue = deque([i for i in range(n) if in_degree[i] == 0])
    order = []

    while queue:
        node = queue.popleft()
        order.append(node)
        for neighbor in graph[node]:
            in_degree[neighbor] -= 1
            if in_degree[neighbor] == 0:
                queue.append(neighbor)

    if len(order) != n:
        return []   # cycle detected — topological sort not possible
    return order

# Course schedule: can you finish all courses?
def can_finish(num_courses, prerequisites):
    order = topological_sort(num_courses, prerequisites)
    return len(order) == num_courses

print(topological_sort(6, [(5,2),(5,0),(4,0),(4,1),(2,3),(3,1)]))  # [4,5,0,2,3,1]
print(can_finish(2, [[1,0]]))    # True
print(can_finish(2, [[1,0],[0,1]]))  # False (cycle)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. Number of islands (connected components)

```python
# DFS approach — O(m*n) time, O(m*n) space
def num_islands(grid):
    if not grid: return 0
    rows, cols = len(grid), len(grid[0])
    count = 0

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols or grid[r][c] == '0':
            return
        grid[r][c] = '0'   # mark as visited
        dfs(r+1, c); dfs(r-1, c); dfs(r, c+1); dfs(r, c-1)

    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == '1':
                count += 1
                dfs(r, c)   # sink the entire island

    return count

grid = [["1","1","0","0","0"],
        ["1","1","0","0","0"],
        ["0","0","1","0","0"],
        ["0","0","0","1","1"]]
print(num_islands(grid))  # 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. Shortest path in an unweighted graph (BFS)

```python
from collections import deque

def shortest_path(graph, start, end):
    if start == end: return 0
    visited = {start}
    queue = deque([(start, 0)])   # (node, distance)

    while queue:
        node, dist = queue.popleft()
        for neighbor in graph[node]:
            if neighbor == end: return dist + 1
            if neighbor not in visited:
                visited.add(neighbor)
                queue.append((neighbor, dist + 1))

    return -1  # no path

graph = {0:[1,2], 1:[0,3], 2:[0,4], 3:[1,5], 4:[2,5], 5:[3,4]}
print(shortest_path(graph, 0, 5))  # 3
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. Dijkstra's shortest path algorithm

```python
import heapq

# Greedy + min-heap — O((V + E) log V)
def dijkstra(graph, start):
    dist = {node: float('inf') for node in graph}
    dist[start] = 0
    heap = [(0, start)]   # (distance, node)

    while heap:
        d, node = heapq.heappop(heap)
        if d > dist[node]: continue   # stale entry
        for neighbor, weight in graph[node]:
            new_dist = d + weight
            if new_dist < dist[neighbor]:
                dist[neighbor] = new_dist
                heapq.heappush(heap, (new_dist, neighbor))

    return dist

# Weighted graph: {node: [(neighbor, weight), ...]}
graph = {
    0: [(1, 4), (2, 1)],
    1: [(3, 1)],
    2: [(1, 2), (3, 5)],
    3: []
}
print(dijkstra(graph, 0))  # {0:0, 1:3, 2:1, 3:4}
```

**Time:** O((V+E) log V) | **Limitation:** Doesn't work with negative weight edges

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. Bellman-Ford algorithm

```python
# Handles negative weights — O(V * E) time
def bellman_ford(vertices, edges, start):
    dist = {i: float('inf') for i in range(vertices)}
    dist[start] = 0

    # Relax all edges V-1 times
    for _ in range(vertices - 1):
        for u, v, w in edges:
            if dist[u] != float('inf') and dist[u] + w < dist[v]:
                dist[v] = dist[u] + w

    # Check for negative weight cycles (Vth relaxation should not improve)
    for u, v, w in edges:
        if dist[u] != float('inf') and dist[u] + w < dist[v]:
            return None  # negative cycle detected

    return dist

# edges: [(from, to, weight)]
edges = [(0,1,4),(0,2,1),(2,1,2),(1,3,1),(2,3,5)]
print(bellman_ford(4, edges, 0))  # {0:0, 1:3, 2:1, 3:4}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. Floyd-Warshall algorithm (All pairs shortest path)

```python
# O(V³) time, O(V²) space — finds shortest path between ALL pairs
def floyd_warshall(n, edges):
    INF = float('inf')
    dist = [[INF] * n for _ in range(n)]
    for i in range(n): dist[i][i] = 0
    for u, v, w in edges: dist[u][v] = w

    for k in range(n):           # intermediate vertex
        for i in range(n):       # source
            for j in range(n):   # destination
                if dist[i][k] + dist[k][j] < dist[i][j]:
                    dist[i][j] = dist[i][k] + dist[k][j]

    return dist

edges = [(0,1,3),(0,3,7),(1,0,8),(1,2,2),(2,0,5),(2,3,1),(3,0,2)]
result = floyd_warshall(4, edges)
for row in result: print(row)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. Minimum Spanning Tree — Prim's algorithm

```python
import heapq

# Greedy + min-heap — O(E log V)
def prim_mst(graph, start=0):
    visited = set()
    heap = [(0, start, -1)]   # (weight, node, parent)
    mst_edges = []
    total_weight = 0

    while heap:
        weight, node, parent = heapq.heappop(heap)
        if node in visited: continue
        visited.add(node)
        if parent != -1:
            mst_edges.append((parent, node, weight))
            total_weight += weight
        for neighbor, w in graph[node]:
            if neighbor not in visited:
                heapq.heappush(heap, (w, neighbor, node))

    return mst_edges, total_weight

graph = {0:[(1,2),(3,6)], 1:[(0,2),(2,3),(3,8),(4,5)],
         2:[(1,3),(4,7)], 3:[(0,6),(1,8),(4,9)], 4:[(1,5),(2,7),(3,9)]}
edges, cost = prim_mst(graph)
print(f"MST edges: {edges}, Total cost: {cost}")  # cost: 16
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 101. Minimum Spanning Tree — Kruskal's algorithm + Union Find

```python
# Sort edges + Union-Find — O(E log E)
def kruskal_mst(n, edges):
    parent = list(range(n))
    rank = [0] * n

    def find(x):
        while parent[x] != x:
            parent[x] = parent[parent[x]]  # path compression
            x = parent[x]
        return x

    def union(x, y):
        px, py = find(x), find(y)
        if px == py: return False   # same component → cycle
        if rank[px] < rank[py]: px, py = py, px
        parent[py] = px
        if rank[px] == rank[py]: rank[px] += 1
        return True

    edges.sort(key=lambda e: e[2])   # sort by weight
    mst = []
    for u, v, w in edges:
        if union(u, v):
            mst.append((u, v, w))
        if len(mst) == n - 1: break

    return mst, sum(e[2] for e in mst)

edges = [(0,1,2),(1,2,3),(0,3,6),(1,3,8),(1,4,5),(2,4,7),(3,4,9)]
mst, cost = kruskal_mst(5, edges)
print(f"MST: {mst}, Cost: {cost}")  # Cost: 16
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Dynamic Programming

<br>

### 102. What is Dynamic Programming? When to use it?

**Answer:**

Dynamic Programming (DP) solves problems by **breaking them into overlapping subproblems**, solving each once, and storing results to avoid recomputation.

**When to use DP — two conditions must hold:**
1. **Optimal Substructure** — optimal solution built from optimal solutions of subproblems
2. **Overlapping Subproblems** — same subproblems solved multiple times

**Common DP patterns:**
- 1D DP: Fibonacci, Climbing Stairs, House Robber
- 2D DP: Knapsack, LCS, Edit Distance
- Interval DP: Matrix Chain Multiplication
- Tree DP: House Robber III

```python
# Identify DP problems by these signals:
# - "minimum/maximum"
# - "number of ways"
# - "can you reach/achieve"
# - "longest/shortest sequence"
# - Involves choices at each step with optimal outcome
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 103. Fibonacci using DP (memoization + tabulation)

```python
# Naive recursion — O(2^n) — very slow
def fib_naive(n):
    if n <= 1: return n
    return fib_naive(n-1) + fib_naive(n-2)

# Memoization (top-down) — O(n) time, O(n) space
from functools import lru_cache
@lru_cache(maxsize=None)
def fib_memo(n):
    if n <= 1: return n
    return fib_memo(n-1) + fib_memo(n-2)

# Tabulation (bottom-up) — O(n) time, O(n) space
def fib_tab(n):
    if n <= 1: return n
    dp = [0] * (n + 1)
    dp[1] = 1
    for i in range(2, n + 1):
        dp[i] = dp[i-1] + dp[i-2]
    return dp[n]

# Space optimized — O(n) time, O(1) space
def fib_optimized(n):
    if n <= 1: return n
    a, b = 0, 1
    for _ in range(2, n + 1):
        a, b = b, a + b
    return b

print(fib_optimized(10))  # 55
print(fib_tab(10))        # 55
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 104. 0/1 Knapsack problem

```python
# Classic DP — O(n*W) time, O(n*W) space
def knapsack_01(weights, values, W):
    n = len(weights)
    dp = [[0] * (W + 1) for _ in range(n + 1)]

    for i in range(1, n + 1):
        for w in range(W + 1):
            # Don't include item i
            dp[i][w] = dp[i-1][w]
            # Include item i if it fits
            if weights[i-1] <= w:
                dp[i][w] = max(dp[i][w], values[i-1] + dp[i-1][w - weights[i-1]])

    return dp[n][W]

# Space optimized — O(W) space
def knapsack_optimized(weights, values, W):
    dp = [0] * (W + 1)
    for i in range(len(weights)):
        # Traverse right to left to avoid using item twice
        for w in range(W, weights[i]-1, -1):
            dp[w] = max(dp[w], values[i] + dp[w - weights[i]])
    return dp[W]

weights = [1, 3, 4, 5]
values  = [1, 4, 5, 7]
W = 7
print(knapsack_01(weights, values, W))        # 9
print(knapsack_optimized(weights, values, W)) # 9
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 105. Longest Common Subsequence (LCS)

```python
# 2D DP — O(m*n) time, O(m*n) space
def lcs(s1, s2):
    m, n = len(s1), len(s2)
    dp = [[0] * (n + 1) for _ in range(m + 1)]

    for i in range(1, m + 1):
        for j in range(1, n + 1):
            if s1[i-1] == s2[j-1]:
                dp[i][j] = 1 + dp[i-1][j-1]
            else:
                dp[i][j] = max(dp[i-1][j], dp[i][j-1])

    return dp[m][n]

# Reconstruct the actual LCS string
def lcs_string(s1, s2):
    m, n = len(s1), len(s2)
    dp = [[0]*(n+1) for _ in range(m+1)]
    for i in range(1,m+1):
        for j in range(1,n+1):
            if s1[i-1]==s2[j-1]: dp[i][j]=1+dp[i-1][j-1]
            else: dp[i][j]=max(dp[i-1][j],dp[i][j-1])
    result = []
    i, j = m, n
    while i > 0 and j > 0:
        if s1[i-1]==s2[j-1]: result.append(s1[i-1]); i-=1; j-=1
        elif dp[i-1][j]>dp[i][j-1]: i-=1
        else: j-=1
    return ''.join(reversed(result))

print(lcs("ABCBDAB", "BDCABA"))      # 4
print(lcs_string("ABCBDAB", "BDCABA"))  # "BCBA" or "BDAB"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 106. Longest Increasing Subsequence (LIS)

```python
# DP — O(n²) time
def lis_dp(nums):
    if not nums: return 0
    n = len(nums)
    dp = [1] * n   # each element is LIS of length 1

    for i in range(1, n):
        for j in range(i):
            if nums[j] < nums[i]:
                dp[i] = max(dp[i], dp[j] + 1)

    return max(dp)

# Binary search + patience sorting — O(n log n) time
import bisect
def lis_fast(nums):
    tails = []   # tails[i] = smallest tail of LIS of length i+1
    for num in nums:
        pos = bisect.bisect_left(tails, num)
        if pos == len(tails): tails.append(num)
        else: tails[pos] = num
    return len(tails)

print(lis_dp([10,9,2,5,3,7,101,18]))   # 4 (2,3,7,18 or 2,5,7,18)
print(lis_fast([10,9,2,5,3,7,101,18])) # 4
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 107. Coin Change — minimum coins

```python
# Bottom-up DP — O(amount * len(coins)) time
def coin_change(coins, amount):
    dp = [float('inf')] * (amount + 1)
    dp[0] = 0   # 0 coins needed to make 0

    for coin in coins:
        for amt in range(coin, amount + 1):
            dp[amt] = min(dp[amt], dp[amt - coin] + 1)

    return dp[amount] if dp[amount] != float('inf') else -1

print(coin_change([1,5,6,9], 11))  # 2 (5+6)
print(coin_change([2], 3))         # -1 (impossible)
print(coin_change([1,2,5], 11))    # 3 (5+5+1)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 108. Coin Change — number of ways

```python
# Count combinations (unbounded knapsack variant)
def coin_change_ways(coins, amount):
    dp = [0] * (amount + 1)
    dp[0] = 1   # one way to make 0: use no coins

    for coin in coins:
        for amt in range(coin, amount + 1):
            dp[amt] += dp[amt - coin]

    return dp[amount]

print(coin_change_ways([1,2,5], 5))    # 4 (5, 2+2+1, 2+1+1+1, 1+1+1+1+1)
print(coin_change_ways([2,3,6,7], 10)) # 5
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 109. Maximum subarray sum (Kadane's algorithm)

```python
# Kadane's — O(n) time, O(1) space
def max_subarray(nums):
    max_sum = current_sum = nums[0]
    for num in nums[1:]:
        current_sum = max(num, current_sum + num)   # extend or start fresh
        max_sum = max(max_sum, current_sum)
    return max_sum

# Return the actual subarray
def max_subarray_with_indices(nums):
    max_sum = current_sum = nums[0]
    start = end = temp_start = 0
    for i in range(1, len(nums)):
        if nums[i] > current_sum + nums[i]:
            current_sum = nums[i]
            temp_start = i
        else:
            current_sum += nums[i]
        if current_sum > max_sum:
            max_sum = current_sum
            start = temp_start
            end = i
    return max_sum, nums[start:end+1]

print(max_subarray([-2,1,-3,4,-1,2,1,-5,4]))        # 6 (4,-1,2,1)
print(max_subarray_with_indices([-2,1,-3,4,-1,2,1,-5,4]))  # (6, [4,-1,2,1])
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 110. Edit Distance (Levenshtein distance)

```python
# Minimum operations (insert, delete, replace) to convert s1 to s2
def edit_distance(s1, s2):
    m, n = len(s1), len(s2)
    dp = [[0] * (n + 1) for _ in range(m + 1)]

    # Base cases
    for i in range(m + 1): dp[i][0] = i   # delete all chars of s1
    for j in range(n + 1): dp[0][j] = j   # insert all chars of s2

    for i in range(1, m + 1):
        for j in range(1, n + 1):
            if s1[i-1] == s2[j-1]:
                dp[i][j] = dp[i-1][j-1]           # no operation needed
            else:
                dp[i][j] = 1 + min(
                    dp[i-1][j],     # delete from s1
                    dp[i][j-1],     # insert into s1
                    dp[i-1][j-1]    # replace
                )

    return dp[m][n]

print(edit_distance("horse", "ros"))    # 3
print(edit_distance("intention", "execution"))  # 5
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 111. Climbing stairs problem

```python
# Can climb 1 or 2 steps — how many ways to reach step n?
# This is Fibonacci! dp[n] = dp[n-1] + dp[n-2]
def climb_stairs(n):
    if n <= 2: return n
    a, b = 1, 2
    for _ in range(3, n + 1):
        a, b = b, a + b
    return b

# Generalized: can climb 1..k steps
def climb_stairs_k(n, k):
    dp = [0] * (n + 1)
    dp[0] = 1
    for i in range(1, n + 1):
        for j in range(1, min(k, i) + 1):
            dp[i] += dp[i - j]
    return dp[n]

print(climb_stairs(5))        # 8
print(climb_stairs_k(5, 3))   # 13
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 112. House Robber problem

```python
# Can't rob two adjacent houses — maximize total
def rob(nums):
    if not nums: return 0
    if len(nums) == 1: return nums[0]
    prev2, prev1 = 0, 0
    for num in nums:
        curr = max(prev1, prev2 + num)
        prev2, prev1 = prev1, curr
    return prev1

# House Robber II — houses arranged in a circle
def rob_circular(nums):
    if len(nums) == 1: return nums[0]
    return max(rob(nums[:-1]), rob(nums[1:]))  # exclude first or last

print(rob([2,7,9,3,1]))           # 12 (2+9+1)
print(rob_circular([2,3,2]))      # 3
print(rob_circular([1,2,3,1]))    # 4
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 113. Matrix chain multiplication

```python
# Find optimal parenthesization to minimize scalar multiplications
def matrix_chain(dims):
    n = len(dims) - 1   # n matrices
    dp = [[0]*n for _ in range(n)]

    # chain_len = length of chain being considered
    for chain_len in range(2, n + 1):
        for i in range(n - chain_len + 1):
            j = i + chain_len - 1
            dp[i][j] = float('inf')
            for k in range(i, j):
                cost = dp[i][k] + dp[k+1][j] + dims[i]*dims[k+1]*dims[j+1]
                dp[i][j] = min(dp[i][j], cost)

    return dp[0][n-1]

# Matrices: A(30x35), B(35x15), C(15x5), D(5x10)
dims = [30, 35, 15, 5, 10]
print(matrix_chain(dims))  # 15750
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 114. Subset sum problem

```python
# Can any subset sum to target? — O(n * target) time
def subset_sum(nums, target):
    dp = {0}   # set of achievable sums
    for num in nums:
        dp = dp | {s + num for s in dp}
    return target in dp

# DP table approach
def subset_sum_dp(nums, target):
    dp = [False] * (target + 1)
    dp[0] = True
    for num in nums:
        for s in range(target, num - 1, -1):  # right to left to avoid reuse
            if dp[s - num]: dp[s] = True
    return dp[target]

print(subset_sum([3, 34, 4, 12, 5, 2], 9))    # True (4+3+2)
print(subset_sum_dp([3, 34, 4, 12, 5, 2], 9)) # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 115. Partition equal subset sum

```python
# Can array be partitioned into two equal sum subsets?
def can_partition(nums):
    total = sum(nums)
    if total % 2 != 0: return False  # odd total → impossible
    target = total // 2
    dp = {0}
    for num in nums:
        dp = dp | {s + num for s in dp if s + num <= target}
        if target in dp: return True
    return target in dp

print(can_partition([1,5,11,5]))  # True (1+5+5 = 11)
print(can_partition([1,2,3,5]))   # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Backtracking

<br>

### 116. What is Backtracking? How does it differ from recursion?

**Answer:**

Backtracking is an **algorithmic technique that explores all possible solutions** by building candidates incrementally and **abandoning (backtracking) a candidate** as soon as it determines it cannot lead to a valid solution.

```
Backtracking template:
def backtrack(state, choices):
    if is_solution(state):
        record(state)
        return
    for choice in choices:
        if is_valid(choice, state):
            make_choice(state, choice)
            backtrack(state, next_choices)   # explore
            undo_choice(state, choice)       # BACKTRACK ← key step
```

| Feature | Recursion | Backtracking |
| ------- | --------- | ------------ |
| Goal | Solve by reducing to subproblem | Explore all possible solutions |
| Pruning | No | Yes — cuts invalid branches early |
| State management | No undo | Undo choices after exploring |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 117. Generate all subsets of a set (Power Set)

```python
# Backtracking — O(2^n * n) time
def subsets(nums):
    result = []
    def backtrack(start, current):
        result.append(list(current))   # every path is a valid subset
        for i in range(start, len(nums)):
            current.append(nums[i])
            backtrack(i + 1, current)
            current.pop()              # backtrack
    backtrack(0, [])
    return result

# Bit manipulation — elegant for small n
def subsets_bits(nums):
    n = len(nums)
    return [[nums[j] for j in range(n) if i & (1 << j)] for i in range(1 << n)]

print(subsets([1,2,3]))  # [[], [1], [1,2], [1,2,3], [1,3], [2], [2,3], [3]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 118. Generate all permutations of an array

```python
# Backtracking — O(n! * n) time
def permutations(nums):
    result = []
    def backtrack(current, remaining):
        if not remaining:
            result.append(list(current))
            return
        for i in range(len(remaining)):
            current.append(remaining[i])
            backtrack(current, remaining[:i] + remaining[i+1:])
            current.pop()
    backtrack([], nums)
    return result

# Swap-based (in-place) — O(n!) time, O(n) space
def permutations_swap(nums):
    result = []
    def backtrack(start):
        if start == len(nums):
            result.append(list(nums))
            return
        for i in range(start, len(nums)):
            nums[start], nums[i] = nums[i], nums[start]   # choose
            backtrack(start + 1)
            nums[start], nums[i] = nums[i], nums[start]   # unchoose
    backtrack(0)
    return result

print(permutations([1,2,3]))
# [[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 119. N-Queens problem

```python
def solve_n_queens(n):
    result = []
    queens = []   # queens[i] = column of queen in row i

    def is_safe(row, col):
        for r, c in enumerate(queens):
            if c == col: return False                    # same column
            if abs(r - row) == abs(c - col): return False  # same diagonal
        return True

    def backtrack(row):
        if row == n:
            # Build board representation
            board = []
            for r in range(n):
                board.append('.' * queens[r] + 'Q' + '.' * (n - queens[r] - 1))
            result.append(board)
            return
        for col in range(n):
            if is_safe(row, col):
                queens.append(col)
                backtrack(row + 1)
                queens.pop()       # backtrack

    backtrack(0)
    return result

solutions = solve_n_queens(4)
print(f"Solutions for 4-Queens: {len(solutions)}")  # 2
for board in solutions:
    for row in board: print(row)
    print()
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 120. Sudoku solver

```python
def solve_sudoku(board):
    def is_valid(board, row, col, num):
        # Check row
        if num in board[row]: return False
        # Check column
        if num in [board[r][col] for r in range(9)]: return False
        # Check 3x3 box
        box_r, box_c = 3 * (row // 3), 3 * (col // 3)
        for r in range(box_r, box_r + 3):
            for c in range(box_c, box_c + 3):
                if board[r][c] == num: return False
        return True

    def backtrack():
        for r in range(9):
            for c in range(9):
                if board[r][c] == '.':
                    for num in '123456789':
                        if is_valid(board, r, c, num):
                            board[r][c] = num
                            if backtrack(): return True
                            board[r][c] = '.'   # backtrack
                    return False  # no valid number — backtrack
        return True  # all cells filled

    backtrack()
    return board
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 121. Word search in a 2D grid

```python
def word_search(board, word):
    rows, cols = len(board), len(board[0])

    def dfs(r, c, idx):
        if idx == len(word): return True
        if r < 0 or r >= rows or c < 0 or c >= cols: return False
        if board[r][c] != word[idx]: return False

        temp = board[r][c]
        board[r][c] = '#'   # mark visited

        found = (dfs(r+1,c,idx+1) or dfs(r-1,c,idx+1) or
                 dfs(r,c+1,idx+1) or dfs(r,c-1,idx+1))

        board[r][c] = temp  # restore (backtrack)
        return found

    for r in range(rows):
        for c in range(cols):
            if dfs(r, c, 0): return True
    return False

board = [["A","B","C","E"],["S","F","C","S"],["A","D","E","E"]]
print(word_search(board, "ABCCED"))  # True
print(word_search(board, "SEE"))     # True
print(word_search(board, "ABCB"))    # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 122. Combination sum — find all combinations that sum to target

```python
# All combinations using unlimited use of each element
def combination_sum(candidates, target):
    result = []
    candidates.sort()

    def backtrack(start, current, remaining):
        if remaining == 0:
            result.append(list(current))
            return
        for i in range(start, len(candidates)):
            if candidates[i] > remaining: break  # pruning
            current.append(candidates[i])
            backtrack(i, current, remaining - candidates[i])  # i (not i+1) allows reuse
            current.pop()

    backtrack(0, [], target)
    return result

print(combination_sum([2,3,6,7], 7))  # [[2,2,3],[7]]
print(combination_sum([2,3,5], 8))    # [[2,2,2,2],[2,3,3],[3,5]]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Advanced Data Structures

<br>

### 123. What is a Trie? Implement insert and search.

```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

class Trie:
    def __init__(self):
        self.root = TrieNode()

    def insert(self, word):          # O(m) where m = word length
        node = self.root
        for char in word:
            if char not in node.children:
                node.children[char] = TrieNode()
            node = node.children[char]
        node.is_end = True

    def search(self, word):          # O(m)
        node = self.root
        for char in word:
            if char not in node.children: return False
            node = node.children[char]
        return node.is_end

    def starts_with(self, prefix):   # O(m) — autocomplete check
        node = self.root
        for char in prefix:
            if char not in node.children: return False
            node = node.children[char]
        return True

trie = Trie()
for word in ["apple", "app", "apt", "application"]:
    trie.insert(word)
print(trie.search("app"))         # True
print(trie.search("ap"))          # False (not a complete word)
print(trie.starts_with("appl"))   # True
```

**Space:** O(alphabet_size × key_length × n) | **Search/Insert:** O(m)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 124. Implement LRU Cache

```python
from collections import OrderedDict

class LRUCache:
    def __init__(self, capacity):
        self.capacity = capacity
        self.cache = OrderedDict()   # insertion-ordered dict

    def get(self, key):              # O(1)
        if key not in self.cache: return -1
        self.cache.move_to_end(key)  # mark as recently used
        return self.cache[key]

    def put(self, key, value):       # O(1)
        if key in self.cache:
            self.cache.move_to_end(key)
        self.cache[key] = value
        if len(self.cache) > self.capacity:
            self.cache.popitem(last=False)   # remove LRU (front of OrderedDict)

# Test
cache = LRUCache(2)
cache.put(1, 1)
cache.put(2, 2)
print(cache.get(1))   # 1 — makes 1 recently used
cache.put(3, 3)       # evicts key 2 (LRU)
print(cache.get(2))   # -1 (evicted)
cache.put(4, 4)       # evicts key 1
print(cache.get(1))   # -1 (evicted)
print(cache.get(3))   # 3
print(cache.get(4))   # 4
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 125. What is a Segment Tree? Build and query.

```python
# Range Sum Query — O(n) build, O(log n) query and update
class SegmentTree:
    def __init__(self, arr):
        self.n = len(arr)
        self.tree = [0] * (4 * self.n)
        self._build(arr, 0, 0, self.n - 1)

    def _build(self, arr, node, start, end):
        if start == end:
            self.tree[node] = arr[start]
        else:
            mid = (start + end) // 2
            self._build(arr, 2*node+1, start, mid)
            self._build(arr, 2*node+2, mid+1, end)
            self.tree[node] = self.tree[2*node+1] + self.tree[2*node+2]

    def query(self, l, r, node=0, start=0, end=None):   # Range sum query
        if end is None: end = self.n - 1
        if r < start or end < l: return 0                # out of range
        if l <= start and end <= r: return self.tree[node]  # fully in range
        mid = (start + end) // 2
        return (self.query(l, r, 2*node+1, start, mid) +
                self.query(l, r, 2*node+2, mid+1, end))

    def update(self, idx, val, node=0, start=0, end=None):
        if end is None: end = self.n - 1
        if start == end:
            self.tree[node] = val; return
        mid = (start + end) // 2
        if idx <= mid: self.update(idx, val, 2*node+1, start, mid)
        else:          self.update(idx, val, 2*node+2, mid+1, end)
        self.tree[node] = self.tree[2*node+1] + self.tree[2*node+2]

arr = [1, 3, 5, 7, 9, 11]
st = SegmentTree(arr)
print(st.query(1, 3))   # 15 (3+5+7)
st.update(1, 10)
print(st.query(1, 3))   # 22 (10+5+7)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 126. What is a Fenwick Tree (Binary Indexed Tree)?

```python
# Point update, prefix sum query — O(log n) both ops, O(n) space
class FenwickTree:
    def __init__(self, n):
        self.n = n
        self.tree = [0] * (n + 1)   # 1-indexed

    def update(self, i, delta):    # O(log n) — add delta at index i
        while i <= self.n:
            self.tree[i] += delta
            i += i & (-i)          # move to next responsible position

    def prefix_sum(self, i):       # O(log n) — sum from 1 to i
        total = 0
        while i > 0:
            total += self.tree[i]
            i -= i & (-i)          # move to parent
        return total

    def range_sum(self, l, r):     # O(log n)
        return self.prefix_sum(r) - self.prefix_sum(l - 1)

arr = [3, 2, -1, 6, 5, 4, -3, 3, 7, 2]
ft = FenwickTree(len(arr))
for i, val in enumerate(arr, 1):
    ft.update(i, val)
print(ft.prefix_sum(5))     # 15 (3+2-1+6+5)
print(ft.range_sum(3, 7))   # 11 (-1+6+5+4-3)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 127. What is Disjoint Set (Union-Find)?

```python
class UnionFind:
    def __init__(self, n):
        self.parent = list(range(n))
        self.rank = [0] * n
        self.components = n

    def find(self, x):              # O(α(n)) amortized — nearly O(1)
        if self.parent[x] != x:
            self.parent[x] = self.find(self.parent[x])  # path compression
        return self.parent[x]

    def union(self, x, y):          # O(α(n)) amortized
        px, py = self.find(x), self.find(y)
        if px == py: return False   # already connected
        if self.rank[px] < self.rank[py]: px, py = py, px
        self.parent[py] = px
        if self.rank[px] == self.rank[py]: self.rank[px] += 1
        self.components -= 1
        return True

    def connected(self, x, y):
        return self.find(x) == self.find(y)

uf = UnionFind(5)
uf.union(0,1); uf.union(1,2); uf.union(3,4)
print(uf.connected(0, 2))   # True
print(uf.connected(0, 3))   # False
print(uf.components)        # 2 (group{0,1,2} and group{3,4})
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 128. What is a Skip List?

**Answer:**

A Skip List is a probabilistic data structure that allows **O(log n) average** search, insert, and delete — maintaining multiple layers of linked lists where each higher layer skips more elements.

```python
import random

class SkipNode:
    def __init__(self, val, level):
        self.val = val
        self.forward = [None] * (level + 1)

class SkipList:
    MAX_LEVEL = 16
    P = 0.5

    def __init__(self):
        self.header = SkipNode(float('-inf'), self.MAX_LEVEL)
        self.level = 0

    def _random_level(self):
        lvl = 0
        while random.random() < self.P and lvl < self.MAX_LEVEL:
            lvl += 1
        return lvl

    def search(self, val):              # O(log n) average
        curr = self.header
        for i in range(self.level, -1, -1):
            while curr.forward[i] and curr.forward[i].val < val:
                curr = curr.forward[i]
        curr = curr.forward[0]
        return curr and curr.val == val

    def insert(self, val):              # O(log n) average
        update = [None] * (self.MAX_LEVEL + 1)
        curr = self.header
        for i in range(self.level, -1, -1):
            while curr.forward[i] and curr.forward[i].val < val:
                curr = curr.forward[i]
            update[i] = curr
        lvl = self._random_level()
        if lvl > self.level:
            for i in range(self.level + 1, lvl + 1):
                update[i] = self.header
            self.level = lvl
        new_node = SkipNode(val, lvl)
        for i in range(lvl + 1):
            new_node.forward[i] = update[i].forward[i]
            update[i].forward[i] = new_node

sl = SkipList()
for v in [3,6,7,9,12]: sl.insert(v)
print(sl.search(6))   # True
print(sl.search(5))   # False
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Greedy Algorithms

<br>

### 129. What is a Greedy Algorithm? When does it work?

**Answer:**

A greedy algorithm makes the **locally optimal choice at each step**, hoping it leads to a globally optimal solution.

**Works when:**
1. **Greedy choice property** — local optimal choice leads to global optimum
2. **Optimal substructure** — optimal solution contains optimal solutions to subproblems

**Fails when:** A locally good choice leads to a globally bad outcome (use DP instead).

| Problem | Greedy Works? |
| ------- | ------------- |
| Activity selection | ✅ Yes |
| Fractional knapsack | ✅ Yes |
| 0/1 knapsack | ❌ No — use DP |
| Shortest path (positive weights) | ✅ Dijkstra |
| Minimum spanning tree | ✅ Prim/Kruskal |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 130. Activity selection problem

```python
# Select maximum number of non-overlapping activities
def activity_selection(activities):
    # Sort by end time
    activities.sort(key=lambda x: x[1])
    selected = [activities[0]]

    for start, end in activities[1:]:
        if start >= selected[-1][1]:   # starts after last selected ends
            selected.append((start, end))

    return selected

# Test
activities = [(1,4), (3,5), (0,6), (5,7), (3,9), (5,9), (6,10), (8,11), (8,12), (2,14)]
result = activity_selection(activities)
print(result)           # [(1,4),(5,7),(8,11)] or similar
print(len(result))      # 4 — maximum number of activities
```

**Time:** O(n log n) — dominated by sorting | **Space:** O(1)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 131. Fractional Knapsack problem

```python
def fractional_knapsack(weights, values, capacity):
    # Calculate value/weight ratio, sort descending
    items = sorted(zip(values, weights), key=lambda x: x[0]/x[1], reverse=True)
    total_value = 0.0

    for value, weight in items:
        if capacity >= weight:
            total_value += value        # take entire item
            capacity -= weight
        else:
            total_value += value * (capacity / weight)  # take fraction
            break   # knapsack full

    return total_value

weights = [10, 20, 30]
values  = [60, 100, 120]
capacity = 50
print(fractional_knapsack(weights, values, capacity))  # 240.0
```

**Time:** O(n log n) | **Space:** O(n)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 132. Huffman encoding

```python
import heapq

class HuffmanNode:
    def __init__(self, char, freq):
        self.char = char; self.freq = freq
        self.left = self.right = None
    def __lt__(self, other): return self.freq < other.freq

def huffman_encoding(text):
    freq = {}
    for c in text: freq[c] = freq.get(c, 0) + 1

    heap = [HuffmanNode(c, f) for c, f in freq.items()]
    heapq.heapify(heap)

    while len(heap) > 1:
        left = heapq.heappop(heap)
        right = heapq.heappop(heap)
        merged = HuffmanNode(None, left.freq + right.freq)
        merged.left = left; merged.right = right
        heapq.heappush(heap, merged)

    codes = {}
    def build_codes(node, code):
        if node.char: codes[node.char] = code; return
        build_codes(node.left, code + '0')
        build_codes(node.right, code + '1')

    build_codes(heap[0], '')
    return codes

codes = huffman_encoding("aababcabcd")
for char, code in sorted(codes.items()): print(f"'{char}': {code}")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 133. Jump Game — can you reach the end?

```python
# Greedy — O(n) time, O(1) space
def can_jump(nums):
    max_reach = 0
    for i, jump in enumerate(nums):
        if i > max_reach: return False      # can't reach position i
        max_reach = max(max_reach, i + jump)
    return True

# Jump Game II — minimum number of jumps to reach end
def jump_min(nums):
    jumps = 0
    current_end = 0
    farthest = 0
    for i in range(len(nums) - 1):
        farthest = max(farthest, i + nums[i])
        if i == current_end:        # must make a jump here
            jumps += 1
            current_end = farthest
    return jumps

print(can_jump([2,3,1,1,4]))    # True
print(can_jump([3,2,1,0,4]))    # False
print(jump_min([2,3,1,1,4]))    # 2
print(jump_min([2,3,0,1,4]))    # 2
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 134. What is the difference between Stack and Queue?

| Feature | Stack | Queue |
| ------- | ----- | ----- |
| Principle | LIFO — Last In, First Out | FIFO — First In, First Out |
| Insert | Push (top) | Enqueue (rear) |
| Remove | Pop (top) | Dequeue (front) |
| Peek | Top element | Front element |
| Use case | DFS, undo/redo, call stack, expressions | BFS, task scheduling, print queue |
| Python impl | `list` or `collections.deque` | `collections.deque` |

```python
from collections import deque
stack = []; stack.append(1); stack.pop()   # LIFO
queue = deque(); queue.append(1); queue.popleft()  # FIFO
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 135. When would you use a HashMap over an array?

```python
# Use HashMap (dict) when:
# 1. Key-value relationship is needed
# 2. Fast lookup by non-integer key
# 3. Sparse data (keys not consecutive)

# Frequency count — HashMap is natural
text = "interview"
freq = {}
for c in text: freq[c] = freq.get(c, 0) + 1
print(freq)  # {'i':2,'n':1,'t':1,'e':2,'r':2,'v':1,'w':1}

# Use array when:
# 1. Keys are integers in a small range (0 to n)
# 2. Need random access by index
# 3. Memory efficiency matters (array < dict overhead)

# Counting sort uses array — keys are 0..255 (ASCII) or 0..n
count = [0] * 256
for c in text: count[ord(c)] += 1
```

| Criteria | Array | HashMap |
| -------- | ----- | ------- |
| Access | O(1) by index | O(1) average by key |
| Memory | Less (no hash overhead) | More |
| Key type | Integers only | Any hashable type |
| Ordering | Ordered by index | Insertion-ordered (Python 3.7+) |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 136. What is the difference between DFS and BFS? When to use which?

| Feature | DFS | BFS |
| ------- | --- | --- |
| Data structure | Stack (recursion or explicit) | Queue |
| Space complexity | O(h) — height | O(w) — width |
| Shortest path | ❌ Not guaranteed | ✅ Yes (unweighted) |
| Memory (sparse deep) | Better | Worse |
| Memory (dense wide) | Worse | Better |
| Use case | Cycle detection, topological sort, backtracking, path finding | Shortest path, level order, connected components |

```python
# BFS for shortest path in grid
# DFS for detecting cycles, exploring all paths, backtracking
from collections import deque

def bfs_shortest(grid, start, end):
    # Use BFS — guarantees shortest path in unweighted grid
    queue = deque([(start, 0)])
    visited = {start}
    while queue:
        (r, c), dist = queue.popleft()
        if (r,c) == end: return dist
        for dr,dc in [(0,1),(0,-1),(1,0),(-1,0)]:
            nr, nc = r+dr, c+dc
            if 0<=nr<len(grid) and 0<=nc<len(grid[0]) and (nr,nc) not in visited and grid[nr][nc]!='#':
                visited.add((nr,nc))
                queue.append(((nr,nc), dist+1))
    return -1
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 137. What is the difference between Greedy and Dynamic Programming?

| Feature | Greedy | Dynamic Programming |
| ------- | ------ | ------------------- |
| Approach | Make locally optimal choice | Solve all subproblems, use results |
| Subproblems | Only one considered at each step | All overlapping subproblems |
| Backtracking | Never revisits choices | Considers all options |
| Correctness | Not always globally optimal | Always globally optimal |
| Efficiency | Usually O(n log n) or O(n) | Usually O(n²) or higher |
| Example | Activity selection, Huffman | Knapsack, LCS, Edit Distance |

```python
# Coin Change: [1, 6, 10], amount = 12
# Greedy: 10+1+1 = 3 coins (WRONG for this set)
# DP:     6+6    = 2 coins (CORRECT)

# Greedy works when a coin system is "canonical"
# (like standard denominations: 1, 5, 10, 25)
# DP always finds optimal solution
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 138. How do you find if a number is a power of 2?

```python
# Bit manipulation trick — O(1)
def is_power_of_two(n):
    return n > 0 and (n & (n - 1)) == 0
# n = 8   → 1000 & 0111 = 0000 → True
# n = 6   → 0110 & 0101 = 0100 → False (not 0)
# n = 0   → False (handled by n > 0)

# Loop approach — O(log n)
def is_power_of_two_loop(n):
    if n <= 0: return False
    while n % 2 == 0: n //= 2
    return n == 1

# Python built-in
import math
def is_power_of_two_builtin(n):
    return n > 0 and math.log2(n).is_integer()

for n in [1, 2, 4, 8, 16, 6, 0, -4]:
    print(f"{n}: {is_power_of_two(n)}")
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 139. Find the single non-duplicate in an array (XOR trick)

```python
# Every number appears twice except one — find the singleton
# XOR: a^a=0, a^0=a, order doesn't matter

def single_number(nums):    # O(n) time, O(1) space
    result = 0
    for num in nums:
        result ^= num        # pairs cancel out, singleton remains
    return result

# Find two non-duplicates using XOR
def single_number_two(nums):
    xor = 0
    for num in nums: xor ^= num    # xor of both singles
    # Find rightmost set bit (differentiates the two singles)
    diff_bit = xor & (-xor)
    a = 0
    for num in nums:
        if num & diff_bit: a ^= num  # only one single has this bit
    return a, xor ^ a

print(single_number([4,1,2,1,2]))         # 4
print(single_number([2,2,1]))             # 1
print(single_number_two([1,2,1,3,2,5]))  # (3, 5) or (5, 3)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 140. Find median of two sorted arrays

```python
# Binary search — O(log(min(m,n))) time
def find_median_sorted_arrays(nums1, nums2):
    # Ensure nums1 is the smaller array
    if len(nums1) > len(nums2):
        nums1, nums2 = nums2, nums1

    m, n = len(nums1), len(nums2)
    lo, hi = 0, m

    while lo <= hi:
        i = (lo + hi) // 2           # partition in nums1
        j = (m + n + 1) // 2 - i    # partition in nums2

        max_left1  = nums1[i-1] if i > 0 else float('-inf')
        min_right1 = nums1[i]   if i < m else float('inf')
        max_left2  = nums2[j-1] if j > 0 else float('-inf')
        min_right2 = nums2[j]   if j < n else float('inf')

        if max_left1 <= min_right2 and max_left2 <= min_right1:
            if (m + n) % 2 == 1:
                return float(max(max_left1, max_left2))
            return (max(max_left1, max_left2) + min(min_right1, min_right2)) / 2.0
        elif max_left1 > min_right2:
            hi = i - 1
        else:
            lo = i + 1

print(find_median_sorted_arrays([1,3], [2]))     # 2.0
print(find_median_sorted_arrays([1,2], [3,4]))   # 2.5
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 141. Merge overlapping intervals

```python
def merge_intervals(intervals):
    if not intervals: return []
    intervals.sort(key=lambda x: x[0])  # sort by start time
    merged = [intervals[0]]

    for start, end in intervals[1:]:
        if start <= merged[-1][1]:           # overlapping
            merged[-1][1] = max(merged[-1][1], end)  # extend
        else:
            merged.append([start, end])      # non-overlapping — add new

    return merged

print(merge_intervals([[1,3],[2,6],[8,10],[15,18]]))  # [[1,6],[8,10],[15,18]]
print(merge_intervals([[1,4],[4,5]]))                  # [[1,5]]
```

**Time:** O(n log n) | **Space:** O(n)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 142. Product of array except self (no division)

```python
# Prefix and suffix product — O(n) time, O(1) extra space
def product_except_self(nums):
    n = len(nums)
    result = [1] * n

    # Left pass: result[i] = product of all nums to the left of i
    prefix = 1
    for i in range(n):
        result[i] = prefix
        prefix *= nums[i]

    # Right pass: multiply result[i] by product of all nums to the right of i
    suffix = 1
    for i in range(n - 1, -1, -1):
        result[i] *= suffix
        suffix *= nums[i]

    return result

print(product_except_self([1,2,3,4]))   # [24,12,8,6]
print(product_except_self([-1,1,0,-3,3]))  # [0,0,9,0,0]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 143. Spiral order traversal of a matrix

```python
def spiral_order(matrix):
    if not matrix: return []
    result = []
    top, bottom = 0, len(matrix) - 1
    left, right = 0, len(matrix[0]) - 1

    while top <= bottom and left <= right:
        # Move right across top row
        for col in range(left, right + 1): result.append(matrix[top][col])
        top += 1
        # Move down right column
        for row in range(top, bottom + 1): result.append(matrix[row][right])
        right -= 1
        # Move left across bottom row (if still valid)
        if top <= bottom:
            for col in range(right, left - 1, -1): result.append(matrix[bottom][col])
            bottom -= 1
        # Move up left column (if still valid)
        if left <= right:
            for row in range(bottom, top - 1, -1): result.append(matrix[row][left])
            left += 1

    return result

matrix = [[1,2,3],[4,5,6],[7,8,9]]
print(spiral_order(matrix))  # [1,2,3,6,9,8,7,4,5]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 144. Rotate a matrix 90 degrees clockwise

```python
def rotate_matrix(matrix):
    n = len(matrix)
    # Step 1: Transpose (swap matrix[i][j] and matrix[j][i])
    for i in range(n):
        for j in range(i + 1, n):
            matrix[i][j], matrix[j][i] = matrix[j][i], matrix[i][j]
    # Step 2: Reverse each row
    for row in matrix:
        row.reverse()
    return matrix

matrix = [[1,2,3],[4,5,6],[7,8,9]]
print(rotate_matrix(matrix))
# [[7,4,1],[8,5,2],[9,6,3]]
```

**Time:** O(n²) | **Space:** O(1) — in-place

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 145. Search in a 2D sorted matrix

```python
# Matrix where each row is sorted and first element of each row > last of previous row
# Binary search treating it as a flat sorted array — O(log(m*n))
def search_matrix(matrix, target):
    m, n = len(matrix), len(matrix[0])
    lo, hi = 0, m * n - 1
    while lo <= hi:
        mid = (lo + hi) // 2
        val = matrix[mid // n][mid % n]    # convert 1D index to 2D
        if val == target: return True
        elif val < target: lo = mid + 1
        else: hi = mid - 1
    return False

# Matrix where rows and columns are both sorted (independent)
# Start from top-right corner — O(m+n)
def search_matrix_ii(matrix, target):
    row, col = 0, len(matrix[0]) - 1
    while row < len(matrix) and col >= 0:
        if matrix[row][col] == target: return True
        elif matrix[row][col] > target: col -= 1
        else: row += 1
    return False

print(search_matrix([[1,3,5,7],[10,11,16,20],[23,30,34,60]], 3))  # True
print(search_matrix_ii([[1,4,7,11],[2,5,8,12],[3,6,9,16]], 5))    # True
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 146. Word ladder (shortest transformation)

```python
from collections import deque

def word_ladder(begin_word, end_word, word_list):
    word_set = set(word_list)
    if end_word not in word_set: return 0

    queue = deque([(begin_word, 1)])
    visited = {begin_word}

    while queue:
        word, length = queue.popleft()
        for i in range(len(word)):
            for c in 'abcdefghijklmnopqrstuvwxyz':
                new_word = word[:i] + c + word[i+1:]
                if new_word == end_word: return length + 1
                if new_word in word_set and new_word not in visited:
                    visited.add(new_word)
                    queue.append((new_word, length + 1))

    return 0  # no transformation found

print(word_ladder("hit","cog",["hot","dot","dog","lot","log","cog"]))  # 5
print(word_ladder("hit","cog",["hot","dot","dog","lot","log"]))        # 0
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 147. Clone a graph

```python
class GraphNode:
    def __init__(self, val=0, neighbors=None):
        self.val = val
        self.neighbors = neighbors if neighbors else []

def clone_graph(node):
    if not node: return None
    cloned = {}   # original node → cloned node

    def dfs(n):
        if n in cloned: return cloned[n]
        clone = GraphNode(n.val)
        cloned[n] = clone
        for neighbor in n.neighbors:
            clone.neighbors.append(dfs(neighbor))
        return clone

    return dfs(node)
```

**Time:** O(V + E) | **Space:** O(V)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 148. Serialize and deserialize a binary tree

```python
from collections import deque

def serialize(root):
    if not root: return "null"
    result = []
    queue = deque([root])
    while queue:
        node = queue.popleft()
        if node:
            result.append(str(node.val))
            queue.append(node.left)
            queue.append(node.right)
        else:
            result.append("null")
    return ','.join(result)

def deserialize(data):
    if data == "null": return None
    vals = data.split(',')
    root = TreeNode(int(vals[0]))
    queue = deque([root])
    i = 1
    while queue and i < len(vals):
        node = queue.popleft()
        if vals[i] != "null":
            node.left = TreeNode(int(vals[i]))
            queue.append(node.left)
        i += 1
        if i < len(vals) and vals[i] != "null":
            node.right = TreeNode(int(vals[i]))
            queue.append(node.right)
        i += 1
    return root

root = TreeNode(1, TreeNode(2), TreeNode(3, TreeNode(4), TreeNode(5)))
s = serialize(root)
print(s)                                  # "1,2,3,null,null,4,5"
print(inorder(deserialize(s)))            # [2,1,4,3,5]
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 149. Design a stack using a linked list

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class LinkedListStack:
    def __init__(self):
        self.top = None
        self._size = 0

    def push(self, data):      # O(1) — insert at head
        node = Node(data)
        node.next = self.top
        self.top = node
        self._size += 1

    def pop(self):             # O(1) — remove from head
        if self.is_empty(): raise IndexError("Stack underflow")
        data = self.top.data
        self.top = self.top.next
        self._size -= 1
        return data

    def peek(self):            # O(1)
        if self.is_empty(): raise IndexError("Empty stack")
        return self.top.data

    def is_empty(self): return self.top is None
    def size(self): return self._size

stack = LinkedListStack()
stack.push(10); stack.push(20); stack.push(30)
print(stack.peek())  # 30
print(stack.pop())   # 30
print(stack.size())  # 2
```

**Advantage over array stack:** No capacity limit — grows dynamically

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 150. What are the top patterns to master for DSA interviews?

**Answer:**

Mastering patterns is more valuable than solving 500 random problems. Most interview questions are variations of these 15 core patterns:

| # | Pattern | Key Problems |
| - | ------- | ------------ |
| 1 | **Sliding Window** | Longest substring without repeating, Min window substring |
| 2 | **Two Pointers** | Two Sum (sorted), 3Sum, Trapping rain water, Container with water |
| 3 | **Fast & Slow Pointers** | Cycle detection, Middle of linked list, Find cycle start |
| 4 | **Binary Search** | Classic search, Rotated array, First/Last position |
| 5 | **Prefix Sum** | Subarray sum equals K, Zero sum subarray |
| 6 | **Hash Map/Set** | Two Sum, Anagrams, Frequency counting, LRU Cache |
| 7 | **Stack (Monotonic)** | Next greater element, Largest rectangle histogram, Trapping water |
| 8 | **BFS (Level order)** | Shortest path, Level order traversal, Word ladder, Islands |
| 9 | **DFS + Backtracking** | Subsets, Permutations, N-Queens, Sudoku, Word search |
| 10 | **Tree DP** | Diameter, Max path sum, Balanced check |
| 11 | **Dynamic Programming** | Knapsack, LCS, LIS, Coin Change, Edit Distance |
| 12 | **Greedy** | Activity selection, Jump game, Interval scheduling |
| 13 | **Union Find** | Connected components, Detect cycle, Kruskal's MST |
| 14 | **Heap/Priority Queue** | Kth largest, Merge K sorted, Top K frequent |
| 15 | **Graph algorithms** | Dijkstra, Topological sort, Cycle detection |

```python
# Study order recommendation:
# Week 1-2: Arrays, Strings, Hash Maps, Two Pointers
# Week 3-4: Linked Lists, Stacks, Queues, Binary Search
# Week 5-6: Trees, BST, BFS/DFS
# Week 7-8: Dynamic Programming, Backtracking
# Week 9-10: Graphs, Heaps, Advanced (Trie, Segment Tree)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

<div align="center">

## 🎉 You've covered all 150 DSA Interview Questions in Python!

---

**If this repo helped you crack your interview, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/dsa-interview-questions?style=social)](https://github.com/sisi-tarak/dsa-interview-questions)

---

### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a bug, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/dsa-interview-questions/pulls)** — all contributions are welcome! 🙌

---

### 📦 Complete Interview Prep Hub

| Status | Repository |
| ------ | ---------- |
| ✅ Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
| ✅ Live | [mern-interview-questions](https://github.com/sisi-tarak/mern-interview-questions) |
| ✅ Live | [dsa-interview-questions](https://github.com/sisi-tarak/dsa-interview-questions) |
| 🔜 Coming | nodejs-interview-questions |
| 🔜 Coming | java-interview-questions |
| 🔜 Coming | python-interview-questions |

⭐ **Star all repos to get notified when new ones drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, Amazon, Google, Microsoft, Flipkart, and other top product companies. Practice these patterns consistently — understanding the approach matters more than memorizing solutions.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
