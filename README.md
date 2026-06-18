# 🧠 NeetCode 150 — Practice Tracker

> **Source:** [neetcode.io/practice/neetcode150](https://neetcode.io/practice/practice/neetcode150)
> 
> **How to use this file:**
> - ✅ = Solved confidently | 🔄 = Revisit needed | ❌ = Not done yet | 💡 = Reviewed only
> - **Hint / One-Liner:** What is the core insight? Write it in your own words after solving.
> - **Approaches:** List all valid approaches (e.g., brute force, optimal) with time/space complexity.
> - **My Notes:** Edge cases, mistakes made, language-specific tricks, etc.

---

## 📊 Progress

| Category | Done | Total |
|---|---|---|
| Arrays & Hashing | 8 | 9 |
| Two Pointers | 0 | 5 |
| Sliding Window | 0 | 6 |
| Stack | 0 | 7 |
| Binary Search | 0 | 7 |
| Linked List | 0 | 11 |
| Trees | 0 | 15 |
| Tries | 0 | 3 |
| Heap / Priority Queue | 0 | 7 |
| Backtracking | 0 | 9 |
| Graphs | 0 | 13 |
| Advanced Graphs | 0 | 6 |
| 1-D Dynamic Programming | 0 | 12 |
| 2-D Dynamic Programming | 0 | 11 |
| Greedy | 0 | 8 |
| Intervals | 0 | 6 |
| Math & Geometry | 0 | 6 |
| Bit Manipulation | 0 | 7 |
| **Total** | **8** | **150** |

---

## 1. Arrays & Hashing

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | 🟢 Easy | ✅ | Use a Set — check if element already added | Sort O(nlogn) · Set O(n) | |
| 2 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | 🟢 Easy | ✅ | Frequency array using `ord(c) - ord('a')` for ASCII offset | Compare frequency arrays O(n) | |
| 3 | [Two Sum](https://leetcode.com/problems/two-sum/) | 🟢 Easy | ✅ | HashMap: store seen values, check complement exists | Brute O(n²) · HashMap O(n) · Sort+2ptr O(nlogn) | |
| 4 | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | 🟡 Medium | ✅ | Sort each word → use as HashMap key, group by key | HashMap with sorted key O(n·klogk) | |
| 5 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | 🟡 Medium | ✅ | Bucket sort: one bucket per frequency, scan from end | Bucket Sort O(n) · Heap O(nlogk) | |
| 6 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | 🟡 Medium | ✅ | Prefix product × Postfix product for each index (no division) | Prefix+Postfix O(n) space O(1) extra | |
| 7 | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | 🟡 Medium | ✅ | Track seen values per row/col/box; boxKey = `"box" + str(r//3) + str(c//3)` | HashSet per row+col+box O(81) | |
| 8 | [Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) | 🟡 Medium | ✅ | Encode each word as `len#word`; decode by reading length then `#` then chars | Length-prefixed encoding O(n) | |
| 9 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | 🟡 Medium | 🔄 | Put all in Set; for each `n` where `n-1` not in Set, count streak upward | Set O(n) · Union-Find O(n·α) | n-1 not in set = start of sequence |

---

## 2. Two Pointers

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | 🟢 Easy | ❌ | | | |
| 2 | [Two Sum II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | 🟡 Medium | ❌ | | | |
| 3 | [3Sum](https://leetcode.com/problems/3sum/) | 🟡 Medium | ❌ | | | |
| 4 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | 🟡 Medium | ❌ | | | |
| 5 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | 🔴 Hard | ❌ | | | |

---

## 3. Sliding Window

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | 🟢 Easy | ❌ | | | |
| 2 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | 🟡 Medium | ❌ | | | |
| 3 | [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | 🟡 Medium | ❌ | | | |
| 4 | [Permutation in String](https://leetcode.com/problems/permutation-in-string/) | 🟡 Medium | ❌ | | | |
| 5 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | 🔴 Hard | ❌ | | | |
| 6 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | 🔴 Hard | ❌ | | | |

---

## 4. Stack

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | 🟢 Easy | ❌ | | | |
| 2 | [Min Stack](https://leetcode.com/problems/min-stack/) | 🟡 Medium | ❌ | | | |
| 3 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | 🟡 Medium | ❌ | | | |
| 4 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | 🟡 Medium | ❌ | | | |
| 5 | [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | 🟡 Medium | ❌ | | | |
| 6 | [Car Fleet](https://leetcode.com/problems/car-fleet/) | 🟡 Medium | ❌ | | | |
| 7 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | 🔴 Hard | ❌ | | | |

---

## 5. Binary Search

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Binary Search](https://leetcode.com/problems/binary-search/) | 🟢 Easy | ❌ | | | |
| 2 | [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | 🟡 Medium | ❌ | | | |
| 3 | [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | 🟡 Medium | ❌ | | | |
| 4 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | 🟡 Medium | ❌ | | | |
| 5 | [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | 🟡 Medium | ❌ | | | |
| 6 | [Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) | 🟡 Medium | ❌ | | | |
| 7 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | 🔴 Hard | ❌ | | | |

---

## 6. Linked List

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | 🟢 Easy | ❌ | | | |
| 2 | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | 🟢 Easy | ❌ | | | |
| 3 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | 🟢 Easy | ❌ | | | |
| 4 | [Reorder List](https://leetcode.com/problems/reorder-list/) | 🟡 Medium | ❌ | | | |
| 5 | [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | 🟡 Medium | ❌ | | | |
| 6 | [Copy List With Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | 🟡 Medium | ❌ | | | |
| 7 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | 🟡 Medium | ❌ | | | |
| 8 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | 🟡 Medium | ❌ | | | |
| 9 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | 🟡 Medium | ❌ | | | |
| 10 | [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | 🔴 Hard | ❌ | | | |
| 11 | [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | 🔴 Hard | ❌ | | | |

---

## 7. Trees

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | 🟢 Easy | ❌ | | | |
| 2 | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | 🟢 Easy | ❌ | | | |
| 3 | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | 🟢 Easy | ❌ | | | |
| 4 | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | 🟢 Easy | ❌ | | | |
| 5 | [Same Tree](https://leetcode.com/problems/same-tree/) | 🟢 Easy | ❌ | | | |
| 6 | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | 🟢 Easy | ❌ | | | |
| 7 | [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | 🟡 Medium | ❌ | | | |
| 8 | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | 🟡 Medium | ❌ | | | |
| 9 | [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | 🟡 Medium | ❌ | | | |
| 10 | [Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | 🟡 Medium | ❌ | | | |
| 11 | [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | 🟡 Medium | ❌ | | | |
| 12 | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | 🟡 Medium | ❌ | | | |
| 13 | [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 🟡 Medium | ❌ | | | |
| 14 | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | 🔴 Hard | ❌ | | | |
| 15 | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | 🔴 Hard | ❌ | | | |

---

## 8. Tries

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | 🟡 Medium | ❌ | | | |
| 2 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | 🟡 Medium | ❌ | | | |
| 3 | [Word Search II](https://leetcode.com/problems/word-search-ii/) | 🔴 Hard | ❌ | | | |

---

## 9. Heap / Priority Queue

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | 🟢 Easy | ❌ | | | |
| 2 | [Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | 🟢 Easy | ❌ | | | |
| 3 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | 🟡 Medium | ❌ | | | |
| 4 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | 🟡 Medium | ❌ | | | |
| 5 | [Task Scheduler](https://leetcode.com/problems/task-scheduler/) | 🟡 Medium | ❌ | | | |
| 6 | [Design Twitter](https://leetcode.com/problems/design-twitter/) | 🟡 Medium | ❌ | | | |
| 7 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | 🔴 Hard | ❌ | | | |

---

## 10. Backtracking

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Subsets](https://leetcode.com/problems/subsets/) | 🟡 Medium | ❌ | | | |
| 2 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | 🟡 Medium | ❌ | | | |
| 3 | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | 🟡 Medium | ❌ | | | |
| 4 | [Permutations](https://leetcode.com/problems/permutations/) | 🟡 Medium | ❌ | | | |
| 5 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | 🟡 Medium | ❌ | | | |
| 6 | [Word Search](https://leetcode.com/problems/word-search/) | 🟡 Medium | ❌ | | | |
| 7 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | 🟡 Medium | ❌ | | | |
| 8 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | 🟡 Medium | ❌ | | | |
| 9 | [N-Queens](https://leetcode.com/problems/n-queens/) | 🔴 Hard | ❌ | | | |

---

## 11. Graphs

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | 🟡 Medium | ❌ | | | |
| 2 | [Clone Graph](https://leetcode.com/problems/clone-graph/) | 🟡 Medium | ❌ | | | |
| 3 | [Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | 🟡 Medium | ❌ | | | |
| 4 | [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | 🟡 Medium | ❌ | | | |
| 5 | [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | 🟡 Medium | ❌ | | | |
| 6 | [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | 🟡 Medium | ❌ | | | |
| 7 | [Walls and Gates](https://leetcode.com/problems/walls-and-gates/) | 🟡 Medium | ❌ | | | |
| 8 | [Course Schedule](https://leetcode.com/problems/course-schedule/) | 🟡 Medium | ❌ | | | |
| 9 | [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | 🟡 Medium | ❌ | | | |
| 10 | [Redundant Connection](https://leetcode.com/problems/redundant-connection/) | 🟡 Medium | ❌ | | | |
| 11 | [Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | 🟡 Medium | ❌ | | | |
| 12 | [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) | 🟡 Medium | ❌ | | | |
| 13 | [Word Ladder](https://leetcode.com/problems/word-ladder/) | 🔴 Hard | ❌ | | | |

---

## 12. Advanced Graphs

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | 🔴 Hard | ❌ | | | |
| 2 | [Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/) | 🟡 Medium | ❌ | | | |
| 3 | [Network Delay Time](https://leetcode.com/problems/network-delay-time/) | 🟡 Medium | ❌ | | | |
| 4 | [Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | 🔴 Hard | ❌ | | | |
| 5 | [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) | 🔴 Hard | ❌ | | | |
| 6 | [Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | 🟡 Medium | ❌ | | | |

---

## 13. 1-D Dynamic Programming

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | 🟢 Easy | ❌ | | | |
| 2 | [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | 🟢 Easy | ❌ | | | |
| 3 | [House Robber](https://leetcode.com/problems/house-robber/) | 🟡 Medium | ❌ | | | |
| 4 | [House Robber II](https://leetcode.com/problems/house-robber-ii/) | 🟡 Medium | ❌ | | | |
| 5 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | 🟡 Medium | ❌ | | | |
| 6 | [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) | 🟡 Medium | ❌ | | | |
| 7 | [Decode Ways](https://leetcode.com/problems/decode-ways/) | 🟡 Medium | ❌ | | | |
| 8 | [Coin Change](https://leetcode.com/problems/coin-change/) | 🟡 Medium | ❌ | | | |
| 9 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | 🟡 Medium | ❌ | | | |
| 10 | [Word Break](https://leetcode.com/problems/word-break/) | 🟡 Medium | ❌ | | | |
| 11 | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | 🟡 Medium | ❌ | | | |
| 12 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | 🟡 Medium | ❌ | | | |

---

## 14. 2-D Dynamic Programming

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Unique Paths](https://leetcode.com/problems/unique-paths/) | 🟡 Medium | ❌ | | | |
| 2 | [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | 🟡 Medium | ❌ | | | |
| 3 | [Best Time to Buy and Sell Stock With Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | 🟡 Medium | ❌ | | | |
| 4 | [Coin Change II](https://leetcode.com/problems/coin-change-ii/) | 🟡 Medium | ❌ | | | |
| 5 | [Target Sum](https://leetcode.com/problems/target-sum/) | 🟡 Medium | ❌ | | | |
| 6 | [Interleaving String](https://leetcode.com/problems/interleaving-string/) | 🟡 Medium | ❌ | | | |
| 7 | [Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | 🔴 Hard | ❌ | | | |
| 8 | [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) | 🔴 Hard | ❌ | | | |
| 9 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | 🟡 Medium | ❌ | | | |
| 10 | [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | 🔴 Hard | ❌ | | | |
| 11 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | 🔴 Hard | ❌ | | | |

---

## 15. Greedy

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | 🟡 Medium | ❌ | | | |
| 2 | [Jump Game](https://leetcode.com/problems/jump-game/) | 🟡 Medium | ❌ | | | |
| 3 | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | 🟡 Medium | ❌ | | | |
| 4 | [Gas Station](https://leetcode.com/problems/gas-station/) | 🟡 Medium | ❌ | | | |
| 5 | [Hand of Straights](https://leetcode.com/problems/hand-of-straights/) | 🟡 Medium | ❌ | | | |
| 6 | [Merge Triplets to Form Target Triplet](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/) | 🟡 Medium | ❌ | | | |
| 7 | [Partition Labels](https://leetcode.com/problems/partition-labels/) | 🟡 Medium | ❌ | | | |
| 8 | [Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/) | 🟡 Medium | ❌ | | | |

---

## 16. Intervals

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Insert Interval](https://leetcode.com/problems/insert-interval/) | 🟡 Medium | ❌ | | | |
| 2 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | 🟡 Medium | ❌ | | | |
| 3 | [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | 🟡 Medium | ❌ | | | |
| 4 | [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/) | 🟢 Easy | ❌ | | | |
| 5 | [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) | 🟡 Medium | ❌ | | | |
| 6 | [Minimum Interval to Include Each Query](https://leetcode.com/problems/minimum-interval-to-include-each-query/) | 🔴 Hard | ❌ | | | |

---

## 17. Math & Geometry

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Rotate Image](https://leetcode.com/problems/rotate-image/) | 🟡 Medium | ❌ | | | |
| 2 | [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | 🟡 Medium | ❌ | | | |
| 3 | [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | 🟡 Medium | ❌ | | | |
| 4 | [Happy Number](https://leetcode.com/problems/happy-number/) | 🟢 Easy | ❌ | | | |
| 5 | [Plus One](https://leetcode.com/problems/plus-one/) | 🟢 Easy | ❌ | | | |
| 6 | [Pow(x, n)](https://leetcode.com/problems/powx-n/) | 🟡 Medium | ❌ | | | |

---

## 18. Bit Manipulation

| # | Problem | Difficulty | Status | Hint / One-Liner | Approaches | My Notes |
|---|---------|-----------|--------|-------------------|------------|----------|
| 1 | [Single Number](https://leetcode.com/problems/single-number/) | 🟢 Easy | ❌ | | | |
| 2 | [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | 🟢 Easy | ❌ | | | |
| 3 | [Counting Bits](https://leetcode.com/problems/counting-bits/) | 🟢 Easy | ❌ | | | |
| 4 | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | 🟢 Easy | ❌ | | | |
| 5 | [Missing Number](https://leetcode.com/problems/missing-number/) | 🟢 Easy | ❌ | | | |
| 6 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | 🟡 Medium | ❌ | | | |
| 7 | [Reverse Integer](https://leetcode.com/problems/reverse-integer/) | 🟡 Medium | ❌ | | | |

---

## 📝 Daily Log

Use this section to track what you solved each day.

| Date | Problem(s) Solved | Time Spent | Reflection |
|------|-------------------|------------|------------|
| | | | |

---

## 💡 Pattern Cheat Sheet

Quick reminders for common patterns — fill in as you learn.

| Pattern | When to Use | Template / Trigger Words |
|---------|-------------|--------------------------|
| HashMap / HashSet | Duplicates, frequency count, complement lookup | "two sum", "contains", "group" |
| Two Pointers | Sorted array, palindrome, pairs | "sorted", "palindrome", "sum" |
| Sliding Window | Subarray/substring with constraint | "longest", "minimum", "at most k" |
| Binary Search | Sorted input, search for boundary | "sorted", "rotated", "minimum speed" |
| DFS / BFS | Graph traversal, tree problems | "connected", "level order", "shortest path" |
| Dynamic Programming | Optimal substructure, overlapping subproblems | "ways to", "minimum cost", "longest" |
| Monotonic Stack | Next greater/smaller element | "daily temperatures", "histogram" |
| Union-Find | Connected components, cycle detection | "connected", "redundant" |
| Heap / Priority Queue | Kth element, streaming median | "k largest", "median", "top k" |
| Backtracking | Combinations, permutations, constraints | "all subsets", "generate all", "place" |
