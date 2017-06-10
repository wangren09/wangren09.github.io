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
Python dictionary is Hash Table such that looking up a key is O(1). The overall complexity is O(n).

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
In an signed 32-bit integer you can store values with range from -2^31 to 2^31-1.

## 13. Roman to Integer
<pre>
class Solution(object):
    def romanToInt(self, s):
        """
        :type s: str
        :rtype: int
        """
        dict_double = {'IV':4, 'IX':9, 'XL':40, 'XC':90, 'CD':400, 'CM':900}
        dict_single = {'I':1, 'V':5, 'X':10, 'L':50, 'C':100, 'D':500, 'M':1000}
        s_num = []
        roman_int = 0
        i = 0
        while i < len(s):
            if i+1 < len(s) and s[i]+s[i+1] in dict_double:
                roman_int = roman_int + dict_double[s[i]+s[i+1]]
                i = i+2
            else:
                roman_int = roman_int + dict_single[s[i]]
                i = i+1
        
        return roman_int
</pre>

## 14. Longest Common Prefix
<pre>
class Solution(object):
    def longestCommonPrefix(self, strs):
        """
        :type strs: List[str]
        :rtype: str
        """
        pre = ''
        if len(strs) < 1:
            return pre
        for i in range(len(strs[0])):
            for j in range(1,len(strs)):
                if i >= len(strs[j]) or strs[0][i] != strs[j][i]:
                    return pre
            pre = pre + strs[0][i]
        return pre
</pre>
The complexity is O(NL), where N is the number of string, and L is the length of the longest common prefix.
