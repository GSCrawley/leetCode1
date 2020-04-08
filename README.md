# leetCode1

# problem #1 : TwoSum Solution
"Given an array of integers, return indices of the two numbers such that they add up to a specific target.
You may assume that each input would have exactly one solution, and you may not use the same element twice."

Example:

Given nums = [2, 7, 11, 15], target = 9,

Because nums[0] + nums[1] = 2 + 7 = 9,
return [0, 1].

# problem #9 : Palindrome Number
"Determine whether an integer is a palindrome. An integer is a palindrome when it reads the same backward as forward."

Communication steps:

# #1: TwoSum Solution

"So, just to clarify, we want to find the indices of two numbers in an array of integers that add up to a certain target number, correct?"

"I'm assuming that there's only one solution for each input, and each element can only be used once."

First we define the class, let's call it Solution, and give it one argument, which we'll call object. 
Then we loop through each element x and find if there is another value that equals to target - x.
For each element, we try to find its complement by looping through the rest of array.

This is probably not the fastest way to do it, but it works.

  
