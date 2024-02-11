#This contains Assignment 3 by Adriana Medina. Reg ex. These are some notes I took to help decipher:

+ ^: Asserts the start of the string.
+ (.): Captures any single character.
+ \w*: Matches zero or more word characters (letters, digits, or underscores).
+ \1: Backreference to the first capturing group, ensuring the end of the string matches the same character as the start.
+ $: Asserts the end of the string.

#Quantifiers control how many times a pattern can match:

+ ? makes a pattern optional (i.e. it matches 0 or 1 times)
+ + lets a pattern repeat (i.e. it matches at least once)
+ * lets a pattern be optional or repeat (i.e. it matches any number of times, including 0).

#Escaping
+ to create the regular expression "\\." we need the string "\\\\."
