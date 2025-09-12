Valid Palindrome
my approach is
First, declare a string variable to store input,
Then, append each character one by one as you read it.
then we have to compare both the strings if the strings are equal then we will return true else false
Variable Name: input
Type: String
Initial Value: "" (empty string)
Purpose: This will store only the alphanumeric characters from s, all in lowercase.
Loop Variable: i, type int, iterates from 0 to s.length() - 1.
s.charAt(i): The character at index i in the original string s.
The if condition checks if the character is:
An uppercase letter: 'A' <= s.charAt(i) <= 'Z'
A lowercase letter: 'a' <= s.charAt(i) <= 'z'
A digit: 0 <= s.charAt(i) - '0' <= 9
If the character is valid, it's converted to lowercase using
It is then appended to input
then we have to Declare reversed and reverse the string
Variable Name: reversed
Type: String
Initial Value: "" (empty string)
Purpose: To store the reverse of input.
Starts from the last index of input (input.length() - 1) and goes to 0.
At each iteration, it appends the character at i to reversed.
Compare input and reversed
This compares whether input and reversed are exactly the same.
If they are, the method returns true, meaning s is a palindrome.
Otherwise, it returns false.
