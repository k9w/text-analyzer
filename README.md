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

## Setup/Installation Requirements

* Go to _GITLINK_
* Cone this repository to your desktop (or other desired location)
* Navigate to the top level of the directory called _Text Alalyzer_
* Open the index.html file in your browser
* Or copy & paste this link in your brower: _PUBLISHEDLINK_

## Known Bugs

* No known issues

## License

If you run into any issues or have questions, ideas or concerns contact: _<EMAIL>_

Copyright (c) _Jan 2022_ 