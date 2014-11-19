\*\*\*\*\*week 6 labnotes

slight difference in mac and linyx the command i send you, what they did
is overrode your system and with more standard of those utilities

touch apples.txt touch oranges.txt touch bananas.md ls cat oranges.txt
man find find . -name "ora\*

dot means 'where to find something' '-name' is find the name

touch orangutangs.txlex find . -name "or*.tx*"

find \~ -name "\*.txt" http://www.gutenberg.org/ebooks/2701 press
http://www.gutenberg.org/cache/epub/2701/pg2701.txt

grep "Moby Dick" pg.2701.txt grep ... print man grep --\> to describe
what it is, it is a full text search

grep "orange"

wc pg2701.txt

cat oranges.txt grep "oranges" oranges.txt | wc 5 10 59 lines, words,
characters

ls cat oranges.txt

what we covered so far -find

-WC -grep

sort oranges.txt

sort oranges.txt | uniq -c

sort oranges.txt | uniq -c

let's new stuff SED let's subtitute, oranges to banana, for example

sed 's/day/night/' 24hr.txt

it didn't do for whole folder, so let's add '-i'

sed -i 's/day/night/' 24hr.txt cat 24hr.txt sed -i 's/night/day'
24hr.txt

sed 's/day/night/' 24hr.txt \>\> night.txt ls cat 24hr.txt

you're going to analyze gender in Moby DIck you create project directory
grab a text wget and save as and make two list of gender words make a
file named 'male"' find words that sounds male "he, his, etc.' and then
another file called 'female' and put in the words 'she, her, etc' then
we grab context and two files one with male context, and another in
female context let's rid of common English words from those files and
then we are left with non-common gender context words from sepearte
files, and count them

weasle words you take text and check for clarity copy three pieces of
writing and going to convert them in plain text then you have plain text
files "weasle"...
