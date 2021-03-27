# Awesome Competitive Programming Problems

This repository contains my implementation of **useful / well-known data structures, algorithms and solutions** for awesome competitive programming problems in **Hackerrank, Project Euler and Leetcode**

I create this for faster implementation and better preparation in interviews as well as programming contests

Written in Python 3 by Le Duc Khai 

<p align="center"> 
      <img src="https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Hackerrank%20Top%20Germany.jpg" width="400"> 
</p>

How to use
----------
- [x] : Useful / well-known data structures or algorithms

- [ ] : Solutions for some awesome competitive programming problems

**Mathematics** : Type of the Algorithm

**Permutation Problems** : Category of the Problem

[Lexicographic Permutations](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lexicographic_Permutations.ipynb) : Name of the problem

```
Awesome-Competitive-Programming 
│   README.md 
│
└───Folder 1        : Type of Algorithm 
│   │   File1.ipynb : Python codes for the problem
│   │   ...   
│   
└───Folder 2
│   │   File2.ipynb
│   │   ...
│     
└───Folder Data Bank: Descriptions and Solution Guides for the Problem 
│   │   File1.pdf
│   │   ...
│
└───...    
```

Algorithms
----------
### A) Data Structures Applications
#### Binary Search Tree Algorithm
1. - [x] [Binary Search Tree](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Structures%20Applications/BST.ipynb): Original Binary Search Tree Algorithm - **O(log(n))**

2. - [x] [Binary Search Tree: Check a Number](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Structures%20Applications/BST_Find.ipynb): Check if a Number is in a Sorted List using BST Algorithm - **O(log(n))**

3. - [x] [Binary Search Tree: Index of a Number](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Structures%20Applications/BST_Find_Index.ipynb): Find the Index of a Number in a Sorted List using BST Algorithm - **O(log(n))**

