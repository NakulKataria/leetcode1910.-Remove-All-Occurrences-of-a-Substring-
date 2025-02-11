# leetcode1910.-Remove-All-Occurrences-of-a-Substring-
<pre>
question-Given two strings s and part, perform the following operation on s until all occurrences of the substring part are removed:
Find the leftmost occurrence of the substring part and remove it from s.
Return s after removing all occurrences of part.
A substring is a contiguous sequence of characters in a string.

solution- Check if part exists in s: Using .includes(part).
-Remove the first occurrence: .replace(part, "") removes only the first occurrence.
-Repeat until no occurrences remain: The while loop continues until part is completely removed from s.
</pre>