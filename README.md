
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/b93e02e6-6468-4a00-9a9e-a00bc0e4cb0f" />



# level-2-code-karaoke
Level 2 questions for code karaoke event, there are 2 questions write the program and test it with examples in those questions and upload in fork 
# Question 1:
1.Tow Sum:
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the same element twice.
You can return the answer in any order.
 
# Example 1:
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

# Example 2:
Input: nums = [3,2,4], target = 6
Output: [1,2]

# Example 3:
Input: nums = [3,3], target = 6
Output: [0,1]

# CODE:
```
def sum():
  nums=[2,7,11,15]
  target=9
  for i in range(len(nums):
      for j in range(i+1,len(nums)):
          if nums[i] + nums[j] == target
                 return[i,j]
print(sum())
```

# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-11-08 103853" src="https://github.com/user-attachments/assets/afa0ca32-4b59-43c8-8f06-9d9ad215fa77" />


# Question 2:
1. Palindrome Number:

Given an integer x, return true if x is a palindrome, and false otherwise.
 
# Example 1:
Input: x = 121
Output: true
Explanation: 121 reads as 121 from left to right and from right to left.
# Example 2:
Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.
# Example 3:
Input: x = 10
Output: false
Explanation: Reads 01 from right to left. Therefore it is not a palindrome.


# CODE:


<img width="1546" height="845" alt="Screenshot 2025-11-08 105306" src="https://github.com/user-attachments/assets/63f23bad-1f64-4be9-880c-db7de35e868f" />


# OUTPUT:
<img width="1546" height="845" alt="Screenshot 2025-11-08 105306" src="https://github.com/user-attachments/assets/6fc45a09-5bef-4a87-a447-ee7d2af2cf65" />

