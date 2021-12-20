# DSA-
solutions to graze over
1. Even Odd tree => simple level order problem with slight modifications
2. All paths from source to end => simple graph backtracking problem which can be solved easliy using recursion template for backtracking
3. Mother vertex in directed graph => good dfs problem idea is to do dfs and remember last finished node as candidate of mother vertex. then do dfs from candidate and see if all other nodes are visited are not.
4.  Find the peak element => classic BS problem with good observations skills
5.  Find peak element in 2d array => full observation based and involved thought process
6.  Min Deletions to make char freq unique => simple greedy problem invloves map for preprocessing then set for calculating unique frequencies and remaining manipulations
7.  Minimum Number of Vertices to Reach All Nodes => DAG problem very simple involves IN/OUT degrees with including why? as we can only visit any vertex which has indegree 0 manually
8.  Maximum Length of a Concatenated String with Unique Characters => backtraking solution where we consider all combinations
9.  Find N Unique Integers Sum up to Zero => Math and observations based problem only task is to find how to fill the array
10. Regions Cut By Slashes => simple problem when we deduce this the number of islands problem just trick is to upscale the grid 3 times so we can easily do a dfsORBfs
11. Jump Game => recursive approach is very simple but time and space consuming Iterative is very efficient but involves thought process and neat observations
12. Jump Game 2 => same logic just extraa calculations to know min jumps
13. Jump Game 3 => bfs problem moving level by level and see if any idx(node) satisfy the condition
14. meeting room => find if person can attend all meetings simple sorting and observation to see if no interval overlap each other
15. meeting room2 => finding min rooms for arranging all the meeting brute force is O(n ^ 2) but using minHeap we can reduce it upto O(nlogn)
16. Count Good Nodes in Binary Tree => preorder passing value from parent to childern
17. Sign of the Product of an Array => idea is to avoid overflow and without doing prod determine sign based on no of -ve integers
18. Find Minimum in Rotated Sorted Array => similar to finding peak element little bit observations based using < in BS
19.  Reorder Routes to Make All Paths Lead to the City Zero => Idea is to create Adj list for both in/out degrees then do dfs and count all the edges whom are in out degree.
20.  Find largest Alphabet in string => simple problem can be solved using hashtable
21.  Redundant Connection => finding the edge which is causing cycle in undirected graph UNION AND FIND really good question
22.  Pacific Atlantic water flow => simple graph bfs dfs problem with traversing from boundary of matrix flood fill algo from ocean reverse thinking involved with some neat observations.
23. Palindromic Substrings => counting no of palindrome substrings New Concept even and odd palindrome easy one 
24. Longest Palindromic subsequece => same logic as LPSubstrig just diff is we dont look for remaing length when st and end ch matches 
25. Number of Operations to Make network connected => use fact that in connected graph of n nodes there is n - 1 edges and simple dfs
26. count primes => brute => better => best Sieve of Eratosthenes
27. Find Elements in a Contaminated Binary Tree => simple dfs with simple math of complete binary tree and set for remembering
28. Evaluate Division => this is undirected graph problem which includes math first task is to build graph adj lists then for every query find the path from source to target by multiplying edges.
29. Battleships in a Board => simple problem dfs like number of islands & this can be solved by just grazing on run
30. Distribute Coins in Binary Tree => this is postorder problem with lot of thought process where we will ask every child what do you want from parent
31. Lowest Common Ancestor of Deepest Leaves => problem can be solved in two steps first find deepes level left and right boundary then find lca using dfs
32. Delete Nodes And Return Forest => very good problem of dfs where we will graze while checking if curr node in target list or not
33. Reduce Array Size to The Half => first create frequency table then store frequencies in maxHeap then do the process
34. Maximum Score From Removing Stones => this is maxHeap problem push all the ip to maxHeap then pop untill we get the result
35. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold => this is simple sliding window problem where we can convert avg to total then count no of subarray of size k with sum gteq total
36. Satisfiability of Equality Equations => simple graph constructing then doing dfs to find the target in particular connected component
37. Time Needed to Buy Tickets => simple observation based algo involves little math 
38. Maximum Level Sum of a Binary Tree => simple level order problem
39. Maximal Network Rank => simple observation based indegrees adj matrix problem
40. Course Schedule IV => simple constructing the graph then doing individual dfs to finding the target
41. Minimize Maximum Pair Sum in Array => sorting then two pointer moving towards each other
42. Validate Binary Tree Nodes => tree root is child to no node so it is observation based problem doing level order with set to handle edge case where tree is graph
43. Next Permutation => this problem is observation based where it can be solved using algorithm
44. Two Furthest Houses With Different Colors => very simple problem which involves observation to get max distance we need to involve either end
45. Watering Plants => simple problem we have to simulate the process and some array specific math
46. Arithmetic Subarrays => problem is simple involves sorting logic and if we want to optimize in time then we need to make use of formula of finding diff bw two elements in arithmatic progression.
47. Find Center of Star Graph => this is very simple problem create freq table and return node which has val equal to nodes - 1
48. Minimum Number of Swaps to Make the String Balanced => this is totally observation based math problem but very easy if we get some insights
49.  Find All Groups of Farmland => bfs problem but if we observe it and figure out to graze over graph boundary then it is very simple problem
50.  Remove Colored Pieces if Both Neighbors are the Same Color => this is mind blowing problem can be solved using simple comman sense if we dont complicate it
51.  Check if All the Integers in a Range Are Covered => very simple problem to solve using brute force but there is trick to use prefix sum and solve it using linear time
52.  Maximum Product Difference Between Two Pairs => sorting problem or finding 2 min and max without sorting in one go
53.  Unique Length-3 Palindromic Subsequences => earlier this problem diverted me towards dp but this is observation based problem for odd palindromes
54.  Truncate Sentence => very simple straight forward simple problem
55.  Finding the Users Active Minutes => simple hashtable and set problem we just need to boil it down to basics
56.   Remove Stones to Minimize the Total => simple heap problem
57.  Check If String Is a Prefix of Array => implementation based very simple problem but description is little bit tricky
58.  Sum of All Odd Length Subarrays => this is classic array manipulation problem.
59.  Removing Minimum and Maximum From Array => simple array observation based problem
60.  Minimum Number of Buckets Required to Collect Rainwater from Houses => simple array visualization and simulation problem
61.  Minimum Cost Homecoming of a Robot in a Grid => simple array based greedy observation is very important
62.  Step-By-Step Directions From a Binary Tree Node to Another => finding the nodes then manipulate it this is very good observation based problem
63.  Check Whether Two Strings are Almost Equivalent => very simple hashmap problem with slice tempering of strings and ord function.
64.  Count Sorted Vowel Strings => simple pattern recognition observation based dp problem
65.  Floyd warshall algo finding shortest distance for all pairs of nodes => vimp problem asked in OA of clooktrack imp concept after dijkstra
66.  Reduction Operations to Make the Array Elements Equal => sorting and count simple problem
67.  Sum of Digits in Base K => very good basic math algorithmic problem
68.  Longest Substring Of All Vowels in Order => simple slinding window problem involving little bit observation to check if curr ele is less than previous
69.  First Missing Positive => very good problem brute force with the set and constant time with cyclic sort asked in yellow.ai
70.  Shuffle an Array => fisher yates algorithm going backwards logic partitions into array
71.  Find Good Days to Rob the Bank => preprocessing is necessary like largest histogram or trapping rainwater
72.  Rings and Rods => simple array manipulation problem
73.  Jewels and Stones => simple hashtable problem
74.  Increasing Order Search Tree => very very good problem with though process of inorder with head and tail pointers
75.  Range Sum of BST => first find source using bst prop then graze for that tree
76.  Missing Number => VIMP problem can be solved using set,math,xor and cyclic sort (1st problem of sde sheet)
77.  Sort Colors => sorting will solve this issue but dutch national flag algo comes to rescue for linear soln with intitution and edge case(2nd problem of sde sheet)
78.  Pow(x,n) => recursive and iterative VIMP problem (13th problem from sde sheet)
79.  Add Binary => very simple problem it can be solved using mod by 2 and divide by 2
80.  Maximum Subarray => this problem can be solved using brute force but this is famous for DP+Greed+Kadane algorithm(4th problme of sde sheet)
81.  Merge Intervals => very simple implementation based problem (5th problem of sde sheet)
82.  Set Matrix Zeroes => very simple implementaion based row and col header problem(7th problem of sde sheet)
83.  Find the Duplicate Number => freq table Or cyclic sort Or sorting Or tortoise and hare algo(cycle finding algo)(6th problem of sde sheet)
84.  integer to string => it is good example of use of % and / operator (asked in dolata capita,bombay)
