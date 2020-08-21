# CrackingAlgorithms
Solutions for my LeetCode challenging and Java practice. Sorted in different topics and add comments for easy understanding.

# Problems and Solutions

| # | Title | Topic | Solution | Basic idea| Difficulty |
|---| ----- | ----- | -------- | --------------------- | ------ |
| 1 | [two-sum](https://leetcode.com/problems/two-sum) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/two-sum.java)| One pass hashtable to check whether the complement in the map | Easy |
| 21 | [merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/merge-two-sorted-lists.java)| Maintain dummy head and tail to iteratively add smalled node to the end | Easy |
| 22 | [generate-parentheses](https://leetcode.com/problems/generate-parentheses) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/generate-parentheses.java)| Check number of left / right parentheses before DFS. | Medium |
| 24 | [swap-nodes-in-pairs](https://leetcode.com/problems/swap-nodes-in-pairs) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Strucure/swap-nodes-in-pairs.java)| Recursion rule `swapPair(head.next.next)` | Medium |
| 25 | [reverse-nodes-in-k-group](https://leetcode.com/problems/) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Strucure/.java)| Find K-group, reverse K-group and link to next reversed sub-list. | Hard |
| 26 | [remove-duplicates-from-sorted-array](https://leetcode.com/problems/remove-duplicates-from-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/remove-duplicates-from-sorted-array.java)| Two pointers, slow is the last element to be returned. | Easy |
| 45 | [jump-game-ii](https://leetcode.com/problems/jump-game-ii) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/jump-game-ii.java)| Array to store the min jumps needed to reach end from i-th position | Hard |
| 46 | [permutations](https://leetcode.com/problems/permutations) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/permutations.java)| Use in-place swap or extra boolean array to mark used state. | Medium |
| 47 | [permutations-ii](https://leetcode.com/problems/permutations-ii) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/permutations-ii.java)| For each level, use HashSet to track whether letter has been used. | Medium |
| 50 | [powx-n](https://leetcode.com/problems/powx-n) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/powx-n.java)| Recursive `x^t = x^(t/2) * x^(t/2)` and be careful with `Interger.MIN_VALUE` | Medium |
| 53 | [maximum-subarray](https://leetcode.com/problems/maximum-subarray) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/maximum-subarray.java)| Max between (previous max_sum + current num) and only current num itself | Easy |
| 54 | [spiral-matrix](https://leetcode.com/problems/spiral-matrix) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/spiral-matrix.java)| Recursion layer by layer, top row -> right col -> bottom row -> left col | Medium |
| 55 | [jump-game](https://leetcode.com/problems/jump-game) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/jump-game.java)| Boolean array to store whether we can jump starting from current index to reach the end | Medium |
| 74 | [search-a-2d-matrix](https://leetcode.com/problems/search-a-2d-matrix) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/search-a-2d-matrix.java)| 2D array to 1D array, Binary Search | Medium |
| 75 | [sort-colors](https://leetcode.com/problems/sort-colors) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/sort-colors.java)| Maintain 3 pointers to partition to 3 areas | Medium |
| 78 | [subsets](https://leetcode.com/problems/subsets) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/subsets.java)| For each level, two state: add to subset or not. Recursion tree will have `num.length` levels. | Medium |
| 80 | [remove-duplicates-from-sorted-array-ii](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/remove-duplicates-from-sorted-array-ii.java)| Two pointers, each time check fast and (slow - 2) | Medium |
| 86 | [partition-list](https://leetcode.com/problems/partition-list) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/partition-list.java)| Maintain two Dummy head and tail for small and large list, then concatenate | Medium |
| 88 | [merge-sorted-array](https://leetcode.com/problems/merge-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/merge-sorted-array.java)| In-place: two pointer from end to start, iteratively copy larger number to the end | Easy |
| 90 | [subsets-ii](https://leetcode.com/problems/subsets-ii) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/subsets-ii.java)| Add element or not add element. If not add, skip all the rest duplicates. | Medium |
| 100 | [same-tree](https://leetcode.com/problems/same-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/same-tree.java)| Recursive compare `LL` & `RL`, `LR` & `RR` to determine whether is same tree for each pair | Easy |
| 101 | [symmetric-tree](https://leetcode.com/problems/symmetric-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/symmetric-tree.java)| Recursive compare `LL` & `RR`, `LR` & `RL` to determine whether symmetric for each pair | Easy |
| 102 | [binary-tree-level-order-traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/BFS/binary-tree-level-order-traversal.java)| BFS, use list to store value on each level | Medium |
| 104 | [maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/maximum-depth-of-binary-tree.java)| Recursion to get max height from left and right child then increase by 1| Easy |
| 110 | [balanced-binary-tree](https://leetcode.com/problems/balanced-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/balanced-binary-tree.java)| Pre-order traverse and compare left & right using `getHeight()` helper function | Easy |
| 141 | [linked-list-cycle](https://leetcode.com/problems/linked-list-cycle) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/linked-list-cycle.java)| Fast and slow pointer, cycle exists when two pointers meet | Easy |
| 143 | [reorder-list](https://leetcode.com/problems/reorder-list) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/reorder-list.java)| Find mid nodes -> Reverse second part -> Merge two parts | Medium |
| 155 | [min-stack](https://leetcode.com/problems/min-stack) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/min-stack.java)| Auxiliary sync stack to store min, push min when num <= min | Easy |
| 167 | [two-sum-ii-input-array-is-sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/two-sum-ii-input-array-is-sorted.java)| Two pointers from left and right | Easy |
| 186 | [reverse-words-in-a-string-ii](https://leetcode.com/problems/reverse-words-in-a-string-ii) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/reverse-words-in-a-string-ii.java)| 3-steps reverse: reverse all words, then reverse whole sentence | Medium |
| 189 | [rotate-array](https://leetcode.com/problems/rotate-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/rotate-array.java)| 3-steps reverse, first part ending at (length - 1 - steps). | Easy |
| 191 | [number-of-1-bits](https://leetcode.com/problems/number-of-1-bits) | Other | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Other/number-of-1-bits.java)| Iteratively right shift and compare `n & 1` with 1 | Easy |
| 203 | [remove-linked-list-elements](https://leetcode.com/problems/remove-linked-list-elements) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Strucure/remove-linked-list-elements.java)| Dummy node, iteratively remove all target | Easy |
| 206 | [reverse-linked-list](https://leetcode.com/problems/reverse-linked-list) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/reverse-linked-list.java)| Iterative and Recursion | Easy |
| 231 | [power-of-two](https://leetcode.com/problems/power-of-two) | Other | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Other/power-of-two.java)| Check whether contain only one 1-bit | Easy |
| 283 | [move-zeroes](https://leetcode.com/problems/move-zeroes) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/move-zeroes.java)| 2 pointers copy non-0s to front of left, then fill left to end with 0s. | Easy |
| 344 | [reverse-string](https://leetcode.com/problems/reverse-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/reverse-string.java)| Two pointers swap or Recursion | Easy |
| 461 | [hamming-distance](https://leetcode.com/problems/hamming-distance) | Other | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Other/hamming-distance.java)| XOR the two Interger and count how many 1-bits | Easy |
| 509 | [fibonacci-number](https://leetcode.com/problems/fibonacci-number) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/fibonacci-number.java)| 2-value Memoization `fibo(N) = fibo(N-2) + fibo(N-1)` | Easy |
| 643 | [maximum-average-subarray-i](https://leetcode.com/problems/maximum-average-subarray-i) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/maximum-average-subarray-i.java)| Sliding window to find the maximum sum with size K | Easy |
| 700 | [search-in-a-binary-search-tree](https://leetcode.com/problems/search-in-a-binary-search-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/search-in-a-binary-search-tree.java)| Iterative and Recursive | Easy |
| 704 | [binary-search](https://leetcode.com/problems/binary-search) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/binary-search.java)| Classical Binary Search | Easy |
| 876 | [middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list/) | Data Structure | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Data_Structure/middle-of-the-linked-list.java)| Fast & Slow two pointers | Easy |
| 912 | [merge-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/merge-sort.java)| Recursion helper function + merge two sorted array | Medium |
| 912 | [quick-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/quick-sort.java)| Pick random pivot + maintain two pointer to partion the array |  Medium |
| 912 | [selection-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/selection-sort.java)| Maintain one partition between sorted part and unsorted part |  Medium |
| 958 | [check-completeness-of-a-binary-tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/check-completeness-of-a-binary-tree.java)| BFS level order traversal, add one bool to indicate whether null found in the leftside | Medium |
| 1047 | [remove-all-adjacent-duplicates-in-string](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/remove-all-adjacent-duplicates-in-string.java)| Two pointer to maintian one in-place stack. | Easy |
| L8 | [rotate-string](https://www.lintcode.com/problem/rotate-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/rotate-string.java)| 3 steps reverse, divided by index `str.length - 1 - offset` | Easy |
| L11 | [search-range-in-binary-search-tree](https://www.lintcode.com/problem/search-range-in-binary-search-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/search-range-in-binary-search-tree.java)| inOrder traverse and check bound condition before recurse left or right | Medium |
| L14 | [first-position-of-target](https://lintcode.com/problem/first-position-of-target) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/first-position-of-target.java)| Classical binary search + `right = mid` when found target to search left-side + post-processing | Easy |
| L39 | [recover-rotated-sorted-array](https://www.lintcode.com/problem/recover-rotated-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/recover-rotated-sorted-array.java)| 3 Steps reverse. One pass to find offset | Easy |
| L229 | [stack-sorting](https://www.lintcode.com/problem/stack-sorting/) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/stack-sorting.java)| Selection sort. Bottom of buffer stack are sorted elements. | Medium |
| L458 | [last-position-of-target](https://lintcode.com/problem/last-position-of-target) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/last-position-of-target.java)| Classical binary search + `left = mid` when found target to search right-side + post-processing | Easy |
| L459 | [closest-number-in-sorted-array](https://www.lintcode.com/problem/closest-number-in-sorted-array) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/closest-number-in-sorted-array.java)| Classical binary search + post-processing to compare distance from left/right to target | Easy |
| L470 | [tweaked-identical-binary-tree](https://www.lintcode.com/problem/tweaked-identical-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/tweaked-identical-binary-tree.java)| Recursion check whether is symmetric or same tree | Medium |
| L686 | [remove-arbitrary-space](https://www.lintcode.com/problem/remove-arbitrary-space) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/remove-arbitrary-space.java)| Two pointers to copy non-space chars to slow position. Add heading space to non-first words. | Easy |