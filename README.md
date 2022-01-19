# wordle-letters
### Which letters are most frequent in the wordle dictionary?

This repository takes a set of 5,757 common American English letters and identifies the most common letters, as well as the most common first and last letters and the most common sequences of three letters. It's intended to help you play Wordle -- but will it make Wordle more fun?

## Data Source
The list of letters is from Donald Knuth's Stanford GraphBase, first published in 1994. The set of words used in this analysis and other interesting language processing artifacts are available [here](https://www-cs-faculty.stanford.edu/~knuth/sgb.html).

## Contents
**sgb-words.txt** is a simple text file with the word set from Stanford GraphBase.

**Letter_Freq.ipynb** is the Jupyter notebook that does the processing.

**All_Letter_Frequencies.txt** is a simple list of letters sorted by their frequency in the word list.

**First_Letter_Frequencies.txt** is a simple list of letters sorted by their frequency as the first leter in the word list.

**Last_Letter_Frequencies.txt** is a simple list of letters sorted by their frequency as the last letter in the word list.

**Three_Letter_Frequencies.txt** is a simple list of three-letter sequences, sorted by their frequency in the word list.

## Use
I'm torn about whether I'll use this or not for Wordle. Isn't the mystery more fun?

Please use these tables if they're helpful to you or extend them to heatmaps, contextual clues, etc.
