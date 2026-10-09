# Code Exercises

My solutions to coding exercises, grouped by platform. Files use the problem number when the platform provides one, followed by the problem name.

## Included solutions

| Problem | Language | Solution | Behavior |
| --- | --- | --- | --- |
| [1. Two Sum](https://leetcode.com/problems/two-sum/) | Python | [1-two-sum.py](LeetCode/1-two-sum.py) | Returns the zero-based indices of two distinct elements whose sum is the target. Uses a hash map for expected O(n) time and O(n) space. |
| [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | C# | [2-add-two-numbers.cs](LeetCode/2-add-two-numbers.cs) | Adds numbers represented by linked lists with digits in reverse order, including a final carry. Uses O(max(m, n)) time and output space. |
| [704. Binary Search](https://leetcode.com/problems/binary-search/) | C# | [704-binary-search.cs](LeetCode/704-binary-search.cs) | Searches a sorted array in O(log n) time and O(1) space. Returns the zero-based index or -1 when the target is absent. |

## Using the solutions

Each file is an independent LeetCode submission. Select the corresponding language in the problem editor and paste the solution. The C# files both define `Solution`, so compile or submit them separately. LeetCode supplies the `ListNode` type used by `AddTwoNumbers`; a local harness must provide that type.

Two Sum assumes exactly one valid pair, as required by the problem. Its existing `(-1, -1)` fallback remains available for inputs without a pair. For example, `Solution().twoSum([2, 7, 11, 15], 9)` returns `(0, 1)`.

This repository contains submission snippets rather than a standalone application. It has no project files, third-party dependencies, or bundled test runner.

## Coding profiles

- [LeetCode](https://leetcode.com/tugcantopaloglu/)
- [HackerRank](https://www.hackerrank.com/topaloglutugcan)

The repository is a selection of solutions; a profile may contain exercises that are not included here.
