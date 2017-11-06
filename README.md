# SwiftReverseAnInteger
Reverse a signed 32 bit integer

This is a Swift solution for the Reverse Integer LeetCode problem.

It can be found at this URL: https://leetcode.com/problems/reverse-integer/description/

In the question it mentions handling situations where the number overflows as a result of reversal. My previous method of handling this was to check for the zeroing of a number durring the process and to respond to this by returning the desired outcome of a 0.

This however did not pass their tests, as the number did not actually overflow. Now my solution uses a hardcoded check against the max and min values of the integer. This would not work to catch over/underflow. 
