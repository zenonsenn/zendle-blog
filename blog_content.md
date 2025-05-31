# About Zendle

Zendle is a finite word game where the only limit is the validation dictionary. The purpose of this game is to provide a stress-free version of Wordle; why stress over getting it in 6 when you can get it eventually?

\
The game starts with you, the player, submitting any valid English word of your desire (no single letter words). The last letter of that word will be the first letter of the next word for you to guess! Zendle allows you to stray away from what it wants you to do, but there would be penalties. However, you do not need to worry; anything goes as long as the word is valid!

# New in Zendle

## alpha-2.3

-   Added visual guide if the first letter or the length is different
-   Made cookies persistent by using local storage
-   Updated cookies messages to now show that actual data instead of cookies is now stored locally
-   Added toggle keyboard button to save screen real estate
-   Added copy answer history to clipboard and export as .txt file

# Fore*word*

There are two perspectives on this matter: those who think that playing plural form, compound words, or abbrevations is essential for this kind of game (some said it's "Scrabble with less steps") and those who think otherwise.

\
My stance is **play whatever word you think it's valid.** The premise of this game is to be _permissive_ so that you'd only think about what word fits the winning criteria and if it's spelt correctly.

\
If you think the plural form of a word shouldn't exist e.g. "environmentals", then don't play it (or bear your own risk by playing it) even if it exists in the validation dictionary. The validation dictionary's main goal is to be _permissive_ and only be there if you misspelt a word. Another example is abbreviations and numericals. They are inside the validation dictionary, but I can't guarantee its completeness. It's in your best interest to use it to your own advantage (risk if it exist or not) or not play it; **play whatever word you think it's valid.** Also, slang exists, but again, I can't guarantee its completeness.

\
If you argue about fairness and balancedness, to me, as long as the game doesn't have a global leaderboard, it shouldn't be an issue.

> It is **not** my duty to curate the dictionary, it was [wiktionary](https://www.wiktionary.org/)'s. I'm here to provide a fun interface for the dictionary.

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
-   Made mobile UI a bit more readable
-   Removed the X...X -> X\_... format because it's not optimised for smaller screen sizes; changed it to a "previous-word, suggestion, answer-field" format
-   Added one more informational text
-   Fixed issue where the screen gets cluttered with informational text if the player answers incorrectly
-   Words now wrap the playing screen when it's long
-   Renamed versions

## alpha-2.1.1

-   History is preserved until the first word played after restart
-   History is available for Lexicomaxxer

## alpha-2.1.2

-   Updated validation dictionary
-   Made the word suggestion method "smarter" by randomising the second letter so that the suggestions are more varied
-   Fixed a bug where answering corretly after an invalid word still shows the invalid word in the previous word display
-   Bugfixes

## alpha-2.1.2b

-   Fixed a bug where the word suggestion still returns words found earliest in the dictionary

## alpha-2.1.2c

-   Fixed a bug where the word suggestion returns duplicate words
-   Increased how many times the word suggestion search attempts to find words

## alpha-2.1.2c-transition

-   Made jupyter notebooks public

## alpha-2.2

-   New validation dictionary!!! I downloaded raw wiktionary data from [kaikki](https://kaikki.org/dictionary/rawdata.html) and only took the English words

## alpha-2.3

-   Added visual guide if the first letter or the length is different
-   Made cookies persistent by using local storage
-   Updated cookies messages to now show that actual data instead of cookies is now stored locally
-   Added toggle keyboard button to save screen real estate
-   Added copy answer history to clipboard and export as .txt file

# Ongoing

-   Set up a method to allow the player to suggest a word to be added in the dictionary (via Github Issues)
-   Time attack mode
-   Scoring calculation blog
-   Open source the codebase

# Contact

If you have any thoughts, suggestions, bug-reports, and alike, you can reach me out on Twitter (@zenonsenn) or Discord!

\
I may not be able to respond properly if you reach me through other means.
