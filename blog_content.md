# About Game

Zendle is a finite word game where the only limit is the validation dictionary. The purpose of this game is to provide a stress-free version of Wordle; why stress over getting it in 6 when you can get it eventually?

\
The game starts with you, the player, submitting any valid English word of your desire (no single letter words). The last letter of that word will be the first letter of the next word for you to guess! Zendle allows you to stray away from what it wants you to do, but there would be penalties. However, you do not need to worry; anything goes as long as the word is valid!

# Changelog

Special thanks to @MintCashew, @PCAnimal\_, @horridkawa (Twitter), and friends for play-testing and making me realise what words start with X that is 6 letters long...

## alpha-1

-   Core features

## alpha-2

-   Added extra informational text and cues to make the game friendlier to learn
-   Added a list of previous answers (click the top right icon)
-   Added a method to search for previous answers
-   Given mercy on easier difficulties so that the player can make up to 3 mistakes
-   Reworked scoring system
-   Weight rare starting letters (e.g. j, x, q, z, y, etc.) to give the player a larger score if they guessed correctly
-   Set a limit on penalties to avoid obscenely large deductions (it was based on a percentage)
-   Bugfixes

## alpha-2.1

-   Fixed "Read the blog" footer not showing in mobile version
-   Removed the X...X -> X\_... format because it's not optimised for smaller screen sizes; changed it to a "previous-word, suggestion, answer-field" format
-   Added one more informational text
-   Fixed issue where the screen gets cluttered with informational text if the player answers incorrectly
-   Words now wrap the playing screen when it's long
-   Renamed versions

# Ongoing

-   Adding words that are valid but not registered in the dictionary or finding/creating a new dictionary
-   Set up a method to allow the player to suggest a word to be added in the dictionary (via Github Issues)
-   Time attack mode
-   Scoring calculation blog
-   Open source the codebase
