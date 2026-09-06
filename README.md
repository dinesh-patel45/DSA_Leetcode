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
## LeetCode 209 — Minimum Size Subarray Sum

### My First Approach
Use a sliding window with two pointers. Expand the window using `j`
and shrink it using `i` whenever the sum becomes greater than or equal to target.

### Problem With My Approach
No major problem. Since all numbers are positive, the sliding window
works optimally.

### Optimal Approach
Use a sliding window with two pointers.

### Complexity
TC: O(n)
SC: O(1)

### Key Learning
When all array elements are positive, sliding window can efficiently
find the minimum length subarray satisfying a sum condition