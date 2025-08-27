# BONGANAY-PA-1
## Problem Assignment #1 
Programming Assignment #1 
Bonganay, Hannah - 2ECE-B

### 1.) ALPHABET SOUP PROBLEM 
Create a function that takes a string and returns a string with its letters in alphabetical order.

#### ALPHABET SOUP OUTPUT
```python 
# Alphabet Soup Output only

print("ALPHABET SOUP OUTPUT")
# define the alphabet soup function
def alphabetSoup(word): 
    result = ''.join(sorted(word)) # sort word to alphabet 
    return result

# results arranged like the alphabet
print(alphabetSoup("unicorns"))  
print(alphabetSoup("rainbows"))  
```

### 2.) EMOTICON PROBLEM
Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.

```python
# Emoticon Problem

# define the emoticonsto replace the corresponding word
def emotify(sentence):
    emoticons = {
        "smile": ":)",
        "sad": ":((",
        "grin": ":D",
        "mad": ">:(",
    } 
# replace word with emoticon
    for word, symbol in emoticons.items():
        sentence = sentence.replace(word, symbol)
        sentence = sentence.replace(word.lower(), symbol)
        
    return sentence

# result as a sentence
print(emotify("Make me smile everytime I am sad because I would like to grin all the time, it keeps me from being mad."))
```

### 3.) UNPACKING LIST PROBLEM
Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

#### UNPACKING OUTPUT ONLY
```python
# Unpacking Output Only

# make the list itself
writeyourcodehere = [12, 13, 14, 15, 16, 17, 18, 19]

# get elements
First = writeyourcodehere[0]
Last = writeyourcodehere[-1]
Middle = writeyourcodehere[1:-1]

# results 
print("First:", First)
print("Middle:", Middle)
print("Last:", Last)
```
