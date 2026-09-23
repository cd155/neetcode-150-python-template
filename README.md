# NeetCode 150 Python Solutions

A collection of solution templates for the "NeetCode 150" LeetCode problems in Python.

## 📚 Overview

This repository contains Python solution templates for the NeetCode 150 list - the Blind 75 plus 75 more LeetCode problems, curated by NeetCode to cover the most important patterns and concepts for technical interviews.

Each problem comes with:

- a solution file in `src/<category>/` with the full problem statement, a `TODO` stub, and example usage
- a test file in `tests/` built from the problem's examples (the tests fail until you implement the solution)

## 🗂️ Structure

Solutions are organized by the [NeetCode 150](https://neetcode.io/practice/practice/neetcode150) categories:

```
src/
├── arrays_and_hashing/  # Arrays & Hashing (9)
├── two_pointers/        # Two Pointers (5)
├── sliding_window/      # Sliding Window (6)
├── stack/               # Stack (7)
├── binary_search/       # Binary Search (7)
├── linked_list/         # Linked List (11)
├── trees/               # Trees (15)
├── heap_priority_queue/ # Heap / Priority Queue (7)
├── backtracking/        # Backtracking (9)
├── tries/               # Tries (3)
├── graphs/              # Graphs (13)
├── advanced_graphs/     # Advanced Graphs (6)
├── dp_1d/               # 1-D Dynamic Programming (12)
├── dp_2d/               # 2-D Dynamic Programming (11)
├── greedy/              # Greedy (8)
├── intervals/           # Intervals (6)
├── math_and_geometry/   # Math & Geometry (8)
└── bit_manipulation/    # Bit Manipulation (7)
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/cd155/neetcode-150-python-template.git
cd neetcode-150-python-template

# Create python virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Running Tests

```bash
# Run all tests
pytest

# Run tests for a specific problem
pytest tests/test_contains_duplicate.py

# Run tests for every problem whose name matches a keyword
pytest -k "linked_list"
```

### Running Individual Solutions

Each solution file can be run independently:

```bash
python src/arrays_and_hashing/contains_duplicate.py
```

### Tracking Progress with GitHub Issues

The **Create NeetCode 150 Issues** workflow opens one issue per problem, labeled `neetcode-150` and
by category. Run it from the repository's **Actions** tab and type `yes` to confirm. Problems that
already have an issue are skipped, so it is safe to run again.

## 📝 Problem Categories

### Arrays & Hashing (9 problems)
- Contains Duplicate (Easy)
- Valid Anagram (Easy)
- Two Sum (Easy)
- Group Anagrams (Medium)
- Top K Frequent Elements (Medium)
- Product of Array Except Self (Medium)
- Valid Sudoku (Medium)
- Encode and Decode Strings (Medium)
- Longest Consecutive Sequence (Medium)

### Two Pointers (5 problems)
- Valid Palindrome (Easy)
- Two Sum II - Input Array Is Sorted (Medium)
- 3Sum (Medium)
- Container With Most Water (Medium)
- Trapping Rain Water (Hard)

### Sliding Window (6 problems)
- Best Time to Buy and Sell Stock (Easy)
- Longest Substring Without Repeating Characters (Medium)
- Longest Repeating Character Replacement (Medium)
- Permutation in String (Medium)
- Minimum Window Substring (Hard)
- Sliding Window Maximum (Hard)

### Stack (7 problems)
- Valid Parentheses (Easy)
- Min Stack (Medium)
- Evaluate Reverse Polish Notation (Medium)
- Generate Parentheses (Medium)
- Daily Temperatures (Medium)
- Car Fleet (Medium)
- Largest Rectangle in Histogram (Hard)

### Binary Search (7 problems)
- Binary Search (Easy)
- Search a 2D Matrix (Medium)
- Koko Eating Bananas (Medium)
- Find Minimum in Rotated Sorted Array (Medium)
- Search in Rotated Sorted Array (Medium)
- Time Based Key-Value Store (Medium)
- Median of Two Sorted Arrays (Hard)

### Linked List (11 problems)
- Reverse Linked List (Easy)
- Merge Two Sorted Lists (Easy)
- Reorder List (Medium)
- Remove Nth Node From End of List (Medium)
- Copy List with Random Pointer (Medium)
- Add Two Numbers (Medium)
- Linked List Cycle (Easy)
- Find the Duplicate Number (Medium)
- LRU Cache (Medium)
- Merge k Sorted Lists (Hard)
- Reverse Nodes in k-Group (Hard)

### Trees (15 problems)
- Invert Binary Tree (Easy)
- Maximum Depth of Binary Tree (Easy)
- Diameter of Binary Tree (Easy)
- Balanced Binary Tree (Easy)
- Same Tree (Easy)
- Subtree of Another Tree (Easy)
- Lowest Common Ancestor of a Binary Search Tree (Medium)
- Binary Tree Level Order Traversal (Medium)
- Binary Tree Right Side View (Medium)
- Count Good Nodes in Binary Tree (Medium)
- Validate Binary Search Tree (Medium)
- Kth Smallest Element in a BST (Medium)
- Construct Binary Tree from Preorder and Inorder Traversal (Medium)
- Binary Tree Maximum Path Sum (Hard)
- Serialize and Deserialize Binary Tree (Hard)

### Heap / Priority Queue (7 problems)
- Kth Largest Element in a Stream (Easy)
- Last Stone Weight (Easy)
- K Closest Points to Origin (Medium)
- Kth Largest Element in an Array (Medium)
- Task Scheduler (Medium)
- Design Twitter (Medium)
- Find Median from Data Stream (Hard)

### Backtracking (9 problems)
- Subsets (Medium)
- Combination Sum (Medium)
- Permutations (Medium)
- Subsets II (Medium)
- Combination Sum II (Medium)
- Word Search (Medium)
- Palindrome Partitioning (Medium)
- Letter Combinations of a Phone Number (Medium)
- N-Queens (Hard)

### Tries (3 problems)
- Implement Trie (Prefix Tree) (Medium)
- Design Add and Search Words Data Structure (Medium)
- Word Search II (Hard)

### Graphs (13 problems)
- Number of Islands (Medium)
- Clone Graph (Medium)
- Max Area of Island (Medium)
- Pacific Atlantic Water Flow (Medium)
- Surrounded Regions (Medium)
- Rotting Oranges (Medium)
- Walls and Gates (Medium)
- Course Schedule (Medium)
- Course Schedule II (Medium)
- Redundant Connection (Medium)
- Number of Connected Components in an Undirected Graph (Medium)
- Graph Valid Tree (Medium)
- Word Ladder (Hard)

### Advanced Graphs (6 problems)
- Reconstruct Itinerary (Hard)
- Min Cost to Connect All Points (Medium)
- Network Delay Time (Medium)
- Swim in Rising Water (Hard)
- Alien Dictionary (Hard)
- Cheapest Flights Within K Stops (Medium)

### 1-D Dynamic Programming (12 problems)
- Climbing Stairs (Easy)
- Min Cost Climbing Stairs (Easy)
- House Robber (Medium)
- House Robber II (Medium)
- Longest Palindromic Substring (Medium)
- Palindromic Substrings (Medium)
- Decode Ways (Medium)
- Coin Change (Medium)
- Maximum Product Subarray (Medium)
- Word Break (Medium)
- Longest Increasing Subsequence (Medium)
- Partition Equal Subset Sum (Medium)

### 2-D Dynamic Programming (11 problems)
- Unique Paths (Medium)
- Longest Common Subsequence (Medium)
- Best Time to Buy and Sell Stock with Cooldown (Medium)
- Coin Change II (Medium)
- Target Sum (Medium)
- Interleaving String (Medium)
- Longest Increasing Path in a Matrix (Hard)
- Distinct Subsequences (Hard)
- Edit Distance (Medium)
- Burst Balloons (Hard)
- Regular Expression Matching (Hard)

### Greedy (8 problems)
- Maximum Subarray (Medium)
- Jump Game (Medium)
- Jump Game II (Medium)
- Gas Station (Medium)
- Hand of Straights (Medium)
- Merge Triplets to Form Target Triplet (Medium)
- Partition Labels (Medium)
- Valid Parenthesis String (Medium)

### Intervals (6 problems)
- Insert Interval (Medium)
- Merge Intervals (Medium)
- Non-overlapping Intervals (Medium)
- Meeting Rooms (Easy)
- Meeting Rooms II (Medium)
- Minimum Interval to Include Each Query (Hard)

### Math & Geometry (8 problems)
- Rotate Image (Medium)
- Spiral Matrix (Medium)
- Set Matrix Zeroes (Medium)
- Happy Number (Easy)
- Plus One (Easy)
- Pow(x, n) (Medium)
- Multiply Strings (Medium)
- Detect Squares (Medium)

### Bit Manipulation (7 problems)
- Single Number (Easy)
- Number of 1 Bits (Easy)
- Counting Bits (Easy)
- Reverse Bits (Easy)
- Missing Number (Easy)
- Sum of Two Integers (Medium)
- Reverse Integer (Medium)

## 🔗 Resources

- [NeetCode 150](https://neetcode.io/practice/practice/neetcode150) - Category roadmap and video explanations
- [LeetCode](https://leetcode.com/)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
