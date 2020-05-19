# Sliding Window

Most of the substring search problem could be solved by sliding window. As a result, I place this method into basic algorithm chapter.

To sum up, sliding window solve the problems by sliding into linear time with two pointer and one loop.



*a window is formed over some part of data, and this window can slide over the data to capture different portions of it. --by Jordan Moore.*



Take an array, ``[1,2,3,4,5,6]``, as an example, if we want to check which two contiguous number is equal to 9, we could use sliding window to solve the problem.

In this question, the window's size should be 2, and we can place the window at the beginning of the array, which means ``[1,2]``.

Next, we examine the sum of 1 and 2, finding 3. Unfourtunately, this is not the number we want, so we move to next two numbers.

We add 3 and remove 1 to move the window forward. Next, we repeat this step until we find the correct answer.

This is basic concept of sliding window.



__Question Types:__

   **Maximum or Minimum Value**

   **Longest or Shortest Value**

   **K-sized Value**

__Clue to use Sliding Window:__

**Contiguous Permutation Anagrams**

__Example__

[https://leetcode.com/problems/minimum-window-substring/](https://leetcode.com/problems/minimum-window-substring/)    
[https://leetcode.com/problems/longest-substring-without-repeating-characters/](https://leetcode.com/problems/longest-substring-without-repeating-characters/)    
[https://leetcode.com/problems/substring-with-concatenation-of-all-words/](https://leetcode.com/problems/substring-with-concatenation-of-all-words/)   
[https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/)   
[https://leetcode.com/problems/find-all-anagrams-in-a-string/](https://leetcode.com/problems/find-all-anagrams-in-a-string/)   

