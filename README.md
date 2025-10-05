# Text_File_Creator
name = input("What's your name? \n")
color = input("Whats your favorite color?\n")

with open('example.txt', 'w') as file:
    file.write(f"Name: {name}\n")
    file.write(f"Favorite color: {color}\n")
