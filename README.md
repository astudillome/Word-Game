# Word-Game
- The game consists of seven tiles that have randomly selected letters (four consonants and three vowels). 

- The user clicks on a tile to use for spelling a word, which populates a field under the available letters tiles.

- There are options for the user while creating the word. The user can undo the last move, clear the word field, reshuffle the provided letters, or enter to submit the word for scoring. There is also a reset button that clears all entries and resets the score.

- For each word that is found the user gets one point per letter, words must be at least four letters long.

- When the enter button is pressed he word s first checked to see if it is on the Words Found list, if it is then an alert stating "Word already found!" issues. is checked against a dictionary database or array. If a match is found a pop alert of "Correct!" is issued. If the word is not found a pop alert of "Word not found, try again!" is issued.

- If the word is in the dictionary then it is  added to the words found list.This will be an unordered list with text decoration removed, no bullets. Score is updated based on the word length.

- After increments of 10 words in the words found list, the user gets an alert of how many words were found and choices of whether to continue playing, reset the game or quit.

If the user chooses to continue playing the word field is cleared,  if the user chooses to reset the game is reloaded, or if the user chooses to quit an alert will state "Thanks for playing. You found ## of words and your score is ##!”
