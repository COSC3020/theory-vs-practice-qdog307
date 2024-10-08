# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.
  1. Asymptotic analysis is focusing on the growth rate of an algorithm as the input grows, this analysis ignores constant factors and lower order terms. When this is used in practical scenarios these factors can impact performance.
  2. It does not consider the hardware that is being used which can have a big impact on the actual use of it.
  3. It ignores the impact of memory hierarchy and cache, both of these things greatly impact the runtime. 

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.
  1. I beleive it would around 7 seconds. I used the equation O(logn), logbase2(10,000). This equaled 13.3 which I timed by 5 and divided by 10.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.
  1. The tree might be inbalanced or not the perefct scenario which would change the time.
  2. The use of memory might be changed, this would depend on the hardware used.
  3. With java there is garbage collections which with a larger data structure would mean a longer collection cycle. 

Add your answers to this markdown file.
 I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

 Sources used- Google search, https://www.geeksforgeeks.org/asymptotic-notation-and-analysis-based-on-input-size-of-algorithms/.
