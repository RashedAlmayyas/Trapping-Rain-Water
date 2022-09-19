## Trapping Rain Water using php

https://leetcode.com/problems/trapping-rain-water/description/

## Problem Description

> Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it is able to trap after raining.

![42.trapping-rain-water-1](https://tva1.sinaimg.cn/large/007S8ZIlly1ghlu2p6pzfj30bg04hmx3.jpg)

> The above elevation map is represented by array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue section) are being trapped. Thanks Marcos for contributing this image!

```
Input: [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6
```

## Prerequisites

- Space-time tradeoff
- Two Pointers
- Monotonic Stack

## Two Arrays

### Solution

The difficulty of this problem is `hard`.
We'd like to compute how much water a given elevation map can trap.

A brute force solution would be adding up the maximum level of water that each element of the map can trap.
