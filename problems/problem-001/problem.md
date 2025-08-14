# In a university exam, each student must submit their answers only once,
# identified by a unique positive integer student ID.
# You are given an array of submission IDs.
# Return True if any student ID appears more than once, otherwise return False.
#
# Input:
# int[] submissions
#
# Output:
# boolean — whether there is any duplicate student ID.
#
# Examples:
# Input: [1021, 45, 1021, 9] → Output: True
# Input: [7, 11, 19] → Output: False
#
# Notes (possible approaches):
# - Brute force: Compare every pair of IDs (O(n^2))
# - Better: Sort the array and check neighboring elements (O(n log n))
# - Best (average): Use a hash set to track seen IDs (O(n) average)
#
# Additional validation rules implemented in this solution:
# - IDs must be positive
# - IDs must be exactly 4 digits long
# - IDs cannot start with 0
# - No duplicate IDs allowed in the same input
