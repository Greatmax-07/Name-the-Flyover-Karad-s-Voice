Assignment 4: String Operations

Q] Develop a program to implement following operations on string :
i. Comparison of two strings
ii. Copy of one string into another
iii. Finding the length of the string
iv. Concatenating two strings into one

My ideation: 
The main theme of the program focuses on gathering public input to ensure a consensus on the name of the flyover project, avoiding any potential debates.
The program collects inputs from the public, specifically requiring Gmail IDs for submission. 
To enforce this, it compares the domain "@gmail.com" within the provided email addresses, ensuring only Gmail accounts are accepted. 

Challenge Faced:
Since "@gmail.com" appears at the end of the mail id, I had to compare two strings from the end but as far I know <string.h> functions compare strings from the start. 

Solution:
So to tackle this issue I came up with the idea of reversing the string and then comparing it. I could not find a function in C that reverses a string so with my knowledge and 
some research online I did it using iteration. I compared the reversed string with the reversed domain i.e."moc.liamg@" . 
I also made sure that there are no spaces in the id entered by the user.
