# Word Game 
This is a word spelling game where the user gets points for correctly spelling and finding words.

## Motivation
This app is inspired by the Spelling Bee game offered by the New York Times. I wanted to see how the functionality worked and if I can do a similar game. 

## Screenshots
![Image of Game]
(Images/WordGAme_app1.png)

![Image of Game Controls]
(Images/WordGAme_app2.png)

## User Stories & Wireframes
In the planning of this app I used the following:
    - Mac OS Pages for detailing user story 
    - Mac OS Numbers used to normalize dictionary data
    - List of 3000 most common used words in English https://www.ef.edu/english-resources/english-vocabulary/top-3000-words/
    - Mr. Data Convverter to convert Numbers data to Javascript array https://shancarter.github.io/mr-data-converter/
    - VS Code to develop app
    - Git and Github for version control
    - This site was built using [GitHub Pages](https://pages.github.com/).

### High-level user stories.
- The game consists of seven tiles that have randomly selected letters (five consonants and two vowels). 

- The user first clicks Begin. Then the user clicks on a tile to select it for spelling a word, which populates a field under the available letters tiles. This becomes the current word at play.

- There are options for the user while creating the word. The user can undo the a move one at a time with the Undo button. Clear the word field with the Clear button. Reshuffle the provided letters with the Shuffle button. Click Submit button to submit the word for scoring. The Begin button also a reset button that clears all entries and resets the score.

- For each word that is found the user gets one point per letter, words must be at least three letters long.

- When the Submit button is pressed he word is first checked to see if it is on the Words Found list, if it is then an alert stating "Word already found. Try again." issues. The current word is then checked against a dictionary array. If a match is found an alert of "Correct!" is issued. If the word is not found an alert of "Word not found. Try again!" is issued.

- If the word is in the dictionary then it is  added to the words found list. This will be an unordered list with no bullets. Then the Score is updated based on the word length.

- After increments of 10 words in the words found list, the user gets an alert of how many words were found and choices of whether to continue playing, reset the game or quit.

- If the user chooses to continue playing the word field is cleared,  if the user chooses to reset the game is reloaded, or if the user chooses to quit an alert will state "Thanks for playing. You found ## of words and your score is ##!”


### Image files of wireframes
![Image of Game]
(Images/MAstudillo_Proj1_Wireframe.png)

## Technologies & Code Snippets
list of technologies
screen captures of your code

## Credits
The data used in this app is provided royalty free from https://wordnet.princeton.edu. I used MDN at https://developer.mozilla.org/en-US/, Stackoverflow at https://stackoverflow.com and other online tutorials to develop and understand code.

## Future development
The app ideally should utilize an API. I would like to implement an API like Datamuse http://www.datamuse.com/api/. Datamuse searches for words based on parameters, one of which is the spelling of the word. 