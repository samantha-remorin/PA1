# Programming Assignment 1
## Introduction to Python

### Description:
The goal of this repository is to be able to showcase the basic codes and functions in phyton.

### Intended Learning Outcomes:
1. To identify the basic codes and functions in Python Programming
2. To be able to apply the different codes and functions in creating a Python program

###  **Problems**



### NO. 1 Alphabet Soup Problem
This program creates a function that takes a string and returns a string with its letters in alphabetical order.

**Sample Output:**

- Enter a word: hello

- ehllo

**Implementation:**
**1. Function Definition**
- `alphabetSoup(word)` → It is a function that takes a string as input and sort it in alphabetical order.
- `sorted()` → Used a built-in fuction where it breaks the word into characters and sorts them alphabetically.
-  `' '.join()` → Joins the letters back into a single word without spaces. 

**2. User Input**
-  `word = input("Enter a word: ")` → let the user type any word that they want to arrange alphabetically.

**3. Output**
-  `print(alphabetSoup(word))` → It will call the function `alphabetSoup(word)` and print the sorted output.
 
---

### NO.2 Emoticon Problem
This program creates a function that changes specific words into emoticons:
  - Smile → :)
  - Grin →  :D
  - Sad →  :((
  - Mad → >:(

**Sample Output:**
- Enter a Sentece: I am Sad

- I am :((

**Implementation:**

**1. Function Definition**
- `emotify(string)` → It is a function that converts certain words to emoticons
- ```
  if "Smile" in string or "smile" in string:
        # Replace the word with its corresponding emoticon
        return string.replace("Smile", ":)").replace("smile", ":)")
  ```
  - The function uses conditional statement `else` and `elif` statement where it would check if the certain word is in the input then it would replace the word to an emoticon. If a match is found, the word is replaced with the appropriate emoticon using the `.replace()` method.
- ```
    else:
        return string
    ```
  - If none of the conditions are satisfied, the function simply returns the original string without changes.
   
      
**2. User Input**
-  `word = input("Enter a word: ")` → let the user type any word.

**3. Output**
-  `print(emotify(text))` → It will call the function and print the sorted output.
---


### NO.3 Unpacking List Problem
This program unpacks the list into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then it will print all three variables. 

**Sample Output:**

- First: 1

- Middle: [2, 3, 4, 5]

- Last: 6

**Implementation:**

**1. Create a List**

```python
numbers = [1, 2, 3, 4, 5, 6]
```

- A list named numbers is created containing six elements.

**2. First Element**

```
print("First:", numbers[0])
```
- numbers[0] accesses the first element of the list (indexing starts at 0).
- In this case, it prints 1.

**3. Middle Elements**
```
print("Middle:", numbers[1:-1])
```
- numbers[1:-1] uses slicing to get all elements starting from index 1 up to (but not including) the last element (-1).
- This gives [2, 3, 4, 5].

**4. Last Element**
```
`print("Last:", numbers[-1])`
```
- numbers[-1] accesses the last element of the list.
- In this case, it prints 6.
