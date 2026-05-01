# Two Pointers

## Problem sheet
https://docs.google.com/spreadsheets/d/1T5-nGsJ9WNwna44e9WWRD0jlZIT5KxVOGvylcvvVrY8/edit?gid=0#gid=0

## Applicability conditions
- Array / Linked list question
- Either given data is sorted or sorting would help
- Merge / Remove duplicates / Rearrange
- Detect cycle / Cycle detection would help
- Pair / Triplet / Quadruplet / etc
- Do not use extra space


## Concepts
- At least one pointer should move after every iteration
- Main logic is about understanding how the pointers move
- When to stop?


## Two Sum 2, give numbers, not index
- Return a and b such that a+b = target
- Array question
- Sorting will help
- Asking for pair
- Sort
- First pointer: begin
- Second pointer: end
- Indices change after sorting, so if index is asked, and array is unsorted, can't sort and can't use two pointer
- If index is asked, and array is sorted, two pointers will work
- How pointers should move for each condition: sum < target, sum == target, sum > target
- When to stop?
