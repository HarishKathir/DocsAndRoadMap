Thanks wen through the whole video and gonna start doing it
for someone who wants a jist:
1. pattern 1 sliding windows. 
a) fixed size window. 
b) dynamic size window

LeetCode Problems to Practice
1. Maximum Sum Subarray of Size K (easy)
2. Longest Substring Without Repeating Characters
3. Longest Repeating Character Replacement
4. Minimum Size Subarray Sum
5. Permutation in String
6. Sliding Window Maximum
7. Find All Anagrams in a String
8. Substring with Concatenation of All Words (advanced)

pro tips for this pattern: 
 1. always store what you're tracking in the window.
 2. use hashmaps.
 3. expand from the right, shrink from left, until the condition breaks.
 
2. Two pointers (sorted array or linked list)

pairs, duplicates, subarrays. 

LeetCode Problems to Practice
Two Sum II - Input Array Is Sorted
Remove Duplicates from Sorted Array
Reverse String
Valid Palindrome
3Sum
Container With Most Water
Merge Sorted Array
Move Zeroes
Linked List Cycle
Trapping Rain Water (advanced)

tips: 
a. Is this array sorted?
b.  two pointers + sliding window

3. Fast and slow pointers pattern 

working with linked list or cyclic data structure. 

LeetCode Problems to Practice
1. Linked List Cycle
2. Linked List Cycle II (Find cycle start)
3. Middle of the Linked List
4. Happy Number - detect repeating number sequence
5. Find the Duplicate Number uses cycle detection in array
6. Palindrome Linked List
7. Reorder List uses fast/slow to split list


combination:

sliding windows + two pointer + fast and slow pointer

4. Frequency + hashmaps

a) quick look-up
b) track occurances

we store useful info in a key value pair.

Sets are also useful they are built internally useing hashmaps.

we use sets when we want unique elements only. 

5. DFS and backtracking

Always store the visited nodes. (we can use a set for it)
recursive depth is important.
3 iterative dfs using stacks, also works, if recursin is hard.

problems to do : 
Best LeetCode Problems to Practice
1. Number of Islands
2. Flood Fill
3. Clone Graph
4. Maximum Depth of Binary Tree
5. Binary Tree Paths
6. Graph Valid Tree
7. Path Sum
8. Accounts Merge
9. Pacific Atlantic Water Flow

6. BFS

bfs is iterative, we use queue to solve it. 
1. pick the starting cell.
2. add to queue.
3. process & marking visited
4. add neighbouring cells to queue.

(trees, graphs, matrix)

problems to solve:
Best LeetCode Problems to Practice
Number of Islands
Word Ladder
Rotting Oranges
7:32
Average of Levels in Binary Tree
Binary Tree Level Order Traversal

Tips: 

1. use queue (FiFO)
2. track visited node to avoid cycle.
3. minimum/shortest: think BFS

4. matrix problem: use direction array


7. Heap, priority queue.
When we want to access the minimum and maximum elements quickly we think of heaps.

heaps usually show up in greedy, graphs and interval based problems.

heap + hashmaps (when we want to group things)
Best LeetCode Problems to Practice
Last Stone Weight
Top K Frequent Elements
Kth Largest Element in an Array
Merge K Sorted Lists
Task Scheduler
Meeting Rooms II

8 Dynamic Programming (DP)

we store the results in an array or dictionary.

best, min, max value.


ask 
a ) whe decision i'm marking
b) what parameters to track ?
c) previous result  to current answer.
d) base problem.

1D dynamic problem
2D dynamic problem
Dynamic programming on strings

Best LeetCode Problems to Practice
Climbing Stairs
House Robber
Longest Palindromic Substring
Longest Common Subsequence
Unique Paths
Coin Change


9 prefix Sum

compute the sum of sub array in constant time.
problems: 303. Range Sum Query - Immutable
307. Range Sum Query - Mutable
327. Count of Range Sum
938. Range Sum of BST
304. Range Sum Query 2D - Immutable


Best LeetCode Problems to Practice
560 - Subarray Sum Equals K
974 - Subarray Sums Divisible by K
930 - Binary Subarrays With Sum
1248 - Count Number of Nice Subarrays
1074 - Number of Submatrices That Sum to Target
363 - Max Sum of Rectangle No Larger Than K
437-Path Sum III
325-Maximum Size Subarray Sum Equals k

10 Modified binary Search.

a ) Sorted array
b )Partially sorted array.
c ) Linear scans to O (log n).

questions to ans:
Best LeetCode Problems to Practice
Search in Rotated Sorted Array
Find Minimum in Rotated Sorted Array
Find First and Last Position of Element in Sorted Array
Koko Eating Bananas
Capacity To Ship Packages Within D Days
Minimum Number of Days to Make m Bouquets
Search a 2D Matrix

ResourcesL

deepti talesra
neetcode and Greg Hogg