# Compsci Lecture 9 notes

## Video 1: String Manipulations

You should be familiar with
 - str()
 - string1 + string2 - string concatenation
 - string*n - string repetiton
 - string[k]- accessing a string character by index
 - string1 < string2 - string comparison

Built-In String Functions
1.len() 
   -Returns the length, the total number of characters in the string, inlcuding white spaces 
   - Example: 
     -len("python")->6
     -len("It's done!")-> 10
     
2.min()
   - Returns the character in the string with the lowest ASCII value
   - Example:
     -min("python")->'h' 
     -min("It's done!")-> _
     
 3.max()
   - Returns the character in the string in the string with the highest ASCII value
     -max("python")->'y' 
     -max("It's done!")-> 't'
     
String Method Split()
- takes in a delimeter(separator) as the parameter
- Dividies the string into several substrings. It divides strings into parts(tokens) according to the delimiter positions in the string and returns a list of the strings(tokens).
- Delimeter is an arbitrary chosen string (usually one character) that determines the boundary of tokens
- Example:
 - >"a::b::c".split("::")-> ["a","b","c"]
 
  
