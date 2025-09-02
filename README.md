# Biazon, Gian Alfred V. Programming Assignment #1
The repository contains solutions to identify the basic codes and functions in Python Programming, solving three different problems.



Problem #1 - ALPHABET SOUP PROBLEM 
                - to create a function that takes a string and returns a string with its letters in alphabetical order.

Code:          


                     alphabet = input("Enter a word: ") #user input a variable
                     
                     string = sorted(alphabet) #makes the string in alphabetical order
                     
                     sorted_alphabet = "''join(string) #makes the sorted strings into another string
                     
                     print (sorted_alphabet) #prints the sorted word into alphabetical order
                     

Output:                    
                    Advanced Programming = aaacddeggimmnnoprrv
                    
Analysis:
                    The most important part in this problem is the "sorted(alphabet)", because it arranges the letters of the word the user typed in alphabetical order. Then the ".join(string)" that combines the sorted letter back into another string.

                    
Problem #2 - EMOTICON PROBLEM
                - to create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin,                    sad, and mad with their corresponding emoticon.

                WORD       EMOTICON
                Smile          :)
                Grin           :D
                Sad            :((
                Mad            >:(
Code:
                emoji = {''smile":":)","grin":":D","sad":": ((","mad":">:("} #a dictionary to assign
                
                return " ". join (emoji.get(word. lower(),word)for word in sentence split()) #split the input word for word
                
                sentence = input ("Enter a sentence: ") #user input
                
                print (emotions (sentence)) #outputs the sentence with translated emoji
                
                
Output:    
                when i am sad i just smile but it makes me mad then i just grin = when i am :(( i just :) but it makes me >:( then i just :D

Analysis:
               The most important part of the code is the dictionary emoji, it stores the words and their matching emoticons. Another key part is ".join(emoji.get(word.lower(), word) for word in sentence.split, since it replaces the matching word with emojis and rebuilds the sentence for output. 
                    
Problem #3 - UNPACKING LIST PROBLEM 
                - to create a function that unpacks the list into three variables, being first, middle, and last, with middle being everything                     in between the first and last element. Then print all three variables.

Code:
             a = [1,2,3,4,5,6] #list set to the variable
             
             First = a[0] #get the first variable on the list and set to "middle"
             
             Middle = a[1:-1] #gets the second and second to the last variable on the list 
             
             Last = a[-1] # gets the last variable on the list and set to "last"
             
             print("First:", First, "Middle:", Middle, "Last:", Last) #output

             
Output:     1st = [1,2,3,4,5,6]
                    Output: first: 1       middle: [2,3,4,5]        last: 6
                    
Analysis:
            The most important part of the code is getting the index, like a[0], it gets the first value. a[1:-1] gets the values in between, and a[-1] gets the last value. Setting them a to variable namely first,middle and last. Then printing them together shows how list slicing nd indexing work to extract specific parts of a list.
                    
