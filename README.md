# DSA LeetCode

My daily LeetCode problem-solving journey.git
## LeetCode 845 — Longest Mountain in Array

### My First Approach
Find every peak and expand left and right to calculate the mountain length.

### Problem With My Approach
The same elements can be traversed multiple times, resulting in O(n²) time.

### Optimal Approach
Use one-pass traversal with `up` and `down` to track the increasing
and decreasing parts of the mountain.

### Complexity
TC: O(n)
SC: O(1)

### Key Learning
A problem that looks like it needs expansion from every peak can sometimes
be solved in one pass by maintaining the current state.