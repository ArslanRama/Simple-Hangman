# Simple-Hangman

<!-- Note:
In this practice, you will just use "array","array methods","while","for","if else" -->



### Step 1: Create array for words
/* "await", "abstract", "boolean", "break", "byte", "case", "catch", "char", "class", "const", "continue", "debugger", "default", "delete", "do", "double", "else", "enum", "export", "extends", "false", "final", "finally", "float", "for", "function", "gogo", "if", "implements", "import", "in", "instanceof", "int", "interface", "let", "long", "native", "new", "null", "package", "protected", "private", "prototype", "public", "return", "short", "super", "static", "switch", "synchronized", "this", "throw", "throws", "true", "transient", "try", "typeof", "undefined", "var", "void", "volatile", "while", "with", "yield" */

$$ Step 2: Choose word randomly

// Step 3: Make an empty array for answer. write this "_" character as much as the number of word's letter on the screen

// Step 4: Selected word lenght will be your remainingLetters

// Step 5: Create a while loop to check if the remaining letters as positive number or not?

// Step 5.1: Show players progress like "This is the number of remaining letters 5"

//Step 5.2 : Prompt player to guess like "Guess a letter or click 'Cancel' to stop the game."

//Step 5.3 : if the prompt is null, leave the game "break"!
//Leave the game

// Step 5.4 : if the guess.lenght is not equal to 1, write "Please enter one single letter."

//Step 5.5 : Otherwise, create a loop depends on the word length and inside the loop if (the word index = guess) store letter to empty answer array! Then, decrease the remainingLetters -1
            
//Update match with guess

//End of playing loop

// Step 6: Outside of the while, show the answer!

// congratulate the player like "Good work! The right answer is " + word