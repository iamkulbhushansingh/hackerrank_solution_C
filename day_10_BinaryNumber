Objective
Today, we're working with binary numbers. Check out the Tutorial tab for learning materials and an instructional video!

Task
Given a base -10 integer, n, convert it to binary (base-2). Then find and print the base -10 integer denoting the maximum number of consecutive 1's in n's binary representation.

Input Format
A single integer, n.

Constraints
1<=n<=10**6

Output Format
Print a single base -10 integer denoting the maximum number of consecutive 1's in the binary representation of n.

Sample Input 1
5

Sample Output 1
1

Sample Input 2
13

Sample Output 2
2

Explanation
Sample Case 1:
The binary representation of 5 is 101, so the maximum number of consecutive 1's is 1.
Sample Case 2:
The binary representation of 13 is 1101, so the maximum number of consecutive 1's is 2.

Solution in Python3 with explaination:
a=int(input())                           #taking numbers as integer
b=bin(a)                                 #converting the number into binary format
b=list(b)                                #making a list will be easier to fetch element from index
l=len(b)                                 #returning length of string for loop purpose
for i in range(l):
     if b=='1':                          #checking every element if 1
          count+=1           
          if count>=max                  #if any other consecutive of 1 found to be greater       
              max=count                  #max will be count
     else:
          count=0                        #if the queue of 1 breaks count will go to 0
print(max)


Happy coding!!
