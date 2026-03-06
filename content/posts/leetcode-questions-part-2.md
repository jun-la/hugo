+++
title = 'Leetcode Questions Part 2'
date = 2026-03-06T10:25:08-08:00
tags = ["leetcode"]
draft = false
+++

A curated list of 100 LeetCode problems for interview preparation with solution templates.

---

## Recommended Study Order

### 1. Array & Hashing - More advanced techniques
- [169. Majority Element](#169-majority-element-easy)
- [229. Majority Element II](#229-majority-element-ii-medium)
- [41. First Missing Positive](#41-first-missing-positive-hard)
- [442. Find All Duplicates in an Array](#442-find-all-duplicates-in-an-array-medium)
- [448. Find All Numbers Disappeared in an Array](#448-find-all-numbers-disappeared-in-an-array-easy)
- [645. Set Mismatch](#645-set-mismatch-easy)
- [274. H-Index](#274-h-index-medium)
- [380. Insert Delete GetRandom O(1)](#380-insert-delete-getrandom-o1-medium)
- [454. 4Sum II](#454-4sum-ii-medium)
- [334. Increasing Triplet Subsequence](#334-increasing-triplet-subsequence-medium)

### 2. Two Pointers - Complex scenarios
- [392. Is Subsequence](#392-is-subsequence-easy)
- [680. Valid Palindrome II](#680-valid-palindrome-ii-easy)
- [16. 3Sum Closest](#16-3sum-closest-medium)
- [18. 4Sum](#18-4sum-medium)
- [75. Sort Colors](#75-sort-colors-medium)
- [844. Backspace String Compare](#844-backspace-string-compare-easy)
- [986. Interval List Intersections](#986-interval-list-intersections-medium)
- [633. Sum of Square Numbers](#633-sum-of-square-numbers-medium)

### 3. Sliding Window - Variable window problems
- [219. Contains Duplicate II](#219-contains-duplicate-ii-easy)
- [643. Maximum Average Subarray I](#643-maximum-average-subarray-i-easy)
- [1004. Max Consecutive Ones III](#1004-max-consecutive-ones-iii-medium)
- [1208. Get Equal Substrings Within Budget](#1208-get-equal-substrings-within-budget-medium)
- [904. Fruit Into Baskets](#904-fruit-into-baskets-medium)
- [1052. Grumpy Bookstore Owner](#1052-grumpy-bookstore-owner-medium)
- [1423. Maximum Points You Can Obtain from Cards](#1423-maximum-points-you-can-obtain-from-cards-medium)

### 4. Stack - Monotonic stack patterns
- [496. Next Greater Element I](#496-next-greater-element-i-easy)
- [503. Next Greater Element II](#503-next-greater-element-ii-medium)
- [84. Largest Rectangle in Histogram](#84-largest-rectangle-in-histogram-hard)
- [402. Remove K Digits](#402-remove-k-digits-medium)
- [456. 132 Pattern](#456-132-pattern-medium)
- [946. Validate Stack Sequences](#946-validate-stack-sequences-medium)
- [1249. Minimum Remove to Make Valid Parentheses](#1249-minimum-remove-to-make-valid-parentheses-medium)
- [1047. Remove All Adjacent Duplicates In String](#1047-remove-all-adjacent-duplicates-in-string-easy)

### 5. Binary Search - Search space problems
- [34. Find First and Last Position of Element in Sorted Array](#34-find-first-and-last-position-of-element-in-sorted-array-medium)
- [162. Find Peak Element](#162-find-peak-element-medium)
- [852. Peak Index in a Mountain Array](#852-peak-index-in-a-mountain-array-medium)
- [69. Sqrt(x)](#69-sqrtx-easy)
- [367. Valid Perfect Square](#367-valid-perfect-square-easy)
- [540. Single Element in a Sorted Array](#540-single-element-in-a-sorted-array-medium)
- [1011. Capacity To Ship Packages Within D Days](#1011-capacity-to-ship-packages-within-d-days-medium)
- [658. Find K Closest Elements](#658-find-k-closest-elements-medium)

### 6. Linked List - Complex operations
- [203. Remove Linked List Elements](#203-remove-linked-list-elements-easy)
- [83. Remove Duplicates from Sorted List](#83-remove-duplicates-from-sorted-list-easy)
- [82. Remove Duplicates from Sorted List II](#82-remove-duplicates-from-sorted-list-ii-medium)
- [24. Swap Nodes in Pairs](#24-swap-nodes-in-pairs-medium)
- [61. Rotate List](#61-rotate-list-medium)
- [86. Partition List](#86-partition-list-medium)
- [92. Reverse Linked List II](#92-reverse-linked-list-ii-medium)
- [328. Odd Even Linked List](#328-odd-even-linked-list-medium)

### 7. Trees - Path problems and traversals
- [94. Binary Tree Inorder Traversal](#94-binary-tree-inorder-traversal-easy)
- [144. Binary Tree Preorder Traversal](#144-binary-tree-preorder-traversal-easy)
- [145. Binary Tree Postorder Traversal](#145-binary-tree-postorder-traversal-easy)
- [101. Symmetric Tree](#101-symmetric-tree-easy)
- [111. Minimum Depth of Binary Tree](#111-minimum-depth-of-binary-tree-easy)
- [112. Path Sum](#112-path-sum-easy)
- [113. Path Sum II](#113-path-sum-ii-medium)
- [129. Sum Root to Leaf Numbers](#129-sum-root-to-leaf-numbers-medium)
- [236. Lowest Common Ancestor of a Binary Tree](#236-lowest-common-ancestor-of-a-binary-tree-medium)
- [437. Path Sum III](#437-path-sum-iii-medium)

### 8. Heap / Priority Queue - Top K and stream problems
- [347. Top K Frequent Elements](#347-top-k-frequent-elements-medium)
- [692. Top K Frequent Words](#692-top-k-frequent-words-medium)
- [378. Kth Smallest Element in a Sorted Matrix](#378-kth-smallest-element-in-a-sorted-matrix-medium)
- [767. Reorganize String](#767-reorganize-string-medium)
- [347. Top K Frequent Elements](#347-top-k-frequent-elements-medium)
- [295. Find Median from Data Stream](#295-find-median-from-data-stream-hard)

### 9. Backtracking - Constraint satisfaction
- [77. Combinations](#77-combinations-medium)
- [47. Permutations II](#47-permutations-ii-medium)
- [93. Restore IP Addresses](#93-restore-ip-addresses-medium)
- [216. Combination Sum III](#216-combination-sum-iii-medium)
- [784. Letter Case Permutation](#784-letter-case-permutation-medium)
- [1239. Maximum Length of a Concatenated String with Unique Characters](#1239-maximum-length-of-a-concatenated-string-with-unique-characters-medium)

### 10. Graphs - Connectivity and paths
- [797. All Paths From Source to Target](#797-all-paths-from-source-to-target-medium)
- [841. Keys and Rooms](#841-keys-and-rooms-medium)
- [547. Number of Provinces](#547-number-of-provinces-medium)
- [802. Find Eventual Safe States](#802-find-eventual-safe-states-medium)
- [1192. Critical Connections in a Network](#1192-critical-connections-in-a-network-hard)
- [785. Is Graph Bipartite?](#785-is-graph-bipartite-medium)
- [1254. Number of Closed Islands](#1254-number-of-closed-islands-medium)
- [1631. Path With Minimum Effort](#1631-path-with-minimum-effort-medium)

### 11. Dynamic Programming - Classic patterns
- [509. Fibonacci Number](#509-fibonacci-number-easy)
- [1137. N-th Tribonacci Number](#1137-n-th-tribonacci-number-easy)
- [64. Minimum Path Sum](#64-minimum-path-sum-medium)
- [120. Triangle](#120-triangle-medium)
- [279. Perfect Squares](#279-perfect-squares-medium)
- [343. Integer Break](#343-integer-break-medium)
- [377. Combination Sum IV](#377-combination-sum-iv-medium)
- [518. Coin Change II](#518-coin-change-ii-medium)
- [97. Interleaving String](#97-interleaving-string-medium)
- [516. Longest Palindromic Subsequence](#516-longest-palindromic-subsequence-medium)

### 12. Greedy - Local optimal decisions
- [455. Assign Cookies](#455-assign-cookies-easy)
- [860. Lemonade Change](#860-lemonade-change-easy)
- [134. Gas Station](#134-gas-station-medium)
- [763. Partition Labels](#763-partition-labels-medium)
- [45. Jump Game II](#45-jump-game-ii-medium)
- [1029. Two City Scheduling](#1029-two-city-scheduling-medium)

### 13. Math & Geometry - Number theory
- [7. Reverse Integer](#7-reverse-integer-medium)
- [9. Palindrome Number](#9-palindrome-number-easy)
- [12. Integer to Roman](#12-integer-to-roman-medium)
- [13. Roman to Integer](#13-roman-to-integer-easy)
- [29. Divide Two Integers](#29-divide-two-integers-medium)
- [31. Next Permutation](#31-next-permutation-medium)

### 14. Bit Manipulation - Binary operations
- [231. Power of Two](#231-power-of-two-easy)
- [342. Power of Four](#342-power-of-four-easy)
- [389. Find the Difference](#389-find-the-difference-easy)
- [461. Hamming Distance](#461-hamming-distance-easy)
- [476. Number Complement](#476-number-complement-easy)
- [137. Single Number II](#137-single-number-ii-medium)
- [260. Single Number III](#260-single-number-iii-medium)

---

## Array & Hashing

### 169. Majority Element (Easy)
[View Problem](https://leetcode.com/problems/majority-element/)
```python
def majorityElement(nums: list[int]) -> int:
    # Boyer-Moore Voting Algorithm - O(n) time, O(1) space
    candidate = None
    count = 0

    for num in nums:
        if count == 0:
            candidate = num
        count += 1 if num == candidate else -1

    return candidate
```

### 229. Majority Element II (Medium)
[View Problem](https://leetcode.com/problems/majority-element-ii/)
```python
def majorityElement(nums: list[int]) -> list[int]:
    # Boyer-Moore extended - O(n) time, O(1) space
    candidate1, candidate2 = None, None
    count1, count2 = 0, 0

    for num in nums:
        if num == candidate1:
            count1 += 1
        elif num == candidate2:
            count2 += 1
        elif count1 == 0:
            candidate1, count1 = num, 1
        elif count2 == 0:
            candidate2, count2 = num, 1
        else:
            count1 -= 1
            count2 -= 1

    # Verify candidates
    result = []
    for c in [candidate1, candidate2]:
        if nums.count(c) > len(nums) // 3:
            result.append(c)
    return result
```

### 41. First Missing Positive (Hard)
[View Problem](https://leetcode.com/problems/first-missing-positive/)
```python
def firstMissingPositive(nums: list[int]) -> int:
    # Cyclic sort - O(n) time, O(1) space
    n = len(nums)

    for i in range(n):
        while 1 <= nums[i] <= n and nums[nums[i] - 1] != nums[i]:
            nums[nums[i] - 1], nums[i] = nums[i], nums[nums[i] - 1]

    for i in range(n):
        if nums[i] != i + 1:
            return i + 1

    return n + 1
```

### 442. Find All Duplicates in an Array (Medium)
[View Problem](https://leetcode.com/problems/find-all-duplicates-in-an-array/)
```python
def findDuplicates(nums: list[int]) -> list[int]:
    # Mark visited by negating - O(n) time, O(1) space
    result = []

    for num in nums:
        idx = abs(num) - 1
        if nums[idx] < 0:
            result.append(abs(num))
        else:
            nums[idx] = -nums[idx]

    return result
```

### 448. Find All Numbers Disappeared in an Array (Easy)
[View Problem](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)
```python
def findDisappearedNumbers(nums: list[int]) -> list[int]:
    # Mark visited by negating - O(n) time, O(1) space
    for num in nums:
        idx = abs(num) - 1
        nums[idx] = -abs(nums[idx])

    return [i + 1 for i in range(len(nums)) if nums[i] > 0]
```

### 645. Set Mismatch (Easy)
[View Problem](https://leetcode.com/problems/set-mismatch/)
```python
def findErrorNums(nums: list[int]) -> list[int]:
    # Math approach - O(n) time, O(1) space
    n = len(nums)
    actual_sum = sum(nums)
    actual_sq_sum = sum(x * x for x in nums)
    expected_sum = n * (n + 1) // 2
    expected_sq_sum = n * (n + 1) * (2 * n + 1) // 6

    diff = expected_sum - actual_sum  # missing - duplicate
    sq_diff = expected_sq_sum - actual_sq_sum  # missing^2 - duplicate^2

    sum_both = sq_diff // diff  # missing + duplicate
    missing = (diff + sum_both) // 2
    duplicate = sum_both - missing

    return [duplicate, missing]
```

### 274. H-Index (Medium)
[View Problem](https://leetcode.com/problems/h-index/)
```python
def hIndex(citations: list[int]) -> int:
    # Counting sort - O(n) time, O(n) space
    n = len(citations)
    counts = [0] * (n + 1)

    for c in citations:
        counts[min(c, n)] += 1

    total = 0
    for i in range(n, -1, -1):
        total += counts[i]
        if total >= i:
            return i

    return 0
```

### 380. Insert Delete GetRandom O(1) (Medium)
[View Problem](https://leetcode.com/problems/insert-delete-getrandom-o1/)
```python
import random

class RandomizedSet:
    def __init__(self):
        self.val_to_idx = {}
        self.vals = []

    def insert(self, val: int) -> bool:
        if val in self.val_to_idx:
            return False
        self.val_to_idx[val] = len(self.vals)
        self.vals.append(val)
        return True

    def remove(self, val: int) -> bool:
        if val not in self.val_to_idx:
            return False
        idx = self.val_to_idx[val]
        last_val = self.vals[-1]
        self.vals[idx] = last_val
        self.val_to_idx[last_val] = idx
        self.vals.pop()
        del self.val_to_idx[val]
        return True

    def getRandom(self) -> int:
        return random.choice(self.vals)
```

### 454. 4Sum II (Medium)
[View Problem](https://leetcode.com/problems/4sum-ii/)
```python
def fourSumCount(nums1: list[int], nums2: list[int], nums3: list[int], nums4: list[int]) -> int:
    # Hash map - O(n^2) time, O(n^2) space
    from collections import Counter

    sum_ab = Counter(a + b for a in nums1 for b in nums2)
    return sum(sum_ab[-(c + d)] for c in nums3 for d in nums4)
```

### 334. Increasing Triplet Subsequence (Medium)
[View Problem](https://leetcode.com/problems/increasing-triplet-subsequence/)
```python
def increasingTriplet(nums: list[int]) -> bool:
    # Track two smallest - O(n) time, O(1) space
    first = second = float('inf')

    for num in nums:
        if num <= first:
            first = num
        elif num <= second:
            second = num
        else:
            return True

    return False
```

---

## Two Pointers

### 392. Is Subsequence (Easy)
[View Problem](https://leetcode.com/problems/is-subsequence/)
```python
def isSubsequence(s: str, t: str) -> bool:
    # Two pointers - O(n) time, O(1) space
    i, j = 0, 0

    while i < len(s) and j < len(t):
        if s[i] == t[j]:
            i += 1
        j += 1

    return i == len(s)
```

### 680. Valid Palindrome II (Easy)
[View Problem](https://leetcode.com/problems/valid-palindrome-ii/)
```python
def validPalindrome(s: str) -> bool:
    # Two pointers with one skip - O(n) time, O(1) space
    def is_palindrome(left, right):
        while left < right:
            if s[left] != s[right]:
                return False
            left += 1
            right -= 1
        return True

    left, right = 0, len(s) - 1
    while left < right:
        if s[left] != s[right]:
            return is_palindrome(left + 1, right) or is_palindrome(left, right - 1)
        left += 1
        right -= 1

    return True
```

### 16. 3Sum Closest (Medium)
[View Problem](https://leetcode.com/problems/3sum-closest/)
```python
def threeSumClosest(nums: list[int], target: int) -> int:
    # Sort + Two pointers - O(n^2) time, O(1) space
    nums.sort()
    closest = float('inf')

    for i in range(len(nums) - 2):
        left, right = i + 1, len(nums) - 1

        while left < right:
            total = nums[i] + nums[left] + nums[right]

            if abs(total - target) < abs(closest - target):
                closest = total

            if total < target:
                left += 1
            elif total > target:
                right -= 1
            else:
                return target

    return closest
```

### 18. 4Sum (Medium)
[View Problem](https://leetcode.com/problems/4sum/)
```python
def fourSum(nums: list[int], target: int) -> list[list[int]]:
    # Sort + Two pointers - O(n^3) time, O(1) space
    nums.sort()
    result = []
    n = len(nums)

    for i in range(n - 3):
        if i > 0 and nums[i] == nums[i - 1]:
            continue
        for j in range(i + 1, n - 2):
            if j > i + 1 and nums[j] == nums[j - 1]:
                continue

            left, right = j + 1, n - 1
            while left < right:
                total = nums[i] + nums[j] + nums[left] + nums[right]
                if total == target:
                    result.append([nums[i], nums[j], nums[left], nums[right]])
                    while left < right and nums[left] == nums[left + 1]:
                        left += 1
                    while left < right and nums[right] == nums[right - 1]:
                        right -= 1
                    left += 1
                    right -= 1
                elif total < target:
                    left += 1
                else:
                    right -= 1

    return result
```

### 75. Sort Colors (Medium)
[View Problem](https://leetcode.com/problems/sort-colors/)
```python
def sortColors(nums: list[int]) -> None:
    # Dutch National Flag - O(n) time, O(1) space
    low, mid, high = 0, 0, len(nums) - 1

    while mid <= high:
        if nums[mid] == 0:
            nums[low], nums[mid] = nums[mid], nums[low]
            low += 1
            mid += 1
        elif nums[mid] == 1:
            mid += 1
        else:
            nums[mid], nums[high] = nums[high], nums[mid]
            high -= 1
```

### 844. Backspace String Compare (Easy)
[View Problem](https://leetcode.com/problems/backspace-string-compare/)
```python
def backspaceCompare(s: str, t: str) -> bool:
    # Two pointers from end - O(n) time, O(1) space
    def next_valid_char(string, idx):
        skip = 0
        while idx >= 0:
            if string[idx] == '#':
                skip += 1
            elif skip > 0:
                skip -= 1
            else:
                break
            idx -= 1
        return idx

    i, j = len(s) - 1, len(t) - 1

    while i >= 0 or j >= 0:
        i = next_valid_char(s, i)
        j = next_valid_char(t, j)

        if i >= 0 and j >= 0 and s[i] != t[j]:
            return False
        if (i >= 0) != (j >= 0):
            return False

        i -= 1
        j -= 1

    return True
```

### 986. Interval List Intersections (Medium)
[View Problem](https://leetcode.com/problems/interval-list-intersections/)
```python
def intervalIntersection(firstList: list[list[int]], secondList: list[list[int]]) -> list[list[int]]:
    # Two pointers - O(m+n) time, O(1) space
    result = []
    i, j = 0, 0

    while i < len(firstList) and j < len(secondList):
        start = max(firstList[i][0], secondList[j][0])
        end = min(firstList[i][1], secondList[j][1])

        if start <= end:
            result.append([start, end])

        if firstList[i][1] < secondList[j][1]:
            i += 1
        else:
            j += 1

    return result
```

### 633. Sum of Square Numbers (Medium)
[View Problem](https://leetcode.com/problems/sum-of-square-numbers/)
```python
def judgeSquareSum(c: int) -> bool:
    # Two pointers - O(sqrt(c)) time, O(1) space
    import math

    left, right = 0, int(math.sqrt(c))

    while left <= right:
        total = left * left + right * right
        if total == c:
            return True
        elif total < c:
            left += 1
        else:
            right -= 1

    return False
```

---

## Sliding Window

### 219. Contains Duplicate II (Easy)
[View Problem](https://leetcode.com/problems/contains-duplicate-ii/)
```python
def containsNearbyDuplicate(nums: list[int], k: int) -> bool:
    # Sliding window with set - O(n) time, O(k) space
    window = set()

    for i, num in enumerate(nums):
        if num in window:
            return True
        window.add(num)
        if len(window) > k:
            window.remove(nums[i - k])

    return False
```

### 643. Maximum Average Subarray I (Easy)
[View Problem](https://leetcode.com/problems/maximum-average-subarray-i/)
```python
def findMaxAverage(nums: list[int], k: int) -> float:
    # Sliding window - O(n) time, O(1) space
    window_sum = sum(nums[:k])
    max_sum = window_sum

    for i in range(k, len(nums)):
        window_sum += nums[i] - nums[i - k]
        max_sum = max(max_sum, window_sum)

    return max_sum / k
```

### 1004. Max Consecutive Ones III (Medium)
[View Problem](https://leetcode.com/problems/max-consecutive-ones-iii/)
```python
def longestOnes(nums: list[int], k: int) -> int:
    # Sliding window - O(n) time, O(1) space
    left = 0
    zeros = 0
    max_len = 0

    for right in range(len(nums)):
        if nums[right] == 0:
            zeros += 1

        while zeros > k:
            if nums[left] == 0:
                zeros -= 1
            left += 1

        max_len = max(max_len, right - left + 1)

    return max_len
```

### 1208. Get Equal Substrings Within Budget (Medium)
[View Problem](https://leetcode.com/problems/get-equal-substrings-within-budget/)
```python
def equalSubstring(s: str, t: str, maxCost: int) -> int:
    # Sliding window - O(n) time, O(1) space
    left = 0
    current_cost = 0
    max_len = 0

    for right in range(len(s)):
        current_cost += abs(ord(s[right]) - ord(t[right]))

        while current_cost > maxCost:
            current_cost -= abs(ord(s[left]) - ord(t[left]))
            left += 1

        max_len = max(max_len, right - left + 1)

    return max_len
```

### 904. Fruit Into Baskets (Medium)
[View Problem](https://leetcode.com/problems/fruit-into-baskets/)
```python
def totalFruit(fruits: list[int]) -> int:
    # Sliding window with at most 2 types - O(n) time, O(1) space
    from collections import defaultdict

    count = defaultdict(int)
    left = 0
    max_len = 0

    for right in range(len(fruits)):
        count[fruits[right]] += 1

        while len(count) > 2:
            count[fruits[left]] -= 1
            if count[fruits[left]] == 0:
                del count[fruits[left]]
            left += 1

        max_len = max(max_len, right - left + 1)

    return max_len
```

### 1052. Grumpy Bookstore Owner (Medium)
[View Problem](https://leetcode.com/problems/grumpy-bookstore-owner/)
```python
def maxSatisfied(customers: list[int], grumpy: list[int], minutes: int) -> int:
    # Sliding window - O(n) time, O(1) space
    base_satisfaction = sum(c for c, g in zip(customers, grumpy) if g == 0)

    # Find max additional satisfaction in window
    window_extra = sum(customers[i] * grumpy[i] for i in range(minutes))
    max_extra = window_extra

    for i in range(minutes, len(customers)):
        window_extra += customers[i] * grumpy[i]
        window_extra -= customers[i - minutes] * grumpy[i - minutes]
        max_extra = max(max_extra, window_extra)

    return base_satisfaction + max_extra
```

### 1423. Maximum Points You Can Obtain from Cards (Medium)
[View Problem](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/)
```python
def maxScore(cardPoints: list[int], k: int) -> int:
    # Sliding window (min subarray) - O(n) time, O(1) space
    n = len(cardPoints)
    window_size = n - k
    total = sum(cardPoints)

    if window_size == 0:
        return total

    window_sum = sum(cardPoints[:window_size])
    min_sum = window_sum

    for i in range(window_size, n):
        window_sum += cardPoints[i] - cardPoints[i - window_size]
        min_sum = min(min_sum, window_sum)

    return total - min_sum
```

---

## Stack

### 496. Next Greater Element I (Easy)
[View Problem](https://leetcode.com/problems/next-greater-element-i/)
```python
def nextGreaterElement(nums1: list[int], nums2: list[int]) -> list[int]:
    # Monotonic stack - O(n) time, O(n) space
    next_greater = {}
    stack = []

    for num in nums2:
        while stack and stack[-1] < num:
            next_greater[stack.pop()] = num
        stack.append(num)

    return [next_greater.get(num, -1) for num in nums1]
```

### 503. Next Greater Element II (Medium)
[View Problem](https://leetcode.com/problems/next-greater-element-ii/)
```python
def nextGreaterElements(nums: list[int]) -> list[int]:
    # Monotonic stack with circular - O(n) time, O(n) space
    n = len(nums)
    result = [-1] * n
    stack = []

    for i in range(2 * n):
        while stack and nums[stack[-1]] < nums[i % n]:
            result[stack.pop()] = nums[i % n]
        if i < n:
            stack.append(i)

    return result
```

### 84. Largest Rectangle in Histogram (Hard)
[View Problem](https://leetcode.com/problems/largest-rectangle-in-histogram/)
```python
def largestRectangleArea(heights: list[int]) -> int:
    # Monotonic stack - O(n) time, O(n) space
    stack = [-1]
    max_area = 0

    for i, h in enumerate(heights):
        while stack[-1] != -1 and heights[stack[-1]] >= h:
            height = heights[stack.pop()]
            width = i - stack[-1] - 1
            max_area = max(max_area, height * width)
        stack.append(i)

    while stack[-1] != -1:
        height = heights[stack.pop()]
        width = len(heights) - stack[-1] - 1
        max_area = max(max_area, height * width)

    return max_area
```

### 402. Remove K Digits (Medium)
[View Problem](https://leetcode.com/problems/remove-k-digits/)
```python
def removeKdigits(num: str, k: int) -> str:
    # Monotonic stack - O(n) time, O(n) space
    stack = []

    for digit in num:
        while k and stack and stack[-1] > digit:
            stack.pop()
            k -= 1
        stack.append(digit)

    # Remove remaining k digits from end
    stack = stack[:-k] if k else stack

    return ''.join(stack).lstrip('0') or '0'
```

### 456. 132 Pattern (Medium)
[View Problem](https://leetcode.com/problems/132-pattern/)
```python
def find132pattern(nums: list[int]) -> bool:
    # Monotonic stack from right - O(n) time, O(n) space
    stack = []
    s3 = float('-inf')  # The middle element (s2 > s3)

    for i in range(len(nums) - 1, -1, -1):
        if nums[i] < s3:
            return True
        while stack and stack[-1] < nums[i]:
            s3 = stack.pop()
        stack.append(nums[i])

    return False
```

### 946. Validate Stack Sequences (Medium)
[View Problem](https://leetcode.com/problems/validate-stack-sequences/)
```python
def validateStackSequences(pushed: list[int], popped: list[int]) -> bool:
    # Simulate stack - O(n) time, O(n) space
    stack = []
    j = 0

    for num in pushed:
        stack.append(num)
        while stack and stack[-1] == popped[j]:
            stack.pop()
            j += 1

    return len(stack) == 0
```

### 1249. Minimum Remove to Make Valid Parentheses (Medium)
[View Problem](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/)
```python
def minRemoveToMakeValid(s: str) -> str:
    # Stack for indices - O(n) time, O(n) space
    to_remove = set()
    stack = []

    for i, char in enumerate(s):
        if char == '(':
            stack.append(i)
        elif char == ')':
            if stack:
                stack.pop()
            else:
                to_remove.add(i)

    to_remove.update(stack)
    return ''.join(c for i, c in enumerate(s) if i not in to_remove)
```

### 1047. Remove All Adjacent Duplicates In String (Easy)
[View Problem](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
```python
def removeDuplicates(s: str) -> str:
    # Stack - O(n) time, O(n) space
    stack = []

    for char in s:
        if stack and stack[-1] == char:
            stack.pop()
        else:
            stack.append(char)

    return ''.join(stack)
```

---

## Binary Search

### 34. Find First and Last Position of Element in Sorted Array (Medium)
[View Problem](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
```python
def searchRange(nums: list[int], target: int) -> list[int]:
    # Two binary searches - O(log n) time, O(1) space
    def find_left():
        left, right = 0, len(nums) - 1
        while left <= right:
            mid = (left + right) // 2
            if nums[mid] < target:
                left = mid + 1
            else:
                right = mid - 1
        return left

    def find_right():
        left, right = 0, len(nums) - 1
        while left <= right:
            mid = (left + right) // 2
            if nums[mid] <= target:
                left = mid + 1
            else:
                right = mid - 1
        return right

    left_idx = find_left()
    right_idx = find_right()

    if left_idx <= right_idx:
        return [left_idx, right_idx]
    return [-1, -1]
```

### 162. Find Peak Element (Medium)
[View Problem](https://leetcode.com/problems/find-peak-element/)
```python
def findPeakElement(nums: list[int]) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left < right:
        mid = (left + right) // 2
        if nums[mid] > nums[mid + 1]:
            right = mid
        else:
            left = mid + 1

    return left
```

### 852. Peak Index in a Mountain Array (Medium)
[View Problem](https://leetcode.com/problems/peak-index-in-a-mountain-array/)
```python
def peakIndexInMountainArray(arr: list[int]) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(arr) - 1

    while left < right:
        mid = (left + right) // 2
        if arr[mid] < arr[mid + 1]:
            left = mid + 1
        else:
            right = mid

    return left
```

### 69. Sqrt(x) (Easy)
[View Problem](https://leetcode.com/problems/sqrtx/)
```python
def mySqrt(x: int) -> int:
    # Binary search - O(log x) time, O(1) space
    if x < 2:
        return x

    left, right = 1, x // 2

    while left <= right:
        mid = (left + right) // 2
        if mid * mid == x:
            return mid
        elif mid * mid < x:
            left = mid + 1
        else:
            right = mid - 1

    return right
```

### 367. Valid Perfect Square (Easy)
[View Problem](https://leetcode.com/problems/valid-perfect-square/)
```python
def isPerfectSquare(num: int) -> bool:
    # Binary search - O(log n) time, O(1) space
    left, right = 1, num

    while left <= right:
        mid = (left + right) // 2
        square = mid * mid
        if square == num:
            return True
        elif square < num:
            left = mid + 1
        else:
            right = mid - 1

    return False
```

### 540. Single Element in a Sorted Array (Medium)
[View Problem](https://leetcode.com/problems/single-element-in-a-sorted-array/)
```python
def singleNonDuplicate(nums: list[int]) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left < right:
        mid = (left + right) // 2
        # Ensure mid is even for pair comparison
        if mid % 2 == 1:
            mid -= 1

        if nums[mid] == nums[mid + 1]:
            left = mid + 2
        else:
            right = mid

    return nums[left]
```

### 1011. Capacity To Ship Packages Within D Days (Medium)
[View Problem](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)
```python
def shipWithinDays(weights: list[int], days: int) -> int:
    # Binary search on capacity - O(n log sum) time, O(1) space
    def can_ship(capacity):
        current = 0
        required_days = 1
        for w in weights:
            if current + w > capacity:
                required_days += 1
                current = 0
            current += w
        return required_days <= days

    left, right = max(weights), sum(weights)

    while left < right:
        mid = (left + right) // 2
        if can_ship(mid):
            right = mid
        else:
            left = mid + 1

    return left
```

### 658. Find K Closest Elements (Medium)
[View Problem](https://leetcode.com/problems/find-k-closest-elements/)
```python
def findClosestElements(arr: list[int], k: int, x: int) -> list[int]:
    # Binary search for window start - O(log(n-k) + k) time
    left, right = 0, len(arr) - k

    while left < right:
        mid = (left + right) // 2
        if x - arr[mid] > arr[mid + k] - x:
            left = mid + 1
        else:
            right = mid

    return arr[left:left + k]
```

---

## Linked List

### 203. Remove Linked List Elements (Easy)
[View Problem](https://leetcode.com/problems/remove-linked-list-elements/)
```python
def removeElements(head: ListNode, val: int) -> ListNode:
    # Dummy head - O(n) time, O(1) space
    dummy = ListNode(0, head)
    curr = dummy

    while curr.next:
        if curr.next.val == val:
            curr.next = curr.next.next
        else:
            curr = curr.next

    return dummy.next
```

### 83. Remove Duplicates from Sorted List (Easy)
[View Problem](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
```python
def deleteDuplicates(head: ListNode) -> ListNode:
    # Single pass - O(n) time, O(1) space
    curr = head

    while curr and curr.next:
        if curr.val == curr.next.val:
            curr.next = curr.next.next
        else:
            curr = curr.next

    return head
```

### 82. Remove Duplicates from Sorted List II (Medium)
[View Problem](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)
```python
def deleteDuplicates(head: ListNode) -> ListNode:
    # Dummy head with prev pointer - O(n) time, O(1) space
    dummy = ListNode(0, head)
    prev = dummy

    while head:
        if head.next and head.val == head.next.val:
            while head.next and head.val == head.next.val:
                head = head.next
            prev.next = head.next
        else:
            prev = prev.next
        head = head.next

    return dummy.next
```

### 24. Swap Nodes in Pairs (Medium)
[View Problem](https://leetcode.com/problems/swap-nodes-in-pairs/)
```python
def swapPairs(head: ListNode) -> ListNode:
    # Iterative - O(n) time, O(1) space
    dummy = ListNode(0, head)
    prev = dummy

    while prev.next and prev.next.next:
        first = prev.next
        second = prev.next.next

        prev.next = second
        first.next = second.next
        second.next = first

        prev = first

    return dummy.next
```

### 61. Rotate List (Medium)
[View Problem](https://leetcode.com/problems/rotate-list/)
```python
def rotateRight(head: ListNode, k: int) -> ListNode:
    # Find length and connect to circle - O(n) time, O(1) space
    if not head or not head.next or k == 0:
        return head

    # Find length and last node
    length = 1
    tail = head
    while tail.next:
        tail = tail.next
        length += 1

    k = k % length
    if k == 0:
        return head

    # Find new tail (length - k - 1 steps from head)
    new_tail = head
    for _ in range(length - k - 1):
        new_tail = new_tail.next

    new_head = new_tail.next
    new_tail.next = None
    tail.next = head

    return new_head
```

### 86. Partition List (Medium)
[View Problem](https://leetcode.com/problems/partition-list/)
```python
def partition(head: ListNode, x: int) -> ListNode:
    # Two dummy heads - O(n) time, O(1) space
    before = before_head = ListNode(0)
    after = after_head = ListNode(0)

    while head:
        if head.val < x:
            before.next = head
            before = before.next
        else:
            after.next = head
            after = after.next
        head = head.next

    after.next = None
    before.next = after_head.next

    return before_head.next
```

### 92. Reverse Linked List II (Medium)
[View Problem](https://leetcode.com/problems/reverse-linked-list-ii/)
```python
def reverseBetween(head: ListNode, left: int, right: int) -> ListNode:
    # Single pass - O(n) time, O(1) space
    if not head or left == right:
        return head

    dummy = ListNode(0, head)
    prev = dummy

    for _ in range(left - 1):
        prev = prev.next

    curr = prev.next
    for _ in range(right - left):
        next_node = curr.next
        curr.next = next_node.next
        next_node.next = prev.next
        prev.next = next_node

    return dummy.next
```

### 328. Odd Even Linked List (Medium)
[View Problem](https://leetcode.com/problems/odd-even-linked-list/)
```python
def oddEvenList(head: ListNode) -> ListNode:
    # Rearrange in place - O(n) time, O(1) space
    if not head:
        return head

    odd = head
    even = head.next
    even_head = even

    while even and even.next:
        odd.next = even.next
        odd = odd.next
        even.next = odd.next
        even = even.next

    odd.next = even_head
    return head
```

---

## Trees

### 94. Binary Tree Inorder Traversal (Easy)
[View Problem](https://leetcode.com/problems/binary-tree-inorder-traversal/)
```python
def inorderTraversal(root: TreeNode) -> list[int]:
    # Iterative with stack - O(n) time, O(n) space
    result = []
    stack = []
    curr = root

    while stack or curr:
        while curr:
            stack.append(curr)
            curr = curr.left
        curr = stack.pop()
        result.append(curr.val)
        curr = curr.right

    return result
```

### 144. Binary Tree Preorder Traversal (Easy)
[View Problem](https://leetcode.com/problems/binary-tree-preorder-traversal/)
```python
def preorderTraversal(root: TreeNode) -> list[int]:
    # Iterative with stack - O(n) time, O(n) space
    if not root:
        return []

    result = []
    stack = [root]

    while stack:
        node = stack.pop()
        result.append(node.val)
        if node.right:
            stack.append(node.right)
        if node.left:
            stack.append(node.left)

    return result
```

### 145. Binary Tree Postorder Traversal (Easy)
[View Problem](https://leetcode.com/problems/binary-tree-postorder-traversal/)
```python
def postorderTraversal(root: TreeNode) -> list[int]:
    # Iterative with two stacks - O(n) time, O(n) space
    if not root:
        return []

    result = []
    stack = [root]

    while stack:
        node = stack.pop()
        result.append(node.val)
        if node.left:
            stack.append(node.left)
        if node.right:
            stack.append(node.right)

    return result[::-1]
```

### 101. Symmetric Tree (Easy)
[View Problem](https://leetcode.com/problems/symmetric-tree/)
```python
def isSymmetric(root: TreeNode) -> bool:
    # Recursive - O(n) time, O(h) space
    def is_mirror(left, right):
        if not left and not right:
            return True
        if not left or not right:
            return False
        return (left.val == right.val and
                is_mirror(left.left, right.right) and
                is_mirror(left.right, right.left))

    return is_mirror(root, root)
```

### 111. Minimum Depth of Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/minimum-depth-of-binary-tree/)
```python
def minDepth(root: TreeNode) -> int:
    # BFS - O(n) time, O(n) space
    if not root:
        return 0

    from collections import deque
    queue = deque([(root, 1)])

    while queue:
        node, depth = queue.popleft()
        if not node.left and not node.right:
            return depth
        if node.left:
            queue.append((node.left, depth + 1))
        if node.right:
            queue.append((node.right, depth + 1))
```

### 112. Path Sum (Easy)
[View Problem](https://leetcode.com/problems/path-sum/)
```python
def hasPathSum(root: TreeNode, targetSum: int) -> bool:
    # DFS - O(n) time, O(h) space
    if not root:
        return False

    if not root.left and not root.right:
        return root.val == targetSum

    remaining = targetSum - root.val
    return hasPathSum(root.left, remaining) or hasPathSum(root.right, remaining)
```

### 113. Path Sum II (Medium)
[View Problem](https://leetcode.com/problems/path-sum-ii/)
```python
def pathSum(root: TreeNode, targetSum: int) -> list[list[int]]:
    # DFS with backtracking - O(n^2) time, O(n) space
    result = []

    def dfs(node, remaining, path):
        if not node:
            return

        path.append(node.val)

        if not node.left and not node.right and node.val == remaining:
            result.append(path[:])
        else:
            dfs(node.left, remaining - node.val, path)
            dfs(node.right, remaining - node.val, path)

        path.pop()

    dfs(root, targetSum, [])
    return result
```

### 129. Sum Root to Leaf Numbers (Medium)
[View Problem](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
```python
def sumNumbers(root: TreeNode) -> int:
    # DFS - O(n) time, O(h) space
    def dfs(node, current_sum):
        if not node:
            return 0

        current_sum = current_sum * 10 + node.val

        if not node.left and not node.right:
            return current_sum

        return dfs(node.left, current_sum) + dfs(node.right, current_sum)

    return dfs(root, 0)
```

### 236. Lowest Common Ancestor of a Binary Tree (Medium)
[View Problem](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
```python
def lowestCommonAncestor(root: TreeNode, p: TreeNode, q: TreeNode) -> TreeNode:
    # Recursive - O(n) time, O(h) space
    if not root or root == p or root == q:
        return root

    left = lowestCommonAncestor(root.left, p, q)
    right = lowestCommonAncestor(root.right, p, q)

    if left and right:
        return root
    return left or right
```

### 437. Path Sum III (Medium)
[View Problem](https://leetcode.com/problems/path-sum-iii/)
```python
def pathSum(root: TreeNode, targetSum: int) -> int:
    # Prefix sum with hash map - O(n) time, O(n) space
    from collections import defaultdict

    def dfs(node, curr_sum):
        if not node:
            return 0

        curr_sum += node.val
        count = prefix_sums[curr_sum - targetSum]

        prefix_sums[curr_sum] += 1
        count += dfs(node.left, curr_sum)
        count += dfs(node.right, curr_sum)
        prefix_sums[curr_sum] -= 1

        return count

    prefix_sums = defaultdict(int)
    prefix_sums[0] = 1
    return dfs(root, 0)
```

---

## Heap / Priority Queue

### 347. Top K Frequent Elements (Medium)
[View Problem](https://leetcode.com/problems/top-k-frequent-elements/)
```python
def topKFrequent(nums: list[int], k: int) -> list[int]:
    # Heap - O(n log k) time, O(n) space
    import heapq
    from collections import Counter

    count = Counter(nums)
    return heapq.nlargest(k, count.keys(), key=count.get)
```

### 692. Top K Frequent Words (Medium)
[View Problem](https://leetcode.com/problems/top-k-frequent-words/)
```python
def topKFrequent(words: list[str], k: int) -> list[str]:
    # Heap with custom comparator - O(n log k) time
    import heapq
    from collections import Counter

    count = Counter(words)
    # Use negative count for max heap, word for alphabetical order
    heap = [(-freq, word) for word, freq in count.items()]
    heapq.heapify(heap)

    return [heapq.heappop(heap)[1] for _ in range(k)]
```

### 378. Kth Smallest Element in a Sorted Matrix (Medium)
[View Problem](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)
```python
def kthSmallest(matrix: list[list[int]], k: int) -> int:
    # Min heap - O(k log n) time, O(n) space
    import heapq

    n = len(matrix)
    heap = [(matrix[0][j], 0, j) for j in range(n)]
    heapq.heapify(heap)

    for _ in range(k):
        val, row, col = heapq.heappop(heap)
        if row + 1 < n:
            heapq.heappush(heap, (matrix[row + 1][col], row + 1, col))

    return val
```

### 767. Reorganize String (Medium)
[View Problem](https://leetcode.com/problems/reorganize-string/)
```python
def reorganizeString(s: str) -> str:
    # Max heap - O(n log 26) time, O(26) space
    import heapq
    from collections import Counter

    count = Counter(s)
    max_heap = [(-freq, char) for char, freq in count.items()]
    heapq.heapify(max_heap)

    result = []
    prev_freq, prev_char = 0, ''

    while max_heap:
        freq, char = heapq.heappop(max_heap)
        result.append(char)

        if prev_freq < 0:
            heapq.heappush(max_heap, (prev_freq, prev_char))

        prev_freq, prev_char = freq + 1, char

    return ''.join(result) if len(result) == len(s) else ''
```

### 347. Top K Frequent Elements (Medium)
[View Problem](https://leetcode.com/problems/top-k-frequent-elements/)
```python
def topKFrequent(nums: list[int], k: int) -> list[int]:
    # Quick select - O(n) average time, O(n) space
    from collections import Counter

    count = Counter(nums)
    unique = list(count.keys())

    def partition(left, right, pivot_idx):
        pivot_freq = count[unique[pivot_idx]]
        unique[pivot_idx], unique[right] = unique[right], unique[pivot_idx]
        store_idx = left

        for i in range(left, right):
            if count[unique[i]] < pivot_freq:
                unique[store_idx], unique[i] = unique[i], unique[store_idx]
                store_idx += 1

        unique[right], unique[store_idx] = unique[store_idx], unique[right]
        return store_idx

    def quickselect(left, right, k_smallest):
        if left == right:
            return

        import random
        pivot_idx = random.randint(left, right)
        pivot_idx = partition(left, right, pivot_idx)

        if k_smallest == pivot_idx:
            return
        elif k_smallest < pivot_idx:
            quickselect(left, pivot_idx - 1, k_smallest)
        else:
            quickselect(pivot_idx + 1, right, k_smallest)

    n = len(unique)
    quickselect(0, n - 1, n - k)
    return unique[n - k:]
```

### 295. Find Median from Data Stream (Hard)
[View Problem](https://leetcode.com/problems/find-median-from-data-stream/)
```python
import heapq

class MedianFinder:
    def __init__(self):
        self.small = []  # Max heap (negated)
        self.large = []  # Min heap

    def addNum(self, num: int) -> None:
        # O(log n) time
        heapq.heappush(self.small, -num)
        heapq.heappush(self.large, -heapq.heappop(self.small))

        if len(self.large) > len(self.small):
            heapq.heappush(self.small, -heapq.heappop(self.large))

    def findMedian(self) -> float:
        # O(1) time
        if len(self.small) > len(self.large):
            return -self.small[0]
        return (-self.small[0] + self.large[0]) / 2
```

---

## Backtracking

### 77. Combinations (Medium)
[View Problem](https://leetcode.com/problems/combinations/)
```python
def combine(n: int, k: int) -> list[list[int]]:
    # Backtracking - O(C(n,k) * k) time
    result = []

    def backtrack(start, current):
        if len(current) == k:
            result.append(current[:])
            return

        for i in range(start, n + 1):
            current.append(i)
            backtrack(i + 1, current)
            current.pop()

    backtrack(1, [])
    return result
```

### 47. Permutations II (Medium)
[View Problem](https://leetcode.com/problems/permutations-ii/)
```python
def permuteUnique(nums: list[int]) -> list[list[int]]:
    # Backtracking with used array - O(n! * n) time
    nums.sort()
    result = []
    used = [False] * len(nums)

    def backtrack(current):
        if len(current) == len(nums):
            result.append(current[:])
            return

        for i in range(len(nums)):
            if used[i]:
                continue
            if i > 0 and nums[i] == nums[i - 1] and not used[i - 1]:
                continue

            used[i] = True
            current.append(nums[i])
            backtrack(current)
            current.pop()
            used[i] = False

    backtrack([])
    return result
```

### 93. Restore IP Addresses (Medium)
[View Problem](https://leetcode.com/problems/restore-ip-addresses/)
```python
def restoreIpAddresses(s: str) -> list[str]:
    # Backtracking - O(3^4) time
    result = []

    def backtrack(start, parts):
        if len(parts) == 4:
            if start == len(s):
                result.append('.'.join(parts))
            return

        for length in range(1, 4):
            if start + length > len(s):
                break

            segment = s[start:start + length]
            if (segment[0] == '0' and length > 1) or int(segment) > 255:
                continue

            backtrack(start + length, parts + [segment])

    backtrack(0, [])
    return result
```

### 216. Combination Sum III (Medium)
[View Problem](https://leetcode.com/problems/combination-sum-iii/)
```python
def combinationSum3(k: int, n: int) -> list[list[int]]:
    # Backtracking - O(C(9,k) * k) time
    result = []

    def backtrack(start, current, remaining):
        if len(current) == k:
            if remaining == 0:
                result.append(current[:])
            return

        for i in range(start, 10):
            if i > remaining:
                break
            current.append(i)
            backtrack(i + 1, current, remaining - i)
            current.pop()

    backtrack(1, [], n)
    return result
```

### 784. Letter Case Permutation (Medium)
[View Problem](https://leetcode.com/problems/letter-case-permutation/)
```python
def letterCasePermutation(s: str) -> list[str]:
    # Backtracking - O(2^n * n) time
    result = []

    def backtrack(idx, current):
        if idx == len(s):
            result.append(''.join(current))
            return

        if s[idx].isalpha():
            current.append(s[idx].lower())
            backtrack(idx + 1, current)
            current.pop()

            current.append(s[idx].upper())
            backtrack(idx + 1, current)
            current.pop()
        else:
            current.append(s[idx])
            backtrack(idx + 1, current)
            current.pop()

    backtrack(0, [])
    return result
```

### 1239. Maximum Length of a Concatenated String with Unique Characters (Medium)
[View Problem](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/)
```python
def maxLength(arr: list[str]) -> int:
    # Backtracking with bitmask - O(2^n * m) time
    def has_unique(s):
        return len(s) == len(set(s))

    result = [0]

    def backtrack(idx, current):
        if has_unique(current):
            result[0] = max(result[0], len(current))
        else:
            return

        for i in range(idx, len(arr)):
            backtrack(i + 1, current + arr[i])

    backtrack(0, '')
    return result[0]
```

---

## Graphs

### 797. All Paths From Source to Target (Medium)
[View Problem](https://leetcode.com/problems/all-paths-from-source-to-target/)
```python
def allPathsSourceTarget(graph: list[list[int]]) -> list[list[int]]:
    # DFS - O(2^n * n) time
    target = len(graph) - 1
    result = []

    def dfs(node, path):
        if node == target:
            result.append(path[:])
            return

        for neighbor in graph[node]:
            path.append(neighbor)
            dfs(neighbor, path)
            path.pop()

    dfs(0, [0])
    return result
```

### 841. Keys and Rooms (Medium)
[View Problem](https://leetcode.com/problems/keys-and-rooms/)
```python
def canVisitAllRooms(rooms: list[list[int]]) -> bool:
    # DFS - O(n + e) time, O(n) space
    visited = set()

    def dfs(room):
        visited.add(room)
        for key in rooms[room]:
            if key not in visited:
                dfs(key)

    dfs(0)
    return len(visited) == len(rooms)
```

### 547. Number of Provinces (Medium)
[View Problem](https://leetcode.com/problems/number-of-provinces/)
```python
def findCircleNum(isConnected: list[list[int]]) -> int:
    # Union-Find - O(n^2 * α(n)) time
    n = len(isConnected)
    parent = list(range(n))

    def find(x):
        if parent[x] != x:
            parent[x] = find(parent[x])
        return parent[x]

    def union(x, y):
        px, py = find(x), find(y)
        if px != py:
            parent[px] = py
            return True
        return False

    provinces = n
    for i in range(n):
        for j in range(i + 1, n):
            if isConnected[i][j] == 1 and union(i, j):
                provinces -= 1

    return provinces
```

### 802. Find Eventual Safe States (Medium)
[View Problem](https://leetcode.com/problems/find-eventual-safe-states/)
```python
def eventualSafeNodes(graph: list[list[int]]) -> list[int]:
    # DFS with coloring - O(V + E) time
    n = len(graph)
    color = [0] * n  # 0: unvisited, 1: visiting, 2: safe

    def dfs(node):
        if color[node] > 0:
            return color[node] == 2

        color[node] = 1
        for neighbor in graph[node]:
            if not dfs(neighbor):
                return False

        color[node] = 2
        return True

    return [i for i in range(n) if dfs(i)]
```

### 1192. Critical Connections in a Network (Hard)
[View Problem](https://leetcode.com/problems/critical-connections-in-a-network/)
```python
def criticalConnections(n: int, connections: list[list[int]]) -> list[list[int]]:
    # Tarjan's algorithm - O(V + E) time
    from collections import defaultdict

    graph = defaultdict(list)
    for u, v in connections:
        graph[u].append(v)
        graph[v].append(u)

    disc = [0] * n
    low = [0] * n
    result = []
    time = [1]

    def dfs(node, parent):
        disc[node] = low[node] = time[0]
        time[0] += 1

        for neighbor in graph[node]:
            if neighbor == parent:
                continue
            if disc[neighbor] == 0:
                dfs(neighbor, node)
                low[node] = min(low[node], low[neighbor])
                if low[neighbor] > disc[node]:
                    result.append([node, neighbor])
            else:
                low[node] = min(low[node], disc[neighbor])

    dfs(0, -1)
    return result
```

### 785. Is Graph Bipartite? (Medium)
[View Problem](https://leetcode.com/problems/is-graph-bipartite/)
```python
def isBipartite(graph: list[list[int]]) -> bool:
    # BFS coloring - O(V + E) time
    from collections import deque

    n = len(graph)
    color = [0] * n

    for start in range(n):
        if color[start] != 0:
            continue

        queue = deque([start])
        color[start] = 1

        while queue:
            node = queue.popleft()
            for neighbor in graph[node]:
                if color[neighbor] == 0:
                    color[neighbor] = -color[node]
                    queue.append(neighbor)
                elif color[neighbor] == color[node]:
                    return False

    return True
```

### 1254. Number of Closed Islands (Medium)
[View Problem](https://leetcode.com/problems/number-of-closed-islands/)
```python
def closedIsland(grid: list[list[int]]) -> int:
    # DFS - O(m*n) time
    rows, cols = len(grid), len(grid[0])

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols:
            return False
        if grid[r][c] == 1:
            return True

        grid[r][c] = 1
        left = dfs(r, c - 1)
        right = dfs(r, c + 1)
        up = dfs(r - 1, c)
        down = dfs(r + 1, c)

        return left and right and up and down

    count = 0
    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == 0 and dfs(r, c):
                count += 1

    return count
```

### 1631. Path With Minimum Effort (Medium)
[View Problem](https://leetcode.com/problems/path-with-minimum-effort/)
```python
def minimumEffortPath(heights: list[list[int]]) -> int:
    # Dijkstra's algorithm - O(m*n log(m*n)) time
    import heapq

    rows, cols = len(heights), len(heights[0])
    dist = [[float('inf')] * cols for _ in range(rows)]
    dist[0][0] = 0
    heap = [(0, 0, 0)]  # (effort, row, col)

    directions = [(0, 1), (0, -1), (1, 0), (-1, 0)]

    while heap:
        effort, r, c = heapq.heappop(heap)

        if r == rows - 1 and c == cols - 1:
            return effort

        if effort > dist[r][c]:
            continue

        for dr, dc in directions:
            nr, nc = r + dr, c + dc
            if 0 <= nr < rows and 0 <= nc < cols:
                new_effort = max(effort, abs(heights[nr][nc] - heights[r][c]))
                if new_effort < dist[nr][nc]:
                    dist[nr][nc] = new_effort
                    heapq.heappush(heap, (new_effort, nr, nc))

    return 0
```

---

## Dynamic Programming

### 509. Fibonacci Number (Easy)
[View Problem](https://leetcode.com/problems/fibonacci-number/)
```python
def fib(n: int) -> int:
    # DP - O(n) time, O(1) space
    if n <= 1:
        return n

    prev2, prev1 = 0, 1
    for _ in range(2, n + 1):
        curr = prev1 + prev2
        prev2, prev1 = prev1, curr

    return prev1
```

### 1137. N-th Tribonacci Number (Easy)
[View Problem](https://leetcode.com/problems/n-th-tribonacci-number/)
```python
def tribonacci(n: int) -> int:
    # DP - O(n) time, O(1) space
    if n == 0:
        return 0
    if n <= 2:
        return 1

    t0, t1, t2 = 0, 1, 1
    for _ in range(3, n + 1):
        t0, t1, t2 = t1, t2, t0 + t1 + t2

    return t2
```

### 64. Minimum Path Sum (Medium)
[View Problem](https://leetcode.com/problems/minimum-path-sum/)
```python
def minPathSum(grid: list[list[int]]) -> int:
    # DP - O(m*n) time, O(n) space
    m, n = len(grid), len(grid[0])
    dp = [float('inf')] * (n + 1)
    dp[1] = 0

    for i in range(m):
        for j in range(n):
            dp[j + 1] = min(dp[j], dp[j + 1]) + grid[i][j]

    return dp[n]
```

### 120. Triangle (Medium)
[View Problem](https://leetcode.com/problems/triangle/)
```python
def minimumTotal(triangle: list[list[int]]) -> int:
    # DP bottom-up - O(n^2) time, O(n) space
    dp = triangle[-1][:]

    for i in range(len(triangle) - 2, -1, -1):
        for j in range(len(triangle[i])):
            dp[j] = triangle[i][j] + min(dp[j], dp[j + 1])

    return dp[0]
```

### 279. Perfect Squares (Medium)
[View Problem](https://leetcode.com/problems/perfect-squares/)
```python
def numSquares(n: int) -> int:
    # DP - O(n * sqrt(n)) time, O(n) space
    dp = [float('inf')] * (n + 1)
    dp[0] = 0

    for i in range(1, n + 1):
        j = 1
        while j * j <= i:
            dp[i] = min(dp[i], dp[i - j * j] + 1)
            j += 1

    return dp[n]
```

### 343. Integer Break (Medium)
[View Problem](https://leetcode.com/problems/integer-break/)
```python
def integerBreak(n: int) -> int:
    # DP - O(n^2) time, O(n) space
    dp = [0] * (n + 1)
    dp[1] = 1

    for i in range(2, n + 1):
        for j in range(1, i):
            dp[i] = max(dp[i], j * (i - j), j * dp[i - j])

    return dp[n]
```

### 377. Combination Sum IV (Medium)
[View Problem](https://leetcode.com/problems/combination-sum-iv/)
```python
def combinationSum4(nums: list[int], target: int) -> int:
    # DP - O(target * n) time, O(target) space
    dp = [0] * (target + 1)
    dp[0] = 1

    for i in range(1, target + 1):
        for num in nums:
            if num <= i:
                dp[i] += dp[i - num]

    return dp[target]
```

### 518. Coin Change II (Medium)
[View Problem](https://leetcode.com/problems/coin-change-ii/)
```python
def change(amount: int, coins: list[int]) -> int:
    # DP - O(amount * n) time, O(amount) space
    dp = [0] * (amount + 1)
    dp[0] = 1

    for coin in coins:
        for i in range(coin, amount + 1):
            dp[i] += dp[i - coin]

    return dp[amount]
```

### 97. Interleaving String (Medium)
[View Problem](https://leetcode.com/problems/interleaving-string/)
```python
def isInterleave(s1: str, s2: str, s3: str) -> bool:
    # DP - O(m*n) time, O(n) space
    m, n = len(s1), len(s2)
    if m + n != len(s3):
        return False

    dp = [False] * (n + 1)
    dp[0] = True

    for j in range(1, n + 1):
        dp[j] = dp[j - 1] and s2[j - 1] == s3[j - 1]

    for i in range(1, m + 1):
        dp[0] = dp[0] and s1[i - 1] == s3[i - 1]
        for j in range(1, n + 1):
            dp[j] = (dp[j] and s1[i - 1] == s3[i + j - 1]) or \
                    (dp[j - 1] and s2[j - 1] == s3[i + j - 1])

    return dp[n]
```

### 516. Longest Palindromic Subsequence (Medium)
[View Problem](https://leetcode.com/problems/longest-palindromic-subsequence/)
```python
def longestPalindromeSubseq(s: str) -> int:
    # DP - O(n^2) time, O(n) space
    n = len(s)
    dp = [0] * n
    dp_prev = [0] * n

    for i in range(n - 1, -1, -1):
        dp[i] = 1
        for j in range(i + 1, n):
            if s[i] == s[j]:
                dp[j] = dp_prev[j - 1] + 2
            else:
                dp[j] = max(dp_prev[j], dp[j - 1])
        dp, dp_prev = dp_prev, dp

    return dp_prev[n - 1]
```

---

## Greedy

### 455. Assign Cookies (Easy)
[View Problem](https://leetcode.com/problems/assign-cookies/)
```python
def findContentChildren(g: list[int], s: list[int]) -> int:
    # Greedy - O(n log n + m log m) time
    g.sort()
    s.sort()

    child = cookie = 0
    while child < len(g) and cookie < len(s):
        if s[cookie] >= g[child]:
            child += 1
        cookie += 1

    return child
```

### 860. Lemonade Change (Easy)
[View Problem](https://leetcode.com/problems/lemonade-change/)
```python
def lemonadeChange(bills: list[int]) -> bool:
    # Greedy - O(n) time, O(1) space
    five = ten = 0

    for bill in bills:
        if bill == 5:
            five += 1
        elif bill == 10:
            if five == 0:
                return False
            five -= 1
            ten += 1
        else:  # bill == 20
            if ten > 0 and five > 0:
                ten -= 1
                five -= 1
            elif five >= 3:
                five -= 3
            else:
                return False

    return True
```

### 134. Gas Station (Medium)
[View Problem](https://leetcode.com/problems/gas-station/)
```python
def canCompleteCircuit(gas: list[int], cost: list[int]) -> int:
    # Greedy - O(n) time, O(1) space
    if sum(gas) < sum(cost):
        return -1

    start = 0
    tank = 0

    for i in range(len(gas)):
        tank += gas[i] - cost[i]
        if tank < 0:
            start = i + 1
            tank = 0

    return start
```

### 763. Partition Labels (Medium)
[View Problem](https://leetcode.com/problems/partition-labels/)
```python
def partitionLabels(s: str) -> list[int]:
    # Greedy - O(n) time, O(26) space
    last = {c: i for i, c in enumerate(s)}
    result = []
    start = end = 0

    for i, c in enumerate(s):
        end = max(end, last[c])
        if i == end:
            result.append(end - start + 1)
            start = i + 1

    return result
```

### 45. Jump Game II (Medium)
[View Problem](https://leetcode.com/problems/jump-game-ii/)
```python
def jump(nums: list[int]) -> int:
    # Greedy - O(n) time, O(1) space
    jumps = 0
    current_end = 0
    farthest = 0

    for i in range(len(nums) - 1):
        farthest = max(farthest, i + nums[i])
        if i == current_end:
            jumps += 1
            current_end = farthest

    return jumps
```

### 1029. Two City Scheduling (Medium)
[View Problem](https://leetcode.com/problems/two-city-scheduling/)
```python
def twoCitySchedCost(costs: list[list[int]]) -> int:
    # Greedy - O(n log n) time, O(1) space
    # Sort by (cost to A) - (cost to B)
    costs.sort(key=lambda x: x[0] - x[1])

    n = len(costs) // 2
    total = 0

    for i in range(n):
        total += costs[i][0]  # First n go to A
        total += costs[i + n][1]  # Last n go to B

    return total
```

---

## Math & Geometry

### 7. Reverse Integer (Medium)
[View Problem](https://leetcode.com/problems/reverse-integer/)
```python
def reverse(x: int) -> int:
    # Math - O(log x) time, O(1) space
    INT_MAX = 2**31 - 1
    INT_MIN = -2**31

    result = 0
    sign = 1 if x > 0 else -1
    x = abs(x)

    while x:
        digit = x % 10
        x //= 10

        if result > (INT_MAX - digit) // 10:
            return 0

        result = result * 10 + digit

    return sign * result
```

### 9. Palindrome Number (Easy)
[View Problem](https://leetcode.com/problems/palindrome-number/)
```python
def isPalindrome(x: int) -> bool:
    # Math - O(log x) time, O(1) space
    if x < 0 or (x % 10 == 0 and x != 0):
        return False

    reversed_half = 0
    while x > reversed_half:
        reversed_half = reversed_half * 10 + x % 10
        x //= 10

    return x == reversed_half or x == reversed_half // 10
```

### 12. Integer to Roman (Medium)
[View Problem](https://leetcode.com/problems/integer-to-roman/)
```python
def intToRoman(num: int) -> str:
    # Greedy - O(1) time, O(1) space
    values = [1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1]
    symbols = ["M", "CM", "D", "CD", "C", "XC", "L", "XL", "X", "IX", "V", "IV", "I"]

    result = []
    for i, v in enumerate(values):
        while num >= v:
            num -= v
            result.append(symbols[i])

    return ''.join(result)
```

### 13. Roman to Integer (Easy)
[View Problem](https://leetcode.com/problems/roman-to-integer/)
```python
def romanToInt(s: str) -> int:
    # Hash map - O(n) time, O(1) space
    values = {'I': 1, 'V': 5, 'X': 10, 'L': 50, 'C': 100, 'D': 500, 'M': 1000}

    result = 0
    for i in range(len(s)):
        if i + 1 < len(s) and values[s[i]] < values[s[i + 1]]:
            result -= values[s[i]]
        else:
            result += values[s[i]]

    return result
```

### 29. Divide Two Integers (Medium)
[View Problem](https://leetcode.com/problems/divide-two-integers/)
```python
def divide(dividend: int, divisor: int) -> int:
    # Bit manipulation - O(log n) time, O(1) space
    INT_MAX = 2**31 - 1
    INT_MIN = -2**31

    if dividend == INT_MIN and divisor == -1:
        return INT_MAX

    negative = (dividend < 0) != (divisor < 0)
    dividend, divisor = abs(dividend), abs(divisor)

    result = 0
    while dividend >= divisor:
        temp, multiple = divisor, 1
        while dividend >= (temp << 1):
            temp <<= 1
            multiple <<= 1
        dividend -= temp
        result += multiple

    return -result if negative else result
```

### 31. Next Permutation (Medium)
[View Problem](https://leetcode.com/problems/next-permutation/)
```python
def nextPermutation(nums: list[int]) -> None:
    # Two-pass - O(n) time, O(1) space
    n = len(nums)

    # Find first decreasing element from right
    i = n - 2
    while i >= 0 and nums[i] >= nums[i + 1]:
        i -= 1

    if i >= 0:
        # Find smallest element larger than nums[i]
        j = n - 1
        while nums[j] <= nums[i]:
            j -= 1
        nums[i], nums[j] = nums[j], nums[i]

    # Reverse suffix
    left, right = i + 1, n - 1
    while left < right:
        nums[left], nums[right] = nums[right], nums[left]
        left += 1
        right -= 1
```

---

## Bit Manipulation

### 231. Power of Two (Easy)
[View Problem](https://leetcode.com/problems/power-of-two/)
```python
def isPowerOfTwo(n: int) -> bool:
    # Bit manipulation - O(1) time, O(1) space
    return n > 0 and (n & (n - 1)) == 0
```

### 342. Power of Four (Easy)
[View Problem](https://leetcode.com/problems/power-of-four/)
```python
def isPowerOfFour(n: int) -> bool:
    # Bit manipulation - O(1) time, O(1) space
    # Must be power of 2 and have 1-bit at odd position
    return n > 0 and (n & (n - 1)) == 0 and (n & 0x55555555) != 0
```

### 389. Find the Difference (Easy)
[View Problem](https://leetcode.com/problems/find-the-difference/)
```python
def findTheDifference(s: str, t: str) -> str:
    # XOR - O(n) time, O(1) space
    result = 0
    for c in s + t:
        result ^= ord(c)
    return chr(result)
```

### 461. Hamming Distance (Easy)
[View Problem](https://leetcode.com/problems/hamming-distance/)
```python
def hammingDistance(x: int, y: int) -> int:
    # XOR and count bits - O(1) time, O(1) space
    xor = x ^ y
    count = 0
    while xor:
        count += xor & 1
        xor >>= 1
    return count
```

### 476. Number Complement (Easy)
[View Problem](https://leetcode.com/problems/number-complement/)
```python
def findComplement(num: int) -> int:
    # Bit manipulation - O(log n) time, O(1) space
    mask = 1
    while mask < num:
        mask = (mask << 1) | 1
    return num ^ mask
```

### 137. Single Number II (Medium)
[View Problem](https://leetcode.com/problems/single-number-ii/)
```python
def singleNumber(nums: list[int]) -> int:
    # Bit manipulation - O(n) time, O(1) space
    ones = twos = 0

    for num in nums:
        ones = (ones ^ num) & ~twos
        twos = (twos ^ num) & ~ones

    return ones
```

### 260. Single Number III (Medium)
[View Problem](https://leetcode.com/problems/single-number-iii/)
```python
def singleNumber(nums: list[int]) -> list[int]:
    # XOR and bit manipulation - O(n) time, O(1) space
    xor = 0
    for num in nums:
        xor ^= num

    # Find rightmost set bit
    diff_bit = xor & (-xor)

    a = b = 0
    for num in nums:
        if num & diff_bit:
            a ^= num
        else:
            b ^= num

    return [a, b]
```

---

## Summary

| Difficulty | Count |
|------------|-------|
| Easy | 32 |
| Medium | 65 |
| Hard | 3 |
| **Total** | **100** |

---

*Good luck with your interview preparation!*
