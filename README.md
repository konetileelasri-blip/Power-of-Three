Power of Three

📌 Problem

Given an integer "n", return "true" if "n" is a power of three. Otherwise, return "false".

A number is a power of three if it can be written as:

"3^x"

where "x" is a non-negative integer.

💡 Example

Input: n = 27
Output: true

Because:

"27 = 3 × 3 × 3"

Another example:

Input: n = 10
Output: false

💻 Language

Java

📂 File

"PowerOfThree.java"

🧠 Approach

1. Check whether "n" is positive.
2. Repeatedly divide "n" by "3" while it is divisible by "3".
3. After the divisions, check whether the result is "1".
4. If it is "1", the original number is a power of three.

⏱️ Complexity

- Time Complexity: O(log n)
- Space Complexity: O(1)

🎯 Goal

To practice loops, conditions, division, and mathematical problem-solving in Java.

👨‍💻 Author

K.LeelaSri# Power-of-Three