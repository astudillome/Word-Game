# Word-Game 

# User Story
- The game consists of seven tiles that have randomly selected letters (five consonants and two vowels). 

- The user first clicks Begin. Then the user clicks on a tile to select it for spelling a word, which populates a field under the available letters tiles. This becomes the current word at play.

- There are options for the user while creating the word. The user can undo the a move one at a time with the Undo button. Clear the word field with the Clear button. Reshuffle the provided letters with the Shuffle button. Click Submit button to submit the word for scoring. The Begin button also a reset button that clears all entries and resets the score.

- For each word that is found the user gets one point per letter, words must be at least three letters long.

- When the Submit button is pressed he word is first checked to see if it is on the Words Found list, if it is then an alert stating "Word already found. Try again." issues. The current word is then checked against a dictionary array. If a match is found an alert of "Correct!" is issued. If the word is not found an alert of "Word not found. Try again!" is issued.

- If the word is in the dictionary then it is  added to the words found list. This will be an unordered list with no bullets. Then the Score is updated based on the word length.

- After increments of 10 words in the words found list, the user gets an alert of how many words were found and choices of whether to continue playing, reset the game or quit.

- If the user chooses to continue playing the word field is cleared,  if the user chooses to reset the game is reloaded, or if the user chooses to quit an alert will state "Thanks for playing. You found ## of words and your score is ##!”
