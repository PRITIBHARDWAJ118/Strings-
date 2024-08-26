# Strings
## Aim: 
To study strings and it's implementation in C++.
## Theory:
String is a sequence of characters used to represent text.. C++ supports two types of strings:
1. C-Style Strings: Arrays of characters ending with a null character (\0).
 example: char str[] = "Hello, World!";
2. std::string: A more versatile and safer string class provided by the C++ Standard Library.
  example: string str = "Hello, World!";

### Various operations  in string: 
1. Concatenation: Combining two strings into one.
C-Style: strcat(dest, src);
std::string: str1 + str2;

2.Comparison: Checking if two strings are equal. 
C-Style: strcmp(str1, str2);
std::string: str1 == str2;

3.Length: Finding the number of characters in a string.
C-Style: strlen(str);
std::string: str.length();

4.Accessing Characters: Individual characters in a string can be accessed using array indexing.
C-Style: str[0];
std::string: str.at(0); or str[0];

5.Substrings: Extracting a portion of a string.
std::string: str.substr(startIndex, length);

##### Palindrome string :
   A string which is equivalent on both the sides. Example: Madam,civic etc.

  ## Output: 

  1. String Input

     ![image](https://github.com/user-attachments/assets/d578ed8e-bfc6-4337-9d59-bbe201b926c3)

2. String concatenation 

![image](https://github.com/user-attachments/assets/908bf8e7-81a7-4896-b5c7-7695fb03d12c)

3. String reverse 

![image](https://github.com/user-attachments/assets/980607f5-e93d-4e1f-9eeb-31e23fb1b0bd)

4. String palindrome

![image](https://github.com/user-attachments/assets/87c94808-87c9-4c0a-8545-048e69e2c9cf)

![image](https://github.com/user-attachments/assets/f56f761a-813f-4940-bd39-3082a4f66ee8)


5. Occurence of letter in string

   ![image](https://github.com/user-attachments/assets/14079a59-71e8-448e-82a9-d4e994d151ea)


## Conclusion :
We learnt about strings and it's implementation in C++ programming.





   
