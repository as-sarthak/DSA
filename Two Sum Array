from typing import List
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        res = {}
        for i,v in enumerate(nums):
            needed = target - v
            if needed in res:
                return (res[needed], i)
            res[v] = i
        return []
        
