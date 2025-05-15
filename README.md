'''Write a program to find the entered character is a vowel or a consonent , while user input could be upper or lower case using if - elif -else'''
ch = input("Enter a char from a -> z")
if ch=='a' or ch=='i' or ch=='o' or ch=='u' :
    print(ch, "is a vowel")
if ch=='A' or ch=='E' or ch=='I' or ch=='O' or ch=='U' :    
    print(ch, "is a vowel")
else:
    print(ch, "is a consonent")
