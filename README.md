# Time_Complexity_All-
Table for time complexities for all Data Structures and algorithms from Big-O-Sheet

## General Understanding of All Time Complexities
| Complexity   | Name                  | Category    | Description                                                         |
| ------------ | --------------------- | ----------- | ------------------------------------------------------------------- |
| O(1)         | Constant Time         | ✅ Best      | Operation takes same amount of time regardless of input size.       |
| O(log n)     | Logarithmic Time      | ✅ Very Good | Time grows slowly as input size increases. Common in binary search. |
| O(n)         | Linear Time           | 👍 Good     | Time grows proportionally to input size.                            |
| O(n log n)   | Linearithmic Time     | ⚖️ Moderate | Common in efficient sorting algorithms like mergesort, heapsort.    |
| O(n²)        | Quadratic Time        | ❌ Bad       | Time increases with the square of input size (nested loops).        |
| O(2ⁿ), O(n!) | Exponential/Factorial | ❌ Worst     | Extremely inefficient; grows too fast.                              |


---

## 📌 PART 1: GitHub README Markdown Tables

### ✅ 1. Common Data Structure Operations


| Data Structure        | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity (Worst) |
|-----------------------|---------------------------|---------------------------|---------------------------|
|                       | Access | Search | Insertion | Deletion | Access | Search | Insertion | Deletion |       |
| Array                 | Θ(1)   | Θ(n)   | Θ(n)      | Θ(n)     | O(1)   | O(n)   | O(n)      | O(n)     | O(n)  |
| Stack                 | Θ(n)   | Θ(n)   | Θ(1)      | Θ(1)     | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |
| Queue                 | Θ(n)   | Θ(n)   | Θ(1)      | Θ(1)     | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |
| Singly Linked List    | Θ(n)   | Θ(n)   | Θ(1)      | Θ(1)     | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |
| Doubly Linked List    | Θ(n)   | Θ(n)   | Θ(1)      | Θ(1)     | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |
| Skip List             | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(n)   | O(n)   | O(n)      | O(n)     | O(n log n) |
| Hash Table            | N/A    | Θ(1)   | Θ(1)      | Θ(1)     | N/A    | O(n)   | O(n)      | O(n)     | O(n)  |
| Binary Search Tree    | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(n)   | O(n)   | O(n)      | O(n)     | O(n)  |
| Cartesian Tree        | N/A    | Θ(log n) | Θ(log n) | Θ(log n) | N/A    | O(n)   | O(n)      | O(n)     | O(n)  |
| B-Tree                | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(n)  |
| Red-Black Tree        | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(n)  |
| Splay Tree            | N/A    | Θ(log n) | Θ(log n) | Θ(log n) | N/A    | O(log n) | O(log n) | O(log n) | O(n)  |
| AVL Tree              | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(n)  |
| KD Tree               | Θ(log n) | Θ(log n) | Θ(log n) | Θ(log n) | O(n)   | O(n)   | O(n)      | O(n)     | O(n)  |



### ✅ 2. Array Sorting Algorithms


| Algorithm       | Time Complexity (Best) | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity |
|----------------|-------------------------|----------------------------|--------------------------|------------------|
| Quicksort      | Ω(n log n)              | Θ(n log n)                 | O(n²)                    | O(log n)         |
| Mergesort      | Ω(n log n)              | Θ(n log n)                 | O(n log n)               | O(n)             |
| Timsort        | Ω(n)                    | Θ(n log n)                 | O(n log n)               | O(n)             |
| Heapsort       | Ω(n log n)              | Θ(n log n)                 | O(n log n)               | O(1)             |
| Bubble Sort    | Ω(n)                    | Θ(n²)                      | O(n²)                    | O(1)             |
| Insertion Sort | Ω(n)                    | Θ(n²)                      | O(n²)                    | O(1)             |
| Selection Sort | Ω(n²)                   | Θ(n²)                      | O(n²)                    | O(1)             |
| Tree Sort      | Ω(n log n)              | Θ(n log n)                 | O(n²)                    | O(n)             |
| Shell Sort     | Ω(n log n)              | Θ(n(log n)²)               | O(n(log n)²)             | O(1)             |
| Bucket Sort    | Ω(n + k)                | Θ(n + k)                   | O(n²)                    | O(n)             |
| Radix Sort     | Ω(nk)                   | Θ(nk)                      | O(nk)                    | O(n + k)         |
| Counting Sort  | Ω(n + k)                | Θ(n + k)                   | O(n + k)                 | O(k)             |
| Cubesort       | Ω(n)                    | Θ(n log n)                 | O(n log n)               | O(n)             |

---

## 📘 PART 2: Explanation of Time Complexities

Let’s go over the **“why”** behind common complexities:

### 📦 Data Structures

#### ✅ Array

* **Access**: `O(1)` because index access is direct.
* **Insert/Delete**: `O(n)` because shifting elements is required.

#### ✅ Stack & Queue

* Operate on ends (top for Stack, front/rear for Queue), hence:

  * **Push/Pop**: `O(1)`
  * **Search**: `O(n)` – have to scan all.

#### ✅ Linked Lists

* **Insert/Delete at head**: `O(1)`
* **Search or Access by index**: `O(n)` – must traverse.

#### ✅ Hash Table

* **Average case**: `O(1)` for Insert/Search/Delete due to hashing.
* **Worst case**: `O(n)` if collisions degenerate to linked list.

#### ✅ BST / AVL / Red-Black Tree

* **Balanced trees** keep height `~log(n)`, so operations are `O(log n)`.
* **Unbalanced BST** can degrade to `O(n)` if input is sorted.

---

### 🔃 Sorting Algorithms

#### ✅ QuickSort

* **Best/Average**: Divide and conquer, `O(n log n)`
* **Worst**: Unbalanced partitions → `O(n²)`

#### ✅ MergeSort

* Always divides array into halves → consistent `O(n log n)`
* Needs `O(n)` extra space for merging.

#### ✅ HeapSort

* Heapify takes `O(n)` + extract-min `O(log n)` \* n times → `O(n log n)`

#### ✅ Insertion, Bubble, Selection Sort

* All involve nested loops → `O(n²)` worst
* Insertion can be fast (`O(n)`) if array is nearly sorted.

#### ✅ Counting/Radix/Bucket Sort

* **Non-comparison-based** (used when input range is known).
* Fast for small keys or limited digits, but uses extra space.

