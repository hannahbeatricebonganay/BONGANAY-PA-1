# BONGANAY-PA-1
## Problem Assignment #1 
Programming Assignment #1 
Bonganay, Hannah - 2ECE-B

### 1.) ALPHABET SOUP PROBLEM 
To create a function that takes a string and returns a string with its letters in alphabetical order.

#### ALPHABET SOUP OUTPUT
##### 1. Define the alphabet soup function
```python 
# Alphabet Soup Output only
print("ALPHABET SOUP OUTPUT")
def alphabetSoup(word):
```
##### 2. Sort the word and return result
```python 
    result = ''.join(sorted(word)) 
    return result
```
##### 3. Prints results arranged like the alphabet
```python 
print(alphabetSoup("unicorns"))  
print(alphabetSoup("rainbows"))  
```

### 2.) EMOTICON PROBLEM
To create a function that changes specific words into emoticons. Given a sentence as a string, replace the words with their corresponding emoticon.

##### 1. Define the emoticons to replace the corresponding word
```python
# Emoticon Problem
def emotify(sentence):
    emoticons = {
        "smile": ":)",
        "sad": ":((",
        "grin": ":D",
        "mad": ">:(",
    }
```
##### 2. Replace word with emoticon
```python
    for word, symbol in emoticons.items():
        sentence = sentence.replace(word, symbol)
        sentence = sentence.replace(word.lower(), symbol)
    return sentence
```
##### 3. Print Result as a sentence
```python
print(emotify("Make me smile everytime I am sad because I would like to grin all the time, it keeps me from being mad."))
```

### 3.) UNPACKING LIST PROBLEM
Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. 

#### UNPACKING OUTPUT

##### 1. Make the list itself (writeyourcodehere)
```python
# Unpacking Output Only
writeyourcodehere = [12, 13, 14, 15, 16, 17, 18, 19]
```
##### 2. Get and position elements to first, last, and middle
```python
First = writeyourcodehere[0]
Last = writeyourcodehere[-1]
Middle = writeyourcodehere[1:-1]
```
##### 3. Print the organized results 
```python
print("First:", First)
print("Middle:", Middle)
print("Last:", Last)
```
