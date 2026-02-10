# ai-hangman

Implementation of the Hangman word-game using Chat GPT-5.



## Overview

This is a version of the classic game of Hangman. A random word (from the game's list) is chosen. The word starts as empty underlined spaces - one space for each letter. You can guess using any of the 26 letters in the alphabet. If you guess all of the letters in a word, you'll win!



## Directions

On each turn, tap on the letter to guess. Just tap the letter - no need to hit Enter.

In each game, letters cannot be repeated. If you guess a letter in a game that has already been guessed, it is ignored.

If a guess matches one or more times in the word, it will show all instances of that letter in the word, in place.

If a guess does not match any letters, the hangman victim is built by one piece. One by one, pieces are added to the victim: the head, body, two arms, and two legs. When there have been six missing guesses, all six pieces will be shown, and the player loses.

If they guess all letters in word, the player wins.



## Details

There are over 400 different words to guess in the game. Every word has 6 to 10 letters. There are at least 5 different letters used in each word. Words are all of reasonably common use (Top 5000 used). Most are common words; there are some proper (aka capitialized) nouns.





## From Release #1 (Build 8 on 11/28/25)

* Generated basic UI.

* Contains 323 common words.



## From Release #2 (Build 14 on 2/4/26)

* Game was an annoying shade of green. Dimmed it a bit to make it easier.

* Contains 494 words (common words and proper names).

* Game had very few 9 and 10 letter-words (1 and 2 for each). Now, there are 50 9-letter words and 40 10-letter words.

* 7-letter words were the most common, by far. Added 8-letter words for a total of 87.

* About 20 duplicates or very similar words were removed.

* Added some states and capitals.

* Added some words for rare letters: J, Q, X, and Z.

* Added some words for letters that had been less used than expected: B, M, O, T, and W.
