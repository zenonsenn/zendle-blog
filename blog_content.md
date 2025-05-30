# About Zendle

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
-   Make mobile UI a bit more readable
-   Removed the X...X -> X\_... format because it's not optimised for smaller screen sizes; changed it to a "previous-word, suggestion, answer-field" format
-   Added one more informational text
-   Fixed issue where the screen gets cluttered with informational text if the player answers incorrectly
-   Words now wrap the playing screen when it's long
-   Renamed versions

## alpha-2.1.1

-   History is preserved until the first word played after restart
-   History is available for Lexicomaxxer

## alpha-3

-   New validation dictionary!!! I'm using enwiktionary dumps. Almost all English words should be there. If you still think a word should be accepted, reporting it will only be possible after I open-sourced the code; for now it is what it is.
-   Fixed a bug where answering corretly after an invalid word still shows the invalid word in the previous word display

# Ongoing

-   Adding words that are valid but not registered in the dictionary or finding/creating a new dictionary
-   Set up a method to allow the player to suggest a word to be added in the dictionary (via Github Issues)
-   Time attack mode
-   Scoring calculation blog
-   Open source the codebase

# Contact

If you have any thoughts, suggestions, bug-reports, and alike, you can reach me out on Twitter (@zenonsenn) or Discord!

\
I may not be able to respond properly if you reach me through other means.
