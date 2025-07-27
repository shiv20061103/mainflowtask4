✅ 1. Find Missing Number

● Objective: Find the missing number from an array containing numbers from 1 to n+1 with one missing.
● Approach: Use the formula Sum = (n+1)*(n+2)//2 Subtract the sum of input list to find the missing number.
● Key Challenges: Handling input size dynamically. Avoiding off-by-one errors in sum formula.
● Solution: Used the mathematical formula and list sum for efficiency.

✅ 2. Check Balanced Parentheses

● Objective: Check if a string containing brackets (), {}, [] is balanced.
● Approach: Use a stack to push opening brackets. On encountering a closing bracket, match it with the top of the stack.
● Key Challenges: Handling mismatched or unpaired brackets. Edge cases like empty strings.
● Solution: Used a dictionary with matching pairs and a stack to check balance.

✅ 3. Longest Word in a Sentence

● Objective: Find the longest word from a given sentence.
● Approach: Use split() to divide the sentence into words. Use max() with key=len.
● Key Challenges: Handling punctuation or empty input.
● Solution: Simple length comparison logic using built-in functions.

✅ 4. Count Words in a Sentence

● Objective: Count the total number of words in a sentence.
● Approach: Use split() which automatically splits at spaces. Count the resulting words.
● Key Challenges: Multiple spaces or empty input.
● Solution: Robust split logic handles multiple spaces correctly.

✅ 5. Check Pythagorean Triplet

● Objective: Check if three integers form a Pythagorean triplet (a² + b² = c²).
● Approach: Sort the numbers to ensure c is the largest. Use the triplet condition.
● Key Challenges: Ensuring correct identification of the hypotenuse.
● Solution: Used sorted() and compared squares.

✅ 6. Bubble Sort

● Objective: Sort a list of integers using Bubble Sort.
● Approach: Repeatedly swap adjacent elements if they are out of order.
● Key Challenges: Reducing unnecessary iterations.
● Solution: Used nested loops to perform swapping and sort the array.

✅ 7. Binary Search

● Objective: Search for a target number in a sorted list using Binary Search.
● Approach: Apply divide-and-conquer to narrow down search range.
● Key Challenges: Correctly updating low and high pointers.
● Solution: Used a while loop with middle index check for efficiency.

✅ 8. Subarray with Given Sum

● Objective: Find a contiguous subarray that sums up to a given value.
● Approach: Used sliding window technique for positive numbers.
● Key Challenges: Handling varying subarray sizes and shifting the window correctly.
● Solution: Maintained a moving window to adjust sum dynamically.

✅ 9. Log Analysis System

● Objective: Analyze a log file and display: Most frequent IPs Most accessed URLs Count of response codes
● Approach: Read log file line-by-line. Parse IP, URL, and code from each line. Use Counter from collections for efficient counting. Restrict file size to 100 MB using os.path.getsize().
● Key Challenges: Problem Solution File too large Added size check (max 100 MB) Malformed log lines Used try-except for safe parsing Efficient counting & performance Used collections.Counter
