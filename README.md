# Sum-of-Squares-of-Special-Elements
class Solution:
    def sumOfSquares(self, nums: List[int]) -> int:
        r=[]
        n=len(nums)
        for i in range(n):
            if n%(i+1)==0:
                r.append(nums[i])
        r1=0
        for i in r:
            r1+=i*i
        return r1
