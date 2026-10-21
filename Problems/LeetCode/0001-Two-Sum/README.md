# Two Sum

- **Platform:** LeetCode
- **Problem Number:** 1
- **Difficulty:** Easy
- **Problem Link:** https://leetcode.com/problems/two-sum/
- **Language:** Java
- **Approach:** Brute Force

## Problem Description

Given an integer array `nums` and an integer `target`, return the indices of two distinct elements whose values add up to the target.

Each input is assumed to have exactly one valid solution, and the same element cannot be used twice.

## Approach: Brute Force

1. Iterate through the array using index `i`.
2. For each element, iterate through the remaining elements using index `j`, starting at `i + 1`.
3. If `nums[i] + nums[j] == target`, return the two indices.
4. If no pair is found, return an empty array.

## Complexity Analysis

- **Time Complexity:** O(n²), because two nested loops may examine every pair of elements.
- **Auxiliary Space Complexity:** O(1), excluding the returned output array.

## Key Learning

Nested loops can be used to check every possible pair. This approach is straightforward but can be improved using a HashMap to achieve O(n) expected time complexity.

## Status

Solved using the brute-force approach.