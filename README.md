Single Number
Example 1:

Input: nums = [2,2,1]
Output: 1

leetcode - easy - time complexity:n


class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        res=0
        for i in nums:
            res=i^res
        return res
