# Test Analyzer (tdd) Practice

#### By Caroline Cerussi & Alex 

#### {Brief description of application}

## Technologies Used

* List all
* the major technologies
* you used in your project
* here

## Description

Describe: wordCounter ()

<-----------------this is our first test ---------------------->

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output : 1

<-----------------test 2---------------------->

Test : "It should return 2 if a passage has two words."
code:
const text = "hello";
wordCounter(text);
Expected Output: 2

<-----------------test 3---------------------->

Test: "It should return 0 for an empty string."
Code: wordCounter(" ");
Expected Output:0

<-----------------test 4---------------------->

Test: "It should return 0 for a string that is only spaces."
Code: wordCounter("           ");
Expected Output: 0

<-----------------test 5---------------------->
Test: "It should not count numbers as words."
code: wordCounter("hi there 77 19");
Expected Ouput: 2

Describe: numberOfOccurrencesInText()

<-----------------this is our first test ---------------------->

Test: "It should return 0 occurences of a word for an empty string."
code:
const text = "";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 0

<-----------------test 2---------------------->
Test: It should return 1 occurrence of a word when the word and the text are the same."
Code:
const text = "red";
const word = "red";
numberOfOccurencesInText(word, text);
Expected Output: 1

<-----------------test 3---------------------->
Test: "It should return 0 occurrences of a word when the word and the text are different."
code:
const text = "red";
const word = "blue";
numberOfOccurrencesInText(word, text);
Expected Output: 0

<-----------------test 4---------------------->
Test:"It should return the number of occurrences of a word."
Code: 
const text = "red blue red red red green";
const word = "red";
numberOfOccurrencesInText(word,text);
Expected Output: 4



{This is a detailed description of your application. Give as much detail as needed to explain what the application does as well as any other information you want users or other developers to have.}

## Setup/Installation Requirements

* This is a great place
* to list setup instructions
* in a simple
* easy-to-understand
* format

{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this application depends on? We recommend deleting the project from your desktop, re-cloning the project from GitHub, and writing down all the steps necessary to get the project working again.}

## Known Bugs

* Any known issues
* should go here

## License

{Let people know what to do if they run into any issues or have questions, ideas or concerns.  Encourage them to contact you or make a contribution to the code.}

June 7 2022 Authorized by Caroline Cerussi & Alex