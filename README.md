ALPHABET SOUP PROBLEM
#first step is to define the function and the function name is from the title of the problem then enclosed in the parenthesis is text which will be sorted in the next line using "".join which joins the characters then the text is sorted
def alphabet_soup (text): 
    return "".join(sorted(text))
#after completing the function, the funtion has to be called and i used print to call the text that was sorted
print (alphabet_soup("hello"))
print (alphabet_soup("hacker"))
ehllo
acehkr

EMOTICON PROBLEM
#the function emotify is defined to start and enclosed in the parenthesis is sentence because the problem needs the sentences to be replaced by emoticons
#each emoticon has their own sentence to be replaced using sentence.replace
def emotify(sentence):
    sentence = sentence.replace("smile", ":)")
    sentence = sentence.replace("grin", ":D")
    sentence = sentence.replace("sad", ":((")
    sentence = sentence.replace("mad", ">:(")
    return sentence
#after completing the function, the funtion has to be called and i used print to call the sentence that were needed to be turned into emoticon
print(emotify("Make me smile"))
print(emotify("I am mad"))
Make me :)
I am >:(

UNPACKING LIST PROBLEM
#lst was used because the problem involves list and it needs to be organized into first, middle, and the last
#the elements in the list is listed in lst
lst = [1, 2, 3, 4, 5, 6]
#this line defines the order in the list
first, *middle, last = lst
#after completing the function, the funtion has to be called and i used print to call the first, middle, and last separately
print("first:", first)
print("middle:", middle)
print("last:", last)
first: 1
middle: [2, 3, 4, 5]
last: 6
