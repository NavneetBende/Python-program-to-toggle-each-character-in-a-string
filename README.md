Toggle each character in a string
The string is a combination of characters, but in programing language like python, a string is an independent datatype that can be treated as character or string both because in python string of length 1 is also a string, not character. In this python program, we will check the type of string available on the basis of their case

So Today we will se program to Toggle each character in a string

Toggle each character in a String
Algorithm
Step 1:- Start.
Step 2:- Take user input as string.
Step 3:- Initialize another Empty String as String1.
Step 4:- Start iterating through string.
Step 5:- Check for the case of each iterator.
Step 6:- Change case of each iterator.
Step 7:- Concatenation each element to String1 after changing it’s case.
Step 8:- Print the String1.
Step 9:- End.
Python program to change case of the String
Run
#take user input
String = 'GuDDuBHaiyA'
#initialize other empty String
String1 = str()
#iterate through String
for i in String:
    #check the case of each iterator
    if i.isupper():
        #change it to opposit case
        i = i.lower()
        #Concat each iterator to String1
        String1 = String1 + i
    else:
        i = i.upper()
        String1 = String1 + i
#print String1
print(String + ' after changing ' + String1)
GuDDuBHaiyA after changing gUddUbhAIYa
Method 2
Program to toggle each character in a string using standard library functions is given below.

Run
 # Python program to toggle each character in a string

str = 'Root'
print("String after the characters are toggled : ",str.swapcase())
String after the characters are toggled : rOOT
