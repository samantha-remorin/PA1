# Programming Assignment 1
## Introduction to Python

### Description
The main goal of these set of programs is to identify the basic codes and functions in Python programming and to be able to apply the different codes and functions in creating a python program.

###  **Problems**



### NO. 1 Alphabet Soup Problem
This program creates a function that takes a string and returns a string with its letters in alphabetical order.

**Sample Output:**

- Enter a word: hello

- ehllo

**Implementation:**
-  Used Python's built-in `sorted()` function to sort characters.  
- Applied the `' '.join()` method to joined the letters with no spaces 
- Requested user input with `input()`
---

### NO.2 Emoticon Problem
This program creates a function that changes specific words into emoticons. 

**Sample Output:**
- Enter a Sentece: I am Sad

- I am :((

**Implementation:**
- Used conditional statement - `else` and `elif` statement
- Used `string.replace()`
- Requested user input with `input()`
- If condition is satisfied, it will change the word with its corresponding emoticon:
  - Smile → :)
  - Grin →  :D
  - Sad →  :((
  - Mad → >:(

---


### NO.3 Unpacking List Problem
This program unpacks the list into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then it will print all three variables. 

**Sample Output:**

- First: 1

- Middle: [2, 3, 4, 5]

- Last: 6


**Implementation:**
- Used list that stores [1,2,3,4,5,6]
- Used indexing to unpack the first and last element
- Used slicing for the middle variable 
