# Mananguit-Experiment-1
# Alphabet Soup Problem
```
#Alphabet Soup Problem
#create user input interface
string = input("Enter a word: ")
#create a function that sorts a string alphabetically
def alphabet_soup(string): 
    i = ''.join(sorted(string)) 
    #use sorted to arrange every letter of a string in a list alphabetically 
    #use join to merge all the items into a single string
    return i
j = alphabet_soup(string) #assign the function to a variable to be able to do a function call
print(j) #call and print the function
```

# Emoticon Problem
```
#Emoticon Problem
#create a dictionary that represent a word into a emote
#create another duplicate of a word incase of capitalization
emote_dictionary = { "Smile" : ":)", "smile":":)","Grin":":D","grin":":D","Sad":":((","sad" : ":((","Mad" : ">:(","mad" : ">:("}
#create user interface to enter a sentence
string = input("Enter a sentence: ")
#create a function that replace the words in the dictionary into the emote
def emotify(string):
    for word, emote in emote_dictionary.items(): #Create a for loop that goes through the combinations in the dictionary
        string = string.replace(word, emote) #replace the word with the emote
    return string
i = emotify(string) #assign the function to a variable to be able to do a function call
print(i)  #call and print the function
```
# Unpacking List Problem
```
#Unpacking List problem
#create a list named writeyourcodehere
writeyourcodehere = [] 
#code for number of items in the list
no_items = int(input("Enter number of items: ")) 
#create a for loop that lets the user enter elements in the list
for i in range(no_items):
    item = input("Enter item: ")
    writeyourcodehere.append(item) #adds the element to the list
#create a function that removes the first and last element in the list
def remove_first_last(j):
    return j[1:-1]
#call the first and last values in the list using indexing
#use the function to call numbers in between first and last
#print the values in the proper format        
print("first: ",writeyourcodehere[0],"   ","middle: ", remove_first_last(writeyourcodehere), "    last: ", writeyourcodehere[-1] )
```

