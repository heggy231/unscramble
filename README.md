# unscramble

- Write a program to unscramble anagrams (between 5 and 7 letters) 
- Find only English dictionary word. (e.g. "leppa" would resolve to "apple", "ythitr" would resolve to "thirty", "gshinra" would resolve to "sharing"). 

- Objective:
  * use given words only once and output a dictionary word
  * assume all scrambled words will unscrambled to be dictionary word

- Anagram solver generate the permutations of given scrambled word.
  - A permutation is reordering of the letters in the word.  
  - As it generates the permutations, it will run a search algorithm
    to see if the permutation is a word in the English language (or in dic)

Limitation: 
  1. words are 5 char - 7 chars
  2. 25 letters in English (256 different character codes)

// standard char in javascript
// case insenstive and please convert to lower case letters
ex:
var scrambledWords = ["leppa", "ythitr", "gshinra", "ehlol"];
var dictionaryWords = ["apple", "thirty", "sharing", "hello"];
