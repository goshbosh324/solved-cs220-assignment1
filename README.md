Download Link: https://assignmentchef.com/product/solved-cs220-assignment1
<br>
In this your first project you write a function

int common(int A[], int B[], int m, int n)

that takes two arrays A[] and B[] of integers, of length m and n, and reports the number of common elements, not counting multiplicities. So [1,3,1,4,6] and [4,4,2,5,1,5,1,1] have just two common elements.

There are many ways to do this, for this homework you are asked to use this algorithm: you sort the two arrays separately, with mergesort, for which you obtain an auxiliary array with malloc. Then you proceed through both arrays, as in merging, identify common elements. Once you found a common element, you skip in both arrays all repetitions of this element.