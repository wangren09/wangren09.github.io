## 1. Two Sum
<pre>
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        if len(nums) <= 1:
            return False
        dict = {}
        for i in range(len(nums)):
            if nums[i] in dict:
                return [dict[nums[i]],i]
            else:
                dict[target-nums[i]] = i
</pre>
Python dictionary is HashTable such that looking up a key is O(1). The overall complexity is O(n).

## 7. Reverse Integer
<pre>
class Solution(object):
    def reverse(self, x):
        """
        :type x: int
        :rtype: int
        """
        if x >= 0:
            x = str(x)
            x = x[::-1]
        else:
            x = str(-x)
            x = x[::-1]
            x = '-'+x
        x = int(x)
        if -2**31 <= x <= 2**31-1:
            return x
        else:
            return 0
</pre>
In an signed 32-bit integer you can store values with range from -2147483648 -2**31 to 2**31-1.
