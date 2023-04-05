# Python-Competitive-Programming-Questions
"""
Question 1:
 Consider today is sunday,In a restaurant,too much crowd in the cash counter the cashier need some help to calculate the bills.
that restaurant has different recipes they are,
menu:-
oniondosa-90 rs
plaindosa-40 rs
ravadosa-75 rs
idli-10 rs
vada-5 rs
poori-30 rs
chapathi -30 rs
pongal-35 rs
tea-25 rs
coffee-35 rs
meals-75 rs
Note: Price details discripted above is without GST.You need add 5 precent of GST for the total amount of a bill.
Input Discription:
Single line consists of recipes with count as shown below.
Output Discription:
Print output as "Total Price(GST inclusive):Rs xx.x"
Testcases:
Input:
tea 2
output:
Total Price(GST inclusive):Rs  52.5
Input:
vada 2 coffee 1
output:
Total Price(GST inclusive):Rs  47.25
Input:
meals 2 ravadosa 5 vada 4 poori 7 oniondosa 4 chapathi 2
output:
Total Price(GST inclusive):Rs  1233.75
Input:
masaladosa 1
Output:
Sorry,Only recipes in the menu !
Question:2
Given a string S converts each of the characters into numbers(ASCII) and print the sum of the numbers.
Input:
abc
output:
294
Question:3
An interview is scheduled for a list of students in GUVI Office, and
the candidate list has been shared to the interview panel
But in the last minute HR came to know the last n students in the
candidate list need to be given priority, since they need to catch a
flight
For Example, with n=7 candidates and k=3 need to catch their flight
So the order need to be changed as
(12.3.4.5.6.7}to{5,6,7,1,2,3,4)
If k <=0.no shuffling is needed
Write a program to help the HR to shuffle the candidate list so that
last n will come in the first
Input:
n-No. of candidates
K-No. of candidates in the end of the list who need
to be given priority
al-Candidates list
Expected Output
Output
Candidates list in shufled order.
Input:
7
3
1 2 3 4 5 6 7
Output:
5 6 7 1 2 3 4
Question:4
Given a number N print all prime numbers less than N.
Input:
10
Output:
2 3 5 7
Question:5
In a magical world,student and teacher are chosen by some rule.You are given the name of the student and name of the teacher,you have to tell whether they are chosen or not.
The process is as follows:the name of the student and teacher are first converted to numbers by the process described below.If the students number mod 47 and teachers number mod 47 is same then they would be chosen otherwise not.The number corresponding to a name is deduced by multiplying individual numbers assigned to its letters.Letter 'A' is assigned 1,'B' is assigned 2...so...till..'Z'is 26.
For instance,"ANKUR" would be 1*14*11*21*18=58212.
Print"CHOSEN" if the above condition satisfied otherwise print "NOT CHOSEN".
INPUT:
Line 1:An Uppercase character string representing the name of the student(S).
Line 2:An Uppercase character string representing the name of the teacher(T).
OUTPUT:
A single line containing either the word "CHOSEN" or the word "NOT CHOSEN".
Constraints:
1<=Length of both strings<=100
Input:
A
Z
Output:
NOT CHOSEN
Input:
COMETQ
HVNGAT
Output:
CHOSEN
Question:6
Karthick is a mathematical genius. He wants to solve the followong problem: given array of N integers A and a number K. During a turn the maximal value over all A[i] is chosen, let's call it MAX. Then A[i]= MAX - A[i] is done for every 1 <=i<= N. Help Karthick to find out how will the array look like after K turns.
Input:
The numbers N and K are given in the first line of an input. Then N integers
are given in the second line which denote the array A.
Output:
Output N numbers on a single line. It should be the array A after K turns.
Example:
Input:
4 1
5 -1 7 0
Output:
2 8 0 7


