# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

I would test the sorting by giving it small array sizes to start with like 1,2,3 to get a base case for time since it claims to work linearly. 
Next I would test it with larger array sizes of 10^n and check if the sorting is still running at O(n). Finally I would check worst cases like
having the array backwords. If the array time isn't the same reguardless of best case and the worst case then the run time complexity must not be O(n).

If you look at the complexity from a theoretical view point then it is increadibly unlikely as the best case for most sorting alorithms is O(nlogn).
So the claim is saying that it is better than the best case for even the quickest sorting algorithm as the claim is saying that worst case it runs at O(n).

Add your answers to this markdown file.
