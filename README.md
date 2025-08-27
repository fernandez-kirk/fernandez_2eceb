ALPHABET SOUP PROBLEM
def alphabet_soup (text):
    return "".join(sorted(text))

print (alphabet_soup("hello"))
print (alphabet_soup("hacker"))
ehllo
acehkr

EMOTICON PROBLEM
def emotify(sentence):
    sentence = sentence.replace("smile", ":)")
    sentence = sentence.replace("grin", ":D")
    sentence = sentence.replace("sad", ":((")
    sentence = sentence.replace("mad", ">:(")
    return sentence

print(emotify("Make me smile"))
print(emotify("I am mad"))
Make me :)
I am >:(

UNPACKING LIST PROBLEM
lst = [1, 2, 3, 4, 5, 6]

first, *middle, last = lst

print("first:", first)
print("middle:", middle)
print("last:", last)
first: 1
middle: [2, 3, 4, 5]
last: 6
