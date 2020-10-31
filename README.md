# AganithaWritten
This repo contains the solution for the question posted by Aganitha. 

Question:
Create a reusable library that can convert a paragraph of spoken english to written english. For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively. Push your code to a public github/gitlab/bitbucket repo and submit the link here.

Solution:
Create a file Anagitha_Solution_1.ipynb
Approach:
1. Created a mappings to known words, numbers, abbreviations, etc.
2. If single letter is found, merge with the next "letter" represented as a word
3. If word representing a number, symbol, abbrivation is found replace, with actual number, symbol, abbrivation respectively
