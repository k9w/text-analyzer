# _Text Analyzer_

#### By _**Michael Shamrell, Mohammed Nur & Jessica Baker**_ 

#### _Text Analyzer_

## Technologies Used

* GIT
* HTML
* CSS
* Bootstrap
* JavaScript
* JQuery

## Description

###Describe: wordCounter()

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

Test: "It should not count numbers as words."
Code: wordCounter("hi there 77 19");
Expected Output: 2

###Describe: numberOfOccurrencesInText()

Test: "It should return 0 occurrences of a word for an empty string."
Code:
const text = "";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 0

Test: "It should return 1 occurrence of a word when the word and the text are the same."
Code:
const text = "red";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 1

Test: "It should return 0 occurrences of a word when the word and the text are different."
Code:
const text = "red";
const word = "blue";
numberOfOccurrencesInText(word, text);
Expected Output: 0

Test: "It should return the number of occurrences of a word."
Code:
const text = "red blue red red red green";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 4

Test: "It should return a word match regardless of case."
Code:
const text = "red RED Red green Green GREEN";
const word = "Red";
numberOfOccurrencesInText(word, text);
Expected Output: 3

###Describe: boldPassage()

Test: "It should return a non-matching word in a p tag."
Code:
const word = "hello";
const text = "yo";
boldPassage(word, text);
Expected Output: "<p>yo</p>"





"Hi there hey yo hi hi yay yo whoa there whoa... yay!"

Make a list of all the words, in order.

Hi
there
hey
yo
hi
hi
yay
yo
whoa
there
whoa
yay


Lowercase all words to eliminate false different words.
Action: Change first word 'Hi' to 'hi'.

hi
there
hey
yo
hi
hi
yay
yo
whoa
there
whoa
yay


Next, from that list, make a new list of each unique word with how many times it's used.

hi      3
there   2
hey     1
yo      2
yay     2
whoa    2


Then, order this second list by most used word to least used.
If two words are used the same amount of times, list the one first that appeared first in the input string.
Action: move 'hey' from third position, to 6th (last).

hi      3
there   2
yo      2
yay     2
whoa    2
hey     1

Finally, to get the three most commonly used words from this string, remove all but the top three list items.

Even though four words were tied for second-most-used in the string, we chose the first two of them in the order the first occurence appeared in the string.

hi      3
there   2
yo      2





## Setup/Installation Requirements

* Go to _https://github.com/michaelshamrell/text-analyzer_
* Cone this repository to your desktop (or other desired location)
* Navigate to the top level of the directory called _Text Alalyzer_
* Open the index.html file in your browser
* _This has not yet been published_

## Known Bugs

* No known issues

## License

If you run into any issues or have questions, ideas or concerns contact: _<EMAIL>_

Copyright (c) _Jan 2022_ 