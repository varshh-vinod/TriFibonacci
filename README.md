# TriFibonacci
Problem Statement
A TriFibonacci sequence begins by defining the first three elements A[0], A[1] and A[2]. The remaining elements are calculated using the following recurrence:
	A[i] = A[i-1] + A[i-2] + A[i-3]
You are given a int[] A which contains exactly one element that is equal to -1, you must replace this element with a positive number in a way that the sequence becomes a TriFibonacci sequence. Return this number. If no such positive number exists, return -1.

Definition    	
Method signature:	int complete(int[] A)

Notes
-	The constraints for the elements of the input int[] A do not necessarily apply for the replacement to the missing element.
 
Constraints
-	A will contain between 4 and 20 elements, inclusive.
-	Each element of A will be -1 or between 1 and 1000000, inclusive.
-	Exactly one element of A will be -1.
 
Examples

 0)    	
 {1,2,3,-1}
Returns: 6

1)
 {10, 20, 30, 60, -1 , 200}
Returns: 110

2)    	
{1, 2, 3, 5, -1}
Returns: -1
No replacement can make this sequence TriFibonacci as 5 is not equal to 1+2+3.

3)    	
{1, 1, -1, 2, 3}
Returns: -1
The missing element must be 0 for this sequence to be TriFibonacci. Since this is not a positive integer, return -1.

4)    	
{-1, 7, 8, 1000000}
Returns: 999985
