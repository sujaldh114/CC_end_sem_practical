# CC_end_sem_practical

class Solution(object):
    def climbStairs(self, n):
        if n <= 2:
            return n
        first = 1
        second =2
        for i in range (3, n +1):
            third = first + second
            first = second
            second = third
        return second

# Screen Shot

        <img width="1905" height="917" alt="image" src="https://github.com/user-attachments/assets/c6196edd-a534-4ec1-8a70-b0d1d58bad1c" />
