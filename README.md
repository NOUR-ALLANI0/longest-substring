# Longest Substring Without Repeating Characters (C)

## Problem
Given a string, find the length of the longest substring without repeating characters.

LeetCode reference:
https://leetcode.com/problems/longest-substring-without-repeating-characters/

## Real-life use case
This problem can model scenarios such as validating input streams,
analyzing logs, or finding the longest sequence of unique events.

## Approach
We use the sliding window technique.
Two pointers move over the string while an array tracks already seen characters.

## Time and Space Complexity
- Time complexity: O(n)
- Space complexity: O(1) (fixed ASCII array)

## How to compile and run tests
```bash
gcc longest_substring.c test_longest_substring.c -o test_program
./test_program