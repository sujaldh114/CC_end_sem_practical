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

<img width="1905" height="917" alt="image" src="https://github.com/user-attachments/assets/8afa6a5b-5da2-487b-9f27-478865e0ba35" />
