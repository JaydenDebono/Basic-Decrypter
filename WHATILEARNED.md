# Basic Decryptor

# Problems I encountered
I got stuck trying to figure out how to replace individual blank spaces (underscores) with correct letters once a user 
clicked a button. Initially, I stored the hidden word display as a standard text string variable.However,trying to change a
single letter at a specific position failed.To fix this I  changed my data structure approach. Instead of a single string, 
I split the display into a List of individual strings 

Since lists can be modified at specific index locations, I used a standard "for loop". When a button is pressed, the
script then updates that exact index position inside the list of blanks. Finally, I learned how to use the ".join()" method 
to merge the list back into a clean line of text to compare the inputed word with the chosen word

I also learned how to make different assets replace different labels using the ( command = lambda ) and how to implement different
backgrounds into the interface