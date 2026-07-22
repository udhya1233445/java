# LeetCode Solutions Collection

This repository contains my Java solutions for various LeetCode problems. These problems cover topics such as Arrays, Hashing, Dynamic Programming, Mathematics, Greedy Algorithms, and Searching techniques.

## Solved Problems

| Problem No. | Problem Name | Difficulty | Approach |
|-------------|--------------|------------|----------|
| 118 | Pascal's Triangle | Easy | Dynamic Programming |
| 135 | Candy | Hard | Greedy (Two Pass) |
| 136 | Single Number | Easy | Bit Manipulation (XOR) |
| 172 | Factorial Trailing Zeroes | Medium | Mathematics |
| 217 | Contains Duplicate | Easy | HashSet |
| 1103 | Distribute Candies to People | Easy | Simulation |
| 1217 | Minimum Cost to Move Chips to The Same Position | Easy | Greedy |
| 1295 | Find Numbers with Even Number of Digits | Easy | Math |
| 1688 | Count of Matches in Tournament | Easy | Observation |
| 1822 | Sign of the Product of an Array | Easy | Counting Negatives |
| 2001 | Number of Pairs of Interchangeable Rectangles | Medium | HashMap |
| 2011 | Final Value of Variable After Performing Operations | Easy | String Processing |
| 2285 | Maximum Total Importance of Roads | Medium | Sorting + Greedy |
| 2651 | Calculate Delayed Arrival Time | Easy | Modulo Arithmetic |
| Binary Search | Binary Search Implementation | Easy | Divide and Conquer |

---

## Topics Covered

- Arrays
- HashMap
- HashSet
- Dynamic Programming
- Greedy Algorithms
- Bit Manipulation
- Mathematics
- Sorting
- Simulation
- String Manipulation
- Binary Search

---

## Sample Solutions

### Single Number (136)
- Uses XOR operation.
- Duplicate numbers cancel each other.
- Time Complexity: `O(n)`
- Space Complexity: `O(1)`

### Contains Duplicate (217)
- Uses `HashSet` to detect duplicates efficiently.
- Time Complexity: `O(n)`
- Space Complexity: `O(n)`

### Candy (135)
- Uses a two-pass greedy approach:
  1. Traverse left to right.
  2. Traverse right to left.
- Ensures every child receives the minimum required candies.

### Pascal's Triangle (118)
- Builds each row using values from the previous row.
- Time Complexity: `O(n²)`

### Binary Search
- Searches an element in a sorted array.
- Time Complexity: `O(log n)`
- Space Complexity: `O(1)`

---

## Repository Structure

```text
├── PascalTriangle.java
├── Candy.java
├── SingleNumber.java
├── FactorialTrailingZeroes.java
├── ContainsDuplicate.java
├── DistributeCandiesToPeople.java
├── MinimumCostToMoveChips.java
├── FindNumbersWithEvenDigits.java
├── CountMatchesInTournament.java
├── SignOfProductArray.java
├── InterchangeableRectangles.java
├── FinalValueAfterOperations.java
├── MaximumImportanceOfRoads.java
├── CalculateDelayedArrivalTime.java
└── binary_search.java
