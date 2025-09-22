# 0217 Contains Duplicate

## Problem
Given an array `nums`, return `true` if any value appears more than once.

[LeetCode link](https://leetcode.com/problems/contains-duplicate/)

---

## Approaches

### v1: List 探索 (O(n^2))
- Use a list to track seen elements
- Check `if n in list` -> O(n) each
- Overall: O(n^2)

### v2: HashSet　探索
- Use a hashSet for constant-time lookup
- `if n in set` -> O(1) each
- Overall: O(n)