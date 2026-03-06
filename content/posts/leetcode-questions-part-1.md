+++
title = 'Leetcode Questions Part 1'
date = 2026-03-06T10:23:47-08:00
tags = ["leetcode"]
draft = false
+++

A curated list of 100 LeetCode problems for interview preparation with solution templates.

---

## Recommended Study Order

### 1. Array & Hashing - Foundation concepts
- [1. Two Sum](#1-two-sum-easy)
- [217. Contains Duplicate](#217-contains-duplicate-easy)
- [242. Valid Anagram](#242-valid-anagram-easy)
- [49. Group Anagrams](#49-group-anagrams-medium)
- [347. Top K Frequent Elements](#347-top-k-frequent-elements-medium)
- [238. Product of Array Except Self](#238-product-of-array-except-self-medium)
- [128. Longest Consecutive Sequence](#128-longest-consecutive-sequence-medium)
- [36. Valid Sudoku](#36-valid-sudoku-medium)
- [271. Encode and Decode Strings](#271-encode-and-decode-strings-medium)
- [560. Subarray Sum Equals K](#560-subarray-sum-equals-k-medium)

### 2. Two Pointers - Common pattern
- [125. Valid Palindrome](#125-valid-palindrome-easy)
- [167. Two Sum II - Input Array Is Sorted](#167-two-sum-ii-input-array-is-sorted-medium)
- [15. 3Sum](#15-3sum-medium)
- [11. Container With Most Water](#11-container-with-most-water-medium)
- [283. Move Zeroes](#283-move-zeroes-easy)
- [26. Remove Duplicates from Sorted Array](#26-remove-duplicates-from-sorted-array-easy)
- [88. Merge Sorted Array](#88-merge-sorted-array-easy)
- [977. Squares of a Sorted Array](#977-squares-of-a-sorted-array-easy)

### 3. Sliding Window - Builds on two pointers
- [121. Best Time to Buy and Sell Stock](#121-best-time-to-buy-and-sell-stock-easy)
- [3. Longest Substring Without Repeating Characters](#3-longest-substring-without-repeating-characters-medium)
- [424. Longest Repeating Character Replacement](#424-longest-repeating-character-replacement-medium)
- [567. Permutation in String](#567-permutation-in-string-medium)
- [209. Minimum Size Subarray Sum](#209-minimum-size-subarray-sum-medium)
- [438. Find All Anagrams in a String](#438-find-all-anagrams-in-a-string-medium)
- [1456. Maximum Number of Vowels in a Substring of Given Length](#1456-maximum-number-of-vowels-in-a-substring-of-given-length-medium)

### 4. Stack - Essential data structure
- [20. Valid Parentheses](#20-valid-parentheses-easy)
- [155. Min Stack](#155-min-stack-medium)
- [150. Evaluate Reverse Polish Notation](#150-evaluate-reverse-polish-notation-medium)
- [22. Generate Parentheses](#22-generate-parentheses-medium)
- [739. Daily Temperatures](#739-daily-temperatures-medium)
- [853. Car Fleet](#853-car-fleet-medium)
- [71. Simplify Path](#71-simplify-path-medium)
- [394. Decode String](#394-decode-string-medium)

### 5. Binary Search - Fundamental algorithm
- [704. Binary Search](#704-binary-search-easy)
- [74. Search a 2D Matrix](#74-search-a-2d-matrix-medium)
- [875. Koko Eating Bananas](#875-koko-eating-bananas-medium)
- [153. Find Minimum in Rotated Sorted Array](#153-find-minimum-in-rotated-sorted-array-medium)
- [33. Search in Rotated Sorted Array](#33-search-in-rotated-sorted-array-medium)
- [981. Time Based Key-Value Store](#981-time-based-key-value-store-medium)
- [35. Search Insert Position](#35-search-insert-position-easy)
- [278. First Bad Version](#278-first-bad-version-easy)

### 6. Linked List - Pointer manipulation
- [206. Reverse Linked List](#206-reverse-linked-list-easy)
- [21. Merge Two Sorted Lists](#21-merge-two-sorted-lists-easy)
- [143. Reorder List](#143-reorder-list-medium)
- [19. Remove Nth Node From End of List](#19-remove-nth-node-from-end-of-list-medium)
- [138. Copy List with Random Pointer](#138-copy-list-with-random-pointer-medium)
- [2. Add Two Numbers](#2-add-two-numbers-medium)
- [141. Linked List Cycle](#141-linked-list-cycle-easy)
- [142. Linked List Cycle II](#142-linked-list-cycle-ii-medium)
- [287. Find the Duplicate Number](#287-find-the-duplicate-number-medium)
- [148. Sort List](#148-sort-list-medium)
- [234. Palindrome Linked List](#234-palindrome-linked-list-easy)
- [160. Intersection of Two Linked Lists](#160-intersection-of-two-linked-lists-easy)

### 7. Trees - Recursive thinking
- [226. Invert Binary Tree](#226-invert-binary-tree-easy)
- [104. Maximum Depth of Binary Tree](#104-maximum-depth-of-binary-tree-easy)
- [543. Diameter of Binary Tree](#543-diameter-of-binary-tree-easy)
- [110. Balanced Binary Tree](#110-balanced-binary-tree-easy)
- [100. Same Tree](#100-same-tree-easy)
- [572. Subtree of Another Tree](#572-subtree-of-another-tree-easy)
- [235. Lowest Common Ancestor of a Binary Search Tree](#235-lowest-common-ancestor-of-a-binary-search-tree-medium)
- [102. Binary Tree Level Order Traversal](#102-binary-tree-level-order-traversal-medium)
- [199. Binary Tree Right Side View](#199-binary-tree-right-side-view-medium)
- [1448. Count Good Nodes in Binary Tree](#1448-count-good-nodes-in-binary-tree-medium)
- [98. Validate Binary Search Tree](#98-validate-binary-search-tree-medium)
- [230. Kth Smallest Element in a BST](#230-kth-smallest-element-in-a-bst-medium)
- [105. Construct Binary Tree from Preorder and Inorder Traversal](#105-construct-binary-tree-from-preorder-and-inorder-traversal-medium)
- [208. Implement Trie (Prefix Tree)](#208-implement-trie-prefix-tree-medium)

### 8. Heap / Priority Queue - Advanced data structure
- [703. Kth Largest Element in a Stream](#703-kth-largest-element-in-a-stream-easy)
- [1046. Last Stone Weight](#1046-last-stone-weight-easy)
- [973. K Closest Points to Origin](#973-k-closest-points-to-origin-medium)
- [215. Kth Largest Element in an Array](#215-kth-largest-element-in-an-array-medium)
- [621. Task Scheduler](#621-task-scheduler-medium)
- [355. Design Twitter](#355-design-twitter-medium)

### 9. Backtracking - Recursion mastery
- [78. Subsets](#78-subsets-medium)
- [39. Combination Sum](#39-combination-sum-medium)
- [46. Permutations](#46-permutations-medium)
- [90. Subsets II](#90-subsets-ii-medium)
- [40. Combination Sum II](#40-combination-sum-ii-medium)
- [79. Word Search](#79-word-search-medium)
- [131. Palindrome Partitioning](#131-palindrome-partitioning-medium)
- [17. Letter Combinations of a Phone Number](#17-letter-combinations-of-a-phone-number-medium)

### 10. Graphs - BFS/DFS applications
- [200. Number of Islands](#200-number-of-islands-medium)
- [133. Clone Graph](#133-clone-graph-medium)
- [695. Max Area of Island](#695-max-area-of-island-medium)
- [417. Pacific Atlantic Water Flow](#417-pacific-atlantic-water-flow-medium)
- [130. Surrounded Regions](#130-surrounded-regions-medium)
- [994. Rotting Oranges](#994-rotting-oranges-medium)
- [286. Walls and Gates](#286-walls-and-gates-medium)
- [207. Course Schedule](#207-course-schedule-medium)
- [210. Course Schedule II](#210-course-schedule-ii-medium)
- [684. Redundant Connection](#684-redundant-connection-medium)

### 11. Dynamic Programming - Problem decomposition
- [70. Climbing Stairs](#70-climbing-stairs-easy)
- [746. Min Cost Climbing Stairs](#746-min-cost-climbing-stairs-easy)
- [198. House Robber](#198-house-robber-medium)
- [213. House Robber II](#213-house-robber-ii-medium)
- [5. Longest Palindromic Substring](#5-longest-palindromic-substring-medium)
- [647. Palindromic Substrings](#647-palindromic-substrings-medium)
- [91. Decode Ways](#91-decode-ways-medium)
- [322. Coin Change](#322-coin-change-medium)
- [152. Maximum Product Subarray](#152-maximum-product-subarray-medium)
- [139. Word Break](#139-word-break-medium)
- [300. Longest Increasing Subsequence](#300-longest-increasing-subsequence-medium)
- [416. Partition Equal Subset Sum](#416-partition-equal-subset-sum-medium)
- [62. Unique Paths](#62-unique-paths-medium)
- [1143. Longest Common Subsequence](#1143-longest-common-subsequence-medium)
- [53. Maximum Subarray](#53-maximum-subarray-medium)
- [55. Jump Game](#55-jump-game-medium)

### 12. Intervals - Common interview topic
- [57. Insert Interval](#57-insert-interval-medium)
- [56. Merge Intervals](#56-merge-intervals-medium)
- [435. Non-overlapping Intervals](#435-non-overlapping-intervals-medium)
- [252. Meeting Rooms](#252-meeting-rooms-easy)
- [253. Meeting Rooms II](#253-meeting-rooms-ii-medium)

### 13. Math & Geometry - Matrix operations
- [48. Rotate Image](#48-rotate-image-medium)
- [54. Spiral Matrix](#54-spiral-matrix-medium)
- [73. Set Matrix Zeroes](#73-set-matrix-zeroes-medium)
- [202. Happy Number](#202-happy-number-easy)
- [66. Plus One](#66-plus-one-easy)
- [50. Pow(x, n)](#50-powx-n-medium)
- [43. Multiply Strings](#43-multiply-strings-medium)

### 14. Bit Manipulation - Optimization techniques
- [136. Single Number](#136-single-number-easy)
- [191. Number of 1 Bits](#191-number-of-1-bits-easy)
- [338. Counting Bits](#338-counting-bits-easy)
- [190. Reverse Bits](#190-reverse-bits-easy)
- [268. Missing Number](#268-missing-number-easy)
- [371. Sum of Two Integers](#371-sum-of-two-integers-medium)

---

## Array & Hashing

### 1. Two Sum (Easy)
[View Problem](https://leetcode.com/problems/two-sum/)
```python
def twoSum(nums: list[int], target: int) -> list[int]:
    # Hash map approach - O(n) time, O(n) space
    seen = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in seen:
            return [seen[complement], i]
        seen[num] = i
    return []
```

### 217. Contains Duplicate (Easy)
[View Problem](https://leetcode.com/problems/contains-duplicate/)
```python
def containsDuplicate(nums: list[int]) -> bool:
    # Set approach - O(n) time, O(n) space
    return len(nums) != len(set(nums))

    # Alternative: Hash set with early exit
    # seen = set()
    # for num in nums:
    #     if num in seen:
    #         return True
    #     seen.add(num)
    # return False
```

### 242. Valid Anagram (Easy)
[View Problem](https://leetcode.com/problems/valid-anagram/)
```python
def isAnagram(s: str, t: str) -> bool:
    # Counter approach - O(n) time, O(1) space (26 letters)
    if len(s) != len(t):
        return False

    count = {}
    for c in s:
        count[c] = count.get(c, 0) + 1
    for c in t:
        count[c] = count.get(c, 0) - 1
        if count[c] < 0:
            return False
    return True

    # Alternative: from collections import Counter
    # return Counter(s) == Counter(t)
```

### 49. Group Anagrams (Medium)
[View Problem](https://leetcode.com/problems/group-anagrams/)
```python
def groupAnagrams(strs: list[str]) -> list[list[str]]:
    # Hash map with sorted string as key - O(n * k log k) time
    from collections import defaultdict

    groups = defaultdict(list)
    for s in strs:
        key = tuple(sorted(s))
        groups[key].append(s)
    return list(groups.values())

    # Alternative: Use character count as key for O(n * k) time
    # def count_key(s):
    #     count = [0] * 26
    #     for c in s:
    #         count[ord(c) - ord('a')] += 1
    #     return tuple(count)
```

### 347. Top K Frequent Elements (Medium)
[View Problem](https://leetcode.com/problems/top-k-frequent-elements/)
```python
def topKFrequent(nums: list[int], k: int) -> list[int]:
    # Bucket sort approach - O(n) time, O(n) space
    from collections import Counter

    count = Counter(nums)
    # Bucket where index = frequency
    buckets = [[] for _ in range(len(nums) + 1)]

    for num, freq in count.items():
        buckets[freq].append(num)

    result = []
    for i in range(len(buckets) - 1, -1, -1):
        for num in buckets[i]:
            result.append(num)
            if len(result) == k:
                return result
    return result
```

### 238. Product of Array Except Self (Medium)
[View Problem](https://leetcode.com/problems/product-of-array-except-self/)
```python
def productExceptSelf(nums: list[int]) -> list[int]:
    # Two-pass approach - O(n) time, O(1) extra space
    n = len(nums)
    result = [1] * n

    # Left products
    left_product = 1
    for i in range(n):
        result[i] = left_product
        left_product *= nums[i]

    # Right products
    right_product = 1
    for i in range(n - 1, -1, -1):
        result[i] *= right_product
        right_product *= nums[i]

    return result
```

### 128. Longest Consecutive Sequence (Medium)
[View Problem](https://leetcode.com/problems/longest-consecutive-sequence/)
```python
def longestConsecutive(nums: list[int]) -> int:
    # Hash set approach - O(n) time, O(n) space
    num_set = set(nums)
    longest = 0

    for num in num_set:
        # Only start counting from sequence start
        if num - 1 not in num_set:
            current = num
            streak = 1

            while current + 1 in num_set:
                current += 1
                streak += 1

            longest = max(longest, streak)

    return longest
```

### 36. Valid Sudoku (Medium)
[View Problem](https://leetcode.com/problems/valid-sudoku/)
```python
def isValidSudoku(board: list[list[str]]) -> bool:
    # Hash sets for rows, cols, boxes - O(81) time, O(81) space
    rows = [set() for _ in range(9)]
    cols = [set() for _ in range(9)]
    boxes = [set() for _ in range(9)]

    for r in range(9):
        for c in range(9):
            if board[r][c] == '.':
                continue

            num = board[r][c]
            box_idx = (r // 3) * 3 + (c // 3)

            if num in rows[r] or num in cols[c] or num in boxes[box_idx]:
                return False

            rows[r].add(num)
            cols[c].add(num)
            boxes[box_idx].add(num)

    return True
```

### 271. Encode and Decode Strings (Medium)
[View Problem](https://leetcode.com/problems/encode-and-decode-strings/)
```python
class Codec:
    # Length-prefix encoding - O(n) time

    def encode(self, strs: list[str]) -> str:
        result = []
        for s in strs:
            result.append(f"{len(s)}#{s}")
        return ''.join(result)

    def decode(self, s: str) -> list[str]:
        result = []
        i = 0
        while i < len(s):
            j = i
            while s[j] != '#':
                j += 1
            length = int(s[i:j])
            result.append(s[j + 1:j + 1 + length])
            i = j + 1 + length
        return result
```

### 560. Subarray Sum Equals K (Medium)
[View Problem](https://leetcode.com/problems/subarray-sum-equals-k/)
```python
def subarraySum(nums: list[int], k: int) -> int:
    # Prefix sum with hash map - O(n) time, O(n) space
    count = 0
    prefix_sum = 0
    prefix_counts = {0: 1}

    for num in nums:
        prefix_sum += num
        # Check if (prefix_sum - k) exists
        if prefix_sum - k in prefix_counts:
            count += prefix_counts[prefix_sum - k]
        prefix_counts[prefix_sum] = prefix_counts.get(prefix_sum, 0) + 1

    return count
```

---

## Two Pointers

### 125. Valid Palindrome (Easy)
[View Problem](https://leetcode.com/problems/valid-palindrome/)
```python
def isPalindrome(s: str) -> bool:
    # Two pointers - O(n) time, O(1) space
    left, right = 0, len(s) - 1

    while left < right:
        while left < right and not s[left].isalnum():
            left += 1
        while left < right and not s[right].isalnum():
            right -= 1

        if s[left].lower() != s[right].lower():
            return False

        left += 1
        right -= 1

    return True
```

### 167. Two Sum II - Input Array Is Sorted (Medium)
[View Problem](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
```python
def twoSum(numbers: list[int], target: int) -> list[int]:
    # Two pointers - O(n) time, O(1) space
    left, right = 0, len(numbers) - 1

    while left < right:
        total = numbers[left] + numbers[right]
        if total == target:
            return [left + 1, right + 1]  # 1-indexed
        elif total < target:
            left += 1
        else:
            right -= 1

    return []
```

### 15. 3Sum (Medium)
[View Problem](https://leetcode.com/problems/3sum/)
```python
def threeSum(nums: list[int]) -> list[list[int]]:
    # Sort + Two pointers - O(n^2) time, O(1) extra space
    nums.sort()
    result = []

    for i in range(len(nums) - 2):
        # Skip duplicates for first element
        if i > 0 and nums[i] == nums[i - 1]:
            continue

        left, right = i + 1, len(nums) - 1
        while left < right:
            total = nums[i] + nums[left] + nums[right]
            if total == 0:
                result.append([nums[i], nums[left], nums[right]])
                # Skip duplicates
                while left < right and nums[left] == nums[left + 1]:
                    left += 1
                while left < right and nums[right] == nums[right - 1]:
                    right -= 1
                left += 1
                right -= 1
            elif total < 0:
                left += 1
            else:
                right -= 1

    return result
```

### 11. Container With Most Water (Medium)
[View Problem](https://leetcode.com/problems/container-with-most-water/)
```python
def maxArea(height: list[int]) -> int:
    # Two pointers - O(n) time, O(1) space
    left, right = 0, len(height) - 1
    max_water = 0

    while left < right:
        width = right - left
        h = min(height[left], height[right])
        max_water = max(max_water, width * h)

        # Move the shorter line inward
        if height[left] < height[right]:
            left += 1
        else:
            right -= 1

    return max_water
```

### 283. Move Zeroes (Easy)
[View Problem](https://leetcode.com/problems/move-zeroes/)
```python
def moveZeroes(nums: list[int]) -> None:
    # Two pointers (in-place) - O(n) time, O(1) space
    insert_pos = 0

    for i in range(len(nums)):
        if nums[i] != 0:
            nums[insert_pos], nums[i] = nums[i], nums[insert_pos]
            insert_pos += 1
```

### 26. Remove Duplicates from Sorted Array (Easy)
[View Problem](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
```python
def removeDuplicates(nums: list[int]) -> int:
    # Two pointers - O(n) time, O(1) space
    if not nums:
        return 0

    insert_pos = 1
    for i in range(1, len(nums)):
        if nums[i] != nums[i - 1]:
            nums[insert_pos] = nums[i]
            insert_pos += 1

    return insert_pos
```

### 88. Merge Sorted Array (Easy)
[View Problem](https://leetcode.com/problems/merge-sorted-array/)
```python
def merge(nums1: list[int], m: int, nums2: list[int], n: int) -> None:
    # Three pointers (from end) - O(m+n) time, O(1) space
    p1, p2, p = m - 1, n - 1, m + n - 1

    while p2 >= 0:
        if p1 >= 0 and nums1[p1] > nums2[p2]:
            nums1[p] = nums1[p1]
            p1 -= 1
        else:
            nums1[p] = nums2[p2]
            p2 -= 1
        p -= 1
```

### 977. Squares of a Sorted Array (Easy)
[View Problem](https://leetcode.com/problems/squares-of-a-sorted-array/)
```python
def sortedSquares(nums: list[int]) -> list[int]:
    # Two pointers - O(n) time, O(n) space
    n = len(nums)
    result = [0] * n
    left, right = 0, n - 1
    pos = n - 1

    while left <= right:
        if abs(nums[left]) > abs(nums[right]):
            result[pos] = nums[left] ** 2
            left += 1
        else:
            result[pos] = nums[right] ** 2
            right -= 1
        pos -= 1

    return result
```

---

## Sliding Window

### 121. Best Time to Buy and Sell Stock (Easy)
[View Problem](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
```python
def maxProfit(prices: list[int]) -> int:
    # Track min price - O(n) time, O(1) space
    min_price = float('inf')
    max_profit = 0

    for price in prices:
        min_price = min(min_price, price)
        max_profit = max(max_profit, price - min_price)

    return max_profit
```

### 3. Longest Substring Without Repeating Characters (Medium)
[View Problem](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
```python
def lengthOfLongestSubstring(s: str) -> int:
    # Sliding window with hash map - O(n) time, O(min(n, 26)) space
    char_index = {}
    max_len = 0
    left = 0

    for right, char in enumerate(s):
        if char in char_index and char_index[char] >= left:
            left = char_index[char] + 1
        char_index[char] = right
        max_len = max(max_len, right - left + 1)

    return max_len
```

### 424. Longest Repeating Character Replacement (Medium)
[View Problem](https://leetcode.com/problems/longest-repeating-character-replacement/)
```python
def characterReplacement(s: str, k: int) -> int:
    # Sliding window - O(n) time, O(26) space
    count = {}
    max_freq = 0
    max_len = 0
    left = 0

    for right in range(len(s)):
        count[s[right]] = count.get(s[right], 0) + 1
        max_freq = max(max_freq, count[s[right]])

        # Window size - max freq > k means too many replacements
        while (right - left + 1) - max_freq > k:
            count[s[left]] -= 1
            left += 1

        max_len = max(max_len, right - left + 1)

    return max_len
```

### 567. Permutation in String (Medium)
[View Problem](https://leetcode.com/problems/permutation-in-string/)
```python
def checkInclusion(s1: str, s2: str) -> bool:
    # Sliding window with frequency count - O(n) time, O(26) space
    if len(s1) > len(s2):
        return False

    s1_count = [0] * 26
    window_count = [0] * 26

    for c in s1:
        s1_count[ord(c) - ord('a')] += 1

    for i, c in enumerate(s2):
        window_count[ord(c) - ord('a')] += 1

        # Remove leftmost char when window exceeds s1 length
        if i >= len(s1):
            window_count[ord(s2[i - len(s1)]) - ord('a')] -= 1

        if window_count == s1_count:
            return True

    return False
```

### 209. Minimum Size Subarray Sum (Medium)
[View Problem](https://leetcode.com/problems/minimum-size-subarray-sum/)
```python
def minSubArrayLen(target: int, nums: list[int]) -> int:
    # Sliding window - O(n) time, O(1) space
    min_len = float('inf')
    left = 0
    current_sum = 0

    for right in range(len(nums)):
        current_sum += nums[right]

        while current_sum >= target:
            min_len = min(min_len, right - left + 1)
            current_sum -= nums[left]
            left += 1

    return min_len if min_len != float('inf') else 0
```

### 438. Find All Anagrams in a String (Medium)
[View Problem](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
```python
def findAnagrams(s: str, p: str) -> list[int]:
    # Sliding window - O(n) time, O(26) space
    if len(p) > len(s):
        return []

    p_count = [0] * 26
    window_count = [0] * 26
    result = []

    for c in p:
        p_count[ord(c) - ord('a')] += 1

    for i in range(len(s)):
        window_count[ord(s[i]) - ord('a')] += 1

        if i >= len(p):
            window_count[ord(s[i - len(p)]) - ord('a')] -= 1

        if window_count == p_count:
            result.append(i - len(p) + 1)

    return result
```

### 1456. Maximum Number of Vowels in a Substring of Given Length (Medium)
[View Problem](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/)
```python
def maxVowels(s: str, k: int) -> int:
    # Sliding window - O(n) time, O(1) space
    vowels = set('aeiou')
    count = sum(1 for c in s[:k] if c in vowels)
    max_count = count

    for i in range(k, len(s)):
        if s[i] in vowels:
            count += 1
        if s[i - k] in vowels:
            count -= 1
        max_count = max(max_count, count)

    return max_count
```

---

## Stack

### 20. Valid Parentheses (Easy)
[View Problem](https://leetcode.com/problems/valid-parentheses/)
```python
def isValid(s: str) -> bool:
    # Stack approach - O(n) time, O(n) space
    stack = []
    pairs = {')': '(', '}': '{', ']': '['}

    for char in s:
        if char in pairs:
            if not stack or stack[-1] != pairs[char]:
                return False
            stack.pop()
        else:
            stack.append(char)

    return len(stack) == 0
```

### 155. Min Stack (Medium)
[View Problem](https://leetcode.com/problems/min-stack/)
```python
class MinStack:
    # Two stacks approach - O(1) for all operations

    def __init__(self):
        self.stack = []
        self.min_stack = []

    def push(self, val: int) -> None:
        self.stack.append(val)
        min_val = min(val, self.min_stack[-1] if self.min_stack else val)
        self.min_stack.append(min_val)

    def pop(self) -> None:
        self.stack.pop()
        self.min_stack.pop()

    def top(self) -> int:
        return self.stack[-1]

    def getMin(self) -> int:
        return self.min_stack[-1]
```

### 150. Evaluate Reverse Polish Notation (Medium)
[View Problem](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
```python
def evalRPN(tokens: list[str]) -> int:
    # Stack approach - O(n) time, O(n) space
    stack = []
    operators = {
        '+': lambda a, b: a + b,
        '-': lambda a, b: a - b,
        '*': lambda a, b: a * b,
        '/': lambda a, b: int(a / b)  # Truncate toward zero
    }

    for token in tokens:
        if token in operators:
            b, a = stack.pop(), stack.pop()
            stack.append(operators[token](a, b))
        else:
            stack.append(int(token))

    return stack[0]
```

### 22. Generate Parentheses (Medium)
[View Problem](https://leetcode.com/problems/generate-parentheses/)
```python
def generateParenthesis(n: int) -> list[str]:
    # Backtracking - O(4^n / sqrt(n)) time (Catalan number)
    result = []

    def backtrack(current: str, open_count: int, close_count: int):
        if len(current) == 2 * n:
            result.append(current)
            return

        if open_count < n:
            backtrack(current + '(', open_count + 1, close_count)
        if close_count < open_count:
            backtrack(current + ')', open_count, close_count + 1)

    backtrack('', 0, 0)
    return result
```

### 739. Daily Temperatures (Medium)
[View Problem](https://leetcode.com/problems/daily-temperatures/)
```python
def dailyTemperatures(temperatures: list[int]) -> list[int]:
    # Monotonic decreasing stack - O(n) time, O(n) space
    n = len(temperatures)
    result = [0] * n
    stack = []  # Store indices

    for i, temp in enumerate(temperatures):
        while stack and temperatures[stack[-1]] < temp:
            prev_idx = stack.pop()
            result[prev_idx] = i - prev_idx
        stack.append(i)

    return result
```

### 853. Car Fleet (Medium)
[View Problem](https://leetcode.com/problems/car-fleet/)
```python
def carFleet(target: int, position: list[int], speed: list[int]) -> int:
    # Sort by position + Stack - O(n log n) time, O(n) space
    cars = sorted(zip(position, speed), reverse=True)
    stack = []

    for pos, spd in cars:
        time = (target - pos) / spd
        if not stack or time > stack[-1]:
            stack.append(time)

    return len(stack)
```

### 71. Simplify Path (Medium)
[View Problem](https://leetcode.com/problems/simplify-path/)
```python
def simplifyPath(path: str) -> str:
    # Stack approach - O(n) time, O(n) space
    stack = []
    parts = path.split('/')

    for part in parts:
        if part == '..':
            if stack:
                stack.pop()
        elif part and part != '.':
            stack.append(part)

    return '/' + '/'.join(stack)
```

### 394. Decode String (Medium)
[View Problem](https://leetcode.com/problems/decode-string/)
```python
def decodeString(s: str) -> str:
    # Stack approach - O(n) time, O(n) space
    stack = []
    current_num = 0
    current_str = ''

    for char in s:
        if char.isdigit():
            current_num = current_num * 10 + int(char)
        elif char == '[':
            stack.append((current_str, current_num))
            current_str = ''
            current_num = 0
        elif char == ']':
            prev_str, num = stack.pop()
            current_str = prev_str + current_str * num
        else:
            current_str += char

    return current_str
```

---

## Binary Search

### 704. Binary Search (Easy)
[View Problem](https://leetcode.com/problems/binary-search/)
```python
def search(nums: list[int], target: int) -> int:
    # Classic binary search - O(log n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left <= right:
        mid = left + (right - left) // 2
        if nums[mid] == target:
            return mid
        elif nums[mid] < target:
            left = mid + 1
        else:
            right = mid - 1

    return -1
```

### 74. Search a 2D Matrix (Medium)
[View Problem](https://leetcode.com/problems/search-a-2d-matrix/)
```python
def searchMatrix(matrix: list[list[int]], target: int) -> bool:
    # Treat as 1D array - O(log(m*n)) time, O(1) space
    if not matrix:
        return False

    m, n = len(matrix), len(matrix[0])
    left, right = 0, m * n - 1

    while left <= right:
        mid = left + (right - left) // 2
        row, col = mid // n, mid % n
        val = matrix[row][col]

        if val == target:
            return True
        elif val < target:
            left = mid + 1
        else:
            right = mid - 1

    return False
```

### 875. Koko Eating Bananas (Medium)
[View Problem](https://leetcode.com/problems/koko-eating-bananas/)
```python
def minEatingSpeed(piles: list[int], h: int) -> int:
    # Binary search on answer - O(n log m) time, O(1) space
    import math

    def can_finish(k):
        hours = sum(math.ceil(pile / k) for pile in piles)
        return hours <= h

    left, right = 1, max(piles)

    while left < right:
        mid = left + (right - left) // 2
        if can_finish(mid):
            right = mid
        else:
            left = mid + 1

    return left
```

### 153. Find Minimum in Rotated Sorted Array (Medium)
[View Problem](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
```python
def findMin(nums: list[int]) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left < right:
        mid = left + (right - left) // 2
        if nums[mid] > nums[right]:
            # Min is in right half
            left = mid + 1
        else:
            # Min is in left half (including mid)
            right = mid

    return nums[left]
```

### 33. Search in Rotated Sorted Array (Medium)
[View Problem](https://leetcode.com/problems/search-in-rotated-sorted-array/)
```python
def search(nums: list[int], target: int) -> int:
    # Modified binary search - O(log n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left <= right:
        mid = left + (right - left) // 2

        if nums[mid] == target:
            return mid

        # Left half is sorted
        if nums[left] <= nums[mid]:
            if nums[left] <= target < nums[mid]:
                right = mid - 1
            else:
                left = mid + 1
        # Right half is sorted
        else:
            if nums[mid] < target <= nums[right]:
                left = mid + 1
            else:
                right = mid - 1

    return -1
```

### 981. Time Based Key-Value Store (Medium)
[View Problem](https://leetcode.com/problems/time-based-key-value-store/)
```python
class TimeMap:
    # Hash map + Binary search - O(1) set, O(log n) get

    def __init__(self):
        self.store = {}  # key -> [(timestamp, value)]

    def set(self, key: str, value: str, timestamp: int) -> None:
        if key not in self.store:
            self.store[key] = []
        self.store[key].append((timestamp, value))

    def get(self, key: str, timestamp: int) -> str:
        if key not in self.store:
            return ""

        values = self.store[key]
        left, right = 0, len(values) - 1
        result = ""

        while left <= right:
            mid = left + (right - left) // 2
            if values[mid][0] <= timestamp:
                result = values[mid][1]
                left = mid + 1
            else:
                right = mid - 1

        return result
```

### 35. Search Insert Position (Easy)
[View Problem](https://leetcode.com/problems/search-insert-position/)
```python
def searchInsert(nums: list[int], target: int) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(nums)

    while left < right:
        mid = left + (right - left) // 2
        if nums[mid] < target:
            left = mid + 1
        else:
            right = mid

    return left
```

### 278. First Bad Version (Easy)
[View Problem](https://leetcode.com/problems/first-bad-version/)
```python
def firstBadVersion(n: int) -> int:
    # Binary search - O(log n) time, O(1) space
    # isBadVersion(version) is provided API
    left, right = 1, n

    while left < right:
        mid = left + (right - left) // 2
        if isBadVersion(mid):
            right = mid
        else:
            left = mid + 1

    return left
```

---

## Linked List

### 206. Reverse Linked List (Easy)
[View Problem](https://leetcode.com/problems/reverse-linked-list/)
```python
def reverseList(head: ListNode) -> ListNode:
    # Iterative - O(n) time, O(1) space
    prev, curr = None, head

    while curr:
        next_temp = curr.next
        curr.next = prev
        prev = curr
        curr = next_temp

    return prev

    # Recursive approach:
    # def reverseList(head):
    #     if not head or not head.next:
    #         return head
    #     new_head = reverseList(head.next)
    #     head.next.next = head
    #     head.next = None
    #     return new_head
```

### 21. Merge Two Sorted Lists (Easy)
[View Problem](https://leetcode.com/problems/merge-two-sorted-lists/)
```python
def mergeTwoLists(list1: ListNode, list2: ListNode) -> ListNode:
    # Iterative - O(n+m) time, O(1) space
    dummy = ListNode(0)
    curr = dummy

    while list1 and list2:
        if list1.val <= list2.val:
            curr.next = list1
            list1 = list1.next
        else:
            curr.next = list2
            list2 = list2.next
        curr = curr.next

    curr.next = list1 or list2
    return dummy.next
```

### 143. Reorder List (Medium)
[View Problem](https://leetcode.com/problems/reorder-list/)
```python
def reorderList(head: ListNode) -> None:
    # Find middle + Reverse + Merge - O(n) time, O(1) space
    if not head or not head.next:
        return

    # Find middle
    slow, fast = head, head
    while fast.next and fast.next.next:
        slow = slow.next
        fast = fast.next.next

    # Reverse second half
    prev, curr = None, slow.next
    slow.next = None
    while curr:
        next_temp = curr.next
        curr.next = prev
        prev = curr
        curr = next_temp

    # Merge two halves
    first, second = head, prev
    while second:
        tmp1, tmp2 = first.next, second.next
        first.next = second
        second.next = tmp1
        first, second = tmp1, tmp2
```

### 19. Remove Nth Node From End of List (Medium)
[View Problem](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
```python
def removeNthFromEnd(head: ListNode, n: int) -> ListNode:
    # Two pointers - O(n) time, O(1) space
    dummy = ListNode(0, head)
    fast = slow = dummy

    # Move fast n+1 steps ahead
    for _ in range(n + 1):
        fast = fast.next

    # Move both until fast reaches end
    while fast:
        fast = fast.next
        slow = slow.next

    slow.next = slow.next.next
    return dummy.next
```

### 138. Copy List with Random Pointer (Medium)
[View Problem](https://leetcode.com/problems/copy-list-with-random-pointer/)
```python
def copyRandomList(head: 'Node') -> 'Node':
    # Hash map approach - O(n) time, O(n) space
    if not head:
        return None

    old_to_new = {}

    # First pass: create all nodes
    curr = head
    while curr:
        old_to_new[curr] = Node(curr.val)
        curr = curr.next

    # Second pass: set next and random pointers
    curr = head
    while curr:
        old_to_new[curr].next = old_to_new.get(curr.next)
        old_to_new[curr].random = old_to_new.get(curr.random)
        curr = curr.next

    return old_to_new[head]
```

### 2. Add Two Numbers (Medium)
[View Problem](https://leetcode.com/problems/add-two-numbers/)
```python
def addTwoNumbers(l1: ListNode, l2: ListNode) -> ListNode:
    # Elementary math - O(max(m,n)) time, O(max(m,n)) space
    dummy = ListNode(0)
    curr = dummy
    carry = 0

    while l1 or l2 or carry:
        val1 = l1.val if l1 else 0
        val2 = l2.val if l2 else 0

        total = val1 + val2 + carry
        carry = total // 10
        curr.next = ListNode(total % 10)
        curr = curr.next

        l1 = l1.next if l1 else None
        l2 = l2.next if l2 else None

    return dummy.next
```

### 141. Linked List Cycle (Easy)
[View Problem](https://leetcode.com/problems/linked-list-cycle/)
```python
def hasCycle(head: ListNode) -> bool:
    # Floyd's Cycle Detection - O(n) time, O(1) space
    slow = fast = head

    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next
        if slow == fast:
            return True

    return False
```

### 142. Linked List Cycle II (Medium)
[View Problem](https://leetcode.com/problems/linked-list-cycle-ii/)
```python
def detectCycle(head: ListNode) -> ListNode:
    # Floyd's algorithm - O(n) time, O(1) space
    slow = fast = head

    # Detect cycle
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next
        if slow == fast:
            break
    else:
        return None

    # Find cycle start
    slow = head
    while slow != fast:
        slow = slow.next
        fast = fast.next

    return slow
```

### 287. Find the Duplicate Number (Medium)
[View Problem](https://leetcode.com/problems/find-the-duplicate-number/)
```python
def findDuplicate(nums: list[int]) -> int:
    # Floyd's Cycle Detection - O(n) time, O(1) space
    slow = fast = nums[0]

    # Find intersection point
    while True:
        slow = nums[slow]
        fast = nums[nums[fast]]
        if slow == fast:
            break

    # Find cycle start
    slow = nums[0]
    while slow != fast:
        slow = nums[slow]
        fast = nums[fast]

    return slow
```

### 148. Sort List (Medium)
[View Problem](https://leetcode.com/problems/sort-list/)
```python
def sortList(head: ListNode) -> ListNode:
    # Merge sort - O(n log n) time, O(log n) space
    if not head or not head.next:
        return head

    # Find middle
    slow, fast = head, head.next
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next

    mid = slow.next
    slow.next = None

    # Recursively sort both halves
    left = sortList(head)
    right = sortList(mid)

    # Merge sorted halves
    dummy = ListNode(0)
    curr = dummy
    while left and right:
        if left.val < right.val:
            curr.next = left
            left = left.next
        else:
            curr.next = right
            right = right.next
        curr = curr.next
    curr.next = left or right

    return dummy.next
```

### 234. Palindrome Linked List (Easy)
[View Problem](https://leetcode.com/problems/palindrome-linked-list/)
```python
def isPalindrome(head: ListNode) -> bool:
    # Reverse second half - O(n) time, O(1) space
    # Find middle
    slow = fast = head
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next

    # Reverse second half
    prev = None
    while slow:
        next_temp = slow.next
        slow.next = prev
        prev = slow
        slow = next_temp

    # Compare
    left, right = head, prev
    while right:
        if left.val != right.val:
            return False
        left = left.next
        right = right.next

    return True
```

### 160. Intersection of Two Linked Lists (Easy)
[View Problem](https://leetcode.com/problems/intersection-of-two-linked-lists/)
```python
def getIntersectionNode(headA: ListNode, headB: ListNode) -> ListNode:
    # Two pointers - O(n+m) time, O(1) space
    if not headA or not headB:
        return None

    pA, pB = headA, headB

    while pA != pB:
        pA = pA.next if pA else headB
        pB = pB.next if pB else headA

    return pA
```

---

## Trees

### 226. Invert Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/invert-binary-tree/)
```python
def invertTree(root: TreeNode) -> TreeNode:
    # Recursive DFS - O(n) time, O(h) space
    if not root:
        return None

    root.left, root.right = root.right, root.left
    invertTree(root.left)
    invertTree(root.right)

    return root
```

### 104. Maximum Depth of Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
```python
def maxDepth(root: TreeNode) -> int:
    # Recursive DFS - O(n) time, O(h) space
    if not root:
        return 0
    return 1 + max(maxDepth(root.left), maxDepth(root.right))
```

### 543. Diameter of Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/diameter-of-binary-tree/)
```python
def diameterOfBinaryTree(root: TreeNode) -> int:
    # DFS with global max - O(n) time, O(h) space
    diameter = 0

    def depth(node):
        nonlocal diameter
        if not node:
            return 0

        left = depth(node.left)
        right = depth(node.right)
        diameter = max(diameter, left + right)

        return 1 + max(left, right)

    depth(root)
    return diameter
```

### 110. Balanced Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/balanced-binary-tree/)
```python
def isBalanced(root: TreeNode) -> bool:
    # DFS with height check - O(n) time, O(h) space
    def check(node):
        if not node:
            return 0

        left = check(node.left)
        right = check(node.right)

        if left == -1 or right == -1 or abs(left - right) > 1:
            return -1

        return 1 + max(left, right)

    return check(root) != -1
```

### 100. Same Tree (Easy)
[View Problem](https://leetcode.com/problems/same-tree/)
```python
def isSameTree(p: TreeNode, q: TreeNode) -> bool:
    # Recursive comparison - O(n) time, O(h) space
    if not p and not q:
        return True
    if not p or not q or p.val != q.val:
        return False
    return isSameTree(p.left, q.left) and isSameTree(p.right, q.right)
```

### 572. Subtree of Another Tree (Easy)
[View Problem](https://leetcode.com/problems/subtree-of-another-tree/)
```python
def isSubtree(root: TreeNode, subRoot: TreeNode) -> bool:
    # DFS + Same tree check - O(m*n) time, O(h) space
    def isSame(p, q):
        if not p and not q:
            return True
        if not p or not q or p.val != q.val:
            return False
        return isSame(p.left, q.left) and isSame(p.right, q.right)

    if not root:
        return False
    if isSame(root, subRoot):
        return True
    return isSubtree(root.left, subRoot) or isSubtree(root.right, subRoot)
```

### 235. Lowest Common Ancestor of a Binary Search Tree (Medium)
[View Problem](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)
```python
def lowestCommonAncestor(root: TreeNode, p: TreeNode, q: TreeNode) -> TreeNode:
    # BST property - O(h) time, O(1) space
    while root:
        if p.val < root.val and q.val < root.val:
            root = root.left
        elif p.val > root.val and q.val > root.val:
            root = root.right
        else:
            return root
```

### 102. Binary Tree Level Order Traversal (Medium)
[View Problem](https://leetcode.com/problems/binary-tree-level-order-traversal/)
```python
def levelOrder(root: TreeNode) -> list[list[int]]:
    # BFS - O(n) time, O(n) space
    if not root:
        return []

    from collections import deque
    result = []
    queue = deque([root])

    while queue:
        level = []
        for _ in range(len(queue)):
            node = queue.popleft()
            level.append(node.val)
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)
        result.append(level)

    return result
```

### 199. Binary Tree Right Side View (Medium)
[View Problem](https://leetcode.com/problems/binary-tree-right-side-view/)
```python
def rightSideView(root: TreeNode) -> list[int]:
    # BFS, take last of each level - O(n) time, O(n) space
    if not root:
        return []

    from collections import deque
    result = []
    queue = deque([root])

    while queue:
        level_size = len(queue)
        for i in range(level_size):
            node = queue.popleft()
            if i == level_size - 1:
                result.append(node.val)
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)

    return result
```

### 1448. Count Good Nodes in Binary Tree (Medium)
[View Problem](https://leetcode.com/problems/count-good-nodes-in-binary-tree/)
```python
def goodNodes(root: TreeNode) -> int:
    # DFS with max tracking - O(n) time, O(h) space
    def dfs(node, max_val):
        if not node:
            return 0

        count = 1 if node.val >= max_val else 0
        max_val = max(max_val, node.val)

        count += dfs(node.left, max_val)
        count += dfs(node.right, max_val)

        return count

    return dfs(root, root.val)
```

### 98. Validate Binary Search Tree (Medium)
[View Problem](https://leetcode.com/problems/validate-binary-search-tree/)
```python
def isValidBST(root: TreeNode) -> bool:
    # DFS with bounds - O(n) time, O(h) space
    def validate(node, min_val, max_val):
        if not node:
            return True

        if node.val <= min_val or node.val >= max_val:
            return False

        return (validate(node.left, min_val, node.val) and
                validate(node.right, node.val, max_val))

    return validate(root, float('-inf'), float('inf'))
```

### 230. Kth Smallest Element in a BST (Medium)
[View Problem](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
```python
def kthSmallest(root: TreeNode, k: int) -> int:
    # Inorder traversal - O(h + k) time, O(h) space
    stack = []
    curr = root
    count = 0

    while stack or curr:
        while curr:
            stack.append(curr)
            curr = curr.left

        curr = stack.pop()
        count += 1
        if count == k:
            return curr.val

        curr = curr.right
```

### 105. Construct Binary Tree from Preorder and Inorder Traversal (Medium)
[View Problem](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
```python
def buildTree(preorder: list[int], inorder: list[int]) -> TreeNode:
    # Recursive with index map - O(n) time, O(n) space
    inorder_map = {val: idx for idx, val in enumerate(inorder)}

    def build(pre_start, pre_end, in_start, in_end):
        if pre_start > pre_end:
            return None

        root_val = preorder[pre_start]
        root = TreeNode(root_val)

        in_root = inorder_map[root_val]
        left_size = in_root - in_start

        root.left = build(pre_start + 1, pre_start + left_size,
                          in_start, in_root - 1)
        root.right = build(pre_start + left_size + 1, pre_end,
                           in_root + 1, in_end)

        return root

    return build(0, len(preorder) - 1, 0, len(inorder) - 1)
```

### 208. Implement Trie (Prefix Tree) (Medium)
[View Problem](https://leetcode.com/problems/implement-trie-prefix-tree/)
```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

class Trie:
    def __init__(self):
        self.root = TrieNode()

    def insert(self, word: str) -> None:
        # O(n) time, O(n) space
        node = self.root
        for char in word:
            if char not in node.children:
                node.children[char] = TrieNode()
            node = node.children[char]
        node.is_end = True

    def search(self, word: str) -> bool:
        # O(n) time, O(1) space
        node = self.root
        for char in word:
            if char not in node.children:
                return False
            node = node.children[char]
        return node.is_end

    def startsWith(self, prefix: str) -> bool:
        # O(n) time, O(1) space
        node = self.root
        for char in prefix:
            if char not in node.children:
                return False
            node = node.children[char]
        return True
```

---

## Heap / Priority Queue

### 703. Kth Largest Element in a Stream (Easy)
[View Problem](https://leetcode.com/problems/kth-largest-element-in-a-stream/)
```python
import heapq

class KthLargest:
    # Min heap of size k - O(log k) add, O(n log k) init

    def __init__(self, k: int, nums: list[int]):
        self.k = k
        self.heap = nums
        heapq.heapify(self.heap)
        while len(self.heap) > k:
            heapq.heappop(self.heap)

    def add(self, val: int) -> int:
        heapq.heappush(self.heap, val)
        if len(self.heap) > self.k:
            heapq.heappop(self.heap)
        return self.heap[0]
```

### 1046. Last Stone Weight (Easy)
[View Problem](https://leetcode.com/problems/last-stone-weight/)
```python
def lastStoneWeight(stones: list[int]) -> int:
    # Max heap - O(n log n) time, O(n) space
    import heapq

    # Python has min heap, so negate values
    heap = [-s for s in stones]
    heapq.heapify(heap)

    while len(heap) > 1:
        first = -heapq.heappop(heap)
        second = -heapq.heappop(heap)
        if first != second:
            heapq.heappush(heap, -(first - second))

    return -heap[0] if heap else 0
```

### 973. K Closest Points to Origin (Medium)
[View Problem](https://leetcode.com/problems/k-closest-points-to-origin/)
```python
def kClosest(points: list[list[int]], k: int) -> list[list[int]]:
    # Max heap of size k - O(n log k) time, O(k) space
    import heapq

    # Use max heap (negate distance)
    heap = []
    for x, y in points:
        dist = -(x * x + y * y)
        if len(heap) < k:
            heapq.heappush(heap, (dist, x, y))
        elif dist > heap[0][0]:
            heapq.heapreplace(heap, (dist, x, y))

    return [[x, y] for (_, x, y) in heap]
```

### 215. Kth Largest Element in an Array (Medium)
[View Problem](https://leetcode.com/problems/kth-largest-element-in-an-array/)
```python
def findKthLargest(nums: list[int], k: int) -> int:
    # Min heap of size k - O(n log k) time, O(k) space
    import heapq

    heap = []
    for num in nums:
        heapq.heappush(heap, num)
        if len(heap) > k:
            heapq.heappop(heap)

    return heap[0]

    # Alternative: Quickselect - O(n) average time
```

### 621. Task Scheduler (Medium)
[View Problem](https://leetcode.com/problems/task-scheduler/)
```python
def leastInterval(tasks: list[str], n: int) -> int:
    # Greedy with max heap - O(m) time where m = total tasks
    import heapq
    from collections import Counter

    count = Counter(tasks)
    max_heap = [-c for c in count.values()]
    heapq.heapify(max_heap)

    time = 0
    queue = []  # (available_time, count)

    while max_heap or queue:
        time += 1

        if max_heap:
            cnt = heapq.heappop(max_heap) + 1  # Process one task
            if cnt < 0:
                queue.append((time + n, cnt))

        if queue and queue[0][0] == time:
            heapq.heappush(max_heap, queue.pop(0)[1])

    return time
```

### 355. Design Twitter (Medium)
[View Problem](https://leetcode.com/problems/design-twitter/)
```python
import heapq
from collections import defaultdict

class Twitter:
    def __init__(self):
        self.time = 0
        self.tweets = defaultdict(list)  # userId -> [(time, tweetId)]
        self.following = defaultdict(set)  # userId -> set of followeeIds

    def postTweet(self, userId: int, tweetId: int) -> None:
        self.tweets[userId].append((self.time, tweetId))
        self.time -= 1  # Decrement for max heap behavior

    def getNewsFeed(self, userId: int) -> list[int]:
        # Merge k sorted lists with heap
        heap = []
        self.following[userId].add(userId)

        for followeeId in self.following[userId]:
            if self.tweets[followeeId]:
                idx = len(self.tweets[followeeId]) - 1
                time, tweetId = self.tweets[followeeId][idx]
                heap.append((time, tweetId, followeeId, idx))

        heapq.heapify(heap)
        result = []

        while heap and len(result) < 10:
            time, tweetId, followeeId, idx = heapq.heappop(heap)
            result.append(tweetId)
            if idx > 0:
                idx -= 1
                time, tweetId = self.tweets[followeeId][idx]
                heapq.heappush(heap, (time, tweetId, followeeId, idx))

        return result

    def follow(self, followerId: int, followeeId: int) -> None:
        self.following[followerId].add(followeeId)

    def unfollow(self, followerId: int, followeeId: int) -> None:
        self.following[followerId].discard(followeeId)
```

---

## Backtracking

### 78. Subsets (Medium)
[View Problem](https://leetcode.com/problems/subsets/)
```python
def subsets(nums: list[int]) -> list[list[int]]:
    # Backtracking - O(n * 2^n) time, O(n) space
    result = []

    def backtrack(start, current):
        result.append(current[:])

        for i in range(start, len(nums)):
            current.append(nums[i])
            backtrack(i + 1, current)
            current.pop()

    backtrack(0, [])
    return result
```

### 39. Combination Sum (Medium)
[View Problem](https://leetcode.com/problems/combination-sum/)
```python
def combinationSum(candidates: list[int], target: int) -> list[list[int]]:
    # Backtracking - O(n^(target/min)) time
    result = []

    def backtrack(start, current, remaining):
        if remaining == 0:
            result.append(current[:])
            return
        if remaining < 0:
            return

        for i in range(start, len(candidates)):
            current.append(candidates[i])
            backtrack(i, current, remaining - candidates[i])  # Can reuse same element
            current.pop()

    backtrack(0, [], target)
    return result
```

### 46. Permutations (Medium)
[View Problem](https://leetcode.com/problems/permutations/)
```python
def permute(nums: list[int]) -> list[list[int]]:
    # Backtracking - O(n! * n) time, O(n) space
    result = []

    def backtrack(current):
        if len(current) == len(nums):
            result.append(current[:])
            return

        for num in nums:
            if num not in current:
                current.append(num)
                backtrack(current)
                current.pop()

    backtrack([])
    return result
```

### 90. Subsets II (Medium)
[View Problem](https://leetcode.com/problems/subsets-ii/)
```python
def subsetsWithDup(nums: list[int]) -> list[list[int]]:
    # Backtracking with skip duplicates - O(n * 2^n) time
    nums.sort()
    result = []

    def backtrack(start, current):
        result.append(current[:])

        for i in range(start, len(nums)):
            # Skip duplicates
            if i > start and nums[i] == nums[i - 1]:
                continue
            current.append(nums[i])
            backtrack(i + 1, current)
            current.pop()

    backtrack(0, [])
    return result
```

### 40. Combination Sum II (Medium)
[View Problem](https://leetcode.com/problems/combination-sum-ii/)
```python
def combinationSum2(candidates: list[int], target: int) -> list[list[int]]:
    # Backtracking with skip duplicates - O(2^n) time
    candidates.sort()
    result = []

    def backtrack(start, current, remaining):
        if remaining == 0:
            result.append(current[:])
            return

        for i in range(start, len(candidates)):
            if candidates[i] > remaining:
                break
            if i > start and candidates[i] == candidates[i - 1]:
                continue

            current.append(candidates[i])
            backtrack(i + 1, current, remaining - candidates[i])
            current.pop()

    backtrack(0, [], target)
    return result
```

### 79. Word Search (Medium)
[View Problem](https://leetcode.com/problems/word-search/)
```python
def exist(board: list[list[str]], word: str) -> bool:
    # DFS backtracking - O(m*n*4^L) time
    rows, cols = len(board), len(board[0])

    def dfs(r, c, idx):
        if idx == len(word):
            return True
        if (r < 0 or r >= rows or c < 0 or c >= cols or
                board[r][c] != word[idx]):
            return False

        # Mark visited
        temp = board[r][c]
        board[r][c] = '#'

        found = (dfs(r + 1, c, idx + 1) or
                 dfs(r - 1, c, idx + 1) or
                 dfs(r, c + 1, idx + 1) or
                 dfs(r, c - 1, idx + 1))

        # Restore
        board[r][c] = temp
        return found

    for r in range(rows):
        for c in range(cols):
            if dfs(r, c, 0):
                return True
    return False
```

### 131. Palindrome Partitioning (Medium)
[View Problem](https://leetcode.com/problems/palindrome-partitioning/)
```python
def partition(s: str) -> list[list[str]]:
    # Backtracking - O(n * 2^n) time
    result = []

    def is_palindrome(sub):
        return sub == sub[::-1]

    def backtrack(start, current):
        if start == len(s):
            result.append(current[:])
            return

        for end in range(start + 1, len(s) + 1):
            substring = s[start:end]
            if is_palindrome(substring):
                current.append(substring)
                backtrack(end, current)
                current.pop()

    backtrack(0, [])
    return result
```

### 17. Letter Combinations of a Phone Number (Medium)
[View Problem](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
```python
def letterCombinations(digits: str) -> list[str]:
    # Backtracking - O(4^n * n) time
    if not digits:
        return []

    phone = {
        '2': 'abc', '3': 'def', '4': 'ghi', '5': 'jkl',
        '6': 'mno', '7': 'pqrs', '8': 'tuv', '9': 'wxyz'
    }

    result = []

    def backtrack(idx, current):
        if idx == len(digits):
            result.append(''.join(current))
            return

        for char in phone[digits[idx]]:
            current.append(char)
            backtrack(idx + 1, current)
            current.pop()

    backtrack(0, [])
    return result
```

---

## Graphs

### 200. Number of Islands (Medium)
[View Problem](https://leetcode.com/problems/number-of-islands/)
```python
def numIslands(grid: list[list[str]]) -> int:
    # DFS - O(m*n) time, O(m*n) space
    if not grid:
        return 0

    rows, cols = len(grid), len(grid[0])
    count = 0

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols or grid[r][c] != '1':
            return
        grid[r][c] = '0'  # Mark visited
        dfs(r + 1, c)
        dfs(r - 1, c)
        dfs(r, c + 1)
        dfs(r, c - 1)

    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == '1':
                count += 1
                dfs(r, c)

    return count
```

### 133. Clone Graph (Medium)
[View Problem](https://leetcode.com/problems/clone-graph/)
```python
def cloneGraph(node: 'Node') -> 'Node':
    # DFS with hash map - O(V+E) time, O(V) space
    if not node:
        return None

    visited = {}

    def dfs(node):
        if node in visited:
            return visited[node]

        clone = Node(node.val)
        visited[node] = clone

        for neighbor in node.neighbors:
            clone.neighbors.append(dfs(neighbor))

        return clone

    return dfs(node)
```

### 695. Max Area of Island (Medium)
[View Problem](https://leetcode.com/problems/max-area-of-island/)
```python
def maxAreaOfIsland(grid: list[list[int]]) -> int:
    # DFS - O(m*n) time, O(m*n) space
    rows, cols = len(grid), len(grid[0])
    max_area = 0

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols or grid[r][c] != 1:
            return 0
        grid[r][c] = 0  # Mark visited
        return 1 + dfs(r+1, c) + dfs(r-1, c) + dfs(r, c+1) + dfs(r, c-1)

    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == 1:
                max_area = max(max_area, dfs(r, c))

    return max_area
```

### 417. Pacific Atlantic Water Flow (Medium)
[View Problem](https://leetcode.com/problems/pacific-atlantic-water-flow/)
```python
def pacificAtlantic(heights: list[list[int]]) -> list[list[int]]:
    # DFS from oceans - O(m*n) time, O(m*n) space
    rows, cols = len(heights), len(heights[0])
    pacific = set()
    atlantic = set()

    def dfs(r, c, visited, prev_height):
        if (r < 0 or r >= rows or c < 0 or c >= cols or
                (r, c) in visited or heights[r][c] < prev_height):
            return

        visited.add((r, c))
        for dr, dc in [(1, 0), (-1, 0), (0, 1), (0, -1)]:
            dfs(r + dr, c + dc, visited, heights[r][c])

    for c in range(cols):
        dfs(0, c, pacific, heights[0][c])
        dfs(rows - 1, c, atlantic, heights[rows - 1][c])

    for r in range(rows):
        dfs(r, 0, pacific, heights[r][0])
        dfs(r, cols - 1, atlantic, heights[r][cols - 1])

    return list(pacific & atlantic)
```

### 130. Surrounded Regions (Medium)
[View Problem](https://leetcode.com/problems/surrounded-regions/)
```python
def solve(board: list[list[str]]) -> None:
    # DFS from border - O(m*n) time, O(m*n) space
    if not board:
        return

    rows, cols = len(board), len(board[0])

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols or board[r][c] != 'O':
            return
        board[r][c] = 'T'  # Temporary mark
        dfs(r + 1, c)
        dfs(r - 1, c)
        dfs(r, c + 1)
        dfs(r, c - 1)

    # Mark border-connected O's
    for r in range(rows):
        dfs(r, 0)
        dfs(r, cols - 1)
    for c in range(cols):
        dfs(0, c)
        dfs(rows - 1, c)

    # Convert
    for r in range(rows):
        for c in range(cols):
            if board[r][c] == 'O':
                board[r][c] = 'X'
            elif board[r][c] == 'T':
                board[r][c] = 'O'
```

### 994. Rotting Oranges (Medium)
[View Problem](https://leetcode.com/problems/rotting-oranges/)
```python
def orangesRotting(grid: list[list[int]]) -> int:
    # Multi-source BFS - O(m*n) time, O(m*n) space
    from collections import deque

    rows, cols = len(grid), len(grid[0])
    queue = deque()
    fresh = 0

    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == 2:
                queue.append((r, c))
            elif grid[r][c] == 1:
                fresh += 1

    minutes = 0
    directions = [(1, 0), (-1, 0), (0, 1), (0, -1)]

    while queue and fresh > 0:
        minutes += 1
        for _ in range(len(queue)):
            r, c = queue.popleft()
            for dr, dc in directions:
                nr, nc = r + dr, c + dc
                if 0 <= nr < rows and 0 <= nc < cols and grid[nr][nc] == 1:
                    grid[nr][nc] = 2
                    fresh -= 1
                    queue.append((nr, nc))

    return minutes if fresh == 0 else -1
```

### 286. Walls and Gates (Medium)
[View Problem](https://leetcode.com/problems/walls-and-gates/)
```python
def wallsAndGates(rooms: list[list[int]]) -> None:
    # Multi-source BFS from gates - O(m*n) time, O(m*n) space
    from collections import deque

    if not rooms:
        return

    rows, cols = len(rooms), len(rooms[0])
    INF = 2147483647
    queue = deque()

    # Add all gates to queue
    for r in range(rows):
        for c in range(cols):
            if rooms[r][c] == 0:
                queue.append((r, c))

    directions = [(1, 0), (-1, 0), (0, 1), (0, -1)]

    while queue:
        r, c = queue.popleft()
        for dr, dc in directions:
            nr, nc = r + dr, c + dc
            if 0 <= nr < rows and 0 <= nc < cols and rooms[nr][nc] == INF:
                rooms[nr][nc] = rooms[r][c] + 1
                queue.append((nr, nc))
```

### 207. Course Schedule (Medium)
[View Problem](https://leetcode.com/problems/course-schedule/)
```python
def canFinish(numCourses: int, prerequisites: list[list[int]]) -> bool:
    # Topological sort (cycle detection) - O(V+E) time
    from collections import defaultdict, deque

    graph = defaultdict(list)
    in_degree = [0] * numCourses

    for course, prereq in prerequisites:
        graph[prereq].append(course)
        in_degree[course] += 1

    queue = deque([i for i in range(numCourses) if in_degree[i] == 0])
    completed = 0

    while queue:
        course = queue.popleft()
        completed += 1
        for next_course in graph[course]:
            in_degree[next_course] -= 1
            if in_degree[next_course] == 0:
                queue.append(next_course)

    return completed == numCourses
```

### 210. Course Schedule II (Medium)
[View Problem](https://leetcode.com/problems/course-schedule-ii/)
```python
def findOrder(numCourses: int, prerequisites: list[list[int]]) -> list[int]:
    # Topological sort - O(V+E) time
    from collections import defaultdict, deque

    graph = defaultdict(list)
    in_degree = [0] * numCourses

    for course, prereq in prerequisites:
        graph[prereq].append(course)
        in_degree[course] += 1

    queue = deque([i for i in range(numCourses) if in_degree[i] == 0])
    order = []

    while queue:
        course = queue.popleft()
        order.append(course)
        for next_course in graph[course]:
            in_degree[next_course] -= 1
            if in_degree[next_course] == 0:
                queue.append(next_course)

    return order if len(order) == numCourses else []
```

### 684. Redundant Connection (Medium)
[View Problem](https://leetcode.com/problems/redundant-connection/)
```python
def findRedundantConnection(edges: list[list[int]]) -> list[int]:
    # Union-Find - O(n * α(n)) time, O(n) space
    n = len(edges)
    parent = list(range(n + 1))
    rank = [0] * (n + 1)

    def find(x):
        if parent[x] != x:
            parent[x] = find(parent[x])
        return parent[x]

    def union(x, y):
        px, py = find(x), find(y)
        if px == py:
            return False
        if rank[px] < rank[py]:
            px, py = py, px
        parent[py] = px
        if rank[px] == rank[py]:
            rank[px] += 1
        return True

    for u, v in edges:
        if not union(u, v):
            return [u, v]
```

---

## Dynamic Programming

### 70. Climbing Stairs (Easy)
[View Problem](https://leetcode.com/problems/climbing-stairs/)
```python
def climbStairs(n: int) -> int:
    # DP (Fibonacci) - O(n) time, O(1) space
    if n <= 2:
        return n

    prev2, prev1 = 1, 2
    for _ in range(3, n + 1):
        curr = prev1 + prev2
        prev2, prev1 = prev1, curr

    return prev1
```

### 746. Min Cost Climbing Stairs (Easy)
[View Problem](https://leetcode.com/problems/min-cost-climbing-stairs/)
```python
def minCostClimbingStairs(cost: list[int]) -> int:
    # DP - O(n) time, O(1) space
    prev2, prev1 = 0, 0

    for i in range(2, len(cost) + 1):
        curr = min(prev1 + cost[i - 1], prev2 + cost[i - 2])
        prev2, prev1 = prev1, curr

    return prev1
```

### 198. House Robber (Medium)
[View Problem](https://leetcode.com/problems/house-robber/)
```python
def rob(nums: list[int]) -> int:
    # DP - O(n) time, O(1) space
    prev2, prev1 = 0, 0

    for num in nums:
        curr = max(prev1, prev2 + num)
        prev2, prev1 = prev1, curr

    return prev1
```

### 213. House Robber II (Medium)
[View Problem](https://leetcode.com/problems/house-robber-ii/)
```python
def rob(nums: list[int]) -> int:
    # Two passes (exclude first or last) - O(n) time, O(1) space
    if len(nums) == 1:
        return nums[0]

    def rob_linear(houses):
        prev2, prev1 = 0, 0
        for h in houses:
            curr = max(prev1, prev2 + h)
            prev2, prev1 = prev1, curr
        return prev1

    return max(rob_linear(nums[:-1]), rob_linear(nums[1:]))
```

### 5. Longest Palindromic Substring (Medium)
[View Problem](https://leetcode.com/problems/longest-palindromic-substring/)
```python
def longestPalindrome(s: str) -> str:
    # Expand from center - O(n^2) time, O(1) space
    def expand(left, right):
        while left >= 0 and right < len(s) and s[left] == s[right]:
            left -= 1
            right += 1
        return s[left + 1:right]

    result = ""
    for i in range(len(s)):
        # Odd length
        odd = expand(i, i)
        if len(odd) > len(result):
            result = odd
        # Even length
        even = expand(i, i + 1)
        if len(even) > len(result):
            result = even

    return result
```

### 647. Palindromic Substrings (Medium)
[View Problem](https://leetcode.com/problems/palindromic-substrings/)
```python
def countSubstrings(s: str) -> int:
    # Expand from center - O(n^2) time, O(1) space
    count = 0

    def expand(left, right):
        nonlocal count
        while left >= 0 and right < len(s) and s[left] == s[right]:
            count += 1
            left -= 1
            right += 1

    for i in range(len(s)):
        expand(i, i)      # Odd length
        expand(i, i + 1)  # Even length

    return count
```

### 91. Decode Ways (Medium)
[View Problem](https://leetcode.com/problems/decode-ways/)
```python
def numDecodings(s: str) -> int:
    # DP - O(n) time, O(1) space
    if not s or s[0] == '0':
        return 0

    prev2, prev1 = 1, 1

    for i in range(1, len(s)):
        curr = 0

        # Single digit
        if s[i] != '0':
            curr += prev1

        # Two digits
        two_digit = int(s[i-1:i+1])
        if 10 <= two_digit <= 26:
            curr += prev2

        prev2, prev1 = prev1, curr

    return prev1
```

### 322. Coin Change (Medium)
[View Problem](https://leetcode.com/problems/coin-change/)
```python
def coinChange(coins: list[int], amount: int) -> int:
    # DP - O(amount * n) time, O(amount) space
    dp = [float('inf')] * (amount + 1)
    dp[0] = 0

    for i in range(1, amount + 1):
        for coin in coins:
            if coin <= i and dp[i - coin] != float('inf'):
                dp[i] = min(dp[i], dp[i - coin] + 1)

    return dp[amount] if dp[amount] != float('inf') else -1
```

### 152. Maximum Product Subarray (Medium)
[View Problem](https://leetcode.com/problems/maximum-product-subarray/)
```python
def maxProduct(nums: list[int]) -> int:
    # Track min and max - O(n) time, O(1) space
    result = nums[0]
    cur_max = cur_min = 1

    for num in nums:
        candidates = (num, num * cur_max, num * cur_min)
        cur_max = max(candidates)
        cur_min = min(candidates)
        result = max(result, cur_max)

    return result
```

### 139. Word Break (Medium)
[View Problem](https://leetcode.com/problems/word-break/)
```python
def wordBreak(s: str, wordDict: list[str]) -> bool:
    # DP - O(n^2 * m) time, O(n) space
    word_set = set(wordDict)
    dp = [False] * (len(s) + 1)
    dp[0] = True

    for i in range(1, len(s) + 1):
        for j in range(i):
            if dp[j] and s[j:i] in word_set:
                dp[i] = True
                break

    return dp[len(s)]
```

### 300. Longest Increasing Subsequence (Medium)
[View Problem](https://leetcode.com/problems/longest-increasing-subsequence/)
```python
def lengthOfLIS(nums: list[int]) -> int:
    # Binary search - O(n log n) time, O(n) space
    from bisect import bisect_left

    sub = []
    for num in nums:
        pos = bisect_left(sub, num)
        if pos == len(sub):
            sub.append(num)
        else:
            sub[pos] = num

    return len(sub)

    # DP approach: O(n^2) time
    # dp = [1] * len(nums)
    # for i in range(1, len(nums)):
    #     for j in range(i):
    #         if nums[j] < nums[i]:
    #             dp[i] = max(dp[i], dp[j] + 1)
    # return max(dp)
```

### 416. Partition Equal Subset Sum (Medium)
[View Problem](https://leetcode.com/problems/partition-equal-subset-sum/)
```python
def canPartition(nums: list[int]) -> bool:
    # DP - O(n * sum) time, O(sum) space
    total = sum(nums)
    if total % 2 != 0:
        return False

    target = total // 2
    dp = [False] * (target + 1)
    dp[0] = True

    for num in nums:
        for j in range(target, num - 1, -1):
            dp[j] = dp[j] or dp[j - num]

    return dp[target]
```

### 62. Unique Paths (Medium)
[View Problem](https://leetcode.com/problems/unique-paths/)
```python
def uniquePaths(m: int, n: int) -> int:
    # DP - O(m*n) time, O(n) space
    dp = [1] * n

    for _ in range(1, m):
        for j in range(1, n):
            dp[j] += dp[j - 1]

    return dp[n - 1]
```

### 1143. Longest Common Subsequence (Medium)
[View Problem](https://leetcode.com/problems/longest-common-subsequence/)
```python
def longestCommonSubsequence(text1: str, text2: str) -> int:
    # DP - O(m*n) time, O(n) space
    m, n = len(text1), len(text2)
    dp = [0] * (n + 1)

    for i in range(1, m + 1):
        prev = 0
        for j in range(1, n + 1):
            temp = dp[j]
            if text1[i - 1] == text2[j - 1]:
                dp[j] = prev + 1
            else:
                dp[j] = max(dp[j], dp[j - 1])
            prev = temp

    return dp[n]
```

### 53. Maximum Subarray (Medium)
[View Problem](https://leetcode.com/problems/maximum-subarray/)
```python
def maxSubArray(nums: list[int]) -> int:
    # Kadane's algorithm - O(n) time, O(1) space
    max_sum = nums[0]
    current_sum = nums[0]

    for i in range(1, len(nums)):
        current_sum = max(nums[i], current_sum + nums[i])
        max_sum = max(max_sum, current_sum)

    return max_sum
```

### 55. Jump Game (Medium)
[View Problem](https://leetcode.com/problems/jump-game/)
```python
def canJump(nums: list[int]) -> bool:
    # Greedy - O(n) time, O(1) space
    max_reach = 0

    for i in range(len(nums)):
        if i > max_reach:
            return False
        max_reach = max(max_reach, i + nums[i])

    return True
```

---

## Intervals

### 57. Insert Interval (Medium)
[View Problem](https://leetcode.com/problems/insert-interval/)
```python
def insert(intervals: list[list[int]], newInterval: list[int]) -> list[list[int]]:
    # Linear scan - O(n) time, O(n) space
    result = []
    i = 0
    n = len(intervals)

    # Add all intervals before newInterval
    while i < n and intervals[i][1] < newInterval[0]:
        result.append(intervals[i])
        i += 1

    # Merge overlapping intervals
    while i < n and intervals[i][0] <= newInterval[1]:
        newInterval[0] = min(newInterval[0], intervals[i][0])
        newInterval[1] = max(newInterval[1], intervals[i][1])
        i += 1
    result.append(newInterval)

    # Add remaining intervals
    while i < n:
        result.append(intervals[i])
        i += 1

    return result
```

### 56. Merge Intervals (Medium)
[View Problem](https://leetcode.com/problems/merge-intervals/)
```python
def merge(intervals: list[list[int]]) -> list[list[int]]:
    # Sort + merge - O(n log n) time, O(n) space
    intervals.sort(key=lambda x: x[0])
    merged = [intervals[0]]

    for start, end in intervals[1:]:
        if start <= merged[-1][1]:
            merged[-1][1] = max(merged[-1][1], end)
        else:
            merged.append([start, end])

    return merged
```

### 435. Non-overlapping Intervals (Medium)
[View Problem](https://leetcode.com/problems/non-overlapping-intervals/)
```python
def eraseOverlapIntervals(intervals: list[list[int]]) -> int:
    # Greedy (sort by end) - O(n log n) time, O(1) space
    intervals.sort(key=lambda x: x[1])
    count = 0
    prev_end = float('-inf')

    for start, end in intervals:
        if start >= prev_end:
            prev_end = end
        else:
            count += 1

    return count
```

### 252. Meeting Rooms (Easy)
[View Problem](https://leetcode.com/problems/meeting-rooms/)
```python
def canAttendMeetings(intervals: list[list[int]]) -> bool:
    # Sort and check overlap - O(n log n) time, O(1) space
    intervals.sort(key=lambda x: x[0])

    for i in range(1, len(intervals)):
        if intervals[i][0] < intervals[i - 1][1]:
            return False

    return True
```

### 253. Meeting Rooms II (Medium)
[View Problem](https://leetcode.com/problems/meeting-rooms-ii/)
```python
def minMeetingRooms(intervals: list[list[int]]) -> int:
    # Two arrays (start/end times) - O(n log n) time, O(n) space
    starts = sorted(i[0] for i in intervals)
    ends = sorted(i[1] for i in intervals)

    rooms = 0
    end_ptr = 0

    for start in starts:
        if start < ends[end_ptr]:
            rooms += 1
        else:
            end_ptr += 1

    return rooms

    # Alternative: Min heap
    # import heapq
    # intervals.sort(key=lambda x: x[0])
    # heap = []
    # for start, end in intervals:
    #     if heap and heap[0] <= start:
    #         heapq.heappop(heap)
    #     heapq.heappush(heap, end)
    # return len(heap)
```

---

## Math & Geometry

### 48. Rotate Image (Medium)
[View Problem](https://leetcode.com/problems/rotate-image/)
```python
def rotate(matrix: list[list[int]]) -> None:
    # Transpose + Reverse - O(n^2) time, O(1) space
    n = len(matrix)

    # Transpose
    for i in range(n):
        for j in range(i + 1, n):
            matrix[i][j], matrix[j][i] = matrix[j][i], matrix[i][j]

    # Reverse each row
    for row in matrix:
        row.reverse()
```

### 54. Spiral Matrix (Medium)
[View Problem](https://leetcode.com/problems/spiral-matrix/)
```python
def spiralOrder(matrix: list[list[int]]) -> list[int]:
    # Boundary tracking - O(m*n) time, O(1) extra space
    result = []
    top, bottom = 0, len(matrix) - 1
    left, right = 0, len(matrix[0]) - 1

    while top <= bottom and left <= right:
        # Right
        for c in range(left, right + 1):
            result.append(matrix[top][c])
        top += 1

        # Down
        for r in range(top, bottom + 1):
            result.append(matrix[r][right])
        right -= 1

        # Left
        if top <= bottom:
            for c in range(right, left - 1, -1):
                result.append(matrix[bottom][c])
            bottom -= 1

        # Up
        if left <= right:
            for r in range(bottom, top - 1, -1):
                result.append(matrix[r][left])
            left += 1

    return result
```

### 73. Set Matrix Zeroes (Medium)
[View Problem](https://leetcode.com/problems/set-matrix-zeroes/)
```python
def setZeroes(matrix: list[list[int]]) -> None:
    # Use first row/col as markers - O(m*n) time, O(1) space
    m, n = len(matrix), len(matrix[0])
    first_row_zero = any(matrix[0][j] == 0 for j in range(n))
    first_col_zero = any(matrix[i][0] == 0 for i in range(m))

    # Mark zeros
    for i in range(1, m):
        for j in range(1, n):
            if matrix[i][j] == 0:
                matrix[i][0] = 0
                matrix[0][j] = 0

    # Set zeros based on markers
    for i in range(1, m):
        for j in range(1, n):
            if matrix[i][0] == 0 or matrix[0][j] == 0:
                matrix[i][j] = 0

    # Handle first row and column
    if first_row_zero:
        for j in range(n):
            matrix[0][j] = 0
    if first_col_zero:
        for i in range(m):
            matrix[i][0] = 0
```

### 202. Happy Number (Easy)
[View Problem](https://leetcode.com/problems/happy-number/)
```python
def isHappy(n: int) -> bool:
    # Floyd's cycle detection - O(log n) time, O(1) space
    def get_next(num):
        total = 0
        while num > 0:
            digit = num % 10
            total += digit * digit
            num //= 10
        return total

    slow = fast = n
    while True:
        slow = get_next(slow)
        fast = get_next(get_next(fast))
        if fast == 1:
            return True
        if slow == fast:
            return False
```

### 66. Plus One (Easy)
[View Problem](https://leetcode.com/problems/plus-one/)
```python
def plusOne(digits: list[int]) -> list[int]:
    # Right to left - O(n) time, O(1) space
    for i in range(len(digits) - 1, -1, -1):
        if digits[i] < 9:
            digits[i] += 1
            return digits
        digits[i] = 0

    return [1] + digits
```

### 50. Pow(x, n) (Medium)
[View Problem](https://leetcode.com/problems/powx-n/)
```python
def myPow(x: float, n: int) -> float:
    # Binary exponentiation - O(log n) time, O(1) space
    if n < 0:
        x = 1 / x
        n = -n

    result = 1
    while n:
        if n & 1:
            result *= x
        x *= x
        n >>= 1

    return result
```

### 43. Multiply Strings (Medium)
[View Problem](https://leetcode.com/problems/multiply-strings/)
```python
def multiply(num1: str, num2: str) -> str:
    # Grade school multiplication - O(m*n) time, O(m+n) space
    if num1 == "0" or num2 == "0":
        return "0"

    m, n = len(num1), len(num2)
    result = [0] * (m + n)

    for i in range(m - 1, -1, -1):
        for j in range(n - 1, -1, -1):
            product = int(num1[i]) * int(num2[j])
            pos1, pos2 = i + j, i + j + 1
            total = product + result[pos2]

            result[pos2] = total % 10
            result[pos1] += total // 10

    # Remove leading zeros
    start = 0
    while start < len(result) - 1 and result[start] == 0:
        start += 1

    return ''.join(map(str, result[start:]))
```

---

## Bit Manipulation

### 136. Single Number (Easy)
[View Problem](https://leetcode.com/problems/single-number/)
```python
def singleNumber(nums: list[int]) -> int:
    # XOR - O(n) time, O(1) space
    result = 0
    for num in nums:
        result ^= num
    return result
```

### 191. Number of 1 Bits (Easy)
[View Problem](https://leetcode.com/problems/number-of-1-bits/)
```python
def hammingWeight(n: int) -> int:
    # Brian Kernighan's algorithm - O(k) time where k = number of 1s
    count = 0
    while n:
        n &= (n - 1)  # Remove rightmost 1 bit
        count += 1
    return count
```

### 338. Counting Bits (Easy)
[View Problem](https://leetcode.com/problems/counting-bits/)
```python
def countBits(n: int) -> list[int]:
    # DP with bit manipulation - O(n) time, O(n) space
    dp = [0] * (n + 1)
    for i in range(1, n + 1):
        dp[i] = dp[i >> 1] + (i & 1)
    return dp
```

### 190. Reverse Bits (Easy)
[View Problem](https://leetcode.com/problems/reverse-bits/)
```python
def reverseBits(n: int) -> int:
    # Bit by bit - O(32) time, O(1) space
    result = 0
    for _ in range(32):
        result = (result << 1) | (n & 1)
        n >>= 1
    return result
```

### 268. Missing Number (Easy)
[View Problem](https://leetcode.com/problems/missing-number/)
```python
def missingNumber(nums: list[int]) -> int:
    # XOR - O(n) time, O(1) space
    n = len(nums)
    result = n
    for i, num in enumerate(nums):
        result ^= i ^ num
    return result

    # Alternative: Sum formula
    # return n * (n + 1) // 2 - sum(nums)
```

### 371. Sum of Two Integers (Medium)
[View Problem](https://leetcode.com/problems/sum-of-two-integers/)
```python
def getSum(a: int, b: int) -> int:
    # Bit manipulation - O(1) time, O(1) space
    # Handle Python's arbitrary precision integers
    MASK = 0xFFFFFFFF
    MAX_INT = 0x7FFFFFFF

    while b != 0:
        carry = ((a & b) << 1) & MASK
        a = (a ^ b) & MASK
        b = carry

    # Handle negative numbers
    return a if a <= MAX_INT else ~(a ^ MASK)
```

---

## Summary

| Difficulty | Count |
|------------|-------|
| Easy | 35 |
| Medium | 65 |
| **Total** | **100** |

---

*Good luck with your interview preparation!*
