# Mutations-
This Python program demonstrates how to modify an immutable string by replacing a character at a specific position.

🧠 Concept

Strings in Python cannot be changed directly.
To “mutate” a string, we can split it into two parts and insert the new character in between:

string[:position] + character + string[position + 1:]
