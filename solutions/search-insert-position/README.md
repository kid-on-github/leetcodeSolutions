# Search Insert Position

Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.

You must&nbsp;write an algorithm with&nbsp;<code>O(log n)</code> runtime complexity.


**Example 1:**
>
> **Input:** nums = [1,3,5,6], target = 5
>
> **Output:** 2

**Example 2:**
>
> **Input:** nums = [1,3,5,6], target = 2
>
> **Output:** 1

**Example 3:**
>
> **Input:** nums = [1,3,5,6], target = 7
>
> **Output:** 4


**Constraints:**

- <code>1 &lt;= nums.length &lt;= 10<sup>4</sup></code>

- <code>-10<sup>4</sup> &lt;= nums[i] &lt;= 10<sup>4</sup></code>

- <code>nums</code> contains **distinct** values sorted in **ascending** order.

- <code>-10<sup>4</sup> &lt;= target &lt;= 10<sup>4</sup></code>
