# Summary of Key Lessons

## 0. Algorithms and Data Structures (ADS)
Continued to [Part 2 of ADS lectures by MIT [24:00]](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/lecture-videos/lecture-11-understanding-program-efficiency-part-2/). Irrelevant to ADS, [problem sets 4 and 5](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/assignments/) may be good practice if there is time.

## 1. Brute Force Works, Just Not As Well On Big Problems.
Brute force methods are usually the easiest, first thing to think of. For an example, see two-sum.py. Beyond the initial solution, one should think of answers that help reduce computational time and/or space. This is related to the idea of **space and time complexity.** In the example of two-sum.py, we see that sacrificing some space by saving values into a **dictionary lookup** instead of double for-loops help reduce time complexity from O(n^2) to O(n), 4000ms to 40ms!

## 2. Binary Search Algorithm
By implementing the low = 0, high = len(array), n = (high - low)//2 and iterating over that, the search space effectively can be halved. This greatly reduces computational time.

## 3. Creativity
Check out the creative solutions on LeetCode discussion pages!
