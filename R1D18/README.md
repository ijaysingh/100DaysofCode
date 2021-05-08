**FIRST QUESTION:**

Find number of elements to be removed to make an array of all distinct elements.

Example:
Ar = {2,1,4,2,1} 

output = 2 (remove 2 and 1).
Input format :
Line 1 : Integer N 
Line 2 : N integers separated be a single space
Output Format :
 Integer

Constraints :
 0 <= N <= 10^4

Sample Input :
5
2 1 4 2 1
Sample Output :
2

**SECOND QUESTION:**

In a given string, find the first non-repeating character .You are given a string, that can contain repeating characters. 
Your task is to return the first character in this string that does not repeat. i.e., occurs exactly once. 
The string will contain characters only from English alphabet set, i.e., ('A' - 'Z') and ('a' - 'z'). 
If there is no non-repeating character print the first character of string.

Input Format :
Line 1 : A String , as mentioned above.
Output Format :
First non-repeating character

Sample Input 1 :
aDcadhc
Sample Output 1:
D

Sample Input 2 :
gdhIgHada
Sample Output 2 :
h

**THIRD QUESTION:**

You are provided with an integer array where each number is present either odd number of times or even number of times. 
You have to find and return the number which is present even number of times.
If multiple numbers are present even number of times, then return that number which occurs first among these numbers in the given array. 
If no such number exists, then return -1.

Note : You may take extra space but solve this problem in O(n) time.

Input Format:
Line 1 : An Integer N i.e. size of array 
Line 2 : N integers which are elements of the array, separated by spaces
Output Format:
Array element occurring even no. of times

Constraints :
1 <= N <= 10^5

Sample Input:
6
2 5 3 5 3 4 
Sample Output:
5

**FOURTH QUESTION**

In Little Flowers Public School, there are many students with same first names. 
You are given a task to find the students with same names.
You will be given a string comprising of all the names of students and you have to tell the name and count of those students having same. 
If all the names are unique, print -1 instead.

Note: We don't have to mention names whose frequency is 1.

Input Format:
The only line of input will have a string ‘str’ with space separated first names of students.
Output Format:
Print the names of students along with their count if they are repeating. If no name is repeating, print -1

Constraints:
1 <= |str| <= 10^5
Time Limit: 1 second

Sample Input 1:
Abhishek harshit Ayush harshit Ayush Iti Deepak Ayush Iti
Sample Output 1:
harshit 2
Ayush 3
Iti 2

Sample Input 2:
Abhishek Harshit Ayush Iti
Sample Output:
-1
