+++
title = 'Leetcode Questions Part 3'
date = 2026-03-06T10:25:14-08:00
tags = ["leetcode"]
draft = false
+++

A curated list of 100 LeetCode problems for interview preparation with solution templates.

## Recommended Study Order

### 1. Array & Hashing - Fundamental operations
- [27. Remove Element](#27-remove-duplicates-from-sorted-array-ii-medium)
- [118. Pascal's Triangle](#118-pascals-triangle-easy)
- [119. Pascal's Triangle II](#119-pascals-triangle-ii-easy)
- [189. Rotate Array](#189-rotate-array-medium)
- [349. Intersection of Two Arrays](#349-intersection-of-two-arrays-easy)
- [350. Intersection of Two Arrays II](#350-intersection-of-two-arrays-ii-easy)
- [414. Third Maximum Number](#414-third-maximum-number-easy)
- [485. Max Consecutive Ones](#485-max-consecutive-ones-easy)
- [566. Reshape the Matrix](#566-reshape-the-matrix-easy)
- [1122. Relative Sort Array](#1122-relative-sort-array-easy)

### 2. Two Pointers - In-place transformations
- [27. Remove Duplicates from Sorted Array II](#27-remove-duplicates-from-sorted-array-ii-medium)
- [344. Reverse String](#344-reverse-string-easy)
- [345. Reverse Vowels of a String](#345-reverse-vowels-of-a-string-easy)
- [557. Reverse Words in a String III](#557-reverse-words-in-a-string-iii-easy)
- [905. Sort Array By Parity](#905-sort-array-by-parity-easy)
- [917. Reverse Only Letters](#917-reverse-only-letters-easy)
- [922. Sort Array By Parity II](#922-sort-array-by-parity-ii-easy)
- [925. Long Pressed Name](#925-long-pressed-name-easy)

### 3. Sliding Window - Subarray problems
- [1100. Find K-Length Substrings With No Repeated Characters](#1100-find-k-length-substrings-with-no-repeated-characters-medium)
- [1151. Minimum Swaps to Group All 1's Together](#1151-minimum-swaps-to-group-all-1s-together-medium)
- [1176. Diet Plan Performance](#1176-diet-plan-performance-easy)
- [1343. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold](#1343-number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold-medium)
- [1652. Defuse the Bomb](#1652-defuse-the-bomb-easy)
- [1984. Minimum Difference Between Highest and Lowest of K Scores](#1984-minimum-difference-between-highest-and-lowest-of-k-scores-easy)
- [2269. Find the K-Beauty of a Number](#2269-find-the-k-beauty-of-a-number-easy)

### 4. Stack - LIFO operations
- [225. Implement Stack using Queues](#225-implement-stack-using-queues-easy)
- [232. Implement Queue using Stacks](#232-implement-queue-using-stacks-easy)
- [682. Baseball Game](#682-baseball-game-easy)
- [1021. Remove Outermost Parentheses](#1021-remove-outermost-parentheses-easy)
- [1441. Build an Array With Stack Operations](#1441-build-an-array-with-stack-operations-medium)
- [1475. Final Prices With a Special Discount in a Shop](#1475-final-prices-with-a-special-discount-in-a-shop-easy)
- [1614. Maximum Nesting Depth of the Parentheses](#1614-maximum-nesting-depth-of-the-parentheses-easy)
- [2696. Minimum String Length After Removing Substrings](#2696-minimum-string-length-after-removing-substrings-easy)

### 5. Binary Search - Logarithmic search
- [374. Guess Number Higher or Lower](#374-guess-number-higher-or-lower-easy)
- [410. Split Array Largest Sum](#410-split-array-largest-sum-hard)
- [744. Find Smallest Letter Greater Than Target](#744-find-smallest-letter-greater-than-target-easy)
- [1283. Find the Smallest Divisor Given a Threshold](#1283-find-the-smallest-divisor-given-a-threshold-medium)
- [1351. Count Negative Numbers in a Sorted Matrix](#1351-count-negative-numbers-in-a-sorted-matrix-easy)
- [1539. Kth Missing Positive Number](#1539-kth-missing-positive-number-easy)
- [2089. Find Target Indices After Sorting Array](#2089-find-target-indices-after-sorting-array-easy)
- [2529. Maximum Count of Positive Integer and Negative Integer](#2529-maximum-count-of-positive-integer-and-negative-integer-easy)

### 6. Linked List - Pointer manipulation
- [237. Delete Node in a Linked List](#237-delete-node-in-a-linked-list-medium)
- [725. Split Linked List in Parts](#725-split-linked-list-in-parts-medium)
- [817. Linked List Components](#817-linked-list-components-medium)
- [876. Middle of the Linked List](#876-middle-of-the-linked-list-easy)
- [1019. Next Greater Node In Linked List](#1019-next-greater-node-in-linked-list-medium)
- [1290. Convert Binary Number in a Linked List to Integer](#1290-convert-binary-number-in-a-linked-list-to-integer-easy)
- [2095. Delete the Middle Node of a Linked List](#2095-delete-the-middle-node-of-a-linked-list-medium)
- [2130. Maximum Twin Sum of a Linked List](#2130-maximum-twin-sum-of-a-linked-list-medium)

### 7. Trees - Recursive traversals
- [108. Convert Sorted Array to Binary Search Tree](#108-convert-sorted-array-to-binary-search-tree-easy)
- [257. Binary Tree Paths](#257-binary-tree-paths-easy)
- [404. Sum of Left Leaves](#404-sum-of-left-leaves-easy)
- [501. Find Mode in Binary Search Tree](#501-find-mode-in-binary-search-tree-easy)
- [530. Minimum Absolute Difference in BST](#530-minimum-absolute-difference-in-bst-easy)
- [617. Merge Two Binary Trees](#617-merge-two-binary-trees-easy)
- [637. Average of Levels in Binary Tree](#637-average-of-levels-in-binary-tree-easy)
- [653. Two Sum IV - Input is a BST](#653-two-sum-iv-input-is-a-bst-easy)
- [700. Search in a Binary Search Tree](#700-search-in-a-binary-search-tree-easy)
- [872. Leaf-Similar Trees](#872-leaf-similar-trees-easy)

### 8. Heap/Priority Queue - Priority operations
- [506. Relative Ranks](#506-relative-ranks-easy)
- [1337. The K Weakest Rows in a Matrix](#1337-the-k-weakest-rows-in-a-matrix-easy)
- [1962. Remove Stones to Minimize the Total](#1962-remove-stones-to-minimize-the-total-medium)
- [2208. Minimum Operations to Halve Array Sum](#2208-minimum-operations-to-halve-array-sum-medium)
- [2336. Smallest Number in Infinite Set](#2336-smallest-number-in-infinite-set-medium)
- [2462. Total Cost to Hire K Workers](#2462-total-cost-to-hire-k-workers-medium)

### 9. Backtracking - Exhaustive search
- [401. Binary Watch](#401-binary-watch-easy)
- [1286. Iterator for Combination](#1286-iterator-for-combination-medium)
- [1415. The k-th Lexicographical String of All Happy Strings of Length n](#1415-the-k-th-lexicographical-string-of-all-happy-strings-of-length-n-medium)
- [1922. Count Good Numbers](#1922-count-good-numbers-medium)
- [1980. Find Unique Binary String](#1980-find-unique-binary-string-medium)
- [2044. Count Number of Maximum Bitwise-OR Subsets](#2044-count-number-of-maximum-bitwise-or-subsets-medium)

### 10. Graphs - Connectivity and paths
- [463. Island Perimeter](#463-island-perimeter-easy)
- [733. Flood Fill](#733-flood-fill-easy)
- [997. Find the Town Judge](#997-find-the-town-judge-easy)
- [1091. Shortest Path in Binary Matrix](#1091-shortest-path-in-binary-matrix-medium)
- [1162. As Far from Land as Possible](#1162-as-far-from-land-as-possible-medium)
- [1971. Find if Path Exists in Graph](#1971-find-if-path-exists-in-graph-easy)
- [2101. Detonate the Maximum Bombs](#2101-detonate-the-maximum-bombs-medium)
- [2316. Count Unreachable Pairs of Nodes in an Undirected Graph](#2316-count-unreachable-pairs-of-nodes-in-an-undirected-graph-medium)

### 11. Dynamic Programming - Optimal substructure
- [303. Range Sum Query - Immutable](#303-range-sum-query-immutable-easy)
- [931. Minimum Falling Path Sum](#931-minimum-falling-path-sum-medium)
- [983. Minimum Cost For Tickets](#983-minimum-cost-for-tickets-medium)
- [1014. Best Sightseeing Pair](#1014-best-sightseeing-pair-medium)
- [1035. Uncrossed Lines](#1035-uncrossed-lines-medium)
- [1049. Last Stone Weight II](#1049-last-stone-weight-ii-medium)
- [1277. Count Square Submatrices with All Ones](#1277-count-square-submatrices-with-all-ones-medium)
- [2466. Count Ways To Build Good Strings](#2466-count-ways-to-build-good-strings-medium)

### 12. Greedy - Local optimum strategies
- [605. Can Place Flowers](#605-can-place-flowers-easy)
- [942. DI String Match](#942-di-string-match-easy)
- [1217. Minimum Cost to Move Chips to The Same Position](#1217-minimum-cost-to-move-chips-to-the-same-position-easy)
- [1323. Maximum 69 Number](#1323-maximum-69-number-easy)
- [1518. Water Bottles](#1518-water-bottles-easy)
- [2144. Minimum Cost of Buying Candies With Discount](#2144-minimum-cost-of-buying-candies-with-discount-easy)

### 13. Math & Geometry - Number theory
- [168. Excel Sheet Column Title](#168-excel-sheet-column-title-easy)
- [171. Excel Sheet Column Number](#171-excel-sheet-column-number-easy)
- [172. Factorial Trailing Zeroes](#172-factorial-trailing-zeroes-medium)
- [204. Count Primes](#204-count-primes-medium)
- [263. Ugly Number](#263-ugly-number-easy)
- [326. Power of Three](#326-power-of-three-easy)
- [412. Fizz Buzz](#412-fizz-buzz-easy)

### 14. Bit Manipulation - Binary operations
- [693. Binary Number with Alternating Bits](#693-binary-number-with-alternating-bits-easy)
- [762. Prime Number of Set Bits in Binary Representation](#762-prime-number-of-set-bits-in-binary-representation-easy)
- [1009. Complement of Base 10 Integer](#1009-complement-of-base-10-integer-easy)
- [1486. XOR Operation in an Array](#1486-xor-operation-in-an-array-easy)
- [1720. Decode XORed Array](#1720-decode-xored-array-easy)
- [2433. Find The Original Array of Prefix Xor](#2433-find-the-original-array-of-prefix-xor-medium)


---

## Array & Hashing

### 27. Remove Element (Easy)
[View Problem](https://leetcode.com/problems/remove-element/)
```python
def removeElement(nums: list[int], val: int) -> int:
    # Two pointers - O(n) time, O(1) space
    k = 0
    for i in range(len(nums)):
        if nums[i] != val:
            nums[k] = nums[i]
            k += 1
    return k
```

### 118. Pascal's Triangle (Easy)
[View Problem](https://leetcode.com/problems/pascals-triangle/)
```python
def generate(numRows: int) -> list[list[int]]:
    # Build row by row - O(n^2) time, O(n^2) space
    result = []
    for i in range(numRows):
        row = [1] * (i + 1)
        for j in range(1, i):
            row[j] = result[i - 1][j - 1] + result[i - 1][j]
        result.append(row)
    return result
```

### 119. Pascal's Triangle II (Easy)
[View Problem](https://leetcode.com/problems/pascals-triangle-ii/)
```python
def getRow(rowIndex: int) -> list[int]:
    # Build in place - O(n) time, O(n) space
    row = [1] * (rowIndex + 1)
    for i in range(2, rowIndex + 1):
        for j in range(i - 1, 0, -1):
            row[j] += row[j - 1]
    return row
```

### 189. Rotate Array (Medium)
[View Problem](https://leetcode.com/problems/rotate-array/)
```python
def rotate(nums: list[int], k: int) -> None:
    # Reverse approach - O(n) time, O(1) space
    n = len(nums)
    k = k % n

    def reverse(start, end):
        while start < end:
            nums[start], nums[end] = nums[end], nums[start]
            start += 1
            end -= 1

    reverse(0, n - 1)
    reverse(0, k - 1)
    reverse(k, n - 1)
```

### 349. Intersection of Two Arrays (Easy)
[View Problem](https://leetcode.com/problems/intersection-of-two-arrays/)
```python
def intersection(nums1: list[int], nums2: list[int]) -> list[int]:
    # Set intersection - O(n + m) time, O(n + m) space
    return list(set(nums1) & set(nums2))
```

### 350. Intersection of Two Arrays II (Easy)
[View Problem](https://leetcode.com/problems/intersection-of-two-arrays-ii/)
```python
def intersect(nums1: list[int], nums2: list[int]) -> list[int]:
    # Counter approach - O(n + m) time, O(min(n, m)) space
    from collections import Counter

    count1 = Counter(nums1)
    result = []

    for num in nums2:
        if count1[num] > 0:
            result.append(num)
            count1[num] -= 1

    return result
```

### 414. Third Maximum Number (Easy)
[View Problem](https://leetcode.com/problems/third-maximum-number/)
```python
def thirdMax(nums: list[int]) -> int:
    # Track top 3 - O(n) time, O(1) space
    first = second = third = float('-inf')

    for num in nums:
        if num in (first, second, third):
            continue
        if num > first:
            first, second, third = num, first, second
        elif num > second:
            second, third = num, second
        elif num > third:
            third = num

    return third if third != float('-inf') else first
```

### 485. Max Consecutive Ones (Easy)
[View Problem](https://leetcode.com/problems/max-consecutive-ones/)
```python
def findMaxConsecutiveOnes(nums: list[int]) -> int:
    # Single pass - O(n) time, O(1) space
    max_count = 0
    current = 0

    for num in nums:
        if num == 1:
            current += 1
            max_count = max(max_count, current)
        else:
            current = 0

    return max_count
```

### 566. Reshape the Matrix (Easy)
[View Problem](https://leetcode.com/problems/reshape-the-matrix/)
```python
def matrixReshape(mat: list[list[int]], r: int, c: int) -> list[list[int]]:
    # Flatten and reshape - O(m*n) time, O(1) extra space
    m, n = len(mat), len(mat[0])
    if m * n != r * c:
        return mat

    result = [[0] * c for _ in range(r)]
    for i in range(m * n):
        result[i // c][i % c] = mat[i // n][i % n]

    return result
```

### 1122. Relative Sort Array (Easy)
[View Problem](https://leetcode.com/problems/relative-sort-array/)
```python
def relativeSortArray(arr1: list[int], arr2: list[int]) -> list[int]:
    # Custom sort - O(n log n) time, O(n) space
    order = {num: i for i, num in enumerate(arr2)}
    return sorted(arr1, key=lambda x: (order.get(x, len(arr2)), x))
```

---

## Two Pointers

### 344. Reverse String (Easy)
[View Problem](https://leetcode.com/problems/reverse-string/)
```python
def reverseString(s: list[str]) -> None:
    # Two pointers - O(n) time, O(1) space
    left, right = 0, len(s) - 1
    while left < right:
        s[left], s[right] = s[right], s[left]
        left += 1
        right -= 1
```

### 345. Reverse Vowels of a String (Easy)
[View Problem](https://leetcode.com/problems/reverse-vowels-of-a-string/)
```python
def reverseVowels(s: str) -> str:
    # Two pointers - O(n) time, O(n) space
    vowels = set('aeiouAEIOU')
    s = list(s)
    left, right = 0, len(s) - 1

    while left < right:
        while left < right and s[left] not in vowels:
            left += 1
        while left < right and s[right] not in vowels:
            right -= 1
        s[left], s[right] = s[right], s[left]
        left += 1
        right -= 1

    return ''.join(s)
```

### 557. Reverse Words in a String III (Easy)
[View Problem](https://leetcode.com/problems/reverse-words-in-a-string-iii/)
```python
def reverseWords(s: str) -> str:
    # Reverse each word - O(n) time, O(n) space
    return ' '.join(word[::-1] for word in s.split())
```

### 925. Long Pressed Name (Easy)
[View Problem](https://leetcode.com/problems/long-pressed-name/)
```python
def isLongPressedName(name: str, typed: str) -> bool:
    # Two pointers - O(n + m) time, O(1) space
    i = j = 0

    while j < len(typed):
        if i < len(name) and name[i] == typed[j]:
            i += 1
        elif j > 0 and typed[j] == typed[j - 1]:
            pass
        else:
            return False
        j += 1

    return i == len(name)
```

### 905. Sort Array By Parity (Easy)
[View Problem](https://leetcode.com/problems/sort-array-by-parity/)
```python
def sortArrayByParity(nums: list[int]) -> list[int]:
    # Two pointers - O(n) time, O(1) space
    left, right = 0, len(nums) - 1

    while left < right:
        if nums[left] % 2 > nums[right] % 2:
            nums[left], nums[right] = nums[right], nums[left]
        if nums[left] % 2 == 0:
            left += 1
        if nums[right] % 2 == 1:
            right -= 1

    return nums
```

### 922. Sort Array By Parity II (Easy)
[View Problem](https://leetcode.com/problems/sort-array-by-parity-ii/)
```python
def sortArrayByParityII(nums: list[int]) -> list[int]:
    # Two pointers - O(n) time, O(1) space
    even, odd = 0, 1
    n = len(nums)

    while even < n and odd < n:
        while even < n and nums[even] % 2 == 0:
            even += 2
        while odd < n and nums[odd] % 2 == 1:
            odd += 2
        if even < n and odd < n:
            nums[even], nums[odd] = nums[odd], nums[even]

    return nums
```

### 917. Reverse Only Letters (Easy)
[View Problem](https://leetcode.com/problems/reverse-only-letters/)
```python
def reverseOnlyLetters(s: str) -> str:
    # Two pointers - O(n) time, O(n) space
    s = list(s)
    left, right = 0, len(s) - 1

    while left < right:
        while left < right and not s[left].isalpha():
            left += 1
        while left < right and not s[right].isalpha():
            right -= 1
        s[left], s[right] = s[right], s[left]
        left += 1
        right -= 1

    return ''.join(s)
```

### 167. Two Sum II - Input Array Is Sorted (Medium) - Variant
### 27. Remove Duplicates from Sorted Array II (Medium)
[View Problem](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/)
```python
def removeDuplicates(nums: list[int]) -> int:
    # Two pointers - O(n) time, O(1) space
    if len(nums) <= 2:
        return len(nums)

    k = 2
    for i in range(2, len(nums)):
        if nums[i] != nums[k - 2]:
            nums[k] = nums[i]
            k += 1

    return k
```

---

## Sliding Window

### 1343. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold (Medium)
[View Problem](https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/)
```python
def numOfSubarrays(arr: list[int], k: int, threshold: int) -> int:
    # Sliding window - O(n) time, O(1) space
    target = threshold * k
    window_sum = sum(arr[:k])
    count = 1 if window_sum >= target else 0

    for i in range(k, len(arr)):
        window_sum += arr[i] - arr[i - k]
        if window_sum >= target:
            count += 1

    return count
```

### 1100. Find K-Length Substrings With No Repeated Characters (Medium)
[View Problem](https://leetcode.com/problems/find-k-length-substrings-with-no-repeated-characters/)
```python
def numKLenSubstrNoRepeats(s: str, k: int) -> int:
    # Sliding window - O(n) time, O(k) space
    if k > 26 or k > len(s):
        return 0

    count = 0
    char_count = {}

    for i in range(len(s)):
        char_count[s[i]] = char_count.get(s[i], 0) + 1

        if i >= k:
            left_char = s[i - k]
            char_count[left_char] -= 1
            if char_count[left_char] == 0:
                del char_count[left_char]

        if i >= k - 1 and len(char_count) == k:
            count += 1

    return count
```

### 1151. Minimum Swaps to Group All 1's Together (Medium)
[View Problem](https://leetcode.com/problems/minimum-swaps-to-group-all-1s-together/)
```python
def minSwaps(data: list[int]) -> int:
    # Sliding window - O(n) time, O(1) space
    total_ones = sum(data)
    if total_ones == 0:
        return 0

    window_ones = sum(data[:total_ones])
    max_ones = window_ones

    for i in range(total_ones, len(data)):
        window_ones += data[i] - data[i - total_ones]
        max_ones = max(max_ones, window_ones)

    return total_ones - max_ones
```

### 1176. Diet Plan Performance (Easy)
[View Problem](https://leetcode.com/problems/diet-plan-performance/)
```python
def dietPlanPerformance(calories: list[int], k: int, lower: int, upper: int) -> int:
    # Sliding window - O(n) time, O(1) space
    points = 0
    window_sum = sum(calories[:k])

    if window_sum < lower:
        points -= 1
    elif window_sum > upper:
        points += 1

    for i in range(k, len(calories)):
        window_sum += calories[i] - calories[i - k]
        if window_sum < lower:
            points -= 1
        elif window_sum > upper:
            points += 1

    return points
```

### 1652. Defuse the Bomb (Easy)
[View Problem](https://leetcode.com/problems/defuse-the-bomb/)
```python
def decrypt(code: list[int], k: int) -> list[int]:
    # Sliding window - O(n) time, O(n) space
    n = len(code)
    result = [0] * n

    if k == 0:
        return result

    start = 1 if k > 0 else n + k
    end = k if k > 0 else n - 1

    window_sum = sum(code[start:end + 1])

    for i in range(n):
        result[i] = window_sum
        window_sum -= code[start % n]
        start += 1
        end += 1
        window_sum += code[end % n]

    return result
```

### 1984. Minimum Difference Between Highest and Lowest of K Scores (Easy)
[View Problem](https://leetcode.com/problems/minimum-difference-between-highest-and-lowest-of-k-scores/)
```python
def minimumDifference(nums: list[int], k: int) -> int:
    # Sort + Sliding window - O(n log n) time, O(1) space
    if k == 1:
        return 0

    nums.sort()
    min_diff = float('inf')

    for i in range(len(nums) - k + 1):
        min_diff = min(min_diff, nums[i + k - 1] - nums[i])

    return min_diff
```

### 2269. Find the K-Beauty of a Number (Easy)
[View Problem](https://leetcode.com/problems/find-the-k-beauty-of-a-number/)
```python
def divisorSubstrings(num: int, k: int) -> int:
    # Sliding window on string - O(n) time, O(n) space
    s = str(num)
    count = 0

    for i in range(len(s) - k + 1):
        sub = int(s[i:i + k])
        if sub != 0 and num % sub == 0:
            count += 1

    return count
```

---

## Stack

### 225. Implement Stack using Queues (Easy)
[View Problem](https://leetcode.com/problems/implement-stack-using-queues/)
```python
from collections import deque

class MyStack:
    def __init__(self):
        self.queue = deque()

    def push(self, x: int) -> None:
        # O(n) push
        self.queue.append(x)
        for _ in range(len(self.queue) - 1):
            self.queue.append(self.queue.popleft())

    def pop(self) -> int:
        return self.queue.popleft()

    def top(self) -> int:
        return self.queue[0]

    def empty(self) -> bool:
        return len(self.queue) == 0
```

### 232. Implement Queue using Stacks (Easy)
[View Problem](https://leetcode.com/problems/implement-queue-using-stacks/)
```python
class MyQueue:
    def __init__(self):
        self.in_stack = []
        self.out_stack = []

    def push(self, x: int) -> None:
        self.in_stack.append(x)

    def pop(self) -> int:
        self._transfer()
        return self.out_stack.pop()

    def peek(self) -> int:
        self._transfer()
        return self.out_stack[-1]

    def empty(self) -> bool:
        return not self.in_stack and not self.out_stack

    def _transfer(self):
        if not self.out_stack:
            while self.in_stack:
                self.out_stack.append(self.in_stack.pop())
```

### 682. Baseball Game (Easy)
[View Problem](https://leetcode.com/problems/baseball-game/)
```python
def calPoints(operations: list[str]) -> int:
    # Stack - O(n) time, O(n) space
    stack = []

    for op in operations:
        if op == '+':
            stack.append(stack[-1] + stack[-2])
        elif op == 'D':
            stack.append(stack[-1] * 2)
        elif op == 'C':
            stack.pop()
        else:
            stack.append(int(op))

    return sum(stack)
```

### 1021. Remove Outermost Parentheses (Easy)
[View Problem](https://leetcode.com/problems/remove-outermost-parentheses/)
```python
def removeOuterParentheses(s: str) -> str:
    # Counter approach - O(n) time, O(n) space
    result = []
    depth = 0

    for char in s:
        if char == '(':
            if depth > 0:
                result.append(char)
            depth += 1
        else:
            depth -= 1
            if depth > 0:
                result.append(char)

    return ''.join(result)
```

### 1441. Build an Array With Stack Operations (Medium)
[View Problem](https://leetcode.com/problems/build-an-array-with-stack-operations/)
```python
def buildArray(target: list[int], n: int) -> list[str]:
    # Simulation - O(n) time, O(n) space
    result = []
    target_set = set(target)
    max_val = target[-1]

    for i in range(1, max_val + 1):
        result.append("Push")
        if i not in target_set:
            result.append("Pop")

    return result
```

### 1475. Final Prices With a Special Discount in a Shop (Easy)
[View Problem](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/)
```python
def finalPrices(prices: list[int]) -> list[int]:
    # Monotonic stack - O(n) time, O(n) space
    result = prices[:]
    stack = []

    for i, price in enumerate(prices):
        while stack and prices[stack[-1]] >= price:
            result[stack.pop()] -= price
        stack.append(i)

    return result
```

### 1614. Maximum Nesting Depth of the Parentheses (Easy)
[View Problem](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/)
```python
def maxDepth(s: str) -> int:
    # Counter - O(n) time, O(1) space
    max_depth = 0
    current = 0

    for char in s:
        if char == '(':
            current += 1
            max_depth = max(max_depth, current)
        elif char == ')':
            current -= 1

    return max_depth
```

### 2696. Minimum String Length After Removing Substrings (Easy)
[View Problem](https://leetcode.com/problems/minimum-string-length-after-removing-substrings/)
```python
def minLength(s: str) -> int:
    # Stack - O(n) time, O(n) space
    stack = []

    for char in s:
        if stack and ((stack[-1] == 'A' and char == 'B') or
                      (stack[-1] == 'C' and char == 'D')):
            stack.pop()
        else:
            stack.append(char)

    return len(stack)
```

---

## Binary Search

### 374. Guess Number Higher or Lower (Easy)
[View Problem](https://leetcode.com/problems/guess-number-higher-or-lower/)
```python
def guessNumber(n: int) -> int:
    # Binary search - O(log n) time, O(1) space
    # guess(num) API returns: -1 if my number is lower, 1 if higher, 0 if correct
    left, right = 1, n

    while left <= right:
        mid = (left + right) // 2
        result = guess(mid)
        if result == 0:
            return mid
        elif result == -1:
            right = mid - 1
        else:
            left = mid + 1

    return -1
```

### 744. Find Smallest Letter Greater Than Target (Easy)
[View Problem](https://leetcode.com/problems/find-smallest-letter-greater-than-target/)
```python
def nextGreatestLetter(letters: list[str], target: str) -> str:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(letters)

    while left < right:
        mid = (left + right) // 2
        if letters[mid] <= target:
            left = mid + 1
        else:
            right = mid

    return letters[left % len(letters)]
```

### 1539. Kth Missing Positive Number (Easy)
[View Problem](https://leetcode.com/problems/kth-missing-positive-number/)
```python
def findKthPositive(arr: list[int], k: int) -> int:
    # Binary search - O(log n) time, O(1) space
    left, right = 0, len(arr)

    while left < right:
        mid = (left + right) // 2
        # Missing count at index mid = arr[mid] - (mid + 1)
        if arr[mid] - mid - 1 < k:
            left = mid + 1
        else:
            right = mid

    return left + k
```

### 1351. Count Negative Numbers in a Sorted Matrix (Easy)
[View Problem](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/)
```python
def countNegatives(grid: list[list[int]]) -> int:
    # Staircase approach - O(m + n) time, O(1) space
    m, n = len(grid), len(grid[0])
    count = 0
    row, col = 0, n - 1

    while row < m and col >= 0:
        if grid[row][col] < 0:
            count += m - row
            col -= 1
        else:
            row += 1

    return count
```

### 2089. Find Target Indices After Sorting Array (Easy)
[View Problem](https://leetcode.com/problems/find-target-indices-after-sorting-array/)
```python
def targetIndices(nums: list[int], target: int) -> list[int]:
    # Count approach - O(n) time, O(1) space
    less_than = sum(1 for x in nums if x < target)
    equal = sum(1 for x in nums if x == target)
    return list(range(less_than, less_than + equal))
```

### 2529. Maximum Count of Positive Integer and Negative Integer (Easy)
[View Problem](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/)
```python
def maximumCount(nums: list[int]) -> int:
    # Binary search - O(log n) time, O(1) space
    from bisect import bisect_left, bisect_right

    neg_count = bisect_left(nums, 0)
    pos_count = len(nums) - bisect_right(nums, 0)

    return max(neg_count, pos_count)
```

### 410. Split Array Largest Sum (Hard)
[View Problem](https://leetcode.com/problems/split-array-largest-sum/)
```python
def splitArray(nums: list[int], k: int) -> int:
    # Binary search on answer - O(n log sum) time, O(1) space
    def can_split(max_sum):
        count = 1
        current = 0
        for num in nums:
            if current + num > max_sum:
                count += 1
                current = num
            else:
                current += num
        return count <= k

    left, right = max(nums), sum(nums)

    while left < right:
        mid = (left + right) // 2
        if can_split(mid):
            right = mid
        else:
            left = mid + 1

    return left
```

### 1283. Find the Smallest Divisor Given a Threshold (Medium)
[View Problem](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/)
```python
def smallestDivisor(nums: list[int], threshold: int) -> int:
    # Binary search on answer - O(n log max) time, O(1) space
    import math

    def compute_sum(divisor):
        return sum(math.ceil(num / divisor) for num in nums)

    left, right = 1, max(nums)

    while left < right:
        mid = (left + right) // 2
        if compute_sum(mid) <= threshold:
            right = mid
        else:
            left = mid + 1

    return left
```

---

## Linked List

### 237. Delete Node in a Linked List (Medium)
[View Problem](https://leetcode.com/problems/delete-node-in-a-linked-list/)
```python
def deleteNode(node):
    # Copy next value and skip - O(1) time, O(1) space
    node.val = node.next.val
    node.next = node.next.next
```

### 876. Middle of the Linked List (Easy)
[View Problem](https://leetcode.com/problems/middle-of-the-linked-list/)
```python
def middleNode(head: ListNode) -> ListNode:
    # Slow and fast pointers - O(n) time, O(1) space
    slow = fast = head

    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next

    return slow
```

### 1290. Convert Binary Number in a Linked List to Integer (Easy)
[View Problem](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/)
```python
def getDecimalValue(head: ListNode) -> int:
    # Bit manipulation - O(n) time, O(1) space
    result = 0
    while head:
        result = (result << 1) | head.val
        head = head.next
    return result
```

### 725. Split Linked List in Parts (Medium)
[View Problem](https://leetcode.com/problems/split-linked-list-in-parts/)
```python
def splitListToParts(head: ListNode, k: int) -> list[ListNode]:
    # Calculate sizes - O(n) time, O(k) space
    length = 0
    curr = head
    while curr:
        length += 1
        curr = curr.next

    base_size = length // k
    extra = length % k
    result = []
    curr = head

    for i in range(k):
        result.append(curr)
        size = base_size + (1 if i < extra else 0)
        for _ in range(size - 1):
            if curr:
                curr = curr.next
        if curr:
            next_head = curr.next
            curr.next = None
            curr = next_head

    return result
```

### 817. Linked List Components (Medium)
[View Problem](https://leetcode.com/problems/linked-list-components/)
```python
def numComponents(head: ListNode, nums: list[int]) -> int:
    # Set lookup - O(n) time, O(n) space
    nums_set = set(nums)
    count = 0
    in_component = False

    while head:
        if head.val in nums_set:
            if not in_component:
                count += 1
                in_component = True
        else:
            in_component = False
        head = head.next

    return count
```

### 1019. Next Greater Node In Linked List (Medium)
[View Problem](https://leetcode.com/problems/next-greater-node-in-linked-list/)
```python
def nextLargerNodes(head: ListNode) -> list[int]:
    # Monotonic stack - O(n) time, O(n) space
    values = []
    while head:
        values.append(head.val)
        head = head.next

    result = [0] * len(values)
    stack = []

    for i, val in enumerate(values):
        while stack and values[stack[-1]] < val:
            result[stack.pop()] = val
        stack.append(i)

    return result
```

### 2095. Delete the Middle Node of a Linked List (Medium)
[View Problem](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/)
```python
def deleteMiddle(head: ListNode) -> ListNode:
    # Slow and fast pointers - O(n) time, O(1) space
    if not head.next:
        return None

    slow = fast = head
    prev = None

    while fast and fast.next:
        prev = slow
        slow = slow.next
        fast = fast.next.next

    prev.next = slow.next
    return head
```

### 2130. Maximum Twin Sum of a Linked List (Medium)
[View Problem](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/)
```python
def pairSum(head: ListNode) -> int:
    # Find middle, reverse, compare - O(n) time, O(1) space
    # Find middle
    slow = fast = head
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next

    # Reverse second half
    prev = None
    while slow:
        next_node = slow.next
        slow.next = prev
        prev = slow
        slow = next_node

    # Compare pairs
    max_sum = 0
    first, second = head, prev
    while second:
        max_sum = max(max_sum, first.val + second.val)
        first = first.next
        second = second.next

    return max_sum
```

---

## Trees

### 108. Convert Sorted Array to Binary Search Tree (Easy)
[View Problem](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
```python
def sortedArrayToBST(nums: list[int]) -> TreeNode:
    # Recursive - O(n) time, O(log n) space
    def build(left, right):
        if left > right:
            return None
        mid = (left + right) // 2
        node = TreeNode(nums[mid])
        node.left = build(left, mid - 1)
        node.right = build(mid + 1, right)
        return node

    return build(0, len(nums) - 1)
```

### 257. Binary Tree Paths (Easy)
[View Problem](https://leetcode.com/problems/binary-tree-paths/)
```python
def binaryTreePaths(root: TreeNode) -> list[str]:
    # DFS - O(n) time, O(n) space
    result = []

    def dfs(node, path):
        if not node:
            return
        path += str(node.val)
        if not node.left and not node.right:
            result.append(path)
        else:
            dfs(node.left, path + "->")
            dfs(node.right, path + "->")

    dfs(root, "")
    return result
```

### 404. Sum of Left Leaves (Easy)
[View Problem](https://leetcode.com/problems/sum-of-left-leaves/)
```python
def sumOfLeftLeaves(root: TreeNode) -> int:
    # DFS - O(n) time, O(h) space
    def dfs(node, is_left):
        if not node:
            return 0
        if not node.left and not node.right:
            return node.val if is_left else 0
        return dfs(node.left, True) + dfs(node.right, False)

    return dfs(root, False)
```

### 501. Find Mode in Binary Search Tree (Easy)
[View Problem](https://leetcode.com/problems/find-mode-in-binary-search-tree/)
```python
def findMode(root: TreeNode) -> list[int]:
    # Inorder traversal - O(n) time, O(n) space
    modes = []
    max_count = 0
    current_count = 0
    current_val = None

    def inorder(node):
        nonlocal max_count, current_count, current_val, modes
        if not node:
            return

        inorder(node.left)

        if node.val == current_val:
            current_count += 1
        else:
            current_val = node.val
            current_count = 1

        if current_count > max_count:
            max_count = current_count
            modes = [current_val]
        elif current_count == max_count:
            modes.append(current_val)

        inorder(node.right)

    inorder(root)
    return modes
```

### 530. Minimum Absolute Difference in BST (Easy)
[View Problem](https://leetcode.com/problems/minimum-absolute-difference-in-bst/)
```python
def getMinimumDifference(root: TreeNode) -> int:
    # Inorder traversal - O(n) time, O(h) space
    prev = None
    min_diff = float('inf')

    def inorder(node):
        nonlocal prev, min_diff
        if not node:
            return

        inorder(node.left)

        if prev is not None:
            min_diff = min(min_diff, node.val - prev)
        prev = node.val

        inorder(node.right)

    inorder(root)
    return min_diff
```

### 617. Merge Two Binary Trees (Easy)
[View Problem](https://leetcode.com/problems/merge-two-binary-trees/)
```python
def mergeTrees(root1: TreeNode, root2: TreeNode) -> TreeNode:
    # Recursive merge - O(n) time, O(h) space
    if not root1:
        return root2
    if not root2:
        return root1

    root1.val += root2.val
    root1.left = mergeTrees(root1.left, root2.left)
    root1.right = mergeTrees(root1.right, root2.right)

    return root1
```

### 637. Average of Levels in Binary Tree (Easy)
[View Problem](https://leetcode.com/problems/average-of-levels-in-binary-tree/)
```python
def averageOfLevels(root: TreeNode) -> list[float]:
    # BFS - O(n) time, O(n) space
    from collections import deque

    result = []
    queue = deque([root])

    while queue:
        level_sum = 0
        level_size = len(queue)

        for _ in range(level_size):
            node = queue.popleft()
            level_sum += node.val
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)

        result.append(level_sum / level_size)

    return result
```

### 653. Two Sum IV - Input is a BST (Easy)
[View Problem](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/)
```python
def findTarget(root: TreeNode, k: int) -> bool:
    # HashSet - O(n) time, O(n) space
    seen = set()

    def dfs(node):
        if not node:
            return False
        if k - node.val in seen:
            return True
        seen.add(node.val)
        return dfs(node.left) or dfs(node.right)

    return dfs(root)
```

### 700. Search in a Binary Search Tree (Easy)
[View Problem](https://leetcode.com/problems/search-in-a-binary-search-tree/)
```python
def searchBST(root: TreeNode, val: int) -> TreeNode:
    # Iterative - O(h) time, O(1) space
    while root:
        if root.val == val:
            return root
        root = root.left if val < root.val else root.right
    return None
```

### 872. Leaf-Similar Trees (Easy)
[View Problem](https://leetcode.com/problems/leaf-similar-trees/)
```python
def leafSimilar(root1: TreeNode, root2: TreeNode) -> bool:
    # DFS - O(n + m) time, O(n + m) space
    def get_leaves(node):
        if not node:
            return []
        if not node.left and not node.right:
            return [node.val]
        return get_leaves(node.left) + get_leaves(node.right)

    return get_leaves(root1) == get_leaves(root2)
```

---

## Heap / Priority Queue

### 1337. The K Weakest Rows in a Matrix (Easy)
[View Problem](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/)
```python
def kWeakestRows(mat: list[list[int]], k: int) -> list[int]:
    # Min heap - O(m log m) time, O(m) space
    import heapq

    strength = [(sum(row), i) for i, row in enumerate(mat)]
    heapq.heapify(strength)

    return [heapq.heappop(strength)[1] for _ in range(k)]
```

### 1046. Last Stone Weight (Easy) - Variant
### 506. Relative Ranks (Easy)
[View Problem](https://leetcode.com/problems/relative-ranks/)
```python
def findRelativeRanks(score: list[int]) -> list[str]:
    # Sort with indices - O(n log n) time, O(n) space
    sorted_indices = sorted(range(len(score)), key=lambda i: -score[i])
    result = [""] * len(score)

    medals = ["Gold Medal", "Silver Medal", "Bronze Medal"]

    for rank, idx in enumerate(sorted_indices):
        if rank < 3:
            result[idx] = medals[rank]
        else:
            result[idx] = str(rank + 1)

    return result
```

### 703. Kth Largest Element in a Stream (Easy) - Variant
### 1046. Last Stone Weight (Easy) - Variant
### 1962. Remove Stones to Minimize the Total (Medium)
[View Problem](https://leetcode.com/problems/remove-stones-to-minimize-the-total/)
```python
def minStoneSum(piles: list[int], k: int) -> int:
    # Max heap - O((n + k) log n) time, O(n) space
    import heapq

    # Negate for max heap
    max_heap = [-p for p in piles]
    heapq.heapify(max_heap)

    for _ in range(k):
        largest = -heapq.heappop(max_heap)
        heapq.heappush(max_heap, -(largest - largest // 2))

    return -sum(max_heap)
```

### 2208. Minimum Operations to Halve Array Sum (Medium)
[View Problem](https://leetcode.com/problems/minimum-operations-to-halve-array-sum/)
```python
def halveArray(nums: list[int]) -> int:
    # Max heap - O(n log n) time, O(n) space
    import heapq

    total = sum(nums)
    target = total / 2
    max_heap = [-num for num in nums]
    heapq.heapify(max_heap)

    operations = 0
    current_sum = total

    while current_sum > target:
        largest = -heapq.heappop(max_heap)
        half = largest / 2
        current_sum -= half
        heapq.heappush(max_heap, -half)
        operations += 1

    return operations
```

### 2462. Total Cost to Hire K Workers (Medium)
[View Problem](https://leetcode.com/problems/total-cost-to-hire-k-workers/)
```python
def totalCost(costs: list[int], k: int, candidates: int) -> int:
    # Two heaps - O(k log candidates) time
    import heapq

    n = len(costs)
    left_heap = []
    right_heap = []
    left = 0
    right = n - 1
    total = 0

    # Initialize heaps
    for _ in range(candidates):
        if left <= right:
            heapq.heappush(left_heap, (costs[left], left))
            left += 1
    for _ in range(candidates):
        if left <= right:
            heapq.heappush(right_heap, (costs[right], right))
            right -= 1

    for _ in range(k):
        if not right_heap or (left_heap and left_heap[0] <= right_heap[0]):
            cost, _ = heapq.heappop(left_heap)
            total += cost
            if left <= right:
                heapq.heappush(left_heap, (costs[left], left))
                left += 1
        else:
            cost, _ = heapq.heappop(right_heap)
            total += cost
            if left <= right:
                heapq.heappush(right_heap, (costs[right], right))
                right -= 1

    return total
```

### 2336. Smallest Number in Infinite Set (Medium)
[View Problem](https://leetcode.com/problems/smallest-number-in-infinite-set/)
```python
import heapq

class SmallestInfiniteSet:
    def __init__(self):
        self.min_heap = []
        self.added_back = set()
        self.current = 1

    def popSmallest(self) -> int:
        if self.min_heap:
            smallest = heapq.heappop(self.min_heap)
            self.added_back.remove(smallest)
            return smallest
        smallest = self.current
        self.current += 1
        return smallest

    def addBack(self, num: int) -> None:
        if num < self.current and num not in self.added_back:
            heapq.heappush(self.min_heap, num)
            self.added_back.add(num)
```

---

## Backtracking

### 257. Binary Tree Paths (Easy) - Listed above
### 401. Binary Watch (Easy)
[View Problem](https://leetcode.com/problems/binary-watch/)
```python
def readBinaryWatch(turnedOn: int) -> list[str]:
    # Bit counting - O(12 * 60) time, O(1) space
    result = []

    for h in range(12):
        for m in range(60):
            if bin(h).count('1') + bin(m).count('1') == turnedOn:
                result.append(f"{h}:{m:02d}")

    return result
```

### 257. Generate Combinations (Referenced above)
### 22. Generate Parentheses (Referenced above)
### 1286. Iterator for Combination (Medium)
[View Problem](https://leetcode.com/problems/iterator-for-combination/)
```python
class CombinationIterator:
    def __init__(self, characters: str, combinationLength: int):
        self.combinations = []
        self._generate(characters, combinationLength, 0, [])
        self.index = 0

    def _generate(self, chars, length, start, current):
        if len(current) == length:
            self.combinations.append(''.join(current))
            return
        for i in range(start, len(chars)):
            current.append(chars[i])
            self._generate(chars, length, i + 1, current)
            current.pop()

    def next(self) -> str:
        result = self.combinations[self.index]
        self.index += 1
        return result

    def hasNext(self) -> bool:
        return self.index < len(self.combinations)
```

### 1980. Find Unique Binary String (Medium)
[View Problem](https://leetcode.com/problems/find-unique-binary-string/)
```python
def findDifferentBinaryString(nums: list[str]) -> str:
    # Cantor's diagonal - O(n) time, O(n) space
    result = []
    for i, num in enumerate(nums):
        # Flip the i-th bit of the i-th number
        result.append('0' if num[i] == '1' else '1')
    return ''.join(result)
```

### 1415. The k-th Lexicographical String of All Happy Strings of Length n (Medium)
[View Problem](https://leetcode.com/problems/the-k-th-lexicographical-string-of-all-happy-strings-of-length-n/)
```python
def getHappyString(n: int, k: int) -> str:
    # Backtracking - O(3 * 2^(n-1)) time
    result = []

    def backtrack(current):
        if len(result) == k:
            return
        if len(current) == n:
            result.append(current)
            return
        for c in 'abc':
            if not current or current[-1] != c:
                backtrack(current + c)

    backtrack('')
    return result[k - 1] if len(result) >= k else ''
```

### 1922. Count Good Numbers (Medium)
[View Problem](https://leetcode.com/problems/count-good-numbers/)
```python
def countGoodNumbers(n: int) -> int:
    # Fast exponentiation - O(log n) time, O(1) space
    MOD = 10**9 + 7

    def power(base, exp):
        result = 1
        while exp > 0:
            if exp % 2 == 1:
                result = (result * base) % MOD
            base = (base * base) % MOD
            exp //= 2
        return result

    even_positions = (n + 1) // 2  # 0, 2, 4, ...
    odd_positions = n // 2  # 1, 3, 5, ...

    return (power(5, even_positions) * power(4, odd_positions)) % MOD
```

### 2044. Count Number of Maximum Bitwise-OR Subsets (Medium)
[View Problem](https://leetcode.com/problems/count-number-of-maximum-bitwise-or-subsets/)
```python
def countMaxOrSubsets(nums: list[int]) -> int:
    # Backtracking - O(2^n) time, O(n) space
    max_or = 0
    for num in nums:
        max_or |= num

    count = 0

    def backtrack(idx, current_or):
        nonlocal count
        if idx == len(nums):
            if current_or == max_or:
                count += 1
            return
        # Include nums[idx]
        backtrack(idx + 1, current_or | nums[idx])
        # Exclude nums[idx]
        backtrack(idx + 1, current_or)

    backtrack(0, 0)
    return count
```

---

## Graphs

### 463. Island Perimeter (Easy)
[View Problem](https://leetcode.com/problems/island-perimeter/)
```python
def islandPerimeter(grid: list[list[int]]) -> int:
    # Count edges - O(m*n) time, O(1) space
    rows, cols = len(grid), len(grid[0])
    perimeter = 0

    for r in range(rows):
        for c in range(cols):
            if grid[r][c] == 1:
                perimeter += 4
                if r > 0 and grid[r - 1][c] == 1:
                    perimeter -= 2
                if c > 0 and grid[r][c - 1] == 1:
                    perimeter -= 2

    return perimeter
```

### 733. Flood Fill (Easy)
[View Problem](https://leetcode.com/problems/flood-fill/)
```python
def floodFill(image: list[list[int]], sr: int, sc: int, color: int) -> list[list[int]]:
    # DFS - O(m*n) time, O(m*n) space
    if image[sr][sc] == color:
        return image

    original = image[sr][sc]
    rows, cols = len(image), len(image[0])

    def dfs(r, c):
        if r < 0 or r >= rows or c < 0 or c >= cols:
            return
        if image[r][c] != original:
            return
        image[r][c] = color
        dfs(r + 1, c)
        dfs(r - 1, c)
        dfs(r, c + 1)
        dfs(r, c - 1)

    dfs(sr, sc)
    return image
```

### 997. Find the Town Judge (Easy)
[View Problem](https://leetcode.com/problems/find-the-town-judge/)
```python
def findJudge(n: int, trust: list[list[int]]) -> int:
    # In-degree and out-degree - O(n + e) time, O(n) space
    if n == 1 and not trust:
        return 1

    trust_count = [0] * (n + 1)

    for a, b in trust:
        trust_count[a] -= 1  # a trusts someone
        trust_count[b] += 1  # b is trusted

    for i in range(1, n + 1):
        if trust_count[i] == n - 1:
            return i

    return -1
```

### 1091. Shortest Path in Binary Matrix (Medium)
[View Problem](https://leetcode.com/problems/shortest-path-in-binary-matrix/)
```python
def shortestPathBinaryMatrix(grid: list[list[int]]) -> int:
    # BFS - O(n^2) time, O(n^2) space
    from collections import deque

    n = len(grid)
    if grid[0][0] == 1 or grid[n - 1][n - 1] == 1:
        return -1

    directions = [(-1, -1), (-1, 0), (-1, 1), (0, -1),
                  (0, 1), (1, -1), (1, 0), (1, 1)]

    queue = deque([(0, 0, 1)])
    grid[0][0] = 1

    while queue:
        r, c, dist = queue.popleft()

        if r == n - 1 and c == n - 1:
            return dist

        for dr, dc in directions:
            nr, nc = r + dr, c + dc
            if 0 <= nr < n and 0 <= nc < n and grid[nr][nc] == 0:
                grid[nr][nc] = 1
                queue.append((nr, nc, dist + 1))

    return -1
```

### 1162. As Far from Land as Possible (Medium)
[View Problem](https://leetcode.com/problems/as-far-from-land-as-possible/)
```python
def maxDistance(grid: list[list[int]]) -> int:
    # Multi-source BFS - O(n^2) time, O(n^2) space
    from collections import deque

    n = len(grid)
    queue = deque()

    for r in range(n):
        for c in range(n):
            if grid[r][c] == 1:
                queue.append((r, c))

    if len(queue) == 0 or len(queue) == n * n:
        return -1

    directions = [(0, 1), (0, -1), (1, 0), (-1, 0)]
    distance = -1

    while queue:
        distance += 1
        for _ in range(len(queue)):
            r, c = queue.popleft()
            for dr, dc in directions:
                nr, nc = r + dr, c + dc
                if 0 <= nr < n and 0 <= nc < n and grid[nr][nc] == 0:
                    grid[nr][nc] = 1
                    queue.append((nr, nc))

    return distance
```

### 1971. Find if Path Exists in Graph (Easy)
[View Problem](https://leetcode.com/problems/find-if-path-exists-in-graph/)
```python
def validPath(n: int, edges: list[list[int]], source: int, destination: int) -> bool:
    # Union-Find - O(n + e * α(n)) time, O(n) space
    parent = list(range(n))

    def find(x):
        if parent[x] != x:
            parent[x] = find(parent[x])
        return parent[x]

    def union(x, y):
        px, py = find(x), find(y)
        if px != py:
            parent[px] = py

    for u, v in edges:
        union(u, v)

    return find(source) == find(destination)
```

### 2316. Count Unreachable Pairs of Nodes in an Undirected Graph (Medium)
[View Problem](https://leetcode.com/problems/count-unreachable-pairs-of-nodes-in-an-undirected-graph/)
```python
def countPairs(n: int, edges: list[list[int]]) -> int:
    # Union-Find with sizes - O(n + e * α(n)) time, O(n) space
    parent = list(range(n))
    size = [1] * n

    def find(x):
        if parent[x] != x:
            parent[x] = find(parent[x])
        return parent[x]

    def union(x, y):
        px, py = find(x), find(y)
        if px != py:
            parent[px] = py
            size[py] += size[px]

    for u, v in edges:
        union(u, v)

    # Count unreachable pairs
    components = []
    for i in range(n):
        if find(i) == i:
            components.append(size[i])

    total = 0
    running_sum = 0
    for s in components:
        total += running_sum * s
        running_sum += s

    return total
```

### 2101. Detonate the Maximum Bombs (Medium)
[View Problem](https://leetcode.com/problems/detonate-the-maximum-bombs/)
```python
def maximumDetonation(bombs: list[list[int]]) -> int:
    # Build graph + DFS - O(n^2) time, O(n^2) space
    from collections import defaultdict

    n = len(bombs)
    graph = defaultdict(list)

    for i in range(n):
        for j in range(n):
            if i != j:
                xi, yi, ri = bombs[i]
                xj, yj, _ = bombs[j]
                dist_sq = (xi - xj) ** 2 + (yi - yj) ** 2
                if dist_sq <= ri ** 2:
                    graph[i].append(j)

    def dfs(node, visited):
        visited.add(node)
        for neighbor in graph[node]:
            if neighbor not in visited:
                dfs(neighbor, visited)
        return len(visited)

    max_detonated = 0
    for i in range(n):
        max_detonated = max(max_detonated, dfs(i, set()))

    return max_detonated
```

---

## Dynamic Programming

### 746. Min Cost Climbing Stairs (Easy) - Referenced above
### 509. Fibonacci Number (Easy) - Referenced above
### 392. Is Subsequence (Easy) - Referenced above
### 1137. N-th Tribonacci Number (Easy) - Referenced above

### 303. Range Sum Query - Immutable (Easy)
[View Problem](https://leetcode.com/problems/range-sum-query-immutable/)
```python
class NumArray:
    def __init__(self, nums: list[int]):
        # Prefix sum - O(n) time, O(n) space
        self.prefix = [0]
        for num in nums:
            self.prefix.append(self.prefix[-1] + num)

    def sumRange(self, left: int, right: int) -> int:
        # O(1) time
        return self.prefix[right + 1] - self.prefix[left]
```

### 338. Counting Bits (Easy) - Referenced above
### 746. Min Cost Climbing Stairs (Easy) - Referenced above

### 1277. Count Square Submatrices with All Ones (Medium)
[View Problem](https://leetcode.com/problems/count-square-submatrices-with-all-ones/)
```python
def countSquares(matrix: list[list[int]]) -> int:
    # DP - O(m*n) time, O(1) space
    m, n = len(matrix), len(matrix[0])
    count = 0

    for i in range(m):
        for j in range(n):
            if matrix[i][j] == 1:
                if i > 0 and j > 0:
                    matrix[i][j] = min(matrix[i-1][j], matrix[i][j-1],
                                       matrix[i-1][j-1]) + 1
                count += matrix[i][j]

    return count
```

### 931. Minimum Falling Path Sum (Medium)
[View Problem](https://leetcode.com/problems/minimum-falling-path-sum/)
```python
def minFallingPathSum(matrix: list[list[int]]) -> int:
    # DP - O(n^2) time, O(1) space
    n = len(matrix)

    for i in range(1, n):
        for j in range(n):
            left = matrix[i-1][j-1] if j > 0 else float('inf')
            mid = matrix[i-1][j]
            right = matrix[i-1][j+1] if j < n - 1 else float('inf')
            matrix[i][j] += min(left, mid, right)

    return min(matrix[n-1])
```

### 983. Minimum Cost For Tickets (Medium)
[View Problem](https://leetcode.com/problems/minimum-cost-for-tickets/)
```python
def mincostTickets(days: list[int], costs: list[int]) -> int:
    # DP - O(n) time, O(n) space
    day_set = set(days)
    last_day = days[-1]
    dp = [0] * (last_day + 1)

    for i in range(1, last_day + 1):
        if i not in day_set:
            dp[i] = dp[i - 1]
        else:
            dp[i] = min(
                dp[i - 1] + costs[0],
                dp[max(0, i - 7)] + costs[1],
                dp[max(0, i - 30)] + costs[2]
            )

    return dp[last_day]
```

### 1014. Best Sightseeing Pair (Medium)
[View Problem](https://leetcode.com/problems/best-sightseeing-pair/)
```python
def maxScoreSightseeingPair(values: list[int]) -> int:
    # DP - O(n) time, O(1) space
    max_score = 0
    max_i = values[0]  # values[i] + i

    for j in range(1, len(values)):
        max_score = max(max_score, max_i + values[j] - j)
        max_i = max(max_i, values[j] + j)

    return max_score
```

### 1035. Uncrossed Lines (Medium)
[View Problem](https://leetcode.com/problems/uncrossed-lines/)
```python
def maxUncrossedLines(nums1: list[int], nums2: list[int]) -> int:
    # DP (LCS) - O(m*n) time, O(n) space
    m, n = len(nums1), len(nums2)
    dp = [0] * (n + 1)

    for i in range(1, m + 1):
        prev = 0
        for j in range(1, n + 1):
            temp = dp[j]
            if nums1[i-1] == nums2[j-1]:
                dp[j] = prev + 1
            else:
                dp[j] = max(dp[j], dp[j-1])
            prev = temp

    return dp[n]
```

### 1049. Last Stone Weight II (Medium)
[View Problem](https://leetcode.com/problems/last-stone-weight-ii/)
```python
def lastStoneWeightII(stones: list[int]) -> int:
    # DP (subset sum) - O(n * sum) time, O(sum) space
    total = sum(stones)
    target = total // 2
    dp = [False] * (target + 1)
    dp[0] = True

    for stone in stones:
        for j in range(target, stone - 1, -1):
            dp[j] = dp[j] or dp[j - stone]

    for j in range(target, -1, -1):
        if dp[j]:
            return total - 2 * j

    return total
```

### 2466. Count Ways To Build Good Strings (Medium)
[View Problem](https://leetcode.com/problems/count-ways-to-build-good-strings/)
```python
def countGoodStrings(low: int, high: int, zero: int, one: int) -> int:
    # DP - O(high) time, O(high) space
    MOD = 10**9 + 7
    dp = [0] * (high + 1)
    dp[0] = 1

    for i in range(1, high + 1):
        if i >= zero:
            dp[i] = (dp[i] + dp[i - zero]) % MOD
        if i >= one:
            dp[i] = (dp[i] + dp[i - one]) % MOD

    return sum(dp[low:high + 1]) % MOD
```

---

## Greedy

### 605. Can Place Flowers (Easy)
[View Problem](https://leetcode.com/problems/can-place-flowers/)
```python
def canPlaceFlowers(flowerbed: list[int], n: int) -> bool:
    # Greedy - O(m) time, O(1) space
    count = 0
    length = len(flowerbed)

    for i in range(length):
        if flowerbed[i] == 0:
            empty_left = (i == 0) or (flowerbed[i - 1] == 0)
            empty_right = (i == length - 1) or (flowerbed[i + 1] == 0)

            if empty_left and empty_right:
                flowerbed[i] = 1
                count += 1
                if count >= n:
                    return True

    return count >= n
```

### 942. DI String Match (Easy)
[View Problem](https://leetcode.com/problems/di-string-match/)
```python
def diStringMatch(s: str) -> list[int]:
    # Two pointers - O(n) time, O(n) space
    low, high = 0, len(s)
    result = []

    for char in s:
        if char == 'I':
            result.append(low)
            low += 1
        else:
            result.append(high)
            high -= 1

    result.append(low)
    return result
```

### 1217. Minimum Cost to Move Chips to The Same Position (Easy)
[View Problem](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position/)
```python
def minCostToMoveChips(position: list[int]) -> int:
    # Count odd and even - O(n) time, O(1) space
    odd = sum(1 for p in position if p % 2 == 1)
    even = len(position) - odd
    return min(odd, even)
```

### 1323. Maximum 69 Number (Easy)
[View Problem](https://leetcode.com/problems/maximum-69-number/)
```python
def maximum69Number(num: int) -> int:
    # Find first 6 and change - O(log n) time, O(log n) space
    s = list(str(num))
    for i in range(len(s)):
        if s[i] == '6':
            s[i] = '9'
            break
    return int(''.join(s))
```

### 1518. Water Bottles (Easy)
[View Problem](https://leetcode.com/problems/water-bottles/)
```python
def numWaterBottles(numBottles: int, numExchange: int) -> int:
    # Simulation - O(log n) time, O(1) space
    total = numBottles
    empty = numBottles

    while empty >= numExchange:
        new_bottles = empty // numExchange
        total += new_bottles
        empty = empty % numExchange + new_bottles

    return total
```

### 2144. Minimum Cost of Buying Candies With Discount (Easy)
[View Problem](https://leetcode.com/problems/minimum-cost-of-buying-candies-with-discount/)
```python
def minimumCost(cost: list[int]) -> int:
    # Sort descending, skip every 3rd - O(n log n) time
    cost.sort(reverse=True)
    total = 0

    for i, c in enumerate(cost):
        if (i + 1) % 3 != 0:
            total += c

    return total
```

---

## Math & Geometry

### 168. Excel Sheet Column Title (Easy)
[View Problem](https://leetcode.com/problems/excel-sheet-column-title/)
```python
def convertToTitle(columnNumber: int) -> str:
    # Base 26 conversion - O(log n) time, O(log n) space
    result = []
    while columnNumber > 0:
        columnNumber -= 1
        result.append(chr(columnNumber % 26 + ord('A')))
        columnNumber //= 26
    return ''.join(reversed(result))
```

### 171. Excel Sheet Column Number (Easy)
[View Problem](https://leetcode.com/problems/excel-sheet-column-number/)
```python
def titleToNumber(columnTitle: str) -> int:
    # Base 26 conversion - O(n) time, O(1) space
    result = 0
    for char in columnTitle:
        result = result * 26 + (ord(char) - ord('A') + 1)
    return result
```

### 172. Factorial Trailing Zeroes (Medium)
[View Problem](https://leetcode.com/problems/factorial-trailing-zeroes/)
```python
def trailingZeroes(n: int) -> int:
    # Count factors of 5 - O(log n) time, O(1) space
    count = 0
    while n >= 5:
        n //= 5
        count += n
    return count
```

### 204. Count Primes (Medium)
[View Problem](https://leetcode.com/problems/count-primes/)
```python
def countPrimes(n: int) -> int:
    # Sieve of Eratosthenes - O(n log log n) time, O(n) space
    if n < 2:
        return 0

    is_prime = [True] * n
    is_prime[0] = is_prime[1] = False

    for i in range(2, int(n ** 0.5) + 1):
        if is_prime[i]:
            for j in range(i * i, n, i):
                is_prime[j] = False

    return sum(is_prime)
```

### 263. Ugly Number (Easy)
[View Problem](https://leetcode.com/problems/ugly-number/)
```python
def isUgly(n: int) -> bool:
    # Factor out 2, 3, 5 - O(log n) time, O(1) space
    if n <= 0:
        return False

    for factor in [2, 3, 5]:
        while n % factor == 0:
            n //= factor

    return n == 1
```

### 326. Power of Three (Easy)
[View Problem](https://leetcode.com/problems/power-of-three/)
```python
def isPowerOfThree(n: int) -> bool:
    # Math approach - O(1) time, O(1) space
    # 3^19 = 1162261467 is largest power of 3 in 32-bit int
    return n > 0 and 1162261467 % n == 0
```

### 412. Fizz Buzz (Easy)
[View Problem](https://leetcode.com/problems/fizz-buzz/)
```python
def fizzBuzz(n: int) -> list[str]:
    # Simple iteration - O(n) time, O(n) space
    result = []
    for i in range(1, n + 1):
        if i % 15 == 0:
            result.append("FizzBuzz")
        elif i % 3 == 0:
            result.append("Fizz")
        elif i % 5 == 0:
            result.append("Buzz")
        else:
            result.append(str(i))
    return result
```

---

## Bit Manipulation

### 190. Reverse Bits (Easy) - Referenced above
### 191. Number of 1 Bits (Easy) - Referenced above
### 268. Missing Number (Easy) - Referenced above

### 693. Binary Number with Alternating Bits (Easy)
[View Problem](https://leetcode.com/problems/binary-number-with-alternating-bits/)
```python
def hasAlternatingBits(n: int) -> bool:
    # XOR with shifted - O(1) time, O(1) space
    xor = n ^ (n >> 1)
    return (xor & (xor + 1)) == 0
```

### 762. Prime Number of Set Bits in Binary Representation (Easy)
[View Problem](https://leetcode.com/problems/prime-number-of-set-bits-in-binary-representation/)
```python
def countPrimeSetBits(left: int, right: int) -> int:
    # Count set bits - O(n) time, O(1) space
    primes = {2, 3, 5, 7, 11, 13, 17, 19}
    count = 0

    for num in range(left, right + 1):
        if bin(num).count('1') in primes:
            count += 1

    return count
```

### 1009. Complement of Base 10 Integer (Easy)
[View Problem](https://leetcode.com/problems/complement-of-base-10-integer/)
```python
def bitwiseComplement(n: int) -> int:
    # XOR with all 1s mask - O(log n) time, O(1) space
    if n == 0:
        return 1

    mask = 1
    while mask < n:
        mask = (mask << 1) | 1

    return n ^ mask
```

### 1486. XOR Operation in an Array (Easy)
[View Problem](https://leetcode.com/problems/xor-operation-in-an-array/)
```python
def xorOperation(n: int, start: int) -> int:
    # Simple XOR - O(n) time, O(1) space
    result = 0
    for i in range(n):
        result ^= start + 2 * i
    return result
```

### 1720. Decode XORed Array (Easy)
[View Problem](https://leetcode.com/problems/decode-xored-array/)
```python
def decode(encoded: list[int], first: int) -> list[int]:
    # XOR decoding - O(n) time, O(n) space
    result = [first]
    for num in encoded:
        result.append(result[-1] ^ num)
    return result
```

### 2433. Find The Original Array of Prefix Xor (Medium)
[View Problem](https://leetcode.com/problems/find-the-original-array-of-prefix-xor/)
```python
def findArray(pref: list[int]) -> list[int]:
    # XOR consecutive elements - O(n) time, O(n) space
    result = [pref[0]]
    for i in range(1, len(pref)):
        result.append(pref[i] ^ pref[i - 1])
    return result
```

---

## Summary

| Difficulty | Count |
|------------|-------|
| Easy | 55 |
| Medium | 42 |
| Hard | 3 |
| **Total** | **100** |

---

*Good luck with your interview preparation!*
