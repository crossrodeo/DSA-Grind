# DSA Grind

Daily practice log for data structures and algorithms. Built to prepare for technical interviews and to keep a consistent, trackable record of problem-solving over time.

## Structure

```
dsa-grind/
├── arrays-strings/
├── hashing/
├── two-pointers/
├── sliding-window/
├── stack-queue/
├── linked-list/
├── binary-search/
├── trees/
├── tries/
├── heaps/
├── backtracking/
├── graphs/
├── dynamic-programming/
├── greedy/
├── intervals/
├── math-bit-manipulation/
├── templates/          # reusable patterns - BFS, DFS, binary search, etc.
├── notes/               # topic notes and cheat sheets
└── README.md
```

Solutions are named `<topic>-<problem-name>.py`, e.g. `graphs-number-of-islands.py`, `dp-longest-increasing-subsequence.py`.

## Solution format

```python
"""
Problem: [Problem Name]
Link: [URL]
Difficulty: Easy / Medium / Hard
Pattern: [e.g. Sliding Window, Two Pointers]

Approach:
[short explanation]

Time Complexity: O(?)
Space Complexity: O(?)
"""

def solution(...):
    pass


if __name__ == "__main__":
    pass
```

## Progress log

| Date | Problem | Topic | Difficulty | Time Taken | Attempts | Notes |
|------|---------|-------|------------|------------|----------|-------|
|      |         |       |            |            |          |       |

Update after every problem solved.

## Topic checklist

- [ ] Arrays & Strings
- [ ] Hashing
- [ ] Two Pointers
- [ ] Sliding Window
- [ ] Stack & Queue
- [ ] Linked List
- [ ] Binary Search
- [ ] Trees (traversals, BSTs)
- [ ] Tries
- [ ] Heaps / Priority Queue
- [ ] Backtracking
- [ ] Graphs (BFS/DFS, topological sort, union-find)
- [ ] Dynamic Programming (1D, 2D, knapsack, LIS)
- [ ] Greedy
- [ ] Intervals
- [ ] Math & Bit Manipulation

## Revision approach

Re-attempt problems marked hard after 3 days, then 7, then 21. Try to re-solve from scratch before checking old code. Group problems by pattern instead of jumping topics. Cap each attempt at 25-30 minutes before looking at hints.

## Resources

- LeetCode - leetcode.com
- NeetCode - neetcode.io
- Striver's A2Z DSA Sheet - takeuforward.org
- Cracking the Coding Interview

## Setup

```bash
git clone https://github.com/crossrodeo/dsa-grind.git
cd dsa-grind
python -m venv .venv
source .venv/bin/activate
```

No external dependencies. Standard library only unless a file header says otherwise.

## Stats

| Metric | Count |
|--------|-------|
| Total Solved | 0 |
| Easy | 0 |
| Medium | 0 |
| Hard | 0 |
| Streak (days) | 0 |
| Topics Completed | 0 / 16 |

## Goals

Solve consistently. Prioritize understanding the pattern over memorizing the solution. Use this as a revision reference before interviews.

<!---LeetCode Topics Start-->
# LeetCode Topics
## Array
|  |
| ------- |
| [1301-number-of-paths-with-max-score](https://github.com/crossrodeo/DSA-Grind/tree/master/1301-number-of-paths-with-max-score) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Breadth-First Search
|  |
| ------- |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/crossrodeo/DSA-Grind/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
## Graph Theory
|  |
| ------- |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/crossrodeo/DSA-Grind/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Heap (Priority Queue)
|  |
| ------- |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Matrix
|  |
| ------- |
| [1301-number-of-paths-with-max-score](https://github.com/crossrodeo/DSA-Grind/tree/master/1301-number-of-paths-with-max-score) |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
## Shortest Path
|  |
| ------- |
| [3286-find-a-safe-walk-through-a-grid](https://github.com/crossrodeo/DSA-Grind/tree/master/3286-find-a-safe-walk-through-a-grid) |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Depth-First Search
|  |
| ------- |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/crossrodeo/DSA-Grind/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
## Union-Find
|  |
| ------- |
| [2492-minimum-score-of-a-path-between-two-cities](https://github.com/crossrodeo/DSA-Grind/tree/master/2492-minimum-score-of-a-path-between-two-cities) |
## Binary Search
|  |
| ------- |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Dynamic Programming
|  |
| ------- |
| [1301-number-of-paths-with-max-score](https://github.com/crossrodeo/DSA-Grind/tree/master/1301-number-of-paths-with-max-score) |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
## Topological Sort
|  |
| ------- |
| [3620-network-recovery-pathways](https://github.com/crossrodeo/DSA-Grind/tree/master/3620-network-recovery-pathways) |
<!---LeetCode Topics End-->