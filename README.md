# BONGANAY-PA-1
## Problem Assignment #1 
Programming Assignment #1 
Bonganay, Hannah - 2ECE-B

### 1.) ALPHABET SOUP PROBLEM 
Create a function that takes a string and returns a string with its letters in alphabetical order.
#### ALPHABET SOUP OUTPUT ONLY
```python 
# Alphabet Soup Output only

print("ALPHABET SOUP OUTPUT ONLY")
def alphabetSoup(word):
    result = ''.join(sorted(word))
    return result

print(alphabetSoup("hannah"))  # aahhnn
print(alphabetSoup("bonganay"))  # agiorttu
```
#### ALPHABET SOUP WITH INPUT
```python 
# Alphabet Soup Input

print("ALPHABET SOUP INPUT")
def alphabetSoup(word):
    result = ''.join(sorted(word))
    return result

word = input("ENTER WORD HERE: ") # EX. ENTER WORD HERE: yes
print("ALPHABET SOUP WORD: ", alphabetSoup(word)) # ALPHABET SOUP WORD: esy
```

### 2.) EMOTICON PROBLEM
Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.

```python
def emotify(sentence):
    emoticons = {
        "smile": ":)",
        "sad": ":((",
        "grin": ":D",
        "mad": ">:(",
        "wow": ":O",
        "evil": ">:)" 
    } 
    
    for word, symbol in emoticons.items():
        sentence = sentence.replace(word, symbol)
        sentence = sentence.replace(word.lower(), symbol)
        
    return sentence

# test the function
print(emotify("Make me smile"))
print(emotify("I am sad"))
print(emotify("I am very mad"))
print(emotify("Make me grin"))
print(emotify("I'm going wow"))
print(emotify("I will be evil"))

```

### 3.) UNPACKING LIST PROBLEM
Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

#### UNPACKING OUTPUT ONLY
```python
# Unpacking Output Only
lst = [12, 13, 14, 15, 16, 17, 18, 19]

first = lst[0]
last = lst[-1]
middle = lst[1:-1]

print("first:", first)
print("middle:", middle)
print("last:", last)
```
#### UNPACKING WITH INPUT
```python
# Unpacking with Input
print("NOW INPUT YOUR OWN NUMBERS")
numbers = input("Enter numbers separated by spaces: ")

lst = [int(x) for x in numbers.split()]

first = lst[0]
last = lst[-1]
middle = lst[1:-1]

print("first:", first)
print("middle:", middle)
print("last:", last)
```
