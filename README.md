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

I would first make sure that the algorithm is sorting the arrays properyly by giving randomly generated arrays and compairing what it returns
to what a sorting algorithm returns to ensure that the array is being sorted properly.
I would test the sorting algorthm by starting with small input sizes and increasing the size measuring the time that it takes to complete each array.
If the algorithm runs at O(n) time then the time should scale linearly with the size of the array.
Finally I would test the algorithm with arrays approaching worst case to see if the time scaling remains linear to the input size.

If you look at the complexity from a theoretical view point then it is increadibly unlikely as the best case for most sorting alorithms is O(nlogn).

the TA helped me by telling me to rephase it better but I wrote it myself.
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

Add your answers to this markdown file.