### B) String Algorithm
#### Suffix Tree - Suffix Array
1. - [x] [Suffix Array (Manber-Myers Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/String%20Algorithm/SuffixArray_ManberMyers.ipynb): Find suffix array of a string S based on Manber-Myers algorithm - **O(n.log(n))** , n = |S|

2. - [x] [Longest Common Prefix Array (Kasai Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/String%20Algorithm/LCPArray_Kasai.ipynb): Find longest common prefix array of a string S with the help of suffix array based on Kasai algorithm - **O(n)** , n = |S|

3. - [x] Longest Palindromic Substring - (O(n)) **(Đang cập nhật)**

4. - [x] Pattern Search - O(log(n)) **(Đang cập nhật)**

### C) Searching and Graph Algorithms
#### Graph Theory
1. - [x] [Graph Representation using Adjacency List: Unweighted, Un-/Directed](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Graph_AdjacencyList.ipynb): Create a Unweighted Un-/Directed Graph using Adjacency List

2. - [x] Graph Representation using Adjacency List: Weighted, Un-/Directed **(Đang cập nhật)**

3. - [x] [Find All Nodes](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Find_AllNodes.ipynb): Find All Nodes in the Unweighted Graph - **O(V+E) for Adjacency List** , V, E is the number of vertices and edges

4. - [x] Find All Edges **(Đang cập nhật)**

5. - [x] [Find All Paths between 2 Nodes](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/Find_AllPaths_BFS.ipynb): Find All Paths between 2 Nodes in a Unweighted Graph using BFS - **NP-Hard** 

6. - [x] [Disjoint Set (Union-Find): Union by Rank and Path Compression](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/DisjointSet.ipynb): Create a Disjoint Set (Union-Find) using "Union by Rank and Path Compression" for an Undirected Graph (used to Detect Cycle) - **Time = O(small constant), Space = O(V)**

#### Detect Cycle
7. - [x] [Detect Cycle: Disjoint Set](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/isCycle_DisjointSet.ipynb): Detect Cycle in an Undirected Graph based on Disjoint Set (Union-Find) using "Union by Rank and Path Compression" - **O(V)**

#### Graph Traversal
8. - [x] [Breadth-First Search](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/BFS.ipynb): Find BFS Path from a Starting Node in Un-/Directed Graph - **O(V+E) for Adjacency List; O(V<sup>2</sup>) for Adjacency Matrix** , V, E is the number of vertices and edges

9. - [x] [Depth-First Search](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/DFS.ipynb): Find DFS Path from a Starting Node in Un-/Directed Graph - **O(V+E) for Adjacency List; O(V<sup>2</sup>) for Adjacency Matrix** , V, E is the number of vertices and edges

#### Minimum Spanning Tree (MST)
10. - [x] [MST: Prim Algorithm](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/MST_Prim.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/MST_Prim.pdf)</sup>: Find Minimum Spanning Tree (MST) of an Undirected Graph using Prim Algorithm - **O(E.log(V))**

11. - [x] [MST: Kruskal Algorithm](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/MST_Kruskal.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/MST_Kruskal.pdf)</sup>: Find Minimum Spanning Tree (MST) of an Undirected Graph using Kruskal Algorithm - **O(E.log(E)) or O(E.log(V))**

#### Shortest Path 
      
| Type of Algorithm    | Subjects of Application                      | Time Complexity                    |
| :---:                | :---:                                        | :---:                              |
| Breadth-First Search | Unweighted, Un-/Directed Graph               | O(V+E) for Adjacency List          |
| Dijkstra             | Non-Negative Un-/Weighted Un-/Directed Graph | O(E.log(V)) for Min-priority Queue |
| Bellman-Ford         |                                              |                                    |
| Floyd-Warshall       |                                              |                                    |
 
12. - [x] [Shortest Path: Breadth-First Search](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/SP_BFS.ipynb): Find the Shortest Path in a Unweighted Un-/Directed Graph based on BFS - **O(V+E) for Adjacency List** , V, E is the number of vertices and edges

13. - [x] [Shortest Path: Dijkstra using Min-Heap](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Searching%20and%20Graph%20Algorithms/SP_Dijkstra_MinHeap.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/SP_Dijkstra_MinHeap.pdf)</sup>: Find Shortest Path of an Non-Negative Un-/Weighted Un-/Directed Graph based on Dijkstra Algorithm using Min-Heap - **O(E.log(V))**

14. - [x] Shortest Path: Bellman-Ford **(Đang cập nhật)**

15. - [x] Shortest Path: Floyd-Warshall **(Đang cập nhật)**

### D) Greedy Algorithm
1. [Sherlock and The Beast](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Greedy%20Algorithm/Sherlock_and_The_Beast.ipynb)
- Find the "Decent Number" having n Digits ("Decent Number" has its digits to be only 3's and/or 5's; the number of 3's it contains is divisible by 5; the number of 5's it contains is divisible by 3; and it is the largest such number for its length)

2. [Largest Permutation](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Greedy%20Algorithm/Largest_Permutation.ipynb)
- Swap 2 digits of a number k times to get largest number - **O(n)**

### E) Dynamic Programming
#### Coin Change Algorithms
> Given an array of choices, every choice is picked **unlimited times**

1. - [x] [Coin Change](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/CoinChange.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Coin%20Change.pdf)</sup>: How many ways to pay V money using C coins [C1,C2,...Cn] - **O(C.V)**

2. - [x] [Integer Partition](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/IntegerPartition.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Integer_Partition.pdf)</sup>: How many ways to partition number N using [1,2,...N] numbers - **O(n<sup>1.5</sup>)**

3. - [x] [Minimum Coin Change](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/MinCoinChange.ipynb): Find Minimum Number of Coins to pay V money using C coins [C1,C2,...,Cn] - **O(C.V)**

#### Knapsack Problems
> Given an array of choices, every choice is picked **only once**

4. - [x] [Knapsack 0/1](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Knapsack_01.ipynb)<sup>[[Wiki]](https://en.wikipedia.org/wiki/Knapsack_problem#0-1_knapsack_problem)</sup>: Given a List of Weights associated with their Values, find the Founding Weights and Maximum Total Value attained with its Total Weight <= Given Total Weight, each Weight is only **picked once** (0/1 Rule)  - **O(N.W)** , N, W is length of weights array and given total weight 

5. - [x] [Partition Problem: Subset Sum](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/PartitionProblem_SubsetSum.ipynb)<sup>[[Wiki]](https://en.wikipedia.org/wiki/Subset_sum_problem)</sup>: Given an Array containing only Positive Integers, find if it can be Partitioned into 2 Subsets having Sum of elements in both subsets is Equal.  - **O(N.T)** , N, T is the length of numbers array and the target sum (=sum/2)

6. - [x] [Partition Problem: Multiway Number Partitioning]()<sup>[[Wiki]]()</sup>: ______________________________

#### Path Sum Problems
7. - [x] [Max Path Sum Triangle](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Max_PathSum_Triangle.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Max_PathSum_Triangle.pdf)</sup>: Find Maximum Path Sum from Top to Bottom of a Triangle - **O(R)** , R is number of rows of the triangle

8. - [x] [Min Path Sum Matrix: Top-Left to Right-Bottom, Right and Down Moves](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Min_PathSum_Matrix.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Min_PathSum_Matrix.pdf)</sup>: Find Min Path Sum from Top-Left to Right-Bottom of a Matrix using Right and Down Moves - **O(R.C)** , R, C is length of row and column of the matrix

#### Subarray/Subsequence/Substring Problems

> Subsequence = Any subset of an array/string 
>
> Subarray = Contiguous subsequence of an array
>
> Substring = Contiguous subsequence of a string

9. - [x] [Max Subarray Sum (Kadane Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Max_SubarraySum.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Max_SubarraySum.pdf)</sup>: Find Maximum Subarray Sum of an Array - **O(n)**

10. - [x] [Min Subarray Sum (Kadane Algorithm's Varient)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Min_SubarraySum.ipynb): Find Minimum Subarray Sum of an Array - **O(n)**

11. - [x] [Longest Common Subsequence (LCS)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/LongestCommonSubsequence.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/LongestCommonSubsequence.pdf)</sup>: Find the longest string S, every character in S is also in S1 and S2 but in order - **O(|S1|.|S2|)**

12. - [x] [Longest Increasing/Decreasing Subsequence (Patience Sorting Algorithm)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Longest_Increasing_Subsequence.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Longest_Increasing_Subsequence.pdf)</sup>: Find the Longest Increasing or Decreasing Subsequence of an Array List based on Patience Sorting Algorithm- **O(n.log(n))**

13. - [x] [Longest Common Substring (Longest Common Factor - LCF)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/Longest_Common_Substring.ipynb): Find the Longest Common Substring (Factor) of 2 strings S1 and S2 - **O(|S1|.|S2|)** 

14. - [x] [Sum Of Substrings](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Dynamic%20Programming/SumOfSubstrings.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/SumOfSubstrings.pdf)</sup>: Find Sum of All Substrings of an Number String S - **O(|S|)**

### F) Mathematics
#### Binomial Coefficient Problems
1. - [x] [Pascal Triangle](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Pascal_Triangle.ipynb): Create Pascal Triangle (to Calculate Multiple Large-Number Combinations) - **O(n<sup>2</sup>)**

2. - [ ] [PE #15: Lattice Paths](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lattice_Paths.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Lattice_Paths.pdf)</sup> : Find the number of routes from the top left corner to the bottom right corner in a rectangular grid

#### Factors Problems
3. - [x] [Factorization](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Factorization.ipynb): Find All Factors of a Number - **O(n<sup>1/2</sup>)**

#### Multiples Problems
4. - [ ] [PE #1: Multiples of 3 and 5](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Multiples_of_3_and_5.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Multiples_of_3_and_5.pdf)</sup>: Find Sum of Multiples of a Number - **O(1)**

#### Permutation Problems
5. - [x] [Lexicographic Permutations](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Lexicographic_Permutations.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Lexicographic_Permutations.pdf)</sup>: Find n-th Lexicographic Permutation of a very long Word - **O(n)**

6. - [x] [Permutation Check](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/arePermutations.ipynb): Check if 2 Numbers/Strings are Permutations - **O(n)** , n = max(|a|,|b|)

#### Primes Problems
7. - [x] ["Sieve Method" All Primes](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Sieve_All_Primes.ipynb): Find All Primes < n - **O(n<sup>1/2</sup>)**

8. - [x] [Primality Test (Common Method)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/isPrime.ipynb): Check if n is a Prime Number using "Common Method" - **O(n<sup>1/2</sup>)**

9. - [x] [Primality Test (Miller-Rabin)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/isPrime_Miller_Rabin.ipynb): Check if n is a Prime Number using Miller-Rabin Probabilistic Test - **O(k.log<sup>3</sup>n)** , k = \[1,2,...]

10. - [x] [Coprimes Check](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/areCoprimes.ipynb): Check if 2 Numbers are Coprime - **O(log a.b)**

#### Primes-Factors Problems
11. - [x] [Euler Totient Function (Number List)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Euler_Totient_NumList.ipynb): Find ALL Numbers of Coprimes < n based on Euler Totient Function - **O((l) + m.loglogm + l.(logm + k))** , k is the number of prime factors of n; m and l is max value and length of the input number list
      
12. - [x] [Euler Totient Function (Single Number)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Euler_Totient_SingleNum.ipynb): Find the Number of Coprimes < n based on Euler Totient Function - **O(n<sup>1/2</sup> + k)** , k is the number of prime factors of the input number n

13. - [x] ["Sieve Method" Smallest Prime Factors (SPF)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Sieve_SPF.ipynb): Find Smallest Prime Factors for All Numbers < N - **O(n.loglogn)** 
 
14. - [x] [Prime Factorization (Smallest Prime Factor)](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PrimeFactorization_SPF.ipynb): Find All Prime Factors of a Number using Smallest Prime Factor (SPF) - **O(log n)** if a list of all Smallest Prime Factors from 0 to n available

15. - [x] [Prime Factorization](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PrimeFactorization.ipynb): Find All Prime Factors of a Number - **O(n<sup>1/2</sup>)**

#### Pythagorean Theorem
16. - [x] [Pythagorean Triplets Perimeter](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PythagoreanTriplets_Perimeter.ipynb): Find Pythagorean Triplets having Perimeter (or Sum) P - **O(P)**

17. - [x] [Pythagorean Triplets Less or Equal N](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/PythagoreanTriplets_LessEqualN.ipynb): Generate all Pythagorean Triplets <= N - **O(N.log(N))**

#### Non-categorized
18. - [ ] [Number Spiral Diagonals](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Mathematics/Number_Spiral_Diagonals.ipynb)<sup>[[PDF]](https://github.com/leduckhai/Awesome-Competitive-Programming/blob/main/Data%20Bank/Number_Spiral_Diagonals.pdf)</sup>: Find Sum of Diagonals of Ulam Spiral Matrix

### Recursion Algorithm
#### Backtracking

#### Divide and Conquer

