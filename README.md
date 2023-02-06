# twoArraysThere are two -element arrays of integers,  and . Permute them into some  and  such that the relation  holds for all  where .

There will be  queries consisting of , , and . For each query, return YES if some permutation ,  satisfying the relation exists. Otherwise, return NO.

Example



A valid  is  and :  and . Return YES.

Function Description

Complete the twoArrays function in the editor below. It should return a string, either YES or NO.

twoArrays has the following parameter(s):

int k: an integer
int A[n]: an array of integers
int B[n]: an array of integers
Returns
- string: either YES or NO

Input Format

The first line contains an integer , the number of queries.

The next  sets of  lines are as follows:

The first line contains two space-separated integers  and , the size of both arrays  and , and the relation variable.
The second line contains  space-separated integers .
The third line contains  space-separated integers .
Constraints

Sample Input

STDIN       Function
-----       --------
2           q = 2
3 10        A[] and B[] size n = 3, k = 10
2 1 3       A = [2, 1, 3]
7 8 9       B = [7, 8, 9]
4 5         A[] and B[] size n = 4, k = 5
1 2 2 1     A = [1, 2, 2, 1]
3 3 3 4     B = [3, 3, 3, 4]
Sample Output

YES
NO
Explanation

There are two queries:

Permute these into  and  so that the following statements are true:

, , and . To permute  and  into a valid  and , there must be at least three numbers in  that are greater than .

![image](https://user-images.githubusercontent.com/43896389/216862650-0999bcea-c159-4542-bb92-ecb0c84da1fd.png)

![image](https://user-images.githubusercontent.com/43896389/216862697-7fa65c72-317c-4d2e-8e8b-69fb46ee6fbd.png)

