# 1. Two Sum

**Problem Link:** [Two Sum — LeetCode](https://leetcode.com/problems/two-sum/)

## Problem Description

You are given an array of integers `nums` and an integer `target`. Return the **indices of the two numbers** such that they add up to `target`.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

## Examples

### Example 1

**Input:**
```text
nums = [2, 7, 11, 15]
target = 9
```

**Output:**
```text
[0, 1]
```

**Explanation:**

The sum of `nums[0]` and `nums[1]` is `2 + 7 = 9`, which equals the target. Therefore, the indices `[0, 1]` are returned.

### Example 2

**Input:**
```text
nums = [3, 2, 4]
target = 6
```

**Output:**
```text
[1, 2]
```

**Explanation:**

The sum of `nums[1]` and `nums[2]` is `2 + 4 = 6`, which equals the target. Therefore, the indices `[1, 2]` are returned.

### Example 3

**Input:**
```text
nums = [3, 3]
target = 6
```

**Output:**
```text
[0, 1]
```

**Explanation:**

The sum of `nums[0]` and `nums[1]` is `3 + 3 = 6`, which equals the target. Therefore, the indices `[0, 1]` are returned.

## Constraints

- `2 <= nums.length <= 10^4`
- `-10^9 <= nums[i] <= 10^9`
- `-10^9 <= target <= 10^9`
- Only one valid answer exists.

